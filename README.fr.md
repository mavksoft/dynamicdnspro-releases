<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="Dynamic DNS Pro" width="96">
</p>

<h1 align="center">Dynamic DNS Pro</h1>

<p align="center">Gardez vos serveurs toujours joignables.<br>DDNS automatique pour iOS et Android — votre IP synchronisée en quelques secondes, plus des agents Windows avec audit et bureau à distance.</p>

<p align="center">
  <a href="https://dynamicdnspro.com"><img src="https://img.shields.io/badge/website-dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-iOS%20%C2%B7%20Android%20%C2%B7%20Windows-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <strong>🇫🇷 Français</strong> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Ce dépôt publie uniquement les releases officielles** — le code source est privé. Téléchargements signés, sommes de contrôle et flux de mise à jour automatique.

## Téléchargement

| | |
|---|---|
| 📱 **App mobile** | iOS et Android — inscrivez-vous gratuitement sur [dynamicdnspro.com](https://dynamicdnspro.com) |
| 🪟 **Agent (Windows)** | [DynamicDNSPro-Agent-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — mise à jour IP, audit du poste et supervision |
| 🖥️ **Remote (Windows)** | [DynamicDNSPro-Remote-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — bureau à distance WebRTC et transfert de fichiers sécurisé |
| 🌍 **Site officiel** | [dynamicdnspro.com](https://dynamicdnspro.com) — portail client, forfaits et FAQ |

## Qu'est-ce que c'est

Dynamic DNS Pro associe un nom facile à retenir (votre-serveur.dynamicdnspro.com) à l'IP publique changeante de votre réseau. L'app détecte chaque changement de réseau — Wi-Fi vers 4G/5G, maison ou ailleurs — et met à jour l'enregistrement en quelques secondes. Fini les scripts et les IP périmées : votre NAS, serveur ou caméra reste joignable sous le même nom.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Fonctionnalités

- **Synchronisation instantanée** — l'app détecte les changements de réseau (Wi-Fi ↔ 4G/5G) et signale la nouvelle IP en quelques secondes.
- **Détection intelligente** — reconnaît proxies, VPN et iCloud Private Relay pour que l'IP enregistrée soit toujours la vraie.
- **Sélection d'interface** — forcez manuellement quelle interface locale ou tunnel VPN déclarer.
- **Agent Windows** — mise à jour IP automatique, audit du poste (matériel SMART inclus) et supervision de services.
- **Module Remote** — bureau à distance WebRTC et transfert de fichiers sécurisé pour l'assistance.
- **Alertes** — notifications email/push quand l'IP change ou qu'un élément se désynchronise (selon forfait).
- **Multi-domaine** — jusqu'à 25 domaines actifs par compte selon le forfait.
- **Six langues** — site et apps en ES / EN / FR / IT / DE / PT.

## Mode d'emploi

1. Inscrivez-vous sur dynamicdnspro.com (forfait Free) et créez votre domaine — ex. `mon-nas.dynamicdnspro.com`.
2. Installez l'app mobile et liez votre domaine : votre IP se met à jour seule à chaque changement de réseau.
3. Sur un PC Windows à garder joignable, installez l'Agent — il actualise l'IP en arrière-plan et audite la machine.
4. Pour l'assistance à distance, installez le module Remote : bureau WebRTC et transfert de fichiers depuis le panneau web.
5. Pointez vos services (VPN, NAS, caméras) sur le nom DDNS — plus besoin de l'IP numérique.

## Éditions et tarifs

| Forfait | Prix | Domaines | Inclut |
|---|---|---|---|
| **Free** | 0 €/mois | 1 | Mises à jour manuelles + background, alertes de changement d'IP |
| **Basic** | 0,99 €/mois | 5 | Sync en background, alertes email/push, multi-domaine |
| **Pro** | 1,99 €/mois | 15 | Alertes prioritaires, config. d'interface, support 24/7 |
| **Elite** | 2,99 €/mois | 25 | Tout Pro, pour les grandes infrastructures |

## Configuration requise

iOS et Android pour l'app mobile · Windows pour Agent et Remote · Chaque release fournit les sommes `.sha256` de tous les binaires.

## Contenu de ce dépôt

- `DynamicDNSPro-Agent-Setup-<version>.exe` — installateur de l'agent Windows (DDNS + audit + supervision)
- `DynamicDNSPro-Remote-Setup-<version>.exe` — installateur du module distant (WebRTC + fichiers)
- `ddnspro-bin-<version>.zip` — binaires complets empaquetés
- `ddns_engine.exe`, `agente_v3.exe`, `supervisor.exe`, `smartctl.exe` — composants autonomes
- `*.sha256` — sommes de contrôle de chaque binaire
- `version.json`, `fleet.json` — flux de version et de flotte pour l'auto-update

[Dernière version](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest)

## Questions fréquentes

**Qu'est-ce qu'un DNS dynamique ?**  
Il associe un nom fixe (votre-nom.dynamicdnspro.com) à une IP qui change. Quand votre opérateur change l'adresse, le nom résout toujours correctement.

**Puis-je déclarer l'IP d'une interface VPN ?**  
Oui — dès le forfait Basic, vous choisissez explicitement quelle interface ou quel tunnel VPN déclarer.

**Pourquoi deux installateurs Windows ?**  
Agent maintient votre DNS à jour et audite la machine ; Remote ajoute le bureau à distance WebRTC et le transfert de fichiers. Installez seulement ce qu'il vous faut.

## Assistance

- Site et portail client : [dynamicdnspro.com](https://dynamicdnspro.com)
- FAQ : [dynamicdnspro.com#faq](https://dynamicdnspro.com/#faq)

---
<p align="center"><sub>Dynamic DNS Pro · © MavkSoft / IT-Systems</sub></p>
