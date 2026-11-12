# Motiv

Meeting notes, summaries and answers, on your own machine. Motiv records your meetings, transcribes them locally and writes summaries with the AI model you choose.

## Download

Get the latest version from [Releases](https://github.com/Emruz/motiv-releases/releases/latest). Each release has a build for Mac, Windows and Linux:

| Platform | File | Install |
| --- | --- | --- |
| Mac (Apple Silicon) | `Motiv_<version>_aarch64.dmg` | Open it and drag Motiv to Applications. |
| Windows 10 and 11 (64-bit) | `Motiv_<version>_x64-setup.exe` (or the `.msi`) | Run it. |
| Linux, Ubuntu or Debian (64-bit) | `Motiv_<version>_amd64.deb` | `sudo apt install ./Motiv_<version>_amd64.deb` |
| Linux, other distributions (64-bit) | `Motiv_<version>_amd64.AppImage` | `chmod +x Motiv_<version>_amd64.AppImage`, then run it. |

The Linux builds need Ubuntu 22.04 or newer (or a distribution from 2022 or later) on an x86-64 computer, with PulseAudio or PipeWire for audio. Some distributions need `libfuse2` installed to run AppImages.

Each download has a matching `.sha256` file. To check a download, put both in one folder and run:

- Mac: `shasum -a 256 -c Motiv_<version>_aarch64.dmg.sha256`
- Linux: `sha256sum -c Motiv_<version>_amd64.deb.sha256`
- Windows (PowerShell): `Get-FileHash Motiv_<version>_x64-setup.exe`, and compare the result with the `.sha256` file.

Builds aren't code-signed yet. On a Mac, the first time, right-click Motiv in Applications and choose **Open**. On Windows, if SmartScreen appears, choose **More info → Run anyway**.

## Updates

**About → Check for Updates** tells you when a new version is here and links to it. Download and install it over the old one (on Linux, install the new `.deb` or replace the AppImage); your meetings and settings stay.

## Help

- [Connecting calendars](docs/CALENDAR_SETUP.md)
- [Privacy policy](PRIVACY_POLICY.md)
- Problems or ideas: [open an issue](https://github.com/Emruz/motiv-releases/issues)

This repository holds Motiv's releases and user docs; the source code is private.
