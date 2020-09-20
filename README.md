# Toontown Level Editor
NOTE: This is an archived repository containing the old source of the Toontown Level Editor, which is found in Panda3D 1.6.2.
It was made obsolete by the recent [Anesidora](https://github.com/satire6/Anesidora) leak release.  You should be better off
using the updated and more stable editor found through [Drew's Toontown Open Level Editor Project.](https://github.com/OpenToontownTools/TTOpenLevelEditor)

# This repository contains:
- Heavily modified Panda3D that can import "libotp" and "libtoontown" (contains DNA parser for the editor).
- All 56 style files (some are blank, but good enough) that are needed to load the editor.
- Working level editor :D

# How to use:
Place your phase files in the root of the level editor and run the "start-level-editor" batch file.
It should set everything up for you. Then use the in-game GUI to load a DNA file, and navigate to
the DNA file you wish to edit.

# More Information
NOTE: Due to the hacky nature of this project, I make no guarantees that it will work for you.
I have tested it on my system with success, and have uninstalled all copies of Panda3D on my
computer and have still been able to run it. It works fine for me, but not for some.

At the moment, this only works on Windows. It is using a Windows Panda3D with the Windows
DLL files needed. Eventually, I may work on a Linux build or even Mac.

As this is using Disney's DNA parser used for Toontown Online, some DNA files may or may not
work. From testing I have found that not all TTI .dna files work. This was mainly tested with
Toontown Online DNA files, which work perfectly.
