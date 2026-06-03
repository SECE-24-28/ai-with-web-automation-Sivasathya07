# Groq AI Chatbot

A simple command-line AI chatbot built using Python and the Groq API.

## Features

* Interactive chatbot
* Streaming AI responses
* Maintains conversation history
* Simple terminal interface

## Requirements

```bash
pip install groq
```

## Usage

1. Add your Groq API key in the code:

```python
client = Groq(
    api_key="YOUR_GROQ_API_KEY"
)
```

2. Run the chatbot:

```bash
python chatbot.py
```

3. Start chatting:

```text
You: Hello
Bot: Hello! How can I help you today?
```

4. Type `exit` to quit.

## Example

```text
==================================================
🤖 Groq AI Chatbot
Type 'exit' to quit
==================================================

You: What is Python?

Bot: Python is a high-level programming language...
```

## Technologies Used

* Python
* Groq API

## Author

Created as a simple AI chatbot project using the Groq API.
