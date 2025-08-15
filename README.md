# Control-Four-5x7-LED-Displays-with-MAX6952-AT89C51

Easily drive four 5x7 dot Matrix LED displays using the **MAX6952** LED Driver and an **AT89C51** Microcontroller - all simulated in **Proteus**.

---

## ✨ Features

- UART-based control of up to **140 LEDs**
- Supports **ASCII characters** (built-in font in MAX6952)
- Configurable **brightness** and **scan limits**
- **Blink mode** support via register settings
- Fully tested in **Proteus 8.6 Professional**

---

## 🛠 Hardware & Software Used

- **AT89C51 Microcontroller** (8051 family)
- **MAX6952** Display Driver IC
- **Four 5x7 Common Anode LED Matrices**
- **Resistors & capacitors** for interfacing
- Simulation Tool: **Proteus 8.6 Professional**
- Language: **C** (compiled with **Keil** compiler)

---

## 📜 How It Works

1. Connect **AT89C51 → MAX6952** via **DIN, CLK, CS**
2. Configure MAX6952 registers (Normal Mode, Scan Limit, Intensity)
3. Send **ASCII codes** to display characters
4. Simulate in **Proteus** & verify output

---

## 📸 Simulation Output

![Simulation Output](simulation.png)
