# GTee Clubhouse 0.1 Beta

First public beta — updated November 10, 2026. Release tag: `v0.1-beta`.

## What's included

GTee Clubhouse is a Windows launcher that brings your Classic and Modern GT games into one visual library, with tools to set up your games, configure your controls and manage your collection.

- **A visual game library:** Browse your collection with game artwork, filter installed games and launch from one place.
- **A welcome screen and guided tour:** Get familiar with Clubhouse and follow shortcuts to Classic or Modern game setup.
- **Modern game setup:** Add complete supported game folders and let Clubhouse check their files, prepare them for play and set up the required databases without a separate database-server installation.
- **Classic game support:** Use the integrated MAME runtime with your own matching ROMs and CHDs, plus picture presets, bezels and trackball settings.
- **Controls and display settings:** Configure keyboard, controller and supported mouse or USB trackball input, with shared and per-game options, fullscreen presentation and an optional second-screen marquee.
- **LaunchBox and Big Box integration:** Export game entries, artwork and launch commands for use with your cabinet frontend.
- **Database backup and maintenance:** Back up and restore Modern game databases, repair the application with the installer, and choose whether to keep your settings and databases when uninstalling.

## Corrections in this installer

This 0.1 Beta includes all ten new PGA 2023–2024 course entries, corrected mouse input and session exit, Arcade Collection hardware/intro updates, a fresh-install Classics ROM folder, actual default-key labels, and safer handling of settings files in use. It also includes the earlier Modern database/launch fixes and LIVE 2025 database backup/restore corrections. Run setup against an existing Beta folder to refresh its software while retaining settings and databases.

## Requirements and installation

Windows 10/11 x64. The app and its runtime dependencies are included. Supply complete matching original game folders, including required original database backups, or matching Classic ROMs/CHDs. Hardware compatibility remains edition-specific.

Download **GTee-Clubhouse-0.1-Beta-Course-Fix-Setup.exe**. Close Clubhouse and games, then select an empty folder for a fresh install or an existing Beta folder for repair/update. Alpha installations are not automatically migrated. Allow at least 8 GB free plus space for your games, caches, databases and backups; setup also uses temporary space on the Windows drive.

On exFAT, setup warns that temporary private sessions will use the Windows user's Local AppData. Persistent settings and saved databases remain in the selected installation folder.

The installer is not Windows Authenticode-signed and may show an unknown-publisher prompt. Use the official release asset and compare its SHA256 with **SHA256SUMS.txt**. Its internal software manifest is signed and verified by the bundled update engine.

Start **GTee Clubhouse.exe** after setup. Use the welcome screen's tour or setup shortcuts. Press **F11** for windowed/fullscreen mode. Existing saved display preferences are retained on update.

## Updating and uninstalling

Rerun setup to repair software or refresh an earlier Beta build. Later Beta installers update the same folder. Back up important databases before maintenance.

Uninstall from Windows Installed Apps. Choose **keep** to retain settings/databases for reinstallation, or **delete all Clubhouse data** to remove managed data, recovery backups and the installation's owned temporary cache. External original game folders are preserved.
