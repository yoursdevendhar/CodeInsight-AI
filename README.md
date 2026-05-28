# ⚡ CodeInsight AI

An AI-powered code analysis and learning platform built using Flask, Groq API, HTML, CSS, and JavaScript.

## 🚀 Features

- 🔍 Line-by-line code explanation
- 🧠 Time & space complexity analysis
- 🐞 Error detection and fixes
- ⚡ Code optimization suggestions
- 📘 Beginner & Advanced learning modes
- 🧪 Auto-generated MCQ quizzes
- 🧾 Dry run execution tracing
- 📄 PDF export support
- 🌙 Dark/Light theme
- 📜 Analysis history
- 💻 Multi-language support:
  - Python
  - JavaScript
  - Java
  - C
  - C++

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript
- Prism.js
- jsPDF

### Backend
- Python
- Flask
- Flask-CORS
- Groq API

---

## 📂 Project Structure

```bash
project/
│
├── app.py
├── requirements.txt
├── templates/
│   └── index.html
├── .env
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yoursdevendhar/CodeInsight-AI.git
cd CodeInsight-AI
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv myenv
```

### 3️⃣ Activate Virtual Environment

#### Windows
```bash
myenv\Scripts\activate
```

#### Mac/Linux
```bash
source myenv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup Groq API Key

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run Application

```bash
python app.py
```

Open browser:

```bash
http://127.0.0.1:5000
```

---

## 📌 API Endpoint

### Analyze Code

```http
POST /analyze
```

#### Request Body

```json
{
  "code": "print('Hello World')",
  "language": "python",
  "mode": "beginner"
}
```

---

## 📷 Features Preview

- Complexity Analysis
- Error Detection
- Quiz Generator
- Optimization Suggestions
- Dry Run Execution
- PDF Report Export

---

## 📦 Requirements

```txt
flask
flask-cors
groq
python-dotenv
```

---

## 👨‍💻 Author

Developed by Devendra 🚀

---

## ⭐ Future Improvements

- User authentication
- Save analysis to database
- AI chat assistant
- Voice explanation
- Code execution sandbox
- Deployment support

---
