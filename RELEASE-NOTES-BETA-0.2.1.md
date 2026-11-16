# GTee Clubhouse 0.2.1 Beta

An update to 0.2 Beta. The 2019 and later LIVE games run faster on mid-range CPUs, and three problems that stopped people from adding or playing games are fixed.

## Disclaimer

GTee Clubhouse is a launcher for legally owned backup copies of your own software and games. No Incredible Technologies (IT) game software, game source code, or game data is distributed with this launcher, and no GT game source code is used to build it. We do not provide any games or game data. All backups are supplied by the user and must correspond to software and games they legally own; users are responsible for ensuring they have the right to use their backups.

## Hardware and game requirements

- **Windows 10/11 x64 and an NVIDIA GPU are required. AMD and Intel graphics are not supported in this release.**
- Allow at least 8 GB free for Clubhouse, plus space for your game files, Play Cache, databases and backups. Setup also uses temporary space on the Windows drive.
- Supply complete, supported Modern game folders with their matching original database backups and supporting files. A lone executable is insufficient.
- Classics require your legally owned backups from the **MAME 0.289 ROM set**, with matching CHDs and required parent/BIOS files. Keep ROM ZIPs zipped.

## Changes in 0.2.1

- **Less stutter in LIVE Nighthawk and Titan games.** These games are limited by the speed of one CPU core. Clubhouse now does much less work on that core for every frame. On a test PC with a Core i7-6700K, LIVE 2026 Titan went from about 16 to about 25 frames per second at the first tee. PCs that already ran these games at full speed will not look different. Older CPUs can still fall short of full speed on the newest Titan games; Graphics Quality Low or Very Low helps further. PGA TOUR games are not changed by this.
- **"Database setup failed" when adding a game.** On PCs whose Windows time zone the bundled database tool does not recognise, adding a Modern game failed, and the game then could not be added again. The warning is now treated as the harmless notice it is. A game left half-added by the earlier failure is set aside (kept, not deleted) and set up again the next time you press Play or add it.
- **Play returned to the menu on some PCs.** Clubhouse now sets the permissions of its private session folder directly, which works on PCs where the previous method left extra permission entries behind.
- **"A previous game session needs attention" could not be cleared.** If a game took a long time to close, Clubhouse could stay locked, and Stop background tasks, restarting Windows and updating did not help. Clubhouse now waits for the game to finish closing. If an installation is already stuck this way, open **Session & diagnostics** and use **Clear stuck session**. This installer can also update an installation that is stuck this way.
- **A game that failed to set up for other reasons can be added again.** More kinds of leftovers from an interrupted first setup are now set aside (kept, not deleted) so the game can be set up fresh.
- **Clear message on PCs without an NVIDIA graphics card.** Play now explains that an NVIDIA card is required instead of failing without a reason. On PCs with two graphics chips, a game that starts on the wrong one is closed with instructions for choosing the NVIDIA card.
- Support reports give more detail when the private folder permissions cannot be set, and record when a fullscreen game window is minimised or did not fill the screen.

## Install or update

1. Download **GTee-Clubhouse-0.2.1-Beta-Setup.exe**.
2. Close Clubhouse and all games. To update from 0.1 or 0.2 Beta, choose the same installation folder. For a fresh installation, choose an empty, writable folder.
3. Open **GTee Clubhouse.exe**. Use the welcome screen's **Guided Tour**, **Classic** or **Modern** shortcuts.

The required runtimes are bundled. Updates and repair preserve settings and saved databases. On exFAT, temporary private sessions use Local AppData on the Windows drive; saved settings and databases remain in your chosen installation folder. Alpha installations are not migrated.

The installer is not Windows Authenticode-signed and may show an unknown-publisher prompt.

To repair, rerun this installer against the same folder. To uninstall, use **Windows Settings > Apps > Installed apps**, then choose whether to retain or remove Clubhouse data. Original game folders outside the installation are preserved.
