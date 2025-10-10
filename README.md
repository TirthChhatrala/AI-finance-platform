# 💰  AI-Powered Finance Management Platform

An intelligent personal finance management system built to help users track expenses, manage budgets, and gain AI-driven financial insights.  
Wealth simplifies financial tracking with **Next.js**, **Tailwind CSS**, **Prisma ORM**, and **Gemini AI**, providing a modern and secure experience for smarter money management.

---

## 🚀 Features

- 🤖 **AI-Powered Receipt Scanning** — Extracts transaction details using **Gemini AI**.
- 💵 **Income & Expense Tracking** — Categorizes and manages all transactions in one place.
- 📊 **Interactive Financial Dashboard** — Real-time analytics using **Recharts**.
- 📧 **Automated Monthly Reports** — Generates and sends personalized summaries via email.
- 🔔 **Budget Alerts** — Notifies users when spending approaches or exceeds limits.
- 🔐 **User Authentication** — Secured with **Clerk** and **Google Sign-In**.
- 🧩 **Background Jobs** — Handles recurring tasks using **Ingest** (report generation, alerts).
- 🧠 **AI Integration** — Automates entry creation and insights through **Gemini AI**.
- 🛡️ **Security Layer** — Protected with **Arcjet** for rate limiting and bot prevention.
- 📱 **Responsive Design** — Built using **Next.js + Shadcn UI + Tailwind CSS** for all devices.

---

## 🧱 System Architecture

### 🖥 Frontend
- Framework: **Next.js**
- Styling: **Tailwind CSS** + **Shadcn UI**
- Visualization: **Recharts** for dynamic analytics and charts

### ⚙️ Backend
- API: **Next.js API Routes**
- ORM: **Prisma ORM**
- Database: **Supabase (PostgreSQL)**
- Authentication: **Clerk** with **OAuth (Google Sign-In)**
- AI Engine: **Gemini AI**
- Background Jobs: **Ingest**
- Email Service: **React Email** + **Resend**
- Security: **Arcjet**

---

## 🔄 Data Flow

1. User logs in securely via Clerk.  
2. Uploads a receipt or adds a transaction manually.  
3. Gemini AI extracts transaction details automatically.  
4. Prisma ORM stores structured data in Supabase.  
5. Dashboard displays updated analytics in real time.  
6. Ingest runs periodic background jobs for alerts and reports.  
7. Users receive AI-generated reports via email.

---

## 🧩 Tech Stack

| Category | Technology |
|-----------|-------------|
| Frontend | Next.js, Tailwind CSS, Shadcn UI |
| Backend | Next.js API Routes, Prisma ORM |
| Database | Supabase (PostgreSQL) |
| Authentication | Clerk (Google Sign-In) |
| AI Integration | Gemini AI |
| Background Jobs | Ingest |
| Email Automation | React Email, Resend |
| Visualization | Recharts |
| Security | Arcjet |

---

## 🧠 AI Integration

Wealth leverages **Gemini AI** for:
- Receipt text extraction and transaction recognition
- Automated categorization of financial entries
- Personalized monthly financial summaries

Future enhancements aim to include **predictive analytics** to forecast spending and **multilingual receipt recognition**.

---

## 🧰 Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/your-username/wealth.git

# 2. Navigate to project folder
cd wealth

# 3. Install dependencies
npm install

# 4. Create a .env file and configure:
# NEXT_PUBLIC_CLERK_FRONTEND_API=
# DATABASE_URL=
# GEMINI_API_KEY=
# ARCJET_API_KEY=
# RESEND_API_KEY=
# SUPABASE_URL=
# SUPABASE_ANON_KEY=

# 5. Run the development server
npm run dev
```

Then visit http://localhost:3000
 to start exploring 🚀.

## 📧 Automated Emails

Monthly financial summaries

Budget limit alerts

Personalized spending insights

All powered by React Email + Resend with secure server-side rendering.

---

## 🧑‍💻 Contributors

Name	ID
Ridham Vadoliya	D23IT172
Tirth Chhatrala	D23IT179

---

## 📜 Conclusion

Wealth redefines personal finance management through automation and intelligence.
By integrating AI, real-time analytics, and secure full-stack architecture, the platform empowers users to make informed financial decisions with ease.

Future Goals:

Expand AI training for multilingual receipts
Integrate predictive analytics for expense forecasting
Enhance visualization with deeper insights

---

## 🪪 License

This project is licensed under the MIT License – feel free to use, modify, and distribute with attribution.
