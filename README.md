# Auto Chat Responder Bot (PyAutoGUI + OpenAI)
A Python automation script that uses PyAutoGUI to interact with your chat UI (like WhatsApp Web), captures the latest messages, and uses OpenAI's GPT model to generate a smart, funny, Hindi-English response in the character.
1. Features:
Automates UI actions like mouse clicks and text selection using pyautogui
Uses pyperclip to read clipboard contents
Uses OpenAI's gpt-3.5-turbo model for generating chat responses
Custom personality-based responses 
Runs in a loop to monitor and reply when specific users send messages

2. How It Works
Opens the chat window using pyautogui.click
Selects and copies the chat using dragTo and ctrl+c
Checks if the last message is from a specific sender (e.g., "Rohan Das")
If yes, sends the chat history to OpenAI and gets a witty response
Pastes the response in the input box and presses enter.

3. Project Structure

.
├── bot.py                  # Main bot script
├── README.md               # Project documentation
├── requirements.txt        # Python package dependencies
└── .env (optional)         # Store secrets like API keys

 4. Credits
OpenAI GPT-3.5 Turbo
PyAutoGUI
pyperclip
