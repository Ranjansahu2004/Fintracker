#  FinTracker

FinTracker is an AI-powered personal finance management platform that helps users track income and expenses, manage budgets, and gain real-time financial insights through an intuitive dashboard.

## Features

- 🔐 Secure Authentication using Clerk
- 💳 Multi-Account Management
- 📈 Interactive Dashboard with Charts
- 💸 Income & Expense Tracking
- 📊 Budget Planning and Monitoring
- 📧 Automated Budget Alerts using Resend + Inngest
- 📅 Monthly Financial Reports
- 🔄 Recurring Transactions
- 🎨 Responsive UI with Tailwind CSS + Shadcn UI
<img width="1000"
alt="Dashboard"
src="https://raw.githubusercontent.com/Ranjansahu2004/Fintracker/main/public/fintrackerdash.png">

---

## 🛠 Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS, Shadcn UI
- **Backend:** Server Actions, Node.js
- **Database:** PostgreSQL + Prisma ORM
- **Authentication:** Clerk
- **Background Jobs:** Inngest
- **Email Service:** Resend
- **Security:** ArcJet

---

## 📂 Project Structure

```bash
app/
actions/
components/
lib/
prisma/
public/
```

---

## ⚙️ Environment Variables

Create a `.env` file and add:

```env
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

RESEND_API_KEY=

ARCJET_KEY=
```

---

## 📦 Installation

```bash
git clone https://github.com/Ranjansahu2004/Fintracker.git

cd Fintracker

npm install

npm run dev
```

---

## 🌟 Future Enhancements

- AI Receipt Scanner
- Gmail Transaction Parsing
- PDF/CSV Bank Statement Upload
- AI Financial Assistant

---

## 👨‍💻 Author

**Ranjan Sahu**

B.Tech, Electronics & Telecommunication Engineering  
Veer Surendra Sai University of Technology (VSSUT), Burla

---

⭐ If you like this project, give it a star on GitHub!