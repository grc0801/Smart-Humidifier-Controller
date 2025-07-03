# Smart Humidifier Controller using ATmega328P – KiCAD Simulation + Arduino Firmware

This project simulates a Bluetooth-enabled smart humidifier controller using the ATmega328P microcontroller. It features both manual and wireless control using a push button and HC-05 Bluetooth module. The system also includes status LED output and MOSFET switching for humidifier control.

The schematic and PCB layout were designed using KiCAD and verified with 0 DRC errors. Firmware is written in Arduino IDE and ready for upload via ISP after fabrication.

---

## 🔧 Features

- Manual control via push button (PD2)
- Wireless Bluetooth control via HC-05 (UART)
- LED status indication
- MOSFET-based humidifier switching
- KiCAD-verified schematic and PCB layout
- Ready-to-fabricate Gerber and drill files

---

## 🛠 Tools Used

- KiCAD (Schematic + PCB Design)
- Arduino IDE (Embedded Firmware)
- Gerber Generator (Production Output)

---

## 🚀 How to Use

1. Open the schematic and layout in KiCAD.
2. Review firmware code in Arduino IDE.
3. After PCB fabrication, upload code to ATmega328P using USBasp or Arduino UNO as ISP.
4. Power the board via 5V and control the humidifier manually or over Bluetooth.

---

## ✅ Result

- Complete circuit and PCB simulated successfully in KiCAD  
- 0 DRC errors and clean layout with modular headers  
- Functional Arduino firmware tested in simulation  
- Project is ready for fabrication and deployment

---

## 💡 Future Scope

- Add automatic humidity sensing and closed-loop control
- Optimize PCB layout using SMD components
- Add OLED/LCD for system feedback
- Integrate voltage regulation and protection

---

## 🙌 Created By

**GIRIDHARAN B**
*if you find any mistake or improvement to be done, let me know*
---

**License**: MIT (for educational use)
