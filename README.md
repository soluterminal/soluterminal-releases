# soluterminal-releases

Release builds of [SoluTerminal](https://soluterminal.com/?utm_source=github&utm_campaign=oss-launch)
for its auto-updater. The source code is at
[soluterminal/soluterminal](https://github.com/soluterminal/soluterminal).

This repository only hosts the compiled binaries and the signed update
manifest, so the app's updater can fetch them anonymously.

## What's published here

Each release contains:

- `solud-linux-amd64` — Linux daemon binary (used by the WSL backend on Windows installs)
- `solud-windows-amd64.exe` — Windows-native daemon binary
- `update.json` — the signed manifest the auto-updater checks

## How to install SoluTerminal

You don't install from this repository. Get the desktop installer from
[soluterminal.com](https://soluterminal.com/?utm_source=github&utm_campaign=oss-launch).

After install, the app updates itself from this repository's latest release.
