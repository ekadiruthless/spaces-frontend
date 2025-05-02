# 🚀 Spaces — A Real-Time Collaboration Platform (Frontend)

**Spaces** is a real-time collaboration platform for academic use, designed for project-based communication between **students** and **supervisors** at Teesside University.

> This is the frontend application built with React, TypeScript, Tailwind CSS, and Vite.

---

## 🌐 Live Demo

🧪 [Try the app live](https://spaces-frontend-omega.vercel.app)

### 🔐 Demo Login

Use the following credentials to explore the platform without signing up:

- **Email:** `q2115884@live.tees.ac.uk`  
- **Password:** `Ruthless11.`

---

## 📌 University Email Requirement

Only users with a **Teesside University email** (`@live.tees.ac.uk`) can register.

During registration, users must select their role:

- 👨‍🏫 **Supervisor**
- 🎓 **Student**

---

## 🛠️ Built With

Frontend stack:

- ![React](https://img.shields.io/badge/React.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
- ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
- ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

---

## ✨ Key Features

- 🔐 University-only email registration
- 👥 Role-based onboarding (Supervisor or Student)
- ⚡  OTP verification
- 🧘 Responsive User Interface

---

## ⚙️ How To Run The Project Loaclly

### 1. Clone the repository or download and open the ZIP file

```bash
git clone https://github.com/prosper20/spaces-frontend.git
cd spaces-frontend
```

### 2. Install dependencies

```bash
yarn install
```

> Make sure [Yarn](https://classic.yarnpkg.com/en/docs/install) and [Node.js](https://nodejs.org/) (v14 or higher) are installed.

### 3. Set up environment variables

Create a `.env` file in the root directory and add the following:

```env
VITE_API_URL=https://spaces-frontend-omega.vercel.app
VITE_APP_DOMAIN=https://spaces-frontend-omega.vercel.app
```

> These values are used to communicate with the backend and define the app’s domain origin.

### 4. Start the development server

```bash
yarn dev
```

Visit:  
📍 `http://localhost:3000`

---

## 🧩 Project Structure

```bash
spaces-frontend/
├── src/
│   ├── components/      # Reusable UI components
│   ├── pages/           # Route-level pages
│   └── utils/           # Utility functions
├── public/              # Static assets
├── .env                 # Environment variables
└── README.md
```

---

## 🧪 Troubleshooting

- Ensure all dependencies are installed (`yarn install`).
- Make sure you're using a compatible Node.js version.
- Double-check the `.env` file values and formatting.
- Confirm that the backend is reachable at `VITE_API_URL`.

---

