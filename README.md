# 👋 Théo Arini — Étudiant DevOps

Étudiant et Tuteur à l'École 42 Lyon depuis novembre 2024, en fin de tronc commun (spécialisation DevOps). Quatre projets d'infrastructure menés de bout en bout, du conteneur au cluster Kubernetes. 

📍 Charbonnières-les-Bains (69) · 🎓 42 Lyon · 🔍 Recherche une alternance DevOps/SRE de 24 mois, disponible dès octobre

---

### 🏆 Progression du cursus

[![tarini's 42 stats](https://badge.mediaplus.ma/darkblue/tarini)](https://github.com/oakoudad/badge42)
- *Projet en cours :* **Inception-of-Things**

---

## 🧰 Stack technique

| Domaine | Outils |
|---|---|
| **Conteneurs & orchestration** | Docker, Docker Compose, Kubernetes (K3s, K3d), Ingress |
| **CI/CD & versioning** | Git, GitHub, Argo CD (GitOps) |
| **Observabilité** | Prometheus, Grafana, stack ELK (Elasticsearch, Logstash, Kibana) |
| **Systèmes & réseau** | Linux, Bash, Vagrant, NGINX (reverse proxy, TLS), Cloudflare Tunnel |
| **Langages** | C, Bash, Rust, Go (notions) |

---

## 🚀 Projets DevOps & infrastructure

### [Inception-of-Things](https://github.com/Stafpecc/Inception-of-things) — *en cours (depuis 08/2026)* · équipe de 3 (avec [sekak](https://github.com/sekak) et [Cipher](https://github.com/Ciph3r-master))
Mise en place d'un cluster Kubernetes de A à Z, en trois parties : déploiement de deux VM Vagrant avec IP statiques et SSH sans mot de passe, installation de K3s (controller/agent) ; configuration d'un Ingress pour router plusieurs applications selon le nom d'hôte ; automatisation du déploiement continu avec K3d et Argo CD depuis un dépôt GitHub.
`Vagrant` `K3s` `K3d` `Ingress` `Argo CD` `GitHub`

### [ft_transcendence](https://github.com/ft-transcendence-tkt-on-vera) — *04/2026 – 08/2026* · équipe de 5 (avec [Pandhacker](https://github.com/pandhacker), [Delmath](https://github.com/delmath), [Cipher](https://github.com/Ciph3r-master) et [Annibalbarca](https://github.com/AnnibalBarca))
Projet final du tronc commun : application web de jeu multijoueur en temps réel, réalisée en équipe. Partie DevOps prise en charge en intégralité : conteneurisation de l'ensemble des microservices, monitoring Prometheus/Grafana, centralisation des logs avec la stack ELK, exposition sécurisée via tunnel Cloudflare et reverse proxy NGINX (HTTPS géré nativement, sans ouverture de ports entrants).
`Docker Compose` `Prometheus` `Grafana` `ELK` `NGINX` `Cloudflare Tunnel`

### [Inception](https://github.com/Stafpecc/Inception) — *04/2026 – 05/2026* · solo
Infrastructure système conteneurisée avec Docker : conteneurs buildés à partir de Dockerfiles personnalisés (aucune image pré-construite), orchestrés avec Docker Compose. Stack NGINX (TLS), WordPress + PHP-FPM et MariaDB, chaque service isolé avec volumes persistants et réseau dédié. Bonus : site statique, Portainer, notifications Discord via webhook, cache Redis.
`Docker` `Docker Compose` `NGINX` `WordPress` `MariaDB` `Redis` `Portainer`

### [Minishell](https://github.com/Stafpecc/minishell) — *03/2025 – 07/2025* · équipe de 2 (avec [ft-ruban](https://github.com/ft-ruban))
Réimplémentation en binôme d'un shell Unix en C reproduisant les fonctionnalités essentielles de bash : parsing de la ligne de commande, pipes et redirections, builtins (`cd`, `echo`, `exit`, `export`...), gestion des signaux et des processus (fork, exec, wait).
`C` `Linux` `Git`

---

## 🎓 Engagements à 42 Lyon

- **Tuteur** *(depuis 11/2024)* -- accompagnement d'étudiants en peer-to-peer sur leurs projets et animation d'ateliers DevOps.
- **Responsable du club Warhammer** *(depuis 11/2024)* -- organisation d'événements et coordination des membres.

---

## 🌐 Langues

**Français** -- langue maternelle
**Anglais** -- documentation technique

---

## 📫 Me contacter

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stafpec/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Stafpecc)
