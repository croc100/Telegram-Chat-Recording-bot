Forty by CRODE
crode.kr | croc
Available for personal use under the CRODE license policy.

Description:
This PHP code is an example of creating a Telegram bot that saves the unique IDs of participants and backs up conversations.

Environment:
- PHP version 5.6 or above
- cURL PHP extension must be installed.

Prerequisite:
1. Create a Telegram Bot: First, create a Telegram bot and obtain an API token. Set the API token you received to the `$telegramToken` variable.
2. Create a Backup Folder: The code uses a file as an example for conversation backup. Create a folder to store the backups and set the path to the folder in the `$backupFilePath` variable.

Usage:
1. Interacting with the Telegram Bot: Search for the bot in the Telegram app and start a conversation with it.
2. Conversation Backup: The conversation with the bot will be stored in files within the `backup` folder, with each participant's unique ID as the file identifier. The conversation content will be appended to the respective file.

You can use the provided PHP code to create a Telegram bot and backup conversations. Make sure to modify the necessary configurations based on the comments within the code.
