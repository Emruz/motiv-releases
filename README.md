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

From 0.34.0, each release also has `SHA256SUMS.txt`, signed with the Motiv release key (`SHA256SUMS.txt.asc`), to check a download came from Motiv. With [GnuPG](https://gnupg.org) installed, put the downloads, both files and [motiv-release-key.asc](motiv-release-key.asc) in one folder and run:

```
gpg --import motiv-release-key.asc
gpg --verify SHA256SUMS.txt.asc SHA256SUMS.txt
shasum -a 256 -c --ignore-missing SHA256SUMS.txt
```

`gpg` should say "Good signature from Shahin Pirooz (Motiv releases)" with key fingerprint `131A 2571 816F 5C60 0F5B 75FC 1511 0610 DE8A 204F`. On Linux use `sha256sum` in place of `shasum -a 256`.

From 0.34.0, the Mac app is signed by Shahin Pirooz and notarized by Apple, so it opens normally. Older Mac versions aren't: the first time, right-click Motiv in Applications and choose **Open**. Windows builds aren't code-signed yet: if SmartScreen appears, choose **More info → Run anyway**.

## Updates

Motiv checks for updates on its own, or use **About → Check for Updates**. When a new version is out, download it and install it over the old one (on Linux, install the new `.deb` or replace the AppImage). Your meetings and settings stay. Each release lists its highlights; **About → What's new** in the app has the full notes.

## Help

Help is in the app: **Settings → Getting started** has help topics, the setup wizard and a tour of using Motiv in a meeting. Calendar setup is in **Settings → Calendars & people → How to connect**.

- Problems or ideas: **Report a problem** or **Suggest a feature** in **Settings → Getting started** (no GitHub account needed). On versions before 0.33, [open an issue](https://github.com/Emruz/motiv-releases/issues).
- Security issues: see the [security policy](SECURITY.md); please don't open a public issue.
- [Licence](LICENSE.md) · [Privacy policy](PRIVACY_POLICY.md) · [Third-party notices](THIRD-PARTY-NOTICES.md)

This repository holds Motiv's installers and policies; the source code is private.
