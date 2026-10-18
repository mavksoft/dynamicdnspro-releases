<p align="center">
  <img src="https://dynamicdnspro.com/assets/img/logo.png" alt="Dynamic DNS Pro" width="96">
</p>

<h1 align="center">Dynamic DNS Pro</h1>

<p align="center">Mantenha os seus servidores sempre acessíveis.<br>DDNS automático para iOS e Android — o seu IP sincronizado em segundos, mais agentes Windows com auditoria e desktop remoto.</p>

<p align="center">
  <a href="https://dynamicdnspro.com"><img src="https://img.shields.io/badge/website-dynamicdnspro.com-0A84FF" alt="website"></a>
  <a href="https://github.com/mavksoft/dynamicdnspro-releases/releases/latest"><img src="https://img.shields.io/github/v/release/mavksoft/dynamicdnspro-releases?label=latest" alt="latest release"></a>
  <img src="https://img.shields.io/badge/platform-iOS%20%C2%B7%20Android%20%C2%B7%20Windows-black" alt="platforms">
  <img src="https://img.shields.io/badge/license-commercial-orange" alt="commercial license">
</p>

<p align="center"><a href="https://mavksoft.github.io/dynamicdnspro-releases/"><img src="https://img.shields.io/badge/docs-mavksoft.github.io%2Fdynamicdnspro-releases-blue" alt="docs"></a></p>

<p align="center">🌍 <a href="README.es.md">🇪🇸 Español</a> · <a href="README.md">🇬🇧 English</a> · <a href="README.de.md">🇩🇪 Deutsch</a> · <a href="README.fr.md">🇫🇷 Français</a> · <a href="README.it.md">🇮🇹 Italiano</a> · <strong>🇵🇹 Português</strong></p>

> **Este repositório publica apenas releases binários oficiais** — o código-fonte é privado. Downloads assinados, checksums e feeds de atualização automática.

## Transferir

| | |
|---|---|
| 📱 **App móvel** | iOS e Android — registe-se grátis em [dynamicdnspro.com](https://dynamicdnspro.com) |
| 🪟 **Agent (Windows)** | [DynamicDNSPro-Agent-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — atualização de IP, auditoria do dispositivo e monitorização de serviços |
| 🖥️ **Remote (Windows)** | [DynamicDNSPro-Remote-Setup.exe](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest) — desktop remoto WebRTC e transferência de ficheiros segura |
| 🌍 **Site oficial** | [dynamicdnspro.com](https://dynamicdnspro.com) — portal de cliente, planos e FAQ |

## O que é

O Dynamic DNS Pro associa um nome fácil de memorizar (o-seu-servidor.dynamicdnspro.com) ao IP público variável da sua rede. A app deteta cada mudança de rede — de Wi-Fi para 4G/5G, de casa para qualquer lado — e atualiza o registo em segundos. Esqueça scripts e IPs desatualizados: aceda ao NAS, servidor ou câmara sempre pelo mesmo nome.

<p align="center"><img src="./screenshots/website.png" width="640" alt="screenshot"></p>

## Funcionalidades

- **Sincronização instantânea** — a app deteta mudanças de rede (Wi-Fi ↔ 4G/5G) e reporta o novo IP em segundos.
- **Deteção inteligente** — reconhece proxies, VPNs e iCloud Private Relay para que o IP no servidor seja sempre o real.
- **Seleção de interface** — force manualmente que interface local ou túnel VPN reportar.
- **Agente Windows** — atualização automática de IP, auditoria do dispositivo (hardware SMART incluído) e monitorização de serviços.
- **Módulo Remote** — desktop remoto WebRTC e transferência de ficheiros segura para assistência.
- **Alertas** — notificações email/push quando o IP muda ou algo sai de sincronia (consoante o plano).
- **Multi-domínio** — até 25 domínios ativos por conta consoante o plano.
- **Seis idiomas** — site e apps em ES / EN / FR / IT / DE / PT.

## Como usar

1. Registe-se em dynamicdnspro.com (plano Free) e crie o seu domínio — ex. `meu-nas.dynamicdnspro.com`.
2. Instale a app móvel e associe o domínio: o seu IP atualiza-se sozinho a cada mudança de rede.
3. Num PC Windows que queira manter acessível, instale o Agent — mantém o IP atualizado em segundo plano e audita a máquina.
4. Para assistência remota, instale o módulo Remote: desktop WebRTC e transferência de ficheiros a partir do painel web.
5. Aponte os seus serviços (VPN, NAS, câmaras) para o nome DDNS — deixa de depender do IP numérico.

## Edições e preços

| Plano | Preço | Domínios | Inclui |
|---|---|---|---|
| **Free** | 0 €/mês | 1 | Atualização manual + background, alertas de mudança de IP |
| **Basic** | 0,99 €/mês | 5 | Sincronização em background, alertas email/push, multi-domínio |
| **Pro** | 1,99 €/mês | 15 | Alertas prioritários, config. de interface, suporte 24/7 |
| **Elite** | 2,99 €/mês | 25 | Tudo do Pro, para grandes infraestruturas |

## Requisitos

iOS e Android para a app móvel · Windows para Agent e Remote · Cada release inclui checksums `.sha256` de todos os binários.

## O que contém este repositório

- `DynamicDNSPro-Agent-Setup-<versão>.exe` — instalador do agente Windows (DDNS + auditoria + monitorização)
- `DynamicDNSPro-Remote-Setup-<versão>.exe` — instalador do módulo remoto (WebRTC + ficheiros)
- `ddnspro-bin-<versão>.zip` — binários completos empacotados
- `ddns_engine.exe`, `agente_v3.exe`, `supervisor.exe`, `smartctl.exe` — componentes avulsos
- `*.sha256` — checksums de cada binário
- `version.json`, `fleet.json` — feeds de versão e frota para auto-atualização

[Versão mais recente](https://github.com/mavksoft/dynamicdnspro-releases/releases/latest)

## Perguntas frequentes

**O que é um DNS dinâmico?**  
Associa um nome fixo (o-seu-nome.dynamicdnspro.com) a um IP que muda. Quando a operadora muda o endereço, o nome resolve sempre corretamente.

**Posso reportar o IP de uma interface VPN?**  
Sim — a partir do plano Basic pode escolher explicitamente que interface ou túnel VPN reportar.

**Porque há dois instaladores Windows?**  
O Agent mantém o seu DNS atualizado e audita a máquina; o Remote acrescenta desktop remoto WebRTC e transferência de ficheiros. Instale apenas o que precisar.

## Suporte

- Site e portal de cliente: [dynamicdnspro.com](https://dynamicdnspro.com)
- FAQ: [dynamicdnspro.com#faq](https://dynamicdnspro.com/#faq)

---
<p align="center"><sub>Dynamic DNS Pro · © MavkSoft / IT-Systems</sub></p>
