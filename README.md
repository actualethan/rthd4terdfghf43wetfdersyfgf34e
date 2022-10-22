# Discord GEN-BOT
Hi this bot is made by ToxicCodes
[pls sub me on yt it's garat tht u subed me in yt thansk for using my code.]
## Installation
Install all dependencies:
```
$ npm install
```

### Configuration
Before you try to start the bot, you need to complete the `config.json` file in the main folder.

#### Default
```json
{
    "token": "",
    "prefix": "gen!",
    "genChannel": "",
    "genCooldown": "1000",
    "color": {
        "green": "0x57F287",
        "yellow": "0xFEE75C",
        "red": "0xED4245",
        "default": "0x5865F2"
    },
    "command": {
        "notfound_message": true,
        "error_message": true
    }
}
```
- `token`: Your discord bot's token
- `prefix`: Your bot's command prefix *(for example: !help | ?help | gen!help)*
- `genChannel`: Forced channel for `gen` command
- `genCooldown`: Cooldown between two executions of `gen` command *(use milliseconds)*
- `notfound_message`: Sends a message to the channel if the message starts with the prefix but does not exists
- `error_message`: Sends a message to the channel if an error occured and this setting is "true
---

## How it works?

### Adding account/data
Add an account or a data with the `add` command. The space character in the data parameter make the write wrong.
- Example: `add example_service abcd`
- Wrong example: `add example_service abcd` ~~`efg hijk`~~ <-- the last 2 arguments are not stored

---

### Account/data generating
You can add account to the bot using `gen` command.
E##`
