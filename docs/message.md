# message

{% hint style="info" %}
If you are making a help command, We suggest to not use the same command prefix as music command because if you set the same prefix for musix, the music help command will come out. 
{% endhint %}

### Commands

| Parameter | Description | Required |
| :--- | :--- | :--- |
| command | Set the command\(includes prefix\) | yes |
| message | what will the bot reply to you | yes |

## Examples

example of doing it properly

```javascript
const dl = require("discord.lib");
dl.sendMessage("help", "reply")
dl.login("Token", "game")
```

example of doing it wrong

```javascript
const dl = require("discord.lib");
dl.sendMessage("A_help", "reply")
dl.musicClient("A_")
dl.login("Token", "game")
```

