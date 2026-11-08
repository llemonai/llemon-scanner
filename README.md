# llemonAI Wi-Fi Scanner

Free Wi-Fi scanning and diagnostics tool for Windows, macOS and Android.

- **Website:** https://llemonai.in
- **Download:** https://llemonai.in/scanner.html#download
- **Latest release:** https://github.com/llemonai/llemon-scanner/releases/latest

## What it does

- Live network scanning — SSID, BSSID, vendor, channel, band, width, RSSI, PHY type, security, and more
- Raw 802.11 beacon frame decoding — full information-element table with hex and human-readable decoding
- Signal history (RSSI vs. time) and 2.4GHz/5GHz channel usage charts
- One-click field-ready PDF export with host diagnostics, location, ISP, and weather
- Built-in printable Field Engineer Checklist for site visits
- AI Companion troubleshooting interview, M-Lab speed test and Network Devices discovery
- About → Check for updates downloads a newer release, checks its SHA-256 checksum and installs it (nothing is checked unless you click it)
- AI chat assistant on the website that can answer questions using your own exported PDF report

## Requirements

Windows 10 (build 19041+) or Windows 11, 64-bit or 32-bit. No installer, no admin rights, no separate .NET runtime install — single self-contained `.exe`.

Android 8.0 (API 26) or later, as a sideloaded `.apk`.

macOS 12 Monterey or later, Apple Silicon or Intel (one universal app, `.dmg` or `.zip`). Allow Location when asked: macOS only shows network names and BSSIDs to apps with Location access. The app isn't notarized by Apple, so the first time right-click it in Applications and choose Open.

Since 16.0.0 every platform shares one version number, and each release holds all the files: `llemonAI-WiFi-Scanner-<version>-win-x64.exe`, `-win-x86.exe`, `-android.apk`, `-macos.dmg` and `-macos.zip`, with `SHA256SUMS.txt`.

## Repo contents

This repository holds only the public website and release binaries — not the application's source code.

- `index.html` — the website home page (hosted via GitHub Pages at llemonai.in)
- `scanner.html` — the llemonAI Wi-Fi Scanner page; `reader.html` — the llemonAI Reader page; `organizer.html` — the llemonAI PDF Organizer page
- `screenshots/` — in-app screenshots used on the site
- Release assets (under [Releases](https://github.com/llemonai/llemon-scanner/releases)) — the downloadable llemonAI Wi-Fi Scanner files

## More from llemonai

**llemonAI Reader** is a free PDF reader, annotator and presentation tool for Windows, macOS and Android. Details are at https://llemonai.in/reader.html, and downloads at https://github.com/llemonai/llemon-reader/releases.

**llemonAI PDF Organizer** is a free PDF organizer for Windows, macOS and Android that changes the resolution page by page — shrink the photos and scans, keep text pages sharp. Details are at https://llemonai.in/organizer.html, and downloads at https://github.com/llemonai/llemon-organizer/releases.

## Contact

llemonai.us@gmail.com
