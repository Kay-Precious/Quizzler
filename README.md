# 🧠 Quizzler - Python Quiz App

Quizzler is a simple Python quiz application that fetches multiple-choice questions from the Open Trivia DB API and displays them in a graphical interface using Tkinter. It gives instant feedback on each answer and keeps track of your score.

---

## 📁 Project Files

- **main.py** – Entry point of the application
- **data.py** – Fetches questions from Open Trivia DB using the `requests` module
- **quizbrain.py** – Handles quiz logic: checking answers, tracking score, managing question flow
- **question_model.py** – Defines the `Question` class used to model each quiz item
- **ui.py** – Builds the GUI with Tkinter and displays the questions and buttons

---

## 🔧 What It Uses

- **Python 3**
- **Tkinter** – for the user interface
- **requests** – to get quiz data from the API
- **html** – to decode special characters like `&quot;` or `&amp;`

---

## 🌐 API Used

- [Open Trivia DB](https://opentdb.com/api.php)

This is where the questions are generated from. The app automatically pulls 10 True/False questions from the API every time it runs.

---

## ✅ How to Run

Make sure all the project files are in one folder.

1. **Install Python** if you don’t have it: [python.org](https://www.python.org/)
2. **Install the required module** (if not already installed):

```bash
pip install requests
```

3. **Run the app**:

```bash
python main.py
```

The quiz window will appear, and you can start answering the questions.

---

## 🌟 Features

- Real-time question fetching
- Clean GUI built with Tkinter
- Instant feedback (green for correct, red for wrong)
- Keeps track of your score
- Uses `html.unescape()` to fix weird characters in the questions

---

## 💡 Possible Future Features

Here are some ideas that could improve the app:

- Select number of questions
- Choose difficulty (easy, medium, hard)
- Category selection (e.g., sports, science, movies)
- Add sound effects or animations
- Show correct answers after the quiz
- Store high scores

---

## 👤 Made By

Kay Precious  
Feel free to fork this project, contribute, or use it as a base for your own quiz apps!
a
