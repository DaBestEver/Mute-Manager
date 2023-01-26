#Mute Manager
About MuteManager
A plugin that provides a way to mute players for a specific amount of time. This plugin will connect to Mojang servers for UUID lookups.

How to install
Just drop the jar file in your plugins directory and restart your server. Configure permissions.

Permissions
mutemanager.mute - Allows players to use /mute (Default: op)
mutemanager.unmute - Allows players to use /unmute (Default: op)
mutemanager.mutelist- Allows players to use /mutelist (Default: op)
mutemanager.listen - Allows players to optionally hear muted players. (Default: false)
mutemanager.mutenotify - Receives notifications when a player is muted. (Default: op)
mutemanager.unmutenotify - Receives notifications when a player is unmuted. (Default: op)
mutemanager.reload - Allows players to use /mutereload. (Default: op)
mutemanager.muteexempt - Players with this are exempt from being muted. (Default: false)
Configuration
See config.yml

Commands
Hint: Use * instead of player name to mute or unmute all players. Hint: To mute a person for 5 days you would do this: /mute player 5d reason

/mute [player|*] ([time(mhd)|perm]) ([reason])
/unmute [player|*]
/mutelist
/mutereload
