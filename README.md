# ALX Listing App

## 📌 Project Overview

The **ALX Listing App** is a scaffolded Next.js project designed as the foundation for building an **Airbnb clone**.  
This milestone sets up the project structure, TypeScript integration, ESLint, TailwindCSS, and reusable components, ensuring a **well-structured and maintainable codebase**.

The main goal of this project is to provide a responsive and clean listing page where users can browse property cards and interact with reusable UI elements such as buttons.

---

## 🗂️ Project Structure

alx-listing-app/
│
├── components/
│ └── common/
│ ├── Card.tsx # Reusable card component for property listings
│ ├── Button.tsx # Reusable button component for actions (e.g., "Book Now")
│
├── interfaces/
│ └── index.ts # TypeScript interfaces (e.g., CardProps, ButtonProps)
│
├── constants/
│ └── index.ts # Global constants (API URLs, config values, UI text)
│
├── public/
│ └── assets/ # Exported assets (images, SVGs, placeholders, etc.)
│
├── pages/
│ ├── index.tsx # Main entry point (listing page)
│ └── \_app.tsx # Custom app configuration
│
├── styles/
│ └── globals.css # Tailwind base, components, and utilities
│
├── tailwind.config.js # Tailwind configuration
└── tsconfig.json # TypeScript configuration

### Directory Purpose:

- **components/** → Reusable UI components (Card, Button, etc.).
- **interfaces/** → TypeScript interfaces for props and types.
- **constants/** → Centralized constants for configuration and text.
- **public/assets/** → Images, icons, and other static assets.

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone <repository-url>
cd alx-listing-app
npm install
npm run dev

Open the app
Visit http://localhost:3000
 in your browser.

 Tech Stack

Next.js (Pages Router)
TypeScript (type safety)
TailwindCSS (styling)
ESLint (linting & clean code)

Notes
Assets should be placed inside public/assets/.
Only Tailwind’s base, components, and utilities are imported in globals.css.
Project uses Pages Router (not App Router) and avoids the src/ directory for simplicity.
```
