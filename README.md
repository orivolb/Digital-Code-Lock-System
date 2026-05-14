# Digital-Code-Lock-System

This project is a hardware-based electronic safe system, designed and implemented on a breadboard. The system validates a pre-defined security code and manages access through visual and audio feedback.

## 🛠 Features & System Logic

The system operates based on the following logic states:

* **Code Validation:** The system compares the user's input against a hard-coded security key.
* **Success State:** Upon entering the correct code, the locking mechanism is triggered to "Open."
* **Error State:** If an incorrect code is entered, a **Warning LED** lights up immediately.
* **Security Alarm:** After **3 consecutive incorrect attempts**, the system enters a lockout state:
    * A dedicated **Alarm LED** remains active.
    * A **Buzzer** sounds a continuous beep to alert for unauthorized access.

## 🔌 Hardware Implementation

* **Prototyping:** Entirely built on a **Breadboard** using discrete components and logic gates.
* **Indicators:** Integrated LEDs for real-time status feedback (Success/Fail/Alarm).
* **Audio Feedback:** Piezo Buzzer for security alerts.
* **Design Tool:** Circuit logic was verified using **NI Multisim** before physical assembly.

## 📁 Project Contents

* `Simulation/` - Multisim schematic files.
* `Docs/` - Full project report and presentation (available in Hebrew).

## 🎓 Academic Context
This project was developed as part of the Electrical Engineering curriculum, demonstrating hands-on skills in digital logic design and hardware prototyping.
