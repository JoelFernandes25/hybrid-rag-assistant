# hybrid-rag-assistant
Ask questions about your research papers and get answers grounded in the documents. An agentic RAG pipeline routes each query, retrieves with MMR, grades every chunk for relevance, and refuses to guess when nothing relevant is found. Built with LangGraph, Groq, FAISS, Streamlit and Docker.
