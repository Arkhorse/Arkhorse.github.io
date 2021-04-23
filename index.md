# Current Horizon version supported: 1.8 BETA 7

# Definitions

#### Game Root Folder:
This is where the games exe is at. Typically `Steam\steamapps\common\Fallout 4`.
#### CC:
Creation Content
#### Mo2:
[Mod Organizer 2](https://www.nexusmods.com/skyrimspecialedition/mods/6194). The only supported mod organizer. If you use Vortex, you will get not help from me. Nexus Mod Manager is not something you want to use due to issues.

# Minimum mods to make Horizon work well:

### [Unofficial Fallout 4 Patch](https://www.nexusmods.com/fallout4/mods/4598)
This mod should be used at all times. It must be loaded at the top of your load order. No other mod (other than CC) should be above it.
### [WSFW](https://www.nexusmods.com/fallout4/mods/35004)
This mod fixes some workshop issues, and is compatible with Horizon now. Load this under HUD Framework.
### [HUDFramework](https://www.nexusmods.com/fallout4/mods/20309)
Not exactly needed for Horizon, but other mods in this list need it. Load this directly under UF4P.
### [F4SE](https://f4se.silverlock.org)
This is needed for Buffout 4. Download and install into the games root folder, and make sure to install the data folder as well.
### [Buffout 4](https://www.nexusmods.com/fallout4/mods/47359)
This mod may be a tad annoying to install, but its well worth it. dont use it with [Baka ScrapHeap](https://www.nexusmods.com/fallout4/mods/46340)
#### Install instructions:
1. Download Buffout 4
2. Install it with Mo2
3. Download the TBB Redistributables (second file). Install this into the games root folder
4. Download [Address Library for F4SE Plugins](https://www.nexusmods.com/fallout4/mods/47327). Install with Mo2
5. Download [xSE PluginPreloader F4](https://www.nexusmods.com/fallout4/mods/33946). Install it to the games root folder.
    1. Open xSE PluginPreloader.xml with notpad ++ or VS code. Dont use notepad.
    2. Change `<LoadMethod Name="OnProcessAttach">` to `<LoadMethod Name="OnThreadAttach">`
    3. Save it
6. If you need it, download the Microsoft Visual C++ Redistributable for Visual Studio 2019. If you already have it installed, you dont need to install it again.
7. Thats it.
### [Bullet Counted Reload System (BCR)](https://www.nexusmods.com/fallout4/mods/41178)
This mod fixes the reload issue with lever action weapons, like the lever actions rifle and shotgun.
Patch for the [Horizon Lever Acton Shotgun](https://www.nexusmods.com/fallout4/mods/45120)
