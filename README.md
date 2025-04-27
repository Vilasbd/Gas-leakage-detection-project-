🚨 Gas Leakage Detection and Prevention System

🧑‍🤝‍🧑 Team Contribution
This project was initiated by Vilas D and completed with the collaboration of 6 friends from various engineering branches.
The project consists of two devices aimed at improving kitchen and household safety against gas leakages.

📸 Project Images

![image alt](https://github.com/Vilasbd/Gas-leakage-detection-project-/blob/020af5dbe7271a4b4d05353a94e742341e0a2762/Picture3.jpg)

❗ Problem Statement
Gas cylinders are widely used for cooking and industrial purposes.
However, accidental gas leakages pose serious threats like fires, explosions, property damage, and even loss of life.

Despite existing safety measures, incidents still occur due to late detection or lack of preventive actions.

This project addresses the problem by developing two devices:

Portable Gas Leak Detection Device with buzzer alert.

Automatic Gas Supply Cut-off Device for proactive prevention.

🛠️ Methodology
The project approach includes:

Gas Detection: Using MQ-2 gas sensors to monitor the environment for LPG.

Immediate Alert: Activating a buzzer for instant warnings (Portable Device).

Automatic Action: Shutting off gas supply through a solenoid valve (Cut-off Device).

Microcontroller Control: Using Arduino Nano to process signals and operate components.

Both devices are designed to be simple, cost-effective, and easy to deploy.

📦 Components Used
🔹 Portable Gas Leak Alert Device
Arduino Nano

MQ-2 Gas Sensor (LPG, Methane, Propane detection)

Buzzer (Audible Alarm)

LEDs (Optional for visual alerts)

5V Power Supply (Battery/Adapter)

Resistors and connecting wires

Compact Casing

🔹 Automatic Gas Supply Cut-off Device
Arduino Nano

MQ-2 Gas Sensor

5V Relay Module

Solenoid Valve (12V)

5V and 12V Power Supplies

Pipe fittings and casing

Resistors and connecting wires

⚙️ Solution
1. Portable Gas Leak Alert Device
Setup: Placed near the gas stove or cylinder.

Working:

MQ-2 continuously senses gas concentrations.

When gas levels exceed the threshold, Arduino triggers a buzzer alarm.

Users are immediately alerted to take manual action.

📸 Project Images

![image alt](https://github.com/Vilasbd/Gas-leakage-detection-project-/blob/a3fe398d6dc00bff25c3b5c2e019f066d88c9fef/Picture1.jpg)

2. Automatic Gas Supply Cut-off Device
Setup: Connected inline with the gas cylinder supply line.

Working:

MQ-2 sensor detects any leakage.

Arduino activates a 5V relay, powering the solenoid valve.

Gas flow is automatically shut off without requiring manual intervention.

Safety is ensured even if no one is present at home.

📸 Project Images

![image alt](https://github.com/Vilasbd/Gas-leakage-detection-project-/blob/5e89e78153fd0402fa26ec980688686541d1fd49/Picture2.jpg)

🚀 Future Implementations
📱 GSM Module Integration: SMS alerts for leakage detection.

🌐 IoT Monitoring: Wi-Fi modules (ESP8266/ESP32) for real-time mobile app notifications.

🔋 Battery Backup: To ensure functionality during power cuts.

🧪 Multi-Gas Detection: Detect additional gases like Carbon Monoxide (CO).

📊 Mobile Dashboard: Monitor leakage history, gas usage, and maintenance status.

🛡️ Self-Diagnostics: Sensor health monitoring and calibration alerts.

