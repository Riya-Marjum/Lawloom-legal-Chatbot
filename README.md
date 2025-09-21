# Lawloom-legal-Chatbot
An AI-powered legal chatbot using RAG, Pinecone, and Google Generative AI to deliver accurate, context-aware legal responses
LegalBot is a chatbot designed to assist legal professionals, researchers, and individuals seeking legal advice by delivering accurate and contextual responses to complex legal queries. The chatbot leverages Retrieval-Augmented Generation (RAG) to enhance the quality of its responses, ensuring they are both relevant and well-informed.

With its ability to perform semantic searches and generate responses using Google Generative AI, LegalBot aims to simplify legal research, streamline document analysis, and provide quick access to legal insights.

Key Features
Tailored for Legal Applications:

Provides concise, accurate answers to legal queries.
Retrieves relevant legal documents or cases from a knowledge base.
Assists in understanding complex legal terminology and concepts.
Retrieval-Augmented Generation (RAG):

Combines semantic search with generative AI to deliver context-rich responses.
Uses Pinecone for efficient document retrieval and ranking.
NLP Techniques Utilized:

Semantic Embeddings: Vectorization of text using Hugging Face embeddings.
Vector Search: Efficient document retrieval using Pinecone.
Generative AI Integration:

Uses Google Generative AI (Gemini) for natural language response generation.
Custom prompt templates for coherent and context-aware outputs.
Web Framework and Interactive UI:

Built using Flask for backend services.
User-friendly chat interface for smooth interactions.
Usage
Clone the repository:https://github.com/Riya-Marjum/Lawloom-legal-Chatbot.git

git clone 
Install dependencies:

pip install -r requirements.txt
Set up environment variables:

Create a .env file in the project root with the following contents:
PINECONE_API_KEY=PINECONE_API_KEY
GEMINI_API_KEY=GEMINI_API_KEY
Run the application:

python app.py
Access the chatbot:

Open your browser and navigate to http://localhost:5000.
How It Works
Semantic Search with Pinecone:

Documents are embedded using Hugging Face models.
Pinecone indexes these embeddings for quick retrieval.
Contextual Query Augmentation:

User input is enriched with retrieved context using a RAG architecture.
Generative AI Response:

Google Generative AI (Gemini) generates a well-formed, contextual reply to the user query.
Web Interface:

Flask handles backend logic and serves the chat UI.
Future Improvements
Integrate neural network-based document ranking for improved retrieval.
Support multi-turn conversations by tracking chat history.
Add support for external APIs to expand the knowledge base dynamically.
Acknowledgements

This project is powered by:

Hugging Face
Pinecone
Google Generative AI
Flask
Special thanks to the open-source community for the incredible tools and frameworks.


