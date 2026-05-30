<div align="center">

```
 ███████╗██████╗ ██╗    ███╗   ███╗ ██████╗ ██╗   ██╗██╗  ██╗████████╗██╗  ██╗██╗██╗  ██╗ █████╗
 ██╔════╝██╔══██╗██║    ████╗ ████║██╔═══██╗██║   ██║██║ ██╔╝╚══██╔══╝██║  ██║██║██║ ██╔╝██╔══██╗
 ███████╗██████╔╝██║    ██╔████╔██║██║   ██║██║   ██║█████╔╝    ██║   ███████║██║█████╔╝ ███████║
 ╚════██║██╔══██╗██║    ██║╚██╔╝██║██║   ██║██║   ██║██╔═██╗    ██║   ██╔══██║██║██╔═██╗ ██╔══██║
 ███████║██║  ██║██║    ██║ ╚═╝ ██║╚██████╔╝╚██████╔╝██║  ██╗   ██║   ██║  ██║██║██║  ██╗██║  ██║
 ╚══════╝╚═╝  ╚═╝╚═╝    ╚═╝     ╚═╝ ╚═════╝  ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

### **Aluri Sri Mokthika** — Building tech that matters, for roads that are real.

---

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 👋 About Me

I'm a developer with a clear focus: **use AI and computer vision to solve problems that exist in the real world** — especially in the Indian context. My work sits at the intersection of safety-critical systems, machine learning, and full-stack development. I believe that good engineering should be grounded in the messiness of reality, not just clean benchmarks.

---

## 🧭 Core Mission

> **Making AI work for India's real-world conditions** — chaotic roads, variable lighting, and communities that need practical software, not theoretical solutions.

Two of my three projects tackle road safety with computer vision, and one builds utility software for real community management. The through-line is clear: **I build things that could genuinely be deployed and used, not just demoed.**

---

## 🚀 Projects

---

### 🚗 [Driver Drowsiness Detection](https://github.com/AluriSriMoukthika/Driver-drowsiness-detection)
`Python` `OpenCV` `dlib` `Computer Vision` `Deep Learning`

A real-time driver safety system that monitors **Eye Aspect Ratio (EAR)** and **Mouth Aspect Ratio (MAR)** to detect signs of fatigue. When drowsiness is detected, the system triggers an audio alert.

**What makes it thoughtful:**
- Separate detection pipelines for **daytime** and **nighttime** conditions
- Uses a pretrained DenseNet201 binary classification model for accuracy
- 68-point facial landmark tracking via `dlib`
- Beep alert system for real-time driver warnings
- Static image testing support alongside live camera feed

> *Road safety isn't a lab problem. This project accounts for real lighting conditions.*

---

### 🛣️ [Indian Lane Detection](https://github.com/AluriSriMoukthika/Indian-Lane-Detection)
`Python` `YOLOv5` `TensorFlow` `PyTorch` `Computer Vision`

A lane detection system **specifically designed for Indian road conditions** — where lane markings are inconsistent, traffic is dense, and lighting varies dramatically.

**What makes it India-specific:**
- Two separate trained models: one for **morning**, one for **nighttime** detection
- **YOLOv5** (`best.pt`) for real-time object detection alongside lane tracking
- Voice audio alerts: *"Keep Left"*, *"Vehicle Ahead"*, *"Vehicle on Left"*
- Video-to-frame pipeline for processing dashcam footage
- Transparent lane overlay rendering for visual clarity

> *Generic lane detection fails on Indian roads. This was built knowing that.*

---

### 🏘️ [Community Renters Management System](https://github.com/AluriSriMoukthika/Community-Renters-Management-System)
`Flask` `SQLite` `JavaScript` `HTML/CSS` `Bootstrap`

A full-stack database-driven web application for managing residential rental communities — handling renters, units, amenities, payments, and maintenance requests under one roof.

**What makes it robust:**
- 19+ SQLite triggers for data integrity enforcement
- Clubhouse booking **conflict detection** via `BEFORE INSERT` triggers
- Maintenance priority engine with automatic SQL view sorting (High → Medium → Low)
- Amenity membership validation before allowing payments
- Fully normalized database schema (3NF/BCNF)
- Role-aware UI built with Flask + Bootstrap

> *Built with the rigor of a production system, not a class project.*

---

## 🧠 What Connects It All

| Theme | Projects |
|---|---|
| 🛡️ Safety-critical AI | Drowsiness Detection, Lane Detection |
| 🇮🇳 India-specific engineering | Indian Lane Detection |
| 🌗 Real-world conditions (day/night) | Both CV projects |
| 🔊 Multimodal output (audio + visual) | Both CV projects |
| 🏗️ Full-stack + database design | Community Renters System |
| 🤝 Collaborative development | All three projects |

---

## 🛠️ Tech Stack

```
Computer Vision    →  OpenCV · dlib · YOLOv5 · facial landmarks
Deep Learning      →  TensorFlow · PyTorch · DenseNet201
Backend            →  Python · Flask · SQLite
Frontend           →  HTML · CSS · Bootstrap · JavaScript
Tools              →  Git · Google Drive (model hosting) · DB Browser for SQLite
```

---

## 📫 Connect

[![GitHub](https://img.shields.io/badge/GitHub-AluriSriMoukthika-181717?style=flat-square&logo=github)](https://github.com/AluriSriMoukthika)

---

<div align="center">
  <sub>Building at the intersection of AI, safety, and real-world impact.</sub>
</div>
