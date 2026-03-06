# 🚗 Child Car Safety Monitor

A hardware-based safety system designed to **detect and alert** when a child is left unattended in a vehicle, helping to prevent heat-related accidents and child endangerment.

---

## 📌 Overview

The **Child Car Safety Monitor** is an electrical and electronics project that uses sensors and alerting mechanisms to monitor child presence inside a parked vehicle. When the system detects that a child remains in the car after the engine is turned off, it triggers an alert to notify the driver or bystanders.

This project was developed as part of an **Electrical and Electronics Laboratory course**, with the goal of building a low-cost, reliable safety solution for a critical real-world problem.

---

## 🎯 Problem Statement

Every year, children are accidentally left in hot cars, leading to tragic outcomes. This system aims to:

- Detect the presence of a child in a vehicle seat
- Monitor the vehicle's ignition/power state
- Trigger audible and/or visual alarms when a child is detected while the car is unattended
- Provide a simple, affordable, and reliable solution

---

## ✨ Features

- 🔍 **Child Detection** – Senses occupancy in child car seats
- 🚨 **Alert System** – Activates an alarm when a child is left alone in the vehicle
- ⚡ **Low Power Design** – Operates efficiently on vehicle power
- 🔧 **Modular Hardware** – Built with standard electronic components for easy assembly and maintenance
- 📋 **Simple Operation** – Requires no user intervention during normal driving

---

## 🛠️ System Components

| Component | Description |
|---|---|
| Pressure / Occupancy Sensor | Detects child presence in the seat |
| Microcontroller | Processes sensor input and manages logic |
| Buzzer / Alarm | Provides audible alert |
| LED Indicator | Visual status feedback |
| Power Supply Module | Powered via vehicle battery |

---

## 📐 System Design

The system continuously monitors two conditions:

1. **Occupancy State** – Is a child detected in the seat?
2. **Vehicle State** – Is the engine/ignition active?

**Alert Logic:**

```
IF (child_detected == TRUE) AND (ignition == OFF)
    THEN trigger_alarm()
ELSE
    standby_mode()
```

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `מערכת למניעת שכחת ילדים ברכב- פרויקט מעבדת חשמל ואלקטרוניקה 2.pptx` | Full project presentation (Hebrew) including system design, circuit diagrams, and results |
| `LICENSE` | MIT License |
| `README.md` | Project documentation (this file) |

---

## 🚀 Getting Started

### Prerequisites

To replicate this project, you will need:

- Electronic components listed in the [System Components](#-system-components) section
- A microcontroller development board (e.g., Arduino, PIC, or equivalent)
- Basic soldering equipment
- A multimeter for testing

### Setup

1. **Review the project presentation** – Open the `.pptx` file for full circuit diagrams, component specifications, and assembly instructions.
2. **Assemble the hardware** – Follow the circuit schematic provided in the presentation.
3. **Program the microcontroller** – Upload the control logic to the microcontroller unit.
4. **Test the system** – Simulate occupancy and ignition states to verify alarm behavior.
5. **Install in vehicle** – Mount sensors and connect to vehicle power following all safety guidelines.

> ⚠️ **Safety Note:** When installing any electronics in a vehicle, ensure all connections comply with your local electrical safety standards and do not interfere with the vehicle's factory systems.

---

## 📊 Project Presentation

The full project documentation, including circuit schematics, component selection rationale, testing results, and future improvements, is available in the PowerPoint presentation included in this repository:

📎 **[Project Presentation (Hebrew)](./מערכת%20למניעת%20שכחת%20ילדים%20ברכב-%20פרויקט%20מעבדת%20חשמל%20ואלקטרוניקה%202.pptx)**

---

## 🔮 Future Improvements

- 📱 **Mobile Notification** – Send SMS or push notification to the driver's phone
- 🌡️ **Temperature Monitoring** – Add a thermometer to track in-car temperature
- 📷 **Camera Integration** – Optional visual confirmation of child presence
- 🔋 **Battery Backup** – Independent power source to ensure the alarm works even after the vehicle battery disconnects
- 🌐 **IoT Connectivity** – Connect to a cloud dashboard for remote monitoring

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](./LICENSE) file for details.

---

## 👩‍💻 Author

**Yareen Hamdan**

- 🎓 Electrical and Electronics Engineering Student
- 📂 GitHub: [@YareenHamdan](https://github.com/YareenHamdan)

---

## 🙏 Acknowledgments

- Electrical and Electronics Laboratory course instructors and staff
- Fellow students for feedback and support during development

---

*Built with ❤️ to keep children safe.*
