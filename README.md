# Soates | https://soates.org

**Every song deserves a beautiful room.**
A music player for YouTube Music: audio only, a studio-grade sound engine, and a
room you design yourself.

Published by the House of Heroia · developed by 8xy

## Download

Get the newest version on [soates.org](https://soates.org/#download) or from the
[Releases](https://github.com/weloveyou8xy/soates/releases/latest) page.

| Platform | File | Updates |
| --- | --- | --- |
| Windows 10 and 11 | `Soates-Setup-x.y.z.exe` (or the portable `.exe`) | Automatic |
| Linux | `Soates-x.y.z-x86_64.AppImage` | Automatic |
| Debian, Ubuntu | `soates_x.y.z_amd64.deb` (`sudo apt install ./soates_*.deb`) | Automatic |
| Linux, other | `Soates-x.y.z-linux-x64.tar.gz` | Manual |
| Android 8.0 and later | `Soates-Android-x.y.z.apk` (public beta, tags `android-v*`) | In the app |

The Windows builds are not code-signed yet. If SmartScreen warns, choose
**More info**, then **Run anyway**. To check that a file is genuine, compare its
SHA-256 checksum with the one on soates.org, which comes straight from GitHub.

## This repository

It holds the releases and the release automation:

- `.github/workflows/linux-packages.yml` builds the Linux packages on Ubuntu for
  every desktop release, starts the AppImage headless as a smoke test and
  attaches the packages to the release.
- `.github/workflows/notify-website.yml` tells soates.org to rebuild when a
  release is published.

*Open beta*
