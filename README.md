# 📝 ToDo Web App

A full-stack **ToDo Application** built using the MERN (MongoDB, Express, React, Node.js) stack. This app allows users to register, login, and manage their personal task list with priority filtering.

---

## 🌐 Deployment Links

- **Frontend**: [https://todo-frontend-krgt.onrender.com](https://todo-frontend-krgt.onrender.com)  
- **Backend**: [https://todo-backend-2pp1.onrender.com](https://todo-backend-2pp1.onrender.com)

---

## 📌 Features

- 🔐 JWT-based user authentication (Signup/Login)
- ✅ Create, update, delete and filter tasks
- ⏱️ Task priority selection (High, Medium, Low)
- 🌈 Responsive UI with Tailwind CSS

---

## 🧑‍💻 Technologies Used

### Frontend
- React.js
- Tailwind CSS
- JavaScript (ES6)
- Render (Deployment)

### Backend
- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose
- JWT (jsonwebtoken)
- bcryptjs (Password hashing)
- dotenv
- CORS
- Render (Deployment)

---

## 🚀 Setup Instructions

### Prerequisites
- Node.js and npm installed
- MongoDB Atlas account
- Git

---

### 🔧 Backend Setup

1. **Clone the backend repo**  
   ```bash
   git clone https://github.com/SamkitJain2006/ToDo_Backend.git
   cd ToDo_Backend
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Create `.env` file in root**  
   ```env
   MONGOURL=<your-mongodb-uri>
   JWT_SECRET=<your-secret-key>
   PORT=8080
   ```

4. **Start the server**  
   ```bash
   node index.js
   ```

---

### 🎨 Frontend Setup

1. **Clone the frontend repo**  
   ```bash
   git clone https://github.com/SamkitJain2006/ToDo_Frontend.git
   cd ToDo_Frontend
   ```

2. **Install dependencies**  
   ```bash
   npm install
   ```

3. **Connect to backend**  
   In `App.js` or wherever the API is called, replace the backend URL:
   ```js
   const BASE_URL = "https://todo-backend-2pp1.onrender.com";
   ```

4. **Run the app**  
   ```bash
   npm start
   ```

---

## 🗂️ Folder Structure

```
ToDo_App/
├── backend/
│   ├── index.js
│   ├── routes/
│   ├── models/
│   └── .env
└── frontend/
    ├── src/
    │   ├── App.js
    │   ├── components/
    │   └── index.css
    └── public/
```

---

## 🧪 Testing

- Signup/Login at frontend
- Create and delete tasks
- Toggle task completion
- Filter by priority
- Logout and test protected routes

---

## 🙌 Acknowledgements

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Render](https://render.com)
- [Tailwind CSS](https://tailwindcss.com)
- [React](https://reactjs.org)
