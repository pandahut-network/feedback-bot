# ReminderBot: A lightweight direct message command-based reminder manager for Discord

This bot allows you to set reminders to ping yourself with a direct message at a specified time. Schedule messages easily and manage your reminders by direct messaging the bot with simple commands!

![image](https://user-images.githubusercontent.com/17630457/147714394-d4ae8343-da59-4810-9edd-b1e1dad43b58.png)


[Top.gg link](https://top.gg/bot/843908993491533885)

![visitors](https://visitor-badge.glitch.me/badge?page_id=pblpbl1024.reminder-bot)

## Add this bot
[Click here](https://discord.com/api/oauth2/authorize?client_id=843908993491533885&permissions=0&scope=bot) to invite the bot to your server, no permissions required.

### Run this bot locally
Run the following commands in a terminal:

`git clone https://github.com/pandahut-network/feedback-bot.git`

`cd reminder-bot`

`npm install`

`npm start`

## Tech Stack
* Bot functionality: Discord.js
* Database functionality: MongoDB

## Usage
**All interactions take place via direct messages**. When you invite the bot to a server, everyone on the server can start using this bot if their DM settings allow it. Type `/` to view all commands and info on how to use them.

`/add` Adds a reminder by specifying a time, date, and message.

Arguments:
* `message` The message to notify you with.

* `time: <hour:minute><am|pm>` The time to send the notification.

* `date: <month/day/year>` The date to send the notification. Leave this blank to default to the current day, or leave `year` blank to default to the current year.

`/remove <id>` Removes a specific reminder in the list by ID.

`/clear` Removes all reminders.

`/list` Lists all active reminders.

### Important Note
Before you start using the bot, you must type `/timezone <offset>` where `<offset>` is the number of hours your time zone is offset from Coordinated Universal Time. [Click here](https://www.timeanddate.com/time/map/) to find your time zone. The offset is the number at the bottom of the map on the highlighted strip when you hover over your location. 

## Upcoming Features
* Support for relative time units when creating a reminder
* Support for intervals (repeating reminders)
