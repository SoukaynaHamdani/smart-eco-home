 
# 🏠 Smart Home Automation System

A connected, intelligent smart home prototype designed to autonomously manage water, air, and energy resources using embedded electronics, smart sensors, and a web-based control interface.

🌐 **Try the live demo**:👉  [Click here](https://lnkd.in/er8Zgthc)

---

## 🚀 Features

### 🌿 Intelligent Irrigation System
- Soil moisture sensor triggers irrigation when dryness is detected.
- Water level sensor prevents irrigation if the tank is empty.
- Real-time alerts notify the user when water is low.

### 🌬️ Automated Window Control
Window behavior based on prioritized sensor logic:
1. **Gas Detection (MQ-5):** Immediate window opening for ventilation.
2. **Rain Detection:** Auto-closing to prevent water ingress.
3. **Temperature > 30°C:** Windows open for natural cooling.

### ☀️ 100% Solar-Powered
- All systems powered by solar panels.
- Rechargeable batteries store energy for autonomous operation.

### 💡 Intelligent LED Lighting
- Remotely controlled per room via the web app.
- Energy-efficient and customizable.

---

## 📲 Web Application

### 🌐 Key Features
- Real-time temperature monitoring with live animated graphs.
- Air humidity and gas detection alerts.
- Instant weather condition updates.
- Dynamic water level display.
- LED control via an interactive room-based interface.

### 🧑‍💻 Built With
- **Frontend:** HTML / CSS / JavaScript
- **Backend:** Firebase Realtime Database
- **Hardware Communication:** ESP32 over Wi-Fi

---

## 🔧 Hardware Architecture

- **ESP32**: Main controller, handles Wi-Fi communication and sensor data.
- **Arduino Mega**: Collects and processes sensor inputs.
- **MQ-5 Sensor**: Gas detection.
- **Rain Sensor**: Detects precipitation.
- **DHT11 / DHT22**: Measures temperature and humidity.
- **Soil Moisture Sensor**: Triggers irrigation.
- **Water Level Sensor**: Prevents dry-run of pump.
- **Relay Module + Pump**: Irrigation control.
- **Solar Panels + Rechargeable Batteries**: Power supply.

---

## 📊 Real-Time Visualization

- Graphs and status indicators update live based on sensor data.
- Firebase ensures reliable, fast synchronization between hardware and the web interface.

---

## 🛠️ How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
