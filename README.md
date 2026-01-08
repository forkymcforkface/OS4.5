# OS4.5: Unofficial Pi5 Edition

This repository contains the unofficial Pi5 version for OS4. The project focuses on kernel tweaks, performance optimization, and expanding hardware/emulator support. 

**Disclaimer:** This is an unofficial project and is not affiliated with the original OS4 developers.

## Project Overview

OS4.5 aims to improve the base OS4 experience through specific kernel modifications and userspace enhancements. Key goals include reducing audio latency, improving boot speeds, and adding support for additional consoles and arcade boards.

## Feature Status

### Current Release B19 (Stable)

**Hardware & Display**
* **CRT Support:** Native compatibility added for VGA888 (Lo-tech) .
* **Storage:** Added support for external USB drives formatted with ext4.
* **Diagnostics:** Added "Show FPS" toggle in Display Settings.

**ROM Access**
* **SD Update:** ROMs and Settings are now accessible directly via inserting SD into a PC.

**User Interface**
* **Auto Scanning:** Games and Systems lists update automatically; manual scanning is no longer required (still available for big system moves).
* **Navigation:** Added "Recently Played" list.
* **Management:** System renaming and sorting available directly within the UI.
* **Safety:** Added confirmation dialogs for removing Favorites or Recents.
* **Kodi:** UI language now syncs with the OS4 system language.

### Added to B20 (Next Release)

**Audio Subsystem**
* **Bug Fixes:** Resolved audio stuttering caused by background buffers.
* **Latency:** Adjustments for reduced audio latency.
* **Hotplug:** Support for USB audio DAC detection without reboot.

**Performance**
* **I/O Throughput:** Optimized RetroArch initialization and "Quit to OS4.5" sequences. Games now start and stop almost instantly.
* **Resource Management:** Optimized background CPU and memory usage for the main UI.

**System Configuration**
* **Core Management:** Added ability to add or change libretro cores.
* **Input:** Integrated `sdlcontrollerdb` for automatic controller mapping.
* **Privacy:** Analytics capture is now toggleable in system settings (Default: Off).

**Added Cores**
* Nintendo DS
* Sega Saturn
* CD-i


### Roadmap & Backlog

The following features are currently in early stages of development:

* **Compatibility:** Support for other ROM folder structures.
* **CRT Adjustments:** Software control for H/V Shift.
* **Theming:** Priority overrides for theme songs, expanded theme selection UI, and screensaver video support.
* **Tools:** Integrated image scraper and updated RetroAchievements.
* **Kiosk Mode:** "Favorites Only" restriction for public setups.
* **Updates:** Online OS4 updates without wiping SD.

## Coming Supported Systems

OS4.5 will add support for the following systems:

**Consoles & Handhelds**
* Atari 5200, Jaguar, Lynx
* Nintendo Virtual Boy, DS, GameCube, Wii
* Sega Saturn, Sega Channel
* Sony PSP
* Philips CD-i, Videopac / Odyssey
* Bandai Wonderswan / Color
* NEC PC-FX
* The 3DO Company Opera 3DO
* SNK NeoGeo
* MAME2003
* TIC-80 (Nesbox)
* BennuGD
* more to come!

## Feedback and Issues

Please use the [Issues] tab to report bugs or request features. Before submitting a new request, please search existing issues to avoid duplicates.
