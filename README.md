# Coalesce Mods

Preselected Among Us mod-bundle.

* [Overview](#Overview)
* [Included Mods](#Included-Mods)
* [Installation](#Installation)
* [Uninstalling](#Uninstalling)

# Overview

Get the most out of Among Us with this handpicked collection of
mods that work great together.

>**⚠ Note: This is only compatible with the Steam version.**
>
>Currently supported version: **v2021.4.14s**
>
>Use [BetterCrewLink](https://github.com/OhMyGuus/BetterCrewLink) for Proximity Voice Chat.

# Included Mods

Click the links in the ***Mod*** column below to read more about each mod.

|Mod                                                           |Description          |
|:-------------------------------------------------------------|:--------------------|
|[CustomServersClient](https://github.com/CrowdedMods/CustomServersClient)|Allows region selector customizations.|
|[CrowdedMod](https://github.com/CrowdedMods/CrowdedMod)|Allows more players and Impostors on impostor server.|
|[TownOfImpostors](https://github.com/AJMix/TownOfImpostors)|Adds a variety of new roles and other features.|

# Installation

- Make a copy of your clean, unmodded game’s root directory `Steam/steamapps/common/Among Us` and rename the copied directory to something like "Among Us Modded". It is advised to install mods in the copied directory, so that steam updates do not break compatibility with mods.
- You can get to your root directory by right-clicking Among Us in Steam -> Properties -> Local Files -> Browse.
- Extract the contents of the [latest released](https://github.com/string-theorist/coalesce/releases) zip file into your "Among Us Modded" folder.
- Ensure the directory that is being modded now contains at least the following:
```
.
├── Among Us_Data
├── BepInEx <--
├── mono <--
├── TownOfImpostors_CustomHats <--
├── TownOfImpostors_Data <--
├── UserData <--
├── Among Us.exe
├── baselib.dll
├── doorstop_config.ini <--
├── GameAssembly.dll
├── steam_appid.txt <--
├── UnityCrashHandler32.exe
├── UnityPlayer.dll
└── winhttp.dll <--
```
- Launch Among Us. Please note that the first time launching the game may take longer than usual, so wait a few minutes before trying to reopen the game.
- If the installation was successful, you should see additional text appear at the top left corner of the screen.

# Uninstalling

- Simply navigate to your Among Us folder and delete the following folders and files:
  - ***BepInEx*** folder
  - ***mono*** folder
  - ***doorstop_config.ini*** file
  - ***winhttp.dll*** file
