# How to use

## Get Link

Get your web hook link from Discord
should look something like this
```
https://canary.discordapp.com/api/webhooks/<HOOKID>/<TOKEN>
```

## Setup

This has to be done.
```
var discord = require('discord-bot-webhook');
discord.hookId = 'PutHookIdHere';
discord.hookToken = 'PutTokenHere';
```

This can be done if you want
```
discord.userName = 'SpiderBot';
discord.avatarUrl = 'SomeUrl';
```

## Use

To send a message after you set

```
discord.sendMessage('SomeText');
```
