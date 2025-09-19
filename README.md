# Better Notes

An AI-powered note enhancement application that improves the clarity and coherence of your notes using textbook content and GPT-4.

## What it does

Better Notes helps students enhance their study notes by:
- Uploading PDF textbooks to build a knowledge base
- Processing your notes through AI to improve clarity and add relevant context
- Using vector search to find the most relevant textbook sections for your notes
- Returning enhanced notes in a clean, formatted output

## How it works

1. Upload a PDF textbook - the system extracts and indexes the content
2. Submit your notes through the web interface
3. The AI finds relevant textbook sections and enhances your notes
4. Get back improved notes with better structure and additional context

## Tech Stack

- **Frontend**: React with Radix UI components
- **Backend**: FastAPI with Python
- **AI**: OpenAI GPT-4 for note enhancement
- **Search**: Pinecone for vector embeddings and similarity search
- **PDF Processing**: PyMuPDF for text extraction
