# 🔧 Voron 2.4 - 250mm Build BOM

**Controller**: BTT Manta M8P + CB1  
**Drivers**: BTT EZ5160 RGB (SPI)  
**Build Volume**: 250×250×250mm

---

## 🟥 Frame & Mechanical

| Name                      | Category        | Quantity | Description                                  | Notes/Vendor                           |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|
| 2020 Aluminum Extrusion   | Frame            | Varies   | Pre-cut for 250mm Voron 2.4                  | Misumi / LDO                           |
| L-Brackets / Hidden Joints| Frame            | ~20      | Frame assembly hardware                      | AliExpress / LDO                       |
| MGN9H Rails               | Linear Motion    | 2        | Y-axis                                       | Hiwin / LDO                            |
| MGN12H Rails              | Linear Motion    | 3        | X + Z axes                                   | Hiwin / LDO                            |
| GT2 20T Pulleys           | Motion           | 6–8      | CoreXY system                                | 5mm bore                               |
| GT2 Belts (open loop)     | Motion           | ~5m      | CoreXY belt system                           | Gates or clone                         |
| GT2 Closed Loop Belts     | Z Motion         | 2–4      | For Z drives (if using belted Z)             | Match your Z setup                     |
| Idlers (Smooth/Toothed)   | Motion           | 8–10     | Bearing-supported, flanged preferred         | LDO / E3D                              |
| Z Idler Mounts            | Z Axis           | 2        | If using Z belt system                       | Printed or metal                       |
| Leadscrews (Optional)     | Z Motion         | 4        | If using leadscrews instead of belts         | Match length to frame height          |

---

## 🟩 Printed Parts

| Name                      | Category        | Quantity | Description                                  | Notes                                 |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|
| Printed Parts (Full Set)  | Structural       | ~100     | Voron official STLs (ABS/ASA recommended)    | Download from [Voron GitHub](https://github.com/VoronDesign/Voron-2) |
| Filament                  | Consumable       | ~1.5kg   | ABS / ASA preferred                          | Black + accent color                   |
| Cable Chains              | Motion           | 2        | X/Y cable management                         | IGUS style                             |

---

## 🟦 Electronics

| Name                      | Category        | Quantity | Description                                  | Notes / Vendor                         |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|
| BTT Manta M8P             | Mainboard        | 1        | Klipper-ready 32-bit control board           | Supports CB1 + SPI drivers             |
| BTT CB1                   | Compute Module   | 1        | Raspberry Pi CM4 alternative                 | Slot directly into M8P                 |
| BTT EZ5160 RGB            | Stepper Drivers  | 5–6      | SPI drivers with RGB feedback                | Z, E, X/Y (if desired)                 |
| Stepper Motors (LDO-42STH)| Motors           | 5        | NEMA 17, spec for Voron 2.4                  | LDO Motors recommended                 |
| AC Heated Bed (KEENOVO)   | Bed Heater       | 1        | 250mm silicone heater                        | With integrated thermistor             |
| SSR (Solid State Relay)   | Power Safety     | 1        | Controls AC heated bed                       | Fotek SSR-40DA or equivalent           |
| Power Supply (24V 350W+)  | Power            | 1        | For motors, hotend, fans                     | MeanWell recommended                   |
| Hotend (E3D Revo/Dragon)  | Hotend           | 1        | All-metal hotend for high-temp printing      | Revo Voron / Phaetus Dragon            |
| Thermistor or PT1000      | Sensor            | 1–2      | For hotend + bed temperature                 | Match your hotend type                 |
| Part Cooling Fan (5015)   | Fans             | 1–2      | High-flow radial blower                      | GDSTime / Delta                        |
| Hotend Fan (4010)         | Fans             | 1        | Keeps hotend cool                            | Always on                              |
| Controller Fan (4010)     | Fans             | 1        | Keeps MCU and drivers cool                   | Optional with good airflow             |
| Endstops / TAP Probe      | Sensors          | 3+       | Mechanical or inductive / Voron TAP          | TAP recommended                        |
| Display (Optional)        | Interface         | 1        | Touchscreen or OLED panel                    | Mainsail/Fluidd recommended            |

---

## 🟨 Wiring & Accessories

| Name                      | Category        | Quantity | Description                                  | Notes                                 |
|---------------------------|-----------------|----------|----------------------------------------------|----------------------------------------|
| 16–24 AWG Silicone Wire   | Wiring           | lots     | For power, sensors, fans                     | Silicone stranded recommended         |
| Ferrules & Crimp Tool     | Wiring           | 1 set    | Clean terminal ends                          | IWISS / Knipex                        |
| DIN Rails & Terminals     | Power Distribution| optional| Makes wiring neat and modular                | Optional but recommended              |
| Heat Shrink Tubing        | Electrical Safety| lots     | For insulating joints                        | Variety pack                          |
| Cable Sleeves / Looms     | Cable Management | lots     | Keeps wires tidy                             | PET braided sleeving                  |
| LED Strip (24V)           | Aesthetic        | optional | Case lighting                                | Diffused strip ideal                  |

---

## 🔧 Firmware & Software

| Tool/Software             | Purpose          | Notes                                           |
|---------------------------|------------------|--------------------------------------------------|
| Klipper                   | Motion Firmware   | Install on CB1 via FluiddPi or MainsailOS       |
| Fluidd / Mainsail         | Web Interface     | Choose your preferred Klipper UI                |
| KIAUH                     | Setup Tool        | Easy install/management of Klipper components   |
| SuperSlicer / OrcaSlicer  | Slicing Software  | Voron profiles available                        |

---

## 📦 Vendors / Kits

- **LDO Voron 2.4 Kit (250mm)** – [LDO Motors](https://www.filastruder.com/)
- **Formbot / Fysetc Kits** – budget-friendly options
- **Voron Design GitHub** – for STLs and official docs

---

> ⚠️ *Don’t forget to check the official Voron [BOM Configurator](https://vorondesign.com/) for the latest specs and tools specific to your version (v2.4r2 or later).*

