# Load Support (UNOFFICIAL 1.20.1 Fabric Backport)

An unofficial Minecraft 1.20.1 Fabric backport of **Load Support** by vaporvee. It keeps the upstream 1.2.1 behavior: show a configurable warning when the Java memory limit is too low, hide the Minecraft window while the separate warning is open, and stop startup after the warning is dismissed. It also plays a configurable sound after loading finishes.

This project is a community-maintained backport. It is not affiliated with or endorsed by vaporvee.

## Requirements

- Minecraft 1.20.1
- Fabric Loader 0.16.14 or newer
- Fabric API 0.92.12+1.20.1
- Cloth Config 11.1.136 for Minecraft 1.20.1
- Java 17 or newer

Install the mod and its dependencies in the client instance. This is a client-only mod and is not required on a dedicated server.

## Configuration

Settings are stored in `config/loadsupport.toml`. The defaults include a 4 GB minimum memory threshold and the Minecraft sound `minecraft:ui.toast.challenge_complete` for the load-complete cue. You can change the minimum, warning text, help link, and sound identifier there.

## Credits and license

The upstream project is [Load Support on Modrinth](https://modrinth.com/mod/loadsupport), and its source is [vaporvee/LoadSupport on Codeberg](https://codeberg.org/vaporvee/LoadSupport). The upstream code and bundled icon are distributed under Apache-2.0; the original license is included in this repository and release JAR. Copyright and attribution for the upstream work remain with its author.

Backport source: [JustHari01/LoadSupport-1.20.1-Fabric-Port](https://github.com/JustHari01/LoadSupport-1.20.1-Fabric-Port).

The generated 512×512 icon in `artwork/LoadSupport-CurseForge-Icon-512.png` is a separate CurseForge project image and is not included in the mod JAR. The upstream icon remains in the JAR under its original license.

## Building

Use Java 17 or newer and run `gradlew.bat remapJar` on Windows or `./gradlew remapJar` on macOS/Linux. The release JAR is written to `build/libs/`.

AI tools assisted with the 1.20.1 compatibility backport and this release description, and generated the separate CurseForge project icon. This disclosure applies only to this unofficial backport, not to the upstream project.
