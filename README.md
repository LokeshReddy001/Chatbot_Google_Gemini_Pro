# Google Gemini Pro Chatbot

This chatbot is powered by Google Gemini Pro, leveraging advanced language models to create engaging conversational experiences.

Explore the Chatbot [here](https://chatbot-geminipro.streamlit.app/)
## Installation

To set up the chatbot, follow these steps:

1. **Install Dependencies:**
    ```bash
    pip install -q -U google-generativeai
    pip install streamlit
    ```

2. **Export API Key:**
    Export your API key to the environment variable `GOOGLE_API_KEY`. Replace `API_KEY` with your actual Google API key. If you don't have an API key, you can get one [here](https://ai.google.dev/)
    ```bash
    export GOOGLE_API_KEY="API_KEY"
    ```

## Usage

1. **Run the Chatbot:**
    ```bash
    streamlit run chatbot.py
    ```
    Replace `chatbot.py` with the filename containing your chatbot code.

2. **Interacting with the Chatbot:**
    Open a web browser and navigate to the provided URL after running the Streamlit app. Interact with the chatbot by typing messages and receiving responses.


