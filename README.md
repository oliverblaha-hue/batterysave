# batterysave

`batterysave` is a small macOS menu bar app that watches your battery in the background and sends a notification when the battery drops below a percentage you choose.

It shows only the `batterysave` logo in the menu bar, so it does not duplicate the built-in macOS battery indicator.

![batterysave logo](batterysave-logo.png)

## Features

- Custom battery alert threshold
- macOS notifications
- Menu bar logo only
- Czech and English language choice during installation
- Optional alerting only while the Mac is discharging
- Starts automatically after login
- Universal macOS build for Apple Silicon and Intel

## Installation

Recommended installation:

1. Download `batterysave-installer.zip` or `batterysave-installer.dmg`.
2. Open `install-batterysave.command`.
3. Choose `Čeština` or `English`.
4. Allow notifications when macOS asks.
5. Click the `batterysave` logo in the menu bar and choose `Set threshold...`.

The `.command` installer copies `batterysave.app` to `/Applications`, sets it to start after login, saves the selected language, and removes the older `BaterkoHlidac` version if it exists.

You can also install `batterysave.pkg`, but the `.command` installer is recommended because it lets you choose the language.

## Usage

After installation, `batterysave` appears in the macOS menu bar as a logo.

Click the logo to:

- change the alert threshold
- test a notification
- quit the app

The app keeps monitoring the battery in the background. When the battery drops below the selected threshold, macOS shows a notification.

## Build From Source

Requirements:

- macOS 12 or newer
- Xcode command line tools
- Swift compiler

Build:

```bash
chmod +x build.sh
./build.sh
