# 🚀 Resume Genie – AI-Powered Resume Toolkit

Resume Genie is an AI-powered career assistant built with Streamlit, Groq LLMs, and LangChain. It helps job seekers create professional application materials, analyze resumes, and receive personalized career guidance through an interactive chatbot.

## ✨ Features

### 📄 AI Cover Letter Generator

* Generates tailored cover letters from your resume and job description.
* Matches skills and experience to specific job requirements.
* Download generated cover letters in Markdown format.

### 📊 Resume vs Job Description Matcher

* Calculates resume-job compatibility.
* Provides ATS compatibility analysis.
* Highlights matched and missing keywords.
* Generates improvement suggestions and skill-gap analysis.

### 🔍 Resume Checker

* Evaluates resume quality and effectiveness.
* Reviews clarity, formatting, ATS readiness, and skill presentation.
* Suggests improvements and career growth opportunities.

### 💬 AI Career Coach

* Interactive chatbot powered by Groq LLM.
* Answers career-related questions based on your uploaded resume.
* Provides interview preparation, resume advice, and career guidance.

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **LLM Provider:** Groq
* **Model:** Llama 3.3 70B Versatile
* **Framework:** LangChain
* **PDF Processing:** PyPDFLoader
* **Language:** Python

---

## 📂 Project Structure

```bash
Resume-Genie/
│
├── main.py
├── logo.png
├── requirements.txt
├── .streamlit/
│   └── secrets.toml
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/resume-genie.git
cd resume-genie
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Mac/Linux:

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure Groq API Key

Create:

```bash
.streamlit/secrets.toml
```

Add:

```toml
GROQ_API_KEY = "your_groq_api_key"
```

---

## ▶️ Run the Application

```bash
streamlit run main.py
```

The application will launch in your browser at:

```bash
http://localhost:8501
```

---

## 🎯 Use Cases

* Students preparing for placements
* Freshers building their first resume
* Professionals switching careers
* Job seekers optimizing ATS scores
* Interview preparation and career coaching

---

## 🔒 Privacy

* Resume data is processed locally during the session.
* No resume content is permanently stored.
* API keys should be securely managed using Streamlit Secrets or environment variables.

---

## 🚀 Future Enhancements

* Resume builder with templates
* Multi-format export (PDF/DOCX)
* LinkedIn profile optimization
* Interview simulator
* Portfolio analysis
* Multi-language support

---

## 👨‍💻 Author

**Ganesh Pawar**

Passionate about AI, Machine Learning, Generative AI, and Full-Stack Development.

If you found this project useful, consider giving it a ⭐ on GitHub!
