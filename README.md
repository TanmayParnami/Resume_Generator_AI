# 📄 Gemini Multi-Template Resume Builder

The **Gemini Multi-Template Resume Builder** is an AI-powered web application built with **Streamlit** that generates complete, realistic resumes across multiple professional styles. Powered by **Google's Gemini 1.5 Flash** model, the app transforms a user-provided professional summary into fully-structured HTML resumes with optional PDF downloads.

---

## 🚀 Features

* **🔐 Secure API Integration**
  Uses the `GOOGLE_API_KEY` securely through environment variables or Streamlit secrets.

* **🧠 AI Resume Generation**
  Utilizes Gemini 1.5 Flash and LangChain's `PromptTemplate` to dynamically generate resumes based on user-provided input.

* **📄 Multi-Template Resume Creation**
  Supports 5 professional resume formats:

  * **Professional** – Standard corporate roles
  * **Creative** – Design and media-centric roles
  * **Technical** – Engineering and software development
  * **Executive** – Senior leadership and board-level positions
  * **Entry-Level** – Students and early-career professionals

* **📎 Resume Previews and Downloads**

  * Styled HTML previews within the app
  * Downloadable PDFs generated with ReportLab

* **🎨 Custom Styling**
  Clean, responsive UI with enhanced resume readability using CSS styling.

---

## 🛠️ Tech Stack

* **Frontend/UI**: [Streamlit](https://streamlit.io/)
* **LLM Integration**: [Google Generative AI (Gemini 1.5 Flash)](https://ai.google.dev/)
* **Templating**: [LangChain PromptTemplate](https://docs.langchain.com/docs/components/prompts/prompt-templates)
* **HTML Parsing**: [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
* **PDF Generation**: [ReportLab](https://www.reportlab.com/)

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
https://github.com/your-username/gemini-resume-builder.git
cd gemini-resume-builder
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure your API key

Set your **Google API Key** as an environment variable or in `.streamlit/secrets.toml`

#### Option A: Set Environment Variable

```bash
export GOOGLE_API_KEY="your-key-here"
```

#### Option B: Streamlit Secrets

Create a file `.streamlit/secrets.toml`:

```toml
GOOGLE_API_KEY = "your-key-here"
```

### 4. Run the app

```bash
streamlit run app.py
```

---

## 📸 Screenshots

*(Add screenshots or demo GIFs here to show how the app looks)*

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

* [Google Generative AI](https://ai.google.dev/)
* [Streamlit](https://streamlit.io/)
* [LangChain](https://www.langchain.com/)
* [ReportLab](https://www.reportlab.com/)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)

---

> Made with 💡 using LLMs to simplify resume building.
