# ChillyCart (hardware)

A simple rp2350 based gameboy(color) cartdrige complete with:
- SPI SD card
- RTC 
- Accelerometer
- 8 MB of PSRAM

## ⚠️ Warning: untested design, DO NOT USE

| Parameter       | Value                 |
|-----------------|-----------------------|
| PCB Layers      | 2                     |
| Surface Finish  | ENIG(w/ gold fingers) |
| Board Thickness | 1.0mm                 |
| Meow            | prrrr                 |

## TODO: 
- *Test if the design actually works and doesn't blow up*
- Route power and PSRAM/flash data lines in a cleaner way
- Provide BOM ( and cost optimize some components )

## Soures of inspiration 
- [kicad-gamepaks](https://github.com/djedditt/kicad-gamepaks) - cartrdge connector and edge cuts
- [Croco Cartridge](https://github.com/shilga/rp2040-gameboy-cartridge) - voltage translator
- [SummerCart](https://github.com/Polprzewodnikowy/SummerCart64) - RTC and power mux