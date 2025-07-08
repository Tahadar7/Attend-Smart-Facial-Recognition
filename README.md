
# Attend Smart – Face Recognition Attendance System

Attend Smart is a facial recognition-based attendance management system built with Python, designed to streamline attendance taking for educational institutions. This project was developed as part of a software engineering course and showcases concepts such as real-time image processing, user role management, database integration, and GUI development.

---

## 🧠 Project Overview

The system captures real-time video from a webcam, recognizes student faces, and marks attendance in a MySQL database. It supports role-based access for Admins and Teachers, allowing them to manage students, courses, sections, and view attendance reports.

---

## 🔧 Features

- Real-time face detection and recognition
- Audio confirmation after successful recognition
- Admin and Teacher login with role-based permissions
- Add/Edit/Delete student, section, and course data
- Attendance reports in CSV and PDF formats
- Email report delivery using SendGrid API
- GUI interface built using Flet (Python UI framework)
- Face encoding stored using Pickle
- Attendance logs and analytics
- Manual attendance editing

---

## ⚙️ Tech Stack

- **Programming Language:** Python 3.8+
- **Face Recognition:** `face_recognition`, `OpenCV`
- **GUI Framework:** `Flet`
- **Database:** MySQL Server 8.0
- **Email API:** SendGrid
- **Others:** NumPy, Pillow, MySQL Connector, Pickle

---

## 📁 Project Structure

- `main.py` – Launches the GUI
- `face_recognition/` – Facial recognition logic
- `ui/` – Flet UI components
- `database/` – MySQL connection and queries
- `utils/` – Utilities (file handling, encoding, logs)
- `attendance/` – Attendance records and export
- `config/` – API keys and system settings

*(File paths may vary based on uploaded zip contents)*

---

## 🚀 How to Run

1. Install Python 3.8+ and MySQL Server
2. Set up the MySQL database and tables (SQL file in project)
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure API keys in `config/settings.py`
5. Run the application:
   ```bash
   python main.py
   ```

---

## 🧪 System Requirements

- Windows OS (with webcam support)
- Python 3.8 or later
- MySQL Server 8.0
- Internet (for SendGrid API)
- At least 8 GB RAM recommended

---

## 👥 Team Members

- Taha Manshoor (23-NTU-CS-1213)  
- Muhammad Zain Ul Abidin (23-NTU-CS-1200)  
- Muhammad Talha (23-NTU-CS-1195)

---

## 📄 License

This project is for educational purposes only.  
You are free to use or modify it for non-commercial use.

---

## 🔗 GitHub Repository

[View on GitHub](https://github.com/Tahadar7/Attend-Smart-Facial-Recognition.git)
