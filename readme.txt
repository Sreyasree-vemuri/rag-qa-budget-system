# Multilingual Budget RAG Chatbot

A sophisticated Retrieval-Augmented Generation (RAG) system that enables users to query Indian Budget documents through voice, text, and multiple languages using Google Gemini and Pinecone.

# Features

- PDF Processing: Upload and process budget documents
- Voice Interface: Speech-to-text and text-to-speech capabilities
- Multilingual Support: 10+ Indian languages with translation
- Advanced RAG: Multi-query retrieval with source citations
- Real-time Responses: Powered by Google Gemini 2.0 Flash
- Vector Database: Pinecone for efficient similarity search

# Tech Stack

- LLM: Google Gemini 2.0 Flash
- Embeddings: Google Generative AI Embeddings
- Vector DB: Pinecone
- Framework: LangChain
- Frontend: Streamlit
- Speech: SpeechRecognition, gTTS
- Translation: Deep Translator

# Demo Applications

1. Basic RAG: `streamlit_app.py` - Core Q&A functionality
2. Voice-Enabled: `streamlit_app_voice.py` - Speech input/output
3. Multilingual: `streamlit_app_translator.py` - 10 language support

# Prerequisites

- Python 3.8+
- Google AI Studio API Key
- Pinecone API Key
- Microphone (for voice features)

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/rag-budget-chatbot.git
cd rag-budget-chatbot