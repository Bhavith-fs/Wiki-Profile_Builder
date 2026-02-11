<h1 align="center">🌐 TharangRepo – Wiki Profile Builder</h1>

<div align="center">

A modern **AI-powered Wiki Profile Builder** that allows users to fetch, edit, and generate Wikitext for their Wikimedia profiles across multiple wiki projects.

🎯 Fetch • Edit • Generate • Enhance  

![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge&logo=nextdotjs)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-Backend-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![AI](https://img.shields.io/badge/AI-Google%20Generative-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-Apache%202.0-black?style=for-the-badge)

</div>

---

## 📋 Overview

Wiki Profile Builder is a **Next.js-based web application** that provides an intuitive interface for managing Wikipedia and Wikimedia user profiles.

The application supports:

- Fetching existing profiles from multiple Wikimedia projects  
- Editing Wikitext with live preview  
- Parsing and rendering Wikitext to HTML  
- Creating new profiles from scratch  
- AI-powered profile generation & suggestions  

It is designed for **Wikimedia contributors, students, and open-source enthusiasts**.

---

## ✨ Core Features

### 🌍 Multi-Wiki Support
Work with profiles across:

- Meta-Wiki  
- English Wikipedia  
- Wikimedia Commons  
- Wikidata  
- English Wiktionary  

---

### 📝 Profile Management

- Fetch existing user profiles from supported wikis  
- Live Wikitext editing with real-time preview  
- Parse and render Wikitext to HTML  
- Create new profiles from scratch  
- Clean structured editing interface  

---

### 🤖 AI-Powered Generation

- Generate profile content using **Google Generative AI**
- Smart suggestions for profile improvement
- Content structuring assistance
- Beginner-friendly writing support

---

### 🔐 Firebase Integration

- Secure authentication (Email/Password & Google Sign-In)
- Cloud storage for profile images
- Persistent user sessions
- Secure configuration using environment variables

---

### 🎨 Modern UI/UX

- Clean and responsive design with Tailwind CSS
- Smooth animations using Framer Motion
- Icon system powered by Lucide React
- Real-time validation and error handling
- Minimal, distraction-free editing interface

---

## 🆕 Additional Functional Features

🔄 Real-time API-based fetching from Wikimedia servers  
📡 MediaWiki Action API integration  
🧩 Modular component-based architecture  
🧠 Client-side state management using Zustand  
🛡️ XSS protection using DOMPurify  
⚙️ CORS-aware API route handling  
📦 Structured project organization for scalability  
🧪 Developer-friendly environment setup  
🌐 Production-ready deployment support  

---

## 🛠️ Tech Stack

### Frontend
- **Next.js 16.1.6** – React framework with App Router  
- **React 19.2.3** – UI Library  
- **TypeScript 5** – Type Safety  
- **Tailwind CSS 4** – Utility-first styling  
- **Framer Motion 12.33.0** – Animations  
- **Zustand 5.0.11** – State Management  

### Backend & Services
- **Firebase 12.9.0**
  - Authentication (Email & Google OAuth)
  - Cloud Storage
- **Google Generative AI 0.24.1**
- **Axios 1.13.4** – API communication

### Development Tools
- **ESLint 9**
- **pnpm** – Fast package manager

---

## 📦 Installation

### Prerequisites
- Node.js 20.x or higher
- pnpm (recommended) or npm/yarn

### Steps

1️⃣ Clone the repository

```bash
git clone https://github.com/MabelMoncy/TharangRepo.git
cd TharangRepo/wiki-profile-builder
```

2️⃣ Install dependencies

```bash
pnpm install
# or
npm install
```

3️⃣ Create `.env.local`

```env
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
NEXT_PUBLIC_GOOGLE_AI_API_KEY=your_google_ai_key
```

4️⃣ Run development server

```bash
pnpm dev
```

5️⃣ Open browser  
Navigate to `http://localhost:3000`

---

## 🚀 Usage

### Fetch Existing Profile
1. Select wiki project  
2. Enter username  
3. Click "Fetch Profile"  
4. Edit Wikitext  
5. Preview changes instantly  

---

### Create New Profile
1. Switch to "Create New"  
2. Enter profile details  
3. Add images & categories  
4. Use AI suggestions  
5. Generate & preview  

---

## 📁 Project Structure

```
wiki-profile-builder/
├── src/
│   ├── app/
│   │   ├── api/
│   │   │   └── parse/
│   │   ├── layout.tsx
│   │   └── page.tsx
│   ├── components/
│   │   ├── auth/
│   │   ├── layout/
│   │   ├── profile/
│   │   └── ui/
│   ├── services/
│   │   ├── firebase.ts
│   │   └── wikiService.ts
│   └── store/
│       └── useStore.ts
├── public/
├── tailwind.config.ts
├── tsconfig.json
└── package.json
```

---

## 🔧 Available Scripts

```bash
pnpm dev
pnpm build
pnpm start
pnpm lint
```

---

## 🌐 Wikimedia API Integration

Uses **MediaWiki Action API** to:

- Fetch user pages  
- Parse Wikitext to HTML  
- Load ResourceLoader modules  
- Follow Wikimedia API etiquette guidelines  

---

## 🔐 Security Features

- DOMPurify for XSS protection  
- Firebase secure authentication  
- Environment variable protection  
- Secure API route design  

---

## 👨‍💻 Author

**Bhavith Madhav**  
Cybersecurity & Network Security Enthusiast  
Open-Source Contributor | Tech Explorer  

---

## 📄 License

Licensed under **Apache License 2.0**

---

## 🤝 Contributing

1. Fork repository  
2. Create feature branch  
3. Commit changes  
4. Push to branch  
5. Open Pull Request  

---

## 📞 Contact

Open an issue in the GitHub repository for support.

---

## 🙏 Acknowledgments

- Wikimedia Foundation  
- Next.js Team  
- Vercel  
- Open-source contributors  

---

<h3 align="center">Built with ❤️ for the Wikimedia Community</h3>
