# Python Keylogger (Educational Demonstration)

⚠️ This project is built strictly for educational and ethical learning purposes.

It demonstrates how keyboard and mouse input can be:
- Captured (event listening)
- Logged to a file
- Programmatically controlled

Unauthorized monitoring of devices or users is illegal and unethical.

---

# 📌 Project Overview

This repository demonstrates three core system-level concepts using Python and the `pynput` library:

1. Keyboard Event Listening
2. Mouse Movement Tracking
3. Input Automation (Controller)

---

# 📂 Project Structure
Python-Keylogger/
│
├── main.py # Keyboard listener
├── listenMouse.py # Mouse movement listener
├── control.py # Mouse/Keyboard controller demo
├── Key_Codes.txt # Key reference notes
├── requirements.txt
└── README.md

---

# 🖥 1️⃣ Keyboard Listener

File: `main.py`

Logs:
- Letters
- Numbers
- Symbols
- Space (converted properly)
- Enter (new line)
- Ignores modifier keys (Shift, Ctrl, Alt)

Output is written to:  log.txt

Run:

```bash
python main.py
🖱 2️⃣ Mouse Movement Listener

File: listenMouse.py

Logs:

Mouse X position

Mouse Y position

Example Output:
Mouse position: (600, 300)
Run:
python listenMouse.py
🎮 3️⃣ Input Controller

File: control.py

Demonstrates:

Moving mouse to a specific screen coordinate

Typing text programmatically

Example:
mouse.position = (600,300)
keyboard.type("i am a key stroker")
Run:

python control.py
🛠 Installation (Windows)

1.Install Python 3.x

2.Clone the repository:

git clone https://github.com/YOUR_USERNAME/Python-Keylogger.git
cd Python-Keylogger

3.Install dependencies:

pip install -r requirements.txt
🧠 Concepts Demonstrated
Event-Driven Programming

The program waits for input events and reacts when they occur.

OS-Level Input Hooks

pynput interacts with operating system input APIs.

Automation

Simulating user input programmatically.

🔒 Cybersecurity Perspective

These techniques are used in:

Automation tools

Accessibility software

Testing frameworks

RPA (Robotic Process Automation)

Malware (if misused)

Understanding how they work helps in both development and defensive security.
