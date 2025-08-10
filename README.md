# Sorting by Height (Basic) – TIA Portal + Factory I/O

This project implements a simple object sorting system by height using TIA Portal and Factory I/O.The goal is to detect short and tall objects on a conveyor belt and route each to the correct path.

---

## 🎥 Simulation Preview
Media\Factory IO\Simulation video.mp4

---

## 🛠 Tools Used
- **TIA Portal V20**
- **WinCC Advanced in TIA V20**
- **TIA Selection Tool V2025**
- **Factory I/O 2.5.5**
- **PLC SIM** for virtual PLC simulation

---

## 📜 Scenario
1. Objects of different heights move along a conveyor belt.
2. A height sensor detects whether the object is tall or short.
3. Based on the detection:
   - Short objects are moved to the left conveyor.
   - Tall objects are moved to the right conveyor.

---

## ▶️ How to Run
1. Open the file `SRC\TIA portal V20\Sorting machine.zap20` into **TIA Portal**.
2. Open the scene file `SRC\Factory IO\Sorting by Height (Basic).factoryio` in **Factory I/O**.
3. In Factory I/O, set the Driver to **PLC SIM** and **S7-1200**.
4. Download the program to the PLC and start the PLC and HMI simulation.
5. 5.Login to HMI with this username(admin) and password(123456) and reset all alarms and start the machine.
