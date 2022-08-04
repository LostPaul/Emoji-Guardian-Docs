---
description: >-
  Here can you find solutions for a few problems that may arise while using our
  Bot.
---

# Troubleshooting

### I can only see a dropdown menu and buttons when I use the help command and other messages are empty too

Solution:\
Go to your settings then go to Text & Images and enable "Show website preview info from links pasted into chat" under Link preview.

![](<.gitbook/assets/Discord\_fZ0NjJTuXJ (1).png>)

![Example](.gitbook/assets/Discord\_8tOfgBB8MA.png)

### The emojis in the messages from Emoji Guardian doesn't work

* Slash commands are like Webhooks and that Webhooks can use external emojis it requires that the everyone role has external emojis permissions

The easy solution for this is just to turn on external emojis permissions for the everyone role either in the role settings or just for one channel.

![In the role settings from your server](.gitbook/assets/Discord\_ja780sjDVH.png)

![In the channel settings](.gitbook/assets/Discord\_glTiSM8Wk5.png)

If want the bot to use external emojis don't do this

![Channel settings](.gitbook/assets/Discord\_UAavmQZJas.png)

## Slash commands doesn't work

Before reading this make sure that you invited the bot with the scope "aplications.commands" you can check if you see slash commands from others when you type "/".\
If you can see the logo from Emoji Guardian you used the right invite.\
If you didn't you can use the invite [https://discord.com/oauth2/authorize?client\_id=887939311373267005\&permissions=1610612864\&scope=bot%20applications.commands](https://discord.com/oauth2/authorize?client\_id=887939311373267005\&permissions=1610612864\&scope=bot%20applications.commands) you don't need to kick the bot you just need to authorise the bot again with the invite above.

### Slash commands doesn't show up when I type /

#### First possible option: You disabled slash commands in your settings

How to enable it in your user settings.

Open your user settings

![](.gitbook/assets/Discord\_aJCa20HdjD.png)

Then go to Text & Images

![](.gitbook/assets/Discord\_UZzZ8A1mOo.png)

Click on "Use slash commands and preview emojis, mentions and markdown syntax as you type" to enable slash commands

![](.gitbook/assets/Discord\_gYztwavnaY.png)

#### Second possible option: It might be a bug or something else

If you are on mobile the first thing you should do is to update your app if a update is available.

If it is still not working or there is no update available try restarting and see if it works then.

If you are using discord on pc read the first option if that doesn't work wait a bit until the slash commands show up or it might be a bug.

### The bot doesn't upload emojis to my server

Make sure that Emoji Guardian has manage emojis permissions before you continue reading

#### Emoji upload limit

Discord currently has a ratelimit of _**50 emoji uploads per hour**_ in each server. Once you go over the limit, Emoji Guardian will get stuck for an hour before being able to finish uploading your emotes. Make sure not to go over this limit, or you'll run into this issue!

## Emojis don't work in the Emoji List

![](.gitbook/assets/Discord\_V82vnUyABC.png)

#### If you have this issue it's because Emoji Guardian doesn't have the roles that are required to use the emojis

#### To resolve this, you have to give Emoji Guardian the roles in order for the emojis to work

#### If you don't want to do that you can set the exclude locked emojis option to true

![](.gitbook/assets/Discord\_lnaQoPsyR9.png)

### That's how the solution looks like

![](<.gitbook/assets/Frame 5.png>)
