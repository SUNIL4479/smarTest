# 🚀 smarTest - Online Contest Platform

A modern, high-performance web application built from scratch using a scalable and developer-friendly frontend stack.  
The project focuses on clean architecture, reusable components, fast builds, and a smooth development experience.

---

## 📌 Overview

This application is designed to be:
- Fast and lightweight
- Easy to maintain and extend
- Visually clean and responsive
- Ready for production deployment

It follows best practices for frontend development and is suitable for personal projects, portfolios, startups, or commercial products.

---
## 🌟 Features

- 👨‍💻 **Contest Management** – Create, edit, and delete contests
- 🧩 **Problem Bank** – Add custom problems with test cases
- 🧪 **Secure Code Evaluation** – Docker sandbox or Judge0
- ⏱️ **Real-Time Submissions** – Verdicts (AC, WA, TLE, RE)
- 📈 **Live Leaderboard** – Dynamic scoring system
- 🔐 **Authentication System** – Admin and participant roles
- 🎯 **Responsive UI** – Optimized for desktop and mobile

## 🛠 Tech Stack

The project is built using the following technologies:

- **Vite** – lightning-fast dev server and optimized builds
- **React** – component-based UI development
- **TypeScript** – type safety and better code reliability
- **Tailwind CSS** – utility-first styling for rapid UI design
- **shadcn/ui** – accessible and reusable UI components

---

## 📁 Project Structure

```txt
src/
├── components/     # Reusable UI components
├── pages/          # Page-level components
├── hooks/          # Custom React hooks
├── lib/            # Utility functions
├── styles/         # Global styles
├── App.tsx         # Root component
└── main.tsx        # Application entry point
```
---
## 🚀 Getting Started

Make sure **Node.js** and **npm** are installed on your system  
(Node.js installation via `nvm` is recommended).

## Clone the Repository

git clone https://github.com/SUNIL4479/smarTest.git

## Navigate to the project

cd smarTest

## install dependencies

npm install

## Run the Project

npm run dev

## Build for Production

npm run build

## 🔒 Security Measures

- All user code is executed in a secure, sandboxed environment.
- Input/output test cases are stored securely and never exposed.

---

## 🧪 To-Do / Roadmap

- [ ] Add test case generation from problem statement
- [ ] Add support for ICPC-style contest freeze
- [ ] Add team-based contests
- [ ] Add editorial/problem discussion page
- [ ] Improve mobile UX
- [ ] Dockerize entire stack

---

## 🗂 Changelog / Development Log

| Date       | Feature/Update                                      
|------------|-----------------------------------------------------
| 2025-07-15 | 🎉 Initialized project repo                          
| 2025-07-16 | 🧱 Created backend API routes for contest & problem  
| 2025-07-17 | 🖼️ Setup frontend with React + Bootstrap            
| 2025-07-18 | 🔐 Added user login/signup with JWT                 
| 2025-07-19 | ⚙️ Integrated Judge0 API for secure code execution  
| 2025-07-20 | 📈 Implemented real-time leaderboard and scoring     
| 2025-07-21 | 📦 Added Docker support for isolated code runner     
| 2025-07-22 | 🧪 Deployed full stack on Railway + Vercel           

---

## 🧠 Credits & Inspiration

- Codeforces (contest format inspiration)
- GeeksforGeeks (problem-style inspiration)
- Judge0 (open-source code execution engine)
- LeetCode (UI/UX reference)

---
