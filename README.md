# python-rocketchat-bot
rocket.chat python basic bot using dpp

# dependancies
`emerge -va python-meteor`
or
`pip install python-meteor`

# usage
```
def hello(bot, message):
    bot.sendMessage(message['rid'], "React from hello command")

rocket = RocketChatBot('username', 'password')
rocket.addPrefixHandler('hello', hello)
rocket.start()
```
