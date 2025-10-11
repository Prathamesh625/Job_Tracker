🧩 AI Job Tracker

Track your job applications and get smart AI suggestions to improve your resume keywords.

🚀 Live Demo

🔗 Frontend: https://your-frontend-link.vercel.app

⚙️ Backend API: https://your-backend-link.onrender.com

📖 Overview

AI Job Tracker is a fullstack web app that helps users manage their job applications and improve their resumes.
It allows users to log jobs, track application status, and (optionally) analyze job descriptions with AI to extract important keywords.

🧱 Tech Stack
Frontend

React (Vite)

React Hook Form

Axios

Tailwind CSS

Backend

Node.js

Express.js

Prisma ORM (SQLite / PostgreSQL)

JWT Authentication

OpenAI API (optional)

✨ Features

✅ Add, update, and delete job applications
✅ Filter jobs by status or company
✅ View dashboard with all jobs
✅ AI-based job description analysis (optional)
✅ Fully responsive UI
✅ Deployed backend and frontend

🗂️ Project Structure
job-tracker/
├── backend/
│   ├── src/
│   │   ├── index.js
│   │   ├── routes/
│   │   └── prisma/
│   ├── package.json
│   └── prisma/schema.prisma
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── api/
│   ├── package.json
│   └── vite.config.js
│
└── README.md

⚙️ Setup Instructions
1. Clone Repo
git clone https://github.com/yourusername/job-tracker.git
cd job-tracker

2. Setup Backend
cd backend
npm install
npx prisma migrate dev
npm run dev


Create a .env file in /backend with:

DATABASE_URL="file:./dev.db"
OPENAI_API_KEY=your_openai_key_here
JWT_SECRET=your_secret_key

3. Setup Frontend
cd ../frontend
npm install
npm run dev

🌐 Deployment

Frontend: Vercel / Netlify

Backend: Render / Railway

Database: SQLite (local) or PostgreSQL (for production)

📸 Screenshots
Dashboard	Add Job

	
💡 Future Enhancements

Add user authentication

Add job status visualization using charts

Email reminders for follow-ups

Resume upload and parsing

👨‍💻 Author

Prathamesh Thorat
🌐 Portfolio

🔗 LinkedIn

💻 GitHub
