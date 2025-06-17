# arm-curl-counter
# 💪 Pose-Based Bicep Curl Counter using OpenCV and MediaPipe

This project is a real-time computer vision application that uses **MediaPipe** and **OpenCV** to detect human body poses and count **bicep curl repetitions** using a webcam feed. It can track repetitions for **left arm**, **right arm**, or **both arms** individually using angle estimation of elbow joints.

---

## 🧠 Features

- Real-time webcam input
- Tracks elbow angles using MediaPipe pose landmarks
- Counts reps when the elbow flexes and extends
- Displays:
  - Repetition count
  - Current stage (Up/Down)
  - Real-time pose skeleton overlay

---

## 🛠️ Tech Stack

- Python 3.10+
- OpenCV
- MediaPipe
- NumPy

---

## 📦 Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/pose-bicep-curl-counter.git
   cd pose-bicep-curl-counter
