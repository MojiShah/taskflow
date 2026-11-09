# TaskFlow 🚀

A Full-Stack Project Management SaaS built with Next.js, React, TypeScript, Tailwind CSS, MongoDB Atlas, and pnpm Workspaces.

## 📌 About

TaskFlow is a project management application designed to manage projects, tasks, teams, and workflows.

This project is built as a Monorepo containing two independent applications:

- **Web:** Full-Stack application built with Next.js.
- **Admin:** Independent admin dashboard built with React and Vite.

Both applications share a common development environment and will communicate through the Next.js backend API.

## 🛠 Tech Stack

### Web Application
- Next.js (App Router)
- React
- TypeScript
- Tailwind CSS

### Admin Dashboard
- React
- Vite
- TypeScript
- Tailwind CSS

### Backend & Database
- Next.js Route Handlers
- MongoDB Atlas
- Mongoose

### Development Tools
- pnpm Workspaces
- Turborepo
- Git & GitHub

## 📁 Project Structure

```text
taskflow/
├── apps/
│   ├── web/                 # Next.js application
│   └── admin/               # React admin dashboard
│
├── packages/
│   ├── shared/              # Shared types and schemas
│   ├── eslint-config/       # Shared ESLint configuration
│   └── typescript-config/   # Shared TypeScript configuration
│
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── turbo.json
├── .gitignore
└── README.md
```

## ⚙️ Prerequisites

Make sure you have installed:

- Node.js (LTS)
- pnpm
- Git

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/taskflow.git
cd taskflow
```

### 2. Install dependencies

```bash
pnpm install
```

### 3. Run applications

```bash
pnpm dev
```

### 4. Open applications

| Application | URL |
|---|---|
| Next.js Web | http://localhost:3000 |
| React Admin | http://localhost:5173 |

## 🧩 Workspace Commands

```bash
pnpm dev
pnpm build
pnpm lint
pnpm typecheck
```

## 🔐 Environment Variables

Environment variables are managed separately for each application.

Create the required environment files based on the corresponding `.env.example` files.

Never commit real credentials, database connection strings, or secrets.

## 🗺 Roadmap

- [x] Monorepo initialization
- [x] Next.js application setup
- [x] React admin application setup
- [x] pnpm Workspace configuration
- [x] Turborepo configuration
- [ ] UI and Design System
- [ ] MongoDB Atlas integration
- [ ] Authentication and Authorization
- [ ] Projects and Tasks CRUD
- [ ] Kanban Board
- [ ] Admin Dashboard
- [ ] Testing
- [ ] Production Deployment

## 📄 License

This project is currently under development.