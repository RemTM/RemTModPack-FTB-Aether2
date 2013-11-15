RemTModPack-FTB
===============

A private custom modpack based on the ever popular Feed The Beast modpack.

Notable differences between the "Feed The Beast: Unleashed" modpack and this one:
- Equivalent Exchange and Tinkers Construct mods have been removed
- Addition of Mo' Creatures!, GregTech, and Weeping Angels
- Compatibility with Aether 2 mod

How to install:
===============

1. Download the .zip of the modpack, which can be found on the right side of the Github website this modpack is available from.
2. Extract the contents of the .zip file to any location of your choice.
3. Launch the MultiMC application, then in the window that pops up, double-click on the RemTModPack-FTB-Aether2 instance.

Server Rules:
=============

1. NO GRIEFING OF ANY KIND (direct or indirect) is allowed on the server which will cause damage to another player's "property". This includes but is not limited to bases, items, owned mobs, etc.
2. While killing another player directly is not permitted, indirect death is permitted as long as it does not break the 1st rule. Indirect death means that your player name must not show up as having killed another player. You will be penalised if this rule is broken.
3. Any dropped items from players due to death indirectly caused by another player must be made available to the killed player whenever possible, otherwise it will be breaking the 1st rule.
4. The rules above can be ignored if 2 or more players agree to "battle it out". The winner is free to take any items a player drops when defeated. The "battle arena" must be agreed upon by all players involved.
5. Aiding of other players in any fashion is allowed.
6. A standard currency/economy system will be made available at a later date. Players are asked to follow the currency system once established to promote fair trade, but will not be enforced.

If any of the first 3 rules are broken with no clear reason as to why it was broken, the player who broke the rule(s) will be punished. The severity of the punishment will be decided by me, the server admin, while taking into account any opinions voiced by any other players involved.

Interested in Aether 2?
=======================

If you are interested in trying out the Aether 2 mod with this modpack, then follow these steps to install the mod to your local copy of the modpack:

1. Go to http://www.minecraftforum.net/topic/1842350-162-alpha-aether-ii-genesis-of-the-void-v1622-new-launcher-better-performance/
2. Download the 1.5.2 client files for Aether 2. There is no need to download anything else.
3. Extract the contents of the aether_1.5.2_1.0.zip to the "~\instances\RemTModPack-FTB-Aether2\minecraft" folder.
4. Enjoy!

This will allow you to enjoy the added features Aether 2 provides, however it is HIGHLY ADVISED that you disable the Aether 2 mod if you wish to play on the server.

Known Bugs/Issues/Imbalances:
===========

These are all known bugs/issues/imbalances as of 14/10/2013 (AEST):

- BUG: TukMC causes items to disappear from IC2 machine inventories
> Fix: TukMC has been defaulted to disabled, but feel free to re-enable it by removing the ".disabled" extension added to the end of it in the mod folder.
> Fix2: With TukMC enabled, you will need to disable "Pointer at Block" option to prevent this bug from occurring in singleplayer worlds. Multiplayer worlds (the server for this modpack for example) will not be affected by this setting, as TukMC is client-side ONLY.

- ISSUE: Aether II restricted to single player ONLY due to horrible graphical glitch
> There is currently no possible fix to rectify this issue when attempting to use Aether II on the server. What's more, just by having Aether II installed client-side only while playing on the server will also cause this issue. So, if you wish to play Aether II with the modpack, please keep in mind that you will need to disable it when playing on the server, unless you are perfectly fine with the insane graphical glitches and invisible enemies.
> On the other hand, if you are playing on a LAN server with Aether II installed, you will likely not encounter this graphical glitch and will then be able to play the modpack to full capacity. Have fun with all your friends! =)

- IMBALANCE: Shingeki no Kyojin mod's 3D manoeuvre gear movement is TOO OP with current recipe
> While this mod will eventually make it to the modpack, I will hold off from doing so for now, as it is way too easy to make, with a movement speed that can and will beat the movement speed of everything else in the modpack at the moment, excluding teleportation. Once I get around to fixing this imbalance, then and only then will the mod be introduced to this modpack. For now, just look forward to it.

- BUG: Graphic issue with GraviTool when changing texture packs (from GraviSuite mod - addon mod for IC2)
> Fix: Can be easily fixed by reloading Minecraft without changing texture packs. The GraviTool graphic will then be restored.

- BUG: Graphic issues with Biomes O' Plenty/Forestry/etc items
> Currently no known fix. These issues may be due to a silent ID conflict in the modpack. Will look into it.

- IMBALANCE: Mine Factory Reloaded (MFR) introduce new "cheaper" machines to other alternative machines/items provided in this modpack
> This has been addressed temporarily with the use of the GregTech recipes for MFR to increase the cost to make these machines. However, it still appears to be "cheaper" due to a lower diamond count requirement. For now, they have been left as is, due to the need to already have some GregTech infrastructure up to be able to construct MFR machines efficiently. Be sure that the recipes will become harder once I've figured out a good way to replace recipes with customised ones.

Changelog:
==========

Note: All dates listed are in the format DD/MM/YYYY according to Australian Eastern Standard Time (AEST)

14/10/2013:
- Updated Minecraft Forge, CodeChickenCore, denLib, Biomes O Plenty, DartCraft Beta, Forge Multipart, IC2 Nuclear Control, Natura, Wireless Redstone Core & Logic, Applied Energistics, Extra Bees, Charge Pads, Extra Utils, Iron Chests, NEI Addons
- Added Mine Factory Reloaded, Translocator, Switches
- Disabled TukMC by default (enable locally by removing ".disabled" extension)
- Removed Death Timer Beta, Modular Powersuits, Modular Powersuits Addon

6/11/2013:
- Added ExtraUtils

27/10/2013:
- Removed GregTech Hunger Nerf
- Added Advanced Machines add-on mod

24/10/2013:
- Added Archimedes' Ships mod
- Added qCraft mod
- Added TukMC mod
- Added Weeping Angels mod
- Removed UgoCraft mod from pending features due to lack of server files
- Updated configs to current working versions

22/10/2013:
- Added ability to view ticks per second in-game (type the '/btps' command in the in-game chat to use)

21/10/2013:
- Added Recipe Remover mod for easier removal of recipes for items
- Removal of Force Wrench recipe (may have caused server issues)
- Nerfed sturdy flight in Dartcraft mod
- Thermal Expansion machine recipes have been made harder
- Thermal Expansion cobblestone generator are disabled (Any form of cobblestone generator is banned on the server)
- Disabled uncrafting feature of the Uncrafting Table
- Disabled ability to import Lua scripts for ComputerCraft from PasteBin (players are asked to write their own Lua code)
- Enabled recycling of cobblestone and mob drops (originally disabled by GregTech)
- Added Damage Indicators mod (enables tracking of entity hit points and damage inflicted)

15/10/2013:
- Enabled option to craft vanilla IC2 machines from GregTech automatic machines
- Re-enabled "Gate Copy" and "IC2 Nuclear Control" mods after resolving ID conflicts

14/10/2013:
- Uploaded modpack to Github repository
- Aether 2 mod has been temporarily removed due to graphic issues with the server
- Gate Copy and IC2 Nuclear Control mods have been disabled due to ID conflicts
