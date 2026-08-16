# Capsule OS

A desktop toolkit for Dokkan Battle: browse every character, build units and events, write and preview animation scripts, make card art, and play the soundtrack.

## Download

**[⬇ Download the latest installer](https://github.com/itZcat17/CapsuleOS-Releases/releases/latest)**

Windows only. Run the installer and you are ready — there is nothing else to set up.

## Updates are automatic

Capsule OS checks for a new version on launch and offers it to you. Downloads are differential, so an update pulls only what actually changed rather than the whole installer again. You will never need to come back to this page after the first install.

You can also check manually in **Settings → Updates**.

### Beta builds

**Settings → Updates → Beta programme** puts you on the beta channel: new builds arrive as soon as they are published, before they reach everyone else. Betas are the real thing, early — expect the occasional rough edge. Leaving the programme puts you back on stable at the next release.

## What is in a release

| File | What it is |
|------|------------|
| `Capsule-OS-Setup-x.y.z.exe` | The installer. This is the one you want. |
| `Capsule-OS-Setup-x.y.z.exe.blockmap` | Lets the app download only the changed parts of an update. |
| `latest.yml` | The manifest installed copies read to find new versions. |

Only the `.exe` is meant to be downloaded by hand; the other two are for the updater.

## Windows SmartScreen

The installer is not code-signed, so Windows may show a blue "Windows protected your PC" box on first run. Choose **More info → Run anyway**. A signing certificate is on the list.

## Reporting a problem

Open an issue here, or use **Settings → Feedback** inside the app — that sends the version and a description straight through, which is far easier to act on than a screenshot.

---

This repository holds **release binaries only**. No source code lives here.
