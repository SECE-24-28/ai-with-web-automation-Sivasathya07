# AI Web Scraper and Summarizer

## Overview

This project is a simple Python application that scrapes content from a website using Playwright and generates a summary using Google's Gemini AI model.

The application extracts webpage text and provides:

* Short Summary
* Key Points
* Important Facts

## Features

* Website content scraping
* Dynamic page support with Playwright
* AI-powered summarization using Gemini
* Simple single-file implementation
* Terminal-based output

## Technologies Used

* Python
* Playwright
* Google Gemini API

## Installation

Install the required packages:

```bash
pip install playwright google-generativeai
playwright install
```

## Configuration

Replace the API key placeholder in the code:

```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

## Usage

Run the Python file:

```bash
python app.py
```

The script will:

1. Open the target website.
2. Extract webpage content.
3. Send the content to Gemini AI.
4. Generate a summary, key points, and important facts.

## Example URL

```python
url = "https://en.wikipedia.org/wiki/Artificial_intelligence"
```

## Sample Output

```text
==================================================
SUMMARY
==================================================

Short Summary:
Artificial Intelligence (AI) is a branch of computer science
that focuses on creating intelligent systems.

Key Points:
- AI enables machines to perform human-like tasks.
- Machine Learning is a subset of AI.
- AI is widely used in various industries.

Important Facts:
- AI research began in the 1950s.
- Deep learning has significantly advanced AI capabilities.
```

## Requirements

```text
playwright
google-generativeai
```

## Author

Developed using Python, Playwright, and Google Gemini AI.
