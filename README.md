# TSPUD-Extract
This repository is a community-ran guide to help you extract assets from The Stanley Parable: Ultra Deluxe.

No assets from the game will be shared here, you have to buy the game on Steam to follow these instructions.

# Table of Contents
- [Setting Everything Up](#setting-everything-up)
- [Models / Meshes](#models--meshes)
- [Images / Textures](#images--textures)
- [Linux](#linux)

## Setting Everything Up
First, be sure you have a Steam version of The Stanley Parable: Ultra Deluxe installed.

You can download many tools, but I recommend [AssetStudio](https://github.com/Perfare/AssetStudio) for a free and simple way to get started.

If you use Linux, you can still follow along by doing [these steps](#linux) first.

Once installed, you can click `File` > `Load folder` and choose the `The Stanley Parable Ultra Deluxe_Data` folder, which should be in `C:\Program Files\Steam\steamapps\common\The Stanley Parable Ultra Deluxe` on Windows and `/home/$USER/.local/share/Steam/steamapps/common/The Stanley Parable Ultra Deluxe` on Linux.

Soon, everything should load, and you, in the `Asset List` tab, should now have a list of all assets in the game.

In the `Filter Type` dropdown you can choose which types of assets you want to see. You can use the search bar to search for an asset name of the filtered type.

Once you find what you want, select your assets to export and `Right Click` > `Export selected assets`, then pick a spot to export them and enjoy your newly exported assets!

## Models / Meshes

| Human-readable name | Name | Path ID | Notes |
|---|---|---|---|
|Figley / Stanlurine / Mini-Stan / Collectible | default | 234 | There is also another Figley model, but lower res |

## Images / Textures
| Human-readable name | Name | Path ID | Notes |
|---|---|---|---|
|Collectible Background (when you find a Figley)|figley_background_pattern|148|This is a tiling/repeatable texture!|

## Linux
[AssetStudio](https://github.com/Perfare/AssetStudio) is not available on Linux, but if you use [Wine](https://winehq.org) (be sure to use a version after `wine-5.17`, I recommend using the latest stable version), you should be able to get it running and follow the same steps in [Setting Everything Up](#setting-everything-up).
