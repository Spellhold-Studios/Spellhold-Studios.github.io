EPIC ENDEAVOURS, enhanced WeiDU version
---------------------------------------

Introduction
------------
Here's what Elhoe wrote about his mod:
"This is a partial conversion for Baldurs Gate 2 in that you will play through a whole adventure without any links to the original game. The mod takes place in a generic fantasy world and is not set in any particular world or setting. Although some areas may appear familiar to the ones in BG2 - SOA, all areas you come across in this mod have been altered (the main reason why you will NO longer be able to start a normal BG2 - SOA game). Many of the creatures have also been altered. Gameplay-wise it will appear to be similar but it should be noted that some areas have a light-hearted and tongue-in-cheek flavour (if you are a movie or video game buff you may notice the references). This is not designed to be a hard-core role-playing experience so please understand this now before starting a new game. It was designed to provide gamers something different to the challenges found in Shadows of Amn."
More details can be found in the eeconv/Readmes/Readme_EE_Elhoe.txt file.

Japheth made the mod compatible with Throne of Bhaal some time ago. Please read the file eeconv/Readmes/Readme_EE_Japheth.txt for more information on the changes made by Japheth.

Configuration required for Windows
----------------------------------
Baldur's Gate II
Throne of Bhaal (optional)
Last applicable patch (2.0.23037 for BG II, 2.5.26498 for ToB)
BG2 Fixpack (optional)

Refrain from installing other mods for Baldur's Gate II. They are almost useless as Epic Endeavours completely replaces the original plot and other mods would almost all the time not be used during the game.

Configuration required for Mac OS X
-----------------------------------
Baldur's Gate II
Throne of Bhaal (optional)
Last applicable patch (1.1.2 for BG II, 2.1.2 for ToB)
BG2 Fixpack (optional)

Refrain from installing other mods for Baldur's Gate II. They are almost useless as Epic Endeavours completely replaces the original plot and other mods would almost all the time not be used during the game.

Installation for Windows
------------------------
- Extract the contents of the archive in the Baldur's Gate II directory (if you have multiple installations, choose the one you wish to use)
- Run the setup-eeconv.exe program from the Baldur's Gate II directory
- Choose your preferred language
- Install the whole mod by answering Y
- Wait until the installation is over (up to a few minutes depending on the computer)
Check that no error message was displayed at the end of the installation then close the text mode window by striking Enter.

Installation for Mac OS X
-------------------------
- Extract the contents of the archive in the Baldur's Gate II directory (if you have multiple installations, choose the one you wish to use)
- Run the setup-eeconv.command program from the Baldur's Gate II directory
  * Depending on the unarchiver or the Mac OS X version you have, you may face a problem with the execution permissions for the setup-eeconv.command file. If you can't run the program, please apply the following procedure (1):
  * Open the Terminal
  * Type the following command: "chmod +x ", with a final space but without pressing Enter for now
  * Drag the file setup-eeconv.command into the Terminal window
  * Then press Enter
  * Run the setup-eeconv.command program again: this time it shall start
- Choose your preferred language
- Install the whole mod by answering Y
- Wait until the installation is over (up to a few minutes depending on the computer)
Check that no error message was displayed at the end of the installation then close the terminal when it displays Logout.

(1) This procedure was inspired by the one provided in the FAQ section of the readme for the Angelo mod on Gibberlings 3 (http://www.gibberlings3.net/readmes/readme-angelo.html). The setup-eeconv.command script insures that setup-eeconv and other mod files have the proper permissions, in order to make things a bit simpler for the player.

How to play
-----------
Run Baldur's Gate II. If you installed Throne of Bhaal, choose the Shadows of Amn part.
You must start a new game for Epic Endeavours.

Bugs
----
Report any problem with the mod on the following forum, graciously hosted on Spellhold Studios:
http://forums.spellholdstudios.net/index.php?showforum=184
French users can also report bugs on "La Couronne de Cuivre" forum:
http://www.baldursgateworld.com/lacouronne/index.php?showforum=85
Thanks.

Uninstalling the mod for Windows
--------------------------------
- Run the setup-eeconv.exe program from the Baldur's Gate II directory
- Choose your preferred language
- Uninstall the whole mod by answering U
To completely remove the mod from the Baldur's Gate II directory, delete the eeconv directory and the files setup-eeconv.exe and setup-eeconv.debug.

Uninstalling the mod for Mac OS X
---------------------------------
- Run the setup-eeconv.command program from the Baldur's Gate II directory
- Choose your preferred language
- Uninstall the whole mod by answering U
To completely remove the mod from the Baldur's Gate II directory, delete the eeconv directory and the files setup-eeconv, setup-eeconv.command and setup-eeconv.debug.

A little piece of history
-------------------------
Elhoe is the author of the original mod, which only worked with Baldur's Gate II - Shadows of Amn at that time.
Japheth converted the mod to using WeiDU et changed it so that it could also work with Throne of Bhaal.
These two versions only exist in English.
When translating the mod into French, we decided to make a new packaging in order to ease translation and to allow translating into other languages. At the same time, we have tried to fix a few flaws of the previous versions. I (Isaya) dealt with this task, with the assistance of Graoumf (tests and bug identification) and Walar and Egrevyn (french translation and tests).

Read the files in the eeconv/Readmes directory for more information from Elhoe and Japheth.

Thanks
------
Credit goes to Elhoe for creating the mod in the first place, the first and one of the few that completely changed the game plot.
Thank you to Japheth for converting the mod using WeiDU, which allowed translating in a much simple way.
Thank you both for allowing this mod update to be released.
Thank you to Walar and Egrevyn for the french translation.
Thank you to Al17 and Alessandro "Ale" Rampinelli for the italian translation.
Thank you to Leonardo Watson for the german translation.
Thank you to Riklaunim and cuttooth for the polish translation.
Thank you to Eric P. for his interest in a Mac OS X version. Without him, it wouldn't exist.
Thank you to CLB and Steve for their beta-test and fixing of the Mac OS X version.
Many thanks to Graoumf for identifying missing texts, bugs and translation mistakes. Without you and your questions on how to publish the translation files, I would never have started working on this update of the mod so that it uses TRA files. Neither would I have tried fixing bugs.
Thanks to Westley Weimer (WeiDU), thebigg (BiggDU/WeiDU), Jon Olav Hauglid (Near Infinity), Avenger (DLTCEP), Dmitry Jemerov (Infinity Explorer) and Per Olofsson (TISpack) for their respective programs.
Finally, kudos to Bioware for creating the game and the game engine, which made all this possible.

History
-------
V1.0.0: Mod created by Elhoe
V1.0.0: Mod conversion by  Japheth
- decreased mod files size using compression programs
- conversion for installation with WeiDU and NSIS Installer
- added compatbility with Throne of Bhaal
V1.0.1: Last version published by Japheth
- fixed bug
V1.0.2: First enhanced version by Isaya
- converted files to using TRA files to ease translation
- recovered texts lost during WeiDU conversion (map notes, epilogue, journal entries)
- new epilogue added for female character
- fixed bug requiring to click twice on a mission scroll to get teleported (hopefully)
- fixed several small bugs (some NPC dialogs, store in the Cromwell's room selling infinite gem bags)
V1.0.3:
- italian translation and german translation added
- fixed bug where the group remained in pseudo-dragon form in mission 4
- fixed bug where the game remained in cutscene mode when coming back from a mission (hopefully)
- fixed bug where experience for clearing buildings wasn't given in mission 13 (hopefully)
- replaced icon for bolts that looked like arrows (now using +3 bolts icons from ToB)
- joignable spellcasters now have a selection of spells in memory (now you can actually use them during the first test)
V1.0.4:
- update to WeiDU v208
- addition of a separate Mac version of the mod. You shall thank Eric P. whose interest in the mod on Mac OS X pushed me to do it
- a few installation changes to accomodate Mac and Windows versions in a single TP2 file
- tried a new approach to solve the bug where the game remains in cutscene mode when starting a mission or in the middle of mission 3 (for some people, especially with Shadows of Amn only). Hopefully it will work not only on my computer...
- special thanks to CLB and madbob for bug reports and to CLB, Graoumf and Steve for their help and tests
V1.0.5:
- update to WeiDU v215, including several benefits (translated readme displayed as install time, version in WeiDU.log)
- polish translation added

Links
-----
Baldurdash (http://members.rogers.com/mrkevvy)
Bioware (http://www.bioware.com)
DLTCEP (http://forums.gibberlings3.net/index.php?showforum=137)
Infinity Explorer (http://infexp.sourceforge.net/ V0.80 or http://www.shsforums.net/index.php?showtopic=31285 V0.85)
Near Infinity (http://www.idi.ntnu.no/~joh/ni/)
TISpack (http://www.pocketplane.net/mambo/index.php?option=com_content&task=blogcategory&id=137&Itemid=96)
WeiDU (http://www.weidu.org)

Epic Endeavours 1.0.0, Elhoe version (http://america.iegmc.net/ee/)


Isaya
isaya_ie@hotmail.com
