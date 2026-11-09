<p align="center">
  <a href="https://ko-fi.com/N4N32AC2LY"><img src="docs/images/support-ko-fi.svg" alt="Support me on Ko-fi" width="220" height="42"></a>
</p>

<p align="center">
  <img src="docs/images/gtee-clubhouse-logo.png" alt="GTee Clubhouse" width="600">
</p>

<h1 align="center">GTee Clubhouse</h1>

<p align="center"><strong>Your GT collection, from 1989 to 2027. One Windows launcher. Zero manual database setup.</strong></p>

<p align="center">
  <a href="https://github.com/natemac/gtee-clubhouse-releases/releases">Releases</a> &nbsp; | &nbsp;
  <a href="#getting-started">Setup guide</a> &nbsp; | &nbsp;
  <a href="SUPPORT.md">Support</a> &nbsp; | &nbsp;
  <a href="https://github.com/natemac/gtee-clubhouse-releases/issues">Report an issue</a>
</p>

GTee Clubhouse brings decades of arcade golf into one visual library. Browse your games, add supported originals, configure your controls, and launch from a desktop or cabinet. From the original GT Golf through GT Fore!, GT LIVE Nighthawk and GT LIVE Titan hardware, and more, Clubhouse brings game setup and everyday management into the same interface.

![GTee Clubhouse logo, main menu, and feature highlights over a tropical golf course](docs/images/github-social-preview-v3.jpg)

## Download and release status

**Beta 1.0 is the first public beta for Windows 10/11 x64.**

[Download the Beta 1.0 installer](https://github.com/natemac/gtee-clubhouse-releases/releases/download/v1.0.0-beta.1/GTee-Clubhouse-Beta-1.0-Setup.exe) · [Release notes, checksum and source archive](https://github.com/natemac/gtee-clubhouse-releases/releases/tag/v1.0.0-beta.1)

Includes the new welcome screen and guided tour, Classic and Modern setup shortcuts, and the latest runtime and game-file validation fixes. Games, ROMs, CHDs and original databases are supplied separately. Read the [Beta 1.0 requirements and known issues](RELEASE-NOTES-BETA-1.0.md) before installing.

The features below describe the current project. Follow the notes supplied with your installed version for its exact capabilities and compatibility.

<details>
<summary>View the Beta 1.0 welcome screen</summary>

![Beta 1.0 welcome screen with guided tour and Classic and Modern setup shortcuts](docs/images/clubhouse-welcome.png)

</details>

## Main features

| Feature | What you can do |
| --- | --- |
| One visual library | Browse Classic and Modern editions with game logos, scenery, artwork, sorting, and installed-game filtering. |
| Welcome and guided tour | Start with Classic or Modern setup shortcuts, or follow a 35-step tour of the app. Reopen the tour from General app settings. |
| Zero manual database setup | Let Clubhouse prepare supported Modern games and create their private databases during game setup. No separate database-server installation or manual SQL configuration is needed for the normal setup flow. |
| Add multiple games | Select complete game folders individually, select several at once, or scan a parent folder for supported editions. |
| Classic games built in | Use the integrated MAME setup for the Classic library, with content checks, bezels, CRT effects, and other picture presets. Supply your own matching ROMs and CHDs. |
| Controls for your setup | Configure keyboard, Xbox/XInput, and DirectInput button mappings, plus supported mouse or USB trackball input. Navigate the launcher with a controller. |
| Global and per-game settings | Set shared defaults, then override supported options for individual editions. |
| Graphics quality controls | Choose Very Low through Very High presets and supported Advanced adjustments for eligible Modern editions. |
| Cabinet presentation | Use fullscreen display, customizable artwork and accent colors, and an optional marquee on a second display. |
| Auto-export to LaunchBox | Export all or installed games with supplied metadata, artwork assets, and ready-to-use headless launch commands. Clubhouse creates the entries and organizes them in LaunchBox for use with LaunchBox and Big Box. |
| Backup and recovery | Back up and restore Modern databases individually or in batches, with recovery checks built into the workflow. |
| Built-in diagnostics | Review setup readiness, check content, stop a background session, and prepare a support report from the app. |

## A library spanning 1989–2027

Clubhouse brings the full span of GT history into one place. Its catalog covers these families:

| Family | Editions |
| --- | --- |
| Early Classics | GT Golf (1989 trackball edition), GT Golf II, GT 3D Golf, GT '97, GT '98, GT '99, GT 2K, and GT Classic |
| Fore! | GT Fore!, Fore! 2002, Fore! 2003, Fore! 2004 Extra, Fore! 2005 Extra, and Fore! Complete |
| GT LIVE Nighthawk | GT LIVE Nighthawk 2006–2025 |
| GT LIVE Titan | GT LIVE Titan 2021, 2022, 2023–2024, 2025, and 2026 |
| Additional games | More supported games available through 2027. See the release notes for details. |

Exact game versions matter. A catalog entry does not mean every revision or hardware configuration is qualified; check the applicable release notes for edition-specific requirements and known issues. Arcade Collection is also represented separately, with its own compatibility limits.

## Zero manual database setup

Adding a supported Modern game handles the routine preparation for you. Clubhouse checks the selected original files, prepares its Play Cache, and imports the required original database backup into a private database when one is missing.

You do not need to install PostgreSQL separately, create database users, configure a system service, or run SQL commands. The required database runtime is managed by Clubhouse, with separate state for each edition.

**Zero manual setup does not mean the games run without databases.** Provide the complete supported original game folder, including its required backup and supporting files. A lone `game.bin` is not enough. Clubhouse keeps its managed runtime state separate from the original game content.

<details>
<summary>View the Games &amp; Databases interface</summary>

![Games and Databases settings showing Add games, readiness columns, and database backup and restore actions](docs/images/clubhouse-games-and-databases.png)

*Earlier development interface shown for orientation.*

</details>

## Getting started

### 1. Install Clubhouse

Download and run **GTee-Clubhouse-Beta-1.0-Setup.exe**. Close Clubhouse and all games before installing. Choose an empty writable folder for a fresh install, or your existing Beta folder to refresh or repair its software while retaining settings and saved progress. Alpha installations are not converted; install Beta into a separate folder.

Allow at least 8 GB free for installation, plus room for game files, Play Cache, databases and backups. Setup also uses temporary space on the Windows drive. On exFAT, setup warns that temporary private sessions use Local AppData on the Windows drive; settings and saved databases remain in the chosen installation folder.

Open **GTee Clubhouse.exe** after setup. Fresh installations start fullscreen and show the welcome screen; choose **Guided Tour**, **Classic**, **Modern** or **Close**. Press **F11** to switch between fullscreen and a window. The runtime is bundled; no separate .NET or PostgreSQL installation is required.

The accompanying corresponding-sources ZIP is for developers and license information. It is not a portable Clubhouse installation.

### 2. Add Modern games

1. Open **Settings > Games & Databases**.
2. Select **Add games** and choose your complete supported original game folder. Use Ctrl/Shift to select multiple folders, or scan their parent folder.
3. Let Clubhouse finish content verification, Play Cache preparation, and database setup. The first setup can take time, depending on the game and drive.
4. Review the reported status. Resolve missing or incompatible files before continuing.
5. Return to **Library**, select the edition, and choose **Play** when it is ready.

### 3. Add Classic games

1. Open **Settings > MAME / Classics** and choose your existing ROM collection using the ROMs folder field, or use the default directory shown there.
2. Follow the default ROM folder's **ADD TO ROMS FOLDER.txt** instructions. Keep required ROM ZIPs and CHDs in their expected named game folders.
3. Keep ROM ZIPs zipped, and include any required parent ROM or BIOS files.
4. Select **Refresh** and check the ROM/CHD status. A green **Not required** entry is normal when that component is unnecessary.
5. Select the game in **Library** and play.

The Classic runtime and its routine configuration are integrated into Clubhouse; you do not need to set up a separate MAME frontend.

### 4. Set your controls and display

Use **Input & navigation** for launcher navigation, **Global Game Controls** for shared button mappings, and **Global Game Settings** for display and game defaults. Choose your trackball device or the appropriate mouse input mode, then adjust sensitivity to suit your setup.

Use **Per-game settings** for supported edition-specific overrides. Classic picture filters, bezels, sensitivity, and volume are available under **MAME / Classics**. Modern graphics controls depend on the selected edition.

### 5. Connect your cabinet frontend

Clubhouse can run on its own or launch games through its headless entry point. Use **Headless launching** to obtain the command for your chosen game and saved settings.

**Auto-export games to LaunchBox with artwork and metadata.** Close LaunchBox and Big Box, choose your LaunchBox folder in Clubhouse, and select **Export** for all games or installed games. Clubhouse automatically creates the game entries, supplies their metadata and headless launch commands, copies available artwork assets, and adds the games to the Arcade platform and GT playlist.

Artwork includes clear logos, fanart backgrounds, marquees, posters, and available front-box and 3D-box images. The export handles the entries and assets together, so you can launch through LaunchBox or Big Box using your saved Clubhouse settings without building each entry by hand.

Review the overwrite/skip choice when matching entries already exist. Enable the optional second-screen marquee in the app's general settings if your cabinet has a marquee display.

## Backups and updates

Run the installer again to repair missing or damaged software. A newer Beta installer updates the same Beta folder; early 1.0 refinements can also refresh a 1.0 installation. Back up important progress before maintenance.

Uninstall through **Windows Settings > Apps > Installed apps**. Choose whether to keep your settings and databases or delete Clubhouse data and recovery backups. Original game folders outside the installation are preserved.

Use **Backup Databases** before upgrades or major changes. **Restore Databases** lets you review matching backups before restoring them. Keep a separate copy of important backups outside the installation folder.

Do not use **Remove game** as an update or repair shortcut: it can remove Clubhouse-owned progress, internal backups, and cache. Use the release's documented update or recovery process instead.

## Troubleshooting and support

- **A Modern game will not add:** Confirm that the full original folder matches a supported version and includes the required database backup and supporting content.
- **A Classic game is unavailable:** Check its ROM, parent/BIOS, and CHD requirements in **MAME / Classics**, then select **Refresh**.
- **Play is blocked by a previous session:** Open **Session & diagnostics**, use **Stop background session**, and let cleanup finish before trying again.
- **Controls or graphics need adjustment:** Start with the documented defaults, check the selected input device and per-game overrides, and consult the release's known issues.
- **You need help:** Read [SUPPORT.md](SUPPORT.md), check [existing issues](https://github.com/natemac/gtee-clubhouse-releases/issues), and include your Clubhouse version, Windows version, game edition, and steps to reproduce the problem.

Support reports can be prepared and sent from the app's Support page. Successful uploads show a confirmation; a selectable local ZIP path is available for manual sharing if upload fails. Keep private databases, game files, account information and raw support archives out of public issues.

## Support development

If Clubhouse makes your collection easier to enjoy, you can [support development on Ko-fi](https://ko-fi.com/N4N32AC2LY).

This repository contains public release documentation and support information. Game content, ROMs, CHDs, original databases, saved progress, and personal configuration are supplied separately and are not distributed here. Third-party notices and required corresponding source accompany the applicable release; see [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
