# 🔓 Uncracked

**Break the habit, not the law.**

Uncracked is a modern, dynamic web catalog dedicated to helping users discover powerful, legal, and open-source alternatives to cracked and pirated software. By providing verified alternatives, the project aims to keep machines safe from malware while promoting the open-source community.

## ✨ Features

- **Dynamic Cloud Catalog:** Software entries are fetched and displayed in real-time.
- **Custom Admin Dashboard:** A built-in management panel to add new software and upload logos directly to the cloud.
- **Smart Search & Filter:** Instantly find alternatives by browsing categories or searching for the proprietary software name (e.g., "Photoshop" or "Office").
- **Cloud Storage Integration:** Automated image hosting for software icons.
- **Fully Responsive:** Smooth, animated UI optimized for both desktop and mobile screens.

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend & Database:** Supabase (PostgreSQL)
- **File Storage:** Supabase Storage Buckets
- **Hosting / Deployment:** Vercel

## 🚀 How It Works

The project runs entirely in the browser using Vanilla JavaScript to communicate with the Supabase REST API. 
- `index.html`: The main public-facing catalog.
- `dashboard.html`: The admin interface for managing the database and storage.

## ⚙️ Setup & Installation (For Forking)

If you want to clone this project and use your own database:

1. Create a free project on [Supabase](https://supabase.com/).
2. Open the Supabase SQL Editor and run the required SQL queries to create the `software` table, the `software-icons` storage bucket, and enable Row Level Security (RLS).
3. Update `SUPABASE_URL` and `SUPABASE_ANON_KEY` inside both `index.html` and `dashboard.html` with your project's credentials.
4. Open `index.html` in your browser.

## 🌐 Deployment

This project is perfectly suited for zero-config deployment on platforms like **Vercel**, **Netlify**, or **GitHub Pages**. 
Simply link your GitHub repository and deploy—no build commands or build directories required.

---
*Developed for a safer, open-source web.*
