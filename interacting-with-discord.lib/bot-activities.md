# bot activities

You could use the dl.login way to set regular games, but you cannot do server count there. The client way is the only way to do that. And this tutorial is to show you how.

{% hint style="info" %}
You need to make sure that only the token is in dl.login function.
{% endhint %}

First, we need to interact with discord.lib client by doing:

```text
const dl = require("discord.lib")
dl.client.on("ready", () => {
 dl.client.user.setActivity(`I am serving ${client.users.size}`)
})
```



