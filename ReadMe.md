# 🎥 Face Recognition Attendance System with Emotion Detection

A Python-based **Face Recognition Attendance System** with **Emotion Detection** using OpenCV, DeepFace, and Tkinter GUI.  
This project allows capturing face images, training a recognizer, marking attendance using face recognition, checking attendance by UID, and performing real-time emotion detection.

---
## Table of Contents
- <a href="#Features">Features</a>
- <a href="#Technologies Used">Technologies Used</a>
- <a href="#Project Structure">Project Structure</a>
- <a href="#Install Required Libraries">Install Required Libraries</a>
- <a href="#How to Run">How to Run</a>
- <a href="#How It Works">How It Works</a>
- <a href="#Algorithm Used">Algorithm Used</a>
- <a href="#Future Enhancements">Future Enhancements</a>
- <a href="#Author">Author</a>

---
<h2><a class="anchor" id="Features"></a>Features</h2>

✔ Capture face images via webcam  
✔ Train LBPH face recognizer  
✔ Real-time face recognition for attendance  
✔ Automatic CSV attendance report generation  
✔ Search attendance by UID  
✔ Real-time emotion detection using DeepFace  
✔ User-friendly Tkinter GUI  

---
<h2><a class="anchor" id="Technologies Used"></a>Technologies Used</h2>

- Python 3.x  
- OpenCV  
- NumPy  
- Pandas  
- Tkinter  
- DeepFace  
- Haarcascade Classifier 

---
<h2><a class="anchor" id="Project Structure"></a>Project Structure</h2>

Face-Recognition-Attendance/
│
├── faces/ # Stored captured face images
├── attendance/ # Generated attendance CSV files
├── trainer.yml # Trained LBPH model
├── labels.npy # Stored label mappings
├── main.py # Main application code
├── README.md # Project documentation

---
<h2><a class="anchor" id="Install Required Libraries"></a>Install Required Libraries</h2>

pip install opencv-python opencv-contrib-python numpy pandas deepface.
(Tkinter comes pre-installed with Python on Windows)

---
<h2><a class="anchor" id="How to Run"></a>How to Run</h2>

python main.py
The GUI window will open.

---
<h2><a class="anchor" id="How It Works"></a>How It Works</h2>

Step 1: Capture Faces
- Enter UID and Name
- Click "Capture Faces"
- The system captures 50 face images

Step 2: Train Recognizer
- Click "Train Recognizer"
- Model is trained using LBPH algorithm

Step 3: Mark Attendance
- Click "Mark Attendance"
- Recognized faces are logged into CSV with time & date

Step 4: Check Attendance
- Enter UID
- Click "Show Attendance"

Step 5: Emotion Detection
- Click "Detect Emotions"
- Displays real-time dominant emotion

---
<h2><a class="anchor" id="Algorithm Used"></a>Algorithm Used</h2>

- LBPH (Local Binary Pattern Histogram) for face recognition
- Haar Cascade Classifier for face detection
- DeepFace for emotion detection

---
<h2><a class="anchor" id="Future Enhancements"></a>Future Enhancements</h2>

- Add database integration (MySQL)
- Add email notifications
- Cloud attendance storage
- Mobile App version

---

## Author

Ram Krishna
Email: ramkrishna000888@gmail.com
Linkeddin: https://www.linkedin.com/in/ramkrishna000/