# Attachments

Our package gives you a feature to send attachment. This doc shows you how to do it.

### Param

| Parameters | Description | Required |
| :--- | :--- | :--- |
| command | The command name | yes |
| url | The directory/url of the image/file | yes |
| buffer | To enable file buffer | no |

### Examples

Example of not using buffer

```text
const dl = require("discord.lib")
dl.attachment("command", "https://example.com/image.png/ or ./path/to/your/file");
dl.login("token", "I am the best bot!")
```

Example of using buffer

{% hint style="info" %}
You are require to specify an directory.
{% endhint %}

```text
const dl = require("discord.lib")
dl.attachment("command", "./path/to/your/file.js", "buffer");
dl.login("token", "I am the best bot!")
```

