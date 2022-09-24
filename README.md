# Half-Life 2 VR Essentials Modpack (v1.0)
Last updated: September 23, 2022

## Preamble
Half-Life 2 has gained a massive library of incredible mods over the years.  Keeping track of the best HL2 mods can be cumbersome as everything is mostly scattered across Gamebanana, ModDB, and Gmod Workshop.  There are arguably no great all-one-one HL2 texture mods for retexturing the entire game, as most texture mods are either not comprehensive or make contentious changes to the game's original artstyle.  

I have made an attempt to greatly simplify Half-Life 2 VR's modding process by creating a standalone copy of Mod Organizer 2 which is preconfigured with the most essential mods for improving immersion in Half-Life 2 VR.  Great care was taken in selecting the best and most "VR friendly" models and textures with an appropriate load order across a wide variety of different texture mods.  All credit for the mods included in this modpack goes to the original mod authors.   

This modpack is also pre-configured with experimental VR support for MINERVA: Metastasis and Nightmare House Remake.  According to Nixel on Gmod Workshop, these campaigns can be completed without their DLL files.  I have not fully tested these campaigns, but they should theoretically work in VR. 

## Installation
#### Mod Organizer 2
1. Download [**HLVR_MO2_Repack_v1.rar**](http://188.42.46.42/hl2vr/HLVR_MO2_Repack_v1.rar) and extract Mod Organizer 2 to a folder of your choice.
2. Download [**EP1+2 Assets.rar**](http://188.42.46.42/hl2vr/EP1+2%20Assets.rar) and extract the contents to your \Steam\steamapps\common\Half-Life 2 VR\ folder.  (This adds episodic assets to your HL2VR folder.  This will NOT allow you to play the episodes, but it will allow you to play Minerva and Nightmare House Remake which all use Episode 1+2 models and textures.)
3. Navigate to where you extracted HLVR_MO2_Repack.rar and run ModOrganizer.exe
4. If you installed Half-Life 2 VR on a drive other than the C drive, please perform the following steps:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Navigate to "Tools >  Settings > Paths" and set the "Managed Game" path to your location for "hl2vr.exe".

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Navigate to "Tools > Executables".  For "Half-Life VR" and "Half-Life VR (Console)":

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set the "Binary" field to your location for "hl2vr.exe" 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Set the "Start in" field to your location for the "Half-Life 2 VR" folder.

5. Select "Run" in the upper right corner of Mod Organizer 2 to launch Half-Life 2 VR with the mods included in this modpack.

#### zDak Total Textures Pack
I would highly recommend using the zDak Total Texture Pack along with my Repack.  It improves lots of materials and models not covered by this Repack and greatly improves immersion in VR.  To use the zDak pack, follow these steps:

1. Download the [zDak Total Textures Pack v5.7](https://www.moddb.com/addons/zdak-total-textures-pack-v13) from ModDB.
2. Extract the VPK files from the zDak pack.
3. Unpack the VPK files using [GCFScape](https://nemstools.github.io/pages/GCFScape-Download.html).
4. Place the extracted "materials", "models", and "sounds" folders in a new folder i.e. "zDak Total Textures Pack" and move this folder to \Your Mod Organizer 2 folder\mods\
5. Optionally remove the following files from the zDak pack as the vanilla textures look better in VR: decal_policeline01a.* and traincar_bars*.*   
6. Launch MO2. Drag and drop the zDak pack ABOVE any other texture mods in the left window pane.  This gives existing mods in the mod list the highest priority.  They will continue to work normally and the zDak pack will retexture anything not covered by the Repack. 

## Configuration

#### Config File
With Mod Organizer 2, you can set custom commands to run at starup by placing them in: *\Your Mod Organizer 2 Folder\mods\Config File\cfg\autoexec.cfg*
(Do not place settings in the autoexec.cfg in your Steam folder as this file is not used by MO2.)

#### Tweak Movement Speed with Autoexec.cfg (Optional)
Walking speed can be tweaked with slower values by adding these two lines to: *\Your Mod Organizer 2 Folder\mods\Config File\cfg\autoexec.cfg*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*hl2_normspeed 120*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*hl2_sprintspeed 220*

Note that these settings will prevent you from moving when crouching.  To adjust walking speed without breaking crouching, you can alternatively tweak your movement speed with VoiceAttack as described below.

#### Tweak Movement Speed with VoiceAttack (Optional)
This modpack binds two seperate walking speeds to the "alt" (slow walking) and "shift" (running) keys.  If you bind words like "walk" and "run" to the "alt" and "shift" keys in the free version of [**VoiceAttack**](https://voiceattack.com/), you can toggle between walking and running on the fly in VR by simply reciting "walk" or "run" in your headset mic!    

## Known Issues
- When using Mod Organizer 2, saved games are stored in MO2's \overwrite\save folder and will not be synced with Steam Cloud. 
- Using mods with existed saved games may cause "AI disabled" problems.  If you run into this issue, open the console and enter the following commands:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*ai_norebuildgraph 1*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*ai_resume*

and then reload your saved game.  Alternatively, find the map you are currently on at the [wiki](https://wiki.sourceruns.org/wiki/Half-Life_2_Maps) and restart from there through the console via: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*map map_name*

## Included Campaign Mods
[**Nightmare House 1 Remake**](https://steamcommunity.com/workshop/filedetails/?id=481052291)

If you wish to install Nightmare House 1 manually without using this Repack, perform the following steps:
- Download Nixel's Gmod Workshop version of Nightmare House. Decompress it with Gmad and install it as a regular mod.
- Download Nightmare House 2 and merge its "materials" and "models" folders with Nightmare House.
- Mount Episode 1+2 in gameinfo.txt and copy Episode 1+2 to \Half-Life 2 VR\ with decompressed VPKs.
- Remove the "bin" folders from Nightmare House and Episodes 1+2.

[**MINERVA: Metastasis**](https://steamcommunity.com/workshop/filedetails/?id=481052291)

If you wish to install MINERVA manually without using this Repack, perform the following steps:
- Download MINERVA from Steam and install it as a regular mod.
- Mount Episode 1+2 in gameinfo.txt and copy Episode 1+2 to \Half-Life 2 VR\ with decompressed VPKs.
- Remove the "bin" folders from MINERVA and Episodes 1+2.

[**MINERVA VR HUD Fix**]
- Custom patched ClientScheme.res and titles.txt to allow for HUD messages to display properly in VR.

## Included Mods (Listed in Recommended Load Order)
[**Half Life 2 HD Enhancement Project**](https://gamebanana.com/mods/6650)
- Swapped main menu concrete textures (concretefloor037b) with better versions from zDak Total Texture Pack v5.7.

[**Cinematic Mod 2013 - Lab Props Only**](https://www.moddb.com/mods/fakefactory-cinematic-mod)
- Used only \models\props_lab\generatorconsoff.\*, \models\props_lab\generatorconsole.\*, "ff_models", and "ff_props".

[**MORE COULOURS - Half-Life Alyx Valve**](https://gamebanana.com/mods/379478)

[**2004 Blood Particles Recreation**](https://gamebanana.com/mods/369550)

[**2004 Water Particles Recreation**](https://gamebanana.com/mods/373490)

[**1K Bills**](https://gamebanana.com/mods/311124)

[**2K Blast Door**](https://gamebanana.com/mods/181038)

[**2K HEV Clipboard**](https://gamebanana.com/mods/181039)

[**2K Trash**](https://gamebanana.com/mods/6603)

[**4K Rug**](https://gamebanana.com/mods/6601)

[**Airboat Remaster**](https://gamebanana.com/mods/181939)

[**BazookaTooth's HL2 FX Pack**](https://gamebanana.com/mods/11302)

[**Better Foliage for Half-Life 2**](https://gamebanana.com/wips/51165)

[**Combine Turret Remake**](https://gamebanana.com/mods/182474)

[**CSGO Large Dumpster Replacement**](https://gamebanana.com/mods/182497)

[**Decals Revamp**](https://gamebanana.com/mods/11358)

[**Blood 4K**](https://gamebanana.com/mods/11370)
- Downscaled to 2048px to prevent engine errors.

[**GAZ-53 Replacement**](https://gamebanana.com/mods/358140)

[**Half Life Alyx Alcohol Bottles**](https://gamebanana.com/mods/182502)

[**Half Life Alyx Cargo Containers**](https://gamebanana.com/mods/182533)

[**Half Life Alyx Claypot**](https://gamebanana.com/mods/380287)

[**Half Life Alyx Combine Consoles + Generator**](https://gamebanana.com/mods/183145)
- Added "$nodecal 1" to VMT files to prevent engine errors.

[**Half Life Alyx Supply Crate**](https://gamebanana.com/mods/182710)

[**Half Life Alyx Trainstation Benches**](https://gamebanana.com/mods/182503)

[**Half-Life 2 Propane Canisters - Remake**](https://gamebanana.com/mods/182547)

[**Half-Life 2 Remade Assets (Citizen Radio)**](https://gamebanana.com/mods/348653)

[**Half-Life 2 Remade Assets (Combine Interface)**](https://gamebanana.com/mods/303851)

[**Half-Life 2 Remade Assets (Razor Train)**](https://gamebanana.com/mods/301708)

[**Half-Life 2 Remade Assets (Suit Charger)**](https://gamebanana.com/mods/300619)

[**Half-Life 2 Remade Assets (Washing Machine)**](https://gamebanana.com/mods/347118)

[**Half-Life 2 Remade Assets DE Source 1 Port - Junk Doll Vending Only**](https://gamebanana.com/mods/300761)
- Used only "doll01", "vendingmachinesoda01a", and "props_junk".

[**Half-Life Alyx Multitool**](https://gamebanana.com/mods/320312)

[**Half-Life Alyx Pigeon**](https://gamebanana.com/mods/318698)

[**Half-Life Alyx Props**](https://gamebanana.com/mods/181050)

[**Extra-Detailed DrBreens Water Set - Blue Popcan**](https://gamebanana.com/mods/181932)

[**Half-Life Alyx Repaired HEV Suit**](https://gamebanana.com/mods/293420)

[**Half-Life Alyx Suitcase**](https://gamebanana.com/mods/330741)

[**HD Beta Antlion Reskin**](https://gamebanana.com/mods/182066)

[**HD Cactus**](https://gamebanana.com/mods/182505)

[**HD Crates**](https://gamebanana.com/mods/182529)

[**HD Decals Pack #1**](https://gamebanana.com/mods/6616)

[**HD Decals Pack #2**](https://gamebanana.com/mods/6615)

[**HD Explosion Decals**](https://gamebanana.com/mods/11355)

[**HD ITEMS - No Battery**](https://www.moddb.com/mods/half-life-2-hd-remastered-texture-pack/downloads/hd1)
- Removed "models\items\battery.\*" to prevent conflict with better version from "Item Revamp Pack".

[**HD Maps Remake**](https://gamebanana.com/mods/6649)

[**HD Newspaper**](https://gamebanana.com/mods/182496)

[**HD Overhaul - Ladders Only**](https://www.playground.ru/half-life_2/file/half_life_2_uluchshennye_tekstury_v_2k-1049020)
- Used only "NEXTGEN_MATERIALS" along with "metal" textures from \materials\Detail, \materials\models\props_c17.

[**HD Remake Corkboards**](https://gamebanana.com/mods/182795)

[**HD Remake Photos**](https://gamebanana.com/mods/182790)

[**HD Retexture Keypad**](https://gamebanana.com/mods/182514)

[**HD Video Feeds**](https://gamebanana.com/mods/310736)

[**HL2 Remake Barrels**](https://gamebanana.com/mods/182561)

[**HD Remake Barrels (Old Version)**](https://gamebanana.com/mods/182562)

[**HLA Bones Pack**](https://gamebanana.com/mods/384956)

[**HLA Buildings**](https://gamebanana.com/mods/181933)

[**HLA Combine's Props**](https://gamebanana.com/mods/366898)
- Added "$nodecal 1" to VMT files to prevent engine errors.

[**HLA Combine's Walls**](https://gamebanana.com/mods/370056)

[**Half-Life Alyx Assets in Half-Life 2**](https://gamebanana.com/mods/291754)

[**HD Remake Combine's Lock**](https://gamebanana.com/mods/183151)

[**HLA Padlock Prop**](https://gamebanana.com/mods/378884)

[**HLA Playground Props**](https://gamebanana.com/mods/386837)

[**HLA Props Pack**](https://gamebanana.com/mods/181058)

[**HLA-L4D1 Flashlight Replacement**](https://gamebanana.com/mods/374478)

[**Intro Test Chamber Replacement**](https://gamebanana.com/mods/57134)

[**Item Revamp Pack - Battery Only**](https://gamebanana.com/mods/181063)
- Used only "battery01".  Removed conflicting "battery" model from HD ITEMS.

[**Jerrycan Replacement**](https://gamebanana.com/mods/296119)

[**Manhack Remake**](https://gamebanana.com/mods/182473)

[**Munancho INC's Improved Ammo Crates**](https://gamebanana.com/mods/182722)

[**New Burning FX**](https://gamebanana.com/mods/11318)

[**Raising The Bar Redux Ceiling Turret Reskin**](https://gamebanana.com/mods/371409)

[**REMASTERED! Half-Life Alyx Combine Prisoner Pods**](https://gamebanana.com/mods/329975)

[**Toxic Slime Reworked**](https://gamebanana.com/mods/6656)

[**Trainstation Remade**](https://gamebanana.com/mods/400743)

[**Vanilla Style Half-Life Alyx Health Charger**](https://gamebanana.com/mods/182565)

[**Water Tower Remake**](https://gamebanana.com/mods/181934)

## Other Recommended Mods
- [**HL2 VR - Comic Book Mod**](https://ko-fi.com/post/ComicBook4K-Release-Y8Y3F2OH5): Beautiful Borderlands style texture mod!
- [**zDak Total Textures Pack**](https://www.moddb.com/addons/zdak-total-textures-pack-v13):  A very nice and comprehensive texture mod which looks beautiful in VR.  Not included in this modpack due to its large filesize.

## Recommended Modding Tools
- [**Mod Organizer 2 Plugin for Half-Life 2 VR**](https://www.nexusmods.com/halflife2/mods/35):  Allows for Skyrim style modding with Mod Organizer 2.  Removes the complexity of managing load order from "custom" folders.
- [**GCFScape**](https://nemstools.github.io/pages/GCFScape-Download.html): Used for decompressing VPK files.
- [**Gmad - Easy Addon Extractor**](https://www.moddb.com/mods/garrys-mod/downloads/gmad-easy-addon-extractor): Used for decompressing Garry's Mod addons.

## Compatability notes
- Black Mesa Source:  Does not work.  Maps work in VR but NPCs do not load.
- Black Mesa: Does not work.  Crashes to the desktop.
- Research and Development: Mr. Whirly does not work.
- HL2 MMod Improved Sounds: Partially working.  Some sounds do not play properly.
- Cinematic Mod 2013: Partially working.  Reflections are glitched. (Reflections oddly worked fine with the Half-Life 2 VR private beta.)

## Changelog
See [Changelog](https://github.com/Ashok0/HL2VREssentials/blob/main/CHANGELOG.md)

## Credits
All credit for this mod pack goes to the following original creators:

*[Jay], [SU]- Zen, Eevah, A-06, A-Shift, Adam "Cargo Cult" Foster, Ahri Lover, Banahezzer, BazookaTooth, Benedict_Kapustin42, Boromir Artementaller, CondiRoks, CrazyHairGuy, cubicApocalypse, Dead-Inside, DetonatedStorm, DrGordonFreeman96, Dynamic_, Ellie, Empower1, Fakefactory, Foxidimi, GameSpy, General Ecchi, H3000, HL2MMod Team, Iiopn, Iretuerye, Isomeric Gamer, Jeremiexp, Jerson Gaming, Jofoyo, jQueary, kalimando, MARK2580, Mbbote, Mine60000, MrBrightside, Munancho INC., MYSTIC, Nixel, nubblecakes, QueenPlague_Cure, Red Menace, Reverend V92, SamMaddie, Shadow_RUN, Sierra Foxtrot, Spoono, The Half-Life 2: Remade Assets Team (Retro Boy, Kube, MDDBULLDOGG, Exeros, hELLO, LVJohnFreeman, E Borge), themanclaw, TwoTime, TwoTime, Volkolak, Vort95, We Create Stuff, Wolfcl0ck, Wood_y, zDaken50, Zekeakers1*.

