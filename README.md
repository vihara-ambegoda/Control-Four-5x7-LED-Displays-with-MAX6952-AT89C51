# Control-Four-5x7-LED-Displays-with-MAX6952-AT89C51

Easily drive four 5x7 dot matrix LED displays using the **MAX6952** LED driver and an **AT89C51** microcontroller - all simulated in **Proteus**.

---

## ✨ Features

- UART-based control of up to **140 LEDs**
- Supports **ASCII characters** (built-in font in MAX6952)
- Configurable **brightness** and **scan limits**
- **Blink mode** support via register settings
- Fully tested in **Proteus 8.6 Professional**

---

## 🛠 Hardware Used

- **AT89C51 Microcontroller** (8051 family)
- **MAX6952** Display Driver IC
- **Four 5x7 Common Anode LED Matrices**
- **Resistors & capacitors** for interfacing

---

## 📜 How It Works

1. Connect **AT89C51 → MAX6952** via **DIN, CLK, CS**
2. Configure MAX6952 registers (normal mode, scan limit, intensity)
3. Send **ASCII codes** to display characters
4. Simulate in **Proteus** & verify output

---

## 💻 Software

- **Language**: C (compiled with **Keil** compiler)
- **Flow**: Initialize → Configure Registers → Send Data → Loop
- **Example output**: Displays `S L I T` across 4 matrices

---

## 📸 Simulation Output

![Simulation Output](simulation.png)
