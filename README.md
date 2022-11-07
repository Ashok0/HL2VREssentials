# Half-Life 2 VR Essentials Modpack (v1.05)
Last updated: November 6th, 2022

## Table of contents
* [Preamble](#preamble)
* [Installation](#installation)
* [Known Issues](#known-issues)
* [Included Mods](#included-mods-listed-in-recommended-load-order)
* [Other Recommended Mods](#other-recommended-mods)
* [Recommended Modding Tools](#recommended-modding-tools)
* [Compatibility Notes](#compatibility-notes)
* [Changelog](#changelog)
* [Credits](#credits)

## Preamble
Half-Life 2 has gained a massive library of incredible mods over the years.  Keeping track of the best HL2 mods can be cumbersome as everything is mostly scattered across Gamebanana, ModDB, and Gmod Workshop.  There are arguably no great all-one-one HL2 texture mods for retexturing the entire game, as most texture mods are either not comprehensive or make contentious changes to the game's original artstyle.  

I have made an attempt to greatly simplify Half-Life 2 VR's modding process by creating a standalone copy of Mod Organizer 2 which is preconfigured with the most essential mods for improving immersion in Half-Life 2 VR.  Great care was taken in selecting the best and most "VR friendly" models and textures with an appropriate load order across a wide variety of different texture mods.  All credit for the mods included in this modpack goes to the original mod authors.   

This modpack is also pre-configured with VR support for Lost Coast, Year Long Alarm, MINERVA: Metastasis, and Nightmare House Remake.  These campaigns are fully playable in VR without their DLL files. If you experience any problems with this mod pack, please submit a bug report so I can continue to improve this mod list!

**New Updates**
- Custom fixes to prevent "Too many indices for index buffer" crashes.
- Removed unstable mods to fix crashes, AI errors, and load zone issues in "We Don't Go To Ravenholm..." and "Follow Freeman".
- Fixed missing sound effects.
- Fixed the incorrect Steam App ID in Mod Organizer 2.
- Fixed the main menu for Nightmare House and MINERVA.
- Removed duplicate MINERVA textures to significantly reduce the filesize.
- Added support for Lost Coast and Year Long Alarm.
- Enabled experimental immersive doors feature and disabled Bloom in the config file.
- Added additional texture mods.
- Added optional HD Alyx style zombie mods. Disabled by default as these mods change the artsyle from the original vanilla models.

## Installation

#### Mod Organizer 2
:small_orange_diamond: ***If the download links below fail to download in your Web browser, please use Internet Download Manager or JDownloader2 which are confirmed to work fine.*** 
1. Download [**HLVR_MO2_Repack_v1.05.rar**](http://188.42.46.42/hl2vr/HLVR_MO2_Repack_v1.05.rar) and extract Mod Organizer 2 to a folder of your choice outside of "Users" or "Program Files".  It's best to extract the folder near the root level of your drive i.e. C:\Games\HL2VR
2. Download [**EP1+2 Assets.rar**](http://188.42.46.42/hl2vr/EP1+2%20Assets.rar) and extract the contents to your \Steam\steamapps\common\Half-Life 2 VR\ folder.  (This adds episodic assets to your HL2VR folder.  This will NOT allow you to play the episodes, but it will allow you to play Minerva and Nightmare House Remake which all use Episode 1+2 models and textures.  You can skip this step if you only wish to play the main campaign.)
3. Navigate to where you extracted **HLVR_MO2_Repack_v1.05.rar** and run **ModOrganizer.exe**
4. If you installed Half-Life 2 VR on a drive other than the C drive, please perform the following steps in Mod Organizer 2:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Navigate to "**Tools >  Settings > Paths**" and set the "**Managed Game**" path to your location for "**hl2vr.exe**".

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Navigate to "**Tools > Executables**" and select "**Half-Life 2 VR**":

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Set the "**Binary**" field to your location for "**hl2vr.exe**". 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Set the "**Start in**" field to your location for the "**Half-Life 2 VR**" folder.

5. Select "**Half-Life 2 VR**" in the upper right drop down bar.  

6. Select "**Run**" in the upper right corner of Mod Organizer 2 to launch Half-Life 2 VR with the mods included in this modpack.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Leave all MINERVA and Nightmare House mods unticked to play the main Half-Life 2 campaign.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Enable the MINERVA mods and leave the Nightmare House mods disabled to play MINERVA.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Enable the Nightmare House mods and leave the MINERVA mods disabled to play Nightmare House.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Enable HD zombie mods under "Optional Texture Mods" to enable Alyx style zombies.  Disabled by default.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;» Untick "No Bloom" to enable Bloom.

#### Launch Settings
With Mod Organizer 2, you can set custom commands to run at starup by placing them in: *\Your Mod Organizer 2 Folder\mods\Config File\cfg\autoexec.cfg*
(Do not place settings in the autoexec.cfg in your Steam folder as this file is not used by MO2.)

#### zDak Total Textures Pack
I would highly recommend using the zDak Total Texture Pack along with my Repack.  It improves lots of materials and models not covered by this Repack and greatly improves immersion in VR.  To use the zDak pack, follow these steps:

1. Download the [zDak Total Textures Pack v5.7](https://www.mediafire.com/file/09itw0czhgj5a57/zDak+Total+Textures+Pack+v5.7_066.zip/file) from ModDB.
2. Extract the VPK files from the zDak pack.
3. Open 'zDak Total Textures Pack v5.7_dir.vpk' in [GCFScape](https://nemstools.github.io/pages/GCFScape-Download.html) and unpack the VPK files.
4. Place the extracted "materials", "models", and "sounds" folders in a new folder i.e. "zDak Total Textures Pack" and move this folder to \Your Mod Organizer 2 folder\mods\
5. Optionally remove the following files from the zDak pack as the vanilla textures look better in VR: decal_policeline01a.* and traincar_bars*.*   
6. Launch MO2. Drag and drop the zDak pack BELOW custom campaign mods and ABOVE any other texture packs/mods in the left window pane.  It should typically be placed above the HL2 HD Enhancement Project.  This gives existing texture mods in the mod list the highest priority.  They will continue to work normally and the zDak pack will retexture anything (in both Half-Life 2 and custom campaigns) not covered by the Repack.   

## Known Issues
- When using Mod Organizer 2, saved games are stored in MO2's \overwrite\save folder and will not be synced with Steam Cloud. 
- Using mods with existed saved games may cause "AI disabled" problems.  If you run into this issue, open the console and enter the following commands:

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*ai_norebuildgraph 1*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*ai_resume*

and then reload your saved game.  Alternatively, find the map you are currently on at the [wiki](https://wiki.sourceruns.org/wiki/Half-Life_2_Maps) and restart from there through the console via: 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*map map_name*

## Included Mods (Listed in Recommended Load Order)
[**Half-Life 2: Lost Coast**](https://store.steampowered.com/app/340/HalfLife_2_Lost_Coast/)

If you wish to install Lost Coast manually without using this Repack, perform the following steps:
- Download Lost Coast from Steam and install it as a regular mod.
- Remove "scripts\hudanimations.txt", "resource\gamemenu.res", and "gameinfo.txt"

[**Nightmare House 1 Remake**](https://steamcommunity.com/workshop/filedetails/?id=481052291)

If you wish to install Nightmare House 1 manually without using this Repack, perform the following steps:
- Download Nixel's Gmod Workshop version of Nightmare House. Decompress it with Gmad and install it as a regular mod.
- Download Nightmare House 2 and merge its "materials" and "models" folders with Nightmare House.
- Copy Episode 1+2 to \Half-Life 2 VR\ with decompressed VPKs. 
- Replace "gameinfo.txt" with "hlvr\gameinfo.txt".  Then add the following lines under "//HL2 Content": 

         game+mod			episodic/ep1_sound_vo_english.vpk	 
         game+mod			episodic/ep1_pak.vpk
         game+mod			ep2/ep2_sound_vo_english.vpk
         game+mod			ep2/ep2_pak.vpk
         game+mod			lostcoast/lostcoast_sound_vo_english.vpk
         game+mod			lostcoast/lostcoast_pak.vpk
- Remove the "bin" folders from Nightmare House and Episodes 1+2.

[**MINERVA: Metastasis**](https://steamcommunity.com/workshop/filedetails/?id=481052291)

If you wish to install MINERVA manually without using this Repack, perform the following steps:
- Download MINERVA from Steam and install it as a regular mod.
- Copy Episode 1+2 to \Half-Life 2 VR\ with decompressed VPKs. 
- Replace "gameinfo.txt" with "hlvr\gameinfo.txt".  Then add the following lines under "//HL2 Content": 

         game+mod			episodic/ep1_sound_vo_english.vpk	 
         game+mod			episodic/ep1_pak.vpk
         game+mod			ep2/ep2_sound_vo_english.vpk
         game+mod			ep2/ep2_pak.vpk
         game+mod			lostcoast/lostcoast_sound_vo_english.vpk
         game+mod			lostcoast/lostcoast_pak.vpk
         
- Remove the "bin" folders from MINERVA and Episodes 1+2.
- Remove GameMenu.res

[**MINERVA HUD Fix for VR**](https://gamebanana.com/mods/403825)
- Custom patched ClientScheme.res and titles.txt to allow for HUD messages to display properly in VR.

[**Half-Life 2: Year Long Alarm**](https://store.steampowered.com/app/747250/HalfLife_2_Year_Long_Alarm/)

If you wish to install Year Long Alarm manually without using this Repack, perform the following steps:
- Download Year Long Alarm from Steam and install it as a regular mod.
- Copy Episode 1+2 to \Half-Life 2 VR\ with decompressed VPKs. 
- Replace "gameinfo.txt" with "hlvr\gameinfo.txt".  Then add the following lines under "//HL2 Content": 

         game+mod			episodic/ep1_sound_vo_english.vpk	 
         game+mod			episodic/ep1_pak.vpk
         game+mod			ep2/ep2_sound_vo_english.vpk
         game+mod			ep2/ep2_pak.vpk
         game+mod			lostcoast/lostcoast_sound_vo_english.vpk
         game+mod			lostcoast/lostcoast_pak.vpk
         
- Remove "bin" folder
- Remove "resource\GameMenu.res"
- Replace "resource\ClientScheme.res" with "\hlvr\resource\ClientScheme.res".  Then replace the "CustomFontFiles" section with the following code to fix the main menu logo: 

         game+mod			episodic/ep1_sound_vo_english.vpk	 
         game+mod			episodic/ep1_pak.vpk
         "1"		"resource/HALFLIFE2.ttf"
         "2"		"resource/HL2crosshairs.ttf"

- Remove "scripts\vgui_screens.txt" and "scripts\weapon*.*" 

[**Half Life 2 HD Enhancement Project**](https://gamebanana.com/mods/6650)
- Swapped main menu concrete textures (concretefloor037b) and stone wall textures (stonewall050f.\*, stonewall050k.\*, stonewall051a.\*, stonewall051a_normal.\*, stonewall051b.\*, stonewall051c.\*) with better versions from zDak Total Textures Pack v5.7.  If the zDak Total Textures Pack is already installed, these textures can simply be deleted from HEP to save space.  
- Added zDak stone wall pre-requisite textures (\FF_Detail\plaster_detail_04.vtf, \FF_Detail\noise_detail_01.vtf, \FF_Detail\gmetal_grey.vtf).  Not necessary if the zDak Total Textures Pack is already installed. 

[**Cinematic Mod 2013 - Lab Props Only**](https://www.moddb.com/mods/fakefactory-cinematic-mod)
- Used only \models\props_lab\generatorconsoff.\*, \models\props_lab\generatorconsole.\*, "ff_models", and "ff_props".

[**[Half Life Alyx] Scanner (Replacement)**](https://steamcommunity.com/sharedfiles/filedetails/?id=2069752118&searchtext=alyx+scanner)

[**MORE COULOURS - Half-Life Alyx Valve**](https://gamebanana.com/mods/379478)

[**2004 Blood Particles Recreation**](https://gamebanana.com/mods/369550)

[**2004 Water Particles Recreation**](https://gamebanana.com/mods/373490)

[**1K Bills**](https://gamebanana.com/mods/311124)

[**2K Blast Door**](https://gamebanana.com/mods/181038)

[**2K HEV Clipboard**](https://gamebanana.com/mods/181039)

[**2K Trash**](https://gamebanana.com/mods/6603)

[**4K Rug**](https://gamebanana.com/mods/6601)

[**Airboat Remaster**](https://gamebanana.com/mods/181939)

[**Alyx-Themed Ration Package**](https://gamebanana.com/mods/320806)

[**BazookaTooth's HL2 FX Pack**](https://gamebanana.com/mods/11302)

[**Buggy Remaster**](https://gamebanana.com/mods/181955)
- Added "$nodecal 1" to VMT files to prevent engine errors.

[**Combine Turret Remake**](https://gamebanana.com/mods/182474)

[**CSGO Large Dumpster Replacement**](https://gamebanana.com/mods/182497)

[**Decals Revamp**](https://gamebanana.com/mods/11358)

[**Blood 4K**](https://gamebanana.com/mods/11370)
- Downscaled to 2048px to prevent engine errors.

[**GAZ-53 Replacement**](https://gamebanana.com/mods/358140)

[**Half Life Alyx Alcohol Bottles**](https://gamebanana.com/mods/182502)

[**Half Life Alyx Cargo Containers**](https://gamebanana.com/mods/182533)

[**Half Life Alyx Cars and Combine Traincar**](https://gamebanana.com/mods/181073)
- Removed "car002a.dx90.vtx" to prevent crashes to the desktop.

[**Half Life Alyx Claypot**](https://gamebanana.com/mods/380287)

[**Half Life Alyx Combine Consoles + Generator**](https://gamebanana.com/mods/183145)
- Added "$nodecal 1" to VMT files to prevent engine errors.

[**Half Life Alyx Trainstation Benches**](https://gamebanana.com/mods/182503)

[**Half-Life 2 Propane Canisters - Remake**](https://gamebanana.com/mods/182547)

[**Half-Life 2 Remade Assets (Citizen Radio)**](https://gamebanana.com/mods/348653)

[**Half-Life 2 Remade Assets (Combine Interface)**](https://gamebanana.com/mods/303851)

[**Half-Life 2 Remade Assets (Razor Train)**](https://gamebanana.com/mods/301708)

[**Half-Life 2 Remade Assets (Suit Charger)**](https://gamebanana.com/mods/300619)

[**Half-Life 2 Remade Assets (Washing Machine)**](https://gamebanana.com/mods/347118)

[**Half-Life 2 Remade Assets DE Source 1 Port - Suitcase Junk Doll Vending Only**](https://gamebanana.com/mods/300761)
- Used only "suitcase", "doll01", "vendingmachinesoda01a", and "props_junk".

[**Half-Life Alyx Car Battery Replacement**](https://steamcommunity.com/sharedfiles/filedetails/?id=2016800872&searchtext=car+battery)

[**Half-Life Alyx Multitool**](https://gamebanana.com/mods/320312)

[**Half-Life Alyx Pigeon**](https://gamebanana.com/mods/318698)

[**Half-Life Alyx Props**](https://gamebanana.com/mods/181050)

[**Extra-Detailed DrBreens Water Set - Blue Popcan**](https://gamebanana.com/mods/181932)

[**Half-Life Alyx Repaired HEV Suit**](https://gamebanana.com/mods/293420)

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

[**HL Alyx Watermelon [REPLACEMENT]**](https://steamcommunity.com/sharedfiles/filedetails/?id=2501044748&searchtext=watermelon)

[**HLA Bones Pack**](https://gamebanana.com/mods/384956)

[**HLA Buildings**](https://gamebanana.com/mods/181933)

[**HLA Combine's Props**](https://gamebanana.com/mods/366898)
- Added "$nodecal 1" to VMT files to prevent engine errors.

[**HLA Combine's Walls**](https://gamebanana.com/mods/370056)

[**Half-Life Alyx Assets in Half-Life 2**](https://gamebanana.com/mods/291754)

[**HD Remake Combine's Lock**](https://gamebanana.com/mods/183151)

[**HLA File Cabinets**](https://gamebanana.com/mods/406912)

[**HLA Padlock Prop**](https://gamebanana.com/mods/378884)

[**HLA Playground Props**](https://gamebanana.com/mods/386837)

[**HLA Props Pack - Shoe Bottles Only**](https://gamebanana.com/mods/181058)
- Used only shoe*.* and \*bottle*.* files.

[**HLA-L4D1 Flashlight Replacement**](https://gamebanana.com/mods/374478)

[**Intro Test Chamber Replacement**](https://gamebanana.com/mods/57134)

[**Item Revamp Pack - Battery Only**](https://gamebanana.com/mods/181063)
- Used only "battery01".  Removed conflicting "battery" model from HD ITEMS.

[**J Barnes Item Crate**](https://www64.zippyshare.com/v/6iMwXfjW/file.html)
- Used custom modded crate textures with City 17 decals removed.  Original mod available [HERE](https://gamebanana.com/mods/182716).

[**Jerrycan Replacement**](https://gamebanana.com/mods/296119)

[**Laundry Machines Remake**](https://gamebanana.com/mods/182498) 

[**Manhack Remake**](https://gamebanana.com/mods/182473)

[**Munancho INC's Improved Ammo Crates**](https://gamebanana.com/mods/182722)

[**New Burning FX**](https://gamebanana.com/mods/11318)

[**Raising The Bar Redux Ceiling Turret Reskin**](https://gamebanana.com/mods/371409)

[**REMASTERED! Half-Life Alyx Combine Prisoner Pods**](https://gamebanana.com/mods/329975)

[**Toxic Slime Reworked**](https://gamebanana.com/mods/6656)

[**Trainstation Remade**](https://gamebanana.com/mods/400743)

[**Vanilla Style Half-Life Alyx Health Charger**](https://gamebanana.com/mods/182565)

[**Water Tower Remake**](https://gamebanana.com/mods/181934)

[**Half-Life Alyx Zombie Replacement 2 FIX**](https://gamebanana.com/mods/182311)

[**[Half Life Alyx] Classic Headcrab (Replacement)**](https://steamcommunity.com/sharedfiles/filedetails/?id=2016485109&searchtext=alyx+headcrab)

[**HLA-Styled Poison Zombie**](https://gamebanana.com/mods/284999)

[**Half-Life Alyx Poison Headcrab in Half-Life 2**](https://gamebanana.com/mods/182446)

## Other Recommended Mods
- [**HL2 VR - Comic Book Mod**](https://ko-fi.com/post/ComicBook4K-Release-Y8Y3F2OH5): Beautiful Borderlands style texture mod!
- [**zDak Total Textures Pack**](https://www.moddb.com/addons/zdak-total-textures-pack-v13):  A very nice and comprehensive texture mod which looks beautiful in VR.  Not included in this modpack due to its large filesize.
- [**Fixed Hands**](https://steamcommunity.com/app/658920/discussions/0/3362523432271321089/): Adds hands to some of the handless models.

## Recommended Modding Tools
- [**Mod Organizer 2 Plugin for Half-Life 2 VR**](https://www.nexusmods.com/halflife2/mods/35):  Allows for Skyrim style modding with Mod Organizer 2.  Removes the complexity of managing load order from "custom" folders.
- [**GCFScape**](https://nemstools.github.io/pages/GCFScape-Download.html): Used for decompressing VPK files.
- [**Gmad - Easy Addon Extractor**](https://www.moddb.com/mods/garrys-mod/downloads/gmad-easy-addon-extractor): Used for decompressing Garry's Mod addons.

## Compatibility Notes
- Black Mesa Source: Incompatible. Maps work in VR but NPCs do not load.
- Black Mesa: Incompatible. Crashes to the desktop.
- Research and Development: Incompatible. Mr. Whirly does not work.
- Entopy Zero: Incompatible. Frequent crashes to the desktop.
- HL2 MMod Improved Sounds: Incompatible. Broken sounds.
- Cinematic Mod 2013: Compatible.  Minor graphical glitches with reflections in the train station and Dr. Breen's office.
- Lost Coast: Compatible.
- Minerva: Compatible.
- Year Long Alarm: Compatible.
- Too Many Crates: Compatible.
- Nightmare Church: Compatible.
- Silent Hill Alchemilla Demo: Compatible.
- Silent Hill Alchemilla Full Version: Untested.  All maps load fine but may contain game breaking bugs.

## Changelog
See [Changelog](https://github.com/Ashok0/HL2VREssentials/blob/main/CHANGELOG.md)

## Credits
All credit for this mod pack goes to the following original creators:

*[Jay], [SU]- Zen, Eevah, A-06, A-Shift, Adam "Cargo Cult" Foster, Ahri Lover, Banahezzer, BazookaTooth, Benedict_Kapustin42, Boromir Artementaller, Chuck Wilson, CondiRoks, CrazyHairGuy, cubicApocalypse, Dead-Inside, DetonatedStorm, DrGordonFreeman96, Dynamic_, E1TUX, EddsNotDedd, Ellie, Empower1, Fakefactory, Foxidimi, GameSpy, General Ecchi, H3000, HL2MMod Team, Iiopn, Iretuerye, Isomeric Gamer, J.Barnes, Jeremiexp, Jerson Gaming, Jofoyo, jQueary, kalimando, MARK2580, Mbbote, MidnightDragons, Mine60000, MrBrightside, Munancho INC., MYSTIC, Nixel, nubblecakes, QueenPlague_Cure, Red Menace, Reverend V92, SamMaddie, Shadow_RUN, Sierra Foxtrot, Spoono, Stan_Jacobs, The Half-Life 2: Remade Assets Team (Retro Boy, Kube, MDDBULLDOGG, Exeros, hELLO, LVJohnFreeman, E Borge), themanclaw, TwoTime, TwoTime, Volkolak, Vort95, We Create Stuff, whynotll83, Wolfcl0ck, Wood_y, zDaken50, Zekeakers1*.

