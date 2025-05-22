# 🎓 DIGISCHOLAR - PMSSS Scholarship Portal

DIGISCHOLAR is a modern web-based platform designed to simplify and streamline the **PMSSS (Prime Minister’s Special Scholarship Scheme)** application process. It enables students to register, verify eligibility, upload documents, and track their application status through a seamless interface.

---

## 🚀 Features

- 🔐 **Login Modal** — User-friendly authentication system.
- 📄 **Document Upload** — Upload and manage essential application documents.
- 📬 **Check Application Status** — Real-time tracking of your application.
- ✅ **Eligibility Form** — Interactive form to determine student eligibility.
- 📝 **PMSSS Registration** — Dedicated section for PMSSS-related registration.
- 📊 **Application Confirmation** — Final review and confirmation module.
- 🤖 **Chatbot Support** — Smart assistant for real-time user queries.
- 📞 **Contact Modal** — Reach out for help with ease.
- 🌐 **Responsive UI** — Works smoothly on mobile, tablet, and desktop.

---

## 🛠️ Tech Stack

| Frontend           | Backend / Hosting          | Tools / Config       |
|--------------------|----------------------------|-----------------------|
| React + TypeScript | Firebase (Auth, Firestore) | Vite, ESLint, Prettier|
| React Router       | Firebase Storage           | Tailwind CSS (if used)|

---

## 📁 Folder Structure

```
src/
├── components/         # Reusable UI components (Navbar, Footer, Modals, etc.)
├── pages/              # Main route components (Register, Eligibility, Upload)
├── firebase.ts         # Firebase configuration
├── App.tsx             # Main App routing and logic
├── main.tsx            # App entry point
└── vite-env.d.ts       # TypeScript environment types
```

---

## 🧪 Setup & Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/deb-001/digischolar-user.git
cd digischolar
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file in the root directory:

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
```

### 4️⃣ Start the development server

```bash
npm run dev
```

Visit: [http://localhost:5173](http://localhost:5173)

---

## 📦 Build for Production

```bash
npm run build
```

Deploy the contents of the `dist/` folder using your preferred hosting platform (Vercel, Firebase Hosting, Netlify, etc.)

---

## 🚀 Deployment (Vercel)

If deploying on [Vercel](https://vercel.com):

1. Push your code to GitHub
2. Connect your repository on Vercel dashboard
3. Set environment variables in project settings
4. Click **Deploy**

---

## 🛡️ Security

- `.env` is included in `.gitignore` ✅
- Never commit secret keys
- Use secure Firebase Firestore rules for database access

---

## 🙋‍♂️ Contributors

- [deb-001](https://github.com/deb-001) — Project Owner & Developer

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📌 Acknowledgements

- [PMSSS Official Website](https://www.aicte-india.org/bureaus/jk)
- [React Documentation](https://reactjs.org/)
- [Firebase Docs](https://firebase.google.com/docs)
