# 🩺 Mediverse Next – Full Stack Doctor Appointment Platform

**Mediverse Next** is a modern, scalable, and AI-ready doctor appointment platform built with **Next.js**, **Tailwind CSS**, **Neon (PostgreSQL)**, **Shadcn UI**, and **Vonage Video API**. It enables real-time virtual consultations, seamless appointment scheduling, and role-based access for patients, doctors, and admins.

Live Demo (coming soon) • [GitHub Repo](https://github.com/Vijaykalyan23/mediverse-next)

---

## 🚀 Features

- 👤 **Multi-role System** (Patients, Doctors, Admins)
- 📅 **Doctor Slot Management & Appointment Booking**
- 🩻 **Specialty-based Doctor Search**
- 💼 **Admin Dashboard** to manage doctors, payouts, verifications
- 📹 **Vonage Video Call Integration** for remote consultations
- 💰 **Doctor Earnings & Payout Tracking**
- 🌈 **Responsive UI** with Shadcn UI and Tailwind CSS
- 🔐 **Secure Authentication Flow**

---

## ⚙️ Tech Stack

| Category        | Stack                               |
|----------------|--------------------------------------|
| Frontend        | Next.js 14 (App Router)              |
| Styling         | Tailwind CSS, Shadcn UI              |
| Backend         | Server Actions (Next.js), Prisma ORM |
| Database        | PostgreSQL (hosted on Neon)          |
| Real-Time Video | Vonage Video API                     |
| Auth            | (Add: NextAuth / Clerk / Custom)     |

---

## 📁 Project Structure (Simplified)

mediverse-next/
├── app/ # App routes (auth, admin, doctor, etc.)
├── components/ # Shared and UI components
├── actions/ # Server-side logic (appointments, doctor, admin)
├── hooks/ # Custom hooks
├── lib/ # Utilities, Prisma client, schema, etc.
├── prisma/ # Prisma schema & migrations
├── public/ # Static assets
├── middleware.js # Route guards
├── next.config.mjs # Next.js config
└── package.json # Dependencies & scripts

yaml
Copy
Edit

---

## 🧩 Modules Overview

| Module          | Description                                  |
|----------------|----------------------------------------------|
| `/onboarding`   | Doctor signup & verification process         |
| `/doctors`      | Browse doctors by specialty, book appointments |
| `/appointments` | Patient dashboard for upcoming bookings      |
| `/admin`        | Manage pending verifications & payouts       |
| `/doctor`       | View appointments, earnings & availability   |
| `/video-call`   | Vonage-powered virtual consultation screen   |

---

## 🔧 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Vijaykalyan23/mediverse-next.git
cd mediverse-next
2. Install Dependencies
bash
Copy
Edit
npm install
3. Setup .env File
Create a .env file in the root with these variables:

env
Copy
Edit
DATABASE_URL=your_neon_database_url
VONAGE_API_KEY=your_vonage_api_key
VONAGE_API_SECRET=your_vonage_api_secret
NEXT_PUBLIC_BASE_URL=http://localhost:3000
4. Prisma Setup
bash
Copy
Edit
npx prisma generate
npx prisma migrate dev
5. Run the App
bash
Copy
Edit
npm run dev
Visit http://localhost:3000

📸 Screenshots
(You can add screenshots here after UI is polished)

🛠 Upcoming Enhancements
📧 Email/SMS reminders

🧠 AI-powered doctor recommendations

📋 Prescription upload

📊 Admin analytics dashboard

🌍 Deployment with Vercel and Neon

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open a PR or submit an issue.

👨‍💻 Author
Vijay Kalyan
🔗 GitHub

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

yaml
Copy
Edit

---

Would you like me to:
- Add **markdown badges** for tech/tools?
- Generate a **repository banner**?
- Or help you create **GitHub issues** for upcoming features?








Ask ChatGPT



Tools


