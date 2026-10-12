# SelfHost (Fabric, Minecraft 1.21.11, Java 21)

Host your singleplayer world from your own PC. Client-side mod; needs Fabric Loader + Fabric API.

## Use it
- Pause menu -> **Host World** (next to Open to LAN), or just type **/host**.
- Premium and non-premium players can join the same world (default config).
- Other commands: /host stop, status, tunnel, maxplayers <n>, whitelist add|remove|list|on|off

## Build the jar
Option A (PC with JDK 21): `./gradlew build` (Windows: `gradlew.bat build`) -> build/libs/selfhost-1.0.0.jar
Option B (no setup): push this folder to a GitHub repo -> Actions tab -> "Build SelfHost jar" -> download the `selfhost-jar` artifact.
Use the jar WITHOUT "-sources" in its name.

Config: config/selfhost.json
