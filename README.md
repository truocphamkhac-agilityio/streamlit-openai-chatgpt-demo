# Streamlit OpenAI ChatGPT Demo

This is a demo to build a chatbot in Python using Streamlit for the frontend and the GPT 3.5 LLM model from OpenAI for the backend.

## Prerequisites

- Python 3.10+
- [Streamlit](https://streamlit.io)
- [OpenAI API Key](https://platform.openai.com/account/api-keys)

## Installation

- Clone this repo and `cd` into it: `git clone [url] && cd [repo]`
- Create a virtual environment: `make virtualenv`
- Enter the virtual environment: `source .venv/bin/activate`
- Install the dependencies: `make install-requirements`

## Run the app

- The app needs secrets to be configured, you'll need to create a `.streamlit/secrets.toml` file with the following content:

```toml
OPENAI_API_KEY = "sk-2...X"
```

- Once environment is set up and secrets are configured, the app can be run by:

```sh
streamlit run src/chatbot_app.py
```

## Testing

```sh
$ pytest -v
```
