# WoW-MoP-5.4.8-Mute
**Mute specific sounds in World of Warcraft - Mists of Pandaria 5.4.8 client.**

Packages of files are just (empty) data files and are non-intrusive and easily 
removed. 

There may be different packages for different options. There should be 
no need to download multiple packages since they would pointlessly partly 
overwrite each other. Just choose a package and you're good to go.

## Install
Extract the contents of a zip file into your World of Warcraft "Data" subdirectory.

## How It Works
1. WoW first looks up the location of individual data files, like sounds, at specific locations *before* it looks them up in the listfiles of its MPQ data archives.
2. This means you can easily customize individual files by placing a file at those locations.
3. By placing an empty file at sound file locations, WoW attempts to play empty sounds and therefore effectively mutes that sound.
4. You can further customize what sounds you wish to hear by just deleting specific empty files, e.g. `Sound\creature\GoblinFemaleZanyNPC\GoblinFemaleZanyNPCGreeting01.ogg`.

## Un-install
Simply delete the extracted contents of the zip file from your "Data" subdirectory.