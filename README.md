# ❓ Quiz Application (Python GUI)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Challenge](https://img.shields.io/badge/Challenge-90DaysOfCode-orange)

---

## 📌 Overview

The Quiz Application is a Python-based desktop application built using Tkinter that presents users with True/False quiz questions fetched dynamically from an external trivia API.

The project follows a modular, object-oriented design and demonstrates how Python can be used to build interactive GUI applications that integrate live data sources. It was developed as part of my **#90DaysOfCode** journey.

---

## 🚀 Key Features

❓ Live quiz questions fetched from Open Trivia DB API  

🖥️ Interactive Tkinter-based GUI  

✅ True / False answer buttons with visual feedback  

📊 Real-time score tracking  

🔄 Automatic question progression  

🎯 Clean, modular, object-oriented code structure  

---

## 📁 Project Structure
```
quiz-app-tkinter-python/
│
├── main.py
│ └── Application entry point
│
├── data.py
│ └── Fetches quiz questions from external API
│
├── question_model.py
│ └── Question data model
│
├── quiz_brain.py
│ └── Core quiz logic and answer validation
│
├── ui.py
│ └── Tkinter-based user interface
│
├── true.png
│ └── True button image asset
│
├── false.png
│ └── False button image asset
│
└── README.md
└── Project documentation
```

---

## 🛠️ Application Workflow

1. Quiz questions are fetched dynamically from an external API.


2. Questions are converted into structured objects using a data model.

3. The GUI displays each question one at a time.

4. Users respond using True or False buttons.

5. Immediate visual feedback is shown for each answer.

6. The score is updated in real time.

7. The quiz ends automatically when all questions are completed.

This demonstrates real-world GUI state management and API-driven workflows.

---

## ▶️ Execution Instructions

### 1️⃣ Clone the Repository
```
git clone https://github.com/your-username/quiz-app-tkinter-python.git
cd quiz-app-tkinter-python
```

### 2️⃣ Install Dependencies
```
pip install requests
```

### 3️⃣ Run the Application
```
python main.py
```

---

## ⚠️ Important Notes

- Python 3.x is required

- Tkinter is included with most Python installations

- Internet connection is required to fetch quiz questions

- Image assets (`true.png`, `false.png`) must remain in the project directory

---

## 🧠 Concepts Demonstrated

Object-Oriented Programming (OOP)  

API integration and JSON parsing  

Tkinter GUI development  

Event-driven programming  

Separation of concerns  

Clean and maintainable Python code  

---

## 🎯 Project Significance

This project demonstrates how Python can be used to build interactive desktop applications that consume live data. It highlights important software development concepts such as modular design, UI logic separation, and user interaction handling—skills relevant to entry-level software and automation roles.

---

## 👨‍💻 Author

**Faiz Hasan**  
BCA Final Year — Graphic Era University  

🚀 Python Learner | **#90DaysOfCode**

---

*“Good design makes learning interactive and engaging.”*
