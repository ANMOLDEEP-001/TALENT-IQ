<h1 align="center"> Full-Stack Interview Platform</h1>
<p align="center">
A modern real-time coding interview platform with video, live code execution, and collaborative features.
</p>

<p align="center">
  <img src="/frontend/public/screenshot-for-readme.png" alt="Demo App" width="90%" />
</p>

---

## ✨ Overview

This platform enables **real-time technical interviews** with an integrated coding environment, video communication, and automated evaluation system.

It is designed to simulate real-world interview scenarios while providing tools for both **interviewers and candidates**.

---

## ⚡ Key Features

### 🧑‍💻 Coding & Evaluation
- VSCode-like in-browser code editor  
- Secure code execution in isolated environment  
- Automatic evaluation using test cases  
- Instant feedback: **Success / Fail**  
- Practice problems (solo coding mode)

---

### 🎥 Real-Time Interview Experience
- 1-on-1 video interview rooms  
- Screen sharing & session recording  
- Mic & camera controls  
- Room locking (max 2 participants)

---

### 💬 Collaboration
- Real-time chat messaging  
- Live interaction during coding sessions  

---

### 📊 Dashboard & UX
- Dashboard with live stats  
- Confetti animation on success 🎉  
- Notifications on failure ❌  

---

### 🔐 Authentication & Security
- Authentication powered by **Clerk**  
- Secure API & session handling  

---

### ⚙️ Backend & Infrastructure
- REST API with **Node.js & Express**  
- Background jobs using **Inngest**  
- Data fetching & caching via **TanStack Query**  
- PR analysis & code optimization using **CodeRabbit**

---

### 🚀 DevOps & Deployment
- Git & GitHub workflow (branches, PRs, merges)  
- Deployment on **Sevalla** (free-tier friendly)

---

## 🧱 Tech Stack

| Layer        | Technology |
|-------------|-----------|
| Frontend    | React + Vite |
| Backend     | Node.js + Express |
| Database    | MongoDB |
| Auth        | Clerk |
| Video/Chat  | Stream |
| Jobs        | Inngest |
| Data Fetch  | TanStack Query |

---

## 🧪 Environment Setup

### 🔹 Backend (`/backend`)

```bash
PORT=3000
NODE_ENV=development

DB_URL=your_mongodb_connection_url

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CLIENT_URL=http://localhost:5173
```

### Frontend (`/frontend`)

```bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

VITE_API_URL=http://localhost:3000/api

VITE_STREAM_API_KEY=your_stream_api_key
```

---

## 🔧 Run the Backend

```bash

cd backend
npm install
npm run dev
```

---

## 🔧 Run the Frontend

```
bash
cd frontend
npm install
npm run dev
```
