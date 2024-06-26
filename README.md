# Jynxer-Bot-Gemini-Context

Jynxer is a Python-based Telegram bot that provides text-based responses using gemini 1.5 pro while remembering the context of the last 30 messages. It's designed to enhance conversational interactions in Telegram chats.

## Features

- **Contextual Responses**: The bot maintains context by remembering the previous messages, allowing for more natural and context-aware replies.
- **Text-Based Interaction**: Jynxer Bot responds to user messages with text-based replies.
- **Telegram Integration**: The bot interacts with users via the Telegram API.
- **Memory Management**: The bot keeps track of the last 30 messages to maintain context.

## Setup

Before getting started, a few things needs to be set up as follows

1. Getting the telegram bot API from `@BotFather` in telegram.
   - Write `/start` and select `/newbot`.
   - Now enter the name, in my case it is `Jynxer`, then enter a username for the bot, for me it is `JynxerBOT`.
   - Once you have done everything, botfather will provide you with your telegram bot API key **(store it safely and securely and avoid sharing it with anyone)**.

2. Getting the Gemini API key
   - Go to https://aistudio.google.com/app/apikey and generate your API key.
   - Avoid sharing the API key with anyone.

## Getting Started

1. **Installation**:
   - Clone this repository:-
      ```bash
      git clone https://github.com/ImonChakraborty/jynxer-BOT-gemini-context.git

  
   - Install dependencies:-
      ```bash
      pip install -r requirements.txt

2. **Open `JynxerTEXT.py` on an editor and add your API keys**:
   - The Telegram Bot API key here:-
   
     ![image](https://github.com/ImonChakraborty/jynxer-BOT-gemini-context/assets/135951651/d20a5093-d77b-451c-bb9e-bffe3c81fac2)

   - The Gemini API key here:-

     ![image](https://github.com/ImonChakraborty/jynxer-BOT-gemini-context/assets/135951651/1174a3ad-5895-46ad-8ab8-f02031c978ac)


3. **Run the Bot**:
      ```bash
      python JynxerTEXT.py

## Usage

- Start interacting with the bot, and it will maintain context for up to 30 messages and then start dequeuing process to maintain latest context.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. Just make sure to provide proper explanation and documentation.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
