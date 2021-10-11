# Parkers Pterodactyl eggs repo

I am working on adding a large collection of public eggs for the Pterodactyl community.

With that I am also accepting PR's for new services and also updates to the current ones.

If you are submitting PR's try and keep names and titles the same.

## How to import an egg

If you are reading this it looks like you are looking to add an egg to your server.

1. Download any of the json files located in the folders below.
   1. It's easiest to right click the `raw` button and save as.
2. In your panel go to the `Nests` section in the admin part of the panel
3. Click the green `Import Egg` button
4. Browse to the json file you saved earlier
5. Select what nest you want to put the egg in.
   1. If you want a new nest you need to create it before importing the egg.

# You must restart your daemon after importing an egg if you are using 0.7. This is not required on 1.X.


## Please read the CONTRIBUTING.md before submitting PRs

## [Bots](/bots)

[Discord](/bots/discord)
* [ATL Bot](/bots/discord/atlbot) Node JS
* [Bastion](/bots/discord/bastion) Node JS
* [CorpBot](/bots/discord/corpbot) Python
* [discord.js](bots/discord/discord.js) Node JS generic
* [discord.py](bots/discord/discord.py) Python generic
* [discordgo](bots/discord/discordgo) Golang generic
* [fragbot](/bots/discord/fragbot) Golang
* [JMusicBot](/bots/discord/jmusicbot) Java
* [nodemon.js](bots/discord/nodemon.js) Nodemon JS generic
* [parkertron](/bots/discord/parkertron) Golang
* [pixel-bot](/bots/discord/pixelbot) Python
* [Redbot](/bots/discord/redbot) Python
* [SinusBot](/bots/discord/sinusbot)

[Other](/bots/other)
* [Big Brother Bot](/bots/other/bigbrotherbot)

[Twitch](/bots/twitch)
  * [PhantomBot](/bots/twitch/phantombot)
  * [SogeBot](/bots/twitch/sogebot)

[TeamSpeak3](bots/teamspeak3)
  * [JTS3ServerMod](/bots/teamspeak3/jts3servermod)

## [Database](/database)
### In-Memory Databases
[Redis](/database/redis)
* [Redis 5](/database/redis/redis-5)
* [Redis 6](/database/redis/redis-6)

### noSQL
* [mongoDB](/database/nosql/mongodb)

### SQL Databases
* [MariaDB](/database/sql/mariadb)
* [PostgreSQL](/database/sql/postgres)

## [Voice Servers](/voice_servers)
* [Lavalink](/voice_servers/lavalink)
* [TeaSpeak](/voice_servers/teaspeak)
* [TS3-Manager](/voice_servers/ts3_manager)

## [Game Eggs](/game_eggs)
[Among Us](game_eggs/among_us)
* [Impostor Server](game_eggs/among_us/impostor_server)
* [CrewLink Server](game_eggs/among_us/crewlink_server)

[BeamNG.drive](game_eggs/beamng)
* [BeamMP Server](game_eggs/beamng/beammp)
* [KissMP](game_eggs/beamng/kissmp)

[ClassiCube](game_eggs/classicube)
* [MCGalaxy](game_eggs/classicube/mcgalaxy)

[Cryofall](game_eggs/cryofall/cryofall)

[Call of Duty 4X](game_eggs/cod/cod4x)

[ET Legacy](game_eggs/enemy_territory/etlegacy)

[FTL: Tachyon](game_eggs/ftl/tachyon)

[Factorio](game_eggs/factorio)
* [Vanilla](game_eggs/factorio/factorio)
* [ModUpdate](game_eggs/factorio/factorio-modupdate)

[Grand Theft Auto](game_eggs/gta)
* GTA V
  * [FiveM](game_eggs/gta/fivem)
  * [RageMP](game_eggs/gta/ragemp)
  * [alt:V](game_eggs/gta/altv)

* GTA SA
  * [Multi Theft Auto](game_eggs/gta/mtasa)
  * [SA-MP](game_eggs/gta/samp)

* GTA
  * [GTAC](game_eggs/gta/gtac)

[Mindustry](game_eggs/mindustry)
  * [Mindustry](game_eggs/mindustry/mindustry)

[League Sandbox](game_eggs/leaguesandbox)
  * [League Sandbox](game_eggs/leaguesandbox/leaguesandbox)

[Minetest](game_eggs/minetest) (including MTG)
  * [Minetest](game_eggs/minetest/minetest)

[Minecraft](game_eggs/minecraft)
* [Bedrock](game_eggs/minecraft/bedrock) Servers for Bedrock Minecraft (Windows 10, mobile, console)
  * [Bedrock](game_eggs/minecraft/bedrock/bedrock)
  * [gomint](game_eggs/minecraft/bedrock/gomint)
  * [Nukkit](game_eggs/minecraft/bedrock/nukkit)  
  * [PocketMine MP](game_eggs/minecraft/bedrock/pocketmine_mp)  

* [Java](game_eggs/minecraft/java) Servers for Java Minecraft
  * [Airplane](game_eggs/minecraft/java/airplane)
  * [Cuberite](game_eggs/minecraft/java/cuberite)
  * [Fabric](game_eggs/minecraft/java/fabric)
  * [Feather](game_eggs/minecraft/java/feather)  
  * [Feed The Beast](game_eggs/minecraft/java/ftb)  
  * [Forge](game_eggs/minecraft/java/forge)  
  * [Magma](game_eggs/minecraft/java/magma)
  * [Mohist](game_eggs/minecraft/java/mohist)
  * [Paper](game_eggs/minecraft/java/paper)
  * [Purpur](game_eggs/minecraft/java/purpur)
  * [Spigot](game_eggs/minecraft/java/spigot)
  * [SpongeForge](game_eggs/minecraft/java/spongeforge)
  * [SpongeVanilla](game_eggs/minecraft/java/spongevanilla)
  * [Technic](game_eggs/minecraft/java/technic)
  * [Tuinity](game_eggs/minecraft/java/tuinity)
  * [VanillaCord](game_eggs/minecraft/java/vanillacord)

* [Proxies](game_eggs/minecraft/proxy) Minecraft Server Proxies
  * [Java](game_eggs/minecraft/proxy/java)
	  * [FlameCord](game_eggs/minecraft/proxy/java/flamecord)
    * [Travertine](game_eggs/minecraft/proxy/java/travertine)
    * [TyphoonLimbo](game_eggs/minecraft/proxy/java/typhoonlimbo)
    * [Velocity](game_eggs/minecraft/proxy/java/velocity)
    * [Waterfall](game_eggs/minecraft/proxy/java/waterfall)
  * [Bedrock](game_eggs/minecraft/proxy/bedrock)
    * [Waterdog PE](game_eggs/minecraft/proxy/bedrock/waterdog_pe)
  * [Cross Platform](game_eggs/minecraft/proxy/cross_platform)
    * [GeyserMC](game_eggs/minecraft/proxy/cross_platform/geyser)
    * [Waterdog](game_eggs/minecraft/proxy/cross_platform/waterdog)

[OpenArena](game_eggs/openarena)  
  * [openarena](game_eggs/openarena/openarena)

[OpenRA](game_eggs/openra)
* [OpenRA Dune2000](game_eggs/openra/openra_dune2000)
* [OpenRA Red Alert](game_eggs/openra/openra_red_alert)
* [OpenRA Tiberian Dawn](game_eggs/openra/openra_tiberian_dawn)

[Red Dead Redemption](game_eggs/rdr)
* [RedM](game_eggs/rdr/redm)

[SteamCMD Servers](game_eggs/steamcmd_servers) These eggs use SteamCMD to install
* [7 Days to Die](game_eggs/steamcmd_servers/7_days_to_die)
* [ARK: Survival Evolved](game_eggs/steamcmd_servers/ark_survival_evolved)
* [Arma](game_eggs/steamcmd_servers/arma)
  * [Arma 3](game_eggs/steamcmd_servers/arma/arma3)
* [Assetto Corsa](game_eggs/steamcmd_servers/assetto_corsa)
* [Avorion](game_eggs/steamcmd_servers/avorion)
* [Barotrauma](game_eggs/steamcmd_servers/barotrauma)
* [Citadel: Forged with Fire](game_eggs/steamcmd_servers/citadel)
* [Conan Exiles](game_eggs/steamcmd_servers/conan_exiles)
* [Don't Starve Together](game_eggs/steamcmd_servers/dont_starve)
* [ECO](game_eggs/steamcmd_servers/eco)
* [Fistful of Frags](game_eggs/steamcmd_servers/fof)
* [HLDS Server](game_eggs/steamcmd_servers/hlds_server)
* [Holdfast: Nations At War](game_eggs/steamcmd_servers/holdfast)
* [Hurtworld](game_eggs/steamcmd_servers/hurtworld)
* [Insurgency: Sandstorm](game_eggs/steamcmd_servers/insurgency_sandstorm)
* [Killing Floor 2](game_eggs/steamcmd_servers/killing_floor_2)
* [Modiverse](game_eggs/steamcmd_servers/modiverse)
* [Mordhau](game_eggs/steamcmd_servers/mordhau)
* [No More Room in Hell](game_eggs/steamcmd_servers/nmrih)
* [Onset](game_eggs/steamcmd_servers/onset)
* [Pavlov VR](game_eggs/steamcmd_servers/pavlov_vr)
* [PixARK](game_eggs/steamcmd_servers/pixark)
* [Post Scriptum](game_eggs/steamcmd_servers/post_scriptum)
* [Project Zomboid](game_eggs/steamcmd_servers/project_zomboid)
* [Quake Live](game_eggs/steamcmd_servers/quake_live)
* [Rising World](game_eggs/steamcmd_servers/rising_world)
* [Risk Of Rain 2](game_eggs/steamcmd_servers/risk_of_rain_2)
* [Rust](game_eggs/steamcmd_servers/rust)
  * [Autowipe](game_eggs/steamcmd_servers/rust/rust_autowipe)
  * [Staging](game_eggs/steamcmd_servers/rust/rust_staging)
* [SCP: Secret Laboratory](game_eggs/steamcmd_servers/scpsl)
  * [dedicated](game_eggs/steamcmd_servers/scpsl/dedicated)
  * [multiadmin](game_eggs/steamcmd_servers/scpsl/multiadmin)
* [Soldat](game_eggs/steamcmd_servers/soldat)
* [Space Engineers](game_eggs/steamcmd_servers/space_engineers)
* [Squad](game_eggs/steamcmd_servers/squad)
* [Starbound](game_eggs/steamcmd_servers/starbound)
* [Stationeers](game_eggs/steamcmd_servers/stationeers)
* [Stormworks: Build and Rescue](game_eggs/steamcmd_servers/stormworks)
* [Subnautica: Nitrox Mod](game_eggs/steamcmd_servers/subnautica_nitrox_mod)
* [Sven Co-op](game_eggs/steamcmd_servers/svencoop)
* [The Forest](game_eggs/steamcmd_servers/the_forest)
* [Team Fortress 2 Classic](game_eggs/steamcmd_servers/team_fortress_2_classic)
* [Unturned](game_eggs/steamcmd_servers/unturned)
* [Valheim](game_eggs/steamcmd_servers/valheim)
  * [Valheim Vanilla](game_eggs/steamcmd_servers/valheim/valheim_vanilla)
  * [Valheim Plus Mod](game_eggs/steamcmd_servers/valheim/valheim_plus)

[Teeworlds](game_eggs/teeworlds)
* [Teeworlds](game_eggs/teeworlds/teeworlds)

[Terraria](game_eggs/terraria)
* [Vanilla](game_eggs/terraria/vanilla)
* [tModLoader](game_eggs/terraria/tmodloader)
* [TShock](game_eggs/terraria/tshock)

[Tycoon Games](game_eggs/tycoon_games)
* [OpenTTD](game_eggs/tycoon_games/openttd)

[Unreal Engine](game_eggs/unreal_engine)
* [Tower Unite](game_eggs/unreal_engine/tower_unite)
* [Tower Unite](game_eggs/steamcmd_servers/tower_unite)

[Veloren](game_eggs/veloren/veloren)

[Vintage Story](game_eggs/vintage_story/vintage_story)

[Wine Generic](game_eggs/wine/generic)

[Xonotic](game_eggs/xonotic/xonotic)

## [Monitoring](/monitoring/)
### Prometheus
* [Prometheus](/monitoring/prometheus)

## [Storage](/storage/)
### S3 Storage
* [minio](/storage/minio)

## [Software](/software/)
### Code Server
* [Code-Server](/software/code-server)
### Gitea
* [Gitea](/software/gitea)
### Grafana
* [Grafana](/software/grafana)
### haste-server
* [haste-server](/software/haste-server)
### RabbitMQ
* [rabbitmq](/software/rabbitmq)
