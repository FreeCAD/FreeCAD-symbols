FreeCAD Symbols Library
=======================

This repository contains a library of SVG symbols to be used in FreeCAD.
Although they consist of simple SVG files, so they can also be imported
inside the 3D document, they are primarily made for use on Drawing pages.
 
It is maintained by the community of users of FreeCAD and is not part of 
the FreeCAD project, although it is made with the aim to bemused as a 
repository of parts by FreeCAD in the future.

Contributing to the library
---------------------------

If you are interested in contributing to this library, please ask for 
write access to this repository on this FreeCAD forum thread: 
http://forum.freecadweb.org/viewtopic.php?f=9&t=10641

Each SVG symbol should be correctly named, and placed into subdirectories 
by family or type.

License
-------

All symbols in this repository are licensed under CC-BY 3.0 
http://creativecommons.org/licenses/by/3.0/ . Each symbol is copyrighted 
by and should be attributed to its respective author(s). See commit 
details to find the authors of each symbol.

If you are uploading symbols to this repository, please make sure you 
are the author of the symbol, or otherwise that you have right to share 
it here under the CC-BY 3.0 license, and make sure the author is 
mentioned in the commit message.

Install
-------

The library is a simple container for SVG files. You can download it
anywhere and import its files in your FreeCAD projects. Inside the 
library, there is also a FreeCAD macro (SymbolsLibrary.FCMacro) that you 
can edit (you must change the path to your Library) and place in your 
FreeCAD macros folder. That macro creates a browser window inside 
FreeCAD, from which you can easily add the symbols to a selected Drawing
page (or, if none is selected, the first one found in the active 
document) by double-clicking them.
