# Phase 3 – Project Design

## Project Name
EduGenie: Google Gemini Powered Learning Assistant

## System Architecture
EduGenie uses a web-based architecture with a FastAPI backend and an HTML/CSS/JavaScript frontend.

## Technologies
- Python
- FastAPI
- Google Gemini API
- HTML
- CSS
- JavaScript
- Jinja2
- Uvicorn

## Main Modules
- Question and Answer
- Concept Explanation
- Quiz Generation
- Text Summarization
- Personalized Learning Path

## Backend
The FastAPI backend receives requests from the frontend, processes the selected learning task, communicates with the Google Gemini API, and returns the generated response.

## Frontend
The frontend provides a simple interface where students can select a task, enter their question or learning content, and view the AI-generated result.

## Data Flow
Student Input → Web Interface → FastAPI Backend → Google Gemini API → AI Response → Web Interface

## Security Design
- Store the Gemini API key in an environment file.
- Do not commit the `.env` file to GitHub.
- Do not expose API keys in frontend code.
- Use `.gitignore` to protect sensitive files.
