# AI Projects Collection

## Overview

This repository contains three Python-based AI projects demonstrating the use of modern AI APIs and automation tools.

### Projects Included

1. **Groq AI Chatbot**

   * Interactive command-line chatbot using the Groq API.
   * Supports real-time streaming responses.
   * Maintains conversation history during the session.

2. **AI Web Scraper and Summarizer**

   * Scrapes webpage content using Playwright.
   * Uses Google's Gemini AI to generate summaries, key points, and important facts.

3. **AI Image Generator**

   * Generates images from text prompts using the Stability AI API.
   * Saves generated images locally as PNG files.

---

## Technologies Used

* Python
* Groq API
* Google Gemini API
* Stability AI API
* Playwright
* Requests Library

---

## Features

### Groq AI Chatbot

* Real-time AI conversations
* Streaming responses
* Conversation memory
* Terminal-based interface

### AI Web Scraper and Summarizer

* Website scraping
* Dynamic webpage support
* AI-powered summarization
* Key point extraction

### AI Image Generator

* Text-to-image generation
* Custom prompt support
* Automatic image saving
* High-quality image creation

---

## Installation

Install the required libraries:

```bash
pip install groq
pip install google-generativeai
pip install playwright
pip install requests
playwright install
```

---

## Configuration

Replace the API key placeholders in the code with your own API keys.

### Groq

```python
api_key="YOUR_GROQ_API_KEY"
```

### Gemini

```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

### Stability AI

```python
API_KEY = "YOUR_STABILITY_AI_API_KEY"
```

---

## Usage

Run any project file using Python:

```bash
python filename.py
```

Examples:

```bash
python chatbot.py
python scraper.py
python image_generator.py
```

---

## Project Descriptions

### 1. Groq AI Chatbot

A simple chatbot that accepts user input and generates AI responses using the Groq API.

**Output Example**

```text
You: Hello

Bot: Hello! How can I assist you today?
```

---

### 2. AI Web Scraper and Summarizer

Scrapes content from a webpage and generates:

* Short Summary
* Key Points
* Important Facts

**Example Website**

```python
url = "https://en.wikipedia.org/wiki/Artificial_intelligence"
```

---

### 3. AI Image Generator

Generates AI images from natural language prompts.

**Example Prompt**

```text
a beautiful small white puppy is playing with butterflies in the evergreen forest, the climate is early morning, the sun is rising and the light is soft, the image is in 4k resolution
```

**Output**

```text
generated_image.png
```

---

## Learning Outcomes

* Working with AI APIs
* Prompt Engineering
* Web Scraping Automation
* AI-Based Content Summarization
* Text-to-Image Generation
* API Integration in Python

---

## Author

Developed using Python and various Generative AI APIs to explore conversational AI, content summarization, and image generation.

