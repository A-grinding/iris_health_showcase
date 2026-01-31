🌿 IRIS HEALTH

🏥 Smart Campus Health Management System
Built with Flutter, Dart & Firebase

<p align="center"> <img src="assets/splash.jpeg" width="220"/> </p>
🚀 About The Project

IRIS HEALTH is a role-based healthcare management application built for campus environments.

It enables seamless interaction between:

🎓 Students

🩺 Doctors

Students can book and track consultations, while doctors can manage queues and provide prescriptions — all powered by Firebase.

🎯 Key Features
👩‍🎓 Student Side

Secure Email Authentication

View Available Doctors

Live Queue Tracking

Appointment History

View Prescriptions

AI-based Doctor Suggestion (IRY Bot)

🩺 Doctor Side

Secure Role-Based Login

View Assigned Patients

See Patient Names in Queue

Write & Submit Prescriptions

Update Consultation Status

📱 App Screens
🔐 Authentication System
<p align="center"> <img src="assets/login_student.jpeg" width="250"/> <img src="assets/login_doctor.jpeg" width="250"/> </p>

Email & Password Login

Role-based routing

Firebase Authentication integration

📧 Email Verification (Firebase Auth)
<p align="center"> <img src="assets/email_verification.jpeg" width="250"/> </p>

Secure account activation

Prevents fake registrations

👨‍⚕️ Doctors Dashboard
<p align="center"> <img src="assets/doctors_list.jpeg" width="250"/> <img src="assets/filter_specialization.jpeg" width="250"/> </p>

Filter by specialization

Live queue count

Active consultations

🧑‍⚕️ Doctor – View Patients
<p align="center"> <img src="assets/doctor_patients.jpeg" width="250"/> </p>

Doctors can:

View patient names

See their position in queue

Access consultation details

📝 Doctor – Write Prescription
<p align="center"> <img src="assets/write_prescription.jpeg" width="250"/> </p>

Doctors can:

Type medical prescriptions

Submit updates to Firestore

Instantly reflect data in student history

👤 Student Profile
<p align="center"> <img src="assets/profile.jpeg" width="250"/> </p>

View consultation count

Unique student ID

Logout securely

📜 Appointment History
<p align="center"> <img src="assets/history.jpeg" width="250"/> </p>

Doctor name

Specialization

Date

Prescription notes

🤖 IRY BOT – Smart Medical Assistant
<p align="center"> <img src="assets/iry_bot.jpeg" width="250"/> </p>

Users describe symptoms and receive specialist suggestions.

Example:

“I feel feverish and have skin rashes”
→ Suggestion: Dermatologist

🏗️ Tech Stack
Technology	Usage
Flutter	Cross-platform UI
Dart	Application Logic
Firebase Authentication	Secure Login
Cloud Firestore	Real-time Database
Firebase Email Action Links	Email Verification
🧠 Architecture Overview
Flutter UI
     ↓
Firebase Authentication
     ↓
Cloud Firestore
     ├── Users Collection
     ├── Doctors Collection
     ├── Appointments Collection
     ├── Prescriptions Collection
     └── Queue Management

🔥 What Makes This Project Strong

✔ Two-Sided Role-Based System
✔ Real-Time Firestore Updates
✔ Doctor-to-Student Data Flow
✔ Prescription Management System
✔ Secure Authentication Flow
✔ Clean & Consistent UI
✔ Chatbot Feature Integration

🛠️ Installation
git clone https://github.com/your-username/iris-health.git
cd iris-health
flutter pub get
flutter run

Firebase Setup Required

Add google-services.json

Enable Email/Password Authentication

Configure Firestore Database

Apply Firestore Security Rules

📂 Required Assets Structure
/assets
   splash.jpeg
   login_student.jpeg
   login_doctor.jpeg
   email_verification.jpeg
   doctors_list.jpeg
   filter_specialization.jpeg
   doctor_patients.jpeg
   write_prescription.jpeg
   profile.jpeg
   history.jpeg
   iry_bot.jpeg

🚀 Future Enhancements

Push Notifications

Time-slot based appointment booking

Doctor availability scheduling

Admin dashboard

AI-powered chatbot upgrade

Analytics dashboard

👨‍💻 Author

Abhishek Dwivedi
Flutter & Firebase Developer
