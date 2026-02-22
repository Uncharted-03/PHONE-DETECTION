# 📵 AI Phone Detection & Alert System

**Author:** Uncharted-03 || Uday  
**GitHub:** [Uncharted-03](https://github.com/Uncharted-03) 
---

This is a Python-based application that uses Computer Vision (YOLOv8) to detect mobile phones in a live webcam feed. When a phone is detected, it triggers an audio alarm. 

This tool is useful for **Study Sessions**, **No-Phone Zones**, or **Focus Time** to prevent digital distractions.

## 🚀 Features
- **Real-time Detection:** Uses the YOLOv8 Nano model for fast and accurate detection.
- **Audio Alert:** Plays an alarm/sound file when a phone is visible.
- **Performance Optimized:** Includes frame skipping and image resizing to run smoothly on standard laptops.
- **Customizable:** Easily change detection sensitivity, cooldown timers, and screen resolution.
- **State-Aware Audio:** Audio stops immediately when the phone is removed from the frame.

## 🛠️ Prerequisites
- Python 3.8 or higher installed on your system.
- A Webcam.

## 📦 Installation

1. **Clone or Download** this repository/folder.
2. Open your terminal/command prompt in the project folder.
3. Install the required Python libraries:

```bash
pip install opencv-python ultralytics pygame
```

## 🎮 Run

```bash
python app.py
```

---

**© 2026 Uncharted-03 || Uday. All rights reserved.**  
*Made with ❤️ by Uday*

