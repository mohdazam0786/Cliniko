# 🩺 Cliniko - Doctor Appointment System

A modern and scalable **doctor appointment booking system** built using **Next.js**, **Clerk** for authentication, **NeonDB (PostgreSQL)** for relational data management, and **Vonage Video API** for secure real-time consultations.

---

## 🔥 Live Demo

🌐 [Live Site](https://cliniko-seven.vercel.app/)

---

## 🚀 Features

### 👨‍⚕️ Doctor Panel
- View upcoming appointments
- Manage availability slots
- Start secure video consultations
- Access patient history

### 👩‍💻 Patient Panel
- Browse and search doctors by specialization
- Book, reschedule, or cancel appointments
- Join real-time video calls with doctors
- View appointment history and status

### 🔐 Authentication
- Clerk-powered login/signup with email/password or OAuth (Google, GitHub, etc.)
- Role-based access: Admin, Doctor, Patient
- Secure session handling and redirects

### 📹 Video Consultation (Vonage)
- 1-on-1 secure video calls between doctor and patient
- Dynamic room/session generation via Vonage API
- End-to-end encrypted communication
- No third-party installation needed

### 🧠 Admin Panel (Optional)
- Manage users and doctors
- Monitor appointment flow and logs
- View analytics (upcoming feature)

---

## 🛠️ Tech Stack

| Tech        | Description                                   |
|-------------|-----------------------------------------------|
| **Next.js** | Fullstack React framework (App Router)        |
| **Clerk**   | Authentication & user session management      |
| **NeonDB**  | Serverless PostgreSQL (SQL database)          |
| **Prisma**  | ORM for PostgreSQL (schema modeling)          |
| **Vonage**  | Secure video API for real-time appointments   |
| **Tailwind**| Styling and layout                            |
| **Vercel**  | Deployment and hosting                        |

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/mohdazam0786/cliniko.git
cd cliniko
npm install
# or
yarn install

