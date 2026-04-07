# Automatic Council Tasks
A mod for Crusader Kings 3 (CK3) that automates the selection of counties for key councillor tasks, reducing micromanagement and improving gameplay flow.
It does this by automatically choosing another valid target for each task for the councillor to do once the last task is complete.

## Features
This mod automates the following council tasks:

### Court Chaplain: Convert Faith
Automatically selects the most optimal county to convert, prioritizing:

1. Liege’s capital
2. Counties in the liege’s realm
3. Capitals of direct vassals
4. Capitals of sub-vassals
5. Any remaining counties

Counties are chosen based on highest opinion first.

### Marshal: Increase Control
Automatically selects counties to increase control, using the same prioritization as above, with counties chosen by highest control.

### Steward: Promote Culture
Automatically selects counties to promote culture, using the same prioritization as above, with counties chosen by highest opinion.

### Vanilla Override Information
This mod overrides the vanilla council tasks for Promote Culture, Increase Control and Convert. It also adds new council task definitions and automation logic. 
All files are prefixed with ACT_ to avoid conflicts and ensure compatibility with other mods.

## Compatibility
Compatible with CK3 version 1.19.*
Should be compatible with most mods that do not override the same council task logic.

### Installation
Install via the Steam workshop and enable "Automatic Council Tasks" in the CK3 launcher
Or to manually install extract the mod to your CK3 mods folder.

## Credits
Created by Chickenboy
Based heavily on the Auto convert / promote / control mods by slaneche