# Typings

This allows you to make your bot to start/stop typing in one or more specific channels.

## startTyping

### Param

| Parameters | Description | required |
| :--- | :--- | :--- |
| command | command to start typing | Yes |

### Example

```javascript
const dl = require("discord.lib")
dl.startTyping("starttyping")
dl.login("token", "Typing started!")
```

## stopTyping

### Param

| Parameters | Description | Required |
| :--- | :--- | :--- |
| command | Command to stop typing | yes |
| force | Force to stop typing | no |

### Example

```javascript
const dl = require("discord.lib")
dl.stopTyping("stoptyping", true)
dl.login("token", "Typing started!")
```

