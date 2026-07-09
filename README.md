# 🚀 Nexcraft – AI App Builder

Build full-stack React applications from a single prompt using AI.

Nexcraft is an AI-powered application builder inspired by platforms like Bolt.new and Lovable. Users can generate complete React applications, preview them instantly, improve them using an autonomous AI agent, and manage projects through a modern dashboard.

---

## 🔗 Live Demo

🌐 Live Application

https://ai-app-builder-gi9r.vercel.app

💻 GitHub Repository

https://github.com/Pragati-coders/AI-App-Builder

---

## 📋 Table of Contents

- Overview
- Live Demo
- Screenshots
- Tech Stack
- Features
- Architecture
- Getting Started
- Environment Variables
- Database Setup
- Future Improvements
- Contributing

---

# 🌟 Overview

Nexcraft is a Full Stack Agentic AI App Builder that enables users to generate production-ready React applications through natural language prompts.

The platform combines:

- Gemini AI for code generation
- Cline SDK for autonomous code improvement
- Sandpack for live previews
- Clerk for authentication
- Supabase for database and storage
- Prisma ORM
- Arcjet rate limiting

Users can describe an application idea, and Nexcraft generates the code, installs dependencies, previews the application, and stores the project history automatically.

---

# 📸 Screenshots

## 🏠 Landing Page

[Landing Page] <img width="960" height="419" alt="landing Page" src="https://github.com/user-attachments/assets/843e542c-575a-41ca-975a-39ec11127d54" />

Modern AI-powered landing page with prompt input and authentication.

---

## 🔐 Authentication

![Authentication](./screenshots/login.png)

Secure Google and Email authentication powered by Clerk.

---

## 💻 Workspace Dashboard

![Dashboard](./screenshots/dashboard.png)

Split-screen workspace with AI chat, generated code, and project management.

---

## 👀 Live Preview

![Preview](./screenshots/preview.png)

Instant application rendering using Sandpack live preview.

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Framework | Next.js 15 |
| Language | TypeScript |
| Styling | Tailwind CSS v4 |
| UI Library | Shadcn UI |
| Authentication | Clerk |
| Database | Supabase PostgreSQL |
| ORM | Prisma |
| Storage | Supabase Storage |
| AI Model | Gemini 3.5 Flash |
| AI Agent | Cline SDK |
| Live Preview | Sandpack |
| Rate Limiting | Arcjet |
| Deployment | Vercel |

---

# ✨ Features

## 🎨 Landing Page

- Modern responsive design
- AI prompt input
- Rotating placeholder suggestions
- Pricing section
- Dark mode interface

---

## 🔐 Authentication

- Google OAuth Login
- Email Authentication
- Secure session management
- Automatic user onboarding
- Credit initialization

---

## 🤖 AI Code Generation

- Gemini 3.5 Flash integration
- Streaming responses
- Structured JSON output
- Dependency validation
- Automatic project creation
- Credit deduction system

---

## 💬 Workspace

- Persistent AI conversations
- Markdown rendering
- Auto-scroll chat
- User avatars
- Image upload support
- Streaming generation status

---

## 🧠 Improve with AI Agent

Powered by Cline SDK.

Features include:

- File-by-file code improvements
- Autonomous reasoning
- Live status updates
- Sandpack synchronization
- Multi-file modifications

---

## 🖥️ Live Code Preview

- Sandpack integration
- Real-time rendering
- Runtime error detection
- Fix with AI functionality
- Export project as ZIP

---

## 📂 Project Management

- Project dashboard
- Conversation history
- Workspace persistence
- Delete projects
- Resume previous sessions

---

## 💳 Credit System

| Plan | Credits |
|--------|----------|
| Free | 10 |
| Starter | 50 |
| Pro | 150 |

- 1 Credit per Generation
- 1 Credit per Improvement
- Client-side validation
- Server-side validation
- Upgrade support

---

# 🏗️ Architecture

```text
User Prompt
      │
      ▼
 Next.js Frontend
      │
      ▼
 Gemini AI API
      │
      ▼
 Structured JSON Response
      │
      ├────────► Sandpack Preview
      │
      ├────────► Workspace Chat
      │
      └────────► Supabase Database
                        │
                        ▼
                Project Storage
```

---

# 🚀 Getting Started

## Clone Repository

```bash
git clone https://github.com/Pragati-coders/AI-App-Builder.git

cd AI-App-Builder
```

## Install Dependencies

```bash
npm install
```

## Prisma Setup

```bash
npx prisma generate

npx prisma db push
```

## Run Development Server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

# 🔑 Environment Variables

Create a `.env.local` file:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

# Database
DATABASE_URL=

# Gemini
GEMINI_API_KEY=

# Arcjet
ARCJET_KEY=
```

---

# 🗄️ Database Setup

## User Model

```text
id
clerkId
name
email
imageUrl
credits
plan
createdAt
updatedAt
```

## Workspace Model

```text
id
userId
title
messages
fileData
createdAt
updatedAt
```

### Storage Structure

```text
workspace-images/
└── userId/
    └── workspaceId/
```

---

# 📁 Project Structure

```text
app/
components/
lib/
prisma/
public/
screenshots/
types/
```

---

# 🚀 Future Improvements

- GitHub Integration
- Version Control
- Team Collaboration
- Multiple AI Models
- Real-Time Collaboration
- Custom Templates
- Mobile Application

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

---

# ⭐ Support

If you found this project helpful, please consider giving it a star ⭐

It helps others discover the project and motivates future development.

---

## 👩‍💻 Author

Pragati Mishra

GitHub:
https://github.com/Pragati-coders

LinkedIn:
https://www.linkedin.com/in/pragati-mishra-2026

---

## 🌐 Live Demo

https://ai-app-builder-gi9r.vercel.app
