# 📊 ExpenseTracker

A **lightweight personal finance dashboard** built with **Vite + React + TypeScript + Tailwind CSS**, designed to help you track expenses, manage budgets, and visualize your finances in a simple, responsive UI.

**Live Preview:** [Finance Master Omega](https://finance-master-omega.vercel.app/)

---

## 🚀 Features

* Dashboard with **summary cards** and **charts**
* Manage **Transactions, Categories, Budgets, Accounts, Reports, Goals, Settings**
* **Mobile-first responsive UI** with accessible hamburger menu
* **Quick add transaction** button for fast entries
* Powered by **shadcn/ui style primitives** for clean design

---

## 🛠 Tech Stack

* **Frontend:** React, TypeScript, Vite
* **Styling:** Tailwind CSS
* **UI Components:** shadcn/ui
* **Routing:** React Router
* **Deployment:** Vercel

---

## ⚡ Quickstart

**Prerequisites:** Node.js 18+ and npm

1. Install dependencies

```bash
npm install
```

2. Run development server

```bash
npm run dev
```

3. Build for production

```bash
npm run build
```

4. Preview the production build locally

```bash
npm run preview
```

---

## 🌐 Vercel Deployment Notes

* This repo includes a `vercel.json` configured for a **Vite SPA** (rewrites all routes to `index.html`).
* **Project Settings:**

  * **Build Command:** `npm run build`
  * **Output Directory:** `dist`
  * **Root Directory:** (folder containing `package.json`)
* If switching to **Next.js**, remove or adapt `vercel.json` for the Next.js preset.

---

## 📁 Important Files

* Mobile nav component: `src/components/layout/MobileNav.tsx`
* Layout wrapper: `src/components/layout/AppLayout.tsx`
* Desktop sidebar: `src/components/layout/Sidebar.tsx`
* Vercel config: `vercel.json`

---

## 📱 Mobile Nav & "Powered by Archer"

* The **mobile hamburger menu** contains all navigation items plus an external link: [Archer](https://abdulbasit-archer.vercel.app/)
* Opens in a **new tab** (`rel="noopener noreferrer"`)
* To modify the "Powered by" link, edit the anchor in `src/components/layout/MobileNav.tsx` (near the bottom of the nav list)

---

## 🤝 Contributing

* Fork the repository
* Create a feature branch
* Submit a Pull Request
* Keep changes focused and include tests where appropriate

---

## 📄 License

MIT License

---

## 📬 Contact

* **Email:** [abdulbasit.alpha25@gmail.com](mailto:abdulbasit.alpha25@gmail.com)
* **Phone / WhatsApp:** +92 341 5878569
* **LinkedIn:** [Abdul Basit](https://www.linkedin.com/in/abdul-basit-741977295/)

---

## ✨ Updated Section

This README was updated to include **live preview links, contact info, and additional contribution instructions**.
