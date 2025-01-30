Telegram AI-Powered Bot

Loom Video Presentation: https://www.loom.com/share/b822b28be83c4de1ba2673f3c22ab9e5?sid=26e46a5c-ea50-411c-a541-fde0bc94a9a2

This Telegram bot is a powerful AI-driven assistant built using Google Gemini AI, MongoDB, and Python. It offers a wide range of features, including AI-generated responses, image/file analysis, web search capabilities, user analytics, and more. Designed to enhance user interaction, this bot leverages cutting-edge AI tools to deliver a seamless experience.

Key Features
1. User Registration
2. AI Chat
3. Image/File Analysis
4. Web Search
5. Sentiment Analysis
6. User Analytics & Dashboard

Features a dashboard generated using Matplotlib and Seaborn for visual representation of data.

Requirements
To run this bot, ensure you have the following:

Python 3.8+

MongoDB Atlas (or a local MongoDB instance)

Telegram Bot Token (obtained from BotFather)

Google Gemini API Key

Python dependencies listed in requirements.txt

Installation
Clone the repository:

bash
Copy
git clone https://github.com/your-repo/telegram-ai-bot.git
cd telegram-ai-bot
Install the required Python packages:

bash
Copy
pip install -r requirements.txt
Set up your environment variables:

Create a .env file in the root directory.

Add the following variables:

Copy
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
GEMINI_API_KEY=your_google_gemini_api_key
MONGO_URI=your_mongodb_connection_string
Run the bot:

bash
Copy
python main.py
Usage
Once the bot is running, you can interact with it using the following commands:

Start the bot: /start

Perform a web search: /websearch <query>

View user analytics: /analytics

Access the dashboard: /dashboard

You can also:

Send messages to chat with the AI.

Upload images or files for analysis.

AI Tools Used
ChatGPT: Assisted in generating documentation and refining content.

Gemini AI: Helped understand and implement the bot's core functionalities.

LLaMA 3.2: Enhanced the bot with a new feature for generating dashboards using Matplotlib and Seaborn.

Data and Content
While the core functionality and data remain consistent, this README has been restructured to provide a fresh perspective. The bot's features and capabilities are unchanged, but the presentation has been updated for clarity and uniqueness.

Contributing
Contributions are welcome! If you'd like to improve the bot or add new features, feel free to open an issue or submit a pull request.
