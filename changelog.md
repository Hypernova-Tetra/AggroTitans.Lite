# **Aggravated Bosses (Lite)** Open Playtest

* Current 7z Compressed Mod File Size: "1.37GB"



#### **β.01 - 2026.10.26**

* Re-Merged Add-on Sound Options in to the mod: Only "Original" and "Sound Edit" are available.
* Adjusted script files.
* Adjusted "SonicComboTweaks" to fix some actions not activating, and removed repeated lines of code.
* Fixed a small detail in Wyvern's Psycho QTE in where random pillars can be floating from other Wyvern animations in the QTE.
* A small adjustment of events between Gignato's SS transformation in Base Story and Battle Rush. Swapping what events play between them.
* A small adjustment of events in Wyvern's Boss Fight in Battle Rush: Removed a QTE after the Phase 2 scene. Moved the Laser QTE in Battle Rush to Master King.
* A small adjustment of events in Wyvern's Boss Fight in Battle Rush: A variant of the Psycho QTE plays where it restores a cut segment of Sonic and Wyvern clashing in a wide camera shot.
* A small adjustment of events in Wyvern's Boss Fight in Master King: Randomizes Laser QTE between 2 distinct animations.



#### **β.00 - 2026.10.04**

* Bumped version number for Open Playtest Release.
* Tweaked how much damage Wyvern takes during events.
* Code Tweaks/Optimization by Nowasu to make Frontiers run better.
* Supreme's unused Cinematic Grand Slam now does damage, although it won't visually show during the event. Thanks again Nowasu!
* Tweaked Knight's Phase 2 events to fix camera cuts when the scene plays in 60FPS after using "Uncap FPS in Cutscenes" code.
* Tweaked Knight's Zero Ring cutscenes to fade out before Sonic hits the screen.
* RagdollClash's "Disable FPS Limit in Cutscenes" code is a permanent feature for Aggro Titans to fix lingering issues with audio desync for certain cutscenes. Discovered by Nowasu.
* Reduced memory churn in the Titan fight logic. Optimized boss event code to remove repeated per-frame memory allocations.



## **Aggro-Titans**



#### **1.01 (Patch)**

* Fixed a crash when loading up the Supreme fight.
* Fixed an issue where Sonic got teleported to the wrong spot.
* Fixed a visual issue where the yellow Chaos Emerald shows up during Wyvern's Missile QTE outside of the failure scene.
* Adjusted BossRush.pac Titan HP values.



#### **1.00 (Release Update)**

* Added Server Link to update through HMM



#### **Initial Release**

* Restructured the Aggro Titans mod to use fewer custom code scripts.
* Reverted certain features in to Folder toggles instead of code toggles.
* Streamlined Supreme's QTEs.

