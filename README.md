# AI-Powered Smart Switchboard System

This project is an intelligent home automation system designed to modernize traditional switchboards using AI, IoT, and mobile app integration. It allows users to control and monitor devices like lights, fans, and appliances remotely, while also enabling energy optimization and automation routines.

---

##  Key Features

- **Smart Control**: Remotely toggle switches for lights, fans, and devices via a mobile app.
- **QR-Based Onboarding**: Scan QR codes to instantly link new switchboards.
- **Real-Time Monitoring**: View device status and room-wise usage updates in real time.
- **Offline Mode**: Local MQTT-based communication works even without internet.
- **Energy Analytics**: AI models predict power consumption and recommend optimizations.
- **Sensor Integration**: Automatically turn devices on/off based on motion, light, or temperature.
- **Secure Access**: Multi-user access with admin and guest permissions.
- **Voice Assistant Ready**: Future support for Google Assistant and Alexa integration.

---

##  Tech Stack

- **Microcontroller**: ESP8266 (NodeMCU)
- **Edge Processor**: Raspberry Pi 5 (with AI HAT+)
- **Mobile App**: Flutter
- **Backend**: Flask + Firebase
- **Communication**: MQTT
- **ML**: Power usage prediction, device automation, anomaly detection

---

##  System Architecture

- ESP8266 controls relays, collects sensor data, and connects via Wi-Fi.
- Raspberry Pi handles AI logic and MQTT broker services.
- Flutter app connects to Firebase and MQTT for real-time UI updates.
- ML models run locally and optionally sync with cloud (Firebase/AWS).
- Firebase Realtime DB is used for logs, access history, and user preferences.

---
##  What Makes This Unique

Unlike basic smart switchboards, this system:

- Uses **edge-based AI** on Raspberry Pi to make real-time automation decisions without needing cloud access.
- Supports **auto-detection and onboarding** of new hardware via QR codes — no hardcoded configuration.
- Is designed to run even in **offline mode** with local MQTT fallback and EEPROM buffering.
- Combines **energy optimization + security alerts** using sensor fusion and anomaly detection.
- Provides a **scalable architecture** that works across rooms, floors, and multiple users — not just a single device.

It's built for real-world deployment — not just a hobby project.

---
##  Open Source Notice

This project is currently not open-sourced due to ongoing development and potential patent application. Only the high-level architecture and design are shared publicly.

If you're interested in a technical walkthrough or demo access, please reach out via LinkedIn or email.

---

##  Contact

**Author**: Buddha Maneesh  
[Portfolio Website](https://maneeshbuddha21.github.io/)  
[LinkedIn](https://www.linkedin.com/in/buddha-maneesh-gupta/)
