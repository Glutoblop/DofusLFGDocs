# Dofus LFG Discord Bot  ﻿<img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/main/res/Icon/Icon.png" width=50 height=50/>
Join the Home Of English Dofus and uses the LFG bot and many others to help your play time in Dofus:   
  
https://www.discord.gg/englishdofus

[<img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/refs/heads/main/res/Icon/add_to_discord.png" width=550>](https://discord.com/oauth2/authorize?client_id=1112419871557431297)

 # Discord Admin Setup
The new version of the LFG bot is stream lined to remove as many permissions for the bot as possible!  
I want everyone who wants to LFG with their community to do so without any concerns for what a bot is receiving in their Discords.  
  
  These are the base permissions the bot has, all it can do is create and delete public threads.
 <img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/refs/heads/main/res/permissions.png" width=600>

### Manage threads is an optional permission, without it the bot will not clean up the threads, but it will function fine. 

In order to mitigate anymore concerns, after adding the bot you should restrict its access to only the channels you want it to see.

This means going into the Integrations settings of your server and telling the bot it can only see the channels you want it to see. 

Inside The International Pub we have done this by restricting it to only see the LFG channels for each supported Dofus server:

 <img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/refs/heads/main/res/intergration.png" width=600>
 
I highly recommend this  because it not only allows the bot to run faster for you, but it also means you have full control knowing that these channels are bot controlled and the bot is definitely not allowed to see manage threads anywhere else. 

# Setup Bot For Use

The loop of the bot is pretty simple, its intended purpose is to:
```
Create public threads inside channels its been assigned when people 
mention the roles been told to look out for.

If it has the ManageThreads permission it will then delete these threads, 
after asking if the Thread is still required and getting no response. 
```
This should go something like this: 
* Monitor channels that you tell it to using the `/add_lfg_channel` command
    * This command should be used inside the text channel you want to mark for use as LFG only
    * For best results also enable slow mode inside this channel between 1 - 5 minutes
    * You can mark as many channels as you want for LFG
* Add LFG roles that people can use to notify other members of their need for help
   * Ensure you enable "mention this role" in the LFG role permissions.
* Use the `/add_lfg_role` command to assign an existing server role as an LFG role
    * This command can be done anywhere, it marks the roles as LFG roles globally on the Discord
* Discord members can now @mention the role they want request help from inside the #lfg-channel you assigned and the bot will automatically create a thread on this LFG message.
    * Slow mode is not active inside the Public Thread, so the LFG channel will become a list of Threads with descriptions of the help required, and inside the threads will be a discussion between players organising when, where and how to help each other. 
    * Threads automatically archive themselves when not used for a while, or the bot will automatically delete them after a few hours of inactivity if no one responds to the bot when it asks if it can be deleted. 

# GOOD LUCK AND LFG
I hope everyone enjoys being able to organise their Dofus communities abit easier!
If you have any feature requests or feedback then please come visit me in the DofusLFG Discord and leave the feedback there:
https://discord.com/invite/9pRdKN3tug


--------------------------------------
[<img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/main/res/Icon/twitter_icon.png" width=50>](https://twitter.com/Glutoblop) [<img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/main/res/Icon/buy_coffee.png" width=50>](https://www.buymeacoffee.com/glutoblop) [<img src="https://raw.githubusercontent.com/Glutoblop/DofusLFGDocs/main/res/Icon/join_discord.png" width=150>](https://www.discord.gg/englishdofus)

