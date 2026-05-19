
# Multi-LLM RAG Chatbot

A Retrieval-Augmented Generation (RAG) based conversational AI project built using LangChain, Groq Llama3, OpenAI APIs, Hugging Face models, and vector search workflows.

This repository demonstrates how to build AI assistants capable of:
- Document question answering
- Conversational memory
- Semantic retrieval
- Multi-LLM integration
- API-based chatbot deployment

---

## Features

- Retrieval-Augmented Generation (RAG)
- LangChain pipelines
- Groq + Llama3 integration
- OpenAI model support
- Hugging Face model experiments
- FastAPI chatbot backend
- PDF document querying
- Vector search workflows
- ObjectBox integration

---

## Project Structure

```bash
.
├── api/                # API integration examples
├── chatbot/            # Chatbot applications
├── chain/              # Retrieval and LangChain workflows
├── groq/               # Groq + Llama3 integrations
├── huggingface/        # Hugging Face model experiments
├── objectbox/          # Vector database experiments
├── openai/             # OpenAI-based RAG examples
├── rag/                # RAG pipeline notebooks
├── requirements.txt
└── README.md
```

---

## Tech Stack

- Python
- LangChain
- OpenAI API
- Groq API
- Llama3
- Hugging Face Transformers
- FastAPI
- Vector Search / Embeddings

---

## Example Use Cases

### Document Question Answering
Upload PDF/text documents and query them using natural language.

### Conversational AI
Build chatbot interfaces powered by multiple LLM providers.

### Semantic Retrieval
Use embeddings and vector search to retrieve relevant context before generation.

---

## Setup

### 1. Clone Repository

```bash
git clone <repository-url>
cd Updated-Langchain-main
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate environment:

#### Windows
```bash
venv\Scripts\activate
```

#### Linux / macOS
```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
HUGGINGFACEHUB_API_TOKEN=your_hf_token
```

---

## Recommended Improvements

- Convert notebook prototypes into modular Python packages
- Add frontend UI using Streamlit or React
- Add Docker support
- Add evaluation metrics for retrieval quality
- Add deployment configuration

---

## Resume Project Description

**Multi-LLM RAG Chatbot using LangChain**

Built a Retrieval-Augmented Generation (RAG) based AI assistant using LangChain, Groq Llama3, OpenAI APIs, and Hugging Face models to enable contextual document querying and conversational AI workflows.

### Suggested Resume Bullets

- Developed a RAG-based conversational AI system using LangChain and Llama3 for contextual document retrieval.
- Integrated Groq, OpenAI, and Hugging Face APIs for multi-model experimentation and response generation.
- Implemented semantic search pipelines using embeddings and vector retrieval techniques.
- Built API-driven chatbot workflows for document-based question answering.

---

## License

This project is available under the MIT License.
