hhhhhhhhhhhhhhhhhhhhhbbbbbbbb# 🚛 Fleet Management System

A modern, full-stack **Fleet Management System** built with **Next.js** for managing vehicles, users, and operations efficiently. This project includes route protection middleware, scalable structure, and is ready for full authentication and backend integration.

---

## 📁 Tech Stack

- **Frontend:** Next.js (App Router)
- **Backend (Coming Soon):** Node.js + Express (planned)
- **Database (Planned):** PostgreSQL + Prisma ORM
- **Auth:** `next-auth` with JWT (setup-ready)
- **Styling:** Tailwind CSS (optional)
- **Deployment:** Vercel / Docker-ready

---

## 🚦 Features

- ✅ Public and Protected Route Access
- 🔐 Middleware-based Route Protection
- 👥 Role-based Access Control (Admin/User)
- 📄 Scalable File and API Structure
- 🚀 Ready for Integration with Auth and API

---

## 📦 Project Structure

src/
│
├── app/
│ ├── page.tsx # Home (Public)
│ ├── login/page.tsx # Login Page (Public)
│ ├── dashboard/page.tsx # Protected Page
│ └── admin/page.tsx # Admin-only Page
│
├── middleware.ts # Auth Guard Middleware
└── ...

csharp
🧪 How to Test (Before Auth Integration)
Visit / – Public Home Page

Visit /login – Public Login Page

Visit /dashboard – Redirects to /login if not "logged in"

Visit /admin – Redirects to /dashboard unless user is "ADMIN"

To simulate roles, change the mock getToken() return value.

🛠️ Getting Started
1. Clone the Repo
git clone https://github.com/your-username/fleet-management-system.git
cd fleet-management-system
2. Install Dependencies
npm install
3. Run Development Server
npm run dev
Visit: http://localhost:3000

🔮 Roadmap
 Middleware Setup with Mock Token

 Integrate next-auth for real authentication

 Backend API with Express + PostgreSQL

 Admin/User Role Dashboard UI

 Vehicle Tracking, Assignment, History Logs

 Deployment with Docker/Vercel

🤝 Contribution
Contributions are welcome! Feel free to fork this project, make changes, and open a pull request.

🪪 License
BinaryHub © UwihanagneyObed
