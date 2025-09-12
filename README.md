# Diablo 3 Wings inside WoW 3.3.5a (Currently only on Mage Armor Buffs):

Hey I finally figured out how to swap my Mage Armor Buffs (Frost, Ice, Molten and Mage Armor) to display Diablo 3 wings instead. So it will display the Diablo 3 wings during the duration of those buffs.
﻿
Huge shoutout to Inico for porting these D3 Wings to WoW 3.3.5a. Took me a few days to figure out how to get them working for me though...\
All I could find was guides to add it to the server files, which I ofc don't have access to on Project-Epoch ^^ !

I had to sift through Project-Epoch's custom Patch files that didnt have list files to look for the "Spell.dbc" and "SpellVisualEffectName.dbc" to keep their custom spells intact.\
If Project-Epoch ever adds more spells they will probably not show up and I will need to update this again.

One side effect is that it also changes Paladin's Avenging Wrath wings spell effect to the Diablo 3 wings when they have it active, and every other Mage with any rank of Frost, Ice, or Mage buff on will have it on your screen as well.\
And your character will have the Paladin wings casting spell effect instead when casting the buff. I tried to do it via a custom spell in the DBC files but had to end up just using Avenging Wrath as a "Donor Spell" since it already places the wings pretty nicely.

# Installation:

Download the latest Release and extract it: https://github.com/RetroUnreal/D3-WINGS-for-WoW-3.3.5a/releases\
Place the patches inside your WoW Installation's Data folder (eg. C:\Program Files\Ascension Launcher\resources\epoch_live\Data)\
If you already have custom patches named "Patch-V.MPQ" OR "Patch-X.MPQ" installed then you will have to rename the patches you already have, or rename mine.\
But you must make sure they are in the same order, Patch-V.MPQ needs to be loaded before Patch-X.MPQ. (The patches load in alphabetical order.)

# README:

Check the "README - Apply to your own buff" file for a tutorial on how to attempt to add it to your own Class's Buffs.\
Check the "README - Change Wings" file for a tutorial on how to change the wings to a different style.
