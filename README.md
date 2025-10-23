Lane-Vehicle-Monitoring-System Public
Vehicle detection and lane-wise traffic analysis on prerecorded videos using YOLOv8 and ByteTrack
python
numpy
supervision
html-css-javascript
opencv-python
bytetrack
yolov8
 Python Updated 9 minutes ago

# Lanewise-Vehicle-Monitoring-System 🚦

## Project Overview
**Vehicle Traffic Analysis** is a system for **vehicle detection and lane-wise traffic monitoring** using **YOLOv8** and **ByteTrack**. It can analyze **pre-recorded videos**, count vehicles per lane, and classify traffic intensity as **Smooth** or **Heavy**, providing visual feedback on video frames.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Real-Time Traffic Monitoring System
This system uses **YOLOv8** for vehicle detection and **ByteTrack** for multi-object tracking. It delivers **lane-wise traffic analytics, vehicle counting, and intensity analysis** for traffic management applications.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Key Features
- **🎯 Real-time Vehicle Detection** – Detect vehicles accurately with YOLOv8.  
- **🔄 Multi-Object Tracking** – Track vehicles consistently using ByteTrack.  
- **📊 Traffic Analytics** – Lane-wise vehicle counting and intensity analysis.  
- **🎥 Video Processing** – Supports multiple video formats.  
- **📈 Visualization** – Real-time tracking with bounding boxes.  
- **🌐 Web Dashboard (Optional)** – Interactive interface for monitoring traffic.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Technology Stack

| Component           | Technology                     |
|---------------------|--------------------------------|
| Object Detection    | YOLOv8 (Ultralytics)           |
| Object Tracking     | ByteTrack                      |
| Computer Vision     | OpenCV                         |
| Video Processing    | OpenCV Video I/O               |
| Data Processing     | NumPy, Supervision             |
| Backend Framework   | FastAPI / Flask                |
| Frontend            | Streamlit / React              |

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Requirements
- Python 3.10+  
- OpenCV  
- NumPy  
- Ultralytics YOLOv8  
- Supervision library (for ByteTrack)  
- NVIDIA GPU (recommended)  
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Minimum System Requirements**:  
- Python 3.8+  
- 4GB RAM  

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Quick Start #QuickStart #Setup #TrafficAnalysis

🛠 Create a Virtual Environment
Run: python -m venv venv
#VirtualEnvironment #Python

⚡ Activate the Virtual Environment

Windows: venv\Scripts\activate

Linux / Mac: source venv/bin/activate
#ActivateEnv #PythonSetup

📦 Install Dependencies
Upgrade pip first: pip install --upgrade pip
Install required libraries: pip install ultralytics opencv-python numpy supervision torch torchvision
#Dependencies #PythonLibraries #YOLOv8

▶️ Run the Traffic Analysis Script
Run: python traffic_analysis.py
#RunScript 

🎥 Run with a Custom Video Input
Run: python traffic_analysis.py --input path/to/your/video.mp4 --output output/video.mp4
#Output


Lane-Vehicle-Monitoring-System-frontend

## 🚀 Live Demo

You can access the live site here:  
[ Live Site](https://sunkukarthik5.github.io/Lane-Vehicle-Monitoring-System-frontend-/)
