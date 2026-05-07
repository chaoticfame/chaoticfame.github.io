# 🌐 ADVANCED WEATHER STATION SIMULATOR // KALAPASTANGAN
> [cite_start]**Project Sector:** ADET211 [cite: 7]
> [cite_start]**Instructor:** Sir June Francisco [cite: 9]
> [cite_start]**Status:** Active Deployment [cite: 87]

[cite_start]The **Advanced Weather Station Simulator** is an Arduino-based system designed to monitor environmental conditions such as temperature, humidity, and light intensity[cite: 15]. [cite_start]The system automatically triggers hardware responses—including a fan, LED, and buzzer—based on real-time sensor telemetry to improve safety and energy efficiency[cite: 16, 17].

---

## 🛠 System Components
[cite_start]The following hardware array is utilized for the station's grid[cite: 18, 21]:

| Component | Description |
| :--- | :--- |
| **Arduino Uno** | [cite_start]Main microcontroller and processing unit [cite: 21] |
| **DHT11 Sensor** | [cite_start]Measures ambient temperature and humidity [cite: 21] |
| **LDR (Photoresistor)** | [cite_start]Detects light intensity levels [cite: 21] |
| **DC Motor (Fan)** | [cite_start]Thermal regulation; activates during high heat [cite: 21] |
| **Buzzer** | [cite_start]Acoustic alert signal for critical humidity [cite: 21] |
| **LED** | [cite_start]Visual status indicator for low-light conditions [cite: 21] |
| **NMOS Transistor** | [cite_start]Facilitates safe motor control and switching [cite: 21] |
| **9V Battery** | [cite_start]Dedicated external power source for the DC fan [cite: 21] |

---

## 🧠 Logic Matrix
[cite_start]The system executes automated protocols based on the following environment thresholds[cite: 48, 51]:

* [cite_start]**🔥 Thermal Alert:** If Temperature is $\ge 30^{\circ}C$, the **Fan** turns ON[cite: 52, 53, 54].
* [cite_start]**🌑 Night Mode:** If Light Level is $< 300$, the **LED** turns ON[cite: 55, 56].
* [cite_start]**💧 Moisture Warning:** If Humidity is $\ge 75\%$, the **Buzzer** activates[cite: 57, 58].

---

## 🚀 Setup & Deployment
[cite_start]Follow these sequences to initialize the station[cite: 27]:

1.  [cite_start]**Hardware Mapping:** Connect components to the designated Digital/Analog pins[cite: 28]:
    * [cite_start]**DHT11:** Digital Pin 7 [cite: 29, 30]
    * [cite_start]**Buzzer:** Digital Pin 8 [cite: 31, 32]
    * [cite_start]**Motor:** Digital Pin 9 (via NMOS) [cite: 33, 34]
    * [cite_start]**LED:** Digital Pin 13 [cite: 35, 36]
    * [cite_start]**LDR:** Analog Pin A0 [cite: 37, 38]
2.  [cite_start]**Interface:** Connect the Arduino Uno to your terminal via USB[cite: 39].
3.  [cite_start]**Uplink:** Upload the firmware using the **Arduino IDE**[cite: 40].
4.  [cite_start]**Telemetry:** Open the Serial Monitor and set the baud rate to **9600**[cite: 41].

---

## ⚠️ Integrity & Safety Protocols
* [cite_start]**Hydrological Hazard:** Do not expose the system to water or moisture[cite: 61].
* [cite_start]**Circuit Protection:** Verify all wiring and use the NMOS transistor for motor safety[cite: 62, 63].
* [cite_start]**Power Management:** Ensure the 9V battery is functioning for the motor load[cite: 65, 68].
* [cite_start]**Maintenance:** Keep sensors dust-free and inspect for loose connections regularly[cite: 68].

---

## 👥 Engineering Team
[cite_start]**Group:** Kalapastangan [cite: 5, 80]
[cite_start]**Section:** BSIT 2-Y2-6 [cite: 79]

* [cite_start]**Stephen Aniceto Lacson** — *Project Manager / Documenter* [cite: 81]
* [cite_start]**Anton Demeterio Elago** — *Programmer / Tester* [cite: 82]
* [cite_start]**Raven Jay Carbonell** — *Hardware Lead / Technician* [cite: 83]
* [cite_start]**Christian Michael Portugal** — *Assistant / Designer* [cite: 84]

---
[cite_start]*Based on physical prototype and testing results for educational purposes[cite: 87].*
