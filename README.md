# PUBG Penguin Roster Chatbot

## Complete Setup Guide

1. **Clone the repository**
   ```bash
   git clone https://github.com/MaxicoTelegram/pubg-penguin-roster-chatbot.git
   cd pubg-penguin-roster-chatbot
   ```

2. **Install Dependencies**
   Make sure you have Python 3.x installed. Then install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**
   Create a `.env` file and set the necessary environment variables (e.g., API keys, database URLs).

4. **Run the Bot**
   Start the bot with the following command:
   ```bash
   python main.py
   ```

## Features
- Automated player roster management for PUBG.
- Integration with PUBG API for real-time data.
- Supports multiple game modes.
- Custom commands for users to interact with the bot.
- Error handling and logging for better debugging.

## API Endpoints
### 1. Get Player Stats
   - **Endpoint:** `/api/player/stats`
   - **Method:** `GET`
   - **Description:** Retrieves the stats of a specified player.
   - **Parameters:**
     - `username`: The username of the player.
     - `platform`: The gaming platform (e.g., PC, Xbox, PlayStation).

### 2. Update Roster
   - **Endpoint:** `/api/roster/update`
   - **Method:** `POST`
   - **Description:** Updates the player roster.
   - **Payload:**
     - `player_ids`: List of player IDs to update.

### 3. Get Game Modes
   - **Endpoint:** `/api/game/modes`
   - **Method:** `GET`
   - **Description:** List all available game modes in PUBG.

## Quick Start Instructions
1. Clone the repository.
2. Install required dependencies using pip.
3. Configure your environment variables in `.env` file.
4. Start the bot using `python main.py`. 

For more detailed information and troubleshooting, please refer to the documentation within the repository.
