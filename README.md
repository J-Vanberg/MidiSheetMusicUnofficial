# MidiSheetMusicUnofficial
Unofficial update to the MidiSheetMusic application authored by Madhav Vaidyanathan.

Changes by Justin Vandenberg (2019):
- Updated rendering to use double-buffering to resolve an issue where the logic thread accessed memory owned by the UI thread. This is the primary issue that caused the application to crash following Windows 10 updates
- Changing volume no longer changes system volume
- Volume level is remembered each time the application is opened
- Added toggle for "smooth" scrolling, due to this being a WinForms/GDI application, this is very CPU intensive!
