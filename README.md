# WeBook Tickets Bot

A specialized automated ticket booking bot for the WeBook website that enables users to secure tickets efficiently without manual intervention.

## Features

- Automated ticket holding and booking
- Credential-free access system
- Custom seat selection
- Event-based booking
- High-speed execution
- Desktop application and web UI options
- Comprehensive documentation

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/webook-bot.git
cd webook-bot
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

### Desktop Application
```bash
python src/main.py
```

### Web UI
```bash
python src/web_app.py
```

## Configuration

Create a `.env` file in the root directory with the following variables:
```
WEBHOOK_URL=your_webhook_url
MAX_RETRIES=3
TIMEOUT=30
```

## Project Structure

```
webook-bot/
├── src/
│   ├── bot/
│   │   ├── __init__.py
│   │   ├── core.py
│   │   ├── seat_selector.py
│   │   └── event_handler.py
│   ├── web/
│   │   ├── __init__.py
│   │   ├── app.py
│   │   └── templates/
│   ├── main.py
│   └── web_app.py
├── tests/
│   └── test_bot.py
├── requirements.txt
├── README.md
└── .env
```

## Documentation

Detailed documentation is available in the `docs/` directory.

## Support

For support, please open an issue in the GitHub repository or contact the development team.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 