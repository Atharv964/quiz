# 🎯 Quiz App | React + Vite

A simple and interactive quiz application built using React and Vite. The app displays multiple-choice questions, allows users to lock an answer, and shows the final score at the end of the quiz.

# 🚀 Features

✔ Built with React + Vite
✔ Multiple-choice quiz questions
✔ Score calculation at the end
✔ Clean UI and smooth user experience
✔ Fully responsive design
✔ Easy to customize questions

# 🛠️ Tech Stack
Technology	Purpose
React	UI Components & State Management
Vite	Fast Development & Build Tool
JavaScript	App Logic
CSS	Styling & Layout

# 📂 Project Structure
quiz-app/
├── public/
├── src/
│   ├── assets/
│   │   └── data.js        # Quiz Questions
│   ├── Components/
│   │   └── Quiz.jsx       # Main Quiz Component
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── package.json
└── vite.config.js

# 📦 Installation & Setup

Make sure you have Node.js installed.
*** Clone the repository
git clone https://github.com/your-username/quiz-app.git

*** Go to project directory
cd quiz-app

*** Install dependencies
npm install

*** Start development server
npm run dev

# 🌐 Deployment

To create a production build:
npm run build

To preview production build:
npm run preview

# ✍️ Updating Quiz Questions

Edit the file:
src/assets/data.js

Example format:
export const data = [
  {
    question: "What does HTML stand for?",
    options: ["Hyperlinks Text Markup Language", "Hyper Text Markup Language", "Home Tool Markup Language", "Hyperlinking and Texting Marking Language"],
    answer: 2
  },
];

