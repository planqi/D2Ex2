D2Ex2
=====

A Diablo II 1.11b/1.13d improvement mod. Been used on realm.angrenost.org.

Features
--------
- Completely reworked party screen, can handle up to 64 players
- Fixed some vanilla bugs, random crashes etc
- Expanded Sounds.Txt limit to 4954, you can easily increase to more (D2Ex2.cpp's patches)
- Reduced TCP/IP / Open BNet join time.
- Lagometer (ported from Q3 source :D)
- Reworked ESC-menu, get rid of .dc6 files. Now creating your own menu is easy as pie (ExOptions.cpp)
- Created a lot of custom controls, you can use them to create your GUI (ie new party screen)
- Supports both 1.11b & 1.13d (set version in stdafx.h)
- ExBuffs module let see you states, auras and remaining time

Installation
-------------
Compile Release build using Visual Studio 2008+, (2012 is supported if you select xp vcl libs in project setup)
Visual Studio 2013 is not supported because it's messing with function order and pointers are not defined correctly even without optimizations.
Copy everything to Diablo II directory, D2Win.dll is a loader for D2Ex2.dll, modded D2Gfx.dll allows you to multi window on 1.13d

Thanks to
----------
MrMag-WS for testing platform
RoluS/Zurek/InteR for some great ideas
Phrozen Keep forums for great source of informations