# Face Recognition Attendance System

## 📌 Project Overview
This project is a **Face Recognition-based Attendance System** that uses **OpenCV, face_recognition, and Firebase** to detect faces, verify student identities, and update attendance records in real-time.

## 🏗️ Features
- 📷 **Face Detection & Recognition** using `face_recognition`
- ☁️ **Cloud Storage & Database** with Firebase (Stores student images & records)
- 📊 **Real-time Attendance Tracking** 
- 🖥️ **Graphical User Interface (GUI)** for attendance visualization
- 🔍 **Efficient Face Matching** using precomputed encodings

## 🏛️ Project Architecture
1. **Image Capture & Preprocessing**: Captures face images from a webcam and converts them to encodings.
2. **Face Encoding Storage**: Stores precomputed encodings using `pickle`.
3. **Face Recognition**: Matches real-time webcam input with stored encodings.
4. **Firebase Integration**: Updates attendance records in Firebase.
5. **GUI Display**: Shows student information and attendance count.

## 🛠️ Technologies Used
- **Python** (OpenCV, NumPy, face_recognition, Firebase Admin SDK)
- **Firebase** (Realtime Database & Storage)
- **OpenCV** (Computer Vision Processing)
- **Pickle** (Serialization for face encodings)

