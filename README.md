# MemoBoat

An AI-powered memo generator that converts raw meeting notes into structured summaries, action items, and key decisions.

## Live Demo
https://memoboat.onrender.com

## About
Meeting notes are often unstructured and difficult to act on. MemoBoat takes raw notes, processes them through the OpenAI API, and returns a clean memo with a summary, action items, and key decisions.

## Tech Stack
- Python, Flask
- SQLite
- OpenAI API (GPT-4.1)
- HTML, CSS, JavaScript

## Setup Instructions
1. Clone the repo
2. Create a virtual environment: `python -m venv venv`
3. Activate it — Windows: `venv\Scripts\activate.bat`
4. Install dependencies: `pip install -r requirements.txt`
5. Add your OpenAI API key to a `.env` file: `OPENAI_API_KEY=your_key_here`
6. Initialize the database: `python init_db.py`
7. Run the app: `flask run`
8. Open http://127.0.0.1:5000