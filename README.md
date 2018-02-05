# [InviteManager](https://discordapp.com/api/oauth2/authorize?client_id=409875566800404480&permissions=268435488&scope=bot)

InviteManager allows you to manage the members of your server by looking at their invites.

For support and feature requests join our discord server: https://discord.gg/Am6p2Hs

IMPORTANT: Due to the way discord handles invites, it is not possible to find out who invited people that are already in your server. It only works for people who join AFTER you add the InviteManager to your server.

[Add bot to your server](https://discordapp.com/api/oauth2/authorize?client_id=409875566800404480&permissions=268435488&scope=bot)

## Commands

### Configure Bot (Mods only)

* `!setprefix <prefix>` Change prefix of commands so there are no collisions with other bots
* `!clearinvites` Clear all invites that happened in the past.
* `!restoreinvites` Restore invites that were cleared using the `!restoreinvites` command
* `!info @user` Display information about a user (who invited him, when he joined, who he invited)
* `!fake` List of users that might be trying to cheat the invite system by joining multiple times

### Manage ranks (Mods only)

* `!addRank @role invitesNeeded description (can be a text)` Add a rank to the bot
* `!removeRank @role` Delete a rank

### User Commands (everyone)

* `!ranks` Show a list of all ranks added by the mods
* `!invites` Displays how many invites the user has
* `!leaderboard #channel` (Channel is optional): Display a leaderboard of the members with the most invites. If the channel property is set, only invites created for that channel will be counted. Otherwise all permanent invites will be counted.
* `!members` Show how many users are in the server (Online, Bots, Humans, How many joined in the last 24hours and in the last week)

## Upcoming Features

* Keep invites even if the channel they were created for gets deleted.
* Find people who invite inactive people. This could be an indicator that they are using a service that adds dummy accounts.
