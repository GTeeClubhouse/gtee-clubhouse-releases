# GTee Clubhouse Beta 1.0

First public beta — November 9, 2026. Release tag: `v1.0.0-beta.1`; application version: `1.0.0`.

[Download and checksums](https://github.com/natemac/gtee-clubhouse-releases/releases/tag/v1.0.0-beta.1)

## What's included

- New welcome screen with a 35-step guided tour and Classic/Modern setup shortcuts. The tour can be reopened from General app settings.
- Fullscreen by default on fresh installations, controller navigation, shared and per-game controls, graphics options, artwork and optional second-screen marquee.
- Integrated Classic runtime, an existing-ROM-folder selector and Modern content/database setup.
- In-app support-report upload with confirmation and a local ZIP fallback.
- Current 4K scaling, GT LIVE 2020 startup-path, GT LIVE 2019/2020 graphics-table and GT LIVE 2017 safe-shadow corrections.
- Corrected PGA 2023–2024 validation metadata for the repaired game folder, including 29 added shader entries and 11 corrected entries. Select the repaired folder in Games & Databases; the installer does not patch or provide game files.
- Installer preparation progress, repair, later-version updates and an uninstall choice to keep settings/databases or delete Clubhouse data.

## Requirements and installation

Windows 10/11 x64. The app and its runtime dependencies are included. Supply complete matching original game folders, including required original database backups, or matching Classic ROMs/CHDs. Hardware compatibility remains edition-specific.

Download **GTee-Clubhouse-Beta-1.0-Setup.exe**. Close Clubhouse and games, then select an empty folder for a fresh install or an existing Beta folder for repair/update. Alpha installations are not automatically migrated. Allow at least 8 GB free plus space for your games, caches, databases and backups; setup also uses temporary space on the Windows drive.

On exFAT, setup warns that temporary private sessions will use the Windows user's Local AppData. Persistent settings and saved databases remain in the selected installation folder.

The installer is not Windows Authenticode-signed and may show an unknown-publisher prompt. Use the official release asset and compare its SHA256 with **SHA256SUMS.txt**. Its internal software manifest is signed and verified by the bundled update engine.

Start **GTee Clubhouse.exe** after setup. Use the welcome screen's tour or setup shortcuts. Press **F11** for windowed/fullscreen mode. Existing saved display preferences are retained on update.

## Updating and uninstalling

Rerun setup to repair software or refresh an earlier 1.0 build. Later Beta installers update the same folder. Back up important databases before maintenance.

Uninstall from Windows Installed Apps. Choose **keep** to retain settings/databases for reinstallation, or **delete all Clubhouse data** to remove managed data, recovery backups and the installation's owned temporary cache. External original game folders are preserved.

## Known issues and testing scope

- Some GT LIVE 2017 pacing issues remain unresolved; a scaled 1080p verification failure is still under investigation.
- Reported GT LIVE 2019/2020 foliage issues have not been reproduced on every affected setup.
- PGA 2027 Sawgrass water rendering remains a known issue.
- Compatibility, physical controls, performance and complete round/save behavior still need testing across hardware and editions. A catalog entry is not a guarantee for every game revision or PC.

The release checks cover packaged welcome/tour behavior, fresh install, repair, same-version refresh, later-version update, both uninstall choices, software integrity/privacy and installed startup readiness. They do not replace gameplay acceptance.

## Downloads and support

Use the installer for normal installation. **GTee-Clubhouse-Beta-1.0-Corresponding-Sources.zip** supplies third-party runtime sources and notices; it is not a portable app. See [third-party notices](THIRD-PARTY-NOTICES.md).

Read [SUPPORT.md](SUPPORT.md) for reporting issues. Keep game files, saved databases, account details and raw support archives out of public issues.
