<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="Dynamic DNS Pro" width="96">
</p>

<h1 align="center">Dynamic DNS Pro</h1>

<p align="center">Keep your servers always reachable.<br>Automatic DDNS for iOS and Android — your IP synced in seconds, plus Windows agents with auditing and remote desktop.</p>

<p align="center">
  <a href="https://dynamicdnspro.com"><img src="https://img.shields.io/badge/website-dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-iOS%20%C2%B7%20Android%20%C2%B7%20Windows-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-releases/"><img src="https://img.shields.io/static/v1?label=docs&message=mavksoft.github.io/dynamicdnspro-releases&color=blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <strong>🇬🇧 English</strong> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **This repository publishes official binary releases only** — the source code is private. Signed downloads, checksums and auto-update feeds.

## Download

| | |
|---|---|
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-releases/main/icons/apple.svg' width='15' style='vertical-align:-2px' alt='apple'><img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-releases/main/icons/android.svg' width='15' style='vertical-align:-2px' alt='android'> **Mobile app** | iOS and Android — sign up free at [dynamicdnspro.com](https://dynamicdnspro.com) |
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Agent (Windows)** | [DynamicDNSPro-Agent-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — IP updates, device audit and service monitoring |
| <img src='https://raw.githubusercontent.com/mavksoft/dynamicdnspro-releases/main/icons/windows.svg' width='15' style='vertical-align:-2px' alt='windows'> **Remote (Windows)** | [DynamicDNSPro-Remote-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — WebRTC remote desktop and secure file transfer |
| <img src='https://dynamicdnspro.com/assets/img/logo.png' width='15' style='vertical-align:-2px'> **Website** | [dynamicdnspro.com](https://dynamicdnspro.com) — client portal, plans and FAQ |

## What it is

Dynamic DNS Pro binds a memorable name (your-server.dynamicdnspro.com) to your network's changing public IP. The app detects every network change — Wi-Fi to 4G/5G, home to anywhere — and updates the record in seconds. No scripts, no stale IPs: reach your NAS, server or camera by the same name, always.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Features

- **Instant sync** — the mobile app detects network changes (Wi-Fi ↔ 4G/5G) and reports the new IP in seconds.
- **Smart detection** — recognizes proxies, VPNs and iCloud Private Relay so the IP on the server is always the real one.
- **Interface selection** — manually force which local interface or VPN tunnel to report for custom integrations.
- **Windows Agent** — automatic IP updates, device audit (including SMART hardware) and service monitoring.
- **Remote module** — WebRTC remote desktop and secure file transfer for assistance.
- **Alerts** — email/push notifications when the IP changes or something falls out of sync (per plan).
- **Multi-domain** — manage up to 25 active domains per account depending on plan.
- **Six languages** — website and apps in ES / EN / FR / IT / DE / PT.

## How to use it

1. Sign up at dynamicdnspro.com (Free plan) and create your domain — e.g. `my-nas.dynamicdnspro.com`.
2. Install the mobile app and link your domain: your IP updates itself on every network change.
3. On any Windows PC you want reachable, install the Agent — it keeps the IP fresh in the background and audits the machine.
4. For remote assistance, install the Remote module: WebRTC desktop and file transfer from the web panel.
5. Point your services (VPN, NAS, cameras) at the DDNS name — you no longer depend on the numeric IP.

## Editions & pricing

| Plan | Price | Domains | Includes |
|---|---|---|---|
| **Free** | €0/mo | 1 | Manual + background updates, IP-change alerts |
| **Basic** | €0.99/mo | 5 | Background sync, email/push alerts, multi-domain |
| **Pro** | €1.99/mo | 15 | Priority alerts, interface config, 24/7 support |
| **Elite** | €2.99/mo | 25 | Everything in Pro, for large infrastructures |

## Requirements

iOS and Android for the mobile app · Windows for Agent and Remote · Every release ships `.sha256` checksums for all binaries.

## What's in this repository

- `DynamicDNSPro-Agent-Setup-<version>.exe` — Windows agent installer (DDNS + audit + monitoring)
- `DynamicDNSPro-Remote-Setup-<version>.exe` — remote module installer (WebRTC + files)
- `ddnspro-bin-<version>.zip` — full packaged binaries
- `ddns_engine.exe`, `agente_v3.exe`, `supervisor.exe`, `smartctl.exe` — standalone components
- `*.sha256` — checksums for every binary
- `version.json`, `fleet.json` — version and fleet feeds for auto-update

[Latest release](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest)

## FAQ

**What is Dynamic DNS?**  
It binds a fixed name (your-name.dynamicdnspro.com) to a changing IP. When your ISP rotates the address, the name always resolves correctly.

**Can I report a VPN interface's IP?**  
Yes — from the Basic plan up you can explicitly choose which interface or VPN tunnel to report.

**Why two Windows installers?**  
Agent keeps your DNS current and audits the machine; Remote adds WebRTC remote desktop and file transfer. Install only what you need.

## Support

- Website & client portal: [dynamicdnspro.com](https://dynamicdnspro.com)
- FAQ: [dynamicdnspro.com#faq](https://dynamicdnspro.com/#faq)

---
<p align="center"><sub>Dynamic DNS Pro · © MavkSoft / IT-Systems</sub></p>
