# WoRTool for desktop

The desktop app for [wortool.com](https://wortool.com): the War of Rights catalog of maps, units and weapons, the WoRSketch planner, the server editor, and your communities and operations, in a window of its own. The catalog keeps working offline once it has been read, and a plan can sit over the game while you play.

## Download

Every build is on the [releases page](https://github.com/molexxxx/wortool-desktop/releases/latest).

| System | File |
| --- | --- |
| Windows 10 and 11 (64-bit) | `wortool-<version>-Windows-Setup.exe` |
| macOS, Apple silicon and Intel | `wortool-<version>-macOS-Installer.dmg` |
| Linux, any distribution | `wortool-<version>-Linux.AppImage` |
| Debian, Ubuntu and derivatives | `wortool-<version>-Linux.deb` |
| Fedora, openSUSE and derivatives | `wortool-<version>-Linux.rpm` |

### Windows

Run the installer. Windows SmartScreen may say it does not recognize the app, because the installer is not yet signed with a code signing certificate; choose "More info", then "Run anyway". The installer asks where to install and adds Start menu and desktop shortcuts.

### macOS

Open the dmg and drag WoRTool into Applications.

### Linux

For the AppImage, mark it executable and run it:

```sh
chmod +x wortool-*-Linux.AppImage
./wortool-*-Linux.AppImage
```

Or install the package for your distribution:

```sh
sudo apt install ./wortool-*-Linux.deb
sudo dnf install ./wortool-*-Linux.rpm
```

## Updates

The app checks this repository's releases a little after it starts and every few hours after that, downloads a new version in the background, and installs it when you quit. Settings shows the version you have and can restart into a downloaded one straight away.

## Signing in

The app signs in through your browser with the same account you use on wortool.com, then returns to the app. Nothing you type into the browser passes through the app.

## Problems and suggestions

Open an [issue](https://github.com/molexxxx/wortool-desktop/issues) with what you did, what you expected, and what happened instead. Your operating system and the version from Settings help. Account, community and privacy questions go through [wortool.com/contact](https://wortool.com/contact).

## About this repository

The app is built from the wortool.com source, which is private. This repository holds the workflow that builds and publishes the installers and hosts the releases the app updates from.
