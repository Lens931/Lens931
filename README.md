# 👋 Salut, moi c’est Lens93

**Développeur indépendant — Web, FiveM/QBCore, sécurité serveur, IA locale, automatisation & outils créatifs.**

Je construis des systèmes concrets : jeux navigateur, outils de sécurité, interfaces modernes, scripts RP/FiveM, apps IA créatives comme **AIBeatMaker Studio**, bots IA, dashboards, backends, automatisations et infrastructures Linux/Docker.

Mon objectif est simple : **transformer des idées complexes en projets utilisables, propres et solides**.

---

## 🧭 Profil

Je suis un créateur autodidacte orienté **produit**, **sécurité**, **expérience utilisateur** et **expérimentation technique**.

J’aime construire des projets complets, du concept jusqu’au déploiement :

- architecture frontend/backend ;
- bases de données et logique métier ;
- interfaces modernes et responsives ;
- automatisation serveur ;
- sécurité applicative ;
- scripts FiveM/QBCore ;
- outils de monitoring ;
- IA locale et workflows créatifs ;
- bots et automatisations ;
- déploiement Linux, Apache, Docker et PostgreSQL.

Je ne cherche pas seulement à “coder des fonctions”.  
Je cherche à créer des systèmes cohérents, maintenables et utiles.

---

## 🔒 Pourquoi peu de repositories publics ?

La majorité de mes projets sont volontairement privés.

Une partie de mon travail touche à des sujets sensibles :

- sécurité serveur ;
- anti-cheat FiveM ;
- honeypots ;
- logique backend de jeux en production ;
- webhooks ;
- configurations serveur ;
- outils d’administration ;
- scripts exploitables si exposés publiquement ;
- prototypes IA ou produits encore en développement.

Par choix, je ne publie pas le code sensible pouvant compromettre la sécurité de mes projets, de mes serveurs ou de mes utilisateurs.

À la place, je privilégie :

- des études de cas ;
- des captures d’écran ;
- des documentations techniques ;
- des changelogs ;
- des aperçus d’architecture ;
- des versions showcase non sensibles.

> Code privé quand la sécurité l’exige.  
> Documentation publique quand elle permet de montrer le travail proprement.

---

## 🚀 Projets principaux

---

### 🥃 Omerta Empire

**Jeu navigateur mafia/prohibition développé en solo**, inspiré des anciens jeux de stratégie persistants comme Vendetta, OGame et les univers criminels des années 1930.

L’objectif : créer un jeu web stratégique, lent, addictif, mobile-friendly, avec une vraie identité visuelle **Art Déco / Mafia / Prohibition**.

**Stack principale :**

- React ;
- TypeScript ;
- Vite ;
- FastAPI ;
- PostgreSQL ;
- Redis ;
- Docker ;
- Apache ;
- WebSocket.

**Fonctionnalités développées :**

- économie persistante ;
- ressources produites en temps réel ;
- bâtiments et salles améliorables ;
- files d’attente de construction ;
- système PvP ;
- espionnage ;
- transports ;
- rapports de combat ;
- carte stratégique ;
- messagerie ;
- alliances ;
- panel admin ;
- dashboard temps réel ;
- interface responsive desktop/mobile.

**Ce que ce projet démontre :**

- conception full-stack ;
- logique de jeu persistante ;
- architecture API ;
- temps réel via WebSocket ;
- gestion de base de données ;
- design produit ;
- déploiement production ;
- résolution de bugs complexes.

---

### 🎛️ AIBeatMaker Studio

**AIBeatMaker Studio** est un projet créatif orienté musique assistée par IA, pensé comme un outil moderne pour générer, éditer, prévisualiser et exporter des boucles, instrumentales ou idées musicales.

L’objectif : construire une expérience proche d’un mini-studio musical, avec une interface claire, des contrôles rapides, une logique de génération audio et un workflow pensé pour les créateurs.

Ce projet ne se limite pas à une simple expérimentation IA : il vise à transformer la génération musicale en vrai outil utilisable, avec une logique produit, un backend local, un pipeline audio et une interface pensée pour produire rapidement des résultats exploitables.

**Démo audio :**

[![SoundCloud Sample](https://img.shields.io/badge/SoundCloud-Audio%20Sample-111111?style=for-the-badge&logo=soundcloud)](https://soundcloud.com/lens-93/instru-west-coast-2-93bpm-making-with-my-software-ia-free-to-use-or-download)

**Échantillon présenté :**  
*Instru West Coast 2 — 93 BPM*  
Instrumentale créée avec mon workflow logiciel IA, publiée comme démonstration sonore du potentiel d’AIBeatMaker Studio.

**Stack principale :**

- React ;
- TypeScript ;
- Vite ;
- Python ;
- FastAPI ;
- PyTorch ;
- modèles IA audio ;
- FFmpeg ;
- scripts desktop/local ;
- logique de traitement audio.

**Fonctionnalités visées / développées :**

- génération musicale assistée par IA ;
- création de loops instrumentaux ;
- variations audio ;
- previews rapides ;
- édition non destructive ;
- exports audio ;
- pipeline de traitement sonore ;
- interface type studio moderne ;
- backend local ;
- logique de jobs de génération ;
- intégration de modèles IA audio ;
- workflow pensé pour beatmakers, créateurs de contenu et producteurs indépendants.

**Ce que ce projet démontre :**

- intégration d’IA créative ;
- conception d’un produit audio complexe ;
- architecture frontend/backend locale ;
- traitement audio ;
- expérimentation avec des modèles génératifs ;
- capacité à transformer une idée IA en logiciel utilisable ;
- vision produit autour de la création musicale ;
- capacité à produire un résultat sonore concret, pas seulement une interface ou un prototype.
  
### 🛡️ LSVAC Anti-Cheat

**Système de protection pour serveurs FiveM/QBCore**, conçu pour renforcer la sécurité, surveiller les comportements suspects et protéger les ressources critiques.

**Fonctionnalités principales :**

- détections côté client et serveur ;
- logs Discord détaillés ;
- système de ban persistant ;
- vérification d’intégrité de fichiers ;
- surveillance d’entités suspectes ;
- protection contre certains abus d’events ;
- alertes administrateur ;
- logique de whitelist ;
- modules standalone.

**Ce que ce projet démontre :**

- compréhension de l’écosystème FiveM ;
- logique de sécurité serveur ;
- gestion d’événements réseau ;
- logging structuré ;
- architecture modulaire ;
- prévention des abus sans exposer de logique exploitable.

---

### 🕷️ RedTigerTrap / Obsidian Firewall

**Honeypot Flask et outil de détection de comportements web suspects**, pensé pour identifier les bots, scanners, tentatives d’intrusion et reconnaissances automatisées.

**Fonctionnalités principales :**

- endpoints leurres ;
- scoring IP ;
- logs enrichis ;
- alertes Discord ;
- catégorisation des comportements suspects ;
- détection de patterns ;
- ralentissement volontaire de certains bots ;
- intégration Fail2Ban ;
- approche défensive et observabilité.

**Ce que ce projet démontre :**

- développement Python ;
- sécurité web défensive ;
- analyse de comportements ;
- automatisation de réponses ;
- intégration système Linux ;
- monitoring et alerting.

---

### 🎮 Scripts FiveM / QBCore

Développement de scripts personnalisés pour serveurs RP, Freeroam et expériences immersives.

**Types de systèmes développés :**

- HUD modernes ;
- menus VIP ;
- systèmes de missions ;
- maisons portables ;
- décoration persistante ;
- systèmes de primes ;
- garages ;
- drift rewards ;
- interactions PNJ ;
- systèmes de police/ambulance ;
- outils admin ;
- protections serveur.

**Ce que ces projets démontrent :**

- maîtrise de Lua ;
- intégration QBCore ;
- logique client/serveur ;
- optimisation des threads ;
- UX en jeu ;
- menus, notifications et interactions immersives.

---

### 🤖 Bots IA & automatisation

Expériences autour de l’IA locale, des bots live et de l’automatisation.

**Domaines explorés :**

- LM Studio ;
- modèles locaux ;
- bots Twitch/TikTok ;
- synthèse vocale ;
- interactions live ;
- Python ;
- Playwright ;
- Selenium ;
- workflows d’automatisation.

**Ce que ces projets démontrent :**

- intégration IA locale ;
- automatisation navigateur ;
- interaction temps réel ;
- scripts Python orientés usage concret ;
- expérimentation produit.

---

## 🧰 Stack technique

### Frontend

![React](https://img.shields.io/badge/React-111111?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-111111?style=for-the-badge&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-111111?style=for-the-badge&logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-111111?style=for-the-badge&logo=javascript)
![HTML5](https://img.shields.io/badge/HTML5-111111?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-111111?style=for-the-badge&logo=css3)

### Backend

![Python](https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=for-the-badge&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=for-the-badge&logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-111111?style=for-the-badge&logo=redis)

### IA / Audio / Automatisation

![PyTorch](https://img.shields.io/badge/PyTorch-111111?style=for-the-badge&logo=pytorch)
![Python](https://img.shields.io/badge/Automation-111111?style=for-the-badge&logo=python)
![FFmpeg](https://img.shields.io/badge/FFmpeg-111111?style=for-the-badge&logo=ffmpeg)

### Game Dev / FiveM

![Lua](https://img.shields.io/badge/Lua-111111?style=for-the-badge&logo=lua)
![FiveM](https://img.shields.io/badge/FiveM-111111?style=for-the-badge)
![QBCore](https://img.shields.io/badge/QBCore-111111?style=for-the-badge)

### Infrastructure

![Linux](https://img.shields.io/badge/Linux-111111?style=for-the-badge&logo=linux)
![Docker](https://img.shields.io/badge/Docker-111111?style=for-the-badge&logo=docker)
![Apache](https://img.shields.io/badge/Apache-111111?style=for-the-badge&logo=apache)
![Git](https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-111111?style=for-the-badge&logo=github)

---

## 🧩 Domaines où je suis le plus actif

| Domaine | Ce que je construis |
|---|---|
| Web full-stack | Interfaces, API, dashboards, jeux navigateur |
| FiveM/QBCore | Scripts RP, systèmes serveur, interactions, HUD |
| Sécurité | Honeypots, anti-cheat, logs, monitoring |
| Infrastructure | Docker, Apache, Linux, reverse proxy, déploiement |
| IA locale | Bots, workflows, intégrations LM Studio |
| IA créative / audio | Génération musicale, previews, exports, pipeline audio |
| Automatisation | Scripts Python, Playwright, outils pratiques |

---

## 🎯 Ce que je construis actuellement

- 🥃 **Omerta Empire** — jeu navigateur mafia/prohibition full-stack.
- 🎛️ **AIBeatMaker Studio** — workstation IA pour générer, éditer et exporter de la musique.
- 🛡️ **Outils de sécurité serveur** pour FiveM et environnements web.
- 🎮 **Scripts FiveM/QBCore** plus propres, immersifs et optimisés.
- 🤖 **Bots IA locaux** pour live, RP et automatisation.
- 🌐 **Interfaces web modernes** avec identité visuelle forte.
- 🧰 **Documentations showcase** pour présenter mes projets sans exposer le code sensible.

---

## 💡 Ce qui m’intéresse

- Architecture full-stack.
- Sécurité applicative.
- Jeux navigateur persistants.
- Expériences RP/FiveM.
- Interfaces premium.
- Automatisation.
- IA locale.
- IA créative.
- Audio génératif.
- Observabilité serveur.
- Outils utiles pour créateurs, admins et communautés.

---

## 🧱 Ma philosophie

> Construire petit à petit, mais construire du solide.

Je préfère avancer avec des projets concrets, testables et améliorables plutôt que simplement accumuler des idées.

Un bon projet, pour moi, doit être :

- utile ;
- lisible ;
- maintenable ;
- sécurisé ;
- agréable à utiliser ;
- améliorable dans le temps.

Je ne cherche pas la perfection immédiate.  
Je cherche la progression constante.

---

## 📌 Ce que je veux montrer ici

Ce profil GitHub n’est pas une simple collection de repositories publics.

C’est une vitrine technique de mon parcours :

- ce que je construis ;
- les domaines que j’explore ;
- les problèmes que je résous ;
- les systèmes que je suis capable d’imaginer, développer et maintenir.

Certains projets restent privés pour des raisons de sécurité, mais le travail existe, évolue et se structure progressivement.

---

## 📊 GitHub Stats

![Lens93 GitHub stats](https://github-readme-stats.vercel.app/api?username=Lens931&show_icons=true&theme=dark&hide_border=true)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Lens931&layout=compact&theme=dark&hide_border=true)

---

## 🌍 Me retrouver

- 🌐 Portfolio : [lens93.dev](https://lens93.dev)
- 💬 Discord : `Lens93`
- 🧪 GitHub : [github.com/Lens931](https://github.com/Lens931)

---

## ⚡ Fun fact

Je peux commencer la journée sur un backend FastAPI, passer sur un script FiveM l’après-midi, corriger une config Apache le soir, puis finir sur une interface mafia Art Déco, un honeypot Flask ou un prototype musical avec IA.

Pas toujours académique.  
Mais toujours en train de construire.
