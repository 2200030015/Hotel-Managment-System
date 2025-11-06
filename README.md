# 🏨 Hotel Management System – Hotel Elite

![MERN Stack](https://img.shields.io/badge/Stack-MERN-green)
![License](https://img.shields.io/badge/License-MIT-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange)

A **full-stack Hotel Management System** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.  
Developed for **Hotel Elite** as part of the *ITPM (Information Technology Project Management)* module,  
this system aims to automate all manual hotel operations into a **centralized online platform**.

---

## 🚀 Technologies Used

- **Frontend:** React.js, HTML5, CSS3, Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose ORM)  
- **Version Control:** Git & GitHub  
- **Tools:** Postman, Visual Studio Code, npm  

---

## 💡 Project Overview

The main objective of this project is to **replace traditional manual management** with an efficient, automated, and online hotel management solution.  
It enables easy handling of customers, employees, rooms, suppliers, and inventory — all in one place.

---

## ✨ Key Features

### 🔹 Customer Management
- Register, login, and manage profiles  
- Make and track room reservations  
- View booking details and history  

### 🔹 Employee Management
- Add, edit, delete employee records  
- Manage roles, designations, and departments  
- Track attendance and work performance  

### 🔹 Room Management
- Perform CRUD operations for rooms  
- Manage room categories (Deluxe, Suite, etc.)  
- View and update room availability and pricing  

### 🔹 Supplier Management
- Manage supplier information and contact details  
- Maintain purchase records and delivery tracking  

### 🔹 Inventory Management
- Track and update stock levels  
- Low-stock alerts and restock notifications  
- Maintain supply history and consumption data  

---

## ⚙️ Installation & Setup Instructions

Follow these steps to set up and run the project locally 👇
1️⃣ Clone the Repository
git clone https://github.com/your-username/hotel-management-system.git
cd hotel-management-system

2️⃣ Setup Backend
cd backend
npm install
npm run server

3️⃣ Setup Frontend
cd frontend
npm install
npm start


🗄️ Folder Structure
hotel-management-system/
│
├── backend/
│   ├── models/          # MongoDB models (User, Room, Employee, etc.)
│   ├── routes/          # API routes
│   ├── controllers/     # Logic for handling routes
│   ├── config/          # Database and environment configuration
│   └── server.js        # Entry point of backend server
│
├── frontend/
│   ├── src/
│   │   ├── components/  # UI components
│   │   ├── pages/       # Application pages
│   │   ├── context/     # Global state management
│   │   └── App.js       # Main React app
│   └── package.json
│
└── README.md

🔐 Environment Variables
Create a .env file inside your backend folder and add the following:
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

🧪 API Endpoints Overview
| Feature   | Method | Endpoint                  | Description             |
| --------- | ------ | ------------------------- | ----------------------- |
| Customer  | POST   | `/api/customers/register` | Register new customer   |
| Customer  | POST   | `/api/customers/login`    | Login existing customer |
| Rooms     | GET    | `/api/rooms`              | Fetch all rooms         |
| Rooms     | POST   | `/api/rooms`              | Add new room            |
| Employee  | POST   | `/api/employees`          | Add employee            |
| Inventory | GET    | `/api/inventory`          | Get inventory list      |
| Supplier  | POST   | `/api/suppliers`          | Add supplier            |

📊 Future Enhancements
🧾 Generate financial and occupancy reports
🔔 Real-time notifications for bookings and low stock
📱 Develop mobile app using React Native
🧠 AI-based room recommendation system
💬 Live chat support integration

🧑‍💻 Contributor
Sowmya Perla
Frontend Developer & Project Lead

💬 Contact
For any queries or collaborations:
📧 2200030015cseh@gmail.com
🔗 https://www.linkedin.com/in/sowmya-perla/
