# Vanilla Nu
This is a modpack started as a project for making the server running smoother while still compatible with vanilla players, since I will be mainly using the vanilla server as a way to teach my friend how to play the game. 

# Requirement(s)
- [Concurrent Chunk Management Engine (Fabric) by RelativityMC](https://modrinth.com/mod/c2me-fabric) requires Java 22 in order to run, or at least the version I am using requires it. Will look into the issue before version 1.0

# Licenses
It is included in the modpack's LICENSES file, at least for most of the mods, attributions should have been done correctly. However, I am still in the process of combing through the rest of them to get the licensing right. Please forgive my tardiness as I am but a single man with multiple projects and very short attention span. 

# To do
- Jade's creator Snownee licensed their software under CC-BY-NC-SA-4.0, which means this modpack more than likely will need to use the same license down the line, will need to double-check
- Fabric API is licensed under Apache License 2.0, will need to check what needs to be done about it
- Text Placeholder API by Patbox, ScalableLux by RelativityMC, Iris Shaders by coderbot, Cloth Config API by shedaniel, and Lithium by CaffeineMC are licensed under LGPL-3.0-only, will need to check what needs to be done about it
- More Culling by fxmorin is licensed under GPL-3.0-only, will need to check what needs to be done about it
- Sodium by CaffeinMC uses PolyForm Shield License 1.0.0, which again, will be on my todo list
- Add inventory sorting to client side because it seems to be a hassle for new platers
- Add zooming to client side mods if possible

# Changelogs
## v0.3 (Upcoming)
- Added Server Sleep to replace Multiplayer Sleep from Vanilla Tweak (Will need testing since it seems to be just a game rule change, will want to see if we can override that with config)
- Added Shulkers Drop Two Shells to replace Double Shulker Shells from Vanilla Tweak

## v0.2
- Added Xaero's Map Server Utils for stopping certain minimap options from working when needed
- Added Uncrafting Recipes to replace the unpacking recipes in Vanilla Tweaks for auto update
- Added client side optimization mods

## v0.1
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
