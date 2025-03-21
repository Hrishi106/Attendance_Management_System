# Attendance Management System using OpenCV

## 📌 Overview
This project is an **AI-based Attendance Management System** that utilizes **OpenCV** and **face recognition** to mark attendance automatically. The system captures faces from a live webcam feed, matches them against a pre-stored dataset, and logs attendance with timestamps.

## 🚀 Features
- 🎥 **Real-time face detection** using OpenCV
- 🤖 **Face recognition** for identifying individuals
- 📜 **Automated attendance logging**
- 📊 **CSV file generation** for attendance records
- 🔒 **Secure & efficient**

## 🛠️ Technologies Used
- **Python**
- **OpenCV** (cv2)
- **NumPy**
- **face_recognition** library
- **Pandas** (for CSV logging)

## 🏗️ Installation

### Prerequisites
Ensure you have **Python 3.7+** installed.

### Step 1: Clone the Repository
```sh
git clone https://github.com/yourusername/attendance-management-opencv.git
cd attendance-management-opencv
```

### Step 2: Install Dependencies
```sh
pip install -r requirements.txt
```

### Step 3: Run the Application
```sh
python attendance.py
```

## 📌 How It Works
1. The webcam captures a frame.
2. The system detects faces using OpenCV.
3. It compares detected faces with stored images.
4. If a match is found, the attendance is marked with a timestamp.
5. Attendance data is saved in a CSV file.

## 📂 Project Structure
```
📁 attendance-management-opencv
│── 📂 images/         # Dataset of known faces
│── 📂 logs/           # Attendance CSV files
│── attendance.py      # Main application script
│── dataset_creator.py # Script to add new users
│── requirements.txt   # Required dependencies
│── README.md          # Project documentation
```

## 🎯 Future Improvements
- 🏷️ **GUI Integration** for ease of use
- ☁️ **Cloud storage support** for attendance logs
- 📲 **Mobile app support** for remote monitoring

## 📝 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Pull requests are welcome! For major changes, please open an issue first.

## 📧 Contact
For any inquiries, reach out at: **your-email@example.com**
