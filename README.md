# clientcommands
Adds several useful client-side commands to Minecraft

## Ungated fork

Upstream version 2.15 added a server opt-in requirement to several commands in response to
[Modrinth content rules](https://github.com/Earthcomputer/clientcommands/blob/eae16398316fa0295fe7172f8fd690f0a6da1f89/docs/server_installation.md).
That requirement prevents the commands from running unless the server installs ClientCommands
or the player has operator privileges.

You can [read EarthComputer's post regarding this here](https://github.com/Earthcomputer/clientcommands/blob/eae16398316fa0295fe7172f8fd690f0a6da1f89/docs/server_installation.md).

This fork removes those client-side checks and restores the pre-2.15 behavior. It is intended for
players who use ClientCommands as a local utility mod and cannot install a companion mod on the
server they play on.

The fork does not grant server permissions or reveal data the client has not received. It only
removes ClientCommands' own local requirement that a server opt in before these commands run.
