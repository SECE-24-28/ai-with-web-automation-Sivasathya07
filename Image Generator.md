# AI Image Generator using Stability AI

## Overview

This project is a Python-based AI image generator that uses the Stability AI API to create images from text prompts.

The user provides a descriptive prompt, and the application generates a high-quality AI image and saves it locally as a PNG file.

## Features

* Text-to-image generation
* Stability AI integration
* Custom prompt support
* Automatic image saving
* Simple single-file implementation

## Technologies Used

* Python
* Requests Library
* Stability AI API

## Installation

Install the Requests library:

```bash
pip install requests
```

## Configuration

Replace the placeholder API key with your Stability AI API key:

```python
API_KEY = "YOUR_STABILITY_AI_API_KEY"
```

## Usage

Run the Python file:

```bash
python main.py
```

## Example Prompt

```text
a beautiful small white puppy is playing with butterflies in the evergreen forest, the climate is early morning, the sun is rising and the light is soft, the image is in 4k resolution
```

## Output

The generated image will be saved as:

```text
generated_image.png
```

Example terminal output:

```text
✅ Image generated successfully!
Saved as generated_image.png
```

## File Structure

```text
main.py
README.md
```

## Future Enhancements

* User input prompts
* Multiple image generation
* Different image formats
* Web-based interface
* Prompt history

## Author

Developed using Python and Stability AI API.
