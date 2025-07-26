# 🧱 Architecture – AI Movie Assistant App

This document describes the architecture of the AI Movie Assistant App, including its main components and how they interact.

---

## 🔧 Application Layers

### 1. Frontend (User Interface)
- Technology: HTML/CSS/JS (or optionally React)
- Provides the interface where users can:
  - Register and log in
  - Enter prompts to receive movie suggestions
  - View, like, comment on, and save movies

### 2. Backend (Server)
- Technology: Python (Flask or Django)
- Handles:
  - User authentication
  - API endpoint for prompt submission
  - Requests to the OpenAI API
  - Database interaction (likes, comments, favorites)

### 3. Database
- Technology: SQLite (lightweight, file-based DB)
- Stores:
  - User accounts
  - Saved favorites
  - Comments
  - Likes

### 4. OpenAI Integration
- External API: OpenAI GPT API
- The backend sends the user’s prompt to the API
- Receives back a list of recommended movies in JSON format

---

## 📊 Simple Component Diagram

