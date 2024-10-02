# PopClip Extensions for Radarr and Sonarr

This repository contains PopClip extensions for [Radarr](https://radarr.video/) and [Sonarr](https://sonarr.tv/) that allow you to quickly add new items to your media servers from selected text.

## Features

- **Radarr**: Easily search and add movies to your Radarr instance.
- **Sonarr**: Quickly search and add TV shows to your Sonarr instance.
- Custom icons for each extension.

## Installation

### 1. Download the Extensions

- Clone this repository or download the `Radarr` and `Sonarr` folders.

### 2. Configure the URLs

Ensure that the URLs in the `Config.plist` files are correct for your Radarr and Sonarr instances. Open the `Config.plist` files in the respective folders and update the URLs to match your local setup:

#### Example Radarr Configuration

```xml
<?xml version="1.0" encoding="UTF-8"?>
<plist version="1.0">
<dict>
    <key>name</key>
    <string>Radarr</string>
    <key>icon</key>
    <string>radarr.png</string>
    <key>url</key>
    <string>http://<your_radarr_ip>:<your_radarr_port>/add/new?term=***</string>
</dict>
</plist>
```

#### Example Sonarr Configuration

```xml
<?xml version="1.0" encoding="UTF-8"?>
<plist version="1.0">
<dict>
    <key>name</key>
    <string>Sonarr</string>
    <key>icon</key>
    <string>sonarr.png</string>
    <key>url</key>
    <string>http://<your_sonarr_ip>:<your_sonarr_port>/add/new?term=***</string>
</dict>
</plist>
```

### 3. Rename the Folders

Once you've updated the URLs in the `Config.plist` files:

- Rename the `Radarr` folder to `Radarr.popclipext`.
- Rename the `Sonarr` folder to `Sonarr.popclipext`.

### 4. Install the Extensions

1. Open the renamed `Radarr.popclipext` and `Sonarr.popclipext` folders.
2. Double-click the `Config.plist` file inside each folder to install the respective extension to PopClip.

## Usage

1. Select the text of a movie (for Radarr) or a TV show (for Sonarr) title in any app.
2. Click the PopClip action for Radarr or Sonarr.
3. The extension will open the appropriate media server in your browser, pre-filled with the search term.

## Icons

- **Radarr**: Custom movie icon.
- **Sonarr**: Custom TV icon.

## Troubleshooting

If the icons do not appear correctly, ensure that the `radarr.png` and `sonarr.png` files are correctly placed in the same directory as their respective `Config.plist` files.

## License

This project is open-source and available under the MIT License. See the LICENSE file for more details.

---

This version now reflects the proper step-by-step order. Let me know if any further adjustments are needed!
