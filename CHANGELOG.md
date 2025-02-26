# Changelog
v1.9.2.3 :
- Fixed files for mods managers.

v1.9.2.2 :
- Graphics, Aspect Ratio, FPS and Resolution rebuilt with the same strategy as Cheats.

v1.9.2.1 :
 - Cheats folder structure rebuilt for better reading legibility.

v1.9.2 : 
- Over 50 new cheats, for version 1.1.2 only.
- Updated Readme and Guide with new recommendations.

v1.9.1 : 
- Updated ChucksFeedAndSeed's DynamicFPS to 1.5.2.
Changelog of the mod : 
  -  added hitch detection similar to FPS++ (thanks to SomeRandomPeople)
  -  added game-speed smoothing, helps with jittery gliding animations, likely other animations too
  -  added sensitivity fixes when in conversations, sensitivity should now remain the same as 30FPS across all framerates
  -  extended conversation fix to innkeeper conversations too (likely other kinds still need sensitivity fixes too, let me know if you find any)
  -  changed max framerate limit from 288FPS to 145FPS, appears to help with shrine out-of-bounds glitches when using limiter disabled
  -  minor fix to framelimiter code, might help make 30FPS video playback smoother
  -  code reorganization, very minor tweaks (will try and setup a repo for it soon)

v1.9 :
- Now you can get mods specifically for your game version!
- Added @Socats s Install Guide PDF and @SpockBauru Recommended Settings page.
- Added Alerion's Xbox, Playstation & Steam Deck 'Controller UI Mods' - "Normal, white" versions.
- Added Sweetmini's 10**80**p FXAA On/Off, with FSR Disabler and DynRes Disabler (breaks AO with resolution scale above 1x on Yuzu).
- Updated Sweetmini's Improved LOD to v2.0 (improved performance compared to v1.0).
- Renamed MarethyuX's "Over 30fps Blackscreen Fix" to "UI Blackscreen Fix" since is needed even for 30fps if you use DynamicFPS mods.
- Cleaned outdated/broken mods.

v1.8.5 :
- Updated DynamicFPS++ (old FPS++) to version 0.5

v1.8.4 :
- Upgraded FPS++ to the new DynamicFPS++

v1.8.3 :
- Added 1.1.2 versions of SweetMini 1008p mod and Standalone FXAA. Please update if you were using the older version on 1.1.2.
- Updated folder structure, and removed old patches
- Updated Lazy Packs with most recent version of FPS++ and removed redundant patches.

v1.8.2 :
- Updated FPS++ to latest version, which adds Ultrahand Y axis fix and works on 1.1.2

v1.8.1 :
- Added 1.1.2 support for Time of Day cheat mods.  

v1.8 :
- Added a file in every mod folders called "Compatible versions.txt" and removed the versions in the mods name prefix.  
- Renamed two mods.  
- Added Ratio mods 1.1.2 support.  
- Added missing Ratio mods.

v1.7.5 :
- Updated remaining mods to 1.1.2 and 1.0.0, at this point pretty much everything important is covered.  

v1.7.4 : 
- Added Remove Lens Flare 1.1.1 and 1.1.2 - Credit: SweetMini.  

v1.7.3 : 
- Updated 1.1.2 static 30 fps and 20 fps.  
- Added Sky Island Fix for 1.1.1 and 1.1.2 - Credit: SweetMini.  
- Added LOD Improvement for 1.1.1 and 1.1.2 - Credit: SweetMini.  
- Updated Lazy Packs.  

v1.7.2 : 
- Added 1.1.2 support for OldManKain's 1080p and Disable Targeting DOF mods.  

v1.7.1 : 
- Added some Time of day cheats for 1.1.0.  

v1.7 : 
- Added 1.1.2 support for some mods. 

v1.6.6 : 
- Add 1.1.1 support for 1080p.  
- Added @OldManKain 1080p + Disable FXAA & FSR scaler patch (Still bugged AO for Yuzu above 1x scaling).  
- Updated 1.1.1 Lazy Packs.  

v1.6.5 : 
- Fixed 60fps static again

v1.6.4 : 
- Fixed 60fps static mod being duplicated from 20fps static mod.

v1.6.3 : 
- Updated Lazy packs to be compatible with update 1.1.1.
      Notes: still subject to change. Please reach out to @hoverbike1 (discord: hoverbike#8377) with feedback or issues.
- Static FPS mods updated to their latest versions.
- Renamed 1008P and 1026p mods to be less confusing hopefully.
 
v1.6.2 : 
fps++ Updated
- Number of frames used for averaging correlates to target framerate now (should make FPS++30 feel consistent with FPS++60)
- Some logic slightly simplified
- Avoid a potential divide by zero error (due to entropy)
- Add an extra safety check, where the dynamic timestep will be skipped if you hitch for an unusually long period of time
- Improve unlocked fps behavior
- Behavior while performance is improving is potentially smoother. Tell me how this feels!

v1.6.1 : 
- Replaced the 1008p FXAA on/off mods with FSR and DynRes disabled for a new method that should be safer and less stressful on the GPU.
- Deleted some more outdated/useless mods.
- Changed some file names to be clearer.

v1.6 : 
- Changed Mods organisation to be more streamlined
- Deleted some outdated/useless mods
- Changed the name formatting so mods are displayed by version correctly when opening the files.

v1.5.7 : 
- Replaced buggy FXAA disable mod with new version. Make sure to download the specific one for your game version.

v1.5.6 :
- Updated FPS++ to v0.4.3.1
- Added Cutscene-fix patches for game versions 1.0.0 and 1.1.1

v.1.5.5 :
- Updated LOD Patch to work with 1.1.1 
- Renamed to "Graphics - Disable LOD Quality Reduction"
- Removed "improve LOD" code that was proven as a placebo

v.1.5.4 :
- Added 30fps version of FPS++.

v.1.5.3 :
- Added new 1008p Mod that includes disable FSR and disable dynamic res built in, with a choice of FXAA on or off
- Renamed 1026p Mod to indicate a minor visual bug

v.1.5.2 : 
- Updated FPS++, now fix cinematics

v.1.5.1 : 
- Fixed Shadow mods names
- Fixed 60fps v4 mod don't working with 1.0.0 and 1.1.1

v.1.5 : 
- Renamed Potato Patches to Lazy Packs.
- Updated several mods to be compatible with 1.0.0 and 1.1.1.
- Updated Dynamic FPS.
- Added FPS+++ and DOF Remover.
- Added 1026p resolution mods.

v.1.4.5 : 
- Fixed some missings in new combo packs.  

v.1.4.4:
- New series of combo patches - "Lazy Packs"!
<br>A single patch containing all patches that you want 
<br>Simply choose a "lazy pack" with the desired resolution, framerate, and UI mod compatibility.  
<br>UI compatibility means that the patch is compatible with mods such as the Xbox UI mod above.  
<br>Otherwise, blackscreenfix is enabled in the non-compatible versions, for use with normal Nintendo UI.
- Updated guide! Click the fourth, bottom arrow in this release post to see

v1.4.3 : 
- Added Cheat - Durability (10x) Mod
- Updated "1.1.0 - FPS - 60fps v3 - BUGGY" with cutscene-fix compatibility fixes.
- Updated "Combo - 60fps v3 + DynamicFPS v1.3 - OLD" with cutscene-fix compatibility fixes.
- Updated "Combo - 60fps v3 + DynamicFPS v1.41 - NEW" with cutscene-fix compatibility fixes.
- Renamed "1.1.0 - FPS - 60fps v3 - BUGGY" to "1.1.0 - FPS - 60fps v3.7.2, now cutscene-fix compatible"
- Renamed "1.1.0 - Combo - 60fps v3 + DynamicFPS v1.31 - OLD" to "1.1.0 - Combo - 60fps v3 + DynamicFPS v1.31 + Cutscene-Fix - OLD"
- Renamed "1.1.0 - Combo - 60fps v3 + DynamicFPS v1.41 - NEW" to 1.1.0 - "Combo - 60fps v3.7.2 + DynamicFPS v1.41 + Cutscene-Fix - NEW"

v1.4.2 : 
- Added Combo - 120fps v3 + DynamicFPS v1.41 Mod
- Added Cutscene-Fix Mod
- Added Over 30FPS Blackscreen Fix Mod

v1.4.1 :
- Added Anisotropic Filtering Fix

v1.4 :
- Updated DynamicFPS to 1.41
- Splited FSR Downscaling and Sharpening remover into 2 different mods
- Updated FSR Sharpening remover
- Updated FXAA remover
- Updated LOD Reduction disabler
- Removed VisualFixes Combo, use splited mods instead
- Removed Potato Patch Combo that don't really increase performances, use splited mods instead
- Edited documentation about Shadow mods, please read

v1.3 :
- Updated DynamicFPS mod from 1.31 to 1.4.  

v1.2.3 :
- Added 360p Mod and Light pack and Unlimited FPS Combo mod, read the documentation to setup correctly.  

v1.2.2 :
- Added 30/60fps + Dynamic FPS Combo mods.  

v1.2.1 :
- Added 18:9 and 16:10 Experimental Ratio mods.  

v1.2 : 
- Experimental 21:9 and 32:9 mods, read informations on the main page : https://github.com/HolographicWings/TOTK-Mods-collection.  

v1.1 : 
- "Potato Patch" by Hoverbike, a collection of patches, is the only patch you need. Just enable it, along with the TOTK 1.1.0 update, and you're off to the races.  

v1.0 : 
- Main release.
