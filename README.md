# Eagle-System
A military simulation management system built in C++ (Eagle System)

<div align="center">

# 🦅 **Eagle System**
### Military Simulation & Command Management Platform  

![Banner](https://raw.githubusercontent.com/https://github.com/200611hacker8/EagleSystem/main/banner.png)

[![Language](https://img.shields.io/badge/language-C%2B%2B-blue.svg)]()
[![Build](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![License](https://img.shields.io/badge/license-Custom-lightgrey.svg)]()
[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)]()

</div>

---

## ⚙️ Overview

**Eagle System** is a military-grade simulation and command management platform built in C++.  
It allows managing vehicles, missions, alerts, and user roles (Admin / Officer / Viewer) in an interactive console interface with **colors**, **sound**, and **real-time alerts**.

---

## 🚀 Key Features

- 🔐 **Role-Based System**
  - Admin / Officer / Viewer permissions and dashboards.
- 🚗 **Vehicle Management**
  - Add, edit, delete, and track vehicle status.
- 🎯 **Mission Control**
  - Assign missions with coordinates and open them directly in Google Maps.
- 🔔 **Alert & Messaging System**
  - Internal communication between users (with read/unread logs).
- 📎 **Attachments**
  - Upload and share files or images via the console.
- 📊 **Reports**
  - Export data to `report.txt` or `report.json` format.
- 🎨 **Modern Console UI**
  - Colored interface, visual separators, and sound effects.
- 💾 **Persistent Data**
  - All information saved automatically in JSON files.

---

## 🗂️ File Structure

| File / Folder | Description |
|----------------|-------------|
| `Eagle system.cpp` | Main application source code |
| `users.json` | Registered users and roles |
| `vehicles.json` | Vehicle data |
| `missions.json` | Mission information with coordinates |
| `alerts.json` | Alerts and communication logs |
| `uploads/` | Folder for file/image uploads (auto-created) |

---

## 🧭 Getting Started

### 🧩 Requirements
- Windows 10 / 11  
- Visual Studio 2022 (C++17 or higher)  
- `nlohmann/json.hpp` JSON library header  

---

### 🛠️ Setup & Run

1. Clone or download the repository:
   ```bash
   git clone https://github.com/200611hacker8/EagleSystem.git
   cd EagleSystem
Open the project in Visual Studio 2022 (.sln file).

Make sure the following structure exists:

pgsql
Copy code
include/json.hpp
src/Eagle system.cpp
Build the project (Ctrl + Shift + B).

Run the system (Ctrl + F5).

👤 Default Admin Account
Username	Password	Role
admin	1234	Admin

You can register new users and assign roles at any time.

🗺️ Google Maps Integration
Each mission supports latitude and longitude coordinates.
When choosing “Open Mission on Map”, the program launches Google Maps in your browser showing the location instantly.

🔔 Alerts System
Admins can send alerts to:

All users (all)

Specific roles (role:Officer)

Individual users (user:John)

Recipients can:

View alerts

Mark them as read

Download attached files or images

All alerts are stored in alerts.json and logged for review.

📈 Reports & Statistics
Export system reports (report.txt / report.json)

Includes:

Vehicle readiness statistics

Mission summaries

User and alert logs

💡 Example Screenshot
(Optional: Add your screenshots here)

markdown
Copy code
![Main Menu](screenshots/main_menu.png)
![Mission Example](screenshots/mission_example.png)
👨‍💻 Developer Info
Developer: [shahad haasan]
📅 Year: 2025
🖥️ Built with: C++17, Visual Studio 2022

🪶 License
This project is open for educational and simulation purposes.
You may modify and distribute it with credit to the original author.

<div align="center">
🦅 Eagle System – Precision, Coordination, Control.
© 2025 All Rights Reserved.

</div> ```
