# 🎓 Student Management System (MERN Stack)

A complete **Student Management System** built using the **MERN stack** (MongoDB, Express.js, React, Node.js).  
This system helps manage student information efficiently with features like adding students, editing details, deleting records, and tracking attendance.

---

## ✨ Features

### ➕ Add Students
- Add new students with:
  - Name  
  - Roll Number  
  - Gender  
  - Attendance fields (optional)

### 👀 View Students
- Display all student records
- Clean tabular UI
- Quick navigation

### ✏️ Edit Student Information
- Update any student detail
- Real-time form validation

### ❌ Delete Student Records
- Remove any student with confirmation pop-up
- Uses SweetAlert2 for smooth UI alerts

### 📋 Attendance Tracking (Optional / Extendable)
- Mark present/absent
- Future-ready structure for attendance reports

---

## 🛠️ Tech Stack

### 🌐 Frontend
- React  
- React Router  
- Axios  
- CSS  
- SweetAlert2  

### 🧩 Backend
- Node.js  
- Express.js  

### 🗄️ Database
- MongoDB (Atlas or Local)

---

## 📂 Folder Structure

student-management-system/
│
├── backend/
│ ├── server.js
│ ├── routes/
│ ├── controllers/
│ ├── models/
│ └── config/
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── App.js
│ │ └── index.js
│ └── public/
│
└── README.md


---

## 🚀 Installation & Setup (Local)

Follow the steps below to run the project on your system.

---

### 📌 1. Clone the Repository
git clone [<your-repo-url>](https://github.com/MrAlpha00/students-management-system-)
cd student-management-system-


---

# 🔧 Backend Setup (Node + Express)

### 📁 Move into backend folder
cd backend


### 📦 Install dependencies
npm install


### ⚙️ Configure Environment Variables  
Create a `.env` file:

MONGO_URI=your-mongodb-connection-url
PORT=5000

### ▶️ Start the backend server
npm start

Backend will run at:
http://localhost:5000

---

# 🎨 Frontend Setup (React)

### 📁 Move into frontend folder
cd ../frontend

### 📦 Install dependencies
npm install

### ▶️ Start the frontend
npm start

Frontend will run at:
http://localhost:3000

---

## 🔗 API Endpoints (Backend)

### 👇 Student Routes
| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /students | Fetch all students |
| POST   | /students | Add a new student |
| GET    | /students/:id | Get a student |
| PUT    | /students/:id | Update a student |
| DELETE | /students/:id | Delete a student |

---

## 🧪 Future Enhancements

### 📌 1. Attendance Reports
- Weekly, monthly, yearly attendance
- Export to PDF/Excel

### 📌 2. Search & Filter System
- Search students by name/roll number
- Filter by department, gender, attendance, etc.

### 📌 3. Authentication System (Admin)
- Admin login/logout
- Protected routes

### 📌 4. Role Management
- Admin
- Teacher

### 📌 5. Student Dashboard
- View personal details
- Attendance summary

### 📌 6. Email Notifications
- Automatic alerts when attendance drops
- Parent notification feature

### 📌 7. Dashboard Analytics
- Total students
- Performance charts
- Attendance trend graphs

---

## 🤝 Contributing
Pull requests are welcome.  
Feel free to open issues or suggest features.

---

## 📜 License
This project is open-source and available under the **apache 2.0**.

