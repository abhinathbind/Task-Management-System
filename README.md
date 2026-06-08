# Task-Management-System
 # 📋 Task Management System

Full-stack task manager with JWT auth, REST API, and PostgreSQL.

🔗 **Live:** [task-management-system-rose-delta.vercel.app](https://task-management-system-rose-delta.vercel.app)
⚡ **API:** [task-management-system-production-7f5c.up.railway.app](https://task-management-system-production-7f5c.up.railway.app)


## Stack
- **Frontend:** Next.js 16, React 19, Tailwind CSS
- **Backend:** Node.js, Express, TypeScript, Prisma
- **Database:** PostgreSQL (Railway)
- **Auth:** JWT + bcrypt
- **Deploy:** Vercel + Railway

## Features
- ✅ Register & Login
- ✅ Create, Update, Delete tasks
- ✅ Status: `TODO` → `IN_PROGRESS` → `COMPLETED`
- ✅ Search & Filter tasks

## Run Locally
```bash
# Backend
cd backend && npm install
# add .env → DATABASE_URL, JWT_SECRET, PORT=5000
npm run dev

# Frontend
cd frontend && npm install
# add .env.local → NEXT_PUBLIC_API_URL=http://localhost:5000
npm run dev
```
