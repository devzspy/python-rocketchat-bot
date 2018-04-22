# Rocket.Chat Python Realtime API SDK

![PythonBot Example](https://media.giphy.com/media/9r8xllMmDzBTExmzbg/giphy.gif)

This is a Python Connector SDK for the RocketChat Realtime API. It uses a DDP connector to create a websocket with a Rocket.Chat server, giving the ability to hear everything that the server sends to a normal user, without the need to create webhooks or use the REST API.

# Connector

The connector..

## Dependences

requirements.txt

## Methods

[WIP]

# Examples

Building your first Python Bot for Rocket.Chat


```
def hello(bot, message):
    bot.sendMessage(message['rid'], "React from hello command")

rocket = RocketChatBot('username', 'password')
rocket.addPrefixHandler('hello', hello)
rocket.start()
```
