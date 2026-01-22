# 🔐 Intruder Detection System Using YOLOv8 & Gradio

## 📌 Overview
This project implements an **AI-based Intruder Detection System** using **YOLOv8** for person detection and **Gradio** for an interactive web interface.

Users can upload a video through the UI, and the system automatically detects intruders (persons), captures them, and stores cropped images with timestamps.

The project demonstrates a complete **computer vision application with a frontend interface**, making it suitable for real-world security use cases.

---

## 🎯 Features
- Upload video through Gradio web UI
- Detect intruders using YOLOv8
- Capture and save intruder images automatically
- Timestamp-based file naming
- Lightweight and fast detection (yolov8n)
- Runs on Google Colab or local system

---

## 🏗️ Architecture
User → Gradio UI → YOLOv8 Model → Intruder Detection → Image Capture → Storage


---

## 🛠️ Technologies Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Gradio
- Google Colab
- Deep Learning
- Computer Vision

---
📊 Output
---
Intruders are detected from video

Cropped intruder images saved in captured/

Easy-to-use web UI for testing

---
⚠️ Limitations
---
Detects only persons (no identity recognition)

Designed for recorded videos

No real-time CCTV stream (yet)

---
🚀 Future Enhancements
---
Live webcam stream

Face recognition

Alert system (email/SMS)

Cloud storage

Admin dashboard

Mobile UI

---
⭐ Conclusion
---
This project demonstrates how deep learning + computer vision + UI can be combined to build a practical intruder detection system for security applications.
