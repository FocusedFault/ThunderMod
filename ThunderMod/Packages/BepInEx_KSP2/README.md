## BepInEx Framework

This is the pack of all the things you need to both start using mods, and start making mods using the BepInEx framework.

### What each folder is for:

-   `BepInEx/plugins` - This is where normal mods/plugins are placed to be loaded. If a mod is just a `NAME.dll` file, it probably goes in here. For your own organisation, consider putting them inside folders, eg: `plugins/ActualRain/ActualRain.dll`

-   `BepInEx/patchers` - These are more advanced types of plugins that need to access Mono.Cecil to edit .dll files during runtime. Only copy paste your mods here if the author tells you to.

-   `BepInEx/config` - If your plugin has support for configuration, you can find the config file here to edit it.

-   `BepInEx/core` - Core BepInEx .dll files, you'll usually never want to touch these files (unless you're updating manually)

### What is included in this pack

**BepInEx 5.4** - https://github.com/BepInEx/BepInEx
This is what loads all of your plugins/mods.

### Writing your own mods

There's 2 documentation pages available:

-   [BepInEx docs](https://docs.bepinex.dev/)

Places to talk:

-   [General BepInEx discord](https://discord.gg/MpFEDAg)

BepInEx contains helper libraries like [MonoMod.RuntimeDetour](https://github.com/MonoMod/MonoMod/blob/master/README-RuntimeDetour.md) and [HarmonyX](https://github.com/BepInEx/HarmonyX/wiki)

### Changelog

-   **5.4.2106**
    -   Setup for Kerbal Space Program 2