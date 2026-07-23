# 🧠 PrepIQ – AI Study Companion

An AI-powered web application that converts study notes into interactive multiple-choice quizzes. Users can paste lecture notes, textbook content, or any study material, choose the difficulty level and number of questions, and instantly generate AI-based quizzes.

---

## 🌍 Live Demo

**Website:** [https://YOUR-LIVE-URL.vercel.app](https://prepiq-ai-study-quiz-ouf2.bolt.host/)

---

## 📌 Problem Statement

Students and teachers spend a lot of time creating quizzes manually. PrepIQ solves this problem by automatically generating quizzes from study material using Artificial Intelligence, making learning faster and more interactive.

---

## ✨ Features

- 🤖 AI-powered quiz generation
- 📄 Generate quizzes from any study notes or text
- 🎯 Select Easy, Medium, or Hard difficulty
- 🔢 Choose 3, 5, or 10 quiz questions
- 📚 Built-in sample notes for quick testing
- 📱 Responsive design for desktop and mobile
- ⚡ Fast and user-friendly interface
- 🌐 Fully deployed and functional web application

---

## 🤖 AI Feature

PrepIQ uses **Google Gemini AI** to analyze user-provided study material and generate relevant multiple-choice questions.


## 🛠 Technologies Used

- Next.js
- React
- TypeScript
- Tailwind CSS
- Google Gemini API
- Git & GitHub
- Vercel

---

## 📸 Screenshots

Add at least three screenshots:

1. Home Page
2. Quiz Generation Interface
3. Generated AI Quiz

---

## 🚀 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
npm install
```

Create a `.env.local` file and add your Gemini API key:

```
GEMINI_API_KEY=YOUR_API_KEY
```

Run the project:

```bash
npm run dev
```

Open **http://localhost:3000** in your browser.

---

## 🎯 Conclusion

PrepIQ is a complete AI-powered study assistant that helps students learn more effectively by instantly generating quizzes from their own study material. It provides a simple, fast, and interactive way to practice and improve understanding.

---

## 👩‍💻 Developer

**Noor Ul Ain**  
BS Computer Science  
Final AI Project – 2026
---

## 📁 Project Structure

```text
├── app/                  # Next.js App Router pages and API routes
├── components/           # Reusable UI components (Quiz, Tutor, Dashboard)
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions and AI helper scripts
├── next.config.js        # Next.js configuration
├── tailwind.config.ts    # Tailwind CSS configuration
└── package.json          # Project dependencies and build scripts
