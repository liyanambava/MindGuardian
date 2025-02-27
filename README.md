# MindGuardian
# MindGuardian Chatbot

MindGuardian is a mental health counseling chatbot powered by Groq's LLM, Pinecone vector search, and Langchain. It provides users with expert mental health support by understanding their queries, retrieving relevant context, and offering thoughtful, contextual responses.

## Features

- **Conversational Memory:** Remembers the last 40 messages for personalized, context-aware responses.
- **Keyword Summarization:** Extracts key topics from user inputs to refine search results.
- **Contextual Retrieval:** Queries a Pinecone vector database to fetch the most relevant past conversations or knowledge snippets.
- **Streamlit Interface:** A user-friendly web interface for seamless interaction.
- **Clear Chat History:** Easily reset conversations for fresh starts.
- **Multi-Page App:** Navigate through sections like Problem Statement, Goals, and Collaborators.

## Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python, Langchain, Pinecone, Groq API
- **Embeddings:** Sentence Transformers (nomic-ai/nomic-embed-text-v1.5)
