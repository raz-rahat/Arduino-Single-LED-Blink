# 🔴 Single LED Blink — Arduino Beginner Project

A classic **"Hello World" of embedded electronics** — this project blinks a single LED on and off every second using an Arduino (or ESP32). Perfect first step for anyone starting with microcontrollers.

## ✨ What It Does
- Turns an LED **ON** for 1 second
- Turns the LED **OFF** for 1 second
- Repeats forever in a simple loop

## 🧰 Components Required
| Component | Quantity | Notes |
|---|---|---|
| Arduino Uno / ESP32 Board | 1 | Either works |
| LED (any color) | 1 | |
| 220Ω Resistor | 1 | Recommended, protects the LED |
| Breadboard | 1 | |
| Jumper Wires (M-M) | 2 | |
| USB Cable | 1 | For power & programming |

## 🔌 Connection / Pinout

| LED Pin | Connects To |
|---|---|
| Anode (long leg, +) | Pin 13 (Arduino) / Pin 2 (ESP32) — through a 220Ω resistor |
| Cathode (short leg, −) | GND |

> 💡 **Tip:** Always connect the resistor in series with the LED to limit current and prevent burnout.
>
> ⚠️ **ESP32 Note:** Be careful with voltage on signal pins when using sensors/motors elsewhere in bigger builds — this simple LED circuit is safe on both boards.

## 📚 Required Libraries
None — this project uses only built-in Arduino functions (`pinMode`, `digitalWrite`, `delay`).

## ⚙️ Setup Instructions
1. Open `Day_1_LED_Code.ino` in Arduino IDE.
2. Wire the LED as shown in the pinout table above.
3. Select your board (**Arduino Uno** or **ESP32 Dev Module**) and the correct COM port.
4. Click **Upload**.
5. Watch the LED blink every 1 second!

## 🧠 What You'll Learn
- Digital output control with `digitalWrite()`
- Using `delay()` for timing
- Basic breadboard wiring & circuit safety (resistors, common ground)

## 📺 Credit & Links
Project by **RAZ**

- 🎥 YouTube: [Tech Raz Friday](https://www.youtube.com/@razfriday)
- 📘 Facebook: [facebook.com/mdraz1995](https://www.facebook.com/mdraz1995)

If this helped you get started with Arduino, consider subscribing for more beginner-friendly embedded projects!

## 📄 License
Free to use and modify for personal and educational projects. Credit to **Tech Raz Friday** is appreciated when sharing or republishing.
