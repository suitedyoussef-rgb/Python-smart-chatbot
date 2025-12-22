🧠 Chatbot Portal (Python Console Application)
📌 Overview

Chatbot Portal is a modular, menu-driven Python console application that combines multiple interactive features into a single chatbot-style system. It is designed to demonstrate real-world Python programming concepts such as modular architecture, file-based authentication, API integration, environment variables, and interactive CLI workflows.

This project is intended for learning, experimentation, and personal use, not for production deployment.

✨ Features
🔐 Authentication System

User signup and login functionality

Credentials stored locally using text files

Session-based access during runtime

🤖 AI Chatbot (Gemini API)

Conversational AI powered by Google Gemini

Accepts free-form user prompts

Requires a Gemini API key set as an environment variable

🖼️ AI Image Generator

Generates AI-based images using text prompts

Uses the Pollinations AI image generation API

Returns a direct image URL in the terminal

🌦️ Weather Information

Fetches real-time weather data from an external API

Displays temperature and weather conditions

📚 Education Mode

Interactive educational content and utilities

Designed for practice and learning

🎮 Entertainment Mode

Text-based entertainment features

Interactive console-based options

🕌 Islamic Mode

Islamic-focused content and tools

Accessible directly from the main menu

➗ Mathematics Module

Supports mathematical calculations

Uses safe evaluation libraries

📝 Notes System

Allows users to save and read notes

Notes are stored locally in a text file

🛠️ Technologies Used

Python 3.8 or higher

google-generativeai (Gemini AI integration)

requests (API communication)

numexpr (safe mathematical evaluation)

Environment variables for API keys

File handling using .txt files

📂 Project Structure
Chatbot/
│
├── src/
│   ├── main.py              # Application entry point
│   ├── main_menu.py         # Main navigation system
│   ├── auth.py              # Authentication logic
│   ├── ai.py                # AI chatbot & image generator
│   ├── weather.py           # Weather API integration
│   ├── education.py         # Education module
│   ├── entertainment.py     # Entertainment module
│   ├── islamic_mode.py      # Islamic features
│   ├── mathematics.py       # Math utilities
│   ├── general.py           # General chatbot logic
│   └── __init__.py
│
├── data/
│   ├── user.txt             # Stored user credentials
│   └── notes.txt            # User notes
│
├── requirements.txt         # Project dependencies
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/chatbot-portal.git
cd chatbot-portal

2️⃣ (Optional but Recommended) Create a Virtual Environment
python -m venv venv
source venv/bin/activate
# On Windows: venv\Scripts\activate

3️⃣ Install Required Dependencies
pip install -r requirements.txt

🔑 Environment Variables
Gemini AI API Key (Required)

To enable the AI chatbot, you must set your Gemini API key as an environment variable.

Windows (PowerShell)
setx GEMINI_API_KEY "your_api_key_here"

macOS / Linux
export GEMINI_API_KEY="your_api_key_here"


⚠️ Without this key, the AI chatbot feature will not function.

▶️ Running the Application

From the project root directory, run:

python src/main.py


You will be presented with:

Login / Signup menu

Main feature selection menu

Interactive command-line prompts

🧪 Usage Notes

The application runs entirely in the terminal

All data is stored locally using text files

Internet connection is required for:

AI chatbot

Image generation

Weather data

Restarting the program logs out the user

🔒 Security Disclaimer

Passwords are stored in plain text

No encryption or hashing is implemented

Do NOT use real or sensitive passwords

This project is not secure for production use

🚧 Limitations

No database (file-based storage only)

No password encryption

No persistent login sessions

CLI-only interface (no GUI)

Basic error handling

🧩 Extending the Project

You can enhance this project by:

Adding new modules in the src/ directory

Implementing password hashing

Integrating a database

Adding a graphical or web-based interface

Improving error handling and validation

Adding logging and analytics

🤝 Contributing

Contributions are welcome.

Fork the repository

Create a feature branch

Commit your changes

Open a Pull Request

Please ensure code clarity and proper testing before submission.

📜 License

This project is provided for educational purposes only.
You are free to modify, learn from, and extend it.

⭐ Acknowledgments

Google Gemini API

Pollinations AI

Python open-source community

If you want, I can also:

Optimize this for GitHub portfolio presentation

Add badges

Write a resume-ready project description

Create documentation screenshots

Convert it into a professional open-source README

Just say the word 👍

DEVELOPER MODE
