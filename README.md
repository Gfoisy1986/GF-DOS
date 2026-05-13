
<p align="center">
  <img src="assets/logo.png" width="640">
</p>

🌌 GF‑DOS — Retro Computing Reborn
Un écosystème moderne conçu pour FreeDOS 1.4, les Pentium‑class machines, DOSBox, 86Box, et tout passionné de rétro‑computing qui veut ramener Internet dans le monde DOS.

GF‑DOS regroupe :

GF‑NetStack (DOS) — moteur réseau moderne

GF‑Web (DOS) — navigateur mobile‑friendly

GF‑DOS Wiki — documentation complète

GF‑DOS Hardware Guides — compatibilité matériel

GF‑DOS PCMCIA Drivers — exemples de drivers

GF‑DOS n’est pas un simple projet.
C’est un univers modulaire, pensé pour durer, documenter, et inspirer.

🚀 Objectifs du projet
Offrir un moteur réseau moderne pour DOS (HTTP, WebSocket, FTP, SMTP, POP3).

Ajouter le support TLS 1.2 via BearSSL DOS (HTTPS + wss://).

Créer un navigateur DOS moderne basé sur HTML mobile + UI curses.

Documenter comment connecter FreeDOS à Internet sur vrai hardware.

Fournir des drivers PCMCIA, guides, et exemples de configuration.

Construire un écosystème écologique, portable, modulaire, pour les développeurs rétro.

🧱 Modules GF‑DOS
1. GF‑NetStack (DOS)
Le cœur réseau de l’univers GF‑DOS.

Fonctionnalités actuelles :

HTTP 1.1

WebSocket ws://

FTP / SMTP / POP3

API simple pour C, Fortran, Lua

Build statique DJGPP pour FreeDOS 1.4

À venir :

TLS 1.2 (BearSSL DOS)

HTTPS

WebSocket sécurisé wss://

2. GF‑Web (DOS)
Le navigateur mobile‑friendly pour FreeDOS.

Fonctionnalités prévues :

rendu HTML mobile minimal

CSS minimal

images ASCII / blocs curses

interface curses moderne

recherche YouTube mobile

boutons “Télécharger”

WebSocket temps réel

HTTPS / wss:// (via BearSSL DOS)

GF‑Web est la vitrine de l’univers GF‑DOS.

3. GF‑DOS Wiki
Documentation officielle, claire et accessible.

Contient :

installation FreeDOS 1.4

setup réseau onboard

setup réseau PCMCIA

Packet Drivers

mTCP

API GF‑NetStack

UI GF‑Web

troubleshooting

4. GF‑DOS Hardware Guides
Guides pour connecter FreeDOS à Internet sur du vrai hardware.

Onboard Ethernet
Intel PRO/100

Broadcom 440x

Realtek RTL8139

Packet Drivers

DHCP

tests mTCP

PCMCIA
Socket Services

Card Services

3Com 3C589 / 3C562

Xircom RealPort

Intel EtherExpress PCMCIA

exemples de CONFIG.SYS / AUTOEXEC.BAT

5. GF‑DOS PCMCIA Driver Examples
Exemples complets pour configurer le réseau PCMCIA sous FreeDOS.

Code
DEVICE=SSPCIC.EXE
DEVICE=CS.EXE
DEVICE=CARDID.EXE
3C589PD.COM 0x60
DHCP
Avec explications, captures d’écran, et diagnostics.


🛠️ Build & Toolchain
GF‑DOS utilise :

DJGPP cross‑compiler (Ubuntu 24.04 → FreeDOS 1.4)

builds statiques .a

EXE DPMI 32‑bit compatibles FreeDOS

API portable C / Fortran / Lua

🤝 Contributions
GF‑DOS est conçu pour être :

modulaire

documenté

accessible

rétro‑écologique

Les contributions sont les bienvenues :
drivers, documentation, modules, tests sur vrai hardware.

🔥 Roadmap
[ ] GF‑NetStack DOS v0.1 (HTTP + WebSocket)

[ ] GF‑NetStack DOS v0.2 (FTP/SMTP/POP3)

[ ] BearSSL DOS port (TLS 1.2)

[ ] GF‑Web v0.1 (HTML mobile minimal)

[ ] GF‑Web v0.2 (images ASCII)

[ ] GF‑Web v0.3 (YouTube mobile + téléchargement)

[ ] GF‑Web v1.0 (HTTPS + wss://)

[ ] Wiki complet

[ ] Hardware guides

[ ] PCMCIA drivers

📬 Contact & Support
GF‑DOS est un projet passionné, conçu pour la communauté rétro.
Pour questions, idées, ou contributions :
→ ouvrir une issue dans le repo GitHub (à venir)
