# AI Code Reviewer

An AI-powered code analysis tool that reviews, explains, and improves code using Large Language Models (LLMs).
Built with **Streamlit (frontend)** and Python-based backend logic.

---

## 🚀 Features

* 🔍 AI Code Review (bugs, improvements, best practices)
* 🧪 Unit Test Generation
* ✨ Code Refactoring
* 📖 Code Explanation
* 💬 AI Assistant (chat with your code)
* 📊 Analysis history tracking

---

## 📂 Project Structure

```bash
AI-Code-Reviewier/
│
├── app.py                     # Streamlit frontend (UI + main logic)
├── ai_suggestions.py          # AI interaction (LLM calls, prompts)
├── code_parser.py             # Code parsing & structure analysis
├── error_detector.py          # Static error detection
│
├── history.json               # Stores past analysis results
├── requirements.txt           # Dependencies
├── README.md                  # Project documentation
│
├── .env                       # API keys (not committed)
├── .gitignore                 # Git ignore rules
│
├── .devcontainer/             # Dev container config
├── .git/                      # Git metadata
├── __pycache__/               # Python cache (auto-generated)
└── .DS_Store                  # System file (ignore)
```

---

## ⚙️ Installation

### 1. Clone repository

```bash
git clone https://github.com/your-username/AI-Code-Reviewier.git
cd AI-Code-Reviewier
```

---

### 2. Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Setup environment variables

Create a `.env` file:

```env
HF_TOKEN=your_huggingface_api_key
```

---

## ▶️ Run the Application

```bash
python -m streamlit run app.py
```

👉 Open: http://localhost:8501

---

## 🔄 How It Works

1. User writes code in the editor
2. Code is analyzed using:

   * `code_parser.py` (structure)
   * `error_detector.py` (static issues)
3. Code is sent to LLM via `ai_suggestions.py`
4. AI generates:

   * review
   * improvements
   * tests
   * explanations
5. Results are displayed in UI
6. History is stored in `history.json`

---

## 🧠 Technologies Used

* **Frontend:** Streamlit
* **Backend Logic:** Python
* **LLM Integration:** HuggingFace
* **Data Storage:** JSON

---

## 💡 Key Concepts

* Prompt Engineering
* AI-assisted Code Review
* Session State Management
* Modular Python Design

---

## 🚀 Future Improvements

* FastAPI backend separation
* RAG (Retrieval Augmented Generation)
* GitHub repo analysis
* Deployment (AWS / Render)
* React frontend

---

## 👨‍💻 Author

**Manas Arora**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
