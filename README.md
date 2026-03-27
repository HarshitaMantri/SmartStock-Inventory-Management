# Smart Stock Inventory System

A comprehensive inventory management system built with a **FastAPI** backend and a **React (Vite)** frontend. This application allows for user authentication, product management, and sales reporting.

## 🚀 Features

-   **User Authentication**: Secure signup and login functionality using JWT and SQLite.
-   **Inventory Management**: Create, read, update, and delete products (stored in MongoDB).
-   **Reporting**: View sales reports and analytics.
-   **Responsive Design**: Built with React and modern CSS for a seamless user experience.

It provides a modern UI with powerful backend support and optional AI assistance for better usability.

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React (Vite)
- JavaScript
- CSS

### 🔹 Backend
- Flask (Python)
- REST API

### 🔹 Database
- MongoDB (NoSQL)

### 🔹 Other Tools
- JWT Authentication
- SMTP (Email alerts)
- Optional OpenAI API (Smart Assistant)

---

## ✨ Features

### 🔐 Authentication
- User Signup & Login
- JWT-based authentication
- Password reset via email
- Role-based access (Admin/User)

---

### 📦 Inventory Management
- Add, update, delete products
- Manage stock levels
- Categories and suppliers
- Stock thresholds (min, max, reorder)

---

### 🔄 Transactions
- Record purchases (stock in)
- Record sales (stock out)
- Maintain transaction history

---

### 🚨 Low-Stock Alerts
- Detect products below threshold
- Email notifications
- Admin test email feature

---

### 📊 Reports
- Generate reports by date/type
- Export as CSV & PDF

---

### 📈 Sales Analytics
- Dashboard with charts
- Sales insights

---

### 🤖 Smart Assistant
- Chat-based help system
- Keyword-based + AI responses

---

## 🏗️ Project Structure


smartstock/
│
├── frontend/ # React frontend
├── backend/ # Flask backend
│ ├── routes/ # API routes
│ ├── utils/ # Email/SMS services
│ ├── database.py # DB connection
│ └── main.py # App entry point
│
├── .env # Environment variables
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/smartstock.git
cd smartstock
2️⃣ Backend Setup
cd backend
pip install -r requirements.txt
cp .env.example .env
python main.py
3️⃣ Frontend Setup
cd frontend
npm install
npm run dev
4️⃣ Start MongoDB
mongod


**🔑 Environment Variables (.env)**
MONGO_URL=mongodb://127.0.0.1:27017
DB_NAME=smartstock_db
SECRET_KEY=your_secret_key

MAIL_USERNAME=your_email
MAIL_PASSWORD=your_app_password
MAIL_SERVER=smtp.gmail.com
MAIL_PORT=587

OPENAI_API_KEY=your_api_key (optional)

 ##🔗 API Endpoints (Sample)
Endpoint	Description
/api/auth/login	User login
/api/auth/register	User signup
/api/products	Product CRUD
/api/transactions	Sales/Purchase
/api/reports	Reports
/api/assistant/chat	Smart assistant

 ##🧠 How It Works
User logs in → JWT authentication
Frontend sends requests to backend
Backend processes logic & interacts with MongoDB
Alerts triggered when stock is low
Reports & analytics generated dynamically

##🎯 Use Cases 
Retail shops
Warehouses
Small businesses
Inventory tracking systems

##🚀 Future Enhancements
Mobile app integration
Advanced analytics (AI predictions)
Barcode scanning
Multi-warehouse support

##👩‍💻 Author
Harshita Mantri
 Python Backend Developer

##⭐ Contribution

Feel free to fork, contribute, and improve the project!

 ##📌 License

This project is for educational purposes.

