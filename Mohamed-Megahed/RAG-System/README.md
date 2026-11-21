### RAG – Automated Document Ingestion Pipeline

Built an automated RAG pipeline using **n8n, Google Drive, Google Embeddings, and Supabase Vector Store**.

The workflow automatically detects newly created files in Google Drive, downloads the documents, processes and splits their content using a Recursive Character Text Splitter, generates vector embeddings, and stores them in Supabase for semantic search and retrieval.

**Technologies Used:**
- n8n – Workflow Automation
- Google Drive – Document Storage and Trigger
- Google Embeddings – Text Embedding Generation
- Recursive Character Text Splitter – Document Chunking
- Supabase Vector Store – Vector Storage and Retrieval
