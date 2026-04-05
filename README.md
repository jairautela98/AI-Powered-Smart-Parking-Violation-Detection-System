# 🚗 AI Smart Parking Violation Detection System Part of Camera-Intelligence)

### *(Live Monitoring Dashboard using Streamlit + YOLO + OpenCV)*

---

## 📌 Overview

This project is an **AI-powered smart parking monitoring system** that detects **wrong parking and no-parking violations** in real time using **computer vision and deep learning**.

It leverages:

* **YOLO (Ultralytics)** for vehicle detection
* **OpenCV** for image processing
* **Streamlit** for live dashboard visualization

The system processes **live CCTV/webcam feeds** and identifies vehicles violating parking rules within defined zones.

---

## 🎯 Key Features

* 🚗 Real-time vehicle detection (cars, bikes, buses, trucks)
* 🧠 Deep learning model (YOLOv8)
* 📍 Custom **No Parking Zone (ROI)** detection
* 🚨 Automatic violation detection
* 📊 Live dashboard with metrics and logs
* 🎥 Supports webcam + uploaded video
* ⚡ Lightweight and easy to deploy

---

## 🖼️ System Workflow

1. Capture video stream (CCTV/Webcam)
2. Detect vehicles using YOLO model
3. Define **No Parking Zone (ROI)**
4. Track vehicles entering the zone
5. Trigger violation alerts
6. Display results on Streamlit dashboard

---

## 🧠 Tech Stack

| Component       | Technology           |
| --------------- | -------------------- |
| Language        | Python 🐍            |
| AI Model        | YOLOv8 (Ultralytics) |
| Computer Vision | OpenCV               |
| Dashboard       | Streamlit            |
| Data Handling   | Pandas / NumPy       |

---

## 📁 Project Structure

```
├── app.py                # Streamlit dashboard
├── yolov8n.pt           # YOLO pretrained model
├── temp.mp4             # Sample video (optional)
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/parking-violation-ai.git
cd parking-violation-ai
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install streamlit opencv-python ultralytics numpy pandas
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

---

## 🎛️ Usage

* Select **Webcam** or **Upload Video**
* Adjust **Detection Confidence**
* Enable/Disable **No Parking Zone (ROI)**
* Monitor:

  * 🚨 Violations count
  * 🚗 Vehicles inside zone
  * 📊 Real-time logs

---

## 📊 Example Output

* Bounding boxes around detected vehicles
* Red boxes = violation
* Live metrics dashboard
* Tabular violation logs

---

## 🚀 Future Enhancements

* 🔢 License Plate Recognition (ANPR)
* ☁️ Cloud integration (AWS / Firebase)
* 📱 SMS/WhatsApp alerts
* 🧠 Advanced tracking (DeepSORT)
* 📍 Geo-fencing with GPS
* 📊 Analytics dashboard (charts & reports)

---

## 🧪 Use Cases

* 🚦 Smart Traffic Management
* 🏙️ Smart City Infrastructure
* 🅿️ Parking Enforcement
* 🚔 Law Enforcement Automation
* 🛣️ Highway Monitoring

---

## 🤝 Contribution

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Commit changes
4. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Your Name**

* GitHub: https://github.com/your-username
* LinkedIn: https://linkedin.com/in/your-profile

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---
