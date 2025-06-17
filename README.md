# Hand Gesture-Based Screen Brightness Controller

This Python application uses your webcam to detect hand gestures and dynamically control your screen brightness. It leverages MediaPipe to detect hand landmarks and calculates the distance between the thumb and index finger to adjust brightness accordingly.

---

## Features

- Real-time hand tracking using MediaPipe
- Measures distance between thumb and index finger
- Maps finger distance to screen brightness (0%–100%)
- Simple and intuitive UI using OpenCV

---

## Requirements

Install all dependencies using the `requirements.txt` file:

```bash
pip install -r requirements.txt
