---
description: This function is not yet stable.
---

# ban



This is the function that will ban a member.

{% hint style="info" %}
For now, only member with ADMINISTRATOR permission could ban member. if you want to specify a permission, you need use the discord.lib.client interacting method. This method will be in the example section below
{% endhint %}

### Parameters

| Parameter | Description | Require |
| :--- | :--- | :--- |
| command | command name | yes |

## Example

### example for using discord.lib kick

```javascript
const dl = require("discord.lib")
dl.kick("A_ban")//usage will be A_ban @member#1234
```

### example for interacting with discord.lib.client

```javascript
const dl = require("discord.lib")
dl.client.on("message", msg => {
 if(msg.startsWith("A_ban")){
  if(!msg.member.hasPermission("your permission"))return;
  let mention = msg.mentions.users.first();
  let member = msg.guild.member(mention)
  member.ban("optional reason for audit log")
 }
})
```

