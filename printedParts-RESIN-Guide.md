# 🎨 Voron 2.4 Printed Parts – Two-Color Material Breakdown

This list details which parts of your Voron 2.4 (350x350x250) build can be printed using **Siraya Tech Blu** resin (🩵 Accent Color) and which must be printed using **ABS or ASA filament** (⚫ Primary Color) for strength, heat resistance, and durability.

---

## 🧱 Material Guidelines

| Material           | Recommended For                             |
|--------------------|----------------------------------------------|
| ⚫ ABS / ASA        | Frame, toolhead, load-bearing & heated parts |
| 🩵 Siraya Tech Blu  | Panels, covers, cosmetic & light-load parts  |

> ⚠️ Do **not** use resin for motor mounts, gantry parts, or structural assemblies under tension or heat.

---

## 🧩 Part Breakdown by Group

### 🔧 Frame & Tools

| Part Name                             | Material     | Color |
|--------------------------------------|--------------|--------|
| rail_installation_guide_center_x2    | Resin         | 🩵     |

---

### ⚙️ Z Drive Assembly

| Part Name(s)                                                               | Material | Color |
|----------------------------------------------------------------------------|----------|--------|
| z_drive_main_*, z_motor_mount_*, z_drive_retainer_*                        | ABS/ASA  | ⚫     |
| [a]_belt_tensioner_a_x2, [a]_belt_tensioner_b_x2                           | Resin    | 🩵     |

---

### 🛞 Z Idlers

| Part Name(s)                                               | Material | Color |
|------------------------------------------------------------|----------|--------|
| z_tensioner_bracket_a_x2, z_tensioner_bracket_b_x2         | ABS/ASA  | ⚫     |
| [a]_z_tensioner_x4_6mm or [a]_z_tensioner_x4_9mm           | Resin    | 🩵     |

---

### 📏 Z Endstop

| Part Name             | Material | Color |
|----------------------|----------|--------|
| nozzle_probe.stl     | ABS/ASA  | ⚫     |

---

### 🛠️ AB Drives

| Part Name(s)                                       | Material | Color |
|----------------------------------------------------|----------|--------|
| ab_motor_mount_*, ab_idler_mount_*                 | ABS/ASA  | ⚫     |
| ab_belt_clamp_a_x2, ab_belt_clamp_b_x2             | ABS/ASA  | ⚫     |

---

### 🔩 XY Joints

| Part Name(s)                   | Material | Color |
|--------------------------------|----------|--------|
| [a]_xy_joint_left/right        | Resin    | 🩵     |

---

### 🖱️ X Carriage

| Part Name(s)              | Material | Color |
|---------------------------|----------|--------|
| x_carriage, x_carriage_back | ABS/ASA  | ⚫     |

---

### 🔧 Toolhead (Afterburner / Stealthburner)

| Part Name(s)                  | Material | Color |
|-------------------------------|----------|--------|
| toolhead_body, toolhead_fan_mount | ABS/ASA | ⚫     |
| [a]_toolhead_front            | Resin    | 🩵     |

---

### 🧱 Skirts & Panels

| Part Name(s)                                                    | Material | Color |
|------------------------------------------------------------------|----------|--------|
| [a]_front_skirt, [a]_rear_skirt, [a]_side_skirt_left/right       | Resin    | 🩵     |

---

### 🔌 Electronics Mounts

| Part Name(s)                      | Material | Color |
|----------------------------------|----------|--------|
| rpi_mount, manta_mount, din_clip | ABS/ASA  | ⚫     |

---

### 📦 Miscellaneous

| Part Name(s)                                   | Material | Color |
|------------------------------------------------|----------|--------|
| cable_chain_mount_x2, led_mount_x2, fan_grill_x2 | Resin    | 🩵     |

---

## ✅ Safe to Print in Resin (🩵 Siraya Tech Blu)

- [ ] Skirts & Panels  
- [ ] Toolhead front cover  
- [ ] XY Joints  
- [ ] Rail guides  
- [ ] LED/fan covers and light mounts  
- [ ] Belt tensioner caps  
- [ ] Chain mounts and low-stress accessories

## ❌ Must Use ABS/ASA (⚫ Critical Structural Parts)

- [ ] AB Drive Mounts  
- [ ] Z Drive Mounts  
- [ ] X Carriage  
- [ ] Belt Clamps  
- [ ] Z Idler Brackets  
- [ ] All motor mounts  
- [ ] Any part under constant tension, heat, or load

---

## 📦 STL Sources

- 🔗 [Voron 2.4 STLs](https://github.com/VoronDesign/Voron-2/tree/V2.4/STLs)
- 🔗 [Voron Afterburner Toolhead](https://github.com/VoronDesign/Voron-Afterburner)
