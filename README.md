# MERN-B-2029

**Building Web Applications with the MERN Stack**
Term 5 · SST 2029 Batch · Scaler School of Technology, Bengaluru

Instructor: **[Mrinal Bhattacharya](https://github.com/mrinal1224)**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)

---

## 📖 About

This repository is the official class companion for **Term 5's MERN module**, where the batch goes from a bare `http` server all the way to a fully deployed, real-time social media application. Each `class-N` folder holds the code, notes, and exercises built live in that session.

The course is worth **3 credits**, graded across four components:

| Component | Weightage |
|---|---|
| Assignments (PSP) | 20% |
| End Term | 30% |
| Final Project | 30% |
| AI Mock Interview | 20% |

---

## 🗺️ Curriculum Roadmap

The centerpiece of the term is a 12-part build: a full-stack **Social Media App**, layered feature by feature.

| # | Session | What it covers | Status |
|---|---|---|---|
| 1 | Intro to Node.js & Backend Dev | Event-driven architecture, core modules, building a server with the raw `http` module | ✅ Done |
| 2 | Introduction to Express | Express fundamentals, routing, HTTP methods | ✅ Done |
| 3 | Intro to MongoDB & CRUD | Connecting Node to MongoDB via Mongoose, full CRUD operations | ⏳ Upcoming |
| 4 | MVC Architecture | Structuring backend code with Model-View-Controller for scalability | ⏳ Upcoming |
| 5 | Social App #1 — Setup | Scaffolding the full-stack app: React frontend + Express backend | ⏳ Upcoming |
| 6 | Social App #2 — DB & Models | MongoDB models for `User` and `Post`, validating data flow | ⏳ Upcoming |
| 7 | Social App #3 — Auth | JWT-based authentication & authorization, protected routes | ⏳ Upcoming |
| 8 | Social App #4 — Controllers & Middleware | Reusable controllers, custom middleware, Cloudinary image uploads | ⏳ Upcoming |
| 9 | Social App #5 — Posts API | Create/read/delete post APIs wired into a dynamic feed UI | ⏳ Upcoming |
| 10 | Social App #6 — Follow/Unfollow | Social graph features and related UI state management | ⏳ Upcoming |
| 11 | Social App #7 — Likes & Comments | Interactive like/comment APIs with real-time UI feedback | ⏳ Upcoming |
| 12 | Social App #8 — Real-time Chat I | Socket.io setup for messaging & notifications | ⏳ Upcoming |
| 13 | Social App #9 — Real-time Chat II | Optimized socket events, edge cases, message persistence | ⏳ Upcoming |
| 14 | Social App #10 — Performance | Lazy loading, code splitting, response caching | ⏳ Upcoming |
| 15 | Social App #11 — Smart Captions | Gemini API integration for AI-generated captions | ⏳ Upcoming |
| 16 | Social App #12 — Deployment | Shipping to Render/Vercel/Railway with env config & CI/CD basics | ⏳ Upcoming |

---

## 📂 Repository Structure

```
MERN-B-2029/
├── class-1(intro to node)/       # Session 1 — raw Node.js HTTP server
├── class-2(express)/
│   └── server/                   # Session 2 — Express routing & HTTP methods
└── .gitignore
```

As the term progresses, each session gets its own `class-N(...)` folder following this same pattern.

---

## 🛠️ Tech Stack

- **Runtime:** Node.js
- **Backend Framework:** Express.js
- **Database:** MongoDB + Mongoose
- **Frontend:** React
- **Auth:** JSON Web Tokens (JWT)
- **Real-time:** Socket.io
- **Media Storage:** Cloudinary
- **AI Integration:** Google Gemini API
- **Deployment:** Render / Vercel / Railway

---

## 🚀 Getting Started

Each `class-N` folder is a self-contained example. To run one:

```bash
# Clone the repo
git clone https://github.com/mrinal1224/MERN-B-2029.git
cd MERN-B-2029

# Move into the session you want to run
cd "class-2(express)/server"

# Install dependencies
npm install

# Start the server
node index.js
```

> Check inside each folder for any session-specific setup notes or environment variables.

---

## 🤝 Contributing

This repo is maintained for the SST 2029 Batch. If you're a classmate following along:

1. Fork the repo
2. Create your session folder following the `class-N(topic)` naming convention
3. Commit your work with a clear message describing what was added
4. Open a pull request

---

## 👤 Maintainer

**Mrinal Bhattacharya** — MERN Educator, Scaler School of Technology
[GitHub](https://github.com/mrinal1224)