# Smart Self-Watering Garden 🌱

An automated, off-grid soil moisture monitoring and watering system built using Arduino and ESP32.  


This project began as an idea I had in 2019 when I first began messing with Arduino. I had bought one of those cheap kits off Amazon that come with a variety of sensors, buttons, pots, etc. Mine also had a moisture sensor in it, and what started out as a few lines of code, a 5v pump and some tubing has formed into a fully modular, automated, solar powered smart garden.

## 🔧 Features
- Real-time soil moisture sensing using analog sensors
- Pump control using MOSFETs for silent, efficient switching
- Boost converter with 18650 battery pack for off-grid power
- Solar Panels to charge batteries and power components during the day
- ESP32 web interface for monitoring live readings
- REST API endpoint
- Capacitor-based power smoothing for sensor stability
- Home Assistant integration, built using mini-graph-cards

## 📐 Circuit Overview
- Arduino reads moisture sensor and controls pump
- ESP32 hosts web interface and provides `/moisture` endpoint
- Battery pack made from 18650 batteries wired in parallel, connected to boost converter tuned to 5.01v
- Capacitors added to key power lines for clean signal and voltage

## 📷 Photos
*To Do: Add images*


## 💡 Future Plans
- OTA updates for ESP32
- Manual pump control from the web UI
- Expand to multiple plant zones with additional sensors

## 📄 License
MIT License
