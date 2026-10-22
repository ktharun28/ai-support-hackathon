# AI-Powered IT Support Assistant

## Problem Statement
Build an application that accepts an IT support ticket, identifies similar historical tickets, and recommends relevant solutions.

## Team Structure

### Person A — Frontend
- Build the user interface using Streamlit.
- Accept ticket descriptions from users.
- Display recommended solutions.

### Person B — Backend
- Build REST API endpoints using FastAPI.
- Receive requests from the frontend.
- Connect the frontend to the AI engine.

### Person C — AI/ML
- Prepare historical ticket data.
- Use TF-IDF and cosine similarity to identify similar tickets.
- Return relevant historical solutions.

## Technology Stack
- Language: Python
- Frontend: Streamlit
- Backend: FastAPI
- AI/ML: scikit-learn
- Version Control: Git and GitHub

## Architecture
Streamlit Frontend → FastAPI Backend → AI Engine → Recommended Solutions

## Success Criteria
- Users can submit a ticket.
- The system returns relevant historical tickets and suggested solutions.
- Invalid or empty input is handled gracefully.
- The application can be demonstrated locally.
