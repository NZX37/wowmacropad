# wowmacropad

wowmacropad is a macropad with a joystick on the side, a screen and a rotary encoder as well as two status leds and is rechargeable!

<img width="965" height="637" alt="Screenshot 2026-11-09 115756" src="https://github.com/user-attachments/assets/01fe7294-d613-4a7d-a4d7-91195d37d932" />


## Features

- ESP32-S3 powered with bluetooth
- USB-C connection
- joystick placed near thumb
- rotary encoder
- Status LEDs
- tft screen

## Design files

KiCad source files are in [`kicad files/`](kicad%20files/). The schematic and board previews are shown below.

| Schematic | PCB layout | CAD |
| --- | --- | --- |
| ![Schematic](images/image1.png) | ![PCB layout](images/image2.png) | ![CAD](images/image3.png) |

## Manufacturing

Ready-to-upload Gerber and drill files are in [`Production Files/`](Production%20Files/).

For a new or modified board revision, open `breadESP32.kicad_pcb` in KiCad and regenerate fabrication outputs from that board before ordering. Check the board outline and manufacturer design rules against your chosen fabricator.

## Bill of materials

# Bill of Materials (BOM)

# Bill of Materials (BOM)

| Item | Qty | Supplier | Cost/Item (USD) | Total Cost (USD) | Link |
|---|---:|---|---:|---:|---|
| ESP32-S3-DevKit-Lipo | 2 | Mouser | $12.76 | $25.52 | [Mouser](https://www.mouser.sg/en/ProductDetail/Olimex-Ltd/ESP32-S3-DevKit-Lipo?qs=Imq1NPwxi76FgMDg4cnCbQ%3D%3D) |
| LCD TFT 1.54" ST7789 | 1 | Mouser | $23.80 | $23.80 | [Mouser](https://www.mouser.sg/en/ProductDetail/Adafruit/3787?qs=wUXugUrL1qx0Txb5soDymA%3D%3D) |
| PCB | 1 | JLCPCB | $10.00 | $10.00 | [JLCPCB](https://jlcpcb.com) |
| Rotating Encoder with Switch 20mm Plum | 2 | Mouser | $2.35 | $4.70 | [Mouser](https://www.mouser.sg/en/ProductDetail/Bourns/PEC16-2220F-N0024?qs=7YHpgRs8DgxGDEH3MBmXIA%3D%3D) |
| Estimated Total Shipping | 1 | — | — | $0.00 | — |

## Cost Summary

| Description | Amount (USD) |
|---|---:|
| Components Subtotal | $64.02 |
| Estimated Shipping | $0.00 |
| **Grand Total** | **$64.02** |

## Cost Summary

| Description | Amount (USD) |
|---|---:|
| Components Subtotal | $54.09 |
| Estimated Shipping | $8.69 |
| **Grand Total** | **$62.78** |

See [`BOM.md`](BOM.md) for the full component list. The TP4056 charger module is external and is not included in this assembly BOM. The project journal is in [`JOURNAL.md`](JOURNAL.md), and the `Firmware/` folder contains a minimal Arduino sketch.
