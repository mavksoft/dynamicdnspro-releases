<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="Dynamic DNS Pro" width="96">
</p>

<h1 align="center">Dynamic DNS Pro</h1>

<p align="center">Halte deine Server immer erreichbar.<br>Automatisches DDNS für iOS und Android — deine IP in Sekunden synchronisiert, plus Windows-Agenten mit Audit und Remote-Desktop.</p>

<p align="center">
  <a href="https://dynamicdnspro.com"><img src="https://img.shields.io/badge/website-dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-iOS%20%C2%B7%20Android%20%C2%B7%20Windows-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fdynamicdnspro-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <strong>🇩🇪 Deutsch</strong> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Dieses Repository veröffentlicht ausschließlich offizielle Binär-Releases** — der Quellcode ist privat. Signierte Downloads, Prüfsummen und Auto-Update-Feeds.

## Download

| | |
|---|---|
| 📱 **Mobile App** | iOS und Android — kostenlos registrieren auf [dynamicdnspro.com](https://dynamicdnspro.com) |
| 🪟 **Agent (Windows)** | [DynamicDNSPro-Agent-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — IP-Updates, Geräte-Audit und Dienst-Monitoring |
| 🖥️ **Remote (Windows)** | [DynamicDNSPro-Remote-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — WebRTC-Remote-Desktop und sicherer Dateitransfer |
| 🌍 **Website** | [dynamicdnspro.com](https://dynamicdnspro.com) — Kundenportal, Pläne und FAQ |

## Was ist das

Dynamic DNS Pro verknüpft einen einprägsamen Namen (dein-server.dynamicdnspro.com) mit der wechselnden öffentlichen IP deines Netzwerks. Die App erkennt jeden Netzwechsel — WLAN zu 4G/5G, zu Hause und unterwegs — und aktualisiert den Eintrag in Sekunden. Keine Skripte, keine veralteten IPs: NAS, Server oder Kamera sind immer unter demselben Namen erreichbar.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funktionen

- **Sofort-Sync** — die App erkennt Netzwechsel (WLAN ↔ 4G/5G) und meldet die neue IP in Sekunden.
- **Intelligente Erkennung** — erkennt Proxys, VPNs und iCloud Private Relay, damit die IP auf dem Server immer die echte ist.
- **Interface-Auswahl** — erzwinge manuell, welches lokale Interface oder welcher VPN-Tunnel gemeldet wird.
- **Windows-Agent** — automatische IP-Updates, Geräte-Audit (inkl. SMART-Hardware) und Dienst-Monitoring.
- **Remote-Modul** — WebRTC-Remote-Desktop und sicherer Dateitransfer für Fernwartung.
- **Alarme** — E-Mail/Push bei IP-Wechsel oder Sync-Problemen (je nach Plan).
- **Multi-Domain** — bis zu 25 aktive Domains pro Konto je nach Plan.
- **Sechs Sprachen** — Website und Apps auf ES / EN / FR / IT / DE / PT.

## So wird es verwendet

1. Auf dynamicdnspro.com registrieren (Free-Plan) und deine Domain anlegen — z. B. `mein-nas.dynamicdnspro.com`.
2. Mobile App installieren und Domain verknüpfen: die IP aktualisiert sich bei jedem Netzwechsel von selbst.
3. Auf Windows-PCs, die erreichbar bleiben sollen, den Agent installieren — hält die IP im Hintergrund frisch und auditiert das Gerät.
4. Für Fernwartung das Remote-Modul installieren: WebRTC-Desktop und Dateitransfer aus dem Web-Panel.
5. Deine Dienste (VPN, NAS, Kameras) auf den DDNS-Namen zeigen lassen — unabhängig von der numerischen IP.

## Editionen & Preise

| Plan | Preis | Domains | Enthält |
|---|---|---|---|
| **Free** | 0 €/Monat | 1 | Manuelle + Background-Updates, IP-Wechsel-Alarme |
| **Basic** | 0,99 €/Monat | 5 | Background-Sync, E-Mail/Push-Alarme, Multi-Domain |
| **Pro** | 1,99 €/Monat | 15 | Prioritäts-Alarme, Interface-Config, 24/7-Support |
| **Elite** | 2,99 €/Monat | 25 | Alles aus Pro, für große Infrastrukturen |

## Voraussetzungen

iOS und Android für die mobile App · Windows für Agent und Remote · Jedes Release enthält `.sha256`-Prüfsummen aller Binärdateien.

## Was dieses Repository enthält

- `DynamicDNSPro-Agent-Setup-<Version>.exe` — Windows-Agent-Installer (DDNS + Audit + Monitoring)
- `DynamicDNSPro-Remote-Setup-<Version>.exe` — Remote-Modul-Installer (WebRTC + Dateien)
- `ddnspro-bin-<Version>.zip` — vollständige gepackte Binaries
- `ddns_engine.exe`, `agente_v3.exe`, `supervisor.exe`, `smartctl.exe` — Einzelkomponenten
- `*.sha256` — Prüfsummen für jede Datei
- `version.json`, `fleet.json` — Versions- und Fleet-Feeds für Auto-Update

[Neueste Version](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest)

## Häufige Fragen

**Was ist Dynamic DNS?**  
Es verknüpft einen festen Namen (dein-name.dynamicdnspro.com) mit einer wechselnden IP. Rotiert dein Provider die Adresse, löst der Name immer richtig auf.

**Kann ich die IP eines VPN-Interfaces melden?**  
Ja — ab dem Basic-Plan wählst du explizit, welches Interface oder welcher VPN-Tunnel gemeldet wird.

**Warum zwei Windows-Installer?**  
Agent hält dein DNS aktuell und auditiert das Gerät; Remote ergänzt WebRTC-Remote-Desktop und Dateitransfer. Installiere nur, was du brauchst.

## Support

- Website & Kundenportal: [dynamicdnspro.com](https://dynamicdnspro.com)
- FAQ: [dynamicdnspro.com#faq](https://dynamicdnspro.com/#faq)

---
<p align="center"><sub>Dynamic DNS Pro · © MavkSoft / IT-Systems</sub></p>
