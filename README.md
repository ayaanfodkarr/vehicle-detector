# 🚗 Real-Time Vehicle Detection System

A real-time computer vision system that detects vehicles, identifies car models, reads license plates, and calculates speed — all simultaneously using deep learning.

## 🎥 What it does
- 🚗 Detects multiple vehicles simultaneously in real-time
- 🏷️ Identifies car models (Toyota, BMW, Range Rover, Limousine etc.)
- 🔢 Reads license plate numbers automatically
- ⚡ Calculates vehicle speed in km/h
- 🎨 Color coded by vehicle type (Car, Bus, Truck, Motorcycle)
- 📊 Shows confidence scores for every detection

## 🛠️ Tech Stack
- Python
- YOLOv8 (Ultralytics) — real-time vehicle detection
- EasyOCR — license plate reading
- OpenCV — video processing
- PyTorch with CUDA — GPU acceleration
- Jupyter Notebook

## 💻 Hardware Used
- NVIDIA GeForce RTX 3060 Laptop GPU
- Runs at 30-50 FPS in real-time

## 💡 Real World Use Case
This system replicates what traffic enforcement cameras do — detecting vehicles, reading plates, and measuring speed automatically without any human intervention.

## 🚀 How to Run
1. Clone the repo
2. Install dependencies:
3. Open `vehicleDetector.ipynb` in Jupyter Notebook
4. Run all cells
5. Point to your video file:
```python
run_vehicle_detector(source='your_video.mp4')
```

## 📸 Results
- ✅ Real-time detection at 30-50 FPS
- ✅ License plate reading works on close-up footage
- ✅ Car model identification (Beach Wagon, Limousine, Sports Car etc.)
- ✅ Speed estimation in km/h
