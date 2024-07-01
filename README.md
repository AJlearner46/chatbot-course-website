# Brainlox Technical Courses Chatbot

This project implements a custom chatbot using Langchain to answer questions about technical courses from Brainlox.

## Setup

1. Clone the repository
2. Create a virtual environment and activate it
3. Install dependencies: `pip install -r requirements.txt`

## Running the application

1. Run the Flask app: `python app.py`
2. The API will be available at `http://localhost:5000/chat`

## API Usage

Send a POST request to `/chat` with the following JSON body:

```json
{
  "query": "What technical courses are available?",
  "chat_history": []
}
