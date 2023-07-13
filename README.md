# GoingDusty
A small DUST-based Fallout New Vegas modlist

## Work in Progress
This modlist is currently a WIP modlist, so there is no support for failed installations, bugs, and/or other issues, and will not be available for the foreseeable future.

## Requirements

- An English copy of the game with all DLCs from either [Steam](https://store.steampowered.com/sub/13435/) or [GOG](https://www.gog.com/game/fallout_new_vegas_ultimate_edition).
  - Only the English version of the game is supported for maximum compatibility.
  - The Microsoft Store and Epic Games Store versions of the game are unsupported:
    - The Microsoft Store version doesn't support xNVSE which is essential for most mods.
    - The Epic Games Store version can be patched to support xNVSE, but Epic's DRM makes it impossible to use Mod Organizer.
  - The german release uses a "No Gore" version, making it also incompatible with xNVSE.
    - If you are on Steam, you can use [DepotDownloader](https://github.com/SteamRE/DepotDownloader) to download the international exe.
- At least 13GB of free storage space. This may be split in 3 different drives.
  - ~9,3GB for Fallout New Vegas installation.
  - ~1GB for modlist download files.
  - ~2,6GB for modlist installation.
- Windows 8 or higher (64-bit). (Linux support is being researched)
- VC++ Runtime Libraries.
  - You can use [TechPowerUp's Visual C++ Redistributable Runtimes All-in-One](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/) to install all of the required libraries at once.
  - Extract the archive and run the included `install_all.bat` as an administrator.
- The latest GPU drivers (either [NVIDIA](https://www.nvidia.com/Download/index.aspx), [AMD](https://www.amd.com/en/support) or [Intel](https://www.intel.com/content/www/us/en/download/19344/intel-graphics-windows-dch-drivers.html)).
- A [Nexus Mods](https://users.nexusmods.com/account/profile) account.
  - Premium is recommended to fully automate the download process but not necessary.

## Installation

  1. Download the latest Wabbajack.
  2. Create a new folder anywhere outside of any default Windows folders.
  3. Place the downloaded Wabbajack.exe in this folder, then run it.
  4. Enable Show Unofficial Lists, then locate Viva New Vegas in the gallery and click the download button in the corner.
  5. In Installation Location select an empty folder that is NOT the following:
     - The Steam folder.
     - Any default Windows folders.
     - The game folder.
     - The folder where you put Wabbajack.exe.
  6. Begin the installation.
  7. Accept the Nexus Mods API request.
     - If you are not a Premium user, you will need to manually click download for each mod.
  8. Once complete, the installation will show a green Installation Complete screen.
     - Support is currently not available for failed installations.

## Post-Install Steps

  1. Go to your game installation folder.
  2. Copy the FalloutNV.exe file to your modlist installation folder`\mods\[NoDelete] 4GB Patched Executable\Root`.
  3. Then go to your modlist installation folder`\tools\FNV 4GB Patcher`.
  5. Copy the `FalloutNVpatch.exe` file to your modlist installation folder`\mods\[NoDelete] 4GB Patched Executable\Root`.
  6. Right-click on FNVpatch.exe and select Run as administrator.
  7. A command prompt window will open and should say FalloutNV.exe patched!
  8. Close the command prompt and a file named FalloutNV_backup.exe should appear in the folder.
  9. Delete `FalloutNVpatch.exe` and `FalloutNV_backup.exe`.

## How to play
  1. In your modlist installation folder, open Mod Organizer 2 (`ModOrganizer.exe`).
  2. Now you can play the game through the `New Vegas` option in the top right:
  3. Run `New Vegas` through MO2.
