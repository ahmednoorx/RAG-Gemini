# RAG-Gemini

An advanced Retrieval-Augmented Generation (RAG) system using Gemini for document-based Q&A.

---

## 🚀 Overview

**RAG-Gemini** is a Streamlit web app that lets you ask questions about a PDF document using Google Gemini’s AI.  
It loads your PDF, splits it into chunks, creates embeddings, and answers your questions using the latest Gemini model.

---

## 📝 Features

- Upload and process PDF documents
- Ask questions in natural language
- Answers are generated using Gemini Pro (Google Generative AI)
- Uses vector search for accurate, context-aware responses

---

## 📦 Requirements

- Python 3.8+
- [Google Gemini API key](https://ai.google.dev/gemini-api/docs/api-key)
- See `requirements.txt` for all Python dependencies

---

## ⚡️ Quickstart

1. **Clone the repo**
    ```bash
    git clone https://github.com/ahmednoorx/RAG-Gemini.git
    cd RAG-Gemini
    ```

2. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your API key**
    - Get your Gemini API key [here](https://ai.google.dev/gemini-api/docs/api-key)
    - Create a `.env` file in the project folder:
      ```
      GOOGLE_API_KEY=your_api_key_here
      ```

4. **Add your PDF**
    - Place your PDF (e.g., `my_paper.pdf`) in the project folder.

5. **Run the app**
    ```bash
    streamlit run app.py
    ```

6. **Ask questions!**
    - Use the chat input at the bottom to ask about your PDF.

---

## 🛠️ Project Structure

```
RAG-Gemini/
│
├── app.py              # Main Streamlit app
├── requirements.txt    # Python dependencies
├── my_paper.pdf        # Your PDF document
├── .env                # API key (not tracked by git)
└── README.md           # This file
```

---

## 🙏 Credits

- [LangChain](https://python.langchain.com/)
- [Google Gemini](https://ai.google.dev/)
- [Streamlit](https://streamlit.io/)

---

## 📄 License

MIT License

---