# Real-Time-People-Counting-System-Using-OpenCV-and-Directional-Tracking

# 👁️ Real-Time People Counting System Using OpenCV & Directional Tracking

A real-time, vision-based analytics system that detects, tracks, and counts people moving **in** and **out** of an enclosed space using advanced computer vision techniques. Built using **Python**, **OpenCV**, and a direction-aware algorithm, this project bridges the gap between AI-powered video surveillance and smart occupancy management.
---
<img width="1917" height="833" alt="image" src="https://github.com/user-attachments/assets/a68d1a13-2e10-45dd-9420-790b9316daad" />


## 🚀 Project Highlights

- ✅ **Real-Time Detection & Tracking** of multiple individuals using OpenCV.
- 🔁 **Bidirectional Movement Analysis** for precise IN and OUT counting.
- ⚡ **Fast and Lightweight**: Optimized for edge devices and laptops.
- 🎯 **Customizable Zone Line** to define your count threshold (doorways, hallways).
- 💻 **Live Visual Feedback** with bounding boxes, tracking lines, and counters.
- 🔌 Modular codebase ready for **IoT, cloud dashboards, or database** integration.

---

## 📷 How It Works

> "Counting isn't just detection. It's understanding motion with context."

1. **Frame Capture**: Video input from webcam or IP camera.
2. **People Detection**: 
   - Option 1: HOG + SVM (fast & lightweight).
   - Option 2: MobileNet-SSD (deep learning-based, higher accuracy).
3. **Object Tracking**: Uses centroid tracking to persist identities across frames.
4. **Line Crossing Logic**: Counts based on trajectory across a virtual boundary line.
5. **Visual Output**: Annotated feed with direction arrows and counters.

---

## 🧠 Tech Stack

| Category          | Technology       |
|------------------|------------------|
| Programming      | Python 3.8+       |
| Computer Vision  | OpenCV, Numpy     |
| Tracking Utility | Imutils (optional) |
| ML Models        | MobileNet-SSD or HOG+SVM |
| Platform         | Cross-platform (Windows/Linux/macOS) |

---

cd people-counter-opencv
pip install -r requirements.txt
