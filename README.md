# clientcommands
Adds several useful client-side commands to Minecraft

## Ungated fork

Upstream version 2.15 added a server opt-in requirement to several commands in response to
[Modrinth content rules](https://github.com/Earthcomputer/clientcommands/blob/eae16398316fa0295fe7172f8fd690f0a6da1f89/docs/server_installation.md).
That requirement prevents the commands from running unless the server installs ClientCommands
or the player has operator privileges.

This fork removes those client-side checks and restores the pre-2.15 behavior for `/careastats`,
`/cfindblock`, `/cfind`, `/cgetdata entity`, `/cghostblock`, and `/cglow entities`. It is intended
for players who use ClientCommands as a local utility mod and cannot install a companion mod on
the server they play on.

The fork does not grant server permissions or reveal data the client has not received. It only
removes ClientCommands' own local requirement that a server opt in before these commands run.

## Social
Discord: https://discord.gg/Jg7Bun7
Patreon: https://www.patreon.com/earthcomputer

## Installation
1. Download and run the [Fabric installer](https://fabricmc.net/use).
   - Click the "vanilla" button, leave the other settings as they are,
     and click "download installer".
   - Note: this step may vary if you aren't using the vanilla launcher
     or an old version of Minecraft.
1. Download [Fabric API](https://minecraft.curseforge.com/projects/fabric)
   and move it to the mods folder (`.minecraft/mods`).
1. Download this fork from the [releases page](https://github.com/EvModder/clientcommands/releases)
   and move it to the mods folder (`.minecraft/mods`).

## Contributing
To contribute translations, see the [translation contribution guidelines](docs/TRANSLATING.md).

For other contributions, see the [contribution guidelines](docs/CONTRIBUTING.md).
