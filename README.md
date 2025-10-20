# 🚗 Vehicle Speed Detection using YOLO and Python

This project uses **YOLO (You Only Look Once)** object detection and computer vision techniques to detect vehicles in real-time and estimate their **speed** from video footage or live camera streams.

By combining **YOLO’s fast object detection** with **frame-by-frame tracking and distance estimation**, the system can accurately estimate the speed of each vehicle in a scene.

---

## 🎯 Features

- 🧠 **Vehicle Detection** using YOLOv5 / YOLOv8  
- 📹 **Real-time tracking** using centroid tracking or DeepSORT  
- ⚡ **Speed estimation** based on pixel displacement and time  
- 🧾 Support for both **video files** and **live camera input**  
- 📊 Outputs speed data overlayed on video frames  
- 💾 Optional: Save processed videos with bounding boxes and speeds

---

## 🧰 Tech Stack

- **Python 3.8+**
- **OpenCV**
- **YOLOv5 / YOLOv8**
- **NumPy**
- **time / datetime**
- **Matplotlib 
