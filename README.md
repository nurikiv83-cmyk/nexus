# NEXUS CLIENT v1.0

A fresh client-side Fabric mod project for Minecraft **1.21.11** and **Java 21**.

## Included in this starter build

- Right Shift opens the NEXUS ClickGUI.
- Dark interface with a selectable 3 x 3 accent palette:
  Blue, Orange, Yellow / Red, Purple, Pink / Green, Dark Blue, Skin.
- Theme, HUD toggle, and cosmetic toggle are saved in `config/nexus-client.properties`.
- Optional local End Rod cosmetic particles around your own player.
- No server-side movement changes, anti-cheat bypass, or hidden cheat features.

## Build

1. Install a JDK 21.
2. Install Gradle 8.14 or newer.
3. Open a terminal in this folder.
4. Run `gradle build`.
5. The mod JAR will be in `build/libs/`.

On Windows, you can run `gradle build` from PowerShell or Command Prompt if Gradle is on PATH.

## Install

Copy `build/libs/nexus-client-1.0.0.jar` into your Minecraft instance's `mods` folder.
Use Fabric Loader for Minecraft 1.21.11 and install a matching Fabric API.

## Notes

This is the initial source project, not a precompiled JAR. The HUD toggle is stored for the next HUD implementation; the first milestone focuses on the GUI, persistent themes, and local cosmetic particles. Cosmetics are local-only and are not visible to other players.
