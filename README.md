
# FinQuarius AI – Personal Finance Platform 

A full-stack AI-powered finance management SaaS platform to help users track, analyze, and optimize spending. Includes features like transaction insights, budget alerts, receipt scanning, monthly reports, and AI-powered analysis — all built with **Next.js 15**, **React 19**, **Tailwind**, **Prisma**, and **Shadcn UI**.

---

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Live Demo](#live-demo)
- [Future Improvements](#future-improvements)

---

## Features

<ul>
  <li>Clerk Authentication (Login/Signup/Profile)</li>
  <li>Secure & Scalable Postgres DB (via Prisma + Supabase)</li>
  <li>Modern UI with Tailwind CSS & ShadCN UI</li>
  <li>Smart Dashboard with Analytics & Graphs</li>
  <li>Bulk Transactions + Filtering + Sorting</li>
  <li>Monthly Budget Setup & Alerts via Cron</li>
  <li>Email Notifications for Budget & Monthly Reports</li>
  <li>AI Receipt Scanner (Gemini AI)</li>
  <li>Recurring Transaction Automation (Inngest)</li>
  <li>Monthly Financial Insights (AI-Powered)</li>
  <li>Advanced Bot & DDoS Protection (Arcjet)</li>
</ul>

---

## Tech Stack

### Frontend
<ul>
  <li>React 19 – App Framework</li>
  <li>Next.js 15 – Full Stack Meta Framework</li>
  <li>Tailwind CSS – Utility-first Styling</li>
  <li>Shadcn/UI – UI Component Library</li>
</ul>

### Backend
<ul>
  <li>Next.js Server Actions – API Handling</li>
  <li>Prisma ORM – PostgreSQL Database Access</li>
  <li>Clerk – Auth & User Management</li>
  <li>Inngest – Cron Jobs & Background Tasks</li>
  <li>Arcjet – Bot Protection & Rate Limiting</li>
  <li>Gemini AI – Smart Receipt Scanner</li>
</ul>

---

## Installation

### Prerequisites
<ul>
<li>Node.js v18+</li>
<li>PostgreSQL (Supabase / Neon)</li>
<li>Vercel CLI (Optional)</li>
</ul>

### Clone the Repository

```bash
git clone https://github.com/DHANDEAJAYKUMAR/finquarius-ai.git
cd finquarius-ai
npm install
npm run dev
```

### Setup Environment

Create a `.env` file in the root:

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

---

## Usage

<ul>
  <li>Sign up or login with Clerk</li>
  <li>Create an account and start logging transactions</li>
  <li>View dashboards, filter data, and visualize stats</li>
  <li>Use AI tools like receipt scanning and auto-insights</li>
  <li>Set budget limits and get email alerts</li>
  <li>Deploy with Vercel for production</li>
</ul>

---

## Project Structure

```
├── app/                         → Next.js App Router structure
│   ├── layout.tsx              → App layout
│   ├── page.tsx                → Landing Page
│   ├── dashboard/              → User Dashboard Pages
│   ├── api/                    → Route Handlers (Server Functions)
│
├── lib/                        → DB, utils, constants
├── components/                 → UI Components (Shadcn-based)
├── actions/                    → Server Actions / Mutations
├── inngest/                    → Background Cron Jobs
├── prisma/                     → DB Models & Seed
├── public/                     → Static Assets
├── styles/                     → Global Styles
├── .env                        → Environment Variables
├── package.json                → Dependencies & Scripts
```

---

## Live Demo

<p>Try it Live Here → <a href="https://finquarius-ai.vercel.app/" target="_blank">
https://finquarius-ai.vercel.app</a></p>
Demo Video
→ <a href="https://drive.google.com/file/d/1qtz7_NLHpgq4arLpOgynGy5C0eNu3gB5/view?usp=drive_link" target="_blank">Click to Watch</a>
---

## Future Improvements

<ul>
  <li>Income Tax Projection Tool</li>
  <li>Multi-currency Support</li>
  <li>AI Investment Recommendation Module</li>
  <li>PDF Export of Monthly Reports</li>
  <li>Custom Themes & Dark Mode</li>
  <li>Voice Expense Logging (AI Voice Bot)</li>
</ul>
