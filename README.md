# PaperPilot
PaperPilot uses a RAG-based architecture. Research papers are uploaded through the frontend, processed by a FastAPI backend, converted into embeddings, and stored in a vector database like FAISS. When a user asks questions, the system retrieves relevant chunks and sends them to a Large Language Model to generate accurate answers.
