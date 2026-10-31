# 📚 RAG-Based PDF Question Answering System

An AI-powered PDF Question Answering System that allows users to upload PDF documents and ask questions in natural language. The application uses Retrieval-Augmented Generation (RAG) to retrieve relevant information and generate accurate, context-aware answers using Google Gemini.

## 🚀 Project Overview

Reading and searching through lengthy PDF documents can be time-consuming. This project simplifies the process by allowing users to upload a PDF and ask questions directly.

It retrieves the most relevant text from the document and uses Google's Gemini model to generate answers based on the retrieved context.

## ✨ Features

- 📄 Upload PDF documents.
- 📝 Extract text from PDF pages.
- ✂️ Split documents into smaller text chunks.
- 🧠 Generate semantic embeddings using Sentence Transformers.
- 🔍 Retrieve relevant information using FAISS.
- 🤖 Generate context-based answers using Google Gemini.
- 📑 Display source text and PDF page references.
- 💬 Interactive Streamlit chat interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Streamlit | Web application interface |
| Google Gemini API | AI-powered answer generation |
| Sentence Transformers | Text embeddings |
| FAISS | Vector similarity search |
| PyPDF | PDF text extraction |
| NumPy | Numerical operations |

## ⚙️ How It Works

1. **PDF Upload:** User uploads a PDF document.
2. **Text Extraction:** PyPDF extracts text from the document.
3. **Text Chunking:** Extracted text is divided into smaller chunks.
4. **Embedding Generation:** Sentence Transformers converts chunks into numerical embeddings.
5. **Vector Storage:** FAISS stores the embeddings for efficient similarity search.
6. **Question Processing:** The user's question is converted into an embedding.
7. **Information Retrieval:** FAISS retrieves the most relevant document chunks.
8. **Answer Generation:** Retrieved context and the question are sent to Google Gemini.
9. **Response Display:** The application displays the generated answer and source page references.

## 🏗️ Project Structure

```text
rag-pdf-question-answering-system/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 💻 Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/rag-pdf-question-answering-system.git
```

### 2. Navigate to the project folder

```bash
cd rag-pdf-question-answering-system
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Get your Gemini API key

Generate an API key from [Google AI Studio](https://aistudio.google.com/apikey).

### 5. Run the application

```bash
streamlit run app.py
```

### 6. Use the application

- Enter your Gemini API key in the sidebar.
- Upload a PDF document.
- Click **Process PDF**.
- Enter your question in the chat interface.
- View the generated answer and retrieved PDF sources.

## 🔐 Security

- Gemini API keys should never be uploaded to GitHub.
- API keys are entered through the application sidebar.
- Do not upload confidential PDF documents to public repositories.

## 🔮 Future Enhancements

- Multiple PDF document support.
- Conversation history and follow-up questions.
- OCR support for scanned PDF documents.
- Improved retrieval accuracy.
- Downloadable answer summaries.
- Chat history management.

## 👩‍💻 Author

**Laasya Reddy Kadumuri**

B.Tech – Computer Science and Engineering

---

⭐ If you find this project interesting, feel free to explore the repository!
