# Price Analysis Telegram Bot

This Telegram bot helps in managing group chats, providing cryptocurrency prices, and greeting new members.

## Features

1. Chat Management:

- Tracks changes in chat membership.
- Logs when a user starts or blocks the bot in private chats.
- Logs when the bot is added to or removed from groups or channels.

2. Greeting New Members:

- Welcomes new members in group chats.
- Sets a time limit for new members to introduce themselves; otherwise, they get banned.

3. Cryptocurrency Price Checking:

- Provides real-time cryptocurrency prices fetched from CoinMarketCap.
- Displays detailed information about the requested cryptocurrency, including price changes, volume, opening/closing prices, and more.
- Supports a wide range of cryptocurrency symbols.

4. Error Handling:

- Logs exceptions that occur during bot operation.
- Notifies the developer about errors via Telegram messages, facilitating rapid debugging.

## Getting Started

### Prerequisites

- Python 3.x
- Install required Python packages: `pip install -r requirements.txt`

### Configuration

1. Create a `secrets.json` file with your API keys and Telegram bot token.
2. Create a `credentials.txt` file with your binance credentials

### Usage

Run the script:

```bash
python main.py
```

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request. Make sure to follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or inquiries, please contact [meghamgarg@gmail.com](mailto:meghamgarg@gmail.com).
