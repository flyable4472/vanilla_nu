# Vanilla Nu
This is a modpack started as a project for making the server running smoother while still compatible with vanilla players, since I will be mainly using the vanilla server as a way to teach my friend how to play the game. 

# Requirement(s)
- [Concurrent Chunk Management Engine (Fabric) by RelativityMC](https://modrinth.com/mod/c2me-fabric) requires Java 22 in order to run, or at least the version I am using requires it. Will look into the issue before version 1.0

# Licenses
It is included in the modpack's LICENSES file, at least for most of the mods, attributions should have been done correctly. However, I am still in the process of combing through the rest of them to get the licensing right. Please forgive my tardiness as I am but a single man with multiple projects and very short attention span. 

# To do
- ~~Text Placeholder API by Patbox, ScalableLux by RelativityMC, Iris Shaders by coderbot, Cloth Config API by shedaniel, and Lithium by CaffeineMC are licensed under LGPL-3.0-only, will need to check what needs to be done about it~~
  - LGPL-3.0-only needs me to attach the license like MIT does, and also requires you to use the same license if you are making a library, which I am not
- ~~Inventory Profiles Next by mirinimi (or blackd?), libIPN by mirinimi (or blackd?) uses AGPL-3.0-or-later, which again, will be on my todo list~~
  - AGPL-3.0-or-later needs me to attach the license like MIT does, and also requires you to use the same license if you are making a derivative work, which ince again, I am not 
- More Culling by fxmorin is licensed under GPL-3.0-only, will need to check what needs to be done about it
- Sodium by CaffeinMC uses PolyForm Shield License 1.0.0, which again, will be on my todo list
- Add zooming to client side mods if possible
- Add the dark menu
- See if there is any way to sync the map mod with server

# Upcoming Release
### v0.4
- Got CC-BY-NC-SA-4.0 and Apache License 2.0 sorted
  - LGPL-3.0-only and AGPL-3.0-or-later are also technically sorted, just need to attach the licenses to the LICENSES file
- Turns out there is a difference between MIT license and tr7zw Protective License, separated the 2 and added the latter into the LICENSES file
- Added the Dark Loading Screen to not kill my eye
- Added Auth Me to keep the session longer while idle

# Changelogs
### v0.3
- Added Server Sleep to replace Multiplayer Sleep from Vanilla Tweak
  - Will need testing since it seems to be just a game rule change, will want to see if we can override that with config
- Added Shulkers Drop Two Shells to replace Double Shulker Shells from Vanilla Tweak
- Added Inventory Profiles Next for inventory sorting since that seems to be a big hurdle for new players
- Added CraftPresence so that I can get discord rich presence setup later down the line

### v0.2
- Added Xaero's Map Server Utils for stopping certain minimap options from working when needed
- Added Uncrafting Recipes to replace the unpacking recipes in Vanilla Tweaks for auto update
- Added client side optimization mods

### v0.1
- Mostly focusing on server only or server and client optimization mods
- AppleSkin mod for better hunger and saturation illustration
- Added Jade for item info
- Xaero's Map and minimap so that new players can find their way around easier
  - Adding [Xaero's Map Server Utils by xxtg666](https://modrinth.com/datapack/xaeros-map-server-utils) on next version
- Loads of data packs from Vanilla Tweak that I have to figure out how to properly integrate into the modpack
  - Idea will be to either find the original page, GitHub, or replace with something from modrinth
- Set Fabric API to version 0.121.0 because Pakku somehow keeps pulling 0.121.1 for Minecraft 1.21.6
  - Hopefully it won't come back and bite me later
- Got most of the licenses into the LICENSES file, with some still needing me to sort out
