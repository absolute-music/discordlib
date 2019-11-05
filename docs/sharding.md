# sharding

## shardManager

This allows you to shard your discord bot.

### Param

| Name | Description | Required |
| :--- | :--- | :--- |
| file | path to your main file | yes |
| amount | shard amount\(Do not put "" around the amount!\) | yes |

### Example

On a new file, write this file down

```text
const dl = require("discord.lib")
dl.shardManager("./path/to/your/file.js", 2)
```

{% hint style="info" %}
You still put your login function in your main file.
{% endhint %}

## broadcastEval

This send a message to all shards

### Param

| Title | Description | Required |
| :--- | :--- | :--- |
| script | The js script | yes |

### Example

```text
const dl = require("discord.lib")
dl.shardManager("./path/to/your/file.js", 2)
dl.broadcastEval(`(${funcName})('${arg}')`);
```

