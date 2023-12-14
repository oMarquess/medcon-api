### MedCon API
# Overview
MedCon API is a Django-based application designed to process PDF documents, specifically focusing on loading, splitting, embedding, and storing these documents in a Chroma database. It utilizes several advanced libraries including LangChain for document handling and sentence transformer models for embeddings.

Features
PDF Loading: Utilizes PyPDFLoader for efficient loading of PDF documents.
Text Splitting: Splits text into manageable chunks using CharacterTextSplitter.
Text Embedding: Employs SentenceTransformerEmbeddings for generating embeddings of the text.
Chroma Database Integration: Stores and manages the documents and their embeddings in a Chroma database.
Installation
Before you begin, ensure you have Python and Django installed on your system. Additionally, the following libraries are required:
