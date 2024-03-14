# AI-Based Questionnaire

This project is a Python-based application for conducting a questionnaire using various AI technologies. The application utilizes speech recognition, natural language processing, and generative AI to interact with users and generate responses.

## Requirements
- Python 3.x
- `pyresparser` library: for parsing resumes
- `playsound` library: for playing audio files
- `speech_recognition` library: for speech recognition
- `gtts` library: for text-to-speech conversion
- `pathlib` library: for handling file paths
- `google.generativeai` library: for generative AI capabilities
- `IPython` library: for displaying Markdown content
- `nltk` library: for natural language processing

## Installation
1. Clone or download the repository.
2. Install the required Python libraries using pip:
    ```
    pip install pyresparser playsound SpeechRecognition gtts nltk
    ```
3. Sign up for an API key for the generative AI from [Google's Generative AI](https://console.cloud.google.com/marketplace/product/google/generativeai.googleapis.com).
4. Set up the API key using:
    ```python
    genai.configure(api_key='YOUR_API_KEY')
    ```
5. Ensure you have the necessary models loaded, such as the 'gemini-pro' model.
    ```python
    model = genai.GenerativeModel('gemini-pro')
    ```

## Usage
1. Run the Python script containing the questionnaire application.
2. Follow the prompts or instructions to proceed with the questionnaire.
3. Users can interact with the questionnaire either by speaking their responses or typing them out.
4. The application processes the responses using natural language processing and generative AI to generate appropriate outputs.



## Credits
- [PyResparser](https://github.com/OmkarPathak/pyresparser)
- [Google Generative AI](https://cloud.google.com/blog/products/ai-machine-learning/getting-started-with-the-generative-ai-models-in-google-cloud)
- [NLTK](https://www.nltk.org/)

