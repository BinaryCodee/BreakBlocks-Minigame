As of July 5, 2023 BreakBlocks-Minigame by BinaryCodee becomes open source. If you are a developer, I would appreciate it if you would make pull requests instead of creating hundreds of forks. Let's make updates available for everyone!
[![Discord](https://discord.gg/urxqAjwtyj)

# Description
BreakBlocks is a mini-game in which you have to destroy as many blocks as possible to earn more points, climb the leaderboard and be the best on the server.  
Once you collect more than 100 Points you can buy Skills, Cosmetics or Particles visible around you.
What are you waiting for? Try it now!

# System requirements
Officially supported servers are [spigot](https://www.spigotmc.org/) and [paper](https://papermc.io/) or other forks of them.
Use of **Java 8** or higher is required to run the plugin.

# Optimization
The map retrieval system relies on zipping and decompressing maps, which can become cumbersome for a PC.
For more and faster optimization, it is recommended to use one of the following solutions:
- Plugin [SlimeWorldManager](https://www.spigotmc.org/resources/slimeworldmanager.69974/) (v2.2.1 **only**)
- Plugin [AdvancedWorldManager](https://www.spigotmc.org/resources/advanced-slimeworldmanager.87209/) (v2.8.0 **only**)
- [AdvancedSlimePaper](https://github.com/InfernalSuite/AdvancedSlimePaper) server jar (**1.20 or newer**)

# Main features

###### Arenas | Ways in which the plugin can be run:
- **SHARED**: can be run between other minigames on the same spigot instance. Games will only be accessible via commands.
- **MULTIARENA**: requires an entire server instance to host the minigame. It will protect the lobby world and games can be accessed via commands, NPCs, signs and GUIs.

###### Languages | Player Language System:
- Each player via the /bb lang <language> command.
can select the desired language, each language can be visible via the /bb lang list command.
- Each player selecting a language from the lists by doing /bb lang list
will change all chat messages, language-to-language configuration and more to him.

###### Groups of arenas | Customization:
- You can group arenas by type (Solo, Duo, Trio, Squad).
- Groups can have updates for squads, initial items, and custom settings from the generator.

###### Arena Settings | Customization:
- Option to set the minimum/maximum number of players in a group/map.
- Options to: allow spectators, disable generators for empty teams, disable internal drop management, use holograms in generators.
- You can create the desired number of teams.
- You can enable map breaking as in a SkyWars game.
- You can enable splitting of generators.
- Custom game rules per map.
- Unlimited generators of iron/gold/diamonds/emeralds.
- Option: ability to add a store and an upgrade store so that items generated by generators can be used. (Soon)

###### Map restore system:
- With our map reset system, you can automatically reset a map.
- To improve the plugin even more and make it more optimized in addition to our simple map reset, we have added the various supports for worlds such as SlimeWorldManager.

###### Specials | Feature:
- In case of disconnection or leaving a game (configurable), it is possible to rejoin it via a command (/bb rejoin).
- Players can jump by placing a tnt/fireball under their feet with configurable values.
- Players with tnt/fireball in their inventory have a red particle on their head (configurable) or other particles that can be purchased using the /cosmetics command in Lobby.

###### Events of the season:
- Halloween/Christmas/Carnival/Summer specials, for these special events you will be able to request an updated version on the discord server and based on which season or holiday we are in we will give you that version of the plugin.

# Contributing
Any help is appreciated

# Contact
[![Discord](https://discord.gg/urxqAjwtyj)

# Developed with
[<img src="https://user-images.githubusercontent.com/21148213/121807008-8ffc6700-cc52-11eb-96a7-2f6f260f8fda.png" alt="" width="150">](https://www.jetbrains.com)
