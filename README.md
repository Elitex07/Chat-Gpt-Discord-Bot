# Discord-Chat-Bot
This is an example Discord Chat Bot based on Open Ai and Discord.js Library. Enjoy!

## Requirements
- A Discord Bot with its Token.
- Open Ai API Key [Get Key from here](https://platform.openai.com)

## Startup
- Create a file named `.env`.
- Enter the following details to it:
```
token="YOUR TOKEN"
OPENAI_API_KEY="API KEY"
```
- Save the file. Open Terminal in the Project Directory.
- Head to `Line 60: index.js`.
- Enter the Channel ID
- Run:
```
npm i
node index.js
```
- You are done.

## Configuration
To get Custom Response, just head to `prompt` variable, and change things accordingly. Do not add so many information, otherwise you will exhaust your free credits quickly.

![image](https://user-images.githubusercontent.com/92834724/224532025-f86a3de2-3d03-4fdc-ba91-d72a98630043.png)

## Troubleshooting
- Error: Status Code 500 : This means there is an server error from OpenAi
- Error: Status Code 429 : You have been ratelimited from OpenAi

## Support
Join our Discord Servers, to get support:

[<img src="https://discordapp.com/api/guilds/890225986375929866/widget.png?style=banner2" alt="Discord Banner 1"/>](https://discord.gg/UN7YBb23tu)
