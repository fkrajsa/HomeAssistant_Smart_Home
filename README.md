# Smart Home Dashboard – Home Assistant Project

This project documents my custom **Home Assistant setup** running on an older **Lenovo Android tablet** and **RPI 3**, mounted on the wall as a smart home control panel. The setup is designed to be functional, minimalistic, and energy-efficient.

---

## 🧠 Overview

* **System:** Home Assistant (core installation)
* **Frontend:** Fully Kiosk Browser (running in kiosk mode on tablet)
* **Device:** Lenovo TB-X304F (10-inch tablet)
* **Mount:** Custom 3D-printed wall bracket (designed and printed by me)
* **Network:** Connected via Wi-Fi to local Home Assistant server running on RPI 3

---

## ⚙️ Features

* **Smart Dashboard:** Custom Lovelace dashboard optimized for 10'' display (dark theme)
* **Camera Feeds:** Two live RTSP IP camera streams directly embedded on the main screen
* **Weather Widget:** Displays real-time local weather using the OpenWeather integration
* **Shopping List:** Built-in shopping list.
* **Screensaver Mode:** Automatically switches to a minimalist clock screen after inactivity (via Fully Kiosk settings)
* **Bathroom heating** - option to remotely turn on bathroom heating.
* **Music Control:** Live Web-Radio on dashboard.

---

## 🧩 Integrations Used

* **Google Home / Tuya / Local RTSP Cameras**
* **OpenWeatherMap API** for weather
* **REST API sensors** for additional data (e.g., name days, calendar, etc.)
* **Browser Mod** for navigation automation and screensaver handling

---

## 🧱 Hardware Setup

* Lenovo tablet fixed in a **3D-printed wall frame** (PLA, White, Creality)
* Frame designed for **cable management** and easy tablet removal
* Powered via **30W USB charger**, tablet has **USB micro connector**.
* Optional external temperature sensor and light sensor connected to the Home Assistant network

---

## 🧰 Software Details

* **Home Assistant** (core) running on Windows 10 server
* **Frontend UI:** Custom Lovelace YAML with minimalist design
* **Browser:** Fully Kiosk Browser (Paid version)
* **Automation examples:**
  * Auto switch to screensaver after 15s inactivity
---

## 🧾 Future Plans

* Add motion sensor to wake the display automatically when someone approaches
* Create a custom HTML dashboard for better performance
* Expand dashboard with energy monitoring & home presence detection

---

## 🖼️ Gallery


---

## 💬 Notes

This project is designed to combine **usability, DIY practicality, and cost efficiency**. Everything runs locally, without dependence on cloud services where possible.

> Built with Home Assistant, RPI and my own patience :D
