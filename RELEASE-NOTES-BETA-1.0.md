# GTee Clubhouse 0.1 Beta

First public beta — November 9, 2026. Release tag: `v0.1-beta`.

[Download and checksums](https://github.com/natemac/gtee-clubhouse-releases/releases/tag/v0.1-beta)

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

This corrected 0.1 Beta fixes Modern database setup and game launches in the Beta folder layout, failed-launch cleanup, PGA 2023–2024 game-file validation, and LIVE 2025 database backup/restore. If you installed the withdrawn build, close Clubhouse and games, then run this installer against the same Beta folder to repair its software while retaining settings and databases.

## Requirements and installation

Windows 10/11 x64. The app and its runtime dependencies are included. Supply complete matching original game folders, including required original database backups, or matching Classic ROMs/CHDs. Hardware compatibility remains edition-specific.

Download **GTee-Clubhouse-0.1-Beta-Launch-Fix-Setup.exe**. Close Clubhouse and games, then select an empty folder for a fresh install or an existing Beta folder for repair/update. Alpha installations are not automatically migrated. Allow at least 8 GB free plus space for your games, caches, databases and backups; setup also uses temporary space on the Windows drive.

On exFAT, setup warns that temporary private sessions will use the Windows user's Local AppData. Persistent settings and saved databases remain in the selected installation folder.

The installer is not Windows Authenticode-signed and may show an unknown-publisher prompt. Use the official release asset and compare its SHA256 with **SHA256SUMS.txt**. Its internal software manifest is signed and verified by the bundled update engine.

Start **GTee Clubhouse.exe** after setup. Use the welcome screen's tour or setup shortcuts. Press **F11** for windowed/fullscreen mode. Existing saved display preferences are retained on update.

## Updating and uninstalling

Rerun setup to repair software or refresh an earlier Beta build. Later Beta installers update the same folder. Back up important databases before maintenance.

Uninstall from Windows Installed Apps. Choose **keep** to retain settings/databases for reinstallation, or **delete all Clubhouse data** to remove managed data, recovery backups and the installation's owned temporary cache. External original game folders are preserved.

## Known issues and testing scope

- Some GT LIVE 2017 pacing issues remain unresolved; a scaled 1080p verification failure is still under investigation.
- Reported GT LIVE 2019/2020 foliage issues have not been reproduced on every affected setup.
- PGA 2027 Sawgrass water rendering remains a known issue.
- Compatibility, physical controls, performance and complete round/save behavior still need testing across hardware and editions. A catalog entry is not a guarantee for every game revision or PC.

The release checks cover packaged welcome/tour behavior, fresh install, repair, same-version refresh, later-version update, both uninstall choices, software integrity/privacy and installed startup readiness. They do not replace gameplay acceptance.

## Downloads and support

Use the installer for normal installation. **GTee-Clubhouse-0.1-Beta-Corresponding-Sources.zip** supplies third-party runtime sources and notices; it is not a portable app. See [third-party notices](THIRD-PARTY-NOTICES.md).

Read [SUPPORT.md](SUPPORT.md) for reporting issues. Keep game files, saved databases, account details and raw support archives out of public issues.
