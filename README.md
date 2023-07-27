# Web Servers - Site Down Notifier

![Logo du bot](lien_vers_votre_logo.png)

## Description
This bot is a Discord bot designed to monitor the status of servers on a specific site and report outages within a Discord channel. When the target site is inaccessible, the bot sends an embed with information about the outage, helping users stay informed in real time.

## Features
- Real-time monitoring of target site status.
- Sending informative Discord embeds when a server is down.
- Notification channel and check frequency customization settings (Default 10000 milliseconds)
  
## How to use the bot

1. Create a new bot from the panel: https://discord.com/developers/applications
2. Invite the bot to your Discord server using the resulting invite link.
3. Configure the notification channel in which the bot will send outage messages.
4. Specify the site you want to monitor by modifying the line `const websiteUrl = 'value';`.
5. Set the check frequency using the line `setInterval(checkWebsiteAndNotify, value in Milliseconds);`.
6. Define the roles to mention on the line `const roleIdsToMention = 'value,value,...';`
7. Custom embed text `const embed = new Discord.EmbedBuilder()`
8. Relax and let the bot do the work! It will notify you as soon as a problem is detected.

## Example of Failure Notification Embed
![Exemple d'Embed](lien_vers_votre_capture_d_ecran.png)

## Noticed
This bot is provided as is, without any warranty. The use of this bot is subject to your own responsibility. We are not responsible for any damage caused by the use of this bot.

## Author
- Maybe Ange - Director of Maybe Ange Corporation
- [Discord Server](https://discord.gg/maybe-ange)
