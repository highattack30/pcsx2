# PCSX2

PCSX2 is an open-source PlayStation 2 (AKA PS2) emulator. Its purpose is to emulate the PS2 hardware, using a combination of MIPS CPU [Interpreters](http://en.wikipedia.org/wiki/Interpreter_\(computing\)), [Recompilers](http://en.wikipedia.org/wiki/Dynamic_recompilation) and a [Virtual Machine](http://en.wikipedia.org/wiki/Virtual_machine) which manages hardware states and PS2 system memory. This allows you to play PS2 games on your PC, with many additional features and benefits.

# Project Details

The PCSX2 project has been running for more than ten years. Once only able to run a few public domain demos, newer versions enable many games to work at full speed, including popular titles such as Final Fantasy X or Devil May Cry 3. Visit the [PCSX2 homepage](http://pcsx2.net) to check the latest compatibility status of games (with more than 2000 titles tested), or ask for help in the [official forums](http://forums.pcsx2.net/).

The latest officially released stable version is version 1.4.0.

Installers and binaries for both Windows and Linux are available from [our website](http://pcsx2.net/download.html).

Development builds are also available from [our website](http://pcsx2.net/download/development/git.html).

![KOF 2002](https://dl.dropboxusercontent.com/u/743491/PCSX2/KoF2002.jpg "KOF 2002")
![Final Fantasy XII](https://dl.dropboxusercontent.com/u/743491/PCSX2/FinalFantasyXII.jpg "Final Fantasy XII")
![Odin Sphere](https://dl.dropboxusercontent.com/u/743491/PCSX2/OdinSphere.jpg "Odin Sphere")

# System Requirements

## Minimum
* OS: Windows Vista SP2 or newer or GNU/Linux (32-bit or 64-bit)
* CPU: Any that supports SSE2 (Pentium 4 and up, Athlon64 and up)
* GPU: DirectX 10 GPU or better
* RAM: 2GB or more

## Recommended
* OS: Windows 7/8/8.1/10 (64-bit) or GNU/Linux (64-bit)
* CPU: Intel Haswell (or AMD equivalent) @ 3.2GHz or better
* GPU: DirectX 11 GPU or greater
* RAM: 4GB or more

## Notes

- You need the [Visual C++ 2015 x86 Redistributables](https://www.microsoft.com/en-us/download/details.aspx?id=48145) for this version to work.

- PCSX2 1.4.0 is the last version to support Windows XP. Windows XP is no longer getting updates (including security-related updates), and graphics drivers for Windows XP are older and no longer maintained.

- Make sure to update your operating system, drivers, and DirectX (if applicable) to ensure you have the best experience possible. Having a newer GPU is also recommended so you have the latest supported drivers.

- Because of copyright issues, and the complexity of trying to work around it, you need a BIOS dump extracted from a legitimately-owned PS2 console to use the emulator. For more information about the BIOS and how to get it from your console, visit [this page](http://pcsx2.net/config-guide/official-english-pcsx2-configuration-guide.html#Bios).

- PCSX2 mainly takes advantage of 2 CPU cores. As of [this commit](https://github.com/PCSX2/pcsx2/commit/ac9bf45) PCSX2 can now take advantage of more than 2 cores using the MTVU speedhack. This can be a significant speedup on CPUs with 3+ cores, however on GS-limited games (or on CPUs with less than 2 cores) it may be a slowdown.

![Pro Evo 2009](https://dl.dropboxusercontent.com/u/743491/PCSX2/ProEvo2009.jpg "Pro Evo 2009")
![Megaman X8](https://dl.dropboxusercontent.com/u/743491/PCSX2/MegamanX8.jpg "Megaman X8") ![TOTA](https://dl.dropboxusercontent.com/u/743491/PCSX2/TOTA.jpg "TOTA")

# Quality Assurance

**Build** | **Status**
--------|--------
Linux   | [![Travis Build Status](https://travis-ci.org/PCSX2/pcsx2.svg?branch=master)](https://travis-ci.org/PCSX2/pcsx2)
Windows  | [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/b67odm0dd506co78/branch/master?svg=true)](https://ci.appveyor.com/project/gregory38/pcsx2/branch/master)
Coverity| [![Coverity Scan Build Status](https://scan.coverity.com/projects/6310/badge.svg)](https://scan.coverity.com/projects/6310)
