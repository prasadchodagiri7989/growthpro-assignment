
# GrowthProAI Full Stack Intern Assignment

## 🔍 Overview
This is a simulated SEO dashboard for local businesses, built using React and Node.js.

## 🗂️ Project Structure

```
.
├── frontend/    → React + Tailwind CSS
└── backend/     → Node.js + Express API
```

## 🚀 Tech Stack
- Frontend: React, Tailwind CSS
- Backend: Node.js, Express
- Deployment (Bonus): Vercel & Render

## 🔧 Features
- Input form for business name and location
- Displays simulated Google rating, reviews, and SEO headline
- Regenerate SEO headline via a GET endpoint
- Dark mode and responsive UI

## 📡 API Endpoints

### `POST /business-data`
Returns mock rating, reviews, and headline.

### `GET /regenerate-headline?name=...&location=...`
Returns a new mock SEO headline.

## 🔗 Live Links
- Frontend (Vercel): https://your-frontend.vercel.app/
- Backend (Render): https://your-backend.onrender.com/

## 💻 Local Setup

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
npm install
node index.js
```

## 📧 Submission
Submitted by: **Your Full Name**  
Email: your@email.com  
GitHub Repo: https://github.com/yourusername/growthpro-intern-assignment
