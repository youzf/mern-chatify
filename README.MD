<h1 align="center">✨ Full-Stack Chat App with Auth & Emails ✨</h1>

![Demo App](/frontend/public/screenshot-for-readme.png)

This project is a full-stack web application built from the ground up with modern technologies, focusing on real-time communication, authentication, and a smooth user experience. It demonstrates best practices in backend security, frontend design, and deployment workflow — making it a solid foundation for scalable web apps.

🔥 Key Features:

- 🔐 Custom JWT Authentication – Secure login system without relying on third-party providers.
- ⚡ Real-time Messaging with Socket.io – Instant chat experience with live updates.
- 🟢 Presence Indicators – See who’s online or offline in real time.
- 🔔 Notifications & Typing Sounds – Engaging chat interactions with toggle controls.
- 📨 Automated Welcome Emails – Sent on signup via Resend.
- 🗂️ Image Uploads via Cloudinary – Simple and reliable media handling.
- 🧰 REST API (Node.js + Express) – Well-structured and scalable backend.
- 🧱 MongoDB Database – Robust NoSQL storage for persistence.
- 🚦 API Rate-Limiting (Arcjet) – Protects against abuse and ensures reliability.
- 🎨 Modern UI – Built with React, Tailwind CSS, and DaisyUI for a clean and responsive design.
- 🧠 State Management – Powered by Zustand for simplicity and performance.
- 🧑‍💻 Git & GitHub Workflow – Branching, pull requests, and merges for team collaboration.
- 🚀 Easy Deployment – Free-tier friendly hosting with Sevalla.

---

## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
