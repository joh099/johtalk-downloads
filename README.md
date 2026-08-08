# JohTalk — downloads

Release binaries for **JohTalk**. This repository holds a README and GitHub Releases
and **no source code** — it is public purely so the download links on
<https://johflow.com> resolve for anyone, without a GitHub account.

## Get it

Download from **[the latest release](https://github.com/joh099/johtalk-downloads/releases/latest)**, or from the site:

**<https://johflow.com/johtalk/>**

| Platform | File |
|---|---|
| Linux | `JohTalk_<version>_amd64.AppImage` — one file, `chmod +x` and run |
| Linux (Debian/Ubuntu) | `JohTalk_<version>_amd64.deb` |
| Windows | `JohTalk_<version>_x64-setup.exe` — per-user install, no admin prompt |
| macOS | not built yet — audio capture and cursor insertion have no macOS code paths |

## Why this repo exists

GitHub serves release assets to anonymous requests only from a *public* repo.
The application source is private, so the binaries are published here instead.
Releases are pushed automatically by CI in the source repo when a version tag
is pushed — nothing is uploaded by hand.

Download links on the site go through `johflow.com/download/…`, which redirects
here. That keeps the hosting choice out of every shared link, so it can move
later without breaking anything.

## Issues

Issues are disabled here because there is no code to file them against.
Reach me through the channels linked at <https://johflow.com/about/>.
