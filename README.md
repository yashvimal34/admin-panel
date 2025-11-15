🧾 Admin Panel Dashboard | MERN Stack

A fully functional Admin Dashboard application built using the MERN stack with authentication, analytics, and complete product and user management.

🚀 Features
🔐 Authentication & Authorization

Login and Register with JWT-based authentication

Protected routes and token handling

Role-based access (Admin / User)

📦 Products Management

Create, Read, Update, Delete (CRUD)

Product images via image URL

Search and filters

Stock management

👥 Users Management

View all users (Admin)

Edit user details including role and avatar

Profile page for regular users to update name, email, avatar, and password

🧾 Dashboard & UI

Dashboard cards with key metrics

Responsive analytics chart

Settings page (profile fields + email notifications + theme toggle)

Mobile-friendly layout using Tailwind CSS

🗄️ Backend & Database

MongoDB + Mongoose

Secure API endpoints with Express

Password hashing and validation

Token-based session management


| Component      | Technology                         |
| -------------- | ---------------------------------- |
| Frontend       | React + Vite + Tailwind CSS        |
| Backend        | Node.js + Express.js               |
| Database       | MongoDB                            |
| Authentication | JWT                                |
| State Mgmt     | React Hooks / Context API          |
| Charts         | Recharts (or the library you used) |


root/
 ├── client/       # React frontend
 ├── server/       # Node/Express backend
 └── README.md
