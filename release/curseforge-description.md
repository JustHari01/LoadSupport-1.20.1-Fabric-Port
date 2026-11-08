# Load Support (UNOFFICIAL 1.20.1 Fabric Backport)

An unofficial Fabric backport of Load Support by vaporvee for Minecraft 1.20.1. It keeps the original client-side memory warning and load-complete sound features, adapted for the older Minecraft and Fabric APIs.

## Features

- Shows a separate warning when the Java memory limit is below the configured minimum.
- Hides the Minecraft window while the warning is open; dismissing the warning stops startup.
- Plays a configurable sound once the title screen opens after loading.
- Lets you configure the minimum memory, warning text, help link, and sound identifier in `config/loadsupport.toml`.

The default memory threshold is 4 GB. The default completion sound is the Minecraft resource `minecraft:ui.toast.challenge_complete`.

## Requirements

- Minecraft 1.20.1
- Fabric Loader 0.16.14 or newer
- Fabric API 0.92.12+1.20.1
- Cloth Config 11.1.136 for Minecraft 1.20.1
- Java 17 or newer

This is a client-only mod. Install it and its dependencies in the client instance; a dedicated server does not need it.

## Attribution and license

Original project: [Load Support by vaporvee on Modrinth](https://modrinth.com/mod/loadsupport). Original source: [vaporvee/LoadSupport on Codeberg](https://codeberg.org/vaporvee/LoadSupport). The upstream source and in-game icon are licensed under Apache-2.0, and the license text is included with this release. This community backport is not affiliated with or endorsed by vaporvee.

Backport source: https://github.com/JustHari01/LoadSupport-1.20.1-Fabric-Port

AI tools assisted with the compatibility backport and release description and generated the separate CurseForge project icon; the icon is not part of the mod JAR, and this disclosure does not describe the upstream project.
