
# Y Assistant

A privacy-focussed local AI chatbot powered by TinyLlama

Y is a lightweight web-based AI assistant designed to run entirely on your local machine. It features a custom architecture demo, a secure login system, and per-session memory, ensuring that your conversations stay private and contextual. Created by S (My pseudonymn).


## Features

- No data leaves your machine. It runs on TinyLlama 1.1B.
- Contextual Memory: Remembers the last 10 messages for a natural conversation flow.
- Secure Access: Protected by a customizable password system.
- Privacy-First: No permanent logs are stored; session data is cleared on request.
- Architecture Demo: Includes a raw GPT-2 initialization script to show how LLMs are structured.


## Installation

Install my-project with npm

```bash
  # Clone the repository
git clone https://github.com/sounak1410/Web-Based-Edge-AI-.git

# Enter the directory
cd Web-Based-Edge-AI-

# Install dependencies
pip install -r requirements.txt

# Run the application
python Edge.py
```
    
## Chatting with Y

1. Open your browser to http://127.0.0.1:5000.

2. Enter the default password: 676767.

3. Chat with Y!

4. Use the Forget 🧠 button to wipe the current session's memory.


## Tech Stack

1. Framework: Flask (Python)

2. Model: TinyLlama-1.1B-Chat-v1.0

3. Libraries: Transformers, Torch, Accelerate
