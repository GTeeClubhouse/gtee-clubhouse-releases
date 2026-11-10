# GTee Clubhouse 0.1 Beta

Welcome to GTee Clubhouse, a Windows launcher for organizing and playing your own Classic and Modern GT game collection. Add your games, follow the guided setup, and launch them from one visual library. This is a beta prerelease for Windows 10/11 x64.

## What's included

- **A visual game library:** Browse your collection with game artwork, filter installed games and launch from one place.
- **A welcome screen and guided tour:** Get familiar with Clubhouse and follow shortcuts to Classic or Modern game setup.
- **Modern game setup:** Add complete supported game folders and let Clubhouse check their files, prepare them for play and set up the required databases without a separate database-server installation.
- **Classic game support:** Use the integrated MAME runtime with your own matching ROMs and CHDs, plus picture presets, bezels and trackball settings.
- **Controls and display settings:** Configure keyboard, controller and supported mouse or USB trackball input, with shared and per-game options, fullscreen presentation and an optional second-screen marquee.
- **LaunchBox and Big Box integration:** Export game entries, artwork and launch commands for use with your cabinet frontend.
- **Database backup and maintenance:** Back up and restore Modern game databases, repair the application with the installer, and choose whether to keep your settings and databases when uninstalling.

## Disclaimer

GTee Clubhouse is a launcher for legally owned backup copies of your own software and games. No Incredible Technologies (IT) game software, game source code, or game data is distributed with this launcher, and no GT game source code is used to build it. We do not provide any games or game data. All backups are supplied by the user and must correspond to software and games they legally own; users are responsible for ensuring they have the right to use their backups.

## What you need

- A Windows 10/11 x64 PC and at least 8 GB of free space for Clubhouse, plus room for your games, databases and backups. Setup also needs temporary space on your Windows drive.
- Your own complete supported Modern game folders, including their required original database backups, or matching Classic ROMs and CHDs. Compatibility depends on the exact game version and your hardware.

## Get started

1. Download **GTee-Clubhouse-0.1-Beta-Setup.exe** from the assets below. This is the installer; the corresponding-sources ZIP is not needed to install or play.
2. Run the installer and choose an empty, writable folder. The required app runtimes are included; you do not need to install .NET or a database server separately.
3. Open **GTee Clubhouse.exe**. Choose **Guided Tour** on the welcome screen for a walkthrough, or choose **Classic** or **Modern** to add your games.
4. Follow the setup prompts and let Clubhouse check your files. Modern database preparation can take time on first setup. For Classics, select your ROM folder and refresh the library.
5. Select a ready game in **Library** and choose **Play**. Configure your mouse, trackball, keyboard or controller in Settings. Clubhouse starts fullscreen; press **F11** to switch to a window.

If you install on an exFAT drive, setup explains that temporary game sessions use Local AppData on your Windows drive. Your saved settings and databases remain in the installation folder you chose.

Windows may show an unknown-publisher prompt because the installer is not Authenticode-signed. Download it from this release page; **SHA256SUMS.txt** contains the checksums for verifying the files.

## Backups, repair and uninstall

Use **Backup Databases** to save your Modern game progress, and keep a separate copy of important backups. If Clubhouse needs repair, close it and your games, then rerun the installer against the same installation folder.

To uninstall, open **Windows Settings > Apps > Installed apps**. Choose whether to keep your settings and databases for reinstallation or delete all Clubhouse data. Original game folders outside the installation are preserved.
