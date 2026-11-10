# Obsidian Client — Minecraft 1.21.11

Black-themed fork of Meteor Client, modified 2026-11-09.
Upstream: https://github.com/MeteorDevelopment/meteor-client/tree/48030717dc0d4898a195a713fb048bf597fc5b54

Download the compiled JAR from this repository's Releases page.

## Build

Install JDK 21 and set JAVA_HOME to its folder. Internet access is required.
From this folder run `./gradlew.bat build` on Windows or `./gradlew build` on Linux.
The installable artifact is `build/libs/obsidian-client-1.21.11-local.jar`.

## Install

Use Minecraft Java 1.21.11 with Fabric Loader 0.18.2 or newer.
Place the installable JAR in that instance's mods folder; remove the original Meteor JAR first.
Press Right Shift to open the GUI. The command prefix is a period.
Settings are stored separately in the instance's obsidian-client folder.

## Changes

- Obsidian branding in mod metadata, GUI theme, chat prefix, HUD group, splash text and launcher.
- Black panels, grayscale controls and white text, with a geometric Obsidian icon.
- Separate configuration directory and renamed build artifact.
- Upstream online-player pings and update destination disabled; Maven publishing removed.
- Discord presence is off by default. Optional use requires your own Discord application ID,
  application name Obsidian Client, and an uploaded asset named obsidian.
- Internal Fabric ID, Java packages and resource namespaces remain meteor-client for compatibility.
  This fork cannot be installed alongside Meteor. Addon compatibility is not runtime-tested.

## Validation

See VALIDATION.txt for actual build results. No Minecraft runtime validation has been performed.
After installation check title branding, GUI contrast, chat prefix, and settings persistence after restart.
Upstream optional cape services and documentation links are retained.

## License and attribution

Derived from Meteor Client by Meteor Development. Original authors, copyright notices,
GPL-3.0 LICENSE and upstream documentation are retained. This is an unofficial modified fork.
Redistributions must comply with the included license, including corresponding source requirements.
