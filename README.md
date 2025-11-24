# 🚗 Smart Parking System – Flask Web Application

Welcome to the **Smart Parking Management System**, a full-stack web application built using **Python Flask**, **HTML Templates**, and **CSS/JS**.  
It helps users **book parking slots**, make **secure payments**, view **QR codes**, and allows admins to **manage users & bookings**.

---

## 📌 Features

### 👤 **User Features**
- Create an account & log in securely  
- Book parking slots in available areas  
- See booking history with details  
- Get a **QR code** for each booking  
- Make payment with an interactive UI  
- View & update profile  

### 🛠 **Admin Features**
- Admin dashboard with analytics  
- View all booking details  
- Manage user accounts  
- Track payments & transaction details  

---

## 📂 Project Structure
Vyshu_Project/
│
├── app.py # Main Flask application
├── init_db.py # Database initialization script
├── requirements.txt # All dependencies
│
├── templates/ # HTML Templates (Jinja2)
│ ├── admin_dashboard.html
│ ├── admin_manage_users.html
│ ├── admin_view_booking.html
│ ├── book.html
│ ├── payment.html
│ ├── payment_success.html
│ ├── profile.html
│ ├── SignUp_LogIn_Form.html
│ └── ...more templates
│
└── static/
├── css, images, icons
├── payment.css
├── parking-bg.mp4
├── uploads/ # Stored user QR codes

---
