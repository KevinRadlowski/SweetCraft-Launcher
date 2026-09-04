# SweetCraft Launcher

SweetCraft Launcher is the official dedicated launcher for the **SweetCraft Minecraft modpack and multiplayer server**.

> **Status:** Work in progress — SweetCraft Launcher is currently under active development and has not yet been publicly released.

## About

SweetCraft is a curated modded Minecraft experience running on Minecraft Java Edition.

The goal of SweetCraft Launcher is to make installing, updating and joining SweetCraft as simple as possible, including for players who are not familiar with manually managing Minecraft mods.

The launcher will automatically maintain an isolated SweetCraft installation containing the exact versions required by the server.

## Planned features

- Automatic Minecraft installation and management
- Automatic Fabric Loader installation
- Automatic installation and updating of the SweetCraft modpack
- Exact mod version management
- Incremental updates
- File integrity verification
- Automatic repair of missing or corrupted managed files
- Separate SweetCraft Minecraft instance
- Microsoft authentication
- Direct connection information for the SweetCraft multiplayer server

## Mod distribution

SweetCraft Launcher is not intended to operate as a general-purpose mod browser or as an alternative mod distribution platform.

Third-party mods are obtained from their authorized upstream distribution sources whenever possible.

The project currently integrates or plans to integrate providers including:

- Modrinth
- CurseForge
- Official mod-author distribution sources

SweetCraft Launcher respects the distribution choices made by individual mod authors.

For CurseForge-hosted projects, the launcher is designed to use the official CurseForge API and authorized download infrastructure. Files for which third-party distribution is disabled will not be circumvented or independently rehosted.

SweetCraft does not claim ownership of third-party Minecraft mods.

All third-party mods remain the property of their respective authors and are subject to their respective licenses and distribution terms.

## Attribution

SweetCraft documentation and launcher interfaces will provide attribution and links to the original project pages for third-party content used by the modpack.

A complete third-party software and mod notice will be maintained as the project approaches public release.

## Technical information

Current SweetCraft target:

- **Minecraft Java Edition:** 26.1.2
- **Mod loader:** Fabric
- **Fabric Loader:** 0.19.3
- **Multiplayer server:** `sweetcraft.datho.st`

The launcher uses versioned manifests and cryptographic hashes to maintain a deterministic installation.

Mods are pinned to specific versions tested with the SweetCraft server rather than automatically selecting arbitrary newer versions.

## Privacy & security

SweetCraft Launcher is being designed with privacy and security in mind.

The launcher will not request or store users' Microsoft passwords.

Microsoft authentication will use the supported OAuth authentication flow.

Secrets and provider API credentials are not stored in this public repository or distributed as part of public manifests.

## Legal notice

SweetCraft Launcher is an independent community project.

It is not affiliated with, endorsed by, or associated with Mojang Studios or Microsoft.

Minecraft is a trademark of Microsoft Corporation.

Third-party trademarks, project names and software belong to their respective owners.

## Project status

SweetCraft Launcher is currently under active development.

Public releases, documentation and additional project information will be published here as development progresses.

---

**SweetCraft Launcher**  
Publisher: Maidenhead
