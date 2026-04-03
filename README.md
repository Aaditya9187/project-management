<div align="center">
  <h1><img src="https://project-management-gs.vercel.app/favicon.ico" width="30" height="30" alt="project-management Favicon">
   Project Management</h1>
  <p>
    An open-source project management platform built with PERN stack.
  </p>
  <p>
    <a href="https://github.com/Aaditya9187/project-management/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge" alt="PRs Welcome"></a>
    <a href="https://github.com/Aaditya9187/project-management/issues"><img src="https://img.shields.io/github/issues/Aaditya9187/project-management?style=for-the-badge" alt="GitHub issues"></a>
  </p>
</div>

---

## 🔗 Live Links

Live Project Preview (Frontend): "https://project-management-workspace.vercel.app" <br/>
Live Project Preview (Backend): "https://project-management-server-matrix.vercel.app"

---

## 📖 Table of Contents

- [✨ Features](#-features)
- [🛠️ Tech Stack](#-tech-stack)

---

## 📝 Features <a name="-features"></a>

- **Multiple Workspaces:** Allow multiple workspaces to be created, each with its own set of projects, tasks, and members.
- **Project Management:** Manage projects, tasks, and team members.
- **Analytics:** View project analytics, including progress, completion rate, and team size.
- **Task Management:** Assign tasks to team members, set due dates, and track task status.
- **User Management:** Invite team members, manage user roles, and view user activity.

---

## 🛠️ Tech Stack <a name="-tech-stack"></a>

| Technology | Purpose |
|------------|---------|
| React.JS + Tailwind CSS | Frontend Development |
| Express.JS | Backend Development |
| Neon | Databse  |
| Clerk | User Authentication |
| Nodemailer + Brevo | Sending Mails Automatically |
| Vercel | Project Deployment |

---

# 🚀 Getting Started

Follow these steps to run the project locally.

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Aaditya9187/project-management.git
cd project-management
```

## 2️⃣ Install Dependencies

Install the required packages using npm for client.

```bash
cd client
npm install
```

Install the required packages using npm for server.

```bash
cd ..
cd server
npm install
```

## 3️⃣ Add Your Environment Variables

Add your environment variables for client by creating a ".env" file in the root directory of client folder.

```bash
VITE_CLERK_PUBLISHABLE_KEY=""
VITE_BASEURL=http://localhost:5000
```

Add your environment variables for server by creating a ".env" file in the root directory of server folder.

```bash
# Run Environment
NODE_ENV = "development" #Change this to production while deploying the project

# Clerk
CLERK_PUBLISHABLE_KEY=""
CLERK_SECRET_KEY=""
CLERK_WEBHOOK_SECRET=""

# Neon Database
DATABASE_URL = ""
DIRECT_URL = ""

#Inngest
INNGEST_EVENT_KEY=""
INNGEST_SIGNING_KEY=""

#SMTP Credentials
SENDER_EMAIL=""
SMTP_USER=""
SMTP_PASS=""
```

## 4️⃣ Run Your Project On Local Host

Run your project's frontend(client).

```bash
npm run dev
```

Run your project's backend(server).

```bash
npm run server
```

## 5️⃣ Open In Browser

Open your frontend(client) in browser by going to:

```bash
http://localhost:5173
```

Open your backend(server) in browser by going to:

```bash
http://localhost:5000
```

<p>🎉 Congratulations you have successfully built and deployed your project locally 🎉</p>

---

<h3 align="center">Built With 💖 And Passion By Aaditya Chhatraliya</h3>


