---

# Daily Giphy Views Tracker Telegram Bot

The Daily Giphy Views Tracker Telegram Bot is designed to track the total views of a specific Giphy project and send daily updates to users on Telegram. This README provides an overview of the project, how to set it up, and how to use it.

## Features

- Bot Creation over Telegram.
- Takes Project as Input from Bot.
- Automates Giphy to fetch the total number of views per day specific to any project.
- Sends Daily Updates of Project Views on Bot.

## Technologies Used

- Node.js
- Telegram Bot API
- Giphy API
- Axios (HTTP client)
- dotenv (Environment variables)

## Setup

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/yourusername/daily-giphy-views-tracker-bot.git
   ```

2. Navigate to the project directory:

   ```
   cd daily-giphy-views-tracker-bot
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your environment variables:

   ```
   TELEGRAM_BOT_TOKEN=your_telegram_bot_token_here
   GIPHY_API_KEY=your_giphy_api_key_here
   ```

5. Start the bot:

   ```
   npm start
   ```

## Usage

1. Start a conversation with your Telegram bot.
2. Send the `/start` command to begin.
3. Use the `/track <project_name> <image|gif>` command to track views for a specific Giphy project. Replace `<project_name>` with the name of the project and `<image|gif>` with the type of content.
4. Receive daily updates on the total views of the tracked project.

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
