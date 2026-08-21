# 🍔 TouchlessOS™

> **Transforming standard screens into AI-powered, germ-free spatial kiosks using a standard webcam and pure JavaScript.**

[![Built with MediaPipe](https://img.shields.io/badge/AI-Google%20MediaPipe-blue)](https://mediapipe.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 💡 The Problem
Public touchscreens (at fast-food restaurants, hospitals, and airports) are major hygiene hazards, accumulating bacteria and germs from thousands of daily users. Traditional touchless hardware setups require expensive infrared sensors and proprietary machinery.

## 🚀 The Solution
**TouchlessOS™** uses software-defined spatial computing. By leveraging Google's MediaPipe Neural Networks via a web browser, it tracks hand joints in real-time, allowing users to point, hover, and use an Apple Vision Pro-style **"pinch-to-click"** gesture to navigate and place orders completely touch-free.

---

## ✨ Key Features
* **Zero Hardware Required:** Runs entirely in any modern web browser using a standard $5 webcam.
* **Spatial Pinch Engine:** High-precision index-and-thumb coordinate tracking with adjustable hitboxes for smooth interaction.
* **Accessibility First (Voice AI):** Integrated Web Speech API reads cart updates and confirmations aloud for visually impaired users.
* **Dynamic Cart Management:** Users can add items, review prices, or pinch to delete specific items directly from the live sidebar.
* **Auto-Scroll Zones:** Hand-tracking-based navigation allows hands-free scrolling through large menus.

---

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Glassmorphic UI design)
* **Logic:** Vanilla JavaScript (ES6+)
* **AI Computer Vision:** Google MediaPipe Hands (CDN-powered)
* **Audio & Speech:** Web Audio API (Synthesized feedback) & Web Speech API

---

## 💻 How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/SamyakWeb25/TouchlessOS.git](https://github.com/SamyakWeb25/TouchlessOS.git)
