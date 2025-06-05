# 🚘 ReAct-Drive

ReAct-Drive is a Python-based system designed to monitor driver alertness using facial landmark analysis and computer vision. By analyzing eye aspect ratio and facial landmarks, the system can detect drowsiness or inattention and provide alerts to help ensure road safety.

---

## Demo


<video src="https://github.com/user-attachments/assets/8a64240a-786c-4d31-bc3d-fe883fa96adf" width="352" height="720"></video>

## 🧠 Features

- **Facial Landmark Detection** using Dlib's 68-point model.
- **Eye Aspect Ratio (EAR) Monitoring** to detect drowsiness.
- **Real-Time Video Processing** using OpenCV.
- **Auditory Alerts** to notify the driver when signs of fatigue are detected.
- **Customizable Sensitivity** and alert thresholds.

---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure you have Python 3 installed, then install the required libraries:

```bash
pip install opencv-python dlib imutils
```
## Installation
Clone the repository:

```bash

git clone https://github.com/AyushS1304/ReAct-Drive.git
cd ReAct-Drive
```
Download the pre-trained shape predictor file from Dlib, extract it, and place it in the project directory.

## 🧪 Running the Application
Main Script
```bash

python final-integration.py 
```

## 🗂️ Project Structure
```bash

ReAct-Drive/
├── final-integration.py                          # Primary script for driver monitoring
├── main_dlib.py                    # Alternative using Dlib facial detection
├── train.py                        # (Optional) Training or tuning script
├── haarcascade_frontalface.xml     # Haar cascade for face detection
├── haarcascade_eye.xml             # Haar cascade for eye detection
├── shape_predictor_68_face_landmarks.dat  # Facial landmark model
├── alert-sound.mp3                 # Alert sound for drowsiness
├── take_a_break.mp3                # Voice alert to take a break
├── focus.mp3                       # Voice alert to stay focused
├── facial_landmarks_68.jpg        # Reference image
├── left-eye.jpg                    # Eye region reference
├── right-eye.jpg                   # Eye region reference
```

## 📄 License
This project is licensed under the MIT License.
