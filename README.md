
## Overview
This project implements a smart chatbot capable of conversational AI with features like:
- Speech-to-Text and Text-to-Speech integration.
- Document ingestion from PDFs, PowerPoints, URLs, and YouTube videos for content-based querying.
- Dynamic retrieval-augmented generation (RAG) architecture for precise answers.

Built with modern libraries like LangChain, OpenAI GPT, ChromaDB, and SpeechRecognition.

## Features
- **Speech Input and Output**: 
  - Transcribes audio queries using OpenAI Whisper.
  - Responds with synthesized speech using Google Text-to-Speech (gTTS).
- **Document Processing**:
  - Supports uploading PDFs, PowerPoints, URLs, and YouTube video transcriptions.
  - Processes content for querying using vectorized embeddings stored in ChromaDB.
- **Context-Aware Conversational AI**:
  - Tracks chat history for enhanced query understanding.
  - Employs GPT-based language models for concise, accurate answers.
- **Interactive UI**:
  - Built using Panel, enabling easy integration of features.
  - Includes toggles for speech-based interaction.

## Technologies Used
- **Programming Languages**: Python
- **AI/ML Frameworks**: OpenAI GPT, LangChain
- **Speech Processing**: SpeechRecognition, Pydub, OpenAI Whisper
- **Text-to-Speech**: Google Text-to-Speech (gTTS)
- **Document Loaders**: LangChain PyPDFLoader, UnstructuredPowerPointLoader, WebBaseLoader, YouTubeAudioLoader
- **Database**: ChromaDB for vectorized storage
- **UI**: Panel

## Installation
1. Clone the repository:
   git clone <repository-url>
   cd <repository-folder>

Install required dependencies:

pip install -r requirements.txt
Set up environment variables:

Create a .env file in the root directory.
Add your OpenAI API key:
makefile


OPENAI_API_KEY=your_openai_api_key

Run the application:

python app.py

**Usage**

**Chatbot UI**
Launch the app and interact via the chatbot interface.
Toggle Speech Input/Output for voice-based conversations.
Upload documents or provide URLs for querying content.
**Speech Features**
Say "Hey Computer" to activate voice input.
Use "Stop" to terminate voice interaction.
**Adding Documents**
Upload PDFs or PowerPoints using the UI.
Provide YouTube links or URLs for processing external content.
**Contributing**
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature-name).
Open a pull request.

Google slide presentation - https://docs.google.com/presentation/d/1ITGmpc7X5W8LuTjNbkKx3VYX8ABugNTimITE-Cn88aU/edit?usp=sharing
