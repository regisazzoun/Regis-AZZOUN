# Bonjour, bienvenue sur mon GitHub 👋

[🇬🇧 **English version ↓**](#english-version)

## Enseignement, réseaux, électronique et intelligence artificielle

Je suis **enseignant en Bac Pro CIEL** (*Cybersécurité, Informatique et réseaux, Électronique*), en **BTS SIO option SISR** (*Solutions d'Infrastructure, Systèmes et Réseaux*) et en **Passerelle BTS**. J'accompagne les apprenants à différents niveaux, depuis la découverte des systèmes et réseaux jusqu'à l'administration d'infrastructures et la préparation à l'enseignement supérieur. Je développe des environnements techniques et des supports pédagogiques qui rapprochent les apprentissages des situations réelles : réseaux d'entreprise, serveurs, supervision, systèmes embarqués, automatisation et, désormais, intelligence artificielle locale.

Ce GitHub rassemble mes **projets en cours**, mes expérimentations et, progressivement, des ressources partageables. Je privilégie les travaux pratiques reproductibles, l'autonomie des élèves et les retours d'expérience — y compris lorsque les essais ne fonctionnent pas du premier coup.

> **Fil conducteur :** expérimenter, comprendre, documenter, corriger et transmettre.

## 🚀 Projets en cours

### 🤖 JARVIS — laboratoire d'IA locale

Un laboratoire visant à construire un assistant IA utilisable localement, capable de travailler sur des documents, du code et, à terme, des tâches d'administration et d'automatisation.

Deux plateformes complémentaires :
- **Mac mini sous Debian**, avec **Razer Core / eGPU NVIDIA** : terrain expérimental pour Thunderbolt, pilotes, CUDA, Ollama et Open WebUI.
- **Dell Precision 5820**, i9-10980XE, **128 Go de RAM**, architecture envisagée avec **deux RTX 3090** : plateforme destinée à des expérimentations plus puissantes et reproductibles.

L'approche est volontairement pragmatique : valider la faisabilité, noter les obstacles, conserver les résultats mesurés et ne pas bloquer une expérimentation sur chaque anomalie mineure.

La documentation technique est construite à partir des **missions Codex** et de leurs comptes rendus. Le dépôt du laboratoire est actuellement privé, dans l'attente de la vérification des informations publiables.

### 🌐 Réseaux Cisco, VLAN et virtualisation

Étude et évolution d'une infrastructure réseau pédagogique et d'établissement :
- Segmentation **VLAN**, trunks Cisco, adressage et administration des commutateurs.
- Liaison entre infrastructure physique, **VMware ESXi** et serveurs **Windows Server**.
- Documentation des configurations, de la topologie et des procédures de maintenance.
- Réflexion sur un VLAN de management, la hiérarchie des équipements et la supervision.

### 📡 Supervision réseau avec Nagios

Conception de procédures et de travaux pratiques autour de **Nagios Core sur Raspberry Pi** :
- Installation et supervision d'hôtes et de services.
- Dépendances parent/enfant et hiérarchie de connectivité.
- Suivi des équipements réseau, accès Internet, pare-feu, virtualisation et stockage.
- Vérifications intermédiaires, questionnaires et grilles d'évaluation pour les élèves.

### 🦾 Bras robotisé Arduino

Développement d'une séquence de travaux pratiques autour d'un **bras robotisé à six servomoteurs**, piloté par **Arduino Mega** :
- Commande avec **trois joysticks PS2** ou une **Wii Nunchuk en I²C**.
- Gestion des zones mortes, du calibrage et des correspondances entre commandes et axes.
- Conception de circuits imprimés et initiation à **Fritzing**.
- Progression différenciée entre classes de Seconde et de Première.

Chaque séance vise à associer un **TP élève**, une **guidance documentaire**, des **indices progressifs (« coup de pouce »)** et un **corrigé enseignant**, avec une charte commune.

### 📰 Veille technologique et cybersécurité sur Raspberry Pi

Développement d'un dispositif d'affichage de veille :
- Agrégation de flux **RSS** sur l'actualité informatique et la cybersécurité.
- Serveur **Node.js**, base **SQLite**, interface Web et traduction en français.
- Affichage d'une **carte d'événements de cybersécurité**.
- Déploiement sur **Raspberry Pi 4**, avec travaux autour de **Docker**, **PM2** et **systemd**.
- Transformation de la solution en travaux pratiques progressifs.

### 🎓 Enseignement : Bac Pro CIEL, BTS SIO SISR et Passerelle BTS

Mon activité pédagogique s'articule autour de trois parcours complémentaires :

- **Bac Pro CIEL** : acquisition des fondamentaux en électronique, informatique, réseaux, cybersécurité et systèmes embarqués ; mise en pratique sur des équipements réels.
- **BTS SIO — option SISR** : approfondissement des infrastructures, de l'administration des systèmes et réseaux, de la virtualisation, de la supervision, de la sécurité et de l'automatisation.
- **Passerelle BTS** : accompagnement de la transition vers l'enseignement supérieur, consolidation des prérequis, montée en autonomie, méthodes de diagnostic et conduite de projets.

Je cherche à créer des **continuités pédagogiques** entre ces formations, avec des situations techniques pouvant être reprises à plusieurs niveaux : une même infrastructure réseau peut servir à découvrir un VLAN, puis à traiter le routage, l'administration, la supervision et la sécurisation.

Les ressources développées comprennent :
- Des progressions et des **TP de trois heures**, avec objectifs, prérequis et points de contrôle.
- Des documents de **guidance élève** et des aides graduées (« coups de pouce ») pour favoriser la recherche autonome.
- Des **corrigés enseignants**, barèmes, questionnaires et grilles d'évaluation.
- Des projets interdisciplinaires combinant réseaux, Linux, virtualisation, électronique et IA locale.
- Des supports pour les **PFMP**, l'orientation et la poursuite d'études.

Parmi les chantiers structurants : la préparation de ressources pour les classes passerelles et la réflexion sur le développement d'une offre **BTS SIO** au sein de l'établissement.

### 📝 Formulaires et outils Web pour la PFMP

Développement d'outils destinés au suivi et à la saisie mobile :
- Formulaires avec cases à cocher, photographies, signatures et génération de PDF.
- Réflexion sur l'hébergement et la diffusion des outils.
- Dépôt existant : **[FormulairePFMP](https://github.com/regisazzoun/FormulairePFMP)**.

## 🔧 Technologies utilisées ou explorées

**Réseaux et systèmes :** Cisco IOS · VLAN · SSH · Debian/Linux · Raspberry Pi · Windows Server · VMware ESXi · Nagios

**Développement et automatisation :** Python · JavaScript / Node.js · Bash · PowerShell · SQLite · Docker · Git / GitHub · systemd

**Électronique et fabrication :** Arduino Mega · ESP32 · servomoteurs · I²C · Fritzing · PCB · impression 3D

**IA locale :** NVIDIA CUDA · GPU/eGPU · Ollama · Open WebUI · modèles de langage · Codex

## 📚 Ma démarche pédagogique

Mes projets ne sont pas seulement des démonstrateurs : ils servent aussi à construire des apprentissages. J'essaie de conjuguer :
1. Une **mise en situation concrète**, sur du matériel et des services réels.
2. Une **progression adaptée au niveau** des élèves et étudiants, du Bac Pro à la Passerelle BTS et au BTS SIO SISR.
3. Des **consignes guidées sans donner immédiatement toutes les réponses**.
4. Des **points de contrôle et une évaluation explicite**.
5. Une documentation assez claire pour être réutilisée et améliorée.

## 🤝 Partage et contributions

Je souhaite partager progressivement des procédures, des scripts, des séquences pédagogiques et des bilans expérimentaux. Les projets présentés peuvent être **en cours de développement** : leur présence ici ne signifie pas que toutes les fonctionnalités sont achevées ou validées.

Les échanges constructifs sur la reproductibilité, l'accessibilité des ressources et les usages pédagogiques sont les bienvenus.

---

*Profil et projets mis à jour en octobre 2026.*

---

## English version

[🇫🇷 Retour à la version française ↑](#bonjour-bienvenue-sur-mon-github-)

### Teaching, networking, electronics and artificial intelligence

I teach **Bac Pro CIEL** (*Cybersecurity, Computer Science and Networks, Electronics*), **BTS SIO — SISR track** (*IT Services for Organizations — Infrastructure, Systems and Network Solutions*), and **Passerelle BTS** (a bridging programme towards higher technical education). I support learners at different stages, from discovering computer systems and networks to managing infrastructure and preparing for higher education. I develop technical environments and teaching materials rooted in real-world situations: enterprise networks, servers, monitoring, embedded systems, automation and, more recently, local artificial intelligence.

This GitHub profile brings together my **ongoing projects**, experiments and, progressively, resources that can be shared. I value reproducible hands-on labs, learner autonomy and lessons learned — including when an experiment does not work on the first attempt.

> **Guiding principle:** experiment, understand, document, improve and share knowledge.

### 🚀 Ongoing projects

#### 🤖 JARVIS — Local AI laboratory

An experimental lab aimed at building a locally hosted AI assistant for working with documents, code and, eventually, system administration and automation tasks.

Two complementary hardware platforms:
- **Debian-based Mac mini** with a **Razer Core / NVIDIA eGPU**: an experimental setup for Thunderbolt, drivers, CUDA, Ollama and Open WebUI.
- **Dell Precision 5820**, i9-10980XE, **128 GB RAM**, with a proposed architecture using **two RTX 3090 GPUs**: intended for more powerful and reproducible experiments.

My approach is pragmatic: establish feasibility, record obstacles, retain measured results and avoid holding up an experiment over every minor issue.

Technical documentation is based on **Codex missions** and their reports. The lab repository is currently private while its contents are reviewed for public release.

#### 🌐 Cisco networking, VLANs and virtualization

Studying and evolving a teaching and school network infrastructure:
- **VLAN** segmentation, Cisco trunks, IP addressing and switch administration.
- Connecting physical infrastructure to **VMware ESXi** and **Windows Server** systems.
- Documenting configurations, network topology and maintenance procedures.
- Exploring management VLANs, equipment hierarchy and network monitoring.

#### 📡 Network monitoring with Nagios

Developing procedures and practical labs around **Nagios Core on Raspberry Pi**:
- Installation and host/service monitoring.
- Parent/child dependencies and connectivity hierarchy.
- Monitoring network equipment, Internet connectivity, firewalls, virtualization and storage.
- Intermediate checks, student questionnaires and assessment rubrics.

#### 🦾 Arduino robotic arm

Designing practical lessons around a **six-servo robotic arm** controlled with an **Arduino Mega**:
- Control using **three PS2 joysticks** or a **Wii Nunchuk over I²C**.
- Dead zones, calibration and mapping controls to axes.
- Printed circuit board design and introduction to **Fritzing**.
- Different learning progressions for French *Seconde* and *Première* students.

Each session is designed with a **student lab handout**, a **guided research document**, **progressive hints** and a **teacher's answer key**, all following a consistent layout.

#### 📰 Technology and cybersecurity news dashboard on Raspberry Pi

Developing a technology news display system:
- Aggregating **RSS feeds** covering IT and cybersecurity news.
- **Node.js** server, **SQLite** database, web interface and French translation.
- Displaying a **cybersecurity event map**.
- Deployment on **Raspberry Pi 4**, including **Docker**, **PM2** and **systemd**.
- Turning the implementation into progressive hands-on lessons.

#### 🎓 Teaching: Bac Pro CIEL, BTS SIO SISR and Passerelle BTS

My teaching activity spans three complementary pathways:

- **Bac Pro CIEL**: foundations in electronics, computing, networking, cybersecurity and embedded systems, with practical work on real equipment.
- **BTS SIO — SISR track**: deeper work on IT infrastructure, systems and network administration, virtualization, monitoring, security and automation.
- **Passerelle BTS**: supporting the transition to higher education through foundational knowledge, autonomy, diagnostic methods and project-based learning.

I aim to build **continuity between these programmes** through technical scenarios adaptable to several levels. A single network infrastructure, for instance, can be used to introduce VLANs and later explore routing, administration, monitoring and security.

The resources I develop include:
- Teaching sequences and **three-hour practical labs**, with objectives, prerequisites and checkpoints.
- **Student guidance documents** and graduated hints to encourage independent research.
- **Teacher answer keys**, scoring schemes, questionnaires and assessment grids.
- Cross-disciplinary projects combining networks, Linux, virtualization, electronics and local AI.
- Materials for **work placements (PFMP)**, career guidance and further studies.

Current areas of work include developing resources for bridging classes and exploring a **BTS SIO programme** at the school.

#### 📝 Work-placement forms and web tools

Developing mobile-friendly tools for collecting and tracking information:
- Forms with checkboxes, photographs, signatures and PDF generation.
- Exploring hosting and distribution options.
- Existing repository: **[FormulairePFMP](https://github.com/regisazzoun/FormulairePFMP)**.

### 🔧 Technologies used or explored

**Networking and systems:** Cisco IOS · VLAN · SSH · Debian/Linux · Raspberry Pi · Windows Server · VMware ESXi · Nagios

**Development and automation:** Python · JavaScript / Node.js · Bash · PowerShell · SQLite · Docker · Git / GitHub · systemd

**Electronics and prototyping:** Arduino Mega · ESP32 · Servomotors · I²C · Fritzing · PCBs · 3D printing

**Local AI:** NVIDIA CUDA · GPUs/eGPUs · Ollama · Open WebUI · Language models · Codex

### 📚 My teaching approach

These projects are not just technology demonstrators: they are also learning opportunities. I aim to combine:
1. **Realistic practical situations**, using actual hardware and services.
2. **Level-appropriate progression**, from vocational high school to Passerelle BTS and BTS SIO SISR.
3. **Guided activities without immediately giving away all the answers**.
4. **Checkpoints and transparent assessment criteria**.
5. Documentation that others can reuse and improve.

### 🤝 Sharing and contributions

I plan to share procedures, scripts, teaching sequences and experimental findings progressively. Projects featured here may still be **under development**; their presence does not mean that every feature has been completed or validated.

Constructive discussion about reproducibility, educational resources and teaching applications is welcome.

---

*Profile and projects updated in October 2026.*
