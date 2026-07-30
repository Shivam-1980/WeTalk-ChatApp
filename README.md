
# 💬 weTalk - Real-Time Chat App (React + Firebase)

[![Made with React](https://img.shields.io/badge/Made%20with-React-blue?logo=react)](https://reactjs.org/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-orange?logo=firebase)](https://firebase.google.com/)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()

---

**weTalk** is a real-time chat application built with React and Firebase, designed for fast, secure, and seamless communication.
It supports user authentication, live chat rooms, and real-time message syncing using Firebase’s cloud infrastructure — all without a traditional backend server.

Fully responsive and serverless by design, weTalk delivers a smooth user experience across devices with minimal setup and maximum scalability.

---

## 🚀 Features

- 🔐 Secure authentication with Firebase (Email/Password)
- 💬 Real-time messaging using Firestore
- 🧑‍🤝‍🧑 Join or create chat rooms
- ⚡ Instant typing and message updates
- 🎨 Clean, responsive React UI
- ☁️ Fully serverless (Firebase)

---

## 🛠️ Tech Stack

| Layer              | Technology                  |
|--------------------|------------------------------|
| Frontend           | React.js (Hooks, JSX, Router) |
| Backend (Serverless)| Firebase (Auth + Firestore)  |
| Real-Time Engine   | Firestore onSnapshot Listeners |
| Styling            | CSS / Custom Styling          |
| Deployment         | Firebase Hosting / Vercel     |

---


## ⚙️ Getting Started

### 🔧 1. Clone the Repository

```bash
git clone https://github.com/Deepbendu/WeTalk.git
cd WeTalk
```

### 📦 2. Install Dependencies

```bash
npm install
```

### 🔑 3. Set Up Firebase

- Go to [firebase.google.com](https://firebase.google.com/)
- Create a Firebase project
- Enable **Email/Password Authentication**
- Create a **Cloud Firestore** database
- Get your web app config under:
  `Project Settings → General → Web App`

Paste it into:

```js
// src/firebase.js
import { initializeApp } from "firebase/app";

const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};

export const app = initializeApp(firebaseConfig);
```

### ▶️ 4. Start the App

```bash
npm start
```

Go to:  
```
http://localhost:3000
```

---

## 🚀 Deployment

### 🔹 Firebase Hosting

```bash
npm run build
firebase init
firebase deploy
```

Or use:

### 🔹 Vercel

- Push your code to GitHub
- Import repo into [Vercel](https://vercel.com/import)
- Auto-deploy with build settings

---

## 🙋‍♂️ About Me

**Shivam Solanki**  
Software Engineer | Full-Stack Developer | Cloud Computing | AI/ML Enthusiast | Oracle OCI Certified | Java • React • SQL || VIT Vellore

Hi! I'm Shivam — a builder who loves combining **cloud, automation, and frontend magic** to make clean, scalable apps.  
I'm always exploring how to bring simplicity to complex systems using tools like **React**, **Firebase**, and **AWS**.  

Made with ❤️ in India 🇮🇳

---

## 📬 Contact

I'm always open to connect for internships, full-time roles, mentorship, or collaborative builds:

> ✉️ shivamsolanki539@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/shivam-solanki-918b0b246) | 📁 [GitHub](https://github.com/Shivam-1980) | 

---

## ⭐ If you liked it...

Feel free to star ⭐ the repo and share it with friends or recruiters.  
Every bit of support helps me grow and build more open-source projects!
