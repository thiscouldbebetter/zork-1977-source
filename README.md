# Zork source code, 1977
This repository contains the source code for a 1977 version of [Zork](https://en.wikipedia.org/wiki/Zork), an interactive fiction game created at MIT by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling. The files are a part of the [Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection](https://archivesspace.mit.edu/repositories/2/resources/1265) at the MIT Libraries Department of Distinctive Collections (DDC).
## File organization and details
### [zork](../zork)
The files within this directory are the Zork specific files from the ```100068.tap``` tape image file within the ```/tots/recovered/vol7``` directory of the [ToTS collection](https://archivesspace.mit.edu/repositories/2/resources/1265). Most files are written in the MDL programming language and were originally created on a PDP-10 timeshare computer running the ITS operating system.

The files were extracted from the tape image using the [itstar program](https://github.com/PDP-10/itstar). The filenames have been adapted to Unix conventions, as per the itstar translation. The original filename syntax would be like, ```LCF; ACT1 37```, for example. All files have been placed into this artificial zork directory for organizational purposes.

The [```lcf```](../zork/lcf) and [```madman```](../zork/madman) directories contain the source code for the game.

The [```act2.27```](../zork/act.27) and [```dung.56```](../zork/dungz.56) files outside of the two main directories, are the decrypted versions of [```act2z.26```](../zork/lcf/) and [```dungz.56```](../zork/lcf/dungz.56). The decrypted versions were created recently and added to this directory by DDC digital archivist, Joe Carrano, for researcher ease of access.  

Files with extensions ```.nbin``` and ```.save``` are binary compiled files.

There was a ```zork.log``` file within the [```madman```](../zork/madman) directory that detailed who played Zork at the time of creation. DDC excluded this file from public release to protect the privacy of those named.

### [codemeta.json](../codemeta.json)
This file is metadata about the Zork files, using the [CodeMeta Project](https://codemeta.github.io/) schema.
### [README.md](../README.md)
This file, the readme detailing the content and context for this repository.
### [tree.txt](../tree.txt)
A file tree listing the files in the [```zork```](../zork) directory showing the original file timestamps as extracted from the tape image. 

## Preferred Citation
Massachusetts Institute of Technology, Tapes of Tech Square (ToTS) collection, MC-0741, Zork source code, 1977, [filename]. Massachusetts Institute of Technology, Department of Distinctive Collections, Cambridge, Massachusetts.
## Acknowledgements
Thanks to [Lars Brinkhoff](https://github.com/larsbrinkhoff) for help with identifying these files and with extracting them using the itstar program mentioned above.
