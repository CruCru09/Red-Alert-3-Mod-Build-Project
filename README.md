# Red-Alert-3-Mod-Build-Project
Do you want to create a MOD for Red Alert 3? Maybe you'll find what you need here!

You need to install Git LFS when cloning, otherwise you won't be able to get the files.

# Quick Start
About the Mod SDK

The RA3 MOD SDK is the official mod development toolkit released by EA for Command & Conquer: Red Alert 3, allowing players to modify game content, create new units, adjust balance, and even create entirely new gaming experiences.

## Core Tools

Mod BuildStudio
A graphical compilation tool that replaces cumbersome command-line operations. You just need to select your Mod and click a button to compile, with faster compilation speeds.

Worldbuilder (Map Editor)
Worldbuilder supports directly using custom Mod assets for map and mission creation. If no new assets are involved, the standard version is sufficient.

## How It Works:

Modifying RA3 essentially involves overriding XML files. The SDK's SageXML folder contains the original game data (units, weapons, UI, etc.). When creating a Mod, you need to:

1. Copy the XML files you want to modify into your Mod folder
2. After modifying the content, register these files via Mod.xml
3. Compile and package them using BuildStudio
