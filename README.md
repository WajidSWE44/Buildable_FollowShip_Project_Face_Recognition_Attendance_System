# Face_Recognition_Attendance_System 
A simple yet powerful Python project to automate attendance using facial recognition technology. Designed for classrooms, offices, or any group setting, this system captures faces via webcam, recognizes known people, and marks attendance automatically.

## Features
Real-time face detection and recognition using OpenCV and face_recognition library
Attendance logging with timestamps saved in CSV files
Recognizes and labels unknown faces as “Anonymous”
Lightweight and easy to use with minimal setup
Console-based user interface for simplicity
Modular code structure for easy customization and expansion

## 🛠️Technologies Used
#### Language:
       Python 3.x
#### Libraries: 
       OpenCV
       face_recognition
       NumPy
       Pandas (for attendance CSV handling)

## 🧠How It Works
#### Data Collection: 
     Capture face images for each person and store with labels.
#### Training/Encoding: 
     Generate facial embeddings for each known individual.
#### Recognition: 
     Detect and match faces in real-time webcam feed.
#### Attendance Logging: 
     Automatically write attendance with date and time into CSV.

## Getting Started
Prerequisites
Python 3.6 or above installed
Webcam connected to your system

## Installation
### Clone or download the repository:
#### git clone 
<https://github.com/WajidSWE44/Buildable_FollowShip_Project_Face_Recognition_Attendance_System>

cd <E:\Fellowship_Project\Face-Recognition-Attendance-System-main\Face-Recognition-Attendance-System-main>

## Install required libraries:
pip install opencv-python face_recognition numpy pandas

## Run the main program:
python attendance.py

## Usage
-> The system will open your webcam and start recognizing faces.
-> Make sure to first add and encode faces using the provided scripts (or your custom data collection).
-> Attendance will be recorded automatically in attendance.csv.

##🚀 Future Improvements
-> Add GUI with Tkinter or Streamlit
-> Integrate deep learning models for better accuracy
-> Support cloud storage and real-time dashboards
-> Add multi-face attendance recognition

##🙋‍♂️ About Me
Hi,this is me Wajid Ali.I am learning and building projects on Python and computer vision. This project helped me understand facial recognition and practical ML applications.

## Contact
#### Feel free to reach out:
✉️ wa4565196@gmail.com
GitHub|https://github.com/WajidSWE44
LinkedIn|www.linkedin.com/in/rao-wajid-ali-b262a5293
