# 📄 AI-Powered Research Paper Summarizer

An intelligent **Generative AI** application that summarizes research papers into structured, easy-to-understand insights using **Groq Llama 3.1**, **LangChain**, and **Gradio**.

Developed to help **students, researchers, and professionals** quickly understand academic papers without reading every page.

---

## 🚀 Features

- 📄 Upload research papers in PDF format
- 🤖 AI-powered summarization using **Groq Llama 3.1**
- 📌 Extracts:
  - Title
  - Objectives
  - Methodology
  - Datasets
  - Key Findings
  - Results
  - Limitations
  - Future Work
- ⚡ Fast inference with Groq API
- 🎨 Interactive Gradio web interface
- 🧠 Powered by LangChain prompt orchestration

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend Development |
| Groq API | LLM Inference |
| Llama 3.1 | Large Language Model |
| LangChain | Prompt & LLM Orchestration |
| Gradio | Web Interface |
| PyPDF | PDF Text Extraction |
| dotenv | Environment Variable Management |

---

## 📂 Project Structure

```
Research-Paper-AI-Summarizer/
│
├── app.py
├── requirements.txt
├── .env
├── README.md
├── assets/
│   └── banner.png
└── sample_papers/
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/research-paper-ai-summarizer.git

cd research-paper-ai-summarizer
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Create a `.env` File

```env
GROQ_API_KEY=your_groq_api_key
```

### Run the Application

```bash
python app.py
```

or

```bash
gradio app.py
```

---

## 💻 How It Works

1. Upload a research paper (PDF).
2. The application extracts the document text.
3. LangChain sends the content to **Groq Llama 3.1**.
4. The model generates a structured summary.
5. Results are displayed instantly through the Gradio interface.

---

## 🎯 Use Cases

- Research Paper Analysis
- Literature Reviews
- Academic Study
- Student Learning
- Technical Document Summarization
- Knowledge Extraction

---

## 📈 Future Improvements

- Multiple LLM support (GPT, Claude, Gemini)
- PDF highlighting
- Export summary to Word/PDF
- Citation extraction
- Multi-document summarization
- Research paper Q&A chatbot

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

Feel free to fork this repository and submit a pull request.

---

## 👨‍💻 Developer

**Muhammad Waseem**

**Data Scientist & AI Engineer**

**Qaira Tech**

Building AI solutions that create real-world impact.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is licensed under the **MIT License**.

Copyright © 2026 Muhammad Waseem | Qaira Tech
