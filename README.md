<div align="center">

<img src="./streamr.png" alt="Streamr logo" width="144" height="144" />

# Streamr

**Your next favorite story starts here.**

Discover movies, series, and anime. Save your favorites. Pick up where you left off.

<p>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-18202b?style=flat-square" alt="Windows 10 and 11" />
  <img src="https://img.shields.io/badge/Architecture-x64%20%7C%20ARM64-18202b?style=flat-square" alt="x64 and ARM64" />
  <img src="https://img.shields.io/badge/Library-Stored%20locally-d8ff3e?style=flat-square&labelColor=18202b&color=d8ff3e" alt="Library stored locally" />
</p>

**[Download Streamr](../../releases)** &nbsp; · &nbsp; [What's new](./CHANGELOG.md) &nbsp; · &nbsp; [Report an issue](../../issues)

</div>

---

## A little space for your stories

Streamr brings discovery, title details, and your personal library into one desktop app.

| Discover | Make it yours | Keep your place |
| :--- | :--- | :--- |
| Movies, TV series, and anime | Light, dark, and system themes | Personal watchlist |
| Genre and year filters | Remembered window size and position | Viewing history and progress |
| Popularity, rating, and release sorting | Playback server preferences | JSON backup and restore |
| Cast, crew, and title information | Reduced-motion option | Continue watching when supported |

## Get Streamr

Visit **[Releases](../../releases)** and expand **Assets** on the version you want to install.

| Your computer | Choose this installer |
| :--- | :--- |
| Intel or AMD 64-bit Windows PC | `Streamr-Setup-VERSION-x64.exe` |
| Windows on ARM PC | `Streamr-Setup-VERSION-arm64.exe` |

**Requirements:** Windows 10 or Windows 11, and an internet connection for catalog browsing and playback. Older Windows versions and 32-bit Windows are not supported.

> Not sure which installer to choose? Open **Windows Settings → System → About → System type**. Choose ARM64 for an ARM-based processor; choose x64 for an x64-based processor.

### Install in a moment

1. Download the installer that matches your computer.
2. Close Streamr if it is already running.
3. Run the installer and follow the setup steps.
4. Open Streamr from the Start menu or desktop shortcut.

Current installers are unsigned. Windows may show a security prompt; verify that the file came from this repository before running it.

## Stay up to date

New installers and release notes belong in this repository's **[Releases](../../releases)** section.

**Updates are currently manual.** Download the newer installer, close Streamr, and run it. Automatic update checking is not enabled in v0.1.1; a future release must integrate and configure the updater first.

This repository distributes application builds and documentation. Streamr's source code is maintained separately and does not need to be public.

## Your library travels with you

Your watchlist, viewing progress, and preferences are stored on your device.

Before changing computers or uninstalling:

1. Open **Settings → Export JSON** and save the backup somewhere safe.
2. Install Streamr on your other computer.
3. Open **Settings → Import JSON** and select your backup.

Import replaces existing library data and preferences after confirmation. Backups contain viewing history, so keep them private.

## Need a hand?

Open an **[issue](../../issues)** and include your Streamr version, Windows version, computer architecture, and steps to reproduce the problem. A screenshot or the exact error message can help.

Do not attach API keys, tokens, `.env` files, or personal library backups.

<details>
<summary><strong>About catalog information and playback</strong></summary>

Catalog information is supplied by TMDB and may be incomplete for some titles. Playback availability, progress reporting, and player controls depend on external providers and can vary by title or region.

This product uses the TMDB API but is not endorsed or certified by TMDB.

</details>

---

<div align="center">

<sub>Streamr · Good stories live here.</sub>

</div>
