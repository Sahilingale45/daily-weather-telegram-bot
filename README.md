# daily-weather-telegram-bot
A scheduled Make.com automation blueprint that fetches daily weather forecasts and automatically broadcasts them to a Telegram chat or channel via a custom bot.
# Scheduled Daily Weather Telegram Broadcast

This repository contains a Make.com (formerly Integromat) scenario blueprint that automates fetching weather updates and broadcasting them straight to a Telegram chat, channel, or group.

## 🚀 How It Works
1. **Trigger (Weather - Get daily weather forecast):** Runs automatically on a customized daily schedule (e.g., every morning at 7:00 AM) to query localized forecasting information.
2. **Action (Telegram Bot - Send a Text Message or a Reply):** Extracts the forecasting details (such as high/low temperatures, description, and humidity levels) and structures them into a clean notification pushed directly to Telegram.

## 📦 What's Included
* `/blueprints/daily-weather-telegram-bot.json`: The complete exported Make.com scenario blueprint configuration file.

## 🔧 Setup Instructions
1. Open your **Make.com** dashboard.
2. Create a new scenario, click the three dots (`...`) located on the bottom navigation control bar, and choose **Import Blueprint**.
3. Upload the `.json` blueprint file from this repository.
4. Establish your configuration parameters:
   * **Weather Module:** Configure the specific city, coordinates, or location you want to monitor, and set your desired daily triggering time on the clock icon.
   * **Telegram Bot Module:** Generate an API Token from Telegram's official `@BotFather`. Create a new connection in Make using your token, and provide your target `Chat ID` (or channel username).
5. Map the weather parameters (e.g., `Temperature`, `Condition Description`) dynamically into your Telegram text message field.
6. Save the configuration and flip the main scheduling toggle switch to **ON**.
