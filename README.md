# soluterminal-releases

Public release artifacts for [soluterminal](https://soluterminal-cloud.onrender.com).

The source code lives in a private repository. This repo only exists to host
the compiled binaries and the auto-update manifest, so the soluterminal app's
in-process updater can fetch them anonymously without requiring users to have
a GitHub token.

## What's published here

Each release contains:

- `solud-linux-amd64` — Linux daemon binary (used by the WSL backend on Windows installs)
- `solud-windows-amd64.exe` — Windows-native daemon binary
- `update.json` — manifest the auto-updater polls every 15 minutes

## How to install soluterminal

You don't install from this repo. Get the desktop installer (MSI) from
the [soluterminal landing page](https://soluterminal-cloud.onrender.com).

After install, the app self-updates from this repo's `latest` release.
