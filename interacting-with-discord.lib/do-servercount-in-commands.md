# Do servercount in commands

You can do servercount in commands by doing something like this:

```text
const dl = require("discord.lib")
dl.client.on("message", msg => {
 if(msg.content === "servercount"){
  msg.channel.send(client.guilds.size)
 }
})
```

