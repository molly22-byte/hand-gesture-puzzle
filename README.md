# 🤏 Hand Gesture Puzzle Game

🚀 A real-time computer vision system that enables users to interact with a dynamic puzzle environment using intuitive hand gestures. By replacing traditional input methods like mouse and touch, the application transforms live camera input into an interactive game, allowing users to capture, generate, and solve puzzles seamlessly through natural hand movements.

---

## 🎬 Demo

![Demo](puzzle demo.mp4)

---

## ✨ Features

* 🧠 Real-time hand tracking using **MediaPipe**
* 🤏 Pinch gesture to **pick & move tiles**
* ✌️ Two-hand gesture to **select frame**
* 🧩 Live camera frame converted into a **3x3 puzzle**
* 🎮 Gesture-based drag & drop interaction
* ⏱️ Timer to track solving performance
* 🎨 Smooth UI with pointer tracking & motion trail

---

## 🧠 System Pipeline

text
Camera → Hand Detection → Gesture Recognition → Puzzle Logic → Rendering

---

## ⚙️ Tech Stack

| Technology | Purpose                    |
| ---------- | -------------------------- |
| OpenCV     | Camera capture & rendering |
| MediaPipe  | Hand tracking & landmarks  |
| NumPy      | Image processing           |
| Python     | Core logic                 |

---

## ▶️ Run Locally

```bash
git clone https://github.com/molly22-byte/hand-gesture-puzzle.git
cd hand-gesture-puzzle
pip install -r requirements.txt
python main.py
```

---

## 🎮 Controls

* ✌️ Two index fingers → Select frame
* 🤏 Pinch → Pick tile
* Release → Drop tile
* Move hand → Drag tile

---

## 📌 Requirements

* Webcam
* Good lighting conditions
* Python 3.8+

---

## 🚀 Future Improvements

* 🌐 Web-based version
* 🎵 Sound feedback
* 🎨 Enhanced UI/UX
* 🧠 Advanced gesture recognition


