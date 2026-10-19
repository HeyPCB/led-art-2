# HeyPCB LED Art 2

More shaped LED boards inspired by films: a light bulb for Edison's thousand failures, a starfighter, a submarine, a snowman, an atom, a trophy for the underdog, each in its own colour. KiCad 10, JLCPCB-ready, CERN-OHL-S-2.0.

<p align="center"><a href="boards/angler/"><img src="boards/angler/media/top.png" width="180" alt="Angler"></a> <a href="boards/atom-age/"><img src="boards/atom-age/media/top.png" width="180" alt="Atomic"></a> <a href="boards/big-apple/"><img src="boards/big-apple/media/top.png" width="180" alt="Gravity"></a> <a href="boards/bone-skull/"><img src="boards/bone-skull/media/top.png" width="180" alt="Bones"></a> <a href="boards/bright-idea/"><img src="boards/bright-idea/media/top.png" width="180" alt="Eureka"></a> <a href="boards/champion/"><img src="boards/champion/media/top.png" width="180" alt="Champion"></a> <a href="boards/clock-face/"><img src="boards/clock-face/media/top.png" width="180" alt="Clock"></a> <a href="boards/clockwork/"><img src="boards/clockwork/media/top.png" width="180" alt="Clockwork"></a> <a href="boards/compass-rose/"><img src="boards/compass-rose/media/top.png" width="180" alt="Compass"></a> <a href="boards/cub-paw/"><img src="boards/cub-paw/media/top.png" width="180" alt="Cub"></a> <a href="boards/cyber-cat/"><img src="boards/cyber-cat/media/top.png" width="180" alt="Cyber Cat"></a> <a href="boards/decagon-dial/"><img src="boards/decagon-dial/media/top.png" width="180" alt="Dial"></a> <a href="boards/desert-cactus/"><img src="boards/desert-cactus/media/top.png" width="180" alt="High Noon"></a> <a href="boards/flash-bolt/"><img src="boards/flash-bolt/media/top.png" width="180" alt="Flash"></a> <a href="boards/frosty/"><img src="boards/frosty/media/top.png" width="180" alt="Frosty"></a> <a href="boards/fruit-bat/"><img src="boards/fruit-bat/media/top.png" width="180" alt="Fruit Bat"></a> <a href="boards/gas-giant/"><img src="boards/gas-giant/media/top.png" width="180" alt="Giant"></a> <a href="boards/giant-heart/"><img src="boards/giant-heart/media/top.png" width="180" alt="Big Heart"></a> <a href="boards/ice-gem/"><img src="boards/ice-gem/media/top.png" width="180" alt="Ice Gem"></a> <a href="boards/jack-lantern/"><img src="boards/jack-lantern/media/top.png" width="180" alt="Jack"></a> <a href="boards/jumbo-cloud/"><img src="boards/jumbo-cloud/media/top.png" width="180" alt="Sky High"></a> <a href="boards/kings-crown/"><img src="boards/kings-crown/media/top.png" width="180" alt="King"></a> <a href="boards/log-cabin/"><img src="boards/log-cabin/media/top.png" width="180" alt="Cabin"></a> <a href="boards/love-bug/"><img src="boards/love-bug/media/top.png" width="180" alt="Love Bug"></a> <a href="boards/maple-leaf/"><img src="boards/maple-leaf/media/top.png" width="180" alt="Maple"></a> <a href="boards/mech/"><img src="boards/mech/media/top.png" width="180" alt="Mech"></a> <a href="boards/mega-gear/"><img src="boards/mega-gear/media/top.png" width="180" alt="Mega Gear"></a> <a href="boards/melody/"><img src="boards/melody/media/top.png" width="180" alt="Melody"></a> <a href="boards/moth/"><img src="boards/moth/media/top.png" width="180" alt="Moth"></a> <a href="boards/mothership/"><img src="boards/mothership/media/top.png" width="180" alt="Mothership"></a> <a href="boards/night-owl/"><img src="boards/night-owl/media/top.png" width="180" alt="Night Owl"></a> <a href="boards/ninja-star/"><img src="boards/ninja-star/media/top.png" width="180" alt="Shuriken"></a> <a href="boards/nonagon/"><img src="boards/nonagon/media/top.png" width="180" alt="Nine"></a> <a href="boards/paladin/"><img src="boards/paladin/media/top.png" width="180" alt="Paladin"></a> <a href="boards/phantom/"><img src="boards/phantom/media/top.png" width="180" alt="Phantom"></a> <a href="boards/pixel-raider/"><img src="boards/pixel-raider/media/top.png" width="180" alt="Raider"></a> <a href="boards/portal-ring/"><img src="boards/portal-ring/media/top.png" width="180" alt="Portal"></a> <a href="boards/sea-turtle/"><img src="boards/sea-turtle/media/top.png" width="180" alt="Turtle"></a> <a href="boards/snow-pine/"><img src="boards/snow-pine/media/top.png" width="180" alt="Pine"></a> <a href="boards/space-helmet/"><img src="boards/space-helmet/media/top.png" width="180" alt="Astronaut"></a> <a href="boards/square-one/"><img src="boards/square-one/media/top.png" width="180" alt="Square One"></a> <a href="boards/starburst/"><img src="boards/starburst/media/top.png" width="180" alt="Starburst"></a> <a href="boards/starfighter/"><img src="boards/starfighter/media/top.png" width="180" alt="Starfighter"></a> <a href="boards/sunset-disc/"><img src="boards/sunset-disc/media/top.png" width="180" alt="Sunset"></a> <a href="boards/tiny-moon/"><img src="boards/tiny-moon/media/top.png" width="180" alt="Luna"></a> <a href="boards/vault-key/"><img src="boards/vault-key/media/top.png" width="180" alt="Vault"></a> <a href="boards/warp-ring/"><img src="boards/warp-ring/media/top.png" width="180" alt="Warp"></a> <a href="boards/yellow-sub/"><img src="boards/yellow-sub/media/top.png" width="180" alt="Submarine"></a></p>

Every board is its own silhouette and solder-mask colour, with addressable RGB LEDs (XL-2020RGBC-2812B, WS2812B-2020 class) following its outline, a CH32V003 RISC-V controller running at 5 V (so it drives the LEDs directly), a MODE button, a 1-wire SWIO programming header, a 3-pin OUT header that chains the light onto the next board, and USB-C power on a tab at the bottom. 4 layers.

| Board | Idea | Mask | Size | DRC errors / unconnected / parity |
|---|---|---|---|---|
| [Angler](boards/angler/) | a light in the deep | Black | 91.3 x 55.39 mm | 0 / 0 / 0 |
| [Atomic](boards/atom-age/) | 1950s sci-fi, three orbits | Blue | 88.01 x 84.85 mm | 0 / 0 / 0 |
| [Gravity](boards/big-apple/) | fell on the right head | Red | 82.77 x 69.86 mm | 0 / 0 / 0 |
| [Bones](boards/bone-skull/) | dead men tell no tales | White | 70 x 77.41 mm | 0 / 0 / 0 |
| [Eureka](boards/bright-idea/) | 1000 ways that did not work | Yellow | 59.97 x 88.98 mm | 0 / 0 / 0 |
| [Champion](boards/champion/) | the underdog takes the cup | Yellow | 83.19 x 91.81 mm | 0 / 0 / 0 |
| [Clock](boards/clock-face/) | 88 mph by midnight | Black | 84.01 x 91.01 mm | 0 / 0 / 0 |
| [Clockwork](boards/clockwork/) | the inventor's workshop | Yellow | 76.01 x 83.01 mm | 0 / 0 / 0 |
| [Compass](boards/compass-rose/) | a map to buried treasure | Blue | 92.01 x 99.01 mm | 0 / 0 / 0 |
| [Cub](boards/cub-paw/) | small paws, big pride | Red | 74 x 79 mm | 0 / 0 / 0 |
| [Cyber Cat](boards/cyber-cat/) | a cat from the neon future | Blue | 74 x 99.01 mm | 0 / 0 / 0 |
| [Dial](boards/decagon-dial/) | tuned to a lost frequency | White | 76.1 x 87.01 mm | 0 / 0 / 0 |
| [High Noon](boards/desert-cactus/) | a spaghetti western standoff | Green | 76.01 x 109.01 mm | 0 / 0 / 0 |
| [Flash](boards/flash-bolt/) | struck by lightning, got fast | Purple | 57.02 x 106.99 mm | 0 / 0 / 0 |
| [Frosty](boards/frosty/) | built from a snow day | White | 52.01 x 93.33 mm | 0 / 0 / 0 |
| [Fruit Bat](boards/fruit-bat/) | out of the cave at dusk | Purple | 112.01 x 74.22 mm | 0 / 0 / 0 |
| [Giant](boards/gas-giant/) | a ringed world far out | Yellow | 113.53 x 75 mm | 0 / 0 / 0 |
| [Big Heart](boards/giant-heart/) | the heart the tin man wanted | White | 94.13 x 92.06 mm | 0 / 0 / 0 |
| [Ice Gem](boards/ice-gem/) | frozen in an ice palace | Blue | 70.01 x 81.01 mm | 0 / 0 / 0 |
| [Jack](boards/jack-lantern/) | carved for a horror double bill | Yellow | 82.81 x 73.61 mm | 0 / 0 / 0 |
| [Sky High](boards/jumbo-cloud/) | a house lifted by balloons | Blue | 94.1 x 63.07 mm | 0 / 0 / 0 |
| [King](boards/kings-crown/) | lost the throne, won it back | Black | 100.01 x 68.92 mm | 0 / 0 / 0 |
| [Cabin](boards/log-cabin/) | a cabin in the woods | Red | 84.01 x 95.21 mm | 0 / 0 / 0 |
| [Love Bug](boards/love-bug/) | a small heart for a rom-com | Red | 60.25 x 61.45 mm | 0 / 0 / 0 |
| [Maple](boards/maple-leaf/) | falling in an autumn scene | Red | 74.15 x 103.99 mm | 0 / 0 / 0 |
| [Mech](boards/mech/) | rebuilt from scrap | Black | 92.01 x 90.01 mm | 0 / 0 / 0 |
| [Mega Gear](boards/mega-gear/) | twenty teeth, one mechanism | White | 92.01 x 99.01 mm | 0 / 0 / 0 |
| [Melody](boards/melody/) | the song from the musical | Black | 55.57 x 101.55 mm | 0 / 0 / 0 |
| [Moth](boards/moth/) | drawn to the light | White | 90.39 x 70.25 mm | 0 / 0 / 0 |
| [Mothership](boards/mothership/) | five tones in the sky | Purple | 112.01 x 64.95 mm | 0 / 0 / 0 |
| [Night Owl](boards/night-owl/) | carrying letters after dark | Purple | 69.99 x 105.41 mm | 0 / 0 / 0 |
| [Shuriken](boards/ninja-star/) | thrown from the shadows | Black | 92.01 x 99.01 mm | 0 / 0 / 0 |
| [Nine](boards/nonagon/) | nine sides, one puzzle | Purple | 78.8 x 84.6 mm | 0 / 0 / 0 |
| [Paladin](boards/paladin/) | dented in a hundred battles | White | 70.01 x 91.01 mm | 0 / 0 / 0 |
| [Phantom](boards/phantom/) | haunting the opera house | Black | 70.01 x 93.75 mm | 0 / 0 / 0 |
| [Raider](boards/pixel-raider/) | insert coin to continue | Purple | 104.89 x 84.29 mm | 0 / 0 / 0 |
| [Portal](boards/portal-ring/) | step through to the other side | Green | 84 x 91.01 mm | 0 / 0 / 0 |
| [Turtle](boards/sea-turtle/) | riding the current | Green | 93.97 x 71.01 mm | 0 / 0 / 0 |
| [Pine](boards/snow-pine/) | a frozen forest | White | 90.01 x 81.01 mm | 0 / 0 / 0 |
| [Astronaut](boards/space-helmet/) | failure is not an option | White | 76 x 87.56 mm | 0 / 0 / 0 |
| [Square One](boards/square-one/) | back to square one, again | Blue | 65.07 x 72.07 mm | 0 / 0 / 0 |
| [Starburst](boards/starburst/) | the opening-night flash | Yellow | 87.51 x 99.01 mm | 0 / 0 / 0 |
| [Starfighter](boards/starfighter/) | delta wing, ready to launch | White | 96.01 x 97.01 mm | 0 / 0 / 0 |
| [Sunset](boards/sunset-disc/) | riding off into it | Red | 92.01 x 99.01 mm | 0 / 0 / 0 |
| [Luna](boards/tiny-moon/) | a small moon, a big story | Purple | 60 x 67.01 mm | 0 / 0 / 0 |
| [Vault](boards/vault-key/) | the key for the heist | Blue | 112.01 x 47.01 mm | 0 / 0 / 0 |
| [Warp](boards/warp-ring/) | a gate to another galaxy | Blue | 92.01 x 99.01 mm | 0 / 0 / 0 |
| [Submarine](boards/yellow-sub/) | all the way under the sea | Yellow | 101.21 x 58.71 mm | 0 / 0 / 0 |

**Not fabricated, assembled or powered.** Every number in a board's README is measured by KiCad 10 on the files in its folder (`report.json`); parts carry LCSC numbers and were in JLCPCB's stock on the date each README gives. Order each board in its stated mask colour. Firmware is not included: these are the boards.

Designed with the HeyPCB method on KiCad 10 by heypcb-kicad's headless pipeline with Freerouting 2.4.1.

## Licence

CERN-OHL-S-2.0, © 2026 heypcb.ai. See [LICENSE](LICENSE).
