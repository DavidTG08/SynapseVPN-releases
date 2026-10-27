# SynapseVPN

A free VPN and security app for Windows 10 and 11: a one-click WireGuard VPN on Cloudflare WARP, threat protection, encrypted file sharing between your own PCs, and a Dark Web Monitor.

**Download:** [zynaps.site](https://zynaps.site/#vpn) or the newest installer under [Releases](https://github.com/DavidTG08/SynapseVPN-releases/releases/latest).
SynapseVPN updates itself, so you only download it once.

This repository only holds the installers and release notes.

## Guide

### Connect
Click **Secure my connection**. The first time, Windows asks for admin approval once to install the VPN engine. After that, Connect works without any prompt. On networks that block VPNs (like some school Wi-Fi), SynapseVPN tries other ports by itself.

### Threat protection
While the VPN is on, SynapseVPN blocks dangerous and phishing sites, trackers and ads in every app and browser. If a site stops working, open **Threat protection → Recently blocked** and click **Allow**. New downloads and files received over Meshnet are checked with Microsoft Defender.

### File transfers over Meshnet
1. Turn on **Meshnet** on both computers (File transfers page).
2. On one computer click **Link a device**; type the code on the other.
3. Drag files onto the linked computer, or click **Send file**. The other computer accepts once for all files sent together.

Files go straight from one PC to the other inside an encrypted WireGuard link, never through a server, of any size and without compression. They're saved in `Downloads\SynapseVPN` and checked when they arrive.

### Dark Web Monitor
Add your email and SynapseVPN checks it against known data breaches every day, and tells you when a new one appears. You can also check whether a password has leaked; the password itself never leaves your PC.

## Help
Email [support@zynaps.site](mailto:support@zynaps.site), or click **?** in the app for answers to common questions.

### "isn't commonly downloaded" warning
SynapseVPN is new, so Microsoft SmartScreen doesn't know it yet. In Edge, click **…** next to the download → **Keep** → **Show more** → **Keep anyway**. Only download SynapseVPN from zynaps.site or this page.
