
# Telegram Meme Bot

A Telegram bot that responds to commands and messages. It can send random memes upon request and handle basic commands like `/start` and `/help`.

## Features

- **/start**: Greets the user with a welcome message.
- **/help**: Provides help information.
- **/meme**: Fetches and sends a random meme from an online API.
- **Text Response**: Replies to text messages containing keywords like "hello" and "meme".

## Prerequisites

Before running the bot, ensure you have the following installed:

- Python 3.7 or higher
- `aiohttp` library
- `python-telegram-bot` library

You can install the required libraries using pip:

```bash
pip install aiohttp python-telegram-bot
```

## Setup

1. **Clone the Repository**

   Clone this repository to your local machine:

   ```bash
   git clone "https://github.com/001AM/MemeBot.git"
   ```

2. **Configure Your Bot**

   Replace the placeholder token in the script with your own Telegram Bot API token. You can obtain a token by creating a new bot via [BotFather](https://core.telegram.org/bots#botfather).

   ```python
   TOKEN: Final = 'YOUR_TELEGRAM_BOT_API_TOKEN'
   ```

3. **Run the Bot**

   Execute the Python script to start the bot:

   ```bash
   python bot.py
   ```

## Code Explanation

- **Imports**: The script uses `aiohttp` for asynchronous HTTP requests and `python-telegram-bot` for interacting with the Telegram Bot API.
- **Commands**:
  - `/start`: Sends a greeting message.
  - `/help`: Sends help information.
  - `/meme`: Fetches and sends a random meme from an external API.
- **Message Handling**: Processes text messages and responds based on keywords. If the message contains "hello", it replies with a friendly greeting. If it contains "meme", it fetches and sends a meme.
- **Error Handling**: Logs errors encountered during bot operation.

## Acknowledgements

- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) for the Telegram bot framework.
- [aiohttp](https://docs.aiohttp.org/en/stable/) for asynchronous HTTP requests.
- [Meme API](https://meme-api.com) for meme fetching.

## Contact

For any questions or feedback, please reach out to [Soham Panchal](mailto:sohampanchal1469@gmail.com).

