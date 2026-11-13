# GTee Clubhouse 0.2 Beta

Organize and launch your own Classic and Modern GT collection from one visual library. This Windows beta includes the setup, controls, artwork, database management and LaunchBox integration from 0.1, with clearer setup feedback and expanded support reports.

## Disclaimer

GTee Clubhouse is a launcher for legally owned backup copies of your own software and games. No Incredible Technologies (IT) game software, game source code, or game data is distributed with this launcher, and no GT game source code is used to build it. We do not provide any games or game data. All backups are supplied by the user and must correspond to software and games they legally own; users are responsible for ensuring they have the right to use their backups.

## Hardware and game requirements

- **Windows 10/11 x64 and an NVIDIA GPU are required. AMD and Intel graphics are not supported in this release.**
- Allow at least 8 GB free for Clubhouse, plus space for your game files, Play Cache, databases and backups. Setup also uses temporary space on the Windows drive.
- Supply complete, supported Modern game folders with their matching original database backups and supporting files. A lone executable is insufficient.
- Classics require your legally owned backups from the **MAME 0.289 ROM set**, with matching CHDs and required parent/BIOS files. Keep ROM ZIPs zipped.

## Changes in 0.2

- Expanded support reports include actual OpenGL renderer information, installed graphics-driver inventory, system and display details, and more log history. Reports retain detected failure context and identify omitted evidence.
- Database and permissions failures provide more useful diagnostic detail, including the failing setup step and original error. A corrected cleanup path prevents a secondary failure from hiding the initial problem.
- Incompatible or incomplete Modern game imports give clearer file-size and matching-version guidance.
- Classic ROM status now names the mismatched file and the required MAME 0.289 ROM set.
- Launch diagnostics better distinguish pending-session problems, and support reports identify the packaged release consistently.

## Install or update

1. Download **GTee-Clubhouse-0.2-Beta-Setup.exe**.
2. Close Clubhouse and all games. For an update from 0.1 Beta, choose the same installation folder. For a fresh installation, choose an empty, writable folder.
3. Open **GTee Clubhouse.exe**. Use the welcome screen's **Guided Tour**, **Classic** or **Modern** shortcuts.

The required runtimes are bundled. Updates and repair preserve settings and saved databases. On exFAT, temporary private sessions use Local AppData on the Windows drive; saved settings and databases remain in your chosen installation folder. Alpha installations are not migrated.

The installer is not Windows Authenticode-signed and may show an unknown-publisher prompt.

To repair, rerun this installer against the same folder. To uninstall, use **Windows Settings > Apps > Installed apps**, then choose whether to retain or remove Clubhouse data. Original game folders outside the installation are preserved.
