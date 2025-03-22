# **INSTALLING**
## Essential Client (recommended)
This mod is compatible with Essential Client (recommended for up to 8 players). Download the [installer](https://essential.gg/en) and follow the prompts to add a 1.21.4 Essential instance to the default launcher (any other version of Minecraft will not work). You can also download the [Essential container mod](https://modrinth.com/mod/essential/versions?g=1.21.4) directly from Modrinth and add it to a **Java Edition 1.21.4 Fabric** instance.
## Setting up the world
Navigate to the latest release of TAG and download the zip file titled "TAGvX.X_MAIN". Extract this folder and add it to your saves folder (for default launcher, this will likely be under _C:\Users[your namespace]\AppData\Roaming.minecraft\saves_).
The game may prompt a warning when attempting to join the world due to the incorporation of experimental features in the map because of the included datapack. To proceed, just select "Yes" if its the first time loading the world, or "I know what I'm doing!" if you're rejoining an existing version of the world.
**Once loaded into the world, run the `/reload` command to reload the datapack.**
## Inviting friends to the world
If using Essential Client, you can add other Minecraft accounts as friends in the social menu and invite them to your game through the Invite button in the game menu. This map also supports LAN connections and many other singleplayer world hosting methods such as Ngrok, however this is not a server file, so it will not work as one.
## Starting the game
Configure game settings (described in depth below in Features) using the signs around the lobby. The game will commence automatically once all players are standing in one of the three chambers - Runners, Taggers, or Spectators.
# **FEATURES**
## Settings
The lobby allows players to configure a variety of game settings using the signs along the bottom of the settings area. Additionally, a brief description is available for each of the settings by right-clicking the top signs. These settings include:
- The map (See the full list of maps below)
- The round duration (30s, 60s, 90s, 2mins, 3mins, 5mins, or 10mins)
- The glowing status of runners and taggers (None, Taggers only, Runners only, or All)
- The runners' headstart before taggers are released (0s, 3s, or 10s)
- The gamemode (See the full list of gamemodes below)
- The nametag status (Never on, only showing for the same team, or Always on)
- The lobby theme
## Gamemodes
The gamemode can be changed using the signs in the lobby. The options include:
- **DEFAULT**: no powerups or game modifiers.
- **WIND**: Each runner receives 8 wind charges to use in the game, while Taggers receive 16. This allows players to wind burst to previously inaccessible locations, or fling wind charges at the opposition and disrupt their movement.
- **SHRUNKEN**: All players are reduced to 0.7x their original size. While you can't crouch through 1 block holes, this gamemode lets players hide a lot easier between 1 block tall spots, as well as making them harder to hit in a chase.
- **SPEED**: All players receive the Speed 2 for the entire duration of the round. This makes players faster and thus harder to catch.
- **LANDMINE**: All players receive 3 pressure plates that can be dropped on the ground (they will not work floating in water). These "landmines" will stun the opposition if they get too close to it, rendering them blind and slow for 10 seconds, providing Runners the opportunity to escape or Taggers the opportunity to catch up.
- **ROCKETS**: In this gamemode, players will hear a rocket sound effect at the location of their closest opposition every 10s. This makes it very hard for Runners to hide, but just as hard for Taggers to creep up on them.
- **INFESTED**: Infested is a spin-off of the popular gamemode "Infected", in which players that are infected have to then infect other players. In Infested, Runners that are tagged become Taggers, and must try to tag the remaining runners before the time runs out. This gamemode works best with 1 Tagger, and the remaining players as Runners.
- **SARDINES**: Sardines operates as the inverse of Infested, as it works best with only 1 Runner. Taggers that tag the Runner are convert into Runners themselves, and need to hide with the original Runner.
## Tournament mode
A tournament mode was added to the map for the Minecraft Tag League (MTL) tournament. To start it, the host of the world must run the command `/trigger Host`. This will allow them to run the command `/trigger TournamentMode`, which will transform the lobby. Tournament mode settings are fixed, excluding the map, which can only be altered by the host. To start a match, the other players must distribute themselves into the Runner and Tagger chambers (or spectator chambers as desired). Each Runner will receive 2 points for every 15 seconds survived, and each Tagger receives 10 points for every tag. Round summaries are shown in chat at the end of every match, while aggregate points across rounds are shown on the sidebar. The scores can be reset by the host using the command `/trigger ResetScores`.
Note: To exit tournament mode, the host can run the command `/trigger NormalMode` or simply `/reload` (the latter will reset all game settings as well).
## Maps
There are 21 maps to pick from, ranging from EASY to EXTREME difficulty. Some visuals of the maps have been included.
### EASY
- **LEVELS** by ParaFraser: The very first map added to TAG, Levels consists of jump boost pads, levitation strips and slowness spots between 4 stark levels, easy for running around and avoiding the Tagger, but very few places to hide.

![Levels](https://cdn.modrinth.com/data/cached_images/768454aeda6935b365b19adede7790d71a2c2a16_0.webp)

- **VILLAGE** by ParaFraser: A traditional plains village, with underground tunnels and roof access.

![Village](https://cdn.modrinth.com/data/cached_images/7d0b4deb20e8ec94384335c9a59ee9d0d5a2c14c.webp)

- **MAZE** by Joe Speedrun, HPX374 and Maze: A hedge maze with water passages and a giant tower to oversee the map.
- **TOWERS** by ParaFraser and GradientGray: A map filled with random towers, Mario-style teleporting pipes, and mega-jump pads.

![Towers](https://cdn.modrinth.com/data/cached_images/af840bff6223feec1ac9d0912134ac3e7fe9c695_0.webp)

- **RACETRACK** by GradientGray and HPX374: A race course in which the Taggers spawn right behind the Runners, and the latter have to traverse and parkour their way through the track.
- **WORKSITE** by HPX374: A construction site, featuring a towering crane, an excavation pit and building supplies scattered around the map.
### MEDIUM
- **ISLANDS** by Fallen Allen Key: A multi-leveled, floating islands map, with water features, picturesque trees, and symbolic stone structures.
- **BIRTHDAY** by ParaFraser: A cake themed map, with slime blocks, lots of parkour opportunities, and multiple tiers of candles

![Birthday](https://cdn.modrinth.com/data/cached_images/45af85b321e946dba911a44afefb0cce9e5b2e73_0.webp)

- **CARNIVAL** by GradientGray and HPX374: A fairground, including a rollercoaster, market stands, and a giant ferris wheel.
- **DESERT** by ParaFraser, GradientGray, Lyxier, Pizu, HPX374: A desert village-style map with underground passages, a temple and central gazebo to loop around.

![Desert](https://cdn.modrinth.com/data/cached_images/c7bd83b3d427499b135f69821677c8da0cf81bc4_0.webp)

- **FOUNDRY** by Bizarctic: An industrial-style map with metal-working themes, including lava basins, pistons and underground passages.
- **GRAVITY** by HPX374: What this parkour-themed map lacks in hidings spaces, it makes up for with water elevators and slime blocks to outmanoeveur and evade the Taggers.

![Gravity](https://cdn.modrinth.com/data/cached_images/17511f501a9593249da799f5b7116b0b57acfbc6_0.webp)

### HARD
- **SHIPWRECK** by Redpill: A cliffside shipwreck, with a coral reef for hiding and several hidden mountain passages.
- **SPONGEBOB** by Erikfzf: A replica of Bikini Bottom from Spongebob, featuring lily pad and slime block parkour, underground passages and various landmarks from the show.
- **BASTION** by GradientGray and Redpill: A bastion remnant-inspired map, with two sides of convoluted blackstone, a connecting bridge at the top of the map and an open space at the bottom.

![Bastion](https://cdn.modrinth.com/data/cached_images/03a65d73518fdcdb0737a91f370e5d86684687c5_0.webp)

- **GRAVEYARD** by GradientGray: 

![Graveyard](https://cdn.modrinth.com/data/cached_images/6a60888698ff6142cd25126f912b94fce95815f4_0.webp)

- **TRAIN** by Redpill and GradientGray: 
- **CITY** by GradientGray and Regionruns: A city square with skyscrapers and residential apartments, surrounding a central pond that leads into subterranean water passages.

![City](https://cdn.modrinth.com/data/cached_images/4f4c94c02662c679b60f0366deb3c3dbeeeaf3ae_0.webp)

### EXTREME
- **RIDGE** by Redpill and GradientGray: A snowy taiga mountainside that hold ice caves and secret passages.

![Ridge](https://cdn.modrinth.com/data/cached_images/39950a87637b70d5cd7c407a325e2cd385dd2d02_0.webp)

- **COURTYARD** by TotallyToast13: A map filled with secret passages and hiding spots between the library, brewery and storage buildings, and into the underground cave and forge level.
- **JUNGLE** by Goldam and GradientGray: A giant map focussing a maze-like jungle temple, with different rooms and redstone contraptions designed to let you lose the Tagger through the different levels.
# TROUBLESHOOTING
Type `/reload` to reload the datapack for troubleshooting, especially on loading into the world. This should completely reset the map and will force end any running match instantly. If the issue persists, ensure you have the correct version of Minecraft installed, then DM me on discord - @parafraser. Note: some maps contain "softlock" spots, which are spots that are intentionally impossible to escape.
# CREDITS
- Lead Map and Datapack Developer: ParaFraser
- Lead Map Maker: GradientGray
- Lead Beta Testers: ParaFraser, Gradient Gray, Erikfzf
- Lead Tournament Organiser: Redpill
- Major Contributions to maps: HPX374, RedPill, and Erikfzf
- Minor Contributions to Maps: Bizarctic, Fallen Allen Key, Region, Pizu, HPX374, Lyxier, SweepJT, Goldam, TotallyToast13, and Joe Speedrun
- Minor Beta Testers: KaaziTheCreeper, HPX374, Region, Cylo, Fennniq, Frigid, Buzzaboo, Bizarctic, WarioTime, and others.
