# SideTrack 0.1.7 Preview

A compact desktop companion for JRiver Media Center on Windows x64.

## Included

Artwork-derived themes with a diagonal gradient and shadow; responsive Play/Pause; a smooth read-only waveform; manual and optional per-track PNG snapshots; configurable connection and player preferences; built-in offline Help.

Automatic snapshots hide elapsed time and played-progress highlighting. Manual snapshots retain both. Waveforms use consistently spaced bars and fall back to a normal progress bar when metadata is missing.

## Setup

JRiver Media Center is required separately. Enable its Media Network / MCWS server, then open SideTrack Settings (F2), enter the connection details, test and save. Python is bundled for the core player.

Artist Radio and the TrackInfo helper are optional and require their own dependencies. Writing artwork colors to JRiver is off by default and only uses an existing custom text field.

## Preview limitations

- Windows x64 only; no macOS or Linux build.
- Installer is unsigned.
- Local installation, launch and uninstall checks passed; separate clean-computer testing remains outstanding.
- SideTrack is freeware for personal or commercial use; see LICENSE.txt. Source code is maintained privately.

For this release, download `SideTrack-Setup-0.1.7-preview-x64.exe`. Checksums are attached as `SHA256SUMS.txt`.
