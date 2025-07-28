# LMS-PROJECT
# 🧠 Brainiacs – Online Course Learning System (LMS)

A full-featured online course platform built with **React.js**, **Node.js**, **Express**, **MongoDB**, and **Clerk** for modern authentication. Designed for both **students** and **teachers**, this system supports role-based dashboards, video-based course creation, progress tracking, and secure user management.

---

## 🌐 Live Demo

🔗 https://lms-project-theta-beryl.vercel.app/

*You can add this link to appear on the right side of your GitHub repo via:*  
**Repo → Settings → General → About → Website → Add your link**

! https://github.com/Junaid-18/Braniacs-Mernstack.git

---



---

## 🚀 Features

### 👨‍🏫 Teacher
- Add, update, delete courses
- Upload video playlists with thumbnails & tags
- View ratings and feedback

### 🎓 Student
- Browse and enroll in courses
- Track learning progress
- Wishlist courses and rate them

### 🔐 Authentication
- OAuth-based login with Clerk
- Role-based access: Student / Teacher
- Secure session handling

---

## 🛠️ Tech Stack

| Layer      | Technology            |
|------------|------------------------|
| Frontend   | React.js, Tailwind CSS |
| Routing    | React Router           |
| Video      | React Player           |
| Backend    | Node.js, Express.js    |
| Database   | MongoDB (with Mongoose)|
| Auth       | Clerk                  |

---

## 📂 Project Structure

```
LMS-PROJECT/
├── client/          # React frontend
│   └── src/
├── server/          # Node + Express backend
│   └── models/
│   └── controllers/
│   └── routes/
├── screenshots/     # UI images for README
└── README.md
```

---

## 🧪 Functional Modules

- ✅ Course Management (CRUD)
- ✅ Video Playback + Resume
- ✅ Progress Tracking & Storage
- ✅ Wishlist System
- ✅ Student Feedback
- ✅ Notifications
- ✅ Mobile Responsive UI

---

## 🔮 Future Enhancements

- 🧠 Gamification (XP, Badges, Leaderboards)
- 🧾 Certificate Generation + Blockchain Verification
- 💬 Live Sessions via Zoom or Jitsi
- 💳 Payment Integration (Stripe/PayPal)
- 📊 Instructor Analytics Dashboard

---

## ⚠️ Limitations

- No admin dashboard yet
- Monetization not integrated
- No live chat/discussions
- Internet required (due to Clerk)
- Only video-based courses (no PDFs/quizzes yet)

---

## ⚙️ How to Run Locally

### 🔗 Clone the Repo

```bash
git clone https://github.com/Junaid-18/Braniacs-Mernstack.git
cd LMS-PROJECT
```

### 📦 Install Dependencies

```bash
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
```

### 🔐 Environment Setup

Create `.env` files in both `client/` and `server/` with these variables:

```env
# client/.env
VITE_CLERK_PUBLISHABLE_KEY=your_public_key
VITE_CLERK_FRONTEND_API=your_frontend_api

# server/.env
CLERK_SECRET_KEY=your_clerk_secret
MONGO_URI=your_mongo_db_url
PORT=5000
```

### ▶️ Run the Project

```bash
# Run frontend
cd client
npm run dev

# Run backend
cd ../server
npm run dev
```

---

## 👨‍💻 Authors

- Muhammad Junaid – `22-NTU-CS-1200`
- Muhammad Umair – `22-NTU-CS-1211`
- Muhammad Safwan – `22-NTU-CS-1207`

---

## 📜 License

This project is created as part of the final year project at **National Textile University, Faisalabad** and is intended for educational purposes only.

---


