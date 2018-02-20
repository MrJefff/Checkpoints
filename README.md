**Checkpoints** Restore points for players to teleport to when the server restarts

Ever had a cluster fuck of players winge and cry to you about a server restart and them loosing their loot? Welp, this solves that... Kinda.

This plugin allows players to set their "checkpoints" on sleeping bags they own. When the server restarts all players get teleported to their set "checkpoints" at their sleeping bags.

This plugin has no configuration file because there's not much to be configured.

## Permissions

- **checkpoints.allow** -- Allows a player to use the commands

## Chat Commands

- **/checkpoint set** -- Sets a checkpoint on the sleeping bag they're looking at.
- **/checkpoint remove** -- Removes a players previously set checkpoint to allow them to set a new one.

## Frequently Asked Questions

**Question:** How does it work?
**Answer:** Good question. It simply checks the reason of the player disconnect, if their disconnect reason contains "restarting", ie "Kicked: Server Restarting", then their player will be moved to their set position.
