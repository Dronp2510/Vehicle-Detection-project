# 🚗 Vehicle Detection & Speed Estimation System

This project is a computer vision–based system for **real-time vehicle detection, tracking, speed estimation, and vehicle counting** using deep learning and object tracking techniques.  
It is implemented in **Python** using a Jupyter Notebook.

---

## 📌 Project Overview

The system detects vehicles from video input, tracks them across frames, estimates their speed based on line-crossing logic, and counts vehicles by class.  
It is suitable for **traffic monitoring, intelligent transportation systems, and academic learning purposes**.

---

## ✨ Features

- 🚘 **Vehicle Detection**
  - Uses a YOLO-based object detection model
  - Detects common vehicle classes such as:
    - Car
    - Bus
    - Truck
    - Motorcycle

- 🔁 **Multi-Object Tracking**
  - Uses the SORT (Simple Online Realtime Tracking) algorithm
  - Maintains consistent IDs for vehicles across frames

- ⏱️ **Speed Estimation**
  - Speed calculated using **line-crossing time**
  - Two horizontal lines placed at a fixed real-world distance (default: 5 meters)
  - Speed is estimated when a vehicle crosses both lines

- 🔢 **Vehicle Counting**
  - Counts vehicles per class
  - Counts are updated in real time

- 🎥 **Video Processing**
  - Works on prerecorded video input
  - Frame-by-frame processing with visual overlays

---

## 🛠️ Technologies Used

- **Python**
- **YOLO (You Only Look Once)** – for vehicle detection
- **OpenCV** – for video processing and visualization
- **SORT Algorithm** – for object tracking
- **NumPy** – for numerical operations
- **Matplotlib** (optional) – for analysis and visualization

---

## 📂 Project Structure


vehicle-detection-project/
│
├── detection_project.ipynb   # Main Jupyter Notebook
├── input_video.mp4           # Input traffic video (user provided)
├── README.md                 # Project documentation

---

📊 Speed Calculation Logic

Two horizontal lines are drawn on the video frame
Known real-world distance between lines (default: 5 meters)

Speed formula used:

Speed = Distance / Time

Speed is displayed in km/h

---

📈 Future Improvements

🚀 Add number plate detection (ANPR)
📐 Camera calibration for more accurate speed estimation

---

📜 License

This project is for educational and learning purposes.

---

Developed by Me(Dron Patel) and My team.
