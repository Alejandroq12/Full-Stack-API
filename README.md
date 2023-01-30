# API Development and Documentation Final Project

## Trivia App

A bunch of team members got the idea to hold trivia on a regular basis and created a webpage to manage the trivia app and play the game, but their API experience is limited and still needs to be built out.

That's where I come in! Help them finish the trivia app so they can start holding trivia and seeing who's the most knowledgeable of the bunch. The application must:

1. Display questions - both all questions and by category. Questions should show the question, category and difficulty rating by default and can show/hide the answer.
2. Delete questions.
3. Add questions and require that they include question and answer text.
4. Search for questions based on a text query string.
5. Play the quiz game, randomizing either all questions or within a specific category.

Completing this trivia app will give me the ability to structure plan, implement, and test an API - skills essential for enabling your future applications to communicate with others.

## About the Stack

### Backend

The [backend](./backend/README.md) directory contains a partially completed Flask and SQLAlchemy server. I will work primarily in `__init__.py` to define my endpoints and can reference models.py for DB and SQLAlchemy setup. These are the files I'd want to edit in the backend:

1. `backend/flaskr/__init__.py`
2. `backend/test_flaskr.py`

> View the [Backend README](./backend/README.md) for more details.

### Frontend

The [frontend](./frontend/README.md) directory contains a complete React frontend to consume the data from the Flask server. 

1. What are the end points and HTTP methods the frontend is expecting to consume?
2. How are the requests from the frontend formatted? Are they expecting certain parameters or payloads?

I must pay special attention to what data the frontend is expecting from each API response to help guide how to format my API specially here:

1. `frontend/src/components/QuestionView.js`
2. `frontend/src/components/FormView.js`
3. `frontend/src/components/QuizView.js`


> View the [Frontend README](./frontend/README.md) for more details.
