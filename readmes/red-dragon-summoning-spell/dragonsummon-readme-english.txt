* ================================================================= *
*                     Red Dragon Summoning Spell                    *
*                           version 2.1.0                           *
*                                                                   *
*     A mod for BGII: ToB (classical and EE games), BGT and EET     *
*                                                                   *
* ================================================================= *

Author: Coco_Pliz


CONTENT
=======

This mod adds a new 9th level spell scroll in Ribald's secret stock of items.

:warning: You must not use it everywhere because Red Dragon is a very big monster and can block your characters.

!!! And don't forget that using it too much will remove pleasure of the game !!!


CREDITS
=======

- Extremist: Proofread the original mod.
- kevmus: First WeiDU conversion.
- ilot: Italian translation.
- Gwendolyne: French translation.
- Lisandro: Spanish translation.
- Fess, Austin and aerie.ru team: Russian translation.
- AL|EN: Wrote Infinity Auto Packager tool which automatically provides Windows, Linux and Mac versions in the same archive file.
( https://forums.beamdog.com/discussion/78364/infinity-auto-packager-automatically-generate-and-adds-mod-packages-to-release-when-you-publish-it )


VERSION HISTORY
===============

Version 2.1.0 (August 30, 2020)
- Added Italian translation (by ilot).

Version 2.0.0 (June 12, 2020)
- Added "dragonsummon.ini" metadata file to support AL|EN's "Project Infinity".
- Renamed "Setup-DragonSummon.tp2" -> "dragonsummon.tp2" to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Added missing `HANDLE_CHARSETS` function to convert string entries for EE games.
- Added `REQUIRE_PREDICATE` conditions to avoid installing the mod in inaccurate games.
- Added component `DESIGNATED` number and "red_dragon_summoning_spell" `LABEL`.
- Removed `READLN` action and included into main component the option adding the scroll in Ribald's secret stock of items, to support AL|EN's "Project Infinity".
- Added native BG2:EE and EET compatibility.
- Added new spell and scroll icon.
- Fixed wrong spell level (9 - was 7).
- Wrote an accurate spell description.
- Added French translation (thanks Gwendolyne).
- Added Russian translation (thanks Fess and Austin).
- Added Spanish translation (thanks Lisandro).
- Updated translations (Gwendolyne and Austin).
- Updated and renamed readme file to "dragonsummon-readme-english.txt", then moved it into new "readme" folder.
- Removed useless "backup" folder.
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Lower cased files.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.
- Updated WeiDU installer to v246.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

Version 1 (May 25, 2009)
- Added an option that places the spell scroll in Ribald's store.
- WeiDU conversion by kevmus.

Original Version
- Initial release.
