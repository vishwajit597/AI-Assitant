# 🤖 AI Assistant Web Application

An **AI Assistant** built using **HTML, CSS, JavaScript, Web Speech API, and Python** that allows users to interact using **voice commands** and **text input**. The assistant can listen, understand commands, respond with speech, and perform basic tasks such as answering questions, opening websites, or executing backend logic via Python.

---

## ✨ Features

* 🎙️ Voice input using **Web Speech API (Speech Recognition)**
* 🔊 Voice output using **Speech Synthesis API**
* 💬 Text-based interaction support
* 🌐 Web-based user interface (HTML + CSS)
* ⚙️ JavaScript for frontend logic and voice handling
* 🐍 Python backend for processing commands and AI logic
* 🔄 Real-time interaction between frontend and backend

---

## 🛠️ Tech Stack

### Frontend

* **HTML5** – Structure of the web application
* **CSS3** – Styling and layout
* **JavaScript (ES6)** – Application logic
* **Web Speech API** – Speech recognition & speech synthesis

### Backend

* **Python** – Core assistant logic


---

## 📂 Project Structure

```bash
AI-Assistant/
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│
├── templates/
│   └── index.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works

1. User clicks the **microphone button**
2. Browser captures voice using **Web Speech API**
3. JavaScript converts speech to text
4. Text command is sent to the **Python backend**
5. Python processes the command and returns a response
6. Assistant replies using **speech synthesis**

---

## 🚀 Getting Started

### Prerequisites

* Python 3.8+
* Modern browser (Chrome recommended)
* Basic knowledge of HTML, CSS, JavaScript, and Python

---

### 🔧 Installation Steps

1. **Clone the repository**

```bash
git clone https://github.com/your-username/ai-assistant.git
cd ai-assistant
```

2. **Install Python dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the backend server**

```bash
python app.py
```

4. **Open the application**

Open your browser and go to:

```
http://127.0.0.1:5000
```

---

## 🧠 Sample Commands

* "Hello"
* "What is the time?"
* "Open Google"
* "Search Python tutorial"

---


## ⚠️ Limitations

* Works best in **Chrome browser**
* Requires microphone permission
* Limited command understanding (rule-based)
* Internet connection required for speech recognition

---

## 🔮 Future Enhancements

* Integrate **OpenAI / LLM APIs**
* Add **Natural Language Processing (NLP)**
* User authentication
* Multi-language support
* Mobile responsiveness

---

## 📚 Learning Outcomes

* Hands-on experience with Web Speech API
* Frontend-backend communication
* Voice-based UI design
* Python-based AI logic

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---


⭐ If you like this project, give it a star on GitHub!
