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
<details>
    <ol>
        <li>Download Buffout 4</li>
        <li>Install it with Mo2</li>
        <li>Download the TBB Redistributables (second file). Install this into the games root folder</li>
        <li>Download <a href="https://www.nexusmods.com/fallout4/mods/47327">Address Library for F4SE Plugins</a>. Install with Mo2</li>
        <li>Download <a href="https://www.nexusmods.com/fallout4/mods/33946">xSE PluginPreloader F4</a>. Install it to the games root folder.</li>
        <ol>
            <li>Open xSE PluginPreloader.xml with notpad ++ or VS code. Dont use notepad.</li>
            <li>Change <code>LoadMethod Name="OnProcessAttach"</code> to <code>LoadMethod Name="OnThreadAttach"</code></li>
            <li>Save it</li>
            <li>If you need it, download the Microsoft Visual C++ Redistributable for Visual Studio 2019. If you already have it installed, you dont need it again.</li>
        </ol>
    	<li>Thats it.</li>
    </ol>
</details>

### [Bullet Counted Reload System (BCR)](https://www.nexusmods.com/fallout4/mods/41178)
This mod fixes the reload issue with lever action weapons, like the lever actions rifle and shotgun.
Patch for the [Horizon Lever Acton Shotgun](https://www.nexusmods.com/fallout4/mods/45120)
