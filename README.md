# PDF Question-Answering RAG Pipeline

A Retrieval-Augmented Generation (RAG) system built with LangChain, ChromaDB, and Google Gemini.

## Overview
- Loads PDF documents with `PyPDFLoader`
- Splits document contents into manageable chunks with `CharacterTextSplitter`
- Embeds and stores chunks using `GoogleGenerativeAIEmbeddings` and `Chroma`
- Answers questions grounded in the document context using Gemini

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<your-repo-name>.git
   cd <your-repo-name>
