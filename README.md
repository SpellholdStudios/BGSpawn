[![GitHub release (latest by date)](https://img.shields.io/github/v/release/SpellholdStudios/BGSpawn?color=darkred&include_prereleases&label=latest%20release)](https://github.com/SpellholdStudios/BGSpawn/releases/latest)
[![Github downloads (all releases)](https://img.shields.io/github/downloads/SpellholdStudios/BGSpawn/total.svg?color=gold)](https://github.com/SpellholdStudios/BGSpawn/releases)
[![Platform](https://img.shields.io/static/v1?label=platform&message=Windows%20%7C%20macOS%20%7C%20Linux&color=informational)](https://github.com/SpellholdStudios/BGSpawn/releases/latest)
[![Supported games](https://img.shields.io/static/v1?label=supported%20games&message=BG2%20%7C%20BGT%20%7C%20BG2%3AEE%20%7C%20EET&color=indigo)](https://github.com/SpellholdStudios/BGSpawn/releases)
[![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20German%20%7C%20Italian%20%7C%20Russian%20%7C%20Spanish%20%7C%20Chinese&color=limegreen)](https://github.com/SpellholdStudios/BGSpawn/releases)

# BGSpawn System

a WeiDU mod For BGT and EET, a Melkor_Morgoth75 production

[![SHS Forums](https://img.shields.io/static/v1?label=Discussion&message=SHS%20Forums&color=951514&labelColor=eee&style=for-the-badge)](http://www.shsforums.net/topic/39639-release-bgspawn-version-111 "Spellhold Studios Forums")

1. Introduction
2. General Overview
3. Installation/Compatibility
4. About the Mod
5. Credits
6. FAQ
7. Changes

# 1. INTRODUCTION

Tired of approaching always the same creatures around BG1's wild areas? Tired to face a single kobold with your party of high levelled characters? Do you love randomness? If the answers are "yes", so this mod could be for you ☺ 
BGSpawn is a WeiDU mod compatible with BGT and EET only. You may contact melkor_morgoth75 at SpellholdStudios forums if you encounter any issue.

# 2. GENERAL OVERVIEW

BGSpawn is a new system who handles "spawned creatures" appearing in Baldur's Gate's areas. I honestly never liked original spawns within the areas in the BG1 part of the game. You always face the very same encounters and, after many games, it has become really boring. Moreover the BG community lately has developed lot of mods for the BG2 portion of the game and I wanted to create something interesting for the BG1 part as well.

The main aim of the mod is simply to give some longevity to the game, especially in a BGT (Baldur's Gate Trilogy) game, where the users may start playing more than one game over and over (with so many mods around you may really want to start and play again and again).
So this mod is intended to be played in a BGT (Baldur's Gate Trilogy) or EET game only, as it uses many of the creatures from that engine.
Another aim of the mod is to give some challenges to the players, even the most experienced will find hard time sometimes playing with the new system. Let's also install a tactic-mod as SCS in your game and definitely spawns now could be a serious problem for your party (you have to think twice about leaving safe cities and go crossing wild lands ☺).

# 3. INSTALLATION/COMPATIBILTY

To install BGSpawn, just unpack your "package" in your game folder and then double-click on Setup-BGSpawn.exe to start the setup process.

Currently 5 components are part of the setup:
   - BGSpawn-system based on levels & party members (core install)
   - Choose time between re-spawns (8 hours,16 hours, 24 hours or close to never).
   - Decrease Spawn Point Probability (default is 100%)
   - Vampiric Wolf Lord (inspired to DavidW Wolf of Ulcaster)
   - BGSpawn random encounters between areas

The first is the core component of the mod and u must install it to have it working.
The "Time between re-spawn" sets how much time will pass before a new encounter spawns again in the very same spawn point after you've faced it. The latter is an optional (but cool) component who implements a different Vampiric Wolf in the game (and it can be faced during your random encounters within the areas).
To uninstall the component(s) just double-click again on Setup-BGSpawn.exe and select the Uninstall option.

BGSpawn should be compatible with any WeiDU mods. It has not been tested with all the mods around so please, get back to melkor_morgoth75 at SpellholdStudios if you find any incompatibility issues.
NOTE: conceptually BGSpawn system is NOT compatible with the BGT-Tweaks components "Tutu-levelled spawn" and/or "Deactivate BGT Spawns", as it handles the same concept (and currently it is based on the Tutu-levelled system). If BGSpawn detects the BGT-Tweak spawn components, it skips the installation process.

BGSpawn requires BGT or EET to be installed, if BGT or EET is not detected it will skip the installation process. It should be installed anytime after BGT or EET.

# 4. ABOUT THE MOD

BGSpawn changes all the "spawns" you may face in all the areas around Baldur's Gate. Now, with the new system, you won't have always the same spawned creature(s) as in the past. This will bring, hopefully, some freshness to the game and some longevity also. Moreover the spawned creatures now are based on the number of your party members and your levels. So you won't see anymore in a party of 6 character at 6th level a single wild dog approaching you, it really doesn't make sense to me. 
All the areas now have many, many different creatures that may spawn around. I implemented the system so that any creature, hopefully, is a possible and real encounter in that area (so, you won't see spiders in a desert land, bandits attacking you along with bears or weird stuff like that). 
You now also have the chance of face "no creature" or neutral encounters in a single spawn point, this makes sense too. The chances are based of course on the area you're travelling, so be prepared to encounter more (and dangerous) creatures in the Firewine Bridge area and maybe less and/or peaceful ones in the High Edge area.
Without spoiling too much, now undead encounters can ONLY be faced or found during the night. Yes, the system has different spawned creatures, depending if it is day-time or night-time. This makes more sense to me and it is closer to the reality, so be prepared if you pass across wild lands during the night ☺ 
Last little note about Humanoids: I implemented a different table-system for any humanoid creature, so the randomness and encounters about Humanoids is even higher. Let's hope you don't face them too much and at high levels … you may have difficult time indeed ☺
Please note that spawned creatures don't disappear in the area where you encountered them and eventually, if u ran away from them and rest, you will face them again (and possibly some others, if u choose the standard 8 hours time for re-spawning).

# 5. CREDITS

Mod Author: Melkor_Morgoth75

Creators of the game: Bioware and Black Isle Studios.

Tools used in creation of BGSpawn: WeiDU, Near Infinity.

Special thanks to:
  - Ascension64, for creating the wonderful WeiDU-edition BGT mod. Moreover, without his help in coding and his patience pointing me through the right directions, this mod couldn't have seen the light.
  - David W, for the kind permission to use some of his creatures (and scripts) of the outstanding SCS mod of him.
  - Erebusant, for providing important feedbacks and helping me with coding.
  - Spellhold Studios for hosting the mod and the BG forums. Without the help of the community, no mod could be completed.
  - Stoneangel, Isaya, Por Lisandro, Prowler & Cronox to provide the various translations of the mod.
  - 10th and Scud for the great help in squashing bugs.

# 6. FAQ
   - The installation fails because "BGT or EET could not be detected.  
   Please install BGT or EET BEFORE BGSpawn, it only works if BGT or EET is installed.
   - I installed the Vampiric Wolf Lord component but the Vampiric Wolf near the Temple of Lathander is not changed.  
   Please note that NOT all the Vampiric Wolves are changed by that component. Vampiric Wolf encounters in BGSpawn are affected.
   - I find too many high level scrolls and treasure with this mod.  
   Please note that most of the creatures are from the original BG2 game and this is something related to the loot assigned by the designers to the game. I strongly suggest to install the Realistic random treasures component of Aurora mod (by Miloch).

# 7. CHANGES

Please see [https://github.com/SpellholdStudios/BGSpawn/BGSpawn/Changelog.md ](https://github.com/SpellholdStudios/BGSpawn/blob/master/BGSpawn/Changelog.md)
