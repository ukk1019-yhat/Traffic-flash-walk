# 🚶 Pedestrian Safety Beacon

A lightweight, browser-based utility designed to increase pedestrian visibility while crossing streets at night. This tool turns your smartphone screen into a high-contrast, flashing strobe light to alert oncoming drivers.

## 🔦 Purpose
Walking at night or in low-visibility conditions can be dangerous. This project provides a "Zero-Install" solution that allows anyone with a smartphone to simulate a traffic wand or hazard light, helping to slow down vehicles and signal intent to cross.

## ✨ Features
* **High-Contrast Strobe:** Uses CSS keyframes to pulse colors (Red, Yellow, Green) for maximum visibility compared to a static light.
* **Screen Wake Lock:** Utilizes the `navigator.wakeLock` API to prevent the phone screen from dimming or locking while in use.
* **One-Handed Interface:** Large, thumb-accessible buttons placed at the bottom of the screen for safe operation while walking.
* **Zero Dependencies:** Built with pure HTML, CSS, and Vanilla JavaScript. No framework overhead.
* **Offline Capable:** Can be saved locally as an HTML file and works without an internet connection.

## 🚀 How to Use
1.  **Open the App:** Navigate to the hosted link (or open the `index.html` file).
2.  **Maximize Brightness:** Manually set your phone brightness to 100% for best results.
3.  **Select Mode:**
    * 🔴 **STOP:** Flashing Red (Use to signal cars to stop).
    * 🟡 **SLOW:** Flashing Amber (Use while waiting on the curb).
    * 🟢 **WALK:** Flashing Green (Use while actively crossing).
4.  **Hold Up High:** Hold the phone screen facing oncoming traffic.

## 🛠️ Installation
There is no installation required. This is a static web page.

## ⚠️ Safety Disclaimer
**PLEASE READ CAREFULLY:**
* **Not a Legal Traffic Device:** This tool is for auxiliary visibility only. It does not replace official traffic signals, crosswalks, or reflective gear.
* **Drivers May Not Stop:** Do not assume a driver sees you or will stop just because you are using this light. Always make eye contact and confirm the vehicle is slowing down before stepping onto the road.
* **Night Use Only:** Phone screens are generally not bright enough to be effective signals during daylight hours.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
