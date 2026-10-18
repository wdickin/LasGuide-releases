# Karttapullautin GUI – downloads

Karttapullautin GUI is a desktop app for Karttapullautin (pullauta), the tool that turns LiDAR `.laz` point clouds into orienteering maps. Pick your `.laz` files, press Start, and the app prepares the data, runs pullauta and shows you the map.

This repository only hosts the ready-to-run downloads. Get them from the [Releases](../../releases/latest) page.

| Your computer | Download |
|---|---|
| Windows 10/11 (64-bit), installer (recommended) | `KarttapullautinGUI-<version>-Setup-x64.exe` |
| Windows 10/11 (64-bit), portable (no install) | `KarttapullautinGUI-<version>-windows-x64.zip` |
| Mac with Apple Silicon (M1, M2, M3, M4…) | `KarttapullautinGUI-<version>-macos-arm64.dmg` |
| Mac with an Intel processor | `KarttapullautinGUI-<version>-macos-intel.dmg` |
| Linux x86_64 (Ubuntu 22.04+ / Debian 12+) | `KarttapullautinGUI-<version>-linux-x86_64.tar.gz` |

The macOS builds are also available as `.zip` files with the same names.

## First launch

- **Windows (installer):** run `KarttapullautinGUI-<version>-Setup-x64.exe`. By default it installs for your user only (no admin rights needed) and adds a Start-menu entry; uninstall it from Apps & features. The installer and app are not code-signed, so SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway**.
- **Windows (portable):** unzip and run `KarttapullautinGUI.exe` from a folder you can write to.
- **macOS:** open the `.dmg` and drag `KarttapullautinGUI.app` to Applications (or unzip the `.zip`). The app is unsigned, so the first time you have to **right-click (or Control-click) the app and choose Open**, then confirm with **Open**. After that it opens normally.
- **Linux:** `tar xzf KarttapullautinGUI-*-linux-x86_64.tar.gz` and run `./KarttapullautinGUI`.

On first Start the app downloads the matching pullauta program automatically. Its settings and work folder are created next to the app when that folder is writable (the installer's folder is), otherwise in your user data folder.
