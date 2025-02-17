Promod Reflex 1.1b - README
By Philipe Jones


This mod is an expansion on Promod LIVE V2.20 EU
http://www.codpromod.com

Please refer to readmepml220.txt for information regarding promod in general.
This readme will ONLY cover modifications made by Promod Reflex.

Patch history for Promod Reflex will be kept up to date on its github repository
https://github.com/PhilipeJones/promod-reflex-

Installation:
This file should be distributed in a zipped package that contains the mod files and "compile.bat"
-Unzip the folder into your CoD4 mods directory
-Run "compile.bat"
-A folder titled pml220-DallasReflex should appear in your CoD4 mods directory, if so the mod has been successfully installed


VERSION HISTORY


_Promod Reflex version 1.1b:


New Skins!
-Replaced the Marines skin with Woodland SAS for better visibility on the standard Promod map pool.

New Guns!
-Skorpion and Barrett added to the Create-a-Class in-game menu in their respective classes!

-Drastically changed MP44 stats to resemble its CoD2 iteration! (Now with one-taps!!!)
-Added P90 as a secret gun, with the stats of the CoD2 Thompson!


After playtesting, fixed many oversights on weapon statistics:

-Nerfed mini-uzi reflex sight LMAOOOO
-Fixed M16 quick switch timing to be in line with normal and suppressed versions
-Removed headbob from all Skorpion variants and muzzleflash from silenced version


Balance Changes:

Skorpion:
-Max damage and min damage ranges both reduced (200 --> 150 and 400 --> 350 respectively)

Barrett:
-Movespeed further reduced from 0.9 --> 0.85
-Quickraisetime increased to 1.25
-Raisetime increased to 1.5
-ADSTransInTime increased from 0.3 --> 0.35

Skorpion felt a little bit too strong up close so hopefully this will reign it in a bit. 
As well, Barrett was seeming to be far better than the standard scopes, so I tried to change it to feel a bit clunkier so that choosing it is more of a tradeoff between damage and freedom with movement.


Future plans to add a "scout" type of sniper, likely drastically reworking Dragunov or M21 for this.
I also would like to rework the G36 in some way that makes it distinct from the M4 Carbine and other weaker ARs.
Maybe making it a burst gun? Giving it an ACOG? Maybe both?
Need to go back through all reflex guns' stats and make sure they perfectly match their normal counterparts, so that all weapons in the mod are consistent amongst themselves.
I'm also still interested in adding red dots to shotguns or acogs to snipers, but I think that is going to be a little more difficult than I thought at first.
Could also add final killcam to the mod in the future, that would be poggers.


_Promod Reflex version 1.1a:
Tweaking weapon values to be in-line with their no attachment equivalents. 
Mod should fulfill the original mission of having fully playable red dots on weapons in CoD4 PromodLIVE 2.20.

In the future, red dots may be taken off some weapons for balance and it's even possible that other attachments like ACOGs, grips, shotgun red dots could be added to the mod. 
Right now I'm working on adding back some of the stock guns that were removed from the game by promod. The Skorpion and the Barrett are the first two I have been looking into and have them both working in promod, but not entirely playable in this version of the mod. 
Now trying to figure out how to balance them in the promod sandbox before finishing them.

(Secret Weapons???)
Barrett Notes-
Decreased magazine size from 10 --> 5
Increased firetime from .05 --> .925 (higher number = fires slower)
Testing heavily increased damage and recoil
Decreased movement speed from 1 --> .9
Increased reload cancel timing from 2.8 --> 3.8

Skorpion Notes-
Max dmg decreased from 50 --> 45
Min dmg decreased from 20 --> 17
Reload cancel time from 2.2 sec --> 1.7 sec
(maybe adjust limb damage if still too good?)

Farther future goals of adding sights used in campaign but not multiplayer, and the special M4 Carbine varieties and other unique weapons from the campaign that are also not present in multiplayer.


_Promod Reflex version 1.0a:
all .gsc files were modified to include reflex, as well as silencer and "none" for assault and spec ops weapon attachments options.
cac_ingame.inc changed to include options for selecting reflex/red dot sight in promod create a class.