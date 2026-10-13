# Ultrac Desktop downloads

Ultrac Desktop provides hosted chat, saved conversations, background tasks, and a local workspace folder selector on macOS.

[Download the latest release](https://github.com/adipundir/ultrac-releases/releases/latest)

## Install

The first release supports Apple Silicon Macs (M1 or later) running macOS 12 or newer. Download the DMG from the release page, open it, and drag Ultrac into Applications. Open Ultrac from Applications and sign in using your emailed code. Your Ultrac account’s access requirements apply.

The installers are signed with a Developer ID Application certificate and notarized by Apple. Node.js and the CLI are not required for hosted chat and tasks.

## Updates

Quit Ultrac, download the newer release, and replace the app in Applications. Updates are manual; there is no in-app updater. Conversations and tasks are stored by the hosted service. Local workspace selection and drafts remain in the app profile.

The workspace panel offers copyable CLI commands. The desktop does not run local agents or index files.

## Verify a download

Each release includes a SHA256SUMS file alongside the DMG and ZIP. Download the installers and that file into one directory, then run:

```sh
shasum -a 256 -c SHA256SUMS
```

This repository contains installers and release notes. The application source remains private.
