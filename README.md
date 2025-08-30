<p align="center">
  <img src="Assets/logo.jpeg" alt="Noor-Ul-Eman Banner" width="100%"/>
</p>

# 🌙 Noor-Ul-Eman — Your Complete Islamic Companion  

> *“A spiritual companion in your pocket — prayers, Qur’an, azkar, hadith, goals, and a vibrant community, all in one place.”*  

Noor-Ul-Eman is a modern open-source Islamic app built to help Muslims **maintain their daily worship, connect with the Qur’an, set and achieve spiritual goals, and engage with the community.**  

---

## 📽️ Demo Video  
🎥 [Watch Demo ](https://drive.google.com/file/d/18W-aKeELc233X8dbLJOqZDF_uEjq4Lec/view?usp=sharing)  

---
---

## 📖 About the Project  
**Noor-Ul-Eman** is a modern web project aimed at building a **beautiful, scalable, and user-friendly platform**.  
This repo contains all the source code, documentation, and deployment details.  

---

## ✨ Core Features  

### 🕌 Prayer & Worship  
- Accurate **location-based prayer times**  
- **Prayer logs & analytics** (missed/offered stats)  
- **Qibla finder** (via MapBox + device compass)  
- **Digital Tasbih counter** with custom dhikr  

### 📖 Qur’an & Hadith  
- Complete Qur’an with **translations**  
- **Multiple bookmarks** & progress tracking  
- Juz and Surah navigation  
- **Advanced search** (Arabic + translations)  
- Hadith collection with “Favorite” option  
- Listen to Qur’an in **6 world-renowned Qari voices**  

### 📚 Duas & Azkar  
- Personal dua & azkar collections  
- Export duas as **PDF**  
- Daily dhikr & goal tracking  

### 🌐 Community  
- Real-time **chat system** (Socket.io)  
- Community feed with posts, comments, likes  
- **Event creation & participation** (study circles, iftar, taraweeh, etc.)  
- Activity tracking & notifications  

### 🎯 Personal Tools  
- Ramadan & daily goal tracking  
- **Reflection journal** for daily thoughts  
- Favorite Hadith & Azkar library  
- Activity logging & reports  

---

## 🧩 Tech Stack  

### Frontend  
- React 18 + Vite  
- TailwindCSS + Framer Motion  
- React Router  
- Socket.io client  
- MapBox API (Qibla & location)  
- ApexCharts (data visualizations)  

### Backend  
- Node.js + Express  
- MongoDB + Mongoose  
- Socket.io server (real-time)  
- Redis (for caching & performance)  
- JWT + Google OAuth (authentication)  
- Nodemailer (email) + Twilio SMS (alerts)  

---

## ⚙️ Prerequisites  
- Node.js (v16 or higher)  
- MongoDB instance  
- npm or yarn  
- Google OAuth credentials  
- MapBox API key  
- Twilio account (optional, for SMS)  

---

## 🚀 Installation & Setup  

### 1. Clone the Repository  
```bash
git clone https://github.com/Imama-Kainat/Noor-UL-Eman.git
cd Noor-UL-Eman
cd backend
npm install
cp .env.example .env   # configure environment variables
npm run dev

cd ../frontend
npm install
cp .env.example .env   # configure environment variables
npm run dev

cd frontend
npm run build

cd ../backend
npm start

Noor-UL-Eman/
│
├── backend/        # Express + MongoDB backend
│   ├── models/     
│   ├── routes/     
│   ├── controllers/
│   └── server.js
│
├── frontend/       # React + Vite frontend
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
└── docs/           # Documentation & diagrams


## 🚀 Features

* 🎨 Clean & Responsive UI
* ⚡ Fast & Scalable Codebase
* 📽️ Demo video for quick walkthrough
* 🧑‍🤝‍🧑 Collaboration-friendly

---

## 🧑‍💻 Contributing

We ❤️ open source! Want to make **Noor-Ul-Eman** better?

1. Fork the repo
2. Create your feature branch

   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes

   ```bash
   git commit -m "Add AmazingFeature"
   ```
4. Push to your branch

   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request 🎉

---

## 📜 License

This project is licensed under the **ISC License** — see the [LICENSE](./LICENSE) file for details.

---



## 📎 Useful Links

* 🔗 [GitHub Repository](https://github.com/Imama-Kainat/Noor-UL-Eman)
* 📄 Documentation: *Coming soon…*
* 📽️ [Demo Video](https://drive.google.com/file/d/18W-aKeELc233X8dbLJOqZDF_uEjq4Lec/view?usp=sharing)
* 💬 Feedback? Suggestions? Bugs? → Open an **issue** or start a **discussion**!

---

