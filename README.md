# StorySpark

StorySpark is a Python-based application that generates creative stories using the Gemini API. This project allows users to input prompts and receive AI-generated stories in response.

## Features

- Generate unique stories from custom prompts
- Integrate with Gemini API for advanced text generation
- Simple and easy-to-use interface
- Includes voice recognition functionality, allowing users to listen to the generated stories. The application uses a speech synthesis library to convert text stories into audio output.

## Requirements

- Python 3.8+
- `requests` library

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/anandku06/StoryGenerator.git
    cd StoryGenerator
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Obtain your Gemini API key from [Google AI](https://ai.google.dev/).

## Usage

1. Set your Gemini API key as an environment variable:
    ```bash
    export GEMINI_API_KEY=your_api_key_here
    ```

2. Run the story generator:
    ```bash
    python story_generator.py
    ```

3. Enter your prompt and receive a generated story.

## Example

```python
from story_generator import generate_story

prompt = "A detective solves a mystery in a futuristic city."
story = generate_story(prompt)
print(story)
```

## Gemini API Integration

StoryGenerator uses the Gemini API to generate stories. The API is called via HTTP requests, sending your prompt and receiving the generated text.

For more details, see the [Gemini API documentation](https://ai.google.dev/docs).

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.