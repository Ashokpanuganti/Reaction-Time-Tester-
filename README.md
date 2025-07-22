# ⏱️ Reaction Time Tester Web App

A simple and fun web application built with **Python Flask**, **HTML/CSS**, and **JavaScript** to test your reaction speed and record your best scores.

---

## 🚀 Features

- ✅ Measures your reaction time to visual cues
- 🎨 Selectable color themes (Dark, Blue, Green, Red)
- 🥇 Leaderboard with top 3 scores
- 🧠 Feedback messages based on performance
- 🗃️ Separated logic (MVC-style decoupling)

---

## 📁 Project Structure

reaction_time_project/
├── app.py # Flask controller
├── score_logic.py # Score update logic
├── score_storage.py # Load/save score logic
├── high_scores.txt # File for storing top 3 scores
├── templates/
│ └── index.html # Main HTML file
├── static/
│ ├── style.css # Page styles
│ └── script.js # Frontend logic
├── README.md # You're reading it now!
└── .gitignore # To ignore pycache and .pyc file



---

## ⚙️ How to Run

### Prerequisites

- Python 3.7+
- Flask

### 🛠️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/reaction_time_project.git
cd reaction_time_project

# 2. Install dependencies
pip install flask

# 3. Run the app
python app.py


http://127.0.0.1:5000/
