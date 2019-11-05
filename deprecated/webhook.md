---
description: Depricated
---

# Webhook

Webhook allows you to send a webhook request on bot boot up. We currently do not allow user  to send webhook on a command to prevent webhook spam.

### Param

| Parameter | Description | Required |
| :--- | :--- | :--- |
| Webhook id | The id of webhook | yes |
| Webhook token | the token of webhook | yes |
| message | msg to send to the webhook | yes |

### Example

```text
const dl = require("discord.lib");
dl.webhook("webhook id", "webhook token", "I am the best bot!")
```

