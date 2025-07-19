![banner](https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=26&pause=1000&color=F7B32B&width=800&lines=Hello+World!+I'm+Viraj+%F0%9F%91%8B;Embedded+Engineer+%7C+PCB+Designer+%7C+Hardware+Nerd+%E2%9A%99%EF%B8%8F;Electronics+%7C+Automation+%7C+Open+Source+%F0%9F%94%A5;Let%E2%80%99s+Build+Something+Cool+Together+%F0%9F%94%BB)

> 🎓 Electronics & Telecommunication Engineering | 🎯 Embedded Systems & PCB Design Enthusiast
---

## 🧠 About Me
```yaml
Name: Viraj S. Patil
Role: First-Year B.Tech in Electronics & Telecommunication
Focus: Embedded Systems | Robotics | PCB Design | Automation
Technologies: C++, Embedded C, Python (Flask), Git, PlatformIO, KiCAD, VS Code
Passions: Late-night soldering, real-world prototyping, problem-solving
```

- 🔬 Building `GuardianPeak`: a mountaineering safety helmet with **fall detection, pulse sensing, storm alerts, GPS SOS** and GSM alerts.
- 🛠️ Former collaborator on large-scale **YouTube tech content**.
- 🎮 Moderator & tech admin of communities (200K+ members).
- 🎧 Music-driven coder — check my vibe at the end of this README.

---

## 🚀 Skills & Tools

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54)
![Embedded C](https://img.shields.io/badge/Embedded%20C-%2300599C?style=flat-square&logo=c)
![PlatformIO](https://img.shields.io/badge/PlatformIO-302F36?style=flat-square&logo=platformio)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-3D%20Simulation-blue?style=flat-square)
![Wokwi](https://img.shields.io/badge/Wokwi-Simulation-green?style=flat-square)
![VS Code](https://img.shields.io/badge/VS--Code-007ACC?style=flat-square&logo=visual%20studio%20code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Fusion360](https://img.shields.io/badge/Fusion%20360-ED1C24?style=flat-square&logo=autodesk&logoColor=white)
![Tinkercad](https://img.shields.io/badge/Tinkercad-FF0C00?style=flat-square&logo=tinkercad&logoColor=white)

---

## 🛠 Projects

### 🧢 GuardianPeak — Smart Mountaineering Helmet
<div align="center">
  <img src="https://media.giphy.com/media/QBd2kLB5qDmysEXre9/giphy.gif" width="300" />
</div>

| Feature | Description |
|--------|-------------|
| ⛰️ Fall Detection | MPU6050 + threshold interrupt + motion status |
| 🌩️ Storm Alert | BMP280 pressure drop detection |
| 💓 Health Monitor | MAX30102 pulse oximeter sensor |
| 🛰️ GPS Tracking | NEO-6M module with signal bar + fake coordinates |
| 📳 GSM SOS | SIM800L alerting with 5-min retry & ACK check |
| 🔋 Battery Sim | Display fake battery % + usage time |

✅ **Fully functional prototype with I2C/UART integration**, buzzers, OLED UI, and safety lockouts.


### 🧪 Embedded Python Diagnostic Simulation

- Python + Flask-based dashboard to **simulate MCU health**, I2C reads, ADC, and more.
- Inspired by STM32CubeMonitor and ESP-IDF Monitor.
- Serial-over-USB + real-time log decoding.

### 📟 Mini Apps
- **GSM Alert Console**: AT command-based SMS responder
- **PCB-2-3D Workflow**: From KiCAD schematic → PCB → FreeCAD render
- **Weather Alert Bot**: Python script using DHT11, BMP180 with Telegram alerts

---

## 🧠 Education & Achievements

- 📚 First Year B.Tech at Rajarambapu Institute of Technology (RIT)
- 🏆 Circuit Crafter Award 2023 (Inter-college tech fest)
- 🧪 Interned at PCB Prototyping Labs, Pune (2022)
- 🗣️ Guest Panel: "Teens Who Tinker", Maker Mela (Virtual)

---

## 📦 Code Stats & Contributions

![Viraj's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Vrajsp&show_icons=true&theme=radical&hide_title=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Vrajsp&layout=compact&theme=tokyonight)

---

## 🎧 Currently Vibing

[![Spotify](https://novatorem-spotify-git-main-vrajsp.vercel.app/api/spotify)](https://open.spotify.com/user/31qy4jfnvd7bppnoezvpv4dwpyjy)

---

## 🌐 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viraj-sp/)
[![GitHub](https://img.shields.io/badge/GitHub-%2312100E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vrajsp)
[![Spotify](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/user/31qy4jfnvd7bppnoezvpv4dwpyjy)

> "The only way to learn electronics is by breaking things — and fixing them even better."

---

## 🧩 Fun Extras

```cpp
// GuardianPeak Alert Routine
if (fallDetected && !ackReceived) {
  buzzer.beep();
  gsm.send("SOS from GuardianPeak. Lat: xx.xx, Lon: yy.yy");
  oled.show("Sending Emergency Alert...");
}
```

📌 Want to collaborate or feature GuardianPeak in your hackathon? **DM me!**
