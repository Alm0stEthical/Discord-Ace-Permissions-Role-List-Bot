## Introduction
This Discord bot helps with managing roles on Discord Ace Permissions. It's like a helper for organizing roles in a server.

## How It Works
The bot sorts roles in either ascending or descending order and makes a file with the sorted roles. It's made to work well with Discord Ace Permissions, so it makes managing roles easier.

## Features
- Sorts roles automatically
- You can choose if roles go up or down
- Makes a file with sorted roles
- A LOT OF [Configuration](config.json)

## Getting Started
To use the bot, follow these steps:
1. Get the bot's code on your computer.
2. Install the things it needs by typing `npm install`.
3. Make a Discord bot and get its ID and token.
4. Put your bot's ID, token, server ID, and what you want the bot to listen for in `config.json`.
5. Change other settings in `config.json` if you want.
6. Invite the bot to your Discord server using a link from Discord's website.
7. Make the bot work by typing `node index.js` in your computer's command line.

## Commands
The bot has one command:
- `/command_name_no_spaces_or_special_characters`: This gets and sorts roles, then saves them to a file. **MAKE SURE TO CHANGE THE COMMAND NAME IN THE [configuration](config.json)!

## Contributing
You can help make the bot better! If you find problems or have ideas, you can tell us by opening an issue or sending changes with a pull request.

## Credits
This bot was made because of the [DiscordAcePerms](https://github.com/JaredScar/DiscordAcePerms) project by [JaredScar](https://github.com/JaredScar/).

## License
This project is under the [MIT License](LICENSE).
