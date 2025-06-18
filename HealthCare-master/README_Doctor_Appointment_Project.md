
# Doctor Appointment Management System

## 📌 Project Overview

The **Doctor Appointment Management System** is a full-stack web application designed to streamline the process of scheduling, managing, and tracking doctor appointments for patients and administrators. The system supports secure login for patients and doctors, real-time availability checks, appointment bookings, and appointment status management.

This project is built as part of the final year engineering curriculum at **IET Lucknow**.

---

## 🚀 Features

- 🔐 **User Authentication** for Patients and Doctors
- 🩺 **Doctor Profile Management** (Specialization, Experience, Timings)
- 📅 **Appointment Booking System** with availability checks
- ✅ **Admin Dashboard** for managing users and appointments
- 📈 **Appointment History** for patients and doctors
- 📨 **Notification Alerts** on appointment status
- 📊 **Search by Doctor Name or Specialization**

---

## 🛠️ Tech Stack

### Frontend:
- React
- Tailwind CSS

### Backend:
- Node.js
- Express.js 

### Database:
- MongoDB

---

## 📂 Project Structure (Sample)

```
doctor-appointment-system/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── App.js
│
├── README.md
├── package.json
└── .env
```

---

## 🔍 How to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Akshat0910/doctor-appointment-system.git
   ```

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   npm start
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm start
   ```

4. **Open in Browser**
   ```
   http://localhost:3000
   ```

---

## 🧪 Test Scenarios

| Module              | Test Scenario                           | Expected Outcome                            | Result     |
|---------------------|------------------------------------------|---------------------------------------------|------------|
| User Registration   | Valid user data                          | Account created successfully                | ✅ Passed  |
| User Login          | Correct credentials                      | Redirect to Dashboard                       | ✅ Passed  |
| Appointment Booking | Select available date/time               | Booking confirmed                           | ✅ Passed  |
| Admin Login         | Access to dashboard                      | View/manage appointments and users          | ✅ Passed  |

---

## 📊 Future Scope

- SMS/Email appointment reminders
- Video Consultation feature
- AI-based doctor suggestion system
- Patient medical history storage and upload

---

## 👨‍💻 Contributors

- Abhijeet  
- Akshat  
- Pankaj

---

## 📃 License

This project is for academic use only and is not intended for commercial deployment.
