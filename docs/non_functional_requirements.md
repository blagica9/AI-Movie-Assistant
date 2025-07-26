# ⚙️ Non-Functional Requirements – AI Movie Assistant App

This document lists the basic non-functional requirements for the AI Movie Assistant App.

---

## 1. Usability
- The interface should be clean and easy to use.
- Users should understand how to interact with the app without needing instructions.
- The design should support both desktop and mobile screens.

## 2. Performance
- The app should respond to user prompts within a few seconds.
- Movie results from the AI should appear without long delays.

## 3. Reliability
- The app should still function even if the AI API fails (e.g., display an error message).
- Basic error handling should be in place for failed API calls or network issues.

## 4. Security (Basic)
- User passwords (if stored) must be securely saved (e.g., using hashing).
- Only logged-in users can save favorites, like, or comment.

## 5. Cost
- The app should rely on free or low-cost tools and services.
- The OpenAI API should be used within its free tier or low-usage limits.
- SQLite is used as the database to avoid any hosting costs.

## 6. Maintainability
- The code should be clear, readable, and separated into logical components (frontend, backend, database).
- Basic comments and documentation should be added for future updates.

---

## Summary
This app should be lightweight, fast, and simple. It should run without expensive tools, and be easy to update or expand later.
