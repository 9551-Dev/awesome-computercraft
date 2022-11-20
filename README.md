# Awesome ComputerCraft [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="assets/cc-tweaked-logo.png" align="right" width="100">](https://computercraft.cc)

> Useful libraries, programs, literature, and mods for [ComputerCraft](https://computercraft.info) and [its forks](https://computercraft.cc).

**ComputerCraft** is a mod for Minecraft which adds computers which are programmable with the Lua programming language. **ComputerCraft: Tweaked** is a fork of the mod for newer Minecraft versions.

***If you are trying to download ComputerCraft, you are in the wrong place. Go to the [CurseForge page for the Forge](https://www.curseforge.com/minecraft/mc-mods/cc-tweaked) or [Fabric versions](https://www.curseforge.com/minecraft/mc-mods/cc-restitched) instead.***

If you want to contribute, see [CONTRIBUTING.md](./CONTRIBUTING.md).

## Contents
<!-- TOC -->
- [Mods](#mods)
    - [ComputerCraft mods](#computercraft-mods)
    - [Add-on mods](#add-on-mods)
    - [Resource packs](#resource-packs)
- [Lua programs](#lua-programs)
    - [Utility](#utility)
    - [Library](#library)
    - [Fun](#fun)
    - [Operating systems](#operating-systems)
    - [Economy](#economy)
    - [Mod-specific programs](#mod-specific-programs)
- [Non-Lua programs](#non-lua-programs)
    - [Bridging](#bridging)
    - [Emulators](#emulators)
    - [Plugins](#plugins)
    - [Tools](#tools)
    - [Economy](#economy-1)
- [Literature](#literature)
    - [Essays](#essays)
    - [Tutorials](#tutorials)
    - [Charts and tables](#charts-and-tables)
    - [Other lists](#other-lists)
- [Resources](#resources)
<!-- /TOC -->


## Mods
### ComputerCraft mods

- [ComputerCraft: Tweaked](https://computercraft.cc) -  A fork of the original ComputerCraft for modern versions of Minecraft.
- [ComputerCraft: Restitched](https://www.curseforge.com/minecraft/mc-mods/cc-restitched) -  A set of patches for CC:T that allow running it on Fabric. 
- [ComputerCraft](http://computercraft.info) -  A mod which adds computers to allow execution of Lua programs. 

### Add-on mods

- [Advanced Peripherals](https://www.curseforge.com/minecraft/mc-mods/advanced-peripherals) -  A mod which adds various peripherals and APIs for interacting with other mods. 
- [Computronics](https://wiki.vexatos.com/wiki:computronics) -  A mod which adds various peripherals, notably for detecting events in the world and for manipulation of sound. 
- [Plethora](https://plethora.madefor.cc) -  A mod which adds peripherals and allows many blocks to be accessed as such. In addition, it also allows for manipulation of the player as a peripheral. 
- [CC:C Bridge](https://www.curseforge.com/minecraft/mc-mods/cccbridge) -  A mod which adds support for the [Create mod](https://ftb.fandom.com/wiki/Create) to ComputerCraft. 

### Resource packs

- [ComputerCreate](https://modrinth.com/resourcepack/computercreate) -  A resource pack which adds texture packs in the style of the [Create](https://ftb.fandom.com/wiki/Create) mod.

## Lua programs
### Utility

- [ComputerCraft Advanced Shell (cash)](https://cash.madefor.cc) -  A Bourne-compatible shell for ComputerCraft. 
- [Consult](https://consult.madefor.cc) -  A text editor emphasizing ease of use and compatibility with many systems. 
    - [Consult: Recrafted](https://github.com/manaphoenix/CONSULT_RECRAFTED) -  A fork of Consult for Recrafted systems.
- [gist](https://pastebin.com/zSLPYpqs) -  A GitHub Gist download/upload program which aims to extend the built-in `pastebin` program, but for Gists. 
- [Howl](https://github.com/SquidDev-CC/Howl) -  A build system for CC and CC:T.
- [LuaIDE](http://www.computercraft.info/forums2/index.php?/topic/12347-) -  A full-fledged IDE for editing Lua files in-game.
- [Mildly Better Shell (MBS)](https://github.com/SquidDev-CC/mbs) -  An improved shell that includes scrollback and improved resolution of completions.
- [ModemShark](https://gist.github.com/MCJack123/56ca71555d9c0f78d4c985f1e9ad28e8) -  Modem packet sniffer with a simple UI.
- [netshell](https://github.com/lyqyd/cc-netshell) -  Access a computer's shell from another computer.
- [rawshell](https://gist.github.com/MCJack123/8c8861e5e3082d2bed18d07641b5b2cc) -  A modern alternative to netshell supporting CraftOS-PC's "raw mode" format, with file transfers, encryption, passwords, WebSockets, and more.
- [unicornpkg](https://unicornpkg.madefor.cc) -  Modern package management that doesn't suck.
- [FSEncrypt](https://gist.github.com/MCJack123/32c56917dc61da336ec0e8ca6aae39f8) -  Transparent filesystem encryption.

### Library

- [Anavrins' ChaCha20](http://www.computercraft.info/forums2/index.php?/topic/25474-) -  Implementation of [ChaCha20](https://en.wikipedia.org/wiki/ChaCha20-Poly1305).
- Anavrins' hashing libraries:
    - [MD5](https://pastebin.com/6PVSRckQ) -  Implementation of [MD5](https://en.wikipedia.org/wiki/MD5).
    - [SHA-1](https://pastebin.com/SfL7vxP3) -  Implementation of [SHA-1](https://en.wikipedia.org/wiki/SHA-1) with [HMAC](https://en.wikipedia.org/wiki/HMAC) support.
    - [SHA-256](http://www.computercraft.info/forums2/index.php?/topic/8169-) -  Implementation of [SHA-256](https://en.wikipedia.org/wiki/SHA-2) with support for [HMAC](https://en.wikipedia.org/wiki/HMAC) and [PBKDF2](https://en.wikipedia.org/wiki/PBKDF2).
- [AUKit](https://mcjack123.github.io/AUKit/) -  The quintessential audio processing and conversion library for ComputerCraft. 
- [Basalt](https://basalt.madefor.cc/) -  A GUI library emphasizing the user experience.
- [Bigfont](https://pastebin.com/3LfWxRWh) -  A library that makes writing something in different font sizes easy.
- [C3D](https://c3d.madefor.cc/) -  An advanced 3D rendering API.
- [CC-Archive](https://github.com/MCJack123/CC-Archive) -  Various libraries for archiving and unarchiving files.
- [dbprotect](https://gist.github.com/MCJack123/4cf6fc941a2d412b4195caafb9636363) -  A protection wrapper over the `debug` API, allowing restricting access to upvalues in protected functions.
- [ecc.lua](https://www.computercraft.info/forums2/index.php?/topic/29803-) -  Implements [elliptic-curve cryptography](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography).
- [ecnet](https://github.com/migeyel/ecnet) -  Secure network communications in ComputerCraft.
- [GuiH](https://guih.madefor.cc) -  A powerful GUI and graphics library.
- [IsometriH](https://github.com/9551-Dev/IsometriH) -  An [isometric rendering](https://en.wikipedia.org/wiki/Isometric_video_game_graphics) engine.
- [Milo](https://github.com/kepler155c/opus-apps/wiki/Milo-(crafting---storage-system)) -  A crafting and inventory management system. Note that this depends on OpusOS and Plethora.
- [RedRun](https://gist.github.com/MCJack123/473475f07b980d57dd2bd818026c97e8) -  A small library for running processes in the background of CraftOS after exiting the program, similar to DOS TSRs.
- [Tamperer](https://github.com/Fatboychummy-CC/Tamperer) -  A library allowing easy creation of settings menus.
- [VeriCode](https://gist.github.com/MCJack123/7752c85918bcf23ada028abd615e8750) -  Provides simple code signing functions for safely transferring code over modems.

### Fun

- [AUKit austream](https://github.com/MCJack123/AUKit/blob/master/austream.lua) -  Based on AUKit, a simple audio player supporting WAV, DFPWM, AIFF, AU, and FLAC.
- [battleship](https://gist.github.com/MCJack123/7082da1d2ac725c33ff77389877ad7f4) -  An implementation of the popular two-player game *[Battleship](https://en.wikipedia.org/wiki/Battleship_(game))*.
- [LuaGB](https://github.com/MCJack123/LuaGB) -  A port of a Game Boy (Color) emulator for ComputerCraft. Works best in CraftOS-PC.
- [lunatic86](https://github.com/MCJack123/lunatic86) -  A port of an 8086 PC emulator for ComputerCraft.
- [Musicify](https://github.com/knijn/musicify) -  A lightweight client for playing music on ComputerCraft: Tweaked.
	- [tracc](https://github.com/MCJack123/tracc/tree/playAudio) -  An XM module tracker/player for ComputerCraft, supporting 8 channel polyphony in-game.
- [YahtCC](https://gist.github.com/MCJack123/4f7f1635998f44630c8440e81213d32e) -  An implementation of the *[Yahtzee](https://en.wikipedia.org/wiki/Yahtzee)* dice game.
- [YouCube](https://github.com/Commandcracker/YouCube) -  Access YouTube and other services in ComputerCraft.
- [YTP2CCP](https://pastebin.com/nxEMWHY3) -  Convert commented YouTube piano notes and play them in CC:T.

### Operating systems

- [LevelOS](http://install.leveloper.cc) -  A modern GUI operating system intended to mimic Windows.
- [Opus](https://github.com/kepler155c/opus) -  An OS which includes a GUI, an app store, and many system-related APIs.
- [Phoenix](https://phoenix.madefor.cc) -  An OS which emphasizes modularity. It implements its own kernel.
    - Phoenix is currently in alpha.
- [Recrafted](https://github.com/ocawesome101/recrafted) -  A rewrite of CraftOS aiming for full feature parity while maintaining "saner API design."
- [UnBIOS](https://gist.github.com/MCJack123/42bc69d3757226c966da752df80437dc) -  A program to "undo" CraftOS, returning the system to the same state it was in before running the BIOS. Useful for OS development.

### Economy

- [msks](https://github.com/MasonGulu/msks) -  A modern, simple shop for the Krist virtual currency.

### Mod-specific programs

> Note: This section contains programs dedicated which are exclusive to a mod and would not make sense in the Utilities section.

- [DraconicControl](https://pastebin.com/UqVHTht5) -  Allows controlling Draconic Evolution's Draconic Reactor from a computer.
- [ReactorControl and TurbineControl](https://pastebin.com/p4zeq7Ma) -  Automatic management of reactors and turbines in Big Reactors.
    - [ReactorControl patched](https://pastebin.com/2ZrbnH5w) -  The above program uses the `parallel` API recursively, which could cause it to break. A patch has been developed to fix this.

## Non-Lua programs

> Note: This section is for programs that are not mods or Lua programs and **directly** relate to the subject of this list.

### Bridging

> Note: This subsection is for programs which allow ComputerCraft things to be accessed out of the game, primarily through the Internet.

- [Cloud Catcher](https://github.com/SquidDev-CC/cloud-catcher) -  A program which enables interaction with computers outside of the game.
- [Ultron Control](https://gitlab.com/Merith-TK/ultron-control) -  A program which exposes a web API for controlling turtles.

### Emulators

- [CCEmuX](https://emux.cc) -  A CC and CC:T emulator which executes the mods directly.
- [Copy Cat](https://github.com/SquidDev-CC/copy-cat) -  A CC:T emulator that runs in a web browser.
- [CraftOS-PC](https://www.craftos-pc.cc) -  A CC:T emulator written in C++ with the intention of speed.

### Plugins

- [CraftOS-PC for VS Code](https://www.craftos-pc.cc/docs/extension) -  Extension for manipulating and running programs via CraftOS-PC in VSCode.
- [`craftos2-plugins`](https://github.com/MCJack123/craftos2-plugins) -  A collection of small plugins for CraftOS-PC, maintained by the creator.
- [VSCode Extensions for ComputerCraft](https://marketplace.visualstudio.com/items?itemName=lemmmy.computercraft-extension-pack) -  Self-explanatory. Contains autocomplete for CC and CC:T functions, as well as a Lua language server.

### Tools

- [cc-tstl-template](https://github.com/MCJack123/cc-tstl-template) -  A template for the TypeScriptToLua compiler that allows writing ComputerCraft programs in TypeScript.
- [sanjuuni](https://github.com/MCJack123/sanjuuni) -  A program to quickly convert image and video files into various formats for playback and streaming in ComputerCraft.

### Economy

- [KristForge](https://github.com/tmpim/kristforge) -  A miner for the Krist virtual currency.
- [Krist Server](https://github.com/tmpim/Krist) -  A virtual currency intended for use with CC and CC:T. 
- [KristWeb2](https://github.com/tmpim/KristWeb2) -  A web wallet for Krist, written in React.

## Literature
### Essays

- [JackMacWindows's essay on ComputerCraft OSes](https://gist.github.com/MCJack123/4b2bca21bdc0cf5c67ce7177326c2154) -  Contains suggestions, discouragement, and encouragement for building a proper operating system.
- [JackMacWindows's essay on sane APIs](https://gist.github.com/MCJack123/39ac0847579b3676cc098aca5860c758) -  Has suggestions for making your APIs easy to use.

### Tutorials
#### Basics
- [Direwolf20's tutorials](https://www.youtube.com/watch?v=wrUHUhfCY5A) -  A series of videos explaining the basics of ComputerCraft programming. 
- [Sethbling's tutorials](https://www.youtube.com/watch?v=DSsx4VSe-Uk) -  See above.
- Lyqyd's *Computer Basics* series ([I](http://www.computercraft.info/forums2/index.php?/topic/15033-computer-basics-i), [II](http://www.computercraft.info/forums2/index.php?/topic/15041-computer-basics-ii/), [III](http://www.computercraft.info/forums2/index.php?/topic/20905-computer-basics-iii/)) -  Though a bit dated, they are excellent for the beginnings of your journey.
- [The FTB Wiki's Getting Started guide for ComputerCraft](https://ftb.fandom.com/wiki/Getting_Started_(ComputerCraft)) -  A useful all-around resource for getting started.

#### Moderate or advanced
- [Bomb Bloke's *Guide to Coroutines*](http://www.computercraft.info/forums2/index.php?/topic/25670-bbs-guide-to-coroutines/) -  Explains why you should not use coroutines, and includes tutorials on using them. 

### Charts and tables

- [JackMacWindows's coroutine flow chart](https://cdn.discordapp.com/attachments/477911902152949771/959769473437560862/Blank_Diagram_1_Page_1.png) -  Demonstrates how coroutines work. Each column represents one coroutine's code flow.
- [KingOfGameYami's event flow chart](https://media.discordapp.net/attachments/477911902152949771/729709228675301380/image.png) -  Demonstrates the flow of events when a program runs.
- [Wojbie's decimal font chart](https://cdn.discordapp.com/attachments/477911902152949771/933498000385400862/1642633650325141456271.png) and [Cake's hex font chart](https://thox.madefor.cc/_images/encodings-cc-chars.png) -  Contains decimal and hex mappings to ComputerCraft font characters.
- [Emma's ComputerCraft compatibility chart](https://docs.google.com/spreadsheets/d/1s4d21cL3QrUyegEzYaVXvqDr1zNorgyZ-fDWeopIC1k/edit?usp=sharing) -  Shows compatibility across emulators and in-game mods.

### Other lists

- [Awesome Lua](https://github.com/LewisJEllis/awesome-lua) - An Awesome list specific to the Lua programming language.
- [Hengestone's list of languages which compile to Lua](https://github.com/hengestone/lua-languages/blob/master/README.md) -  A list of languages which compile to Lua.

## Resources

- [Tweaked.cc documentation](https://tweaked.cc) -  Contains documentation for most methods in CC and CC:T.
- [CC's forums](https://computercraft.info/forums2) -  An extremely valuable resource, filled with tutorials and programs.
- [CC:T's forums](https://forums.computercraft.cc) -  Also extremely valuable, but is newer.
- [Minecraft Computer Mods Discord](https://discord.gg/H2UyJXe) -  A Discord server for getting help with programming in CC and CC:T.
- [Lua's manual](https://www.lua.org/manual/) -  Contains documentation on methods not covered in Tweaked.cc. Sections 5 (Auxillary Library) and 6 (Standard Library) are of particular interest.
- ~~[CC's original wiki](http://www.computercraft.info/wiki/Main_Page) -  Contains some useful legacy information.~~ **Considered deprecated by modern standards.**

## Footnotes

- Note on acronyms: `CC` is ComputerCraft, `CC:T` is ComputerCraft: Tweaked, and `CC:R` is ComputerCraft: Restitched.
