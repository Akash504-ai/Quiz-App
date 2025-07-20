# 📚 Quiz App

A simple and interactive Quiz App built using **React.js**. Users can test their knowledge by answering multiple-choice questions, see the correct answer instantly, and get a final score at the end.

---

## 📸 Preview

![Quiz App Screenshot]
<img width="866" height="751" alt="image" src="https://github.com/user-attachments/assets/5cfc1f46-a2dd-4a93-9d47-c4f61b4774bd" />

---

## 🚀 Features

- 📖 Displays one question at a time  
- ✅ Instantly highlights correct and wrong answers  
- 📊 Score tracking  
- 🔁 Reset quiz anytime  
- 🔒 Prevents multiple answers for one question  

---

## 🛠️ Tech Stack

- **React.js**
- **CSS** (custom styling)
- **Vite** (for faster development)

---

## 📁 Folder Structure

Quiz-app/
├── public/
├── src/
│ ├── assets/
│ │ └── data.js # Contains all quiz questions and answers
│ ├── Components/
│ │ └── Quiz/
│ │ ├── Quiz.jsx # Main Quiz component
│ │ └── Quiz.css # Styles for quiz
│ ├── App.jsx
│ ├── main.jsx
│ └── index.css
├── index.html
├── package.json
├── vite.config.js
└── README.md


---

## 📦 Installation & Running Locally

```bash
# 1. Clone the repository
https://github.com/Akash504-ai/Quiz-App

# 2. Navigate into the project folder
cd quiz-app

# 3. Install dependencies
npm install

# 4. Run the development server
npm run dev


📋 Data Format (data.js)

export const data = [
  {
    question: "Which of the following is a web browser?",
    option1: "Linux",
    option2: "Google Chrome",
    option3: "GitHub",
    option4: "Python",
    ans: 2
  },
  // Add more questions...
];


🔧 To-Do / Improvements
Add progress bar

Add timer per question

Store scores in local storage

Add categories/difficulty levels

🧑‍💻 Author
Made with ❤️ by Akash Santra

📜 License
This project is licensed under the MIT License.
