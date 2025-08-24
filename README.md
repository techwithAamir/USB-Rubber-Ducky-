
# USB Rubber Ducky (Arduino HID Attack Simulation)

This project is an **Arduino-based USB Rubber Ducky clone** that emulates a keyboard (HID device) to automatically execute pre-programmed keystroke payloads. It demonstrates how USB devices can be used to simulate real-world **injection attacks** and highlights the importance of strong authentication and endpoint security.



##  Features

* Emulates a USB keyboard using **Arduino HID libraries**.
* Automatically types predefined PINs/passwords with `Enter` key presses.
* Payload script generated with **Dckuino.js**.
* Customizable payloads for different use cases.
* Works on supported Arduino boards (e.g., **Digispark ATtiny85, Arduino Leonardo**).



##  How It Works

1. The device initializes HID emulation when plugged into a computer.
2. Waits a few seconds to allow the system to be ready.
3. Sequentially types a set of PINs (`1234`, `0000`, `1111`, etc.) followed by the **Enter** key.
4. Repeats the process for multiple PIN attempts, simulating a **brute-force test**.



##  Tools & Technologies

* **Arduino IDE**
* **Keyboard.h Library**
* **Dckuino.js** (payload generator)
* **Digispark ATtiny85 / Arduino Leonardo**



##  Use Cases

* **Cybersecurity Training:** Demonstrates how HID injection attacks work.
* **Awareness:** Shows risks of weak PINs/passwords.
* **Automation:** Payloads can be modified for repetitive keystroke tasks.



 Disclaimer

This project is for **educational and ethical purposes only**. Do not use it on any device or system without explicit permission. Unauthorized use may be illegal.



