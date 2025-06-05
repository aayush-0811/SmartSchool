# 🎓 SmartSchool - School Management System

**SmartSchool** is a full-featured School Management System designed to streamline administrative operations, simplify student and staff management, and enhance communication between stakeholders.

> 🔗 **Live Demo**: [smart-school-opal.vercel.app](https://smart-school-opal.vercel.app/)

---

## 🛠️ Tech Stack

- **Frontend**: React, Redux, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose ODM)
- **Authentication**: JWT-based Auth System
- **Deployment**: Vercel (Frontend) & Render/Other (Backend)

---

## 👥 User Roles

1. **Admin**
   - Manage teachers and students
   - Assign classes
   - Monitor attendance and grades

2. **Teacher**
   - Take and update attendance
   - Record and update student grades
   - View class lists and student records

3. **Student**
   - View attendance records
   - View grades and feedback
   - Update personal profile

---

## 🚀 Features

- ✅ Secure login/signup with role-based access
- ✅ Manage student and teacher records
- ✅ Attendance tracking per subject/class
- ✅ Grade entry and performance tracking
- ✅ Responsive and mobile-friendly UI
- ✅ Modern dashboard for each user role
- ✅ Protected routes and token handling
- ✅ Error handling and validation

---

## 📸 Screenshots

> Include screenshots or a short walkthrough GIF here for better engagement.

---

## 📁 Folder Structure
client/            # React frontend
│
└───src/
├── components/
├── pages/
├── redux/
└── utils/

server/            # Express backend
│
└───routes/
└───controllers/
└───models/
└───middleware/
└───config/

---

## 🧪 Getting Started Locally

### Prerequisites

- Node.js
- MongoDB (local or cloud e.g. MongoDB Atlas)

### Clone and Setup

```bash
git clone https://github.com/your-username/smartschool.git
cd smartschool

cd server
npm install
# Create .env file
touch .env

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

cd client
npm install
npm run dev
