# 🔧 Voron 2.4 - 350x350x250mm Build BOM (with HermitCrab CAN)

**Controller**: BTT Manta M8P + CB1  
**Drivers**: BTT EZ5160 RGB (SPI)  
**Toolhead**: HermitCrab CAN + Toolboard  
**Build Volume**: 350×350×250mm  
**Firmware**: Klipper  
**Estimated Total Cost**: **~$1,100 USD**

---

## 🟥 Frame & Mechanical — *~$350*

| Name                      | Category        | Quantity | Description                                  | Notes/Vendor         | Est. Cost |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------|-----------|
| 2020 Aluminum Extrusion   | Frame            | Varies   | Pre-cut for 350mm Voron 2.4                  | Misumi / LDO         | $140      |
| L-Brackets / Hidden Joints| Frame            | ~20      | Frame assembly hardware                      | AliExpress / LDO     | $20       |
| MGN9H Rails               | Linear Motion    | 2        | Y-axis                                       | Hiwin / LDO          | $30       |
| MGN12H Rails              | Linear Motion    | 3        | X + Z axes                                   | Hiwin / LDO          | $60       |
| GT2 20T Pulleys           | Motion           | 8        | CoreXY system                                | 5mm bore             | $10       |
| GT2 Belts (open loop)     | Motion           | ~6m      | CoreXY belt system                           | Gates or clone       | $20       |
| GT2 Closed Loop Belts     | Z Motion         | 4        | For Z drives (belted Z)                      | Match your Z setup   | $15       |
| Idlers (Smooth/Toothed)   | Motion           | 10       | Bearing-supported, flanged preferred         | LDO / E3D            | $25       |
| Z Idler Mounts            | Z Axis           | 2        | If using Z belt system                       | Printed or metal     | —         |
| Leadscrews (Optional)     | Z Motion         | 4        | If using leadscrews instead of belts         | Match frame height   | $30       |

---

## 🟩 Printed Parts — *~$60*

| Name                      | Category        | Quantity | Description                                  | Notes                                  | Est. Cost |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|-----------|
| Printed Parts (Full Set)  | Structural       | ~100     | Voron official STLs (ABS/ASA recommended)    | Self-printed or outsourced             | $60       |
| Filament                  | Consumable       | ~1.8kg   | ABS / ASA preferred                          | Black + accent color                   | —         |
| Cable Chains              | Motion           | 2        | X/Y cable management (350mm compatible)      | IGUS style                             | Included  |

---

## 🟦 Electronics — *~$365*

| Name                      | Category        | Quantity | Description                                  | Notes / Vendor                         | Est. Cost |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|-----------|
| BTT Manta M8P             | Mainboard        | 1        | Klipper-ready 32-bit control board           | Supports CB1 + SPI drivers             | $75       |
| BTT CB1                   | Compute Module   | 1        | Raspberry Pi CM4 alternative                 | Slot directly into M8P                 | $35       |
| BTT EZ5160 RGB            | Stepper Drivers  | 5        | SPI drivers with RGB feedback                | TMC5160 SPI                            | $70       |
| Stepper Motors (LDO-42STH)| Motors           | 5        | NEMA 17, spec for Voron 2.4                  | LDO Motors recommended                 | $80       |
| AC Heated Bed (KEENOVO)   | Bed Heater       | 1        | 350mm silicone heater                        | With integrated thermistor             | $55       |
| SSR (Solid State Relay)   | Power Safety     | 1        | Controls AC heated bed                       | Fotek SSR-40DA                         | $10       |
| Power Supply (24V 400W)   | Power            | 1        | For motors, hotend, fans                     | MeanWell preferred                     | $35       |
| Thermistors / PT1000      | Sensors           | 2        | For hotend + bed                             | NTC 100K or PT1000                     | $10       |
| Part Cooling Fan (5015)   | Fans             | 2        | High-flow radial blower                      | GDSTime / Delta                        | $15       |
| Hotend Fan (4010)         | Fans             | 1        | Keeps hotend cool                            | Always on                              | $5        |
| Controller Fan (4010)     | Fans             | 1        | Keeps MCU and drivers cool                   | Optional                               | $5        |
| Endstops / TAP Probe      | Sensors          | 3+       | Mechanical or inductive / Voron TAP          | TAP recommended                        | $20       |
| Display (Optional)        | Interface         | 1        | Touchscreen or OLED panel                    | Mainsail/Fluidd compatible             | $15       |

---

## 🦀 HermitCrab CAN System — *~$100*

| Name                      | Category        | Quantity | Description                                  | Notes                                 | Est. Cost |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|-----------|
| HermitCrab CAN Kit        | Toolhead System | 1        | Includes CAN toolboard and quick swap plate  | Biqu official                          | $85       |
| CAN Toolhead Wiring       | Wiring           | 1        | High-speed twisted pair                      | Included or custom                     | —         |
| U2C / CAN Adapter (opt.)  | CAN Interface    | 1        | If not using onboard CAN-FD on Manta         | BTT or custom                          | $15       |

---

## 🟨 Wiring & Accessories — *~$63*

| Name                      | Category        | Quantity | Description                                  | Notes                                 | Est. Cost |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|-----------|
| 16–24 AWG Silicone Wire   | Wiring           | lots     | For power, sensors, fans                     | Silicone stranded                     | $10       |
| Ferrules & Crimp Tool     | Wiring           | 1 set    | Clean terminal ends                          | IWISS / Knipex                        | $15       |
| DIN Rails & Terminals     | Power Distribution| optional| Makes wiring modular                         | Optional                              | —         |
| Heat Shrink Tubing        | Safety           | lots     | For insulating joints                        | Variety pack                          | $5        |
| Cable Sleeves / Looms     | Cable Management | lots     | Keeps wires tidy                             | PET braided sleeving                  | $10       |
| LED Strip (24V)           | Aesthetic        | optional | Case lighting                                | Optional                              | $5        |
| SD Card (16–32GB)         | Storage          | 1        | For OS / Klipper                             | MicroSD                               | $8        |

---

## 🧰 Tools & Consumables — *~$70*

| Name                      | Category        | Quantity | Description                                  | Notes                                 | Est. Cost |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|-----------|
| Soldering Kit             | Tools            | 1        | For hotend/fan terminations                  | Iron + solder                         | $25       |
| JST Kit & Crimpers        | Tools            | 1 set    | For connector building                       | JST-XH / PH                           | $20       |
| Lubricants / Tapes        | Misc             | 1 set    | Loctite, lithium grease, Kapton              | Consumables                           | $10       |
| Zip Ties / Clips          | Misc             | many     | For strain relief and bundling               | Variety pack                          | $5        |
| Heat Gun (opt.)           | Tools            | 1        | For shrink tubing                            | Optional                              | $10       |

---

## 🔧 Firmware & Software

| Tool/Software             | Purpose          | Notes                                           |
|---------------------------|------------------|--------------------------------------------------|
| Klipper                   | Motion Firmware   | Install on CB1 via FluiddPi or MainsailOS       |
| Fluidd / Mainsail         | Web Interface     | Choose your preferred Klipper UI                |
| KIAUH                     | Setup Tool        | Easy install/management of Klipper components   |
| SuperSlicer / OrcaSlicer  | Slicing Software  | Voron profiles available                        |

---

## 📦 Vendor Recommendations

- **LDO Kit (Pre-bundled)** – [Filastruder](https://www.filastruder.com/)
- **BIQU (HermitCrab)** – [BIQU Official Store](https://biqu.equipment/)
- **BTT Boards** – [BigTreeTech AliExpress](https://btt.aliexpress.com/)
- **Misc Hardware** – Amazon / AliExpress / West3D

---

> ⚠️ **Don’t forget to use the official Voron [BOM Configurator](https://vorondesign.com/) to match with the latest version-specific updates and community mods.**
