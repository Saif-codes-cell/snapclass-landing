   # 🎓 SnapClass AI

![Python](https://img.shields.io/badge/Python-3.11-blue)

![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red)

![Supabase](https://img.shields.io/badge/Database-Supabase-green)

![License](https://img.shields.io/badge/License-MIT-yellow)


### AI-Powered Smart Attendance System using Face Recognition & Voice Authentication

Mark attendance securely with Artificial Intelligence.
Built using Python, Streamlit, Supabase, Face Recognition, and Voice Authentication.

🌐 **Live Demo:** https://your-demo-link.streamlit.app

💻 **Landing Page:** https://your-vercel-link.vercel.app

⭐ If you like this project, consider giving it a star!


-------------------------------------------------------------
               SNAPCLASS AI

AI Attendance Management System

Face Recognition
Voice Authentication
QR Enrollment
Teacher Dashboard
Student Dashboard

Powered by Python + Streamlit + Supabase
-------------------------------------------------------------


## 📖 About the Project

SnapClass AI is an AI-powered attendance management system that replaces traditional attendance methods with intelligent authentication.

The application combines Face Recognition and Voice Authentication to verify students before recording attendance, making the process faster, more secure, and more reliable.

The project includes dedicated dashboards for students and teachers, QR-based subject enrollment, attendance reports, and a responsive landing page.


## ✨ Features

- 👤 Face Recognition Authentication
- 🎤 Voice Authentication
- 📚 Subject Enrollment
- 📱 QR Code Joining
- 👨‍🏫 Teacher Dashboard
- 👨‍🎓 Student Dashboard
- 📊 Attendance Reports
- ☁️ Supabase Database Integration
- 🌐 Streamlit Deployment
- 🚀 Responsive Landing Page


## 🛠 Tech Stack

### Frontend
- HTML
- CSS
- JavaScript
- Streamlit

### Backend
- Python

### Database
- Supabase

### AI Libraries
- face_recognition
- OpenCV
- NumPy
- Librosa
- Resemblyzer

### Deployment
- Streamlit Cloud
- Vercel

### Version Control
- Git
- GitHub



## 🏗️ Project Architecture

  User
   │
   ▼
Landing Page (Vercel)
   │
   ▼
Streamlit Application
   │
   ├── Face Recognition
   ├── Voice Authentication
   ├── Attendance Module
   ├── Teacher Dashboard
   └── Student Dashboard
            │
            ▼
         Supabase
```



## 📸 Screenshots


### Landing Page

![Landing](assets/screenshots/landing.png)

---

### Student Dashboard

![Student](assets/screenshots/student_dashboard.png)

---

### Teacher Dashboard

![Teacher](assets/screenshots/teacher_dashboard.png)

---

### Attendance

![Attendance](assets/screenshots/attendance.png)


## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Saif-codes-cell/SnapClass
```

Move into the project

```bash
cd SnapClass-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

Create a `.streamlit/secrets.toml` file and add your Supabase credentials.

Run the application

```bash
streamlit run app.py
```

## 📂 Folder Structure

```text
SnapClass-AI/
├── assets/
│   └── screenshots/
├── src/
├── app.py
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```



## 🚀 Future Enhancements

- 📊 Advanced attendance analytics and dashboards
- 📧 Email notifications for attendance updates
- 🌙 Dark mode support
- 📱 Improved mobile responsiveness
- 🛡️ Face anti-spoofing for enhanced security
- 👨‍💼 Admin dashboard for institution-wide management
- 📚 Multi-class and multi-department support
- 📄 Export attendance reports as PDF and Excel
- 🔔 Real-time attendance notifications
- 🐳 Docker support and CI/CD pipeline



## 💡 Challenges & Learnings

During the development of SnapClass AI, I worked through several real-world challenges including:

- Configuring AI libraries
- Deploying ML applications
- Managing cloud databases
- Integrating face and voice authentication
- Debugging deployment issues
- Optimizing application performance

This project strengthened my practical skills in Python, AI integration, cloud deployment, and full-stack application development.


## 👨‍💻 Author

**Saif Chogle**

B.Sc. Computer Science Student

AI & Machine Learning Enthusiast

GitHub:
https://github.com/Saif-codes-cell/SnapClass

LinkedIn:
https://linkedin.com/in/saif-chogle



## 📜 License

This project is licensed under the MIT License.


## 🎥 Demo

### 🌐 Live Demo
https://saif-snapclass.streamlit.app

### 🏠 Landing Page
https://snapclass-landing-one.vercel.app


## 🙏 Acknowledgements

This project was inspired by the idea of making classroom attendance smarter through Artificial Intelligence.

Special thanks to the open-source community and the libraries that made this project possible.


## 🤖 AI Components

- Face Recognition using face_recognition
- Voice Authentication using Resemblyzer
- Image Processing with OpenCV
- Audio Feature Extraction using Librosa