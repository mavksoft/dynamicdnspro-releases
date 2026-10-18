<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="Dynamic DNS Pro" width="96">
</p>

<h1 align="center">Dynamic DNS Pro</h1>

<p align="center">Mantén tus servidores siempre localizables.<br>DDNS automático para iOS y Android — tu IP sincronizada en segundos, más agentes Windows con auditoría y escritorio remoto.</p>

<p align="center">
  <a href="https://dynamicdnspro.com"><img src="https://img.shields.io/badge/website-dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-iOS%20%C2%B7%20Android%20%C2%B7%20Windows-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center">🌍 <strong>🇪🇸 Español</strong> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <a href="README.pt.md">🇵🇹 Português</a></p>

> **Este repositorio publica únicamente releases oficiales** — el código fuente es privado. Descargas firmadas, checksums y feeds de auto-actualización.

## Descarga

| | |
|---|---|
| 📱 **App móvil** | iOS y Android — regístrate gratis desde [dynamicdnspro.com](https://dynamicdnspro.com) |
| 🪟 **Agent (Windows)** | [DynamicDNSPro-Agent-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — actualización de IP, auditoría y monitorización |
| 🖥️ **Remote (Windows)** | [DynamicDNSPro-Remote-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — escritorio remoto WebRTC y transferencia de archivos |
| 🌍 **Web oficial** | [dynamicdnspro.com](https://dynamicdnspro.com) — acceso clientes, planes y FAQ |

## Qué es

Dynamic DNS Pro asocia un nombre fácil de recordar (tu-servidor.dynamicdnspro.com) con la IP pública dinámica de tu red. La app detecta cada cambio de red — de Wi-Fi a 4G/5G, de casa a cualquier sitio — y actualiza el registro en segundos. Olvídate de scripts y de IPs que caducan: accede a tu NAS, tu servidor o tu cámara siempre por el mismo nombre.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funciones

- **Sincronización instantánea** — la app móvil detecta los cambios de red (Wi-Fi ↔ 4G/5G) y reporta la nueva IP en segundos.
- **Detección inteligente** — reconoce proxies, VPNs e iCloud Private Relay para que la IP en el servidor sea siempre la real.
- **Selección de interfaz** — fuerza manualmente qué interfaz local o túnel VPN reportar para integraciones personalizadas.
- **Agente Windows** — actualización automática de IP, auditoría del equipo (hardware SMART incluido) y monitorización de servicios.
- **Módulo Remote** — escritorio remoto WebRTC y transferencia de archivos segura para asistencia.
- **Alertas** — avisos por email/push cuando cambia la IP o algo se desincroniza (según plan).
- **Multi-dominio** — gestiona hasta 25 dominios activos por cuenta según el plan.
- **Seis idiomas** — web y apps en ES / EN / FR / IT / DE / PT.

## Cómo se usa

1. Regístrate en dynamicdnspro.com (plan Free, gratis) y crea tu dominio — por ejemplo `mi-nas.dynamicdnspro.com`.
2. Instala la app móvil y vincula tu dominio: tu IP se actualiza sola cada vez que cambia la red.
3. En un PC con Windows que quieras mantener localizable, instala el Agent — actualiza la IP en segundo plano y audita el equipo.
4. Para asistencia remota, instala el módulo Remote: escritorio WebRTC y transferencia de archivos desde el panel web.
5. Apunta tus servicios (VPN, NAS, cámaras) al nombre DDNS — ya no dependes de la IP numérica.

## Ediciones y precios

| Plan | Precio | Dominios | Incluye |
|---|---|---|---|
| **Free** | 0 €/mes | 1 | Actualización manual + background, alertas de cambio de IP |
| **Basic** | 0,99 €/mes | 5 | Sincronización en background, alertas email/push, multi-dominio |
| **Pro** | 1,99 €/mes | 15 | Alertas prioritarias, config. de interfaz, soporte 24/7 |
| **Elite** | 2,99 €/mes | 25 | Todo Pro, para grandes infraestructuras |

## Requisitos

iOS y Android para la app móvil · Windows para Agent y Remote · Cada release incluye checksums `.sha256` de todos los binarios.

## Qué contiene este repositorio

- `DynamicDNSPro-Agent-Setup-<versión>.exe` — instalador del agente Windows (DDNS + auditoría + monitorización)
- `DynamicDNSPro-Remote-Setup-<versión>.exe` — instalador del módulo remoto (WebRTC + archivos)
- `ddnspro-bin-<versión>.zip` — binarios completos empaquetados
- `ddns_engine.exe`, `agente_v3.exe`, `supervisor.exe`, `smartctl.exe` — componentes sueltos
- `*.sha256` — checksums de cada binario
- `version.json`, `fleet.json` — feeds de versión y flota para auto-actualización

[Última release](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest)

## Preguntas frecuentes

**¿Qué es un Dynamic DNS?**  
Asocia un nombre fijo (tu-nombre.dynamicdnspro.com) a una IP que cambia. Si tu operadora te cambia la IP, el nombre siempre apunta bien.

**¿Puedo reportar la IP de una VPN?**  
Sí — desde los planes Basic puedes elegir explícitamente qué interfaz o túnel VPN reportar.

**¿Por qué hay dos instaladores de Windows?**  
Agent mantiene tu DNS al día y audita el equipo; Remote añade escritorio remoto WebRTC y transferencia de archivos. Puedes instalar solo el que necesites.

## Soporte

- Web y acceso clientes: [dynamicdnspro.com](https://dynamicdnspro.com)
- FAQ: [dynamicdnspro.com#faq](https://dynamicdnspro.com/#faq)

---
<p align="center"><sub>Dynamic DNS Pro · © MavkSoft / IT-Systems</sub></p>
