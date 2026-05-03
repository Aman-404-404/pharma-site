# 💊 PharmaSite — Online Pharmacy Web Application

A modern, full-stack online pharmacy website built with **Next.js 16**, **TypeScript**, **Supabase**, and **Tailwind CSS**. This project includes product listings, a shopping cart, user authentication, and a checkout system powered by Stripe.

---

## 🌐 Live Demo

[https://pharma-site-amber.vercel.app](https://pharma-site-amber.vercel.app)

---

## ✨ Features

- 🛒 Shopping cart with real-time updates
- 🔐 User authentication (Sign up / Login) via Supabase
- 💳 Payment integration with Stripe
- 📦 Product listing and detail pages
- 📱 Fully responsive design (mobile & desktop)
- 🌙 Light/Dark mode support
- 📧 Email notifications via Resend

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Next.js 16 | React framework & routing |
| TypeScript | Type-safe JavaScript |
| Tailwind CSS | Styling |
| Supabase | Database & Authentication |
| Stripe | Payment processing |
| Radix UI | Accessible UI components |
| Vercel | Deployment & hosting |

---

## 🚀 Getting Started (Run Locally)

### 1. Clone the repository
```bash
git clone https://github.com/Aman-404-404/pharma-site.git
cd pharma-site
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables

Create a `.env.local` file in the root folder and add:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
STRIPE_SECRET_KEY=your_stripe_secret_key
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
RESEND_API_KEY=your_resend_api_key
```

### 4. Set up the database

- Go to [supabase.com](https://supabase.com) and create a project
- Open the **SQL Editor** and run the `supabase-schema.sql` file from this repo

### 5. Start the development server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```
pharma-site/
├── app/             # Next.js app router pages
├── components/      # Reusable UI components
├── context/         # React context (cart, auth)
├── hooks/           # Custom React hooks
├── lib/             # Utility functions & Supabase client
├── public/          # Static assets (images, icons)
├── styles/          # Global CSS styles
└── supabase-schema.sql  # Database schema
```

---

## ☁️ Deployment

This project is deployed on **Vercel**. To deploy your own copy:

1. Push code to GitHub
2. Go to [vercel.com](https://vercel.com) → Import your repo
3. Add the environment variables listed above
4. Click **Deploy**

---

## 📄 License

This project was built for educational/assignment purposes.
