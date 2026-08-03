# ⚽ SOCCER-MATCH-ANALYSE

> **AI-powered Football Match Analysis using Computer Vision and Deep Learning**

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg)
![YOLO](https://img.shields.io/badge/YOLO-Object%20Detection-red.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 📖 Overview

SOCCER-MATCH-ANALYSE is an AI-powered football analytics project that automatically analyzes football match videos using computer vision.

The application detects and tracks players, referees, and the ball, assigns players to teams using jersey colors, compensates for camera movement, estimates player speed and distance covered, and generates an annotated output video.

---

## ✨ Features

- 🎯 Player, referee and ball detection
- 📍 Multi-object tracking
- 👕 Automatic team assignment
- 📷 Camera movement estimation
- 🗺️ Perspective transformation
- ⚡ Speed estimation
- 📏 Distance covered
- 🎥 Annotated output video

---

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Scikit-learn
- Pandas
- YOLO

---

## 📂 Project Structure

```text
SOCCER-MATCH-ANALYSE/
├── camera_movement_estimator/
├── player_ball_assigner/
├── speed_and_distance_estimator/
├── team_assigner/
├── trackers/
├── utils/
├── view_transformer/
├── input_videos/
├── output_videos/
├── models/
├── stubs/
├── main.py
└── yolo_inference.py
```

## 🚀 Installation

```bash
git clone https://github.com/1949-2005/SOCCER-MATCH-ANALYSE.git
cd SOCCER-MATCH-ANALYSE

python -m venv venv

# Windows
venv\Scripts\activate

pip install -r requirements.txt

python main.py
```

## 🗺️ Roadmap

- Real-time analysis
- Heatmaps
- Pass detection
- Ball possession
- xG estimation
- Tactical dashboard

## 👨‍💻 Author

**Othmane Zitouni**

GitHub: https://github.com/1949-2005

⭐ If you like this project, give it a star!
