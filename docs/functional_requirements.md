# ✅ Functional Requirements – AI Movie Assistant App

This document outlines the core features that the AI Movie Assistant App must support in its initial version.

---

## 1. User Registration and Login
- Users should be able to register with an email and password.
- Users should be able to log in and log out.
- Logged-in users can access features like liking and saving movies.

## 2. Enter Prompt for Movie Recommendation
- Users can write a text prompt describing the type of movie they want to watch (e.g., "a romantic film with a sad ending").
- The app will send this prompt to the OpenAI API (ChatGPT) for processing.
- The response will include a list of recommended movies in structured format (e.g., title, description, year, genre).

## 3. View Recommended Movies
- The app will display a list of movies returned by the AI.
- Each movie will be shown with basic details: title, short description, release year.

## 4. Like a Movie
- Logged-in users can like movies from the recommended list.
- Likes are saved and visible only to that user.

## 5. Save Movies to Favorites
- Users can save movies to a "Favorites" list.
- The list can be accessed through a separate view or page.

## 6. Comment on a Movie
- Users can add comments to recommended movies.
- Comments are visible only to the logged-in user (for simplicity).

---

## (Optional / Later Features)
- Notifications for new movie suggestions or weekly recommendations
- Tagging or organizing favorites by genre or mood
- Sharing a movie suggestion with a friend

---

## Summary
The core functionality focuses on prompt-based movie recommendations with basic user interaction: authentication, liking, saving, and commenting.
