# Blender Agent Releases

Official release downloads for Blender Agent desktop.

## Download

Latest release:

https://github.com/pictor-network/blender-agent-releases/releases/latest

Windows x64 installer:

https://github.com/pictor-network/blender-agent-releases/releases/download/v0.1.0/blender-agent-win-x64-0.1.0.exe

## Install on Windows

1. Download `blender-agent-win-x64-0.1.0.exe` from the latest release.
2. Run the installer.
3. If Windows SmartScreen appears, choose **More info** and then **Run anyway**.
4. Open Blender Agent from the Start menu or desktop shortcut.
5. Sign in, choose a plan if required, then follow the in-app Blender setup flow.

## Auto Update

The Windows app reads update metadata from the release asset:

https://github.com/pictor-network/blender-agent-releases/releases/download/v0.1.0/latest.yml

Keep `latest.yml` and the `.exe` in the same GitHub Release tag. The `sha512` and `size` values in `latest.yml` must match the uploaded installer exactly.

## macOS and Linux

macOS and Linux builds are not published in this release yet. When they are available, they should be uploaded to the same release tag with their matching update metadata, for example `latest-mac.yml` or `latest-linux.yml`.
