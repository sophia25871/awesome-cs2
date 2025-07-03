<div align="center" style="text-align: center">
<h3>Awesome CS2</h3>
<p>
  An awesome list for all available cs2 development information, including modding frameworks, development resources, plugins and etc.
</p>
<p>
  Last Sync: <strong>2026/10/13 06:32:16</strong>
</p>
<p>
  Project Uptime: <strong>1 year</strong>
</p>

</div>

# Contents
- [General](#general)
- [Tools](#tools)
- [Status Trackers](#status-trackers)
- [Modding Frameworks](#modding-frameworks)
- [Development Resources](#development-resources)
- [Communities](#communities)
- [Plugins](#plugins)
  - [Metamod Plugins](#metamod-plugins)
  - [CounterStrikeSharp Plugins](#counterstrikesharp-plugins)
  - [SwiftlyS2 Plugins](#swiftlys2-plugins)
- [Contributors](#contributors)
- [Contributing](#contributing)

# General
- **[Source2 Wiki](https://source2.wiki)**\
  *An actively maintained source2 wiki, where you can learn information about workshop tools and entities.*

- **[cs2browser.net](https://cs2browser.net)**\
  *A clean and live cs2 community server browser without fake servers and advertisements.*

- **[Valve Official Documentation](https://developer.valvesoftware.com/)**\
  *Valve's official documentation for cs2 and other source games.*\
  ***Not recommended for checking cs2 information, most of them are outdated or absent.***

- **[gamebanana.com](https://gamebanana.com/games/18134)**\
  *A workshop resource website that contains cs2 models, maps and etc.*

# Tools
- **[Source2Viewer](https://s2v.app/)**\
  *A powerful tool to unpack and decompile resources from vpk files.*

- **[VPulse Editor](https://github.com/LionDoge/vpulse-editor)**\
  *A visual programming tool to write the vpulse script, which is a new unreleased visualized script system for source2 to replace vscript.*

- **[Schema Dumper](https://github.com/GAMMACASE/Source2SchemaDumper)**\
  *A metamod plugin for dumping schemas from game binary, and also able to generate a header file that can be imported in IDA for reverse engineering.*

- **[DepotDownloader](https://github.com/SteamRE/DepotDownloader)**\
  *A tool to download game files of a specific version.*

- **[PltPatcher](https://github.com/GAMMACASE/PltPatcher)**\
  *A IDA python plugin to patch plt sections when IDA fails to do so automatically, you might encounter such problem when decompiling linux binaries, made by GAMMACASE.*

# Status Trackers

- **[SteamDB](https://steamdb.info/app/730/charts/)**\
  *A website tracking steam games information.*

- **[cs2-signatures](https://github.com/ianlucas/cs2-signatures)**\
  *A github repo for tracking gamedata status after a game update.*

# Modding Frameworks
- **[Metamod](https://github.com/alliedmodders/metamod-source)** [[Website](https://www.sourcemm.net/downloads.php?branch=dev)] [[Discord](https://discord.com/invite/HUc67zN)]\
  *The cobblestone of all of the current open source framework since source1, written in C++, hard to develop but have access to fundamental things.*\
  ***Please notice that it's the dev branch that support cs2, make sure you download the right version.***
  
- **[CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp)** [[Website](https://docs.cssharp.dev/)] [[Discord](https://discord.com/invite/eAZU3guKWU)]\
  *The most popular modding framework for cs2, the plugins are written in c#.*\
  *Alias: CS#, cssharp*

- **[SwiftlyS2](https://github.com/swiftly-solution/swiftlys2)** [[Website](https://swiftlys2.net)] [[Discord](https://swiftlys2.net/discord)]\
  *A modding framework that support c#, with more features than counterstrikesharp.*

- **[Modsharp](https://github.com/Kxnrl/modsharp-public)** [[Website](https://docs.modsharp.net/)] [[Discord](https://discord.com/invite/wKarAjHm2G)]
  *Modern Source 2 Modding Solution.*

- **[Plugify](https://github.com/untrustedmodders/plugify)** [[Website](https://plugify.net)] [[Discord](https://discord.gg/untrustedmodders)]\
  *A modding framework that support tons of programming languages, more information can be found in there discord channel and website.*

# Development Resources
These are the websites with resources that you might need to check during development.

- **[ConVars](https://github.com/SteamDatabase/GameTracking-CS2/blob/master/DumpSource2/convars.txt)**\
  *A list of all cs2 convars, directly dumped from latest cs2 binary.*

- **[Commands](https://github.com/SteamDatabase/GameTracking-CS2/blob/master/DumpSource2/commands.txt)**\
  *A list of all cs2 commands, directly dumped from latest cs2 binary.*

- **[Game Events](https://cs2.poggu.me/dumped-data/game-events)**\
  *A list of all cs2 game events.*\
  *The data might be outdated, if so, you can find the latest ones here:*\
  *[core.gameevents](https://github.com/SteamDatabase/GameTracking-CS2/blob/master/game/core/pak01_dir/resource/core.gameevents)*
  *[game.gameevents](https://github.com/SteamDatabase/GameTracking-CS2/blob/master/game/csgo/pak01_dir/resource/game.gameevents)*
  *[mod.gameevents](https://github.com/SteamDatabase/GameTracking-CS2/blob/master/game/csgo/pak01_dir/resource/mod.gameevents)*

- **[Schemas](https://github.com/SteamDatabase/GameTracking-CS2/tree/master/DumpSource2/schemas)**\
  *A list of all cs2 schema classes and fields, directly dumped from latest cs2 binary.*

- **[Schema Explorer](https://s2v.app/SchemaExplorer/)**\
  *A website that visualize all schema classes and fields, with advanced query features.

- **[Source2 Dumper](https://boeing666.github.io/source2-dumper)**\
  *A website that visualize all schema classes and fields, convars, commands and etc.

- **[Entities](https://source2.wiki)**\
  *A list of all cs2 entities.*

- **[Protobufs](https://github.com/SteamDatabase/GameTracking-CS2/blob/master/Protobufs)**\
  *A list of all cs2 protobuf definitions.*

- **[Datamaps](https://swiftlys2.net/docs/api/datamaps/)**\
  *A list of all cs2 datamap (entity keyvalues field, input, output and etc.)*
  
- **[gdc.kitsune-lab.com](https://gdc.kitsune-lab.com)**\
  *A online gamedata tracker and validator, maintaining an active list for function signatures and offsets. If there's an game update that break your server, you might find the new gamedata here.*

- **[wiki.alliedmods.net](https://wiki.alliedmods.net/)**\
  *Alliedmodders' wiki. You can find documentation about metamod, ambuild and sourcehook development here.*

- **[HL2SDK](https://github.com/alliedmodders/hl2sdk/tree/cs2)**\
  *Actively maintained SDK for cs2.*

- **[HL2SDK Wend4r's fork](https://github.com/Wend4r/sourcesdk)**\
  *A fork of hl2sdk, if there's a game update, you might find what have changed in here or in pull requests.*

- **[cstrike15_src](https://github.com/perilouswithadollarsign/cstrike15_src)**\
  *CSGO Leaked source code in 2020, cs2 is still using some codes from it.*

- **[cs2.poggu.me](https://cs2.poggu.me/)**\
  *A general information website made by poggu.*

- **[Source2ZE Map Porting Guide](https://docs.google.com/document/d/1buKzjP-2com9GcXVxCfyRBi6sDiKmzMoVy9RNbYQqIo)**\
  *A guide about porting map from csgo, written by s2ze community.*

- **[S2TS](https://s2ts.net/)**\
  *A project that compiles typescript codes into .vts_c files that can run in cs2 scripting engine.*\
  *Also provide documentation for current SourceTS API.*

# Communities
- **[Alliedmodders Discord](https://discord.com/invite/HUc67zN)**\
  *Official discord for alliedmodders, you can find discussions about metamod and sdk here.*

- **[Source2ZE Discord](https://discord.gg/QsSGf9ZEVs)**\
  *Official discord for source2ze community, mainly targeting workshop developers, you can find discussions including maps, models and cs2fixes here.*

- **[CounterStrikeSharp Discord](https://discord.com/invite/eAZU3guKWU)**\
  *Official discord for counterstrikesharp, you can find plugins, code snippets and development discussion here.*

- **[ModSharp Discord](https://discord.gg/wKarAjHm2G)**\
  *Official discord for modsharp, which is a currently unreleased modding framework.*

- **[SwiftlyS2 Discord](https://swiftlys2.net/discord)**\
  *Official discord for swiftlys2, you can find swiftlys2 plugins, code snippets, and discuss about swiftlys2 modding framework here.*

- **[Plugify Discord](https://discord.gg/untrustedmodders)**\
  *Official discord for plugify, you can find plugify plugins, code snippets, and discuss about plugify modding framework here.*

- **[bbs.csgocn.net](https://bbs.csgocn.net/)**\
  *A Chinese forum for cs2 server development.*

- **[hlmod.net](https://hlmod.net/)**\
  *A Russian forum for source games development.*

# Plugins

## Metamod Plugins

- **[Source2ZE/CS2Fixes](https://github.com/Source2ZE/CS2Fixes)**<br>
  ⭐ 363<br>
  ⏱️ updated 11 minutes ago<br>
  *A plugin with tons of fixes and features aimed but not limited to zombie escape.*

- **[KZGlobalTeam/cs2kz-metamod](https://github.com/KZGlobalTeam/cs2kz-metamod)**<br>
  ⭐ 207<br>
  ⏱️ updated 1 hour ago<br>
  *KZ plugin for cs2. WIP, not ready for release.*

- **[Source2ZE/MultiAddonManager](https://github.com/Source2ZE/MultiAddonManager)**<br>
  ⭐ 132<br>
  ⏱️ updated 2 weeks ago<br>
  *A plugin that allows you to use multiple workshop addons at once and have clients download them.*

- **[Source2ZE/ServerListPlayersFix](https://github.com/Source2ZE/ServerListPlayersFix)**<br>
  ⭐ 68<br>
  ⏱️ updated 1 month ago<br>
  *Populates the user information inside the steam api, as a result this fixes the players not showing up in the server browser.*

- **[Source2ZE/CS2ServerGUI](https://github.com/Source2ZE/CS2ServerGUI)**<br>
  ⭐ 67<br>
  ⏱️ updated 2 weeks ago<br>
  *A plugin that shows entities, net messages, events and etc with a GUI.*

- **[Source2ZE/CleanerCS2](https://github.com/Source2ZE/CleanerCS2)**<br>
  ⭐ 66<br>
  ⏱️ updated 1 month ago<br>
  *A simple plugin that allows you to filter out console prints with regular expressions.*

- **[Source2ZE/MovementUnlocker](https://github.com/Source2ZE/MovementUnlocker)**<br>
  ⭐ 64<br>
  ⏱️ updated 2 weeks ago<br>
  *A plugin that removes the max speed limitation from players on the ground, feels like CS:S. Useful for zombie knockback, several movement gamemodes, or just easier bhop.*

- **[Salvatore-Als/cs2-fake-rcon](https://github.com/Salvatore-Als/cs2-fake-rcon)**<br>
  ⭐ 64<br>
  ⏱️ updated 1 week ago<br>
  *Fakercon adds the fake_rcon_password and fake_rcon commands because Valve has not integrated the original command into the game (or it is broken).*

- **[Source2ZE/StripperCS2](https://github.com/Source2ZE/StripperCS2)**<br>
  ⭐ 54<br>
  ⏱️ updated 2 weeks ago<br>
  *A plugin that allows server operators to manage map lump data similarly to how Stripper:Source worked.*

- **[Cruze03/FakeRanks-RevealAll](https://github.com/Cruze03/FakeRanks-RevealAll)**<br>
  ⭐ 54<br>
  ⏱️ updated 2 weeks ago<br>
  *A metamod plugin that reveals ranks of all players in server for player who presses tab.*

- **[Interesting-exe/CS2Fixes-RampbugFix](https://github.com/Interesting-exe/CS2Fixes-RampbugFix)**<br>
  ⭐ 36<br>
  ⏱️ updated 5 months ago<br>
  *Minimizes rampbugs. This plugin isn't perfect and rampbugs will continue to occur until Valve decides to finally fix them.*

- **[Source2ZE/AcceleratorCS2](https://github.com/Source2ZE/AcceleratorCS2)**<br>
  ⭐ 32<br>
  ⏱️ updated 1 month ago<br>
  *A plugin that generate a crash dump when there's a crash.*

- **[XBribo/CS2-Bot-Hider](https://github.com/XBribo/CS2-Bot-Hider)**<br>
  ⭐ 30<br>
  ⏱️ updated 23 hours ago<br>
  *CS2-Bot-Hider is a plugins that can disguise CS2 bots as real players.*

- **[GAMMACASE/Source2SchemaDumper](https://github.com/GAMMACASE/Source2SchemaDumper)**<br>
  ⭐ 28<br>
  ⏱️ updated 5 days ago<br>
  *A plugin that can dump the schemas and generate a header file.*

- **[XBribo/CS2-Bot-Controller](https://github.com/XBribo/CS2-Bot-Controller)**<br>
  ⭐ 25<br>
  ⏱️ updated 1 day ago<br>
  *CS2-Bot-Controller(CS2-Bot-Mimic2) is a plugin that takes control of a bot's behaviour.*

- **[Cruze03/GameBanFix](https://github.com/Cruze03/GameBanFix)**<br>
  ⭐ 22<br>
  ⏱️ updated 2 weeks ago<br>
  *Fixes issue where if a player with game ban joins, other players even without a ban are then unable to join.*

- **[samyycX/Audio](https://github.com/samyycX/Audio)**<br>
  ⭐ 17<br>
  ⏱️ updated 4 days ago<br>
  *A demo and a metamod lib to provide similar functions to the previous SM-Ext-Audio extension in csgo, that is, sending custom audio streams such as a song through a bot's voice chat.*


## CounterStrikeSharp Plugins

- **[shobhit-pathak/MatchZy](https://github.com/shobhit-pathak/MatchZy)**<br>
  ⭐ 505<br>
  ⏱️ updated 1 week ago<br>
  *MatchZy is a plugin for CS2 (Counter Strike 2) for running and managing practice/pugs/scrims/matches with easy configuration!*

- **[Nereziel/cs2-WeaponPaints](https://github.com/Nereziel/cs2-WeaponPaints)**<br>
  ⭐ 415<br>
  ⏱️ updated 1 week ago<br>
  *A plugin to change weapon paints, gloves, agents and etc.*

- **[B3none/cs2-retakes](https://github.com/B3none/cs2-retakes)**<br>
  ⭐ 319<br>
  ⏱️ updated 2 hours ago<br>
  *CS2 implementation of retakes written in C# for CounterStrikeSharp. Based on the version for CS:GO by Splewis.*

- **[daffyyyy/CS2-SimpleAdmin](https://github.com/daffyyyy/CS2-SimpleAdmin)**<br>
  ⭐ 189<br>
  ⏱️ updated 1 week ago<br>
  *Manage your Counter-Strike 2 server with simple commands!*

- **[counterstrikesharp-panel/css-bans](https://github.com/counterstrikesharp-panel/css-bans)**<br>
  ⭐ 146<br>
  ⏱️ updated 6 days ago<br>
  *CSS-BANS is an admin web panel for Counter-Strike 2, powered by CounterStrikeSharp.*

- **[samyycX/CS2-PlayerModelChanger](https://github.com/samyycX/CS2-PlayerModelChanger)**<br>
  ⭐ 138<br>
  ⏱️ updated 4 days ago<br>
  *A cssharp plugin to change player models.*

- **[NockyCZ/CS2-Deathmatch](https://github.com/NockyCZ/CS2-Deathmatch)**<br>
  ⭐ 133<br>
  ⏱️ updated 4 days ago<br>
  *A plugin to implement deathmatch gamemode.*

- **[NiGHT757/AFKManager](https://github.com/NiGHT757/AFKManager)**<br>
  ⭐ 86<br>
  ⏱️ updated 1 year ago<br>
  *AFK Manager plugin for CS2 based on player-checker by sazonische from CS:GO.*

- **[partiusfabaa/cs2-VIPCore](https://github.com/partiusfabaa/cs2-VIPCore)**<br>
  ⭐ 75<br>
  ⏱️ updated 2 months ago<br>
  *A vip plugin for cs2.*

- **[oqyh/cs2-Game-Manager-GoldKingZ](https://github.com/oqyh/cs2-Game-Manager-GoldKingZ)**<br>
  ⭐ 75<br>
  ⏱️ updated 2 months ago<br>
  *Block/Hide unnecessaries in game.*

- **[Cruze03/FortniteEmotesNDances](https://github.com/Cruze03/FortniteEmotesNDances)**<br>
  ⭐ 74<br>
  ⏱️ updated 2 weeks ago<br>
  *This plugin allows players to use Emotes & Dances just like Fortnite.*

- **[partiusfabaa/cs2-ranks](https://github.com/partiusfabaa/cs2-ranks)**<br>
  ⭐ 68<br>
  ⏱️ updated 1 year ago<br>
  *Each player is assigned a rank based on their accumulated experience points. Ranks range from "None" to the prestigious "The Global Elite."*

- **[B3none/cs2-instadefuse](https://github.com/B3none/cs2-instadefuse)**<br>
  ⭐ 68<br>
  ⏱️ updated 1 month ago<br>
  *A plugin that allows players to instantly defuse the bomb.*

- **[Oz-Lin/cs2-rockthevote](https://github.com/Oz-Lin/cs2-rockthevote)**<br>
  ⭐ 66<br>
  ⏱️ updated 1 year ago<br>
  *General purpose map voting plugin, started as a simple RTV and now has more features.*

- **[daffyyyy/CS2-Tags](https://github.com/daffyyyy/CS2-Tags)**<br>
  ⭐ 61<br>
  ⏱️ updated 1 year ago<br>
  *Adds tags to the server that can be easily edited, tags can be assigned via permission or steamid64.*

- **[Lan2Play/PugSharp](https://github.com/Lan2Play/PugSharp)**<br>
  ⭐ 61<br>
  ⏱️ updated 7 months ago<br>
  *Pugsharp is a PUG System Plugin for CS2 based on the awesome CounterStrikeSharp by roflmuffin.*

- **[CounterStrike2-Plugins-Archive/cs2-tags](https://github.com/CounterStrike2-Plugins-Archive/cs2-tags)**<br>
  ⭐ 51<br>
  ⏱️ updated 1 year ago<br>
  *A tag plugin designed to enhance your CS2 experience with a dynamic tagging system. Customise and manage player tags effortlessly for a more interactive and engaging game environment.*

- **[schwarper/CS2MenuManager](https://github.com/schwarper/CS2MenuManager)**<br>
  ⭐ 48<br>
  ⏱️ updated 2 months ago<br>
  *CS2MenuManager is a modern, extensible and easy to use menu system for Counter-Strike 2 based on the CounterStrikeSharp library.*

- **[KillStr3aK/ResourcePrecacher](https://github.com/KillStr3aK/ResourcePrecacher)**<br>
  ⭐ 45<br>
  ⏱️ updated 1 year ago<br>
  *This plugin can precache custom resources.*

- **[HvH-gg/CS2-Essentials](https://github.com/HvH-gg/CS2-Essentials)**<br>
  ⭐ 38<br>
  ⏱️ updated 8 months ago<br>
  *It includes basic features like reset score and rage quit as well as optional restrictions for weapons, friendly fire, rapid fire and other exploit/crash fixes.*

- **[zwolof/cs2-executes](https://github.com/zwolof/cs2-executes)**<br>
  ⭐ 38<br>
  ⏱️ updated 11 months ago<br>
  *CS2 implementation of executes written in C# for CounterStrikeSharp. Based on the version for CS:GO by Splewis.*

- **[schwarper/CS2TraceRay](https://github.com/schwarper/CS2TraceRay)**<br>
  ⭐ 36<br>
  ⏱️ updated 6 months ago<br>
  *A trace ray library developed for use in Counter Strike 2, in conjunction with the CounterStrikeSharp API. This enables the use of trace ray with TraceMask, Contents and skip enums.*

- **[darkerz7/EntWatchSharp](https://github.com/darkerz7/EntWatchSharp)**<br>
  ⭐ 32<br>
  ⏱️ updated 2 weeks ago<br>
  *Notify players about entity interactions.*

- **[oqyh/cs2-Chat-Logger-GoldKingZ](https://github.com/oqyh/cs2-Chat-Logger-GoldKingZ)**<br>
  ⭐ 32<br>
  ⏱️ updated 1 year ago<br>
  *Log chat to local/discord webhook/mysql/web server.*

- **[oqyh/cs2-Connect-Disconnect-Sound-GoldKingZ](https://github.com/oqyh/cs2-Connect-Disconnect-Sound-GoldKingZ)**<br>
  ⭐ 32<br>
  ⏱️ updated 9 months ago<br>
  *Emit a sound when a player connects or disconnects.*

- **[ssypchenko/cs2-gungame](https://github.com/ssypchenko/cs2-gungame)**<br>
  ⭐ 30<br>
  ⏱️ updated 2 weeks ago<br>
  *GunGame is a gameplay plugin inspired by the SourceMode GunGame plugin.*

- **[R0mz1k/css-C4-Timer](https://github.com/R0mz1k/css-C4-Timer)**<br>
  ⭐ 30<br>
  ⏱️ updated 1 year ago<br>
  *This plugin adds countdown to c4 bomb explosion to your server.*

- **[grrhn/ThirdPerson-WIP](https://github.com/grrhn/ThirdPerson-WIP)**<br>
  ⭐ 24<br>
  ⏱️ updated 1 year ago<br>
  *WIP ThirdPerson plugin for CS2 expect bugs.*

- **[wiruwiru/AutomaticAds-CS2](https://github.com/wiruwiru/AutomaticAds-CS2)**<br>
  ⭐ 23<br>
  ⏱️ updated 2 months ago<br>
  *This plugin allows you to schedule and display announcements in the chat at customizable intervals. Each announcement is accompanied by a brief sound effect to capture players' attention seamlessly.*

- **[Kandru/cs2-update-manager](https://github.com/Kandru/cs2-update-manager)**<br>
  ⭐ 23<br>
  ⏱️ updated 4 months ago<br>
  *The Plugin Update Manager is a plugin for Counter-Strike 2 designed to automatically update all your other plugins.*

- **[Cruze03/Clientprefs](https://github.com/Cruze03/Clientprefs)**<br>
  ⭐ 22<br>
  ⏱️ updated 7 months ago<br>
  *This plugin exposes some natives for developers to save player data to SQLite / MySQL without actually adding sql code to your plugin giving developers easy access to save player cookie to database.*

- **[qstage/CS2-HidePlayers](https://github.com/qstage/CS2-HidePlayers)**<br>
  ⭐ 21<br>
  ⏱️ updated 1 year ago<br>
  *Allows you to hide player models.*

- **[Kandru/cs2-roll-the-dice](https://github.com/Kandru/cs2-roll-the-dice)**<br>
  ⭐ 21<br>
  ⏱️ updated 18 hours ago<br>
  *This plugin lets your players roll the dice each round (at any time during an round) to get either a positive or negative effect for the current round.*

- **[samyycX/CS2-SkyboxChanger](https://github.com/samyycX/CS2-SkyboxChanger)**<br>
  ⭐ 20<br>
  ⏱️ updated 4 days ago<br>
  *A plugin allow player to change their own skybox material, color and brightness on every map dynamically and seamle