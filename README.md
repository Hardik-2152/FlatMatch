# 🏠 FlatMatch

FlatMatch is a full-stack property rental platform designed to connect landlords with potential tenants seamlessly. It features role-based dashboards and a unique compatibility scoring algorithm that matches flatmates based on shared lifestyle habits and constraints.

## ✨ Features

- **Role-Based Access**: Dedicated workflows and permissions for both Landlords and Tenants.
- **Advanced Filtering**: Fast, robust PostgreSQL queries to filter properties by location and budget.
- **Smart Compatibility**: Custom algorithm to match potential flatmates based on sleep schedules, cleanliness, and lifestyle habits.
- **Secure Authentication**: End-to-end security using JSON Web Tokens (JWT) and bcrypt password hashing.
- **Responsive UI**: A modern, interactive frontend built with React and managed via the Context API.

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Context API, HTML/CSS
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL
- **Authentication**: JWT, bcryptjs

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- PostgreSQL installed and running locally

### 1. Backend Setup
Open a terminal and navigate to the backend folder:
```bash
cd backend
npm install
```
Create a `.env` file inside the `backend` directory with your database credentials:
```env
DB_USER=postgres
DB_PASSWORD=your_database_password
DB_HOST=localhost
DB_PORT=5432
DB_NAME=flatmatch
JWT_SECRET=your_super_secret_key
```
Start the backend server (it will automatically create the required database tables):
```bash
node index.js
```

### 2. Frontend Setup
Open a new, separate terminal and navigate to the frontend folder:
```bash
cd frontend
npm install
npm run dev
```
The application will launch in your browser at `http://localhost:5173`.

---

*Designed and developed as a collaborative full-stack project.*
