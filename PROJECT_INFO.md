# ✋ Hand Raise Detection using YOLOv8 Pose Estimation

A real-time computer vision application that detects whether a person has raised their hand using **YOLOv8 pose estimation** and a webcam feed. Built with `Ultralytics`, `OpenCV`, and Python, this project leverages keypoint detection to analyze body posture and determine hand-raising gestures.

---

## 📌 Features

- 🔍 Real-time pose estimation with YOLOv8
- 🙋 Hand raise detection using keypoints
- 🎥 Live webcam feed with overlayed feedback
- 🖼 Visual output using OpenCV

---

## 🧠 How It Works

1. Load YOLOv8 pose estimation model (`yolov8n-pose.pt`)
2. Capture video using OpenCV
3. Detect keypoints for each frame
4. Compare wrist and shoulder positions to check if a hand is raised
5. Display result: `"Hands Raised"` or `"Hands Not Raised"` in real-time

---

## 📂 Project Structure
📦 hand-raise-detector/
├── hand_raise_detection.py     # Main Python script
├── README.md                   # Project documentation
└── requirements.txt            # Dependencies (optional)

---

## 🖥️ Demo Screenshot

> _[You can add an actual screenshot or GIF here later]_

---

## 🚀 Getting Started

### 📋 Prerequisites

- Python 3.8+
- Webcam or video input
- YOLOv8 pose model (`yolov8n-pose.pt`)

### 🔧 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/hand-raise-detector.git
cd hand-raise-detector

# Install dependencies
pip install ultralytics opencv-python numpy
