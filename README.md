# 🤖 Automatic Face Recognition Attendance System using ESP32-CAM

A smart and automated attendance system using **ESP32-CAM** and **OpenCV** to detect, recognize, and log attendance through facial recognition — ideal for educational institutes or office environments.

---

## 📌 Project Highlights

- 🎥 Real-time face detection via ESP32-CAM
- 🧠 Face recognition using pre-trained models
- ✅ Auto-attendance marking with timestamp
- 💾 Attendance records stored in file/database
- 🖥️ Python OpenCV-powered backend

---

## 🧩 Components Used

| Component         | Description                              |
|------------------|------------------------------------------|
| ESP32-CAM         | Captures and streams facial images       |
| Python (3.x)      | Main programming language                |
| OpenCV            | Used for face detection & recognition    |
| USB to TTL Module | For programming ESP32-CAM                |

---

## ⚙️ How It Works

1. ESP32-CAM captures a video stream.
2. OpenCV detects faces in the feed.
3. Pre-trained model recognizes individuals.
4. Attendance is logged with name, date & time.
5. Data is stored for record-keeping.

---

## 🚀 Getting Started

### 🔌 Hardware Setup

- Connect ESP32-CAM to USB-TTL converter
- Configure camera and Wi-Fi settings in Arduino IDE
- Upload firmware to ESP32-CAM
- Deploy the module for live streaming

### 🖥️ Software Setup

```bash
# 1. Clone the repository
git clone https://github.com/your-username/face-recognition-attendance-system.git
cd face-recognition-attendance-system

# 2. Install Python dependencies
pip install opencv-python

# 3. Run the attendance system
python attendance_system.py
