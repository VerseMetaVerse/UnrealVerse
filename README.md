# The UNREAL Universe <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/fd300acf-5804-4394-a120-9020886d3a52" width="10%">

Verse, and UEFN and Fortnite and UE5 with a convergence of the tech upcoming in UE6
This started as a collection of all the information and links about Epic's Verse programming language, but since Verse is expected to converge into the general Unreal codebase in 2024 or 2025 the scope of information found here will expand to be more useful to everyone Unreal with the addition of information on Fortnite as well as the traditional Unreal UE5 ecosystem

# Epic Games

- https://github.com/EpicGames/Signup To access our repositories,
  - sign up for an Epic account at UnrealEngine.com https://www.unrealengine.com/ and
  - register your GitHub ID using these instructions. https://www.unrealengine.com/ue4-on-github
  - After that, you can find our repositories here: Unreal Engine https://github.com/EpicGames/UnrealEngine and
  - https://github.com/EpicGamesExt
  - https://epicgamesext.github.io/BlenderTools/
- https://github.com/jaydenmilne/steamsync Tool to automatically add games from the Epic Games Launcher to Steam
- https://github.com/nikop/epic-games-ratings Ratings for all games in Epic Games Store
- https://www.unrealengine.com/en-US/feed
- https://www.unrealengine.com/en-US/uses/switching-to-unreal-engine
- https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-5-3-documentation
- https://portal.productboard.com/epicgames/1-unreal-engine-public-roadmap/tabs/106-unreal-engine-5-4
- Epic Games Ownership - https://en.wikipedia.org/wiki/Epic_Games
  - Tim Sweeney 51.4%  https://en.wikipedia.org/wiki/Tim_Sweeney_(game_developer)
  - Tencent 40%  https://en.wikipedia.org/wiki/Tencent
  - Disney 9% https://en.wikipedia.org/wiki/The_Walt_Disney_Company
  - Sony 5.4%  https://en.wikipedia.org/wiki/Sony
  - Kirkbi (LEGO) 3.2%  https://en.wikipedia.org/wiki/Kirkbi

# Creating with Unreal

- Verse
- Visual Verse
- Blueprints
- C++

# Verse (UEFN, UE6)

"Verse is being designed as a programming language for the metaverse, with upcoming features to enable future scalability to *vast open worlds built by millions of creators for billions of players*. Verse is launching in Fortnite today, and will come to all Unreal Engine users a couple years down the road."
https://www.unrealengine.com/en-US/blog/dive-into-epic-s-announcements-from-gdc-2023

Verse has been designed by Simon Peyton Jones and Tim Sweeney but very few people should start their Verse learning journey by examining the design.

- [Beyond functional programming: a taste of Verse. Simon Peyton Jones & Tim Sweeney Lambda Days 2023](https://www.youtube.com/watch?v=OJv8rFap0Nw)
- [Beyond Functional Programming: The Verse Programming Language (Simon Peyton Jones)](https://www.youtube.com/watch?v=832JF1o7Ck8)
- Simon Peyton Jones - https://simon.peytonjones.org [Verse Calculus ](https://simon.peytonjones.org/assets/pdfs/verse-March23.pdf) https://en.wikipedia.org/wiki/Lambda_calculus
- Verse programming language showcased https://www.youtube.com/watch?v=Xon9r3piIIw&t=251s

# Visual Verse (UE6 ?)

- Verse will function like C++ currently does and a new layer with a concept like Blueprints will be coming
- [Visual Verse](https://twitter.com/UnrealVerseGuru/status/1636691915927171072) from [UnrealVerseGuru](https://github.com/UnrealVerseGuru/VerseProgrammingLanguage)
- This empty repo could be a place holder or just some random thing - https://github.com/EpicVerseStudio

# Blueprints (UE5, UE6)

# C++ (UE5, UE6)
![cpp](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a912860-1d74-4671-a700-ed43ffa84724)

# Other Programming Languages

### Unreal Engine .NET  

- ![68747470733a2f2f692e696d6775722e636f6d2f63365a6e3753452e706e67](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a763647-97bb-43ce-b278-255dae177aaf)
- Unreal Engine .NET 6 integration - UnrealCLR is a plugin which natively integrates .NET host into the Unreal Engine with the Common Language Runtime for direct execution of managed code to build a game/application logic using the full power of C# 10.0, F# 6.0, and .NET facilities with engine API. The project is aimed at stability, performance, and maintainability. https://github.com/nxrighthere/UnrealCLR
- ![dotnet](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/ba02d53e-b257-4d03-927c-5fb4745b2737) UnrealSharp attempts to add a dotnet core integration to some parts of Unreal Engine. It does this by creating what the dotnet documentation calls a "native host" in the context of a subsystem, and exposes functionality by providing function pointers to dotnet https://github.com/lambda-snail/UnrealSharp


# UNREAL STUDIO

## UE6

Since Verse is expected to converge into the general Unreal codebase in 2024 or 2025 the scope of information found here will probably expand to be more useful to everyone

## UE5

Since Verse is expected to converge into the general Unreal codebase in 2024 or 2025 the scope of information found here will probably expand to be more useful to everyone

## UEFN

Unfortunately, the only way to compile and run Verse programs is within the UEFN editing environment. (See below for a list of experimental Verses) Verse will eventually beccome standard in all versions of Unreal in order to provide increased security and massive scale, which is essential to supporting a MetaVerse.

Verse is supposed to be released as OSS at which point we might see a stand alone compiler which would really reduce one barrier to learning the language. You could then also envision from that a Jupyter compatible version that would encourage adhoc and online learning.

Delivering the first version of of Verse as Unreal Editor for Fortnite (UEFN) means that there are 3 sub systems of concern in making a Verse program:

- The Verse Language itself - https://github.com/kbfngg/uefn/blob/main/modules/Verse/Verse.digest.verse
- An interface API to Unreal - https://github.com/kbfngg/uefn/blob/main/modules/UnrealEngine/UnrealEngine.digest.verse
- An interface API to Fornite - https://github.com/kbfngg/uefn/blob/main/modules/Fortnite/Fortnite.digest.verse

Every Verse project generates 3 digest files that correspond to that

- KBFNGG - (see links just above) - https://github.com/kbfngg/uefn
- https://github.com/LemonGamingFN/uefn-verse-digests
- https://github.com/LilWikipedia/UEFNVerseAssistant

UEFN Features You Can Only Build With Verse - https://dev.epicgames.com/community/learning/talks-and-demos/Vln0/fortnite-uefn-features-you-can-only-build-with-verse-unreal-fest-2023

# FAB.COM

The New Asset Store (Included in UEFN, part of UE6?)


- [FAB.COM](https://www.fab.com) eventually to replace Marketplce, currently works in UEFN [https://create.fortnite.com/news/spotlight-fab-content-added-to-uefn-in-august-2023?isWelcome=true&team=personal]
- [Announcing Fab, an Evolution of the Unreal Engine Marketplace](https://forums.unrealengine.com/t/announcing-fab-an-evolution-of-the-unreal-engine-marketplace/795198)
- [Announcing Fab, the Next Phase for Sketchfab](https://sketchfab.com/blogs/community/announcing-fab-the-next-phase-for-sketchfab)
- [ANNOUNCING A NEW CHAPTER FOR QUIXEL](https://quixel.com/blog/2023/3/22/announcing-a-new-chapter-for-quixel)
- [Introducing Fab – A Unified Creator Marketplace from Epic Games](https://magazine.artstation.com/2023/03/introducing-fab/)


# Sample Games

## Verse Samples

### UEFN Fortnite Islands on Github

- <img src="https://github.com/pheobus78/UEFN_ForTemple/raw/main/assets/fortemple.png" width="50%"> For Temple: https://github.com/pheobus78/UEFN_ForTemple and access it at https://www.fortnite.com/creative/island-codes/9444-4916-7452 
- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/ad4f06e6-2b90-43e3-882f-a537e06addc9" width="50%"> Cyber Tag: https://github.com/ViktorNorman/Cyber-Tag and access it at https://www.fortnite.com/creative/island-codes/0045-2606-3270

## Blueprint Samples


## C++ Samples
![cpp](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/4d0b2e9c-aef2-4434-b6d6-e23a3aa92cb7)

- ![AirSimDroneManual](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/8b22d424-e741-4ca6-9ec1-a02a4115e57e)
- Open source simulator for autonomous vehicles built on Unreal Engine / Unity, from Microsoft AI & Research https://github.com/microsoft/AirSim
- Third-person Action Roguelike made in Unreal Engine C++. Project for Unreal Engine C++ Course & Stanford University https://github.com/tomlooman/ActionRoguelike
- https://github.com/KARNB24/Astral-Warfare Welcome to Astral Warfare: Quantum Reckoning, an action-packed game developed on Unreal Engine 5.3.2

# TOOLS

## Verse and UEFN Tools

https://github.com/Meshcapade/mc-uefn Meshcapade support for Unreal Editor for Fortnite (UEFN) This plugin allows you to quickly retarget motions created on the Meshcapade.me platform onto your own characters in Unreal Editor for Fortnite. Bodies created on the Meshcapade platform are created using the SMPL core technology, and are thus referred to as SMPL-bodies.

## Fortnite Tools

- https://github.com/LeleDerGrasshalmi/FortniteEndpointsDocumentation
- https://github.com/MixV2/EpicResearch Research about Epic's non-documented API. All the documentation can be found within the docs folder.
- https://github.com/fnbrjs/fnbr.js A library to interact with Epic Games' Fortnite HTTP and XMPP services
- https://github.com/FortniteCentral/MercuryCommons A common utility package for CUE4Parse and interfacing with Epic Games/Fortnite services.
- 

## UE5 Tools

General Tools and Plugins for Unreal Studio

- https://github.com/JonasReich/OpenUnrealAutomationTools Lightweight scripts for automating UE4 / UE5 processes like builds, automation tests, etc.
- https://github.com/JonasReich/OpenUnrealUtilities Open Unreal Utilities - Open Source Utilties for Unreal Engine
- https://github.com/NotYetGames/DlgSystem Dialogue Plugin System for Unreal Engine
- https://cdn1.epicgames.com/ue/product/Screenshot/OptimizationToolFull-1920x1080-e51ff7b569d5dc9b63e826037dda09c6.png?resize=1&w=1920 https://www.unrealengine.com/marketplace/en-US/product/optimization-debug-tool The Optimization Debug Tool Helps you to do easy optimization for multiple static and skeletal meshes related to LODs and Nanite methods, as well as optimization for textures associated with quality and memory use. On the other hand, the tool can spot and debug almost any aspect of game development, and the additional ability of the tool includes the option to modify quality settings and set them in-game in a few simple clicks.
- https://cdn1.epicgames.com/ue/product/Screenshot/Sunset-1920x1080-9915cf54f5965e863c9291101e9206fd.jpg?resize=1&w=1920 https://www.unrealengine.com/marketplace/en-US/product/ultra-dynamic-sky A flexible dynamic sky system with natural cloud motion, plus customizable sun, moon and stars.

## Blueprint Tools

Tools that help make Blueprints

- https://github.com/nachomonkey/RefreshAllNodes plugin that refreshes and compiles all of your blueprints
- https://github.com/rfsheffer/RyHelpfulHelpers/raw/master/Resources/Icon128.png https://github.com/rfsheffer/RyHelpfulHelpers Extremely helpful helper functions for developing Blueprint and C++ projects in Unreal Engine. https://www.unrealengine.com/marketplace/en-US/product/ryan-s-helpful-helpers
- https://user-images.githubusercontent.com/47295080/147773806-fbaae57b-51e7-400f-a1a4-88a92bd77bd4.png https://github.com/LouisRaverdy/DiscordRPC plugin for making presence, invite, join and spectating with Discord.
- https://github.com/gjverhoeff/sumatras-studios-tools Evolving Blueprint Library plugin with functions I use often within Unreal Engine 5. Small now, but adding when a new function is needed.
- https://github.com/DoubleDeez/MDViewModel Model-View-ViewModel Plugin with automatic data binding to use in UMG Widget, Actor, and Object Blueprints
- https://github.com/DoubleDeez/MDMetaDataEditor plugin to enable editing meta data of Blueprint Properties, Functions, and Function and Event Parameters
- https://github.com/pramberg/NeatFunctions plugin that adds some new metadata tags you can put on UFUNCTIONs to get a better user experience when the functions are used in Blueprint.
- https://github.com/Incanta/unreal-bp-csv-parsing plugin that adds CSV parsing blueprint nodes
- https://github.com/ZackBradshaw/Bluepy Plugin for unreal to generate blueprints using Gen AI
- https://github.com/uextm/UEXTMIntegers Wrappers for integer types to enable Blueprint/UPROPERTY/UFUNCTION support in Unreal Engine.
- https://github.com/HoussineMehnik/UE4-EditorScriptingToolsPlugin Extend and customize some part the Unreal Editor using Blueprints. The plugin comes with some basic tools samples. https://unrealengineresources.com/plugins
- https://github.com/Yorshka-Vermilion/UnrealEngine---Maze-generator-and-solver blueprint for generating mazes of given size, and build in algorithms (A* and wall-follower) to solve them.
- https://github.com/heyomidk/HardReferenceFinder editor plugin for identifying hard references in a blueprint graph.
- https://github.com/jlnordin/LiveBlueprintVariableDebugging plugin that adds support for viewing live Blueprint variable values directly in the Actor details pane when playing or simulating in the editor.
- https://github.com/thejinchao/turbolink plugin enables Google gRPC work with Unreal Engine using C++ and Blueprint


## C++ Tools
![cpp](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/fd0573fc-01f6-42f2-90a8-4ca6b91b368b)

Tools that help make C++



- ![e9906d80-8cc3-11eb-8ae0-3ed530fea978](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/86e09552-30be-4cfc-bf42-f1928b8cc4f8)
- Design-agnostic node system for scripting game’s flow in Unreal Engine https://github.com/MothCocoon/FlowGraph 

# REFERENCE

## Verse Reference

### Books and Reference

A very basic Verse Book [src](https://github.com/glinesbdev/versus) [Read it here](https://verse-book.netlify.app/verse/)

- The book has an NPC Dialog Example: https://verse-book.netlify.app/examples/custom-npc-dialog/


## Articles

- [Getting Started with Verse in UEFN](https://www.chrismccole.com/blog/getting-started-with-uefn-and-verse-unreal-engine-fortnite-creator-20)
- [Publishing your UEFN project to Fortnite - Releasing Our First Fortnite UEFN Island](https://www.chrismccole.com/blog/releasing-our-first-fortnite-uefn-game)
- [Type system of Fortnite's Verse language](https://brianmckenna.org/blog/verse_types)
- [A Deep Dive Into Epic Games' Verse Programming Language](https://80.lv/articles/a-deep-dive-into-epic-games-verse-programming-language/)
- [How Epic Games views the metaverse and the State of Unreal | Tim Sweeney](https://venturebeat.com/games/how-epic-games-views-the-metaverse-and-the-state-of-unreal-tim-sweeney/)
- [Unreal Engine 5.2 Preview + UE for Fortnite + Verse](https://gamefromscratch.com/unreal-engine-5-2-preview-ue-for-fortnite-verse/)
- Bringing Verse Transactional Memory Semantics to C++ Introducing AutoRTFM: a transactional memory system for C++ code in Unreal Engine. Starting in Fortnite version 28.10, some of our servers—large C++ executables based on Unreal Engine—are compiled with a new compiler that gives C++ transactional memory semantics that are compatible with Verse. This is a first step towards exposing even more Unreal Engine functionality to Verse while preserving Verse semantics. The Verse programming language has transactional memory as a first-class feature.  https://www.unrealengine.com/en-US/tech-blog/bringing-verse-transactional-memory-semantics-to-c
- Fortnite is winning the metaverse - Epic’s new partnership with Disney is just one more step in building out its virtual realm. https://www.theverge.com/24065901/fortnite-metaverse-disney-epic-partnership 


## Reddit

- https://www.reddit.com/r/uefn/
- https://www.reddit.com/r/FortniteCreative/
- https://www.reddit.com/r/TheFortniteCreatives/
- https://www.reddit.com/user/UnrealVerseGuru/
- https://www.reddit.com/r/VerseUnreal/




# Verse and UEFN Education

- The [Fortnite Sensei](https://www.youtube.com/@fortnite_sensei) 
  - from the amazing Unreal Sensei - https://www.youtube.com/@unrealsensei
  - https://www.unrealsensei.com/
- Warforge https://www.youtube.com/@WarforgeXP
- Pi Equals Three https://www.youtube.com/@piequalsthree3200
  - https://github.com/PiEqualsThree/UEFN-Tutorials
- Graeme Bull - https://www.youtube.com/playlist?list=PLFwDePNaxc-k37rZBSib8IrT8Ot0rDwbX
  
# Verse Tools

- Epic UEFN - https://store.epicgames.com/en-US/p/fortnite--uefn
- Visual Studio Code - used by UEFN to edit Verse code
    - https://code.visualstudio.com
    - https://en.wikipedia.org/wiki/Visual_Studio_Code
    - Note that UEFN installs a VS Code Extension for Verse automatically
 
Misc NOT tested
- VSCode extension: Visual Reference Explorer & Helper for Verse - https://github.com/cronofear-dev/VerseReferenceExplorer
- https://github.com/Manifest-Git/verse-extension
- vscode extension containing a collection of snippets for the Verse programming language - https://github.com/Ethan-Guest/verse-language-snippets 

## Creator Portal Info

- A discord bot that checks creators islands for new islands and concurent players - https://github.com/eason825/CreatorBot
## Other link repos

## Verse
- Awesom Verse (not updated) https://github.com/spilth/awesome-verse
- UnrealVerseGuru https://github.com/UnrealVerseGuru/VerseProgrammingLanguage
    - https://github.com/UnrealVerseGuru
    - https://www.youtube.com/@UnrealVerseGuru
    - https://unrealverseguru.github.io
    - https://www.reddit.com/user/UnrealVerseGuru/
    - https://www.reddit.com/r/VerseUnreal/
    - https://twitter.com/UnrealVerseGuru
    - 

## UE5

- https://github.com/Coop56/awesome-unreal
- https://github.com/insthync/awesome-unreal
- https://github.com/mikeroyal/Unreal-Engine-Guide AI created mess of mostly useless info




## Epic Docs

### Epic Forums

- [Fortnite Forum Verse](https://forums.unrealengine.com/tags/c/development-discussion/programming-scripting/verse/196/fortnite)
- [Fortnite Forum FAB](https://forums.unrealengine.com/tags/c/development-discussion/fab-alpha/195/fortnite)
- [Unreal Forum Fortnite](https://forums.unrealengine.com/tags/intersection/unreal-engine/fortnite)
- [Verse Codex](https://forums.unrealengine.com/t/verse-codex-naming-conventions-program-structure-code-clarity/838073) [on GitHub](https://github.com/UnrealVerseGuru/VerseProgrammingLanguage/blob/main/UEFN%20Verse/UEFN_VerseCodex.md)
- [Snippets Repository](https://dev.epicgames.com/community/fortnite/snippets)



### Epic Reference

- [Verse API Reference](https://dev.epicgames.com/documentation/en-us/uefn/verse-api)
- [Verse Language Quick Reference](https://dev.epicgames.com/documentation/en-us/uefn/verse-language-quick-reference)
- [Verse Language Reference](https://dev.epicgames.com/documentation/en-us/uefn/verse-language-reference)
    - [Specifiers and Attributes](https://dev.epicgames.com/documentation/en-us/uefn/specifiers-and-attributes-in-verse)
    - [Modules and Paths](https://dev.epicgames.com/documentation/en-us/uefn/modules-and-paths-in-verse)
    - [Composite Types](https://dev.epicgames.com/documentation/en-us/uefn/composite-types-in-verse)
    - [Container Types](https://dev.epicgames.com/documentation/en-us/uefn/container-types-in-verse)
    - [Time Flow and Concurrency](https://dev.epicgames.com/documentation/en-us/uefn/concurrency-in-verse)
    - [Control Flow](https://dev.epicgames.com/documentation/en-us/uefn/control-flow-in-verse)
    - [Failure](https://dev.epicgames.com/documentation/en-us/uefn/failure-in-verse)
    - [Functions](https://dev.epicgames.com/documentation/en-us/uefn/functions-in-verse)
    - [Expressions](https://dev.epicgames.com/documentation/en-us/uefn/expressions-in-verse)
    - [Constructor](https://dev.epicgames.com/documentation/en-us/uefn/constructor-in-verse)


### Epic Specific How To

- [User Interface](https://dev.epicgames.com/documentation/en-us/uefn/getting-to-know-the-user-interface-in-unreal-editor-for-fortnite)
- [Animation and Cinematics](https://dev.epicgames.com/documentation/en-us/uefn/animation-and-cinematics-in-unreal-editor-for-fortnite)
- [Devices](https://dev.epicgames.com/documentation/en-us/uefn/devices-in-unreal-editor-for-fortnite)
- [Environments and Landscapes](https://dev.epicgames.com/documentation/en-us/uefn/environments-and-landscapes-in-unreal-editor-for-fortnite)
- [In-Game User Interfaces](https://dev.epicgames.com/documentation/en-us/uefn/creating-in-game-ui-in-verse)
- [Visual Effects](https://dev.epicgames.com/documentation/en-us/uefn/visual-effects-in-unreal-editor-for-fortnite)
- [Lighting](https://dev.epicgames.com/documentation/en-us/uefn/lighting-in-unreal-editor-for-fortnite)
- [Materials](https://dev.epicgames.com/documentation/en-us/uefn/materials-in-unreal-editor-for-fortnite)
- [Modeling](https://dev.epicgames.com/documentation/en-us/uefn/modeling-in-unreal-editor-for-fortnite)
- [Audio](https://dev.epicgames.com/documentation/en-us/uefn/audio-in-unreal-editor-for-fortnite)
- [Create Your Own Device in Verse](https://dev.epicgames.com/documentation/en-us/uefn/create-your-own-device-in-verse)
- [Learn Game Mechanics](https://dev.epicgames.com/documentation/en-us/uefn/learn-game-mechanics-in-unreal-editor-for-fortnite) 
- [Build a Game](https://dev.epicgames.com/documentation/en-us/uefn/build-a-game-in-unreal-editor-for-fortnite)



### Epic Templates

- [Sample Project and Feature Example Templates](https://dev.epicgames.com/documentation/en-us/uefn/sample-projects-and-templates-in-unreal-editor-for-fortnite)
- [Verse Detonation Template](https://dev.epicgames.com/documentation/en-us/uefn/verse-detonation-template-in-unreal-editor-for-fortnite)
- [Verse Elimination Template](https://dev.epicgames.com/documentation/en-us/uefn/verse-elimination-template-in-unreal-editor-for-fortnite)
- [Verse Parkour Template](https://dev.epicgames.com/documentation/en-us/uefn/verse-parkour-template-in-unreal-editor-for-fortnite)
- [Animation 101 Template](https://dev.epicgames.com/documentation/en-us/uefn/animation-101-template-in-unreal-editor-for-fortnite)
- [Deserted: Domination Template](https://dev.epicgames.com/documentation/en-us/uefn/deserted-domination-template-in-unreal-editor-for-fortnite)

### Epic Intro



- [What's New in Unreal Editor for Fortnite](https://dev.epicgames.com/documentation/en-us/uefn/whats-new-in-unreal-editor-for-fortnite)
- [Learn Programming with Verse](https://dev.epicgames.com/documentation/en-us/uefn/learn-programming-with-verse-in-unreal-editor-for-fortnite)
- [Collaborating in Unreal Editor for Fortnite](https://dev.epicgames.com/documentation/en-us/uefn/collaborating-in-unreal-editor-for-fortnite)
- [Unreal Revision Control](https://dev.epicgames.com/documentation/en-us/uefn/unreal-revision-control-in-unreal-editor-for-fortnite)
- [Creating Teams in Creator Portal](https://dev.epicgames.com/documentation/en-us/uefn/creating-teams-in-creator-portal-in-unreal-editor-for-fortnite)
- [Get Started with UEFN](https://dev.epicgames.com/community/fortnite/getting-started/uefn)
- [Unreal Editor for Fortnite Documentation](https://dev.epicgames.com/documentation/en-us/uefn/unreal-editor-for-fortnite-documentation)
- [Import from the Fab Marketplace](https://dev.epicgames.com/documentation/en-us/uefn/import-from-fab-in-unreal-editor-for-fortnite)
- [Get Started with Verse](https://dev.epicgames.com/community/fortnite/getting-started/verse)

 

## Misc Info

- [Max size of a UEFN Island/Map](https://twitter.com/UnrealVerseGuru/status/1638972673249144858) from [UnrealVerseGuru on Musk Platform](https://twitter.com/UnrealVerseGuru)
- https://www.reddit.com/r/uefn/
- https://www.reddit.com/user/UnrealVerseGuru/
- https://www.reddit.com/r/VerseUnreal/
- https://www.reddit.com/r/FortniteCreative/
- Tracking UEFN versions - https://github.com/Mast3rGamers/UEFN-releases
- https://github.com/Tevtongermany/UEFN-Assets-Gallery/wiki
- Giant information repository (JA) but has useful diagrams and links - https://github.com/ken-okabe/functional-programming-from-scratch-ja

## Verse Experimental User Implementations

- A mini-Verse implementation - https://github.com/gregr/experiments/tree/master/verse
- Verse Interpreter - https://github.com/Benson-sama/Verse-Interpreter
- Experiments with the Verse Calculus in miniKanren - https://github.com/webyrd/wreckto-verseo
- Verse Compiler - https://github.com/Elioby/VerseCompiler
- Verse Interpreter (Python) - https://github.com/Marcel-TO/Verse-Interpreter-in-Python
- Verse Interpreter (Haskel) - https://github.com/michifueby/Verse-Interpreter
- WIP - An abstract machine for the Verse language [Eric Conlon](https://ericconlon.com) - https://github.com/ejconlon/lyric
- Verse Interpreter (C#) - https://github.com/onur1211/verse-interpreter
- "This repo was a first try to create a VS Code language extension for a own version of the Verse language. Unfortunately I wasn't very successful for now, just startet off. And it is currently not planned to finish this attempt." - https://github.com/m1sjo/vsCode-verse-language-extension



## Misc Verse code on Github

- STARS - if you have wandered to this repo wondering why I gave your project a STAR, well first a reward for uploading any Verse Code which is not common at all and second it makes easier for me to identify new projects with Verse...

This list is NOT curated but it might be useful to you since it is surprisingly hard to search for Verse code repos on Github due to name congestion (any topic with a -verse e.g. SpiderVerse) and the lack of a GitHub language type for Verse

- https://github.com/kbfngg/uefn
- Verse Samples - https://github.com/OsirionGG/Verse-Samples
- https://github.com/kbfngg/verse-modules
- https://github.com/Petlja/demo_uefn_mini_games
- https://github.com/svarelanic/LightsPuzzle
- UEFN Verse Library - https://github.com/IslandArchitekt/UEFN-Verse-Library
- Advent of Code 2023 in Verse for UEFN - https://github.com/zachlute/AdventOfCode2023
- UEFN Devices - https://github.com/sanxfxteam/uefn-devices
- A repository for UEFN (Unreal Editor for Fortnite) generic devices - https://github.com/garrettpfoy/uefn-generic-devices
- https://github.com/futouyiba/UefnVerseCode
- UEFN - Custom game made in Unreal Engine for Fortnite Creative (only Verse code) - https://github.com/Gguardiola/UnrealEngine-Fortnite-CarZoneFights
- https://github.com/Semoyy/UEFN_Infinite
- https://github.com/Meshcapade/mc-uefn
- https://github.com/appiemaster/TimerUI
- NextbotAI https://github.com/Dyplay/NextbotAI_UFEN
- Verse Devices https://github.com/naz-zal/UEFN-Verse
- https://github.com/liyability/custom-playspace
- https://github.com/verse-commons/verse-commons
- https://github.com/JeremyThomsen96/VerseBasicCollision
- https://github.com/Monnapse/UI-Extension-for-UEFN
- https://github.com/JonyWhalee/instantRespawn
- https://github.com/Tsaryii/Verse-Snippets
- https://github.com/appiemaster/Bingo
- https://github.com/appiemaster/Choose-Your-Fortnite-Banner
- https://github.com/Wesleystone88/Verse_Devices
- https://github.com/vcu-ssg/ssg-gamedev-uefn-verse
- https://github.com/PiEqualsThree/Custom-UI
- https://github.com/PiEqualsThree/UEFN-Tutorials
- https://github.com/PiEqualsThree/Verse-Scripts
- https://github.com/Binpuki/verse_tools
- https://github.com/Mostafa-Elbadry/Verse-Language
- https://github.com/The3v0luti0n/CreativeVerseExamples
- https://github.com/nhapq/uefn_verse_examples
- https://github.com/BushyCreate/PaperFN
- https://github.com/AloofBuddha/learn-verse
- https://github.com/mikeyaworski/UEFN-Verse-Devices
- https://github.com/bk-kurt/UE-fortnite-device-timer-via-verse
- https://github.com/nazmi1414/UEFN-VerseLanguage-portfolio
- https://github.com/colory-games/LetsLearnUEFN-VerseForBeginners-Samples
- https://github.com/nhapq/uefn_verse_examples
- https://github.com/eiei114/uefn_mvp_sample
- https://github.com/MadsMGrin/Verse
- https://github.com/GholemHub/UEFN_Verse_Examples
- https://github.com/ppmasa8/UEFN_Verse_practice
- https://github.com/CristovaoVictorOLM/UEFN-MAP-PICTURES-AND-VERSE-CODE
- https://github.com/imaginarycomponent/RedVsBlueSample
- https://github.com/jack-whatley/uefn-weather-code
- https://github.com/Klenky/Verse-UEFN-Practice
- https://github.com/benmac0/UEFN
- https://github.com/iwaken71/IwakenVerseToolkit
- https://github.com/Halforctimelord/UEFN-Verse-CreatureSpawner
- https://github.com/JuNijen/CK_UEFN
- https://github.com/RedAvengerYT/VerseScriptsUEFN
- https://github.com/AitorWesterhof/PublicUEFNScripts
- https://github.com/mattyatea/uefn
- https://github.com/ZenixYT/UEFN-scripts
- https://github.com/colory-games/Unreal-VerseBeginnerEdition-Samples
    - Docs: https://colory-games.net/site/uefn_verse_about/  (Japan)
- https://github.com/acid-nine/uefn_verse_scripts
- https://github.com/eason825/VerseProjects
- https://github.com/IslandArchitekt/UEFN-Verse-Library
- https://github.com/BonesintCreation/Verse-Snippets
- https://github.com/KitchenGun/UEFN_VerseStudy
- https://github.com/CoffeeJavaBeans/CodeForUEFNprojects
- https://github.com/Pearl-UEFN/UEFN-Codes
- https://github.com/tsuruken0802/SampleUEFN
- https://github.com/olopsman/uefn-verse-sample
- https://github.com/CoffeeJavaBeans/fortniteProject
- https://github.com/imaginarycomponent/StartMenuSample
- (Alert: GPL) https://github.com/Androoideka/uefn-verse-lab
- https://github.com/marcosguijr/uefn
- https://github.com/arjff/UEFN_DEMO_1
- Verse cannot read files/databases, so we're forced to use an external script to create a .Verse file - https://github.com/Keiron-Beadle/LabyrinthData
- GPL license makes this rather useless: "A collection of usage examples for verse within unreal engine for fortnite" - https://github.com/wassti/Verse_Boilerplate
- https://github.com/felislsd/UEFN_TestProject
- "This is the first ever open sourced GitHub repo of Verse in the world!" - https://github.com/Cubed/uefn-verse-projects

# Unreal Marketplace Items That Might Be Worth A Look

These generally cost various amounts but can be used in any amount for any purpose as long as they are used with the Unreal Engine

- TO-BE-TESTED: EXTILE PLUS Non-repetitive tiling master materials Removes tiling repetition on any texture and create complex effects directly in material. (Extile was recently featured in the 2022 Venice Film Festival)  https://www.unrealengine.com/marketplace/en-US/product/extile-plus-non-repetitive-tiling-material YT: https://www.youtube.com/watch?v=6rOaPmDWCd0
- TO-BE-TESTED: EasyFog from the same maker as EasyMapper (https://www.unrealengine.com/marketplace/en-US/product/easymapper) - https://www.unrealengine.com/marketplace/en-US/product/easyfog YT https://www.youtube.com/watch?v=CyRksVjviwg
- TO-BE-TESTED: ProInstance Tools Plugin - same maker as "Blockout Tools" for procedural placement https://www.unrealengine.com/marketplace/en-US/product/proinstance-tools-plugin docs - https://dmkarpukhin.itch.io/proinstance-tools-plugin YT: https://www.youtube.com/watch?v=YYhLWI5Nl4E and https://www.youtube.com/watch?v=-teNQEs_aZE
- TO-BE-TESTED: Blockout Tools Plugin  - https://www.unrealengine.com/marketplace/en-US/product/blockout-tools-plugin YT: https://www.youtube.com/watch?v=rXjbH-JmLKU
- NANITE: VERTEX: TO-BE-TESTED: EasyMapper - some sort of modern material manager with Nanite and Vertex Blending - https://www.unrealengine.com/marketplace/en-US/product/easymapper docs on YT - https://youtu.be/UWrCA-t0v3U
- PCG: TO-BE-TESTED: Massive World - Procedural Generation with PCG - some sort of PCG Landscape generator https://www.unrealengine.com/marketplace/en-US/product/massive-world-procedural-generation-with-pcg - DOCS: https://qwertystudio.gitbook.io/massive-world YT: https://www.youtube.com/watch?v=YrHXOdrbGks
- PCG: TO-BE-TESTED: PCG Biome: River Generator - Some sort of water area generator  using PCG system - https://www.unrealengine.com/marketplace/en-US/product/pcg-river-biome-generator-interactive-foliage-tree-water - Docs - https://defect.gitbook.io/defect-marketplace - YT: https://www.youtube.com/watch?v=6lWTHgW66MY
- TO-BE-TESTED: Retro Sci-Fi Guy's make a place you would actually enjoy exploring! https://www.unrealengine.com/marketplace/en-US/profile/Olivier+Garrigue?count=20&sortBy=effectiveDate&sortDir=DESC&start=0 - Example: - SciFi 'Populate' Pack - https://www.unrealengine.com/marketplace/en-US/product/scifi-populate-pack YT: https://www.youtube.com/watch?v=pJdHAWJUjgQ
- TO-BE-TESTED: Basic Splined Mesh Blueprint - FREE general purpose spline code in Blueprint https://www.youtube.com/watch?v=hFZljPUWW8Q Can be purchased here: https://www.unrealengine.com/marketplace/en-US/product/basic-splined-mesh-blueprint?sessionInvalidated=true or downloaded for free (Source: Unreal Showcase) 














- []()
- []()
- []()



