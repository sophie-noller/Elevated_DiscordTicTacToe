# Elevated_DiscordTicTacToe
for cis 3962, discord bot for tic tac toe but elevated and tournament hosting

To start, required download discord.py

You will also need a Discord server and account

This project is a Discord bot that allows users to play Tic-Tac-Toe directly within a Discord server.

## Proof of Concept

The Proof of Concept demonstrates that a Python application can communicate with Discord using the Discord API and the `discord.py` library.

The current prototype:

* Connects a Python application to Discord
* Registers a `/tictactoe` slash command
* Responds to the command
* Displays a 3×3 Tic-Tac-Toe board
* Identifies the Discord user who started the game

The Proof of Concept will be expanded during development to support player turns, moves, win detection, draw detection, and multiple games.

## Technologies

* Python 3
* discord.py
* Discord API
* Git/GitHub
* Visual Studio Code

## Requirements

* Python 3
* pip
* A Discord account
* A Discord server for testing
* A Discord bot created through the Discord Developer Portal

## Installation

Clone the repository:

```bash
git clone YOUR-GITHUB-REPOSITORY-URL
```

Navigate into the project:

```bash
cd discord-tictactoe
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment.

On Mac/Linux:

```bash
source .venv/bin/activate
```

On Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Install the required dependency:

```bash
python -m pip install -r requirements.txt
```

## Running the Bot

The bot requires a Discord bot token stored in the `DISCORD_TOKEN` environment variable.

On Mac/Linux:

```bash
export DISCORD_TOKEN="YOUR_BOT_TOKEN"
python bot.py
```

On Windows PowerShell:

```powershell
$env:DISCORD_TOKEN="YOUR_BOT_TOKEN"
python bot.py
```

After the bot connects to Discord, use the following command in the test Discord server:

```text
/tictactoe
```

The bot will respond with a Tic-Tac-Toe board.

## Operating System

The Proof of Concept can be developed and tested on Windows 11 or macOS.

## Python Version

Python 3

## Dependencies

The project uses `discord.py` to communicate with Discord and interact with Discord slash commands.


