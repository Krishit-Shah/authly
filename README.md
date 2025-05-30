# 🔐 Authly – Secure Auth System (MERN)

> A full-stack authentication system with Email OTP verification, password reset, JWT protection, and clean UI using Bootstrap.

## 🚀 Features

- 🔐 User Signup + Login with JWT
- 📧 OTP Verification via Email during Signup
- 🛡️ Protected Dashboard (Private Route)
- 🔁 Forgot Password with Email Reset Link
- 🎨 Bootstrap 5 UI + Toast Notifications
- 🔒 Secure Password Hashing using bcrypt
- ✉️ Nodemailer-based Email Service
- 🧠 Temporary in-memory store for OTP
- 🗂️ Fully structured: `frontend/` + `backend/`

---
## 🧪 How to Run the Project Locally

### 1. 📦 Clone the Repository 

```bash
git clone https://github.com/Krishit-Shah/authly.git
cd authly
```
### 2.⚙️ Backend Setup
```bash
cd backend
npm install
```
📁 Create a `.env` file inside `backend/` with the following environment variables:
```bash
PORT=5000
MONGO_URI=mongodb://localhost:27017/authly
JWT_SECRET=supersecretkey
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
CLIENT_URL=http://localhost:3000
```

🔐 Note: Use a Gmail App Password if you have 2FA enabled.

### Start the backend server:
```bash 
npm start
```
🌐 Server runs at: http://localhost:5000

### 3.💻 Frontend Setup
```bash
cd ../frontend
npm install
npm start
```
🌐 Frontend runs at: http://localhost:3000

## 4.📦 Installed Dependencies

### 🔧 Backend

- express
- mongoose
- dotenv
- bcryptjs
- jsonwebtoken
- nodemailer
- cors

```bash
npm install express mongoose dotenv bcryptjs jsonwebtoken nodemailer cors
```

### 💻 Frontend
- react
- react-dom
- react-router-dom
- axios
- react-toastify
- bootstrap
```bash
npm install react react-dom react-router-dom axios react-toastify bootstrap
```
---

## 🛠️ Tech Stack

| 🔧 Frontend   | ⚙️ Backend | 🔐 Security | 🧰 Tools |
|--------------|------------|-------------|-------------|
| React        | Node.js    | JWT         | Toastify    |
| Bootstrap 5  | Express    | Bcrypt.js   | Nodemailer  |
| React Router | MongoDB    | OTP Emails  | Dotenv      |

## 👨‍💻 Author
Krishit Shah
- A complete MERN stack authentication solution built with a focus on security, scalability, and clean architecture.

## 📄 License
- This project is free to use for learning and educational purposes.

## 📝 Contributing
- Contributions are welcome. Please submit a pull request with your changes.

## 🚨 Issues
- Please report any issues or bugs in the `issues` section.
## 📈 Future Development

- 🔐 Google OAuth Login using `react-oauth/google`  
- 🌗 Light/Dark Mode toggle with persistent theme storage  
- 🧩 Admin-only dashboard with role-based access control  
- 📱 Fully mobile-optimized layout using Bootstrap grid  
- 💬 Custom error handling with user-friendly messages  
- 🔁 Resend OTP with cooldown + expiration UI  
- 🧾 In-app activity logs (user actions & login history)  
- 🌍 Deployment to Render (backend) + Vercel (frontend) with custom domain  
- 🧠 Migration from in-memory store to Redis for OTP in production
