# HeyPCB LED Art 2

More shaped LED boards inspired by films: a light bulb for Edison's thousand failures, a starfighter, a submarine, a snowman, an atom, a trophy for the underdog, each in its own colour. KiCad 10, JLCPCB-ready, CERN-OHL-S-2.0.

<p align="center"><a href="boards/atom-age/"><img src="boards/atom-age/media/top.png" width="180" alt="Atomic"></a> <a href="boards/big-apple/"><img src="boards/big-apple/media/top.png" width="180" alt="Gravity"></a> <a href="boards/bright-idea/"><img src="boards/bright-idea/media/top.png" width="180" alt="Eureka"></a> <a href="boards/champion/"><img src="boards/champion/media/top.png" width="180" alt="Champion"></a> <a href="boards/desert-cactus/"><img src="boards/desert-cactus/media/top.png" width="180" alt="High Noon"></a> <a href="boards/frosty/"><img src="boards/frosty/media/top.png" width="180" alt="Frosty"></a> <a href="boards/jack-lantern/"><img src="boards/jack-lantern/media/top.png" width="180" alt="Jack"></a> <a href="boards/night-owl/"><img src="boards/night-owl/media/top.png" width="180" alt="Night Owl"></a> <a href="boards/pixel-raider/"><img src="boards/pixel-raider/media/top.png" width="180" alt="Raider"></a> <a href="boards/sea-turtle/"><img src="boards/sea-turtle/media/top.png" width="180" alt="Turtle"></a> <a href="boards/space-helmet/"><img src="boards/space-helmet/media/top.png" width="180" alt="Astronaut"></a> <a href="boards/starfighter/"><img src="boards/starfighter/media/top.png" width="180" alt="Starfighter"></a> <a href="boards/yellow-sub/"><img src="boards/yellow-sub/media/top.png" width="180" alt="Submarine"></a></p>

Every board is its own silhouette and solder-mask colour, with addressable RGB LEDs (XL-2020RGBC-2812B, WS2812B-2020 class) following its outline, a CH32V003 RISC-V controller running at 5 V (so it drives the LEDs directly), a MODE button, a 1-wire SWIO programming header, a 3-pin OUT header that chains the light onto the next board, and USB-C power on a tab at the bottom. 4 layers.

| Board | Idea | Mask | Size | DRC errors / unconnected / parity |
|---|---|---|---|---|
| [Atomic](boards/atom-age/) | 1950s sci-fi, three orbits | Blue | 88.01 x 84.85 mm | 0 / 0 / 0 |
| [Gravity](boards/big-apple/) | fell on the right head | Red | 82.77 x 69.86 mm | 0 / 0 / 0 |
| [Eureka](boards/bright-idea/) | 1000 ways that did not work | Yellow | 59.97 x 88.98 mm | 0 / 0 / 0 |
| [Champion](boards/champion/) | the underdog takes the cup | Yellow | 83.19 x 91.81 mm | 0 / 0 / 0 |
| [High Noon](boards/desert-cactus/) | a spaghetti western standoff | Green | 76.01 x 109.01 mm | 0 / 0 / 0 |
| [Frosty](boards/frosty/) | built from a snow day | White | 52.01 x 93.33 mm | 0 / 0 / 0 |
| [Jack](boards/jack-lantern/) | carved for a horror double bill | Yellow | 82.81 x 73.61 mm | 0 / 0 / 0 |
| [Night Owl](boards/night-owl/) | carrying letters after dark | Purple | 69.99 x 105.41 mm | 0 / 0 / 0 |
| [Raider](boards/pixel-raider/) | insert coin to continue | Purple | 104.89 x 84.29 mm | 0 / 0 / 0 |
| [Turtle](boards/sea-turtle/) | riding the current | Green | 93.97 x 71.01 mm | 0 / 0 / 0 |
| [Astronaut](boards/space-helmet/) | failure is not an option | White | 76 x 87.56 mm | 0 / 0 / 0 |
| [Starfighter](boards/starfighter/) | delta wing, ready to launch | White | 96.01 x 97.01 mm | 0 / 0 / 0 |
| [Submarine](boards/yellow-sub/) | all the way under the sea | Yellow | 101.21 x 58.71 mm | 0 / 0 / 0 |

**Not fabricated, assembled or powered.** Every number in a board's README is measured by KiCad 10 on the files in its folder (`report.json`); parts carry LCSC numbers and were in JLCPCB's stock on the date each README gives. Order each board in its stated mask colour. Firmware is not included: these are the boards.

Designed with the HeyPCB method on KiCad 10 by heypcb-kicad's headless pipeline with Freerouting 2.4.1.

## Licence

CERN-OHL-S-2.0, © 2026 heypcb.ai. See [LICENSE](LICENSE).
