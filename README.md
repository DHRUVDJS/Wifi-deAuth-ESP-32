

---

# 🔓 ESP32 WiFi Deauther

<img src="https://deauther.com/img/logo.png" alt="Deauther Logo" width="200" />

**Scan for nearby Wi-Fi networks, identify connected clients, and send deauthentication packets to disconnect them — all using ESP32.**  
Ideal for learning, testing, and Wi-Fi security demonstrations.

---

---

## 🔑 Default WiFi Access Point

- **IP TO ACCESS THE GUI :** `192.168.4.1`
- **SSID:** `pwned`  
- **Password:** `deauther`

> Connect to this AP and access the web interface (if supported on your build).

---

## 💡 About This Project

This project brings Wi-Fi testing and deauthentication capabilities to the **ESP32** platform.  
It’s an extended version of the original ESP8266 Deauther, modified to support ESP32 boards and tailored for cybersecurity labs, education, and testing outdated or vulnerable 802.11b/g/n Wi-Fi devices.

### Features:
- Scan nearby access points and clients
- Launch deauth attacks to disconnect specific devices
- Flood area with fake access points
- CLI or Web UI (optional)
- LED status indicators (optional)

---

## ⚠️ Disclaimer

This tool is intended strictly for **educational and authorized testing** only.

**Use it only on networks you own or have explicit permission to test.**  
Check your local laws before running any form of wireless attack.  
We are not responsible for misuse or illegal activities conducted with this firmware.

---

## 🔧 Getting Started

Make sure you have:
- ESP32 board
- Arduino IDE / PlatformIO
- Installed required libraries (like `WiFi.h`, `ESPAsyncWebServer`, etc.)

---

#Let me know if you'd like this saved as a `README.md` file, or if you're also making hardware (like a 3D-printed case or custom PCB), I can add that section too!
