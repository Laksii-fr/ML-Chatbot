# ML-Chatbot

## FastAPI Chatbot

This is a chatbot project built using PyTorch for the machine learning model and FastAPI to serve the chatbot as an API. The chatbot processes user inputs and provides relevant responses based on predefined intents.

## Features

- **FastAPI** is used to expose the chatbot via an HTTP API.
- The chatbot is powered by a neural network built with **PyTorch**.
- **nltk** is used for tokenizing and preprocessing user inputs.
- Supports real-time responses through API calls.

## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.7 or above
- PyTorch (to run the model)
- FastAPI and Uvicorn (to serve the chatbot as an API)

## Installation

1. **Clone the repository**:
   ```git clone https://github.com/your-username/fastapi-chatbot.git```
   cd fastapi-chatbot
2. **How to Use**:
   Run the FastAPI server:
       ```uvicorn app:app --reload```
3. **Example Curl**
   ```
       curl -X 'POST' \
      'http://127.0.0.1:8000/chat/' \
      -H 'Content-Type: application/json' \
      -d '{"message": "Hi, how are you?"}'
   ``` 
