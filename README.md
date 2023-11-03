# ThunderMod
 RoR2 mod template made with Thunderkit

### Quickstart
1. Create repo from this template or download the ZIP
2. Open the ThunderMod folder in Unity (make sure you have 2019.4.26f installed)
3. Click `No Thanks` to the "API Update Required" popup
4. Once the project loads, click on the `ThunderKit Settings` tab in the Thunderkit window
5. Click `Browse` and locate your Risk of Rain 2 exe file. You can find it by going to steam > clicking the cog icon on the game page, click `Manage`, click `Browse Local Files`, then click on the exe file
6. Click on `Import` then click `Restart Project` when you get the "Disable Assembly Updater" popup, this will prevent the "API Update Required" popups.
8. Once it finishes importing it'll prompt you to restart
9. If you get a prompt about a missing Bepinex, install it from the Thunderkit package manager `Tools` > `Thunderkit` > `Packages` and install Bepinex from the thunderstore tab.
10. If you have a `BepInEx.Harmony.dll` error don't worry about it unless you're going to be using Harmony, if that's the case get some help in the modding discord's `thunderkit` channel or Thunderkit discord.
11. NOTICE: there is a bug in the latest ThunderKit version so you'll have to manually add `RISKOFRAIN2` (just type that in) to the project's scripting define symbols. To find the scripting define symbols you need to go to `Edit` > `Project Settings` > `Playe`r and type in `RISKOFRAIN2` to your Scripting Define Symbols.
12. That's it! You should be ready to get started.
13. To build the project and get your assetbundle go to `Pipelines` click the pipelines file then click on the `Execute` button, your files will be in `Thunderkit` > `Libraries` for the dll and `Thunderkit` > `AssetBundleStaging` for your assetbundle.
