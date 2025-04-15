# 🛠️ Voron 2.4 250mm Build

Welcome to the build repository for my **Voron 2.4** CoreXY 3D printer. This project is based on the official Voron Design, using a 250mm build size and upgraded with modern components like the **BTT Manta M8P**, **CB1 compute module**, and **EZ5160 RGB stepper drivers**.

---

## 📦 Specifications

- **Model**: Voron 2.4r2  
- **Build Size**: 250 × 250 × 250 mm  
- **Frame Type**: CoreXY with stationary bed  
- **Firmware**: Klipper  
- **Controller**: BTT Manta M8P + CB1  
- **Stepper Drivers**: BTT EZ5160 RGB (SPI)  
- **Hotend**: Revo Voron / Phaetus Dragon (TBD)  
- **Bed Heater**: 250mm AC Silicone (KEENOVO)  
- **UI**: Fluidd / Mainsail (Web-based)  

---

## 🧾 Bill of Materials

> The full BOM is located here: [`docs/BOM.md`](docs/BOM.md)

---

## 🚧 Build Progress

| Task                          | Status         |
|-------------------------------|----------------|
| Frame Assembly                | 🔲 Not Started |
| Motion System (CoreXY, Z)     | 🔲 Not Started |
| Electronics & Wiring          | 🔲 Not Started |
| Klipper Firmware Setup        | 🔲 Not Started |
| Initial Motion Test           | 🔲 Not Started |
| Print Quality Tuning          | 🔲 Not Started |

---

## 📷 Photos & Updates

Coming soon…

---

## 📚 Resources

- [Voron Design Official](https://vorondesign.com/)
- [Voron GitHub](https://github.com/VoronDesign)
- [LDO Documentation](https://docs.ldomotors.com/)
- [Klipper Firmware](https://www.klipper3d.org/)
- [Voron Discord](https://discord.gg/voron)

---

## 🤝 Credits

- Voron Design Team  
- BigTreeTech for hardware  
- LDO Motors  
- Community contributors  

---

> **Note**: This is a personal build log and BOM reference. For official guides and verified parts lists, please refer to [vorondesign.com](https://vorondesign.com).

---

## 📁 Repository Structure

```bash
voron-2.4-250/
├── docs/
│   └── BOM.md              # Full bill of materials
├── firmware/
│   └── printer.cfg         # Klipper configuration (in progress)
├── stls/
│   └── ...                 # Custom/modified printable parts
├── macros/
│   └── ...                 # Klipper macros
├── config/
│   └── cb1/                # Configs for CB1 + Manta M8P
└── README.md
