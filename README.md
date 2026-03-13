# Enterprise Assistant RAG System

An enterprise-grade **Retrieval-Augmented Generation (RAG)** system designed to enable intelligent document retrieval and AI-powered question answering over enterprise knowledge bases.

The system ingests documents, indexes them into a vector database, and allows users to query enterprise data using natural language powered by large language models.

---

## 🚀 Features

* 📄 Document ingestion pipeline
* 🔎 Semantic search using vector embeddings
* 🤖 AI-powered question answering
* ⚡ Fast retrieval pipeline
* 🧠 Retrieval-Augmented Generation architecture
* 🐳 Dockerized deployment
* 📦 Modular architecture for enterprise use

---

## 🏗 Project Architecture

The project is divided into modular components:

```
enterprise-assistant-rag-system/
│
├── api/                # API service for user queries
├── ingestion/          # Document ingestion pipeline
├── retrieval/          # Vector search and retrieval
├── docker-compose.yml  # Multi-service orchestration
├── Dockerfile          # Container configuration
├── requirements.txt    # Python dependencies
```

### Core Modules

**API Layer**

* Handles user queries
* Connects retrieval system with LLM response generation

**Ingestion Pipeline**

* Loads enterprise documents
* Creates embeddings
* Stores them in vector database

**Retrieval Engine**

* Performs similarity search
* Retrieves relevant knowledge chunks

---

## 🧠 How RAG Works

1. Documents are ingested and chunked
2. Text is converted into vector embeddings
3. Embeddings are stored in a vector database
4. User query is embedded
5. Similar documents are retrieved
6. Retrieved context is passed to the LLM
7. The model generates a grounded answer

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/ankitkumarbyte/Enterprise-Assistant-RAG-System-.git
cd Enterprise-Assistant-RAG-System-
```

Create virtual environment:

```bash
python -m venv venv
```

Activate environment:

```bash
# Windows
venv\Scripts\activate

# Linux / Mac
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🐳 Run with Docker

```bash
docker-compose up --build
```

---

## 🧪 Run API

```bash
python api/main.py
```

---

## 🔧 Technologies Used

* Python
* FastAPI
* Vector Databases
* Large Language Models (LLMs)
* Docker
* Retrieval-Augmented Generation (RAG)

---

## 📊 Use Cases

* Enterprise knowledge assistants
* Internal document search
* AI customer support systems
* Intelligent knowledge management
* Corporate knowledge retrieval

---

## 🔮 Future Improvements

* Multi-document format support
* Streaming responses
* UI dashboard
* Authentication and RBAC
* Hybrid search (keyword + vector)

---

## 👨‍💻 Author

**Ankit Kumar**

GitHub: https://github.com/ankitkumarbyte

---

## 📜 License

This project is released under the MIT License.
