# FOUNDATION // OS Desktop

The Windows desktop client for the hosted FOUNDATION // OS workstation.

## Download

Use only this file from the latest GitHub Release:

FoundationOSSetup.exe

That is the installer. Windows x64 is the supported system.

Do not download these files manually. The installed application uses them for automatic updates:

- RELEASES
- FoundationOS-<version>-full.nupkg

## What the application does

The desktop client opens the hosted FOUNDATION // OS service. Protected areas require an authorized FOUNDATION account. The same account works in the browser and in the desktop client.

## Install

1. Open the latest release on this repository.
2. Confirm the file name is FoundationOSSetup.exe.
3. Download that file only.
4. Open the downloaded installer.

The installer adds a Start menu shortcut and a Desktop shortcut named FOUNDATION OS.

## Updates

An installed copy checks for a newer desktop revision on its own. When one is ready, the workstation offers to restart and apply it. You do not need to download FoundationOSSetup.exe again for a normal update.

Hosted workstation changes can be published without a new desktop installer. A desktop download is only required for a new desktop revision.

## Windows security notice

This desktop build is not yet Authenticode-signed. Windows may therefore show:

- Unknown Publisher
- Microsoft Defender SmartScreen

That is expected for this direct-download beta. Do not turn SmartScreen off.

Before opening the installer, confirm that it came from the official FoundationOS-Releases repository. If SmartScreen appears, read the prompt. Use More info, then Run anyway, only for this installer and only when you intentionally downloaded it from that official release. Leave Windows security settings unchanged.
