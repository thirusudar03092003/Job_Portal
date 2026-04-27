# 🚀 Job Portal — Full Stack Application (React + Django REST API)

## 📘 Project Overview

**Job Portal** is a full-stack web application built using **React (Vite + Tailwind CSS)** on the frontend and **Django + Django REST Framework** on the backend.

The application allows users to:

* Register and login
* View available job listings
* Apply for jobs

The backend handles authentication, API logic, and database operations using **PostgreSQL**, while the frontend provides a responsive and user-friendly interface.

---

## ✨ Features

* ✅ User Registration (React form + API)
* ✅ User Login & Authentication
* ✅ View Job Listings
* ✅ Apply for Jobs
* ✅ Prevent Duplicate Applications
* ✅ PostgreSQL Database Integration
* ✅ REST API Architecture
* ✅ API Testing with Postman
* ✅ Responsive UI using Tailwind CSS
* ✅ Navigation using React Router

---

## 🛠 Tech Stack

| Layer    | Technology                             |
| -------- | -------------------------------------- |
| Frontend | React (Vite)                           |
| Styling  | Tailwind CSS                           |
| Routing  | React Router DOM                       |
| Backend  | Django                                 |
| API      | Django REST Framework                  |
| Database | PostgreSQL (Production) & SQLite (Dev) |
| Tools    | Postman, Git, GitHub                   |

---

## 📁 Project Structure

```bash id="tq6h8v"
job-portal/
├── backend/           # Django backend
│   ├── manage.py
│   ├── backend/
│   └── requirements.txt
│
├── frontend/          # React frontend (Vite)
│   ├── src/
│   └── package.json
│
├── README.md
└── LICENSE
```

---

## ⚙️ Installation & Setup

### 🔹 1. Clone the Repository

```bash id="5y1cjo"
git clone https://github.com/thirusudar03092003/Job_Portal.git
cd Job_Portal
```

---

### 🔹 2. Backend Setup (Django)

```bash id="ujp3u5"
cd backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
```

---

### 🔹 3. Configure Environment Variables

Create a `.env` file inside the backend folder:

```env id="ajuf82"
SECRET_KEY=your_secret_key
DEBUG=True

DB_NAME=your_db_name
DB_USER=your_user
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
```

---

### 🔹 4. Run Migrations

```bash id="6xw2yb"
python manage.py makemigrations
python manage.py migrate
```

---

### 🔹 5. Start Backend Server

```bash id="q7q3r1"
python manage.py runserver
```

Backend runs at:

```bash id="7v38u8"
http://127.0.0.1:8000/
```

---

### 🔹 6. Frontend Setup (React)

```bash id="6d5nhc"
cd ../frontend
npm install
npm run dev
```

Frontend runs at:

```bash id="qkqj0z"
http://localhost:5173/
```

---

## 🔗 API Endpoints

| Endpoint     | Method | Description            |
| ------------ | ------ | ---------------------- |
| `/register/` | POST   | Register a new user    |
| `/login/`    | POST   | Login user             |
| `/jobs/`     | GET    | Fetch all job listings |
| `/apply/`    | POST   | Apply for a job        |

> ⚠️ Jobs are currently created manually via Django admin or shell.

---

## 🧪 Testing with Postman

1. Register a user
2. Login
3. Fetch jobs using `/jobs/`
4. Apply for jobs using `/apply/`

---

## 🎯 Key Learnings

* 🔗 Connecting React frontend with Django REST APIs
* 🔐 Implementing authentication in Django
* 🗄 Using PostgreSQL with Django
* ⚙️ Designing REST APIs
* 🎨 Building responsive UI with Tailwind CSS
* 🌐 Managing routing in React

---

## 💡 Future Improvements

* 🔑 JWT Authentication
* 📝 Create Job API (Employer functionality)
* 🔍 Job search & filtering
* ⭐ Save / bookmark jobs
* 📊 Admin dashboard

---

## 🤝 Contribution

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📄 License

This project is licensed under the MIT License.



