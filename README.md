<p align="center"><img src="icon.png" width="112" alt="Halodial icon"></p>
<h1 align="center">Halodial</h1>
<p align="center"><b>Everything you do with a file, one flick away.</b><br>A dial for your Mac that opens under your pointer.</p>
<p align="center"><a href="https://github.com/Halodial/releases/releases/latest/download/Halodial.dmg"><b>Download Halodial</b></a> · <a href="https://halodial.github.io">Website</a> · <a href="https://github.com/Halodial/releases/releases">All versions</a></p>

---

This repository holds Halodial's downloads and the update feed the app checks. Free during early access.

## What it does

- **Hold ⌘ while dragging a file**: a dial opens under it with File, Convert, Edit and Share.
- **Shake a file while dragging**: a shelf opens to park it on.
- **Tap with four fingers**: the launcher, with volume, music, display and system controls, apps and folders.

Pictures, video, audio, PDFs, documents, spreadsheets, slides and archives. Everything runs on your Mac; nothing is uploaded.

## Requirements

macOS 14 Sonoma or later, on a Mac with Apple silicon.

## Installing

**One line, no prompts** (paste into Terminal):

```sh
curl -fsSL https://halodial.github.io/install.sh | sh
```

**Homebrew, no prompts:**

```sh
brew tap halodial/tap && brew trust halodial/tap && brew install --cask halodial
```

**Or the disk image:** open `Halodial.dmg`, drag Halodial onto Applications and open it. macOS says Apple could not verify it, because Halodial isn't notarized by Apple yet: click **Done**, then **System Settings › Privacy & Security › Open Anyway**. You only do this once.

Halodial checks for updates daily and installs them itself (menu bar › Check for Updates…).

## Files here

| File | What it is |
| --- | --- |
| `Halodial.dmg` (in each release) | The app |
| `appcast.xml` (in each release) | The update feed, signed so the app only installs genuine updates |

---

© 2026 Sarthak Kamble. All rights reserved. Halodial includes open-source components; their licences are inside the app (Settings › About › Show Licences).
