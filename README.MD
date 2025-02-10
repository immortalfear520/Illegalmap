# Illegalmap
<div align="center">
  <a target="_blank">
    <img alt="version" src="https://img.shields.io/github/v/release/Quantizr/DungeonRoomsMod?color=%239f00ff&style=for-the-badge" />
  </a>
  <a target="_blank">
    <img alt="mcversion" src="https://img.shields.io/badge/MC%20Version-1.8.9-blue?color=%239f00ff&style=for-the-badge" />
  </a>
</div>


I will not consider adding features that are too cheaty, pointless or are just unrelated to this module.

IllegalMap is a ChatTriggers module that scans each Dungeon to give extra information to the user, like which rooms and puzzles are in the dungeon and exactly how many secrets there are before the dungeon even starts. The map also shows the user other useful information like the total secrets, death penalties, crypts, mimic and the current score right underneath the map so that the user never needs to look at the tab list. IllegalMap can be used on its own as your primary dungeon map, with significantly more features than any other map currently. IllegalMap is highly customizable through the /dmap command.

Note: Due to Hypixel's render distance limitation, not all of the dungeon will be visible from the starting room.

<img src="https://i.imgur.com/yMl9bRa.png">

## Features
## Dungeon Preview
IllegalMap automatically scans the dungeon as soon as you enter it. After the dungeon has been fully scanned (And the chunks all loaded), it will stop scanning.
By default, all of the rooms before the dungeon begins will be shown clearly, but once the dungeon starts all of the unexplored rooms will be darkened so that they can be distinguished from already explored rooms.
There is an option to show room names and secrets all the time in the Config gui (/dmap), however if you want a cleaner looking map it is recommended to use the **"Peek Rooms"** keybind which will only show room names while the key is being held.

<div class="row" align="center">
    <img src="https://i.imgur.com/iujvHR2.png" width=30%/>
    <img src="https://i.imgur.com/azlvob4.png" width=30%/>
    <img src="https://i.imgur.com/lVIlFmj.png" width=30%/>
</div>

## Dungeon Info
IllegalMap shows useful info about the dungeon underneath the map (By default) including found-remaining-total secrets, crypts, minimum secrets (For S+), score pentalty for deaths, the current score and the mimic status (See screenshots from Dungeon Preview).
The dungeon info can also be configured to display seperately from the map, or remain under the map during clear and seperate upon entering boss.

<img src="https://i.imgur.com/UCrQTUA.png" width=50%/>

## Star Mob ESP and Radar
Scans for star mobs in the world. Can be configured to have boxes drawn around them in the world, or show their locations on the map as small icons.

<img src="https://i.imgur.com/1LtnSpG.png" width=30%/>

The mob heads can be configured to have their border colors changed or just appear as small colored dots.

## Dungeon Logs
IllegalMap logs all of the dungeons that you scan. This lets the user view interesting statistics about the dungeon like the average number of secrets per floor, which puzzles or rooms appear the most (or least) or the average number of wither doors in each dungeon.
The command for Dungeon Logs is **"/dlogsnew \[floor]"**. If no floor is given, then it will show the statistics for every dungeon that you have logged.
The room percentages shown for rooms and puzzles show how the percentage of runs which that room appears in.

<img src="https://i.imgur.com/yecwGr4.png"/>
<img src="https://i.imgur.com/QLjAaHm.png"/>

## Feature List
##### General
- Show unexplored dungeon rooms
- Show number of secrets in dungeon before the dungeon starts
- Automatically scans the dungeon
- Change background color and transparency of map
- Change map, head and checkmark scale
- Customizable map border
  - Smooth RGB option
  - Solid color
- Accurate player icons (Always links icons to correct player)
- Show player usernames on map
  - Option to show player names whilst holding spirit leaps
  - Show player ranks on the map
- Automatically notifies of new IllegalMap updates

#### Score Calculator
- Customizable 270/300 score messages
- Client-side 270/300 score messages
- Auto detect mimic being found
- Announce mimic being killed
- Option to show seperately from the main map

##### Rooms
- Show which room contains the mimic (Floor 6-7)
- Show room names
- Show room secrets
- Darken unexplored rooms
- Change wither door color on the map for visibility or aesthetics

#### Misc
- Star mob radar
  - Shows all of the loaded star mobs on your map
  - Togglable via /star
- Wither door ESP
- Star mob ESP
  - Also togglable via /staresp


### Installation

Download the newest Release and use it like every other forge mod.

### How to install a forge mod
- [Download the latest forge version](http://files.minecraftforge.net/maven/net/minecraftforge/forge/index_1.8.9.html "Download Forge")
- Run it to install forge  

- Open minecraft launcher and check if forge's profile is there, if not then you can create it ![image](https://user-images.githubusercontent.com/74936369/111808098-b8d7bf00-88e4-11eb-8a2d-60e93b1406a5.png)
- **Windows**: Press windows+r and type %appdata%/.minecraft/
- **Linux**: .minecraft is located in your home folder. ~/.minecraft
- **Mac**: do ⌘ (Command) + Space type "~/Library/Application Support/minecraft/
- Create a folder called "mods" if it isnt there already. then put the mods you download inside that folder and start minecraft.
                   
### Legal Disclaimer

This was made for educational purposes only, nobody which directly involved in this project is responsible for any damages caused.
**You are responsible for your actions.**
