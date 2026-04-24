# 🎓 Attend Smart <img src="https://github.com/sheikhzainfiaz/Attend_Smart/blob/3d5e993469f5d7125432527a997372cd642babe5/assets/logo.png" alt="Attend Smart Logo" width="60"/>

**Attend Smart** is a **face recognition–based attendance management system** built with **Python**.
It automates attendance tracking using real-time facial recognition, ensuring **accuracy, security, and efficiency** for educational institutions.

Originally developed with integration for **National Textile University (NTU)**, the system is **fully adaptable** for other institutions.

---

## 🧠 Project Overview

The system captures real-time video via webcam, detects and recognizes student faces, and marks attendance in a **MySQL database**.

It supports **role-based access (Admin & Teacher)** and provides tools to manage students, courses, and attendance reports efficiently.

---

## 🚀 Features

### 🎯 Face Recognition Attendance

* Built using `face_recognition` and OpenCV
* Real-time face detection & verification
* High accuracy attendance marking

### 🔐 Role-Based System

* Admin & Teacher login
* Secure authentication with validation
* Manual attendance editing support

### 🏫 University Validation

* Validates users against official university records
* Designed for NTU but customizable

### 📧 Email Notifications (SendGrid)

* Teacher credentials sent on account creation
* Login alerts for security
* Attendance reports via email

### 📊 Reports & Export

* Export attendance for any date
* Formats supported:

  * Excel (via pandas)
  * CSV
  * PDF (via reportlab)

### ⚡ Fast & Modern UI

* Built with **Flet**
* Responsive and user-friendly interface

### 🔊 Extra Features

* Audio confirmation on successful recognition
* Attendance analytics & logs
* Face encodings stored using Pickle

---

## 🛠 Tech Stack

| Component            | Technology                       |
| -------------------- | -------------------------------- |
| **Language**         | Python 3.8+                      |
| **Database**         | MySQL Server 8.0                 |
| **UI Framework**     | Flet                             |
| **Face Recognition** | face_recognition, OpenCV         |
| **Email Service**    | SendGrid API                     |
| **Libraries**        | NumPy, Pillow, Pandas, ReportLab |

---

## 📦 Requirements

```txt
flet==0.21.0
opencv-python
face_recognition
numpy
Pillow
mysql-connector-python
sendgrid
pandas
reportlab
python-dotenv
```

---

## 📁 Project Structure

```
main.py            # Application entry point
face_recognition/  # Face detection & encoding logic
ui/                # Flet UI components
database/          # MySQL connection & queries
utils/             # Helper functions & utilities
attendance/        # Attendance handling & export
config/            # API keys & system settings
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/sheikhzainfiaz/attend_smart.git
cd attend_smart
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Setup MySQL Database

* Create a database
* Import `.sql` file from `database/` folder

### 4️⃣ Configure Environment Variables

For SendGrid:

```bash
export SENDGRID_API_KEY="your_api_key_here"
```

Or create a `.env` file:

```
SENDGRID_API_KEY=your_api_key_here
```

### 5️⃣ Run Application

```bash
python main.py
```

---

## 📸 Screenshots

### 🔐 Login Page

![Login](https://raw.githubusercontent.com/sheikhzainfiaz/Attend_Smart/cba5b2ef5047636d8ea26e6af4c696d06cb2b1a7/Screenshot%202025-08-13%20113556.png)

---

### 📊 Dashboard

![Dashboard](https://raw.githubusercontent.com/sheikhzainfiaz/Attend_Smart/35d1d1bfac1cb830098931793912bc3c34721616/Screenshot%202025-08-13%20114104.png)

---

### 📥 Export Attendance

![Export](https://raw.githubusercontent.com/sheikhzainfiaz/Attend_Smart/35d1d1bfac1cb830098931793912bc3c34721616/Screenshot%202025-08-13%20114001.png)

---

## 📧 Email Notification Flow

* **On Teacher Creation** → Credentials sent via email
* **On Login** → Security notification email
* **Reports** → Sent directly via SendGrid

---

## 🧪 System Requirements

* Windows OS (Webcam required)
* Python 3.8+
* MySQL Server 8.0
* Internet connection (for SendGrid)
* Recommended: 8GB RAM

---

## 👥 Team Members

* **Taha Manshoor**
* **Muhammad Talha**
* **Muhammad Zain Ul Abidin**

---

## 📜 License

This project is for **educational purposes**.
You are free to use and modify it for **non-commercial use**.

```
⚠️ Do not misuse this project
```

---

## 🔗 GitHub Repository

👉 [https://github.com/sheikhzainfiaz/attend_smart](https://github.com/Tahadar7/Attend-Smart-Facial-Recognition)

---
