# exampleBot

This function let the package download a example bot file with all code with filename `bot.js` 

### Parameter

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter</th>
      <th style="text-align:left">Description</th>
      <th style="text-align:left">Required</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">destination</td>
      <td style="text-align:left">
        <p>download destination,</p>
        <p>use &quot;./&quot; for downloads in the</p>
        <p>current folder</p>
      </td>
      <td style="text-align:left">yes</td>
    </tr>
  </tbody>
</table>### Example

```javascript
const dl = require("discord.lib")
dl.exampleBot("./")
//will create a bot.js file with all code in it
```

