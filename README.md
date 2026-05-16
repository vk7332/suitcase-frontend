# ⚖️ SUITCASE Frontend

AI-Powered Advocate Operating System Frontend for Indian Legal Practice.

SUITCASE is a modern Legal SaaS platform designed for Advocates, Law Firms, Trial Courts, and High Court practice management.

This repository contains the frontend application built with React, TypeScript, and Vite.

---

# 🚀 Features

## Legal Workflow

* Case Dashboard
* Hearing Management
* Cause List Tracking
* Limitation Calculator
* Client Management
* Court Fee Tracking
* Billing Dashboard

## AI Features

* AI Legal Research Assistant
* Courtroom Assistant
* Whisper Suggestions
* Auto Objection Detection
* Cross Examination Suggestions
* Written Arguments Generator

## Productivity Tools

* PDF Generation
* Annexure & Index Generator
* Digital Signing UI
* Notes Auto Save
* Voice Input/Output
* Courtroom Mode

## SaaS Features

* Subscription Billing
* Usage Tracking
* Credits System
* Team/Organization Dashboard
* Admin Analytics UI

---

# 🛠 Tech Stack

* React
* TypeScript
* Vite
* TailwindCSS
* Supabase
* Razorpay
* EmailJS

---

# 📁 Project Structure

```bash
src/
 ├── app/
 ├── core/
 ├── devtools/
 ├── lib/
 ├── modules/
 └── styles/
```

---

# ⚙️ Environment Variables

Create:

```bash
.env
```

Example:

```env
VITE_API_URL=https://your-backend.up.railway.app

VITE_SUPABASE_URL=https://your-project.supabase.co

VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

VITE_RAZORPAY_KEY_ID=your_razorpay_key

VITE_EMAILJS_PUBLIC_KEY=your_emailjs_public_key
```

---

# 📦 Installation

```bash
npm install
```

---

# ▶️ Development Server

```bash
npm run dev
```

Frontend runs on:

```bash
http://localhost:5173
```

---

# 🏗 Production Build

```bash
npm run build
```

---

# ☁️ Deployment

Recommended Deployment:

| Service  | Platform |
| -------- | -------- |
| Frontend | Vercel   |
| Backend  | Railway  |
| Database | Supabase |

---

# 🔒 Security

Never expose:

* Supabase Service Role Key
* OpenAI API Keys
* Razorpay Secret Keys
* JWT Secrets

Only public frontend variables should begin with:

```bash
VITE_
```

---

# 🌐 Official Domain

https://e-suitcase.in

---

# 👨‍⚖️ Author

Adv. Vipin Kumar

---

# 📜 License

Proprietary Software

All Rights Reserved © SUITCASE LegalTech
