## DiscordSync
Paper plugin enforcing Discord synchronization

### Features
##### 1. Mandatory Discord account linking
To join the Minecraft server, users must link a Discord account. Upon join, users will be given a unique 4-character code.
Users can link accounts by using `/link <code>` in a DM with the bot user. Accounts can also be unlinked with `/unlink`.

Note: You can also enable the reverse by setting a role to grant on link and granting that role exclusive server access.

##### 2. Discord <-> Minecraft chat bridge
A configurable chat bridge set for a specific Discord channel. Complete with events and death messages.

##### 3. Moderation synchronization
Synchronize bans and mutes between your Discord and Minecraft servers.

##### 4. Offline mode username authentication
To make offline mode feasable, you can require users to verify their logins via Discord DM.
An accessible embed containing information about a login is sent to a user, accepting it grants that IP address login access for 1 hour.

##### 5. Offline mode skins
Users may upload skins for use in offline mode through usage of the `/skin` command.

### Requirements
##### PaperMC
This plugin uses Mojang mappings and Paper-specific functionality.
##### (Optional) MySQL database
For larger servers that want a cetralized storage solution.

### Credit
##### Thanks to the following projects for making this plugin possible:
- [PaperMC](https://papermc.io/software/paper)
- [JDA](https://github.com/discord-jda/JDA)
##### Inspiration was drawn from the following projects:
- [DiscordSRV](https://github.com/DiscordSRV/DiscordSRV)
- [AuthMeReloaded](https://github.com/AuthMe/AuthMeReloaded)
