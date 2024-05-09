## Introduction
This Discord bot helps manage roles on Discord with Ace Permissions. Instead of manually setting up a list of roles ([roleList](https://github.com/JaredScar/DiscordAcePerms/blob/85e61d1a4a3a270bd50fc012ce4a2581ff5b926f/config.lua#L9)), this bot does it for you.

## How It Works
The bot arranges roles either from lowest to highest or highest to lowest and then saves them in a file. It's designed to make handling roles easier, especially with Discord Ace Permissions.

## Features
- Automatically sorts roles
- Choose whether roles go up or down
- Saves sorted roles in a file
- Lots of configuration options

## Getting Started
To use the bot, follow these steps:
1. Download the bot's code to your computer.
2. Install necessary packages by typing `npm install`.
3. Create a Discord bot and get its ID and token.
4. Put your bot's ID, token, server ID, and what you want the bot to listen for in `config.json`.
5. Customize other settings in `config.json` if needed.
6. Invite the bot to your Discord server using a link from Discord's website.
7. Activate the bot by typing `node index.js` in your computer's command line.

## Commands
The bot has one command:
- `/command_name_no_spaces_or_special_characters`: This command fetches and sorts roles, then saves them to a file. **MAKE SURE TO CHANGE THE COMMAND NAME IN THE [configuration](config.json)!

## Contributing
You can help improve the bot! If you encounter issues or have ideas, you can let us know by opening an issue or sending changes with a pull request.

## Credits
This bot was created inspired by the [DiscordAcePerms](https://github.com/JaredScar/DiscordAcePerms) project by [JaredScar](https://github.com/JaredScar/).

## License
This project is licensed under the [MIT License](LICENSE).
