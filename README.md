

# AD Tool - Discord Self Bot

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.8%2B-blue.svg)

## Description

AD Tool is a powerful self-bot for Discord designed to streamline and automate various tasks within your Discord server. With AD Tool, you can effortlessly send automated messages, manage server members, and much more, all while enhancing your overall Discord experience.

## Features

- **Automated Message Sending**: Schedule and send messages to specific channels automatically.
- **User-Friendly Interface**: Intuitive design for seamless usage.

## Requirements

Before running AD Tool, ensure you have the following:

- Python 3.8 or higher
- The `discord.py` library installed

## Installation

### Method 1: Clone the Repository

1. **Clone this repository**:
   ```bash
   git clone https://github.com/davenwoody/ad-tool.git
   cd ad-tool
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Your Token**:
   - Open the `config.py` file and insert your Discord token.

### Method 2: Using Docker

If you prefer using Docker, you can set up AD Tool in a containerized environment:

1. **Build the Docker image**:
   ```bash
   docker build -t ad-tool .
   ```

2. **Run the Docker container**:
   ```bash
   docker run -d --name ad-tool-container ad-tool
   ```

3. **Configure Your Token**:
   - Ensure to pass your Discord token as an environment variable or modify the `config.py` file within the container.

### Method 3: Using Virtual Environment

For a cleaner setup, consider using a virtual environment:

1. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```

2. **Activate the virtual environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Your Token**:
   - Open the `config.py` file and insert your Discord token.

## Usage

To run AD Tool, execute the following command:

```bash
python main.py
```

Once the bot is running, you can utilize the predefined commands to manage your server effectively.

## Warning

Please be aware that using self-bots on Discord violates the [Discord Terms of Service](https://discord.com/terms) and may result in your account being banned. Use at your own risk.

## Contributing

We welcome contributions from everyone! If you would like to contribute, please follow these steps:

1. Fork this repository.
2. Create a new branch (`git checkout -b feature-xyz`).
3. Make your changes and commit (`git commit -m 'Add some feature'`).
4. Push to your branch (`git push origin feature-xyz`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.

## Contact

If you have any questions or suggestions, feel free to reach out to me on [Instagram](https://instagram.com/davenjebeh) or via [Email](mailto:davenwoodys@gmail.com).

---

Thank you for using AD Tool! We hope it enhances your Discord experience!
