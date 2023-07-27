# Web Servers - Site Down Notifier

<div align="center">
  <img src="https://cdn.discordapp.com/app-icons/1121550072782540800/727818f8f63e57b71e8fe5af8670444e.png?size=256" alt="Maybe Ange Corporation">
</div>

## Description
This bot is a Discord bot designed to monitor the status of servers on a specific site and report outages within a Discord channel. When the target site is inaccessible, the bot sends an embed with information about the outage, helping users stay informed in real time.

## License and source code price
The price of the source code as well as obtaining the license and <span>**15€**</span> (Negotiable).
After purchase, the source code is sent to you with support.
Remember that the source code is protected by copyright and any use by unauthorized third parties will be prosecuted by the police, we use tools capable of finding our source codes.

## Source code price
Licence, Source code & Support <span>**15€**</span> (Negotiable)

## Features
- Real-time monitoring of target site status.
- Sending informative Discord embeds when a server is down.
- Notification channel and check frequency customization settings (Default 10000 milliseconds)
  
## How to use the bot

1. Create a new bot from the panel: ![https://discord.com/developers/applications](https://discord.com/developers/applications)
2. Invite the bot to your Discord server using the resulting invite link.
3. Configure the notification channel in which the bot will send outage messages.
4. Specify the site you want to monitor by modifying the line `const websiteUrl = 'value';`.
5. Set the check frequency using the line `setInterval(checkWebsiteAndNotify, value in Milliseconds);`.
6. Define the roles to mention on the line `const roleIdsToMention = 'value,value,...';`
7. Custom embed text `const embed = new Discord.EmbedBuilder()`
8. Relax and let the bot do the work! It will notify you as soon as a problem is detected.

## Example of Failure Notification Embed
![Example of Failure Notification Embed](https://github.com/MaybeAnge/Images/blob/main/Web%20Servers.png)

## Noticed
This bot is provided as is, without any warranty. The use of this bot is subject to your own responsibility. We are not responsible for any damage caused by the use of this bot.

## Licence CC-BY-ND-4.0
Copyright Maybe Ange™ Corporation © 2023. All rights reserved.

All content in this bot, including but not limited to text, images, graphics, audio and video files, logos and trademarks are protected by applicable copyright and trademark laws. trade. Unless otherwise stated, the source code is the exclusive property of Maybe Ange™ Corporation.

You may not reproduce, distribute, modify, publicly display, transmit, publish or use the source code for commercial or non-commercial purposes without the prior written permission of Maybe Ange™ Corporation. Any unauthorized use of the contents of this source code constitutes copyright and trademark infringement and may result in legal action.

By using this source code, you agree to respect the copyrights and trademarks of Maybe Ange™ Corporation. If you have any questions or concerns regarding the copyrights or trademarks of Maybe Ange™ Corporation, please contact our teams at the following email address: contact.support@maybe-ange.com

## Author
- Maybe Ange - Director of Maybe Ange™ Corporation
- [Discord Server](https://discord.gg/maybe-ange)
