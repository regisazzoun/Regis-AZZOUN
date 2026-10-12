# Bonjour, bienvenue sur mon GitHub 👋

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
