# 🌫️ Air Monitoring System (IoT + Web Dashboard)

A real-time Air Monitoring System built using **ESP8266**, **DHT22**, **MQ-2 gas sensor**, **ThingSpeak Cloud**, and a fully custom **Web Dashboard**.  
The system measures Temperature, Humidity, and Gas concentration, uploads the data to the cloud, and visualizes everything in an interactive dashboard.

---

## 🚀 Features
- Real-time Temperature, Humidity & Gas monitoring  
- Live auto-updating dashboard (JS + ThingSpeak API)  
- Embedded ThingSpeak graphs  
- Air Quality Index (AQI) score  
- Alerts + alert filtering  
- Device location map (Leaflet.js)  
- Dark/Light mode  
- Threshold settings (saved via localStorage)  
- Downloadable PDF report  
- Clean, modern UI

---

## 🛠️ Tech Stack
**Hardware:** ESP8266 NodeMCU, DHT22, MQ-2  
**Firmware:** Arduino IDE (C/C++)  
**Cloud:** ThingSpeak IoT Platform  
**Frontend:** HTML, CSS, JavaScript, Leaflet.js, jsPDF  

---

## 📡 System Workflow
1. Sensors measure Temperature, Humidity, and Gas levels  
2. ESP8266 reads sensor data and uploads it to ThingSpeak  
3. ThingSpeak stores data and generates real-time charts  
4. Web dashboard fetches data via ThingSpeak REST API  
5. Dashboard displays live readings, graphs, alerts & AQI  

---
## 📁 Project Structure
-index.html

---

## 📦 Setup Instructions
### ESP8266
1. Open Arduino IDE  
2. Install ESP8266 board package  
3. Update WiFi credentials + ThingSpeak API Write Key  
4. Upload the code  

### Web Dashboard
1. Open `index.html` in a browser  
2. Update your ThingSpeak **Channel ID** and **Read API Key** in `script.js`  
3. Dashboard starts showing real-time data  

---

## 📊 ThingSpeak Configuration
Fields used:
- **Field 1:** Temperature  
- **Field 2:** Humidity  
- **Field 3:** Gas Level  

Make sure your channel is **public or has API read key enabled**.

---

## 📍 Device Location
The dashboard shows device location using **Leaflet.js**.  
Update coordinates in `script.js` if needed.

---

## ⭐ Future Improvements
- SMS/Email alert system  
- Local data caching  
- Mobile app version  
- Expanded multi-sensor support  

---

## 👩‍💻 Developer

B.Tech CSE – IGDTUW  
-Aaisha Farheen 
-Aditi Gupta
-Anshika Sharma
-Aparna Ranjan


## 📁 Project Structure
## 📁 Project Structure
