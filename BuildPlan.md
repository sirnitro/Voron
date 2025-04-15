# 🏗️ Voron 2.4 - 350x350x250 Build Plan

This document outlines the full project structure for building the Voron 2.4 printer with HermitCrab CAN toolhead integration. Use as a checklist or project roadmap.

---

## 📁 Project Folder: Voron 2.4 - 350x350x250 Build

---

### 📄 List: 1️⃣ Frame & Mechanical

#### ✅ Task: Cut & Prep Extrusions
- [ ] Cut 2020 extrusions to spec
- [ ] Tap M5 holes on all ends
- [ ] Label each piece (A1–I2)
- [ ] Deburr and clean

#### ✅ Task: Assemble Frame
- [ ] Install base extrusions
- [ ] Square and tighten corners
- [ ] Add vertical uprights
- [ ] Assemble top frame

#### ✅ Task: Install Linear Rails
- [ ] Mount MGN9H rails (Y-axis)
- [ ] Mount MGN12H rail (X-axis)
- [ ] Mount MGN12H rails (Z-axis)
- [ ] Check alignment and smooth travel

#### ✅ Task: Z-Axis Assembly
- [ ] Install Z idlers
- [ ] Mount Z motors
- [ ] Install Z belts or leadscrews
- [ ] Install bed frame rails (G1–G3)

---

### 📄 List: 2️⃣ Printed Parts

#### ✅ Task: Print Required Parts
- [ ] Verify part list (STLs)
- [ ] Slice with proper profiles
- [ ] Print in ABS or ASA
- [ ] Inspect and clean up parts

#### ✅ Task: Assemble Sub-Components
- [ ] Toolhead assemblies
- [ ] XY joints and carriages
- [ ] Z-idlers and motor mounts
- [ ] Cable chain mounts

---

### 📄 List: 3️⃣ Electronics & Wiring

#### ✅ Task: Mount Electronics
- [ ] Install Manta M8P
- [ ] Insert CB1
- [ ] Mount SSR
- [ ] Mount power supply
- [ ] Install DIN rails (optional)

#### ✅ Task: Wire Power System
- [ ] Connect 24V to Manta
- [ ] Wire SSR to AC bed heater
- [ ] Ground frame & verify polarity

#### ✅ Task: Wire Motors & Sensors
- [ ] Connect stepper motors
- [ ] Install and wire Z probe (TAP or inductive)
- [ ] Install endstops if used
- [ ] Wire thermistors

#### ✅ Task: CANbus & HermitCrab
- [ ] Mount HermitCrab on toolhead
- [ ] Run CAN cable to Manta
- [ ] Terminate CAN lines properly
- [ ] Configure CAN toolboard in firmware

#### ✅ Task: Fans & Accessories
- [ ] Wire part cooling fan
- [ ] Wire hotend fan (always on)
- [ ] Wire board cooling fan
- [ ] Wire LED lighting (optional)

---

### 📄 List: 4️⃣ Motion & Hotend System

#### ✅ Task: Install Stepper Drivers
- [ ] Insert EZ5160s into Manta
- [ ] Set SPI jumpers
- [ ] Verify driver orientation

#### ✅ Task: Install Toolhead
- [ ] Mount hotend to carriage
- [ ] Connect heater and thermistor
- [ ] Attach fan shroud and part fans
- [ ] Connect HermitCrab plugs

#### ✅ Task: Route Belts
- [ ] Install XY belts to pulleys
- [ ] Adjust belt tension evenly
- [ ] Secure belt ends
- [ ] Test for binding

---

### 📄 List: 5️⃣ Firmware & Software

#### ✅ Task: Flash Klipper Firmware
- [ ] Flash Manta using DFU mode
- [ ] Setup CB1 with FluiddPi or MainsailOS
- [ ] Configure CANboot for toolhead
- [ ] Flash toolboard firmware

#### ✅ Task: Configure Printer.cfg
- [ ] Define motors and drivers
- [ ] Set kinematics for CoreXY
- [ ] Set CANbus UUID for HermitCrab
- [ ] Add thermistors and fans

#### ✅ Task: Motion Tuning
- [ ] Verify movement on all axes
- [ ] Run homing test
- [ ] Tune PID for hotend and bed
- [ ] Calibrate Z-offset

---

### 📄 List: 6️⃣ Final Assembly & Testing

#### ✅ Task: Cable Management
- [ ] Sleeve and secure cables
- [ ] Use zip ties or channels
- [ ] Isolate AC and DC lines
- [ ] Label connectors

#### ✅ Task: Initial Power On
- [ ] Confirm all voltages
- [ ] Check for smoke or shorts
- [ ] Confirm Klipper connection

#### ✅ Task: Validation
- [ ] Run test cube
- [ ] Validate probe accuracy
- [ ] Check thermal graphs
- [ ] Test emergency stop

#### ✅ Task: Optional Mods
- [ ] Add LED strips
- [ ] Install touchscreen
- [ ] Add camera module
- [ ] Customize enclosure
