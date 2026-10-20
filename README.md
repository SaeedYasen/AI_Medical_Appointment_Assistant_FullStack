# 🏥 Hospital Appointment Chatbot (AI-Powered)

An AI-driven full-stack system designed to automate hospital appointment bookings. The chatbot replaces traditional call centers by analyzing patient symptoms using AI, determining the correct medical department, retrieving available slots, and booking appointments automatically.

> **Project Origin:** Developed as part of the *AI-Integrated Full-Stack Python Secure Development* course at **Tsofen (2025)**.

---

## 🚀 Key Features

* **🔐 Secure Authentication:** User registration and login using JWT.
* **🧠 AI Symptom Analysis:** Powered by OpenAI to process natural language descriptions and direct patients to the right medical department.
* **📅 Automated Scheduling:** Fetches real-time available slots and books appointments via GBooking API.
* **💬 Seamless Chatbot Experience:** End-to-end interactive booking flow for patients.

---

## 🛠️ Tech Stack

| Domain | Technologies |
| :--- | :--- |
| **Frontend** | React.js, HTML5, CSS3, REST API Integration |
| **Backend** | Python, Flask, JWT Authentication, RESTful APIs |
| **Database** | MongoDB / MongoDB Atlas |
| **External APIs** | OpenAI API (Symptom Analysis), GBooking API (Appointment System) |

---

## 🧠 Architecture & System Flow
User → React Frontend → Flask Backend API → MongoDB
├── OpenAI API (Symptom Analysis)
└── GBooking API (Appointment Booking)
1. **Auth:** User registers and logs in securely.
2. **Analysis:** Patient describes symptoms in plain language; OpenAI identifies the required department.
3. **Retrieval:** Backend queries GBooking API for available doctors and appointment slots.
4. **Booking:** Patient selects a slot, and the appointment is confirmed and logged into MongoDB.

---

## 👨‍💻 Key Contributions

* Developed and managed the core backend services using **Flask**.
* Implemented secure user authentication with **JWT**.
* Integrated **OpenAI API** for NLP symptom classification.
* Connected and handled external scheduling logic via **GBooking API**.
* Configured **MongoDB** schemas and database transactions.
* Worked within an Agile team environment with weekly sprints.

---

## 📜 License & Usage

This project was developed for educational purposes under the Tsofen 2025 program. Please contact the maintainer for permissions regarding usage or redistribution.
