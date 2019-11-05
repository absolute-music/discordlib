# client

{% hint style="info" %}
Whenever you use client in the client function, you need to put dl. in front
{% endhint %}

Using the client option of discord.lib will allow you to get the client of the bot login from our library. You can also use this to interact with the library [discord.js](https://npmjs.com/package/discord.js).

## Get client

```text
const dl = require("discord.lib")
dl.client.on("message", message => {
    message.channel.send("I love discord.lib")
})
)
```

{% hint style="info" %}
You could use everything in the events section of [this page](https://discord.js.org/#/docs/main/stable/class/Client)
{% endhint %}

### Example of using discord.lib client

```text
const dl = require("discord.lib")
dl.client.on("ready", () => {
 dl.client.user.setActivity(`I am serving ${client.guilds.size} server`)
})
```

