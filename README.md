# 📍 Halo Route: Smart Tourist Safety System

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Leaflet](https://img.shields.io/badge/Leaflet.js-71B045?style=for-the-badge&logo=leaflet&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### 🛡️ Your Digital Guardian for Safer Travels
**Halo Route** is an incident response and safety monitoring platform. It provides real-time tracking and automated alerts to ensure tourists stay within safe zones while exploring new locations.

---

## 📌 Key Features

* **Guardian Module:** Core safety logic developed to monitor user movement and trigger emergency protocols.
* **Live Geo-Fencing:** Dynamic "Red Zone" detection. If a user enters a high-risk area, the system alerts both the user and emergency contacts.
* **Real-Time Tracking:** Integrated interactive maps with draggable markers to simulate movement and test safety triggers.
* **Incident Response:** One-tap **Panic Button** for immediate assistance and automated location sharing.
* **Smart UI:** Responsive dashboard featuring high-contrast "Dark Mode" for better visibility during night-time travel.

---

## 🏗️ System Architecture



1.  **User Interface:** Live map display and safety dashboard.
2.  **Safety Logic (Guardian):** Processes coordinates against predefined safety parameters.
3.  **Alert System:** Triggers notifications and emergency signals when geo-fences are breached.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Grid/Flexbox Layouts)
* **Scripting:** JavaScript (ES6+)
* **Mapping API:** Leaflet.js / OpenStreetMap
* **Logic Engine:** Guardian Module (Custom JS safety algorithms)

---

---

## 📂 Project Structure

```text
├── assets/             # Images, Icons, and Stylesheets
├── js/
│   ├── guardian.js     # Core safety & alert logic
│   └── map.js          # Leaflet.js implementation
├── index.html          # Main safety dashboard
└── README.md           # Project documentation
