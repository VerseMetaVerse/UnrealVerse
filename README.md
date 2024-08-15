

# The UNREAL Universe  <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/fd300acf-5804-4394-a120-9020886d3a52" width="20%">


> [!IMPORTANT]
> Verse, and UEFN and Fortnite and UE5 with a convergence of the tech upcoming in UE6
> This started as a collection of all the information and links about Epic's Verse programming language, but since Verse is expected to converge into the general Unreal codebase in 2024 or 2025 the scope > of information found here will expand to be more useful to everyone in the Unreal Universe with the addition of information on Fortnite as well as the traditional Unreal UE5 ecosystem

General Unreal News - https://www.unrealengine.com/en-US/feed

### This Document

The document is organized by categories of 
- Unreal Programming Languages
    - Low level (C++, Verse)
    - High level (Blueprints, VisualVerse)
- Extra Programming Languages
    - Python (Editor scripting)
    - Python (via Addon)
    - C# and F# (via Addon)
    - Lua (via Addon)
- Important Companions such as Blender

There is also a "Type of Interest" set of categories that I hope to feature with a color code of some sort:
- Background, History and Future Directions
- A Learning path via Document Links
- A Learning path via Video Tutorial Links
- Quick Reference Links
- Lists of Tools and Utilities
- Lists of Plugins and Addons, both OSS/Free and recommended commercial
- Samples, Examples and Full Featured Code
- 3D and 2D Assets, both OSS/Free and recommended commercial
- Pointers to other collections of Game Development info

# Epic Games

- Hopefully more detail can eventually be found at https://github.com/VerseMetaVerse/EpicGames
- https://github.com/EpicGames/Signup To access our repositories,
  - sign up for an Epic account at UnrealEngine.com https://www.unrealengine.com/ and
  - register your GitHub ID using these instructions. https://www.unrealengine.com/ue4-on-github
  - After that, you can find our repositories here: Unreal Engine https://github.com/EpicGames/UnrealEngine and https://github.com/EpicGamesExt
  - Blender addons that improve the game development workflow between Blender and Unreal https://epicgamesext.github.io/BlenderTools/ https://github.com/EpicGamesExt/BlenderTools
  - Official mirror of Blender https://github.com/blender/blender http://www.blender.org/
      - <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/b5694db7-8938-4044-93f8-9f7def7208a8" width="40%">
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
- Other

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

<img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a912860-1d74-4671-a700-ed43ffa84724" width="8%">

# Other Programming Languages

### Unreal Engine .NET  (C#, F#)

- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a763647-97bb-43ce-b278-255dae177aaf" width="30%">
- Unreal Engine .NET 6 integration - UnrealCLR is a plugin which natively integrates .NET host into the Unreal Engine with the Common Language Runtime for direct execution of managed code to build a game/application logic using the full power of C# 10.0, F# 6.0, and .NET facilities with engine API. The project is aimed at stability, performance, and maintainability. https://github.com/nxrighthere/UnrealCLR
- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/ba02d53e-b257-4d03-927c-5fb4745b2737" width="5%"> UnrealSharp attempts to add a dotnet core integration to some parts of Unreal Engine. It does this by creating what the dotnet documentation calls a "native host" in the context of a subsystem, and exposes functionality by providing function pointers to dotnet https://github.com/lambda-snail/UnrealSharp

### Python

- A Recipe Book on ways to use Python in Unreal Engine 5 written by Brian Kortbus https://github.com/bralkor/unreal_python_recipe_book
- Some of my personal scripts i made to use for my own projects, but free of charge to be used for any project https://github.com/mamoniem/UnrealEditorPythonScripts
- GameLink is for faster iterations than ever been possible, and at the same time a huge reduction in the time, effort & most importantly the “Cost” of game development. https://github.com/mamoniem/ugl
- Visual Studio Code extension with features to assist when writing python code for Unreal Engine https://github.com/nils-soderman/vscode-unreal-python
- This project is a collection of internal tools developed in Python for working with Unreal Engine. It includes functionalities for retrieving version information from a Git repository, updating Unreal Engine configuration files, and handling template files. https://github.com/IT-Hock/UEBuildTools  ![logo](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/351fd7ac-9e33-42fe-b81f-43032c4db788)


### Lua

Tencent ![18461506](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/b17a5cae-282c-4844-9564-8abe00d9f067) 
- NOTE: Tencent owns 40% of Epic Games, they appear to have TWO separate Lua plugins:
- lua dev plugin for unreal engine 4 or 5 https://github.com/Tencent/sluaunreal
- A feature-rich, easy-learning and highly optimized Lua scripting plugin for UE. https://github.com/Tencent/UnLua
    - ![UnLua](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/48b7182f-0a82-4e0b-b585-cf0d282285d5)
    - https://github.com/Tencent/UnLua/blob/master/Docs/EN/UnLua_Programming_Guide.md

# UNREAL STUDIO

Minimum and recommended hardware specifications and necessary software for developing with Unreal Engine (also includes specs for a typical system used at Epic) https://dev.epicgames.com/documentation/en-us/unreal-engine/hardware-and-software-specifications-for-unreal-engine

Docs: https://dev.epicgames.com/documentation/en-us/unreal-engine/unreal-engine-5-4-documentation?application_version=5.4
Forum: https://forums.unrealengine.com/categories?tag=unreal-engine

## UE6

Since Verse is expected to converge into the general Unreal codebase in 2024 or 2025 the scope of information found here will probably expand to be more useful to everyone

## UE5

Since Verse is expected to converge into the general Unreal codebase in 2024 or 2025 the scope of information found here will probably expand to be more useful to everyone

## UEFN

UEFN Docs: https://dev.epicgames.com/documentation/en-us/uefn/unreal-editor-for-fortnite-documentation
Fortnite Creative Docs: https://dev.epicgames.com/documentation/en-us/fortnite-creative/fortnite-creative-documentation
Verse Docs: https://dev.epicgames.com/documentation/en-us/uefn/learn-programming-with-verse-in-unreal-editor-for-fortnite
UEFN Forum: https://forums.unrealengine.com/categories?tag=fortnite

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

<img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a912860-1d74-4671-a700-ed43ffa84724" width="8%">

- ![AirSimDroneManual](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/8b22d424-e741-4ca6-9ec1-a02a4115e57e)
- Open source simulator for autonomous vehicles built on Unreal Engine / Unity, from Microsoft AI & Research https://github.com/microsoft/AirSim
- Third-person Action Roguelike made in Unreal Engine C++. Project for Unreal Engine C++ Course & Stanford University https://github.com/tomlooman/ActionRoguelike
- https://github.com/KARNB24/Astral-Warfare Welcome to Astral Warfare: Quantum Reckoning, an action-packed game developed on Unreal Engine 5.3.2


# $${\color{cyan}PCG}$$

- PCGEx is a free (libre) Unreal 5 plugin that expands PCG capabilities. It offers a variety of high-performance nodes; with an edge for building relational graphs (Freeform, Delaunay, Voronoi, MST etc), advanced pathfinding; and much more - https://github.com/Nebukam/PCGExtendedToolkit
 - An example project showcasing PCGExtendedToolkit https://github.com/Nebukam/PCGExExampleProject
 - ProcGenLabs PCG nodes - https://github.com/mikec316/PGL-PCGNodes
- PCGAsset - https://github.com/TimChen1383/PCGAsset
- This repo collects my public PCG tools - https://github.com/ExportGeometry/pcg-extension
- Maze - https://github.com/NextopCode/UE5-MazePCG
- OpenPCG - https://github.com/ubuntunux/OpenPCG
- David's unreal engine example projects - https://github.com/david-pp/UEExampleProjects
- This project is to experiment with UE5 features - https://github.com/gam0022/UE5_Examples
- Accompanying project to the Unreal PCG Tutorial series: https://www.youtube.com/watch?v=BqPhdQOweqU&list=PLA03OHAaHgYpo0enf8p-2oEpja3grLOKZ - https://github.com/freetimecoder/unreal-pcg-examples
- Repository for PCG Tutorial in Unreal 5.4 - https://www.youtube.com/channel/UC8oszEDFBhDmpeXtnPrDP4A - https://github.com/Amathlog/TutorialPCG
  - https://github.com/Amathlog/PCG_CustomNodes
- An A* pathfinding implementation with PCG (Procedural Content Generation) to generate custom splines in unreal engine between two points - https://github.com/spood/PCGPathfinding
- Unreal PCG Templates - https://github.com/DeveloperBastian/PCG_Templates
- Road design tool for UnrealEngine - https://github.com/fullike/RoadBuilder
- A procedural stacking tool, using PCG for Unreal Engine 5 - https://github.com/TheNeuronCollider/TheBoxStacker
- Explore a dynamically generated rainforest world in Unreal Engine with Procedural Content Generation (PCG). Traverse lush, dense foliage, encounter diverse wildlife, and uncover hidden treasures as the rainforest evolves with each new adventure. Experience the wonder of nature in a virtual ecosystem where every journey is unique, courtesy of PCG - https://github.com/AlexCrombieF/PCG
- TerraPrime is an advanced landscape automaterial and PCG toolkit for Unreal Engine 5.4+, designed to enhance terrain realism with seamless integration of Nanite and Lumen. It offers a variety of features including dynamic texture blending, elevation-based material application, and an array of customizable biome - https://github.com/OrchidIsle/TerraPrime
- Landscape Combinator is an Unreal Engine 5.4 plugin for Windows and Linux that lets you create landscapes from real-world data in a few simple steps: https://github.com/LandscapeCombinator/LandscapeCombinator


# $${\color{cyan}ECS}$$

- <img width="25%" src="https://github.com/user-attachments/assets/9a86c076-f105-49fd-a0be-70ffb5011838"> Gaming meets modern C++ - a fast and reliable entity component system (ECS) and much more - https://github.com/skypjack/entt
- <img width="25%" src="https://github.com/user-attachments/assets/f4242305-42f8-4cf3-8024-037704c1bbf5">  fast entity component system (ECS) for C & C++ - https://github.com/SanderMertens/flecs


# $${\color{cyan}SNIPPETS}$$

## UNREAL SNIPPETS

- A bunch of notes and code snippets that I write while figuring out how to use the Unreal Engine - https://github.com/ibbles/LearningUnreal
- vscode-unreal-snippets - https://github.com/pseuplex/vscode-unreal-snippets
- Unreal Engine Code Example & Snippets - https://github.com/david-pp/UESnippets
- A collection of code snippets for Unreal Engine projects - https://github.com/TheJamsh/UnrealSnippets
- UE4 related useful code snippets - https://github.com/sasmaster/UnrealEngineCodeSnippets
- Unreal Snippets - https://github.com/Tonetfal/UnrealSnippets
- Select Snippets of Code for Implementing Rollback - https://github.com/Clarkmonsterman/Unreal-Networking
- Quality of life code snippets for Unreal Engine - https://github.com/mika314/QofL
- list of useful Unreal Engine snippets. For Visual Studio 2022 - https://github.com/TheOnlySocialHermit/UnrealSnippets

## VERSE SNIPPETS

- collection of a ton of Verse scripts for UEFN / Fortnite Creative! https://github.com/MadsMGrin/Verse
- Unreal Engine Fortnite Verse Code Snippets - https://github.com/Bexarclaw/UEFN-Verse-Snippets
- vscode extension containing a collection of snippets for the Verse programming language https://github.com/Ethan-Guest/verse-language-snippets
- Verse snippets for use with UEFN https://github.com/mandeep/VerseMaxxing
- Code snippets in Verse Language https://github.com/phanmer/uefn
- Code in Verse or other languages to solve algorithms https://github.com/CoffeeJavaBeans/CodeForUEFNprojects
- Examples of scripts on Versal for the Unreal Engine Fortnite Editor https://github.com/GholemHub/UEFN_Verse_Examples
- code snippets in Verse, and make learning process easier https://github.com/powolnik/Verse-Reference-Library
> [!WARNING]
> *INSANE LICENSE FOR SNIPPETS*
>  Snippets and examples of Verse code https://github.com/jamessmoore/verse-snippets
>  https://github.com/Tsaryii/Verse-Snippets

# $${\color{cyan}QUATERNIONS}$$

## Quaternions and other Friends

"The quaternions are members of a noncommutative division algebra first invented by William Rowan Hamilton. The idea for quaternions occurred to him while he was walking along the Royal Canal on his way to a meeting of the Irish Academy, and Hamilton was so pleased with his discovery that he scratched the fundamental formula of quaternion algebra,  i^2=j^2=k^2=ijk=-1, into the stone of the Brougham bridge" - https://mathworld.wolfram.com/Quaternion.html


- Vectors & Dot Product • Math for Game Devs [Part 1] https://www.youtube.com/watch?v=MOYiVLEnhrw
- https://github.com/CraftedCart/BlueprintRotationLibrary

## QUARTERNIONS in GPU and Niagara

- Niagara Set Quaternion Array - https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara/NiagaraSetQuaternionArray?application_version=5.4

## QUATERNIONS in Epic Python

- unreal.Quat - https://docs.unrealengine.com/5.0/en-US/PythonAPI/class/Quat.html

## QUARTERNIONS Epic Examples

- Custom Gravity in UE 5.4 - https://dev.epicgames.com/community/learning/tutorials/w6l7/unreal-engine-custom-gravity-in-ue-5-4
- Nearest Neighbor Model 5.4 - https://dev.epicgames.com/community/learning/tutorials/pwaY/unreal-engine-nearest-neighbor-model-5-4

## QUARTERNIONS Epic Reference

- https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Quat?application_version=5.3
- https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math

## QUARTERNIONS in Unreal Marketplace
- Smooth Movement - BP Math Extended by Vector and Quaternion Interpolation https://www.unrealengine.com/marketplace/en-US/product/smooth-movement-bp-math-extended-by-vector-interpolation-quaternion-rotation
- Unified Rotations https://www.unrealengine.com/marketplace/en-US/product/unified-rotations
- Clean Gimball Lock Solution / 6 Degree of Freedom Movement Component https://www.unrealengine.com/marketplace/en-US/product/ezdof-clean-gimball-lock-solution-6-degree-of-freedom-movement-component



# TOOLS

## Verse and UEFN Tools

- Epic UEFN - https://store.epicgames.com/en-US/p/fortnite--uefn
- Visual Studio Code - used by UEFN to edit Verse code
    - https://code.visualstudio.com
    - https://en.wikipedia.org/wiki/Visual_Studio_Code
    - Note that UEFN installs a VS Code Extension for Verse automatically
 
### Misc Verse Tools
- Checking up-time of UEFN services https://github.com/jok-dev/uefn-uptime
- VSCode extension: Visual Reference Explorer & Helper for Verse - https://github.com/cronofear-dev/VerseReferenceExplorer
- https://github.com/Manifest-Git/verse-extension
- vscode extension containing a collection of snippets for the Verse programming language - https://github.com/Ethan-Guest/verse-language-snippets
- Verse Helper extension for VS Code https://github.com/konstantinbelyakov/verse-helper-vscode
- Meshcapade support for Unreal Editor for Fortnite (UEFN) This plugin allows you to quickly retarget motions created on the Meshcapade.me platform onto your own characters in Unreal Editor for Fortnite. Bodies created on the Meshcapade platform are created using the SMPL core technology, and are thus referred to as SMPL-bodies. https://github.com/Meshcapade/mc-uefn 


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

<img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a912860-1d74-4671-a700-ed43ffa84724" width="8%">

### Tools for Unreal based on C++

- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/0e6e7c0c-f0bf-4660-8a48-c6360f67f9c3" width="30%">
- A Voxel Plugin for Unreal Engine https://github.com/Phyronnaz/VoxelPlugin
- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/86e09552-30be-4cfc-bf42-f1928b8cc4f8" width="50%">
- Design-agnostic node system for scripting game’s flow in Unreal Engine https://github.com/MothCocoon/FlowGraph 

### Misc C++ Tools and Libs of interest to Unreal Developers

<img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/2a912860-1d74-4671-a700-ed43ffa84724" width="8%">

- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/e9b3e3cc-3872-466f-bfa5-3fda54895097" width="20%">
- The official Open-Asset-Importer-Library Repository. Loads 40+ 3D-file-formats into one unified and clean data structure. https://github.com/assimp/assimp

# BLENDER ADDONS

- Blender addons that improve the game development workflow between Blender and Unreal https://epicgamesext.github.io/BlenderTools/ https://github.com/EpicGamesExt/BlenderTools
- Official mirror of Blender https://github.com/blender/blender http://www.blender.org/
    - <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/b5694db7-8938-4044-93f8-9f7def7208a8" width="40%">
- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/bcea4a6b-e073-4b36-a847-9c525cdfed47" width="30%">
    - Stable Diffusion built-in to Blender https://github.com/carson-katri/dream-textures



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
  


## Creator Portal Info

- A discord bot that checks creators islands for new islands and concurent players - https://github.com/eason825/CreatorBot



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
- UEFN - Custom game made in Unreal Engine for Fortnite Creative (only Verse code) - https://github.com/Gguardiola/UnrealEngine-Fortnite-CarZoneFights.
- This is a collection of UEFN Verse Language Snippets, I'm setting to the side as a learning experience for the verse language - https://github.com/TylerAustInW/VerseSnippets
- Basic Gun Game System With UI - https://github.com/BonesintCreation/Verse-Snippets
- This is my code written to power my Fortnite mining map. I hope you enjoy - https://github.com/EthanSkltn/Fortnite-Mining-Game
- Common reusable UEFN verse classes - https://github.com/psykoloGG/VerseClasses
- This Script will allow you to automatically respawn the player instead of them having a cooldown to respawn - https://github.com/seandotnet/VerseRespawnScript
- Verse files showcasing my experiments, such as developing custom mechanics - https://github.com/AlbertSteinn/Custom-Codes
- Unreal Engine Fortnite Verse Code Snippets - https://github.com/Bexarclaw/UEFN-Verse-Snippets
- Fortnite programming languague templates - https://github.com/victorgxn/verse_templates
- Random Output Device https://github.com/CCruzFight/UEFN
- custom UEFN FFA map with three game modes (Boxfight, Zonewars, Realistics) https://github.com/AlbertSteinn/Boxfight-Zonewars-Realistics
- custom 1v1 map for Fortnite with unique gameplay mechanics using Verse programming. https://github.com/AlbertSteinn/Steinn-1v1-Map
- custom UEFN map designed to practice piece control and mechanics in Fortnite https://github.com/AlbertSteinn/Mechanics-Training-Map
- custom UEFN map designed for competitive boxfight tournaments in Fortnite. https://github.com/AlbertSteinn/Boxfight-Tournament-Map
- Verse devices https://github.com/DragonHunter1357/verse-devices
- This is a useful tool created for UEFN https://github.com/posita33/PositiveUEFNUtility/tree/develop
- Wayfinder https://github.com/kiffpuppygames/Wayfinder
- Verse script that allows you to use custom weapons (kind of) - https://github.com/ItsKuf/Kuff_CustomWeapons
- Wallhack script made with UEFN scripting language VERSE. Use for Creative 2.0! https://github.com/ItsKuf/kuff_wallhack
- The code I wrote for this open world game mode I created in Fortnite using Epic Games' Verse language. https://github.com/mikeramosco/universe182
- Verse files used in YouTube tutorials https://github.com/JHBOGameDev/YTVerseTutorials 
- UEFN SceneGraph Sample 01 https://github.com/nobanashi/SceneGraphSample01
- custom UEFN button written in Verse - https://github.com/imcouri/verse_custom_button
- Code snippets in Verse Language https://github.com/phanmer/uefn
- I create tutorials for Verse in Unreal Editor for Fortnite on my YouTube channel: https://www.youtube.com/channel/UCsg1W2c0YnHLbQT9S_d4V5A - the code snippets for each video so you can easily copy + paste! Use this code freely in your own games and experiences. Enjoy! https://github.com/nulleqcodes/uefn-tutorials
- This repo is supposed to contain code snippets in Verse, and make learning process easier - https://github.com/powolnik/Verse-Reference-Library
- All infomation and code in this file some files look like code but is strictly code info - https://github.com/Tstrongvode/codesverse
- boss example code just use to modify - https://github.com/Tstrongvode/BossExampleRepo
- lichbossfightmechanics a bunch of resources to train chatgpton - https://github.com/Tstrongvode/GPTlichbossfightmechanics
- just copy and pasting digest info - https://github.com/Tstrongvode/versedigest
- https://github.com/tuurGevers/open-source-game
- https://github.com/tuurGevers/verse_multilang
- https://github.com/tuurGevers/Build_detect
- https://github.com/tuurGevers/uefn_raycasting
- https://github.com/tuurGevers/UEFN_NPC_utils
- https://github.com/tuurGevers/uefn-timer-lib
- https://github.com/tuurGevers/hexagon_tilr_generation_uefn
- https://github.com/tuurGevers/procedural-dungeon
- https://github.com/tuurGevers/conway_verse
- https://github.com/tuurGevers/verse_utils
- A collection of verse snippets I made to use in UEFN https://github.com/mephistia/verse-snippets
- https://github.com/Yuvin15/VerseCode-For-Upcoming-game
- https://github.com/imcouri/verse_custom_button
- Verse code used across my projects https://github.com/babakaros/Verse
- Verse snippets for use with UEFN https://github.com/mandeep/VerseMaxxing
- Explore a growing collection of code files and libraries designed to simplify and enhance your content creation process using Unreal Editor and Verse. This toolkit streamlines repetitive tasks and empowers you to build content faster. We welcome contributions from fellow developers who share our passion for enriching the Fortnite content creation landscape. https://github.com/NeurealUEFN/Verse
- https://github.com/EthanSkltn/Fortnite-1v1-buildfight-map-UEFN-verse.
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
- https://github.com/marcosguijr/uefn
- https://github.com/arjff/UEFN_DEMO_1
- Verse cannot read files/databases, so we're forced to use an external script to create a .Verse file - https://github.com/Keiron-Beadle/LabyrinthData
- This script is a template for creating purchasable items in the game https://github.com/Tsaryii/TycoonStomper
- This one is very niche, it is to stress test your server performance. You just run the 'LatencyManager' function whenever you want to start a test! It'll return the multithreaded score and every single thread score.https://github.com/Tsaryii/StressTestor
- https://github.com/felislsd/UEFN_TestProject
- "This is the first ever open sourced GitHub repo of Verse in the world!" - https://github.com/Cubed/uefn-verse-projects

  
> [!WARNING]
> *ALERT: GPL* The following projects with the GPL license are a poor fit for library or snippet code to be used elsewhere *TO BE AVOIDED*

- A collection of usage examples for verse within unreal engine for fortnite - https://github.com/wassti/Verse_Boilerplate
- Testing ground for the Verse language in Unreal Engine for Fortnite -  https://github.com/Androoideka/uefn-verse-lab
- TycoonKitX is a comprehensive tycoonkit meant to be easily expanded upon! - https://github.com/Tsaryii/ProjectOST
- Modular & Dynamic Verse Tycoon Kit. https://github.com/Tsaryii/TycoonKitX
- A free tycoonkit to use in UEFN https://github.com/Tsaryii/SuperKitX-1.0.1

# Unreal Marketplace Items That Might Be Worth A Look

These generally cost various amounts but can be used in any amount for any purpose as long as they are used with the Unreal Engine

- One Earth to rule them all. A realistic high-fidelity asset with feature rich shaders for orbital scenes and truly cinematic Earth close ups. Easy customization directly from blueprint parameters. - https://www.unrealengine.com/marketplace/en-US/product/incredible-earth-80k
- TO-BE-TESTED: EXTILE PLUS Non-repetitive tiling master materials Removes tiling repetition on any texture and create complex effects directly in material. (Extile was recently featured in the 2022 Venice Film Festival)  https://www.unrealengine.com/marketplace/en-US/product/extile-plus-non-repetitive-tiling-material YT: https://www.youtube.com/watch?v=6rOaPmDWCd0
- TO-BE-TESTED: EasyFog from the same maker as EasyMapper (https://www.unrealengine.com/marketplace/en-US/product/easymapper) - https://www.unrealengine.com/marketplace/en-US/product/easyfog YT https://www.youtube.com/watch?v=CyRksVjviwg
- TO-BE-TESTED: ProInstance Tools Plugin - same maker as "Blockout Tools" for procedural placement https://www.unrealengine.com/marketplace/en-US/product/proinstance-tools-plugin docs - https://dmkarpukhin.itch.io/proinstance-tools-plugin YT: https://www.youtube.com/watch?v=YYhLWI5Nl4E and https://www.youtube.com/watch?v=-teNQEs_aZE
- TO-BE-TESTED: Blockout Tools Plugin  - https://www.unrealengine.com/marketplace/en-US/product/blockout-tools-plugin YT: https://www.youtube.com/watch?v=rXjbH-JmLKU
- NANITE: VERTEX: TO-BE-TESTED: EasyMapper - some sort of modern material manager with Nanite and Vertex Blending - https://www.unrealengine.com/marketplace/en-US/product/easymapper docs on YT - https://youtu.be/UWrCA-t0v3U
- PCG: TO-BE-TESTED: Massive World - Procedural Generation with PCG - some sort of PCG Landscape generator https://www.unrealengine.com/marketplace/en-US/product/massive-world-procedural-generation-with-pcg - DOCS: https://qwertystudio.gitbook.io/massive-world YT: https://www.youtube.com/watch?v=YrHXOdrbGks
- PCG: TO-BE-TESTED: PCG Biome: River Generator - Some sort of water area generator  using PCG system - https://www.unrealengine.com/marketplace/en-US/product/pcg-river-biome-generator-interactive-foliage-tree-water - Docs - https://defect.gitbook.io/defect-marketplace - YT: https://www.youtube.com/watch?v=6lWTHgW66MY
- TO-BE-TESTED: Retro Sci-Fi Guy's make a place you would actually enjoy exploring! https://www.unrealengine.com/marketplace/en-US/profile/Olivier+Garrigue?count=20&sortBy=effectiveDate&sortDir=DESC&start=0 - Example: - SciFi 'Populate' Pack - https://www.unrealengine.com/marketplace/en-US/product/scifi-populate-pack YT: https://www.youtube.com/watch?v=pJdHAWJUjgQ
- TO-BE-TESTED: Basic Splined Mesh Blueprint - FREE general purpose spline code in Blueprint https://www.youtube.com/watch?v=hFZljPUWW8Q Can be purchased here: https://www.unrealengine.com/marketplace/en-US/product/basic-splined-mesh-blueprint?sessionInvalidated=true or downloaded for free (Source: Unreal Showcase) 

# MetaVerse OR ROBLOX

![Screenshot 2024-06-09 141440](https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/e11e5fa2-b9cb-4c0f-bd14-04c6e0dd4fae)
IKEA wants to pay real people to work in its new store inside Roblox game - https://www.cnn.com/2024/06/07/tech/ikea-job-roblox-intl-scli-gbr/index.html




# Other Misc Game Development LINK Repositories

- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/78edfb5e-c234-46de-b286-6fde1dba3712" width="60%">
    - Gamedev https://github.com/FronkonGames/Awesome-Gamedev
- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/3b84e5aa-10f8-454d-b3ae-2ee0c1db23bd" width="50%">
    - https://github.com/ellisonleao/magictools
- <img src="https://github.com/VerseMetaVerse/UnrealVerse/assets/17344588/7bf909f9-0dba-45ba-b8d9-d866aef886f7" width="50%">
    - A curated list of awesome Blender addons, tools, tutorials; and 3D resources for everyone. https://github.com/agmmnn/awesome-blender
- <img src="https://github.com/user-attachments/assets/f2438242-ee8c-40e8-a6cb-dad4f069cae1" width="50%"> Curated List of Multiplayer Game Network Programming Resources https://github.com/ThusSpokeNomad/GameNetworkingResources
-  <img src="https://github.com/user-attachments/assets/ade8d758-3cb3-40fb-ac21-7c3d1c13e1f3" width="20%"> 🎮 🎲 A wonderful list of Game Development resources. - https://github.com/Kavex/GameDev-Resources
- 🎮 A step-by-step guide to implementing SSAO, depth of field, lighting, normal mapping, and more for your 3D game - https://github.com/lettier/3d-game-shaders-for-beginners
- Awesome Learn Gamedev - A curated collection of game development learning resources - https://github.com/notpresident35/awesome-learn-gamedev
- 🎮 A list of popular/awesome video games, add-ons, maps, etc. hosted on GitHub. Any genre. Any platform. Any engine. - https://github.com/leereilly/games


## Other Verse link repos

- Awesom Verse (not updated) https://github.com/spilth/awesome-verse
- UnrealVerseGuru https://github.com/UnrealVerseGuru/VerseProgrammingLanguage
    - https://github.com/UnrealVerseGuru
    - https://www.youtube.com/@UnrealVerseGuru
    - https://unrealverseguru.github.io
    - https://www.reddit.com/user/UnrealVerseGuru/
    - https://www.reddit.com/r/VerseUnreal/
    - https://twitter.com/UnrealVerseGuru

## Other UE5 link repos

- https://github.com/Coop56/awesome-unreal
- https://github.com/insthync/awesome-unreal
- https://github.com/mikeroyal/Unreal-Engine-Guide AI created mess of mostly useless info
- Awesome Unreal Engine 5 - https://github.com/Coop56/awesome-unreal
- A collection of free software and free culture resources for making amazing games - https://github.com/Calinou/awesome-gamedev
- A categorized collection of awesome opensource Unreal Engine 4 and 5 repos - https://github.com/insthync/awesome-unreal
- A curated list of resources for working with Unreal Engine 4. (Awesome Unreal Engine 4) - https://github.com/terrehbyte/awesome-ue4
- A collection of awesome things regarding the Unreal Engine ecosystem. - https://github.com/Riccici/awesome-unreal
- (2 years old) UE4/UE5 Ressources Collection (Plugins, Effects, Doc, Tools, etc...) - https://github.com/aiekick/Awesome_Unreal_Engine_4_-_5
- (2 years old) Personal reference of good resources for Unreal Engine. - https://github.com/Zenahr/awesome-ue-resources
- (3 years old) https://github.com/ssddffvv/Awesome_Unreal_Engine_4
- (4 years old) A curated list of awesome virtual production resources using Unreal Engine - https://github.com/lazpremarathna/awesome-virtual-production
- (3 years old) Modules and General Plugin Development - https://github.com/ssddffvv/UE4-Plugin-Resources
- This Unreal Engine Guide appears to be generated by AI - https://github.com/mikeroyal/Unreal-Engine-Guide


# Other Engines Possibly Interesting

- Stride Game Engine (formerly Xenko) https://github.com/stride3d/stride
- Open 3D Engine (O3DE) is an Apache 2.0-licensed multi-platform 3D engine that enables developers and content creators to build AAA games, cinema-quality 3D worlds, and high-fidelity simulations without any fees or commercial obligations. - https://github.com/o3de/o3de

# Kibbles and Bits

- Unleash your creativity with Pixelorama, a powerful and accessible open-source pixel art multitool. Whether you want to create sprites, tiles, animations, or just express yourself in the language of pixel art, this software will realize your pixel-perfect dreams with a vast toolbox of features. Available on Windows, Linux, macOS and the Web! - https://github.com/Orama-Interactive/Pixelorama
- []()
- []()
- []()

	- Programming Language
		- $${\color{blue}BLUEPRINT}$$
		- $${\color{magenta}VERSE}$$
		- $${\color{yellow}c++}$$
	- Large Tools like Blender - TEAL
	- Learning - LIME
	- Reference - ORANGE
	- Small Tools and Utilities - CYAN
	- Plugins and addons - CYAN
	- Libraries - CYAN
	- Samples/Examples - GREEN
	- 2D and 3D assets - PINK
    - Background Info - OLIVE


> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
>
> 

- $${\color{blue}Blue}$$
- $${\color{brown}Brown}$$
- $${\color{cyan}Cyan}$$
- $${\color{darkgray}DarkGray}$$
- $${\color{gray}Gray}$$
- $${\color{green}Green}$$
- $${\color{lightgray}LightGray}$$
- $${\color{lime}Lime}$$
- $${\color{magenta}Magenta}$$
- $${\color{olive}Olive}$$
- $${\color{orange}Orange}$$
- $${\color{pink}Pink}$$
- $${\color{purple}Purple}$$
- $${\color{red}Red}$$
- $${\color{teal}Teal}$$
- $${\color{violet}Violet}$$
- $${\color{white}White}$$
- $${\color{yellow}Yellow}$$


# $${\color{orange}Orange}$$
# $${\color{yellow}Yellow}$$
# $${\color{lightblue}Light \space Blue}$$
# $${\color{blue}Blue}$$
# $${\color{lightgreen}Light \space Green}$$
# $${\color{green}Green}$$
# $${\color{red}Red}$$


