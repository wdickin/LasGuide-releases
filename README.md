# Karttapullautin GUI – downloads

Karttapullautin GUI is a desktop app for Karttapullautin (pullauta), the tool that turns LiDAR `.laz` point clouds into orienteering maps. Pick your `.laz` files, press Start, and the app prepares the data, runs pullauta and shows you the map.

This repository only hosts the ready-to-run downloads. Get them from the [Releases](../../releases/latest) page.

| Your computer | Download |
|---|---|
| Windows 10/11 (64-bit) | `KarttapullautinGUI-<version>-windows-x64.zip` |
| Mac with Apple Silicon (M1, M2, M3, M4…) | `KarttapullautinGUI-<version>-macos-arm64.zip` |
| Mac with an Intel processor | `KarttapullautinGUI-<version>-macos-intel.zip` |
| Linux x86_64 (Ubuntu 22.04+ / Debian 12+) | `KarttapullautinGUI-<version>-linux-x86_64.tar.gz` |

## First launch

- **Windows:** unzip and run `KarttapullautinGUI.exe`. The app is not code-signed, so SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway**.
- **macOS:** unzip and move `KarttapullautinGUI.app` to Applications. The app is unsigned, so the first time you have to **right-click (or Control-click) the app and choose Open**, then confirm with **Open**. After that it opens normally.
- **Linux:** `tar xzf KarttapullautinGUI-*-linux-x86_64.tar.gz` and run `./KarttapullautinGUI`.

On first Start the app downloads the matching pullauta program automatically. Put the app in a folder you can write to; its settings and work folder are created next to it.
