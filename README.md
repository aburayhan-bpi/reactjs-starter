🚀 React + TypeScript + Redux + React Router Starter

A clean, scalable, and production-ready starter project built using:

React + TypeScript

Redux Toolkit

React Router v6

Modern folder architecture

Reusable layouts & components

Centralized styles (global + variables + animations)

This structure is ideal for SaaS apps, dashboards, admin panels, and large-scale applications.

📁 Project Folder Structure


src/
├── api/                  # API calls (services)
│
├── assets/               # Images, icons, fonts
│
├── components/           # Reusable UI and common components
│   ├── common/
│   └── ui/
│
├── hooks/                # Custom hooks
│
├── layouts/              # Reusable layout components
│   ├── AuthLayout.tsx
│   └── MainLayout.tsx
│
├── pages/                # All app pages
│   ├── Auth/
│   ├── dashboard/
│   ├── home/
│   └── NotFound.tsx
│
├── redux/                # Redux Toolkit store + features
│   ├── features/
│   └── store.ts
│
├── routes/               # Routing configuration
│   ├── AppRoutes.tsx
│   ├── ProtectedRoute.tsx
│   └── index.tsx
│
├── styles/               # Global styles
│   ├── animations.css
│   ├── globals.css
│   └── variables.css
│
├── types/                # Global TypeScript types
│
├── utils/                # Helper functions (formatting, validation)
│
├── App.css
├── App.tsx
├── index.css
└── main.tsx




🛠️ Features
✔ React + TypeScript

Strong typing, reliable component structure, and maintainable code.

✔ Redux Toolkit

State management using slices, clean reducers, and centralized store.

✔ Protected Routing

Middleware-like route protection using ProtectedRoute.tsx.

✔ Layout-Based Routing

Pages automatically inherit layouts such as:

MainLayout → Dashboard / Home

AuthLayout → Login / Register

✔ Organized Styles

globals.css → base reset + global styles

variables.css → color, spacing, shadow tokens

animations.css → reusable CSS animations

✔ Scalable Architecture

Each feature has its own folder, easy to expand as the project grows.





🚀 Tech Stack
Technology	Usage
React	UI library
TypeScript	Strong typing
Redux Toolkit	Global state
React Router v6	Routing/navigation
CSS Modules / Global CSS	Styling




📦 Installation
npm install

▶️ Run the Project
npm run dev


The app will start at:

http://localhost:5173

🧩 Build for Production
npm run build