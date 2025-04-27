# **INSTALLING**
## Essential Client (recommended)
This mod is compatible with Essential Client (recommended for up to 8 players). Download the [installer](https://essential.gg/en) and follow the prompts to add a 1.21.5 Essential instance to the default launcher (any other version of Minecraft will not work). You can also download the [Essential container mod](https://cdn.modrinth.com/data/k2ZPuTBm/versions/IYzDAO59/essential_1-3-5-12_fabric_1-21-5.jar) directly from Modrinth and add it to a **Java Edition 1.21.5 Fabric** instance.
## Setting up the world
Navigate to the latest release of TAG and download the zip file titled "TAGvX.X_MAIN". Extract this folder and add it to your saves folder (for default launcher, this will likely be under `C:\Users[your namespace]\AppData\Roaming.minecraft\saves`).

The game may prompt a warning when attempting to join the world due to the incorporation of experimental features in the map because of the included datapack. To proceed, just select "Yes" if its the first time loading the world, or "I know what I'm doing!" if you're rejoining an existing version of the world.

**Once loaded into the world, run the `/reload` command to reload the datapack.**
## Inviting friends to the world
If using Essential Client, you can add other Minecraft accounts as friends in the social menu and invite them to your game through the Invite button in the game menu. This map also supports LAN connections and many other singleplayer world hosting methods such as Ngrok, however this is not a server file, so it will not work as one.
## Starting the game
Configure game settings (described in depth below in Features) using the shulker box in the lobby. The game will commence automatically once all players are standing in one of the three chambers - Runners, Taggers, or Spectators.
# **FEATURES**
## Settings
To configure the variety of settings, one player must run the command `/trigger Host`. This will give the "Host" a trial key that can be used to unlock the shulker and modify the game settings. Additionally, a brief description is available for each of the settings by right-clicking the top signs. These settings include:
- The map (See the full list of maps below)
- The round duration (30s, 60s, 90s, 2mins, 3mins, 5mins, or 10mins)
- The glowing status of runners and taggers (None, Taggers only, Runners only, or All players)
- The gamemode (See the full list of gamemodes below)
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
A tournament mode was added to the map for the Minecraft Tag League (MTL) tournament. To start it, the "Host" can enable/disable tournament mode from the game settings shulker box. To start a match, the other players must distribute themselves into the Runner and Tagger chambers (or spectator chambers as desired). Each Runner will receive 2 points for every 15 seconds survived, and each Tagger receives 10 points for every tag. Round summaries are shown in chat at the end of every match, while aggregate points across rounds are shown on the sidebar. The scores can be reset by the host using the command `/trigger ResetScores`.
## Maps
There are 30 maps to pick from, ranging from EASY to EXTREME difficulty.
### EASY
- **LEVELS** by ParaFraser
- **BACKROOMS** by Redpill
- **VILLAGE** by ParaFraser
- **MAZE** by Joe Speedrun, hpx and Goldam
- **TOWERS** by ParaFraser and GradientGray
- **GREEN HILL ZONE** by Redpill and ParaFraser
- **BED FIGHT** by Japonk86
- **RACE TRACK** by GradientGray and hpx
### MEDIUM
- **GRAVITY** by hpx
- **FORTRESS** by xSzymi__ and Japonk86
- **MELODY** by ParaFraser, KaaziTheCreeper and SammmyG
- **ISLANDS** by Fallen Allen Key
- **BIRTHDAY** by ParaFraser
- **MAFIA** by AutomattPL, Japonk86
- **DESERT** by ParaFraser, GradientGray, Lyxier, Pizu, hpx
- **CARNIVAL** by GradientGray and hpx
- **SHIPWRECK** by Redpill
- **FOUNDRY** by Bizarctic
### HARD
- **BIKINI BOTTOM** by Erikfzf
- **BASTION REMNANT** by GradientGray and Redpill
- **GRAVEYARD** by GradientGray
- **CITY** by GradientGray and Regionruns
- **TRAIN** by Redpill and GradientGray
- **ENCHANTED** by Redpill and ParaFraser
### EXTREME
- **RIDGE** by Redpill and GradientGray
- **COURTYARD** by TotallyToast13
- **LUNAR COLONY** by SimmonsSprite, BfatcatB, TotallyToast13 and Redpill
- **CAT'S CASTLE** by BfatcatB
- **JUNGLE** by Goldam and GradientGray
# TROUBLESHOOTING
Type `/reload` to reload the datapack for troubleshooting, especially on loading into the world. This should completely reset the map and will force end any running match instantly. If the issue persists, ensure you have the correct version of Minecraft installed, then DM me on discord - @parafraser. 

Note: some maps contain "softlock" spots, which are spots that are intentionally impossible to escape.
# CREDITS
- Lead Map and Datapack Developer/Creator: ParaFraser
- Lead Map Maker: GradientGray, Redpill
- Lead Beta Tester: Erikfzf
- Tournament Organiser: Redpill
- Major Contributions to maps: HPX374, RedPill, Japonk86 and Erikfzf
- Minor Contributions to Maps: Bizarctic, Fallen Allen Key, Region, Pizu, HPX374, Lyxier, SweepJT, Goldam, TotallyToast13, AutomattPL, KaaziTheCreeper, SammmyG, xSzymi__, SimmonsSprite, BfatcatB, and Joe Speedrun
- Minor Beta Testers: KaaziTheCreeper, HPX374, Region, Cylo, Fennniq, Frigid, Buzzaboo, Bizarctic, WarioTime, and others.
