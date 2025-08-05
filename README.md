# Upgrad_RAG_Assg_Legal_Ashwini-H-V

Upgrad Legal QnA System – Project Summary (RAG & NLP)
This project involved building a Legal Question-Answering (QnA) system using a Retrieval-Augmented Generation (RAG) approach, integrating LangChain, OpenAI’s GPT-3.5-turbo, and text-embedding-3-small, with vector databases like FAISS and Qdrant.

Legal documents were preprocessed, chunked, and embedded for semantic search. These embeddings were stored in vector databases to support similarity-based retrieval. A custom LangChain pipeline was developed to generate context-aware answers. The system was evaluated using benchmark answers within pandas DataFrames.

✅ Key Highlights
The model produced relevant answers when appropriate source context was available.

Token limitations constrained input size, which impacted response accuracy.

FAISS and Qdrant showed comparable retrieval performance.

A custom LangChain RAG chain successfully supported contextual answering.

🚀 Future Improvements
Scale the system to support larger datasets

Enhance evaluation methodology

Optimize the retrieval and chunking pipeline

This project showcases the complete pipeline for building a RAG-based QnA system tailored to legal document understanding and retrieval.
