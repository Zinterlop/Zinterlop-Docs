# FAQ

## How do I invite MCServer Status Bot to my server?

You will need **`Manage Server`** or **`Administrator`** permissions to invite MCServer Status Bot. Use this [Discord Oauth URL](https://discord.com/api/oauth2/authorize?client_id=878374018099597392&permissions=18432&scope=bot) to invite the bot.

## What is the default prefix and how can I change it?

The default prefix is `!`. At the moment, there is no ability to change the default prefix.

## Why is MCServer Status Bot offline?

The bot may be offline due to the machine either being offline/shutdown or the bot had an error and went offline without any command. 
If the bot does go offline, please report this by joining our [Discord](https://discord.gg/jWFB56RqUN)

## Why is MCServer Status Bot not updating my status message?

There is a chance that we might've reset the database for the status messages so it will require you to set it up most likely but it is extremely easy to setup.
Another reason is it can be that the bot is offline and it does not update while it is offline

## Why is the status message saying its offline while my server is online? 

here are the following reasons to why this issue is occurring.

For the following Minecraft Java Softwares Spigot and for Minecraft Bedrock BDS(Minecraft Official Software) these softwares cannot be queried at the moment
The softwares the bot can query are the following. PocketMine-MP, Nukkit, WaterDog/WaterDogPE and Paper (Minecraft java software)

If you are using the softwares that cannot be queried its normal that this issue is happening, if you are not then please continue reading.

As the bot uses queries you are required to have queries enabled. Having them disabled will mean the bot will return the offline embed message. 
So to fix this issue, you will be required to enable queries on your server.
