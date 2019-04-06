# About
Recently due to some bad actors Discord ended up blocking the entire User-Agent of an application I use.

Unfortunately this application doesn't allow you to modify the User-Agent header either so as a result I've thrown this sample nginx config together to show what can be done to work around this issue.

The nginx script itself has been designed with https in mind and does work when filled out appropriately. In theory there's nothing to stop a http-based version from working but hey, encrypt the internet and all that!

## Usage
Typically your average discord api usage would look like 
`https://discordapp.com/api/guilds/123451234512345/members/678906890`

_Instead_, you replace the discord url with your own, e.g.
`https://discord.yourdomain.com/api/guilds/123451234512345/members/678906890`


## Disclaimers
As usual, use at your own risk and use responsibly. No warranty / support is provided and the script is supplied as-is.

