<div align="center">

<img src="docs/img/favicon.png" alt="Shift" width="96" height="96">

# Shift

**Your whole library, one controller away.**

A controller-first game launcher for Windows handhelds, built for the Xbox Full Screen Experience.

[![Latest release](https://img.shields.io/github/v/release/red-Geck0/ShiftLauncher-releases?style=for-the-badge&label=latest&color=7c5cff)](../../releases/latest)
[![Total downloads](https://img.shields.io/github/downloads/red-Geck0/ShiftLauncher-releases/total?style=for-the-badge&label=downloads&color=2ea043)](../../releases)
[![Latest version downloads](https://img.shields.io/github/downloads/red-Geck0/ShiftLauncher-releases/latest/total?style=for-the-badge&label=this%20version&color=0ea5e9)](../../releases/latest)
[![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-0078d4?style=for-the-badge&logo=windows11&logoColor=white)](#system-requirements)

<a href="https://apps.microsoft.com/detail/9PJW4XLWDJLR?mode=direct"><img src="https://get.microsoft.com/images/en-us%20dark.svg" alt="Get it from Microsoft Store" width="170"></a>

[Download](#download) &nbsp;|&nbsp; [Features](#features) &nbsp;|&nbsp; [Screenshots](#screenshots) &nbsp;|&nbsp; [FAQ](#faq) &nbsp;|&nbsp; [Support](../../issues)

<br>

<img src="docs/img/hero-claw.webp" alt="Shift running on a Windows handheld" width="860">

</div>

<br>

## Features

- **Every store, one grid.** Steam, Epic Games, GOG, Xbox / Game Pass, Battle.net, Ubisoft Connect and EA app, all in one library.
- **Controller first.** D-pad, sticks, bumpers and an on-screen keyboard. Button hints at the bottom of the screen always show what does what.
- **Built for Xbox Full Screen Experience.** Tested on Windows 11 handhelds running Xbox mode, not just on a desktop.
- **Browse your store catalogs.** See games you own but have not installed yet, and start the install without leaving Shift.
- **Tags, not folders.** Put a game under as many tags as you like, with a built-in Tag Manager and auto tags per store.
- **Playtime tracking.** Recorded automatically and stored locally on your PC.
- **Themes and artwork.** Several layouts (360x, Bento, Spotlight, Shelf, Wall) with official store art or covers from SteamGridDB.
- **Release calendar.** Upcoming and newly added games at a glance.

## Screenshots

<table>
  <tr>
    <td width="50%"><img src="docs/img/shot-bento-theme.webp" alt="Bento theme"><br><sub><b>Bento theme</b></sub></td>
    <td width="50%"><img src="docs/img/shot-shelf-theme.webp" alt="Shelf theme"><br><sub><b>Shelf theme</b></sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="docs/img/shot-wall-theme.webp" alt="Wall theme"><br><sub><b>Wall theme</b></sub></td>
    <td width="50%"><img src="docs/img/shot-release-calendar.webp" alt="Release calendar"><br><sub><b>Release calendar</b></sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="docs/img/shot-gog-deals.webp" alt="GOG deals"><br><sub><b>Store catalogs and deals</b></sub></td>
    <td width="50%"><img src="docs/img/shot-tag-manager.webp" alt="Tag Manager"><br><sub><b>Tag Manager</b></sub></td>
  </tr>
</table>

## Download

| Source | Updates | Notes |
| --- | --- | --- |
| **[Microsoft Store](https://apps.microsoft.com/detail/9PJW4XLWDJLR)** (recommended) | Automatic | Signed by Microsoft, nothing to configure. |
| **[GitHub Releases](../../releases/latest)** | Built-in updater | Download the `.msi` and run it. |

Download counts above only cover GitHub. Installs from the Microsoft Store are counted separately.

## System requirements

- Windows 10 / 11 (x64), Windows 11 Xbox Full Screen Experience supported
- Steam installed for full Steam library support
- Xbox app installed for Game Pass detection

## FAQ

<details>
<summary><b>Windows says the installer is from an unknown publisher.</b></summary>
<br>
The GitHub <code>.msi</code> is not signed with a paid code-signing certificate, so SmartScreen may warn on first run. Choose <b>More info</b>, then <b>Run anyway</b>. The Microsoft Store build is signed by Microsoft and does not show this warning.
</details>

<details>
<summary><b>Does Shift update itself?</b></summary>
<br>
Yes. The Store version updates through the Store, and the GitHub version checks this repository for newer releases.
</details>

<details>
<summary><b>Do I need a mouse or keyboard?</b></summary>
<br>
No. Every screen is designed to be driven by a gamepad.
</details>

<details>
<summary><b>I found a bug.</b></summary>
<br>
Please <a href="../../issues">open an issue</a> and attach the log file from the device where it happened. Logs from the handheld help far more than a description.
</details>

## About this repository

This repository hosts installers and release notes only. Each version is published on the [Releases](../../releases) page, newest first.
