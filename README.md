# 🩺 Student Health Passport

A simple **web application** to maintain a student's basic health information in one place.  
Users can register, log in, manage vaccination records, medical history, allergies, and appointments,  
and can **download their health passport as a PDF**.

---

## 📌 Overview

This project was developed as an academic mini project.  
It focuses on keeping important health details organised and easily sharable for students.

---

## ✨ Features

- 👤 **User Registration & Login**
  - Create a new account with name, email, and password
  - Login using registered email and password

- 🧾 **Profile Management**
  - View basic profile (name, email)
  - Update name from the profile section

- 💉 **Health Records**
  - Add vaccination records (vaccine name + date)
  - View and remove vaccination entries
  - Add / edit **Medical History**
  - Add / edit **Allergies**

- 📅 **Appointments**
  - Schedule new health check-up appointments
  - View all upcoming appointments
  - Cancel existing appointments

- 📄 **Download Health Passport (PDF)**
  - Generates a PDF using **jsPDF**
  - Includes:
    - Name & Email
    - Vaccination records
    - Medical history
    - Allergies
    - Appointments

---

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Library:** [jsPDF](https://github.com/parallax/jsPDF) (for PDF generation)  
- **Storage:** In-memory JavaScript objects (no backend/database yet)

---

## 📂 Project Structure

```text
healthpassport/
│── index.html       # Main single-page application
│── style.css        # Separated styles
│── script.js        # Separated JS logic
│── README.md        # Project documentation
│── screenshots/     # UI screenshots
