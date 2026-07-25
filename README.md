# Production-Ready Developer Portfolio Website

A modern, high-performance developer portfolio built with **Next.js (App Router)**, **TypeScript**, **Tailwind CSS**, **Framer Motion**, and **Lucide React**, pre-populated with **Yarramreddy Siva Nagalakshmi**'s resume details.

![Portfolio Preview](https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&q=80&w=1200)

---

## 🌟 Key Features

- **Responsive Modern Design**: Sleek dark mode by default with obsidian glassmorphism cards, glowing ambient accents, and responsive navigation.
- **Hero Section**: Personal details, role badge, dynamic headline, contact CTAs, and key capability highlights.
- **About & Education**: Professional bio and interactive timeline covering academic credentials (B.Tech CSE AI, Intermediate, SSC).
- **Skills Grid**: Categorized tech stack display (Frontend, Machine Learning & AI, Databases & Analytics, Tools & Deployment).
- **Featured Projects**: Filterable project showcase featuring repository links, live demos, and tech tags (Bella Vista Restaurant, Customer Churn Prediction, Credit Card Fraud Detection).
- **Interactive Contact Form**: Validated contact form with state feedback and direct social channels (GitHub, LinkedIn, Email, Phone).
- **Vercel Deployment Ready**: Zero TypeScript errors, optimized imports, clean metadata, and production configuration.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Animations**: [Framer Motion](https://www.framer.com/motion/)
- **Icons**: [Lucide React](https://lucide.dev/)

---

## 💻 Local Development Setup

Follow these steps to run the portfolio locally on your computer:

### 1. Prerequisites
Ensure you have **Node.js** (v18.x or higher) installed on your system.

### 2. Install Dependencies
In your project terminal, run:
```bash
npm install
```

### 3. Run Development Server
Start the local server:
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the application live.

### 4. Build for Production
To test the production build locally:
```bash
npm run build
npm run start
```

---

## 🚀 How to Deploy to Vercel

### Option A: Using GitHub & Vercel Dashboard (Recommended)

1. Push this codebase to a new repository on your **GitHub** account:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio release"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```
2. Log in to [Vercel](https://vercel.com).
3. Click **"Add New"** -> **"Project"**.
4. Import your newly created GitHub repository.
5. Vercel will automatically detect **Next.js** framework settings.
6. Click **"Deploy"**. Your site will be live within 1 minute!

### Option B: Using Vercel CLI

1. Install Vercel CLI globally:
   ```bash
   npm i -g vercel
   ```
2. Run the deployment command in the project directory:
   ```bash
   vercel
   ```

---

## ✏️ Customizing Portfolio Data

All personal info, projects, skills, and education history are centrally managed inside:
```
data/portfolio.ts
```
Simply edit this file to update any project links, text, skills, or social profiles!
