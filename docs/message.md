# message

{% hint style="info" %}
If you are making a help command, We suggest to not use command including "help" because if you set the same prefix for musix, the music help command will come out. 
{% endhint %}

### Commands

| Parameter | Description | Required |
| :--- | :--- | :--- |
| command | Set the command\(includes prefix\) | yes |
| message | what will the bot reply to you | yes |

```text
const dl = require("discord.lib");
dl.sendMessage("command", "reply")
dl.login("Token", "game")
```

