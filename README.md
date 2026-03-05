# 🩺 Doctor Appointment Booking System (Prescripto)

A full-stack **Doctor Appointment Booking Web Application** that allows users to book appointments with doctors, manage profiles, and make secure payments. The platform also provides separate dashboards for **Admin** and **Doctors** to manage appointments efficiently.

---

## 🚀 Features

### 👤 User
- User registration and login
- Browse doctors by specialization
- Book appointments with available time slots
- Online payment integration
- View and manage booked appointments
- Update profile information

### 👨‍⚕️ Doctor
- Doctor login system
- View patient appointments
- Mark appointments as completed or cancelled
- Manage availability

### 🛠 Admin
- Admin dashboard
- Add and manage doctors
- View all appointments
- Cancel appointments
- Monitor system activity

---

## 🏗 Tech Stack

### Frontend
- React.js
- React Router
- Axios
- Tailwind CSS
- React Toastify

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- Multer (Image Upload)

### Payment Gateway
- Stripe

---

## 📂 Project Structure

```
doctor-appointment-app
│
├── admin        # Admin dashboard
├── backend      # Node.js + Express backend
├── frontend     # User interface (React)
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Tarun-7092/doctor-appointment-app.git
cd doctor-appointment-app
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a **.env** file inside backend and add:

```
PORT=4000
MONGODB_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret
```

Run backend:

```bash
npm run server
```

---

### 3. Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

### 4. Admin Panel Setup

```bash
cd admin
npm install
npm run dev
```

---

## 🔐 Environment Variables

The backend requires the following environment variables:

- MONGODB_URI
- JWT_SECRET
- RAZORPAY_SECRET_KEY


---

## 📈 Future Improvements

- Email notifications for appointments
- Doctor availability calendar
- Video consultation feature
- Appointment reminders

---

## 👨‍💻 Author

**Tarun Kumar**  
B.Tech Computer Science Engineering Student  

GitHub:  
https://github.com/Tarun-7092
