# PulseChat 💬⚡

PulseChat is a **modern, full-stack chat application** built with the MERN stack, designed to be lightning-fast, scalable, and developer-friendly. It’s not just another chat app it’s a playground where cutting-edge backend architecture meets sleek, modular frontend design.

---

## 🚀 Tech Stack

* **Frontend:** React (with Vite) + TailwindCSS + shadcn/ui
* **Backend:** Node.js + Express.js
* **Database:** MongoDB with Mongoose ORM
* **Authentication:** JWT (JSON Web Token) for secure login & session management
* **State Management:** Redux Toolkit
* **Others:** TanStack Query for efficient server state handling, EncoreJS for PDF generation (future extension)

---

## 🛠️ How It Was Built

The project was structured with a **clear separation of concerns**:

* The **server folder** houses all backend logic, routes, and database models.
* The **client folder** is dedicated to the React-powered UI.
* Shared conventions and modularization were enforced to keep the codebase maintainable.

Starting with a barebones Express server, MongoDB integration was added using Mongoose for schema modeling. A `User` model forms the backbone of authentication, while dedicated routes (`/register`, `/login`) keep API endpoints clean and scalable. On the frontend, React’s component-driven architecture powers the interface, styled with Tailwind for rapid, responsive design.

---

## 🎯 Why It Was Made This Way

PulseChat wasn’t built with shortcuts it was architected to demonstrate **real world production standards**:

* **MongoDB** was chosen for its document flexibility, perfect for storing chat messages and user metadata.
* **JWT** ensures stateless, secure authentication without bloated session storage.
* **Express.js** keeps the backend lightweight yet powerful, with room to extend features like WebSockets for live messaging.
* **React + Vite** delivers a blazing-fast developer experience and near-instant reloads.
* **Redux Toolkit** eliminates boilerplate and keeps state predictable across the app.

In short, every piece of the stack was chosen deliberately: lightweight where speed mattered, powerful where scalability was critical.

---

## ⚡ How to Run Locally

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/PulseChat.git
   cd PulseChat
   ```

2. **Setup environment variables:**
   Copy `.env.example` → `.env` and add your own `MONGO_URI` + `JWT_SECRET`.

3. **Install dependencies:**

   ```bash
   cd server && npm install
   cd ../client && npm install
   ```

4. **Run the servers:**

   * Start backend:

     ```bash
     cd server && npm start
     ```
   * Start frontend:

     ```bash
     cd client && npm run dev
     ```

Visit `http://localhost:5173` and feel the pulse of real-time chat.

---

## 🌟 The Vision

PulseChat isn’t just a chat project it’s a **foundation for something bigger**: collaborative tools, real-time notifications, and future-ready integrations. Built this way, it’s not just a demo, it’s a **blueprint for modern web apps**.

---



