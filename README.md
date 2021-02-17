# Zork source code, 1978 April
This repository contains the source code for an April 1978 version of [Zork](https://en.wikipedia.org/wiki/Zork), an interactive fiction game created at MIT by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [zork](../main/zork)
The files within this directory are the Zork specific files from the ```7005896.tap``` tape image file within the ```/tots/recovered/vol5/7005896``` directory of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

The files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be formatted like, ```~~~GSB; ACT1Z 1```, for example. All files have been placed into this artificial zork directory for organizational purposes.

The [```~~~gsb```](../main/zork/~~~gsb) directory contains the source code for the game. Some of the files are encrypted as found in the original tape image.

### [codemeta.json](../main/codemeta.json)
This file is metadata about the Zork files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [README.md](../main/README.md)
This file is the readme detailing the content and context for this repository.
### [tree.txt](../main/tree.txt)
A file tree listing the files in the [```zork```](../main/zork) directory showing the original file timestamps as extracted from the tape image.

## Preferred Citation
[filename], Zork source code, 1978 April, Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts. [swh:1:dir:9973a3b0378b7690d2ea46eca2a740b955b9fdbe](https://archive.softwareheritage.org/swh:1:dir:9973a3b0378b7690d2ea46eca2a740b955b9fdbe/)
## Rights
The ownership status of these files is not entirely clear. To the extent that MIT holds rights in these files, we are happy to support their broad public use.  Any questions about permissions should be directed to [permissions-lib@mit.edu](mailto:permissions-lib@mit.edu)
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
