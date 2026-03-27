🚀 AI-Powered Placement Knowledge Base (RAG)
A high-performance Retrieval-Augmented Generation (RAG) system designed to provide instant, context-aware answers from university placement materials and technical documentation.

Built with FastAPI, LangChain, and Groq, this project demonstrates a production-grade approach to handling private data with LLMs.

🛠️ Tech Stack
Language: Python 3.10+

Orchestration: LangChain

LLM: Groq (Llama-3-70b/Mixtral) for ultra-fast inference.

Vector Database: ChromaDB (Local persistent storage).

API Framework: FastAPI

Package Manager: uv (for 10x faster dependency resolution).

✨ Key Features
Efficient Document Ingestion: Uses PyPDFDirectoryLoader to process bulk PDF materials.

Smart Context Chunking: Implements RecursiveCharacterTextSplitter to maintain semantic meaning within text fragments.

High-Speed Retrieval: Leverages Groq’s LPU (Language Processing Unit) for near-instant response generation.

Persistent Vector Store: Embeddings are stored locally in ChromaDB, ensuring data isn't re-processed on every run.

API-First Design: Fully documented endpoints via Swagger/OpenAPI.

📂 Project Structure
Plaintext
├── data/               # Source PDF files (Placement/Academic notes)
├── chroma_db/          # Persistent vector database storage
├── main.py             # FastAPI application and RAG logic
├── .env                # API keys (ignored by git)
└── requirements.txt    # Project dependencies


<img width="1241" height="490" alt="image" src="https://github.com/user-attachments/assets/a442caaf-df65-47b5-87b7-8a46fc1df450" />

