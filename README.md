# Stealth Chat: downloads

This repository only hosts **installers and the auto-update feed** for Stealth Chat. The source code is private.

## Install

Open the [latest release](https://github.com/devfoundry16/stealth-chat-releases/releases/latest) and download:

| Platform | File |
|---|---|
| macOS, Apple Silicon | `stealth-chat-<version>-mac-arm64.dmg` |
| macOS, Intel | `stealth-chat-<version>-mac-x64.dmg` |
| Windows 10/11 (x64) | `stealth-chat-setup-<version>.exe` |

The builds aren't code-signed yet:

- **macOS:** right-click the app and choose **Open** the first time.
- **Windows:** on the SmartScreen prompt, choose **More info**, then **Run anyway**.

## Updates

The app checks this repository each time it starts.

- **Windows:** updates download in the background and install the next time you restart the app.
- **macOS:** the app shows **Version X is available. Download**, which links here.

The `latest.yml` and `latest-mac.yml` files attached to each release are the update feed. Don't delete them.
