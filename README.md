# Morinus 9.6.3 for Apple Silicon (macOS)

An unofficial Apple Silicon (`arm64`) build of the open-source astrology software [Morinus 9.6.3](https://sourceforge.net).

## System Requirements
* **Architecture:** Apple Silicon (M1, M2, M3, M4 or newer)
* **OS:** macOS 27 (Golden Gate) or later

## Installation
1. Download the latest `.dmg` image from the [Releases](../../releases) page.
2. Open the downloaded `.dmg` file and drag `Morinus.app` into your **Applications** folder.
3. Because the app is not notarized with an Apple Developer certificate, macOS Gatekeeper may block it on first launch. To allow it to run, open **Terminal** and execute:
   ```bash
   xattr -cr /Applications/Morinus.app
   ```
4. Launch the application from your **Applications** folder or Launchpad.

## Credits
* **Original Author:** Robert Nagy
* **Updated Version (9.6.3):** Special thanks to [shin10567](https://sourceforge.net) for maintaining and updating the Morinus project.

## License
This project is distributed under the **GNU General Public License v3.0 (GPL-3.0)**, in accordance with the original Morinus source code license. See the [LICENSE](LICENSE) file for details.
