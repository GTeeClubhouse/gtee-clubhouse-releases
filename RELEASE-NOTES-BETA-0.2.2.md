# GTee Clubhouse 0.2.2 Beta

An update to 0.2.1 Beta that restores the 3D grass in the rough on six games. Everything else is unchanged from 0.2.1.

## Disclaimer

GTee Clubhouse is a launcher for legally owned backup copies of your own software and games. No Incredible Technologies (IT) game software, game source code, or game data is distributed with this launcher, and no GT game source code is used to build it. We do not provide any games or game data. All backups are supplied by the user and must correspond to software and games they legally own; users are responsible for ensuring they have the right to use their backups.

## Hardware and game requirements

- **Windows 10/11 x64 and an NVIDIA GPU are required. AMD and Intel graphics are not supported in this release.**
- Allow at least 8 GB free for Clubhouse, plus space for your game files, Play Cache, databases and backups. Setup also uses temporary space on the Windows drive.
- Supply complete, supported Modern game folders with their matching original database backups and supporting files. A lone executable is insufficient.
- Classics require your legally owned backups from the **MAME 0.289 ROM set**, with matching CHDs and required parent/BIOS files. Keep ROM ZIPs zipped.

## Changes in 0.2.2

- **3D grass in the rough is back** in LIVE 2025 Nighthawk, LIVE TITAN 2025, LIVE TITAN 2026, PGA TOUR 2025 and PGA TOUR 2026. These games showed flat grass because of a mistake in the games' own grass setup, which the game makers corrected in PGA TOUR 2027. Clubhouse now applies the same correction while these games run. Your game files are not changed.
- **LIVE TITAN 2023-2024** now turns the game's grass on at the Medium, High and Very High graphics levels. If you changed this game's graphics settings yourself, your settings are kept.

0.2.2 includes everything in 0.2.1: [0.2.1 release notes](https://github.com/GTeeClubhouse/gtee-clubhouse-releases/releases/tag/v0.2.1-beta).

## Install or update

1. Download **GTee-Clubhouse-0.2.2-Beta-Setup.exe**.
2. Close Clubhouse and all games. To update from 0.1, 0.2 or 0.2.1 Beta, choose the same installation folder. For a fresh installation, choose an empty, writable folder.
3. Open **GTee Clubhouse.exe**. Use the welcome screen's **Guided Tour**, **Classic** or **Modern** shortcuts.

The required runtimes are bundled. Updates and repair preserve settings and saved databases. On exFAT, temporary private sessions use Local AppData on the Windows drive; saved settings and databases remain in your chosen installation folder. Alpha installations are not migrated.

The installer is not Windows Authenticode-signed and may show an unknown-publisher prompt.

To repair, rerun this installer against the same folder. To uninstall, use **Windows Settings > Apps > Installed apps**, then choose whether to retain or remove Clubhouse data. Original game folders outside the installation are preserved.
