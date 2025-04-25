# Virtual-Mouse
# 🖱️ Virtual Mouse

A Python-based Virtual Mouse application that allows users to control their computer's mouse cursor using facial movements captured through a webcam. This project uses computer vision and machine learning techniques to track facial features and convert them into mouse movements.

---

## 📌 Objective

To create a virtual mouse system that:
- Tracks facial movements using a webcam.
- Moves the cursor on the screen according to these movements.
- Provides basic click functionality through facial expressions.

---

## 🧰 Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
  - `OpenCV` – for real-time computer vision tasks
  - `mediapipe` – for facial landmark detection
  - `pyautogui` – for controlling the mouse cursor
  - `NumPy` – for numerical operations
- **Environment**: Python 3.x

---

## 📁 Dataset

This project does not require an external dataset. It uses real-time video input from the webcam to detect facial landmarks and perform mouse actions.

---

## 🧠 Key Steps

1. **Face Detection**: Detect facial landmarks using `mediapipe`.
2. **Mouse Movement**: Map the position of key facial landmarks to move the cursor on the screen.
3. **Mouse Click**: Detect specific facial expressions (like blinking or a smile) to simulate mouse clicks.

---

## 🚀 Getting Started

### 📦 Install Requirements

```bash
pip install opencv-python mediapipe pyautogui numpy
