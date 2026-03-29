# Chatbot using Gemini Pro

A conversational AI chatbot built with **Google Gemini Pro** and **Streamlit**. The app provides a clean, interactive chat interface where users can have multi-turn conversations powered by Google's Generative AI model.

## Features

- Multi-turn conversation with full chat history maintained per session
- Powered by Google's `gemini-pro` generative model
- Clean, wide-layout Streamlit UI with chat bubbles
- API key managed securely via environment variables

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Google Gemini Pro | Generative AI model |
| Streamlit | Web UI framework |
| python-dotenv | Environment variable management |

## Project Structure

```
chatbot-using-gemini-pro/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── .env                # API key config (not committed)
```

## Getting Started

### Prerequisites

- Python 3.8+
- A Google Gemini API key (available at [Google AI Studio](https://aistudio.google.com/))

### Installation

```bash
git clone https://github.com/smunir25/chatbot-chatbot-using-gemini-pro.git
cd chatbot-chatbot-using-gemini-pro
pip install -r requirements.txt
```

### Configuration

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_google_api_key_here
```

### Run

```bash
streamlit run app.py
```

Visit `http://localhost:8501` in your browser.

## Usage

1. Type your message in the input box at the bottom of the page
2. Press **Enter** to send
3. The assistant responds using Gemini Pro, with full conversation context preserved across turns

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
