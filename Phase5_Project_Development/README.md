# Phase 5 – Project Development

## Project Name
EduGenie: Google Gemini Powered Learning Assistant

## Development Overview
The EduGenie application is developed as a web-based AI learning assistant using Python, FastAPI, Google Gemini API, HTML, CSS, and JavaScript.

## Backend Development
The FastAPI backend provides endpoints for the main learning features:

- `/qa` – Question and Answer
- `/explain` – Concept Explanation
- `/quiz` – Quiz Generation
- `/summarize` – Text Summarization
- `/learn/recommendations` – Personalized Learning Path

## AI Modules

### Question and Answer
Uses Google Gemini to provide clear and student-friendly answers.

### Concept Explanation
Uses Google Gemini to explain educational topics in simple language with definitions, main points, examples, and conclusions.

### Quiz Generation
Uses Google Gemini to generate three multiple-choice questions with four options and the correct answers.

### Text Summarization
Uses Google Gemini to summarize educational text while keeping the important points.

### Personalized Learning Path
Uses Google Gemini to create a learning path from beginner to advanced concepts with practice activities.

## Frontend Development
The frontend provides:
- Task selection
- Text input
- Submit button
- AI response display
- Simple student-friendly interface

## Integration
The frontend sends requests to the FastAPI backend. The backend processes the request through the appropriate AI module and returns the generated response.

## Security
The Gemini API key is stored in the `.env` file and excluded from GitHub using `.gitignore`.

## Development Result
The completed application provides five AI-powered educational features through a single web interface.
