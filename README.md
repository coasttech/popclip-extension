# PopClip Extensions for Radarr and Sonarr

This repository contains PopClip extensions for [Radarr](https://radarr.video/) and [Sonarr](https://sonarr.tv/) that allow you to quickly add new items to your media servers from selected text.

## Features

- **Radarr**: Easily search and add movies to your Radarr instance.
- **Sonarr**: Quickly search and add TV shows to your Sonarr instance.
- Custom icons for each extension.

## Installation

### 1. Download the Extensions

- Clone this repository or download the `Radarr` and `Sonarr` folders.
  
### 2. Install the Extensions

1. Open the `Radarr.popclipext` or `Sonarr.popclipext` folder.
2. Double-click the `Config.plist` file to install the extension to PopClip.

### 3. Configuration

Ensure that your Radarr and Sonarr instances are running on the correct IP address and port. Update the `Config.plist` files if needed to match your local network setup.

### Example Configuration (Radarr)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<plist version="1.0">
<dict>
    <key>name</key>
    <string>Radarr</string>
    <key>icon</key>
    <string>radarr.png</string>
    <key>url</key>
    <string>http://10.10.10.7:7879/pewrad/add/new?term=***</string>
</dict>
</plist>
```

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

Let me know if you'd like to make any adjustments!
