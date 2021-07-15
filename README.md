# SquaredAvenue

SquaredAvenue is an small experiment made up by Jakub Olan, to check what we can archive by building Minecraft server (as application which needs a lot of
resources) on Kubernetes and what problems may come when it comes to scalability. SquaredAvenue is an pretty big adventure mixed with technology modpack which
should probivde few good hours to spend time with.

## Features

-  Stunning new biomes by [Biomes'O'Plenty](https://www.curseforge.com/minecraft/mc-mods/biomes-o-plenty)
-  New [Chisel]()-based blocks and furnitures ([Bibliocraft]()) to make your buildings awesome.
-  New structures and dungeons to discover, powered by [Rougelike Dungeons]() and [Reccurrent Complex]()
-  Interesting underground life with upgraded caves, dungeons and mining mechanics.
-  Unique tool crafting experience with [Thinker's Construct]() and [Tetra]()

## Usage

Complete guide for installing client-side mods with [CurseForge]() and building server based on [Docker]() or if somebody prefers production-like environment
[Kubernetes]() with [Skaffold]().

```
$ git clone https://github.com/ZiQiLN/mystic-alchemists.git
$ cd mystic-alchemists
$ cd docker-compose up -f "docker-compose.lite.yaml"
```

## Recommendations

-  **Minium allocated RAM**: 6GB
-  **Recommended allocated RAM**: 8GB
-  [**Optifine**](OPTIFINE.md): Partial Support for OptiFine HD U F5 (not included)

## Credits

Modpack was build by [@ziqiln](https://github.com/ziqiln) with usage of code published in other repositories (for building Docker-backed Server) like
[itzg/minecraft-server](https://github.com/itzg/docker-minecraft-server).
