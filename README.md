# RAG-LLM-Chatbot
Task for RAG LLM-Chatbot for AI-d. Mostlyon data preprocessing

Build a pipeline that ingests Ai-D documents, chunks them appropriately, generates embeddings, and upserts into the vector store.

Acceptance Criteria:

- Supports PDF, DOCX, and plain text input formats
- Chunk size and overlap configurable
- Idempotent — re-running does not duplicate records
