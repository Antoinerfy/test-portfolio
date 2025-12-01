## 🛡️ Projet – Haute disponibilité Web avec UCARP

Ce projet m’a permis de mettre en place une architecture de haute disponibilité basée sur UCARP afin d’assurer la continuité de service d’un serveur web.  
UCARP permet à deux serveurs configurés en actif/passif de partager une adresse IP virtuelle. Cette adresse “flottante” bascule automatiquement entre les serveurs en cas de panne, garantissant que le service web reste accessible à tout moment.  
J’ai ainsi étudié le fonctionnement d’un cluster CARP, la gestion de la priorité entre les nœuds, le mécanisme d’élection du maître et le principe de basculement (failover) observé en situation réelle.

### ✅ Objectifs atteints
- Comprendre et mettre en œuvre le fonctionnement d’une adresse IP virtuelle
- Déployer un cluster actif/passif assurant la haute disponibilité
- Observer et vérifier le basculement automatique entre maître et backup
- Assurer la continuité de service du site web sans interruption pour l’utilisateur

## 🏗️ Projet – Étude et mise en place d’un cluster Actif/Passif (HA)

Dans le cadre d’un appel d’offre simulé, j’ai étudié, conçu et maquetté une solution de haute disponibilité pour un service web.  
L’objectif était de garantir la continuité de service grâce à un cluster composé de deux serveurs configurés en mode actif/passif.  
J’ai installé un environnement GNU/Linux, sécurisé l’accès aux machines via SSH, puis mis en place un mécanisme d’adresse IP virtuelle permettant au service de rester accessible même en cas de panne du serveur principal.  
Ce projet m’a permis de comprendre la logique de fonctionnement d’un cluster, la gestion des rôles actif/passif, ainsi que les critères nécessaires à la recette de validation.

### ✅ Objectifs atteints
- Analyser un besoin de haute disponibilité et proposer une architecture adaptée  
- Installer et configurer deux serveurs destinés à fonctionner en cluster actif/passif  
- Mettre en place un accès sécurisé via SSH pour l’administration du cluster  
- Démontrer la continuité de service à l’aide d’une adresse IP virtuelle commune

## 🔐 Projet – Sauvegarde automatique sécurisée (SSH + Script + Cron)

Ce projet consistait à concevoir un système de sauvegarde automatisée vers un serveur distant en utilisant le protocole SSH.  
J’ai mis en place un serveur SSH sécurisé, configuré une authentification par clé, puis créé un script automatisant l’envoi d’archives de sauvegarde.  
La planification a été réalisée via Crontab afin d’exécuter la sauvegarde de manière régulière et sans intervention humaine.  
Le projet m’a permis de comprendre le fonctionnement de SSH, le principe d’authentification par clés, ainsi que la planification de tâches automatisées dans un environnement Linux.

### ✅ Objectifs atteints
- Mettre en place un serveur SSH sécurisé avec authentification par clé  
- Automatiser une sauvegarde vers un serveur distant à l’aide d’un script  
- Programmer l’exécution régulière de la sauvegarde via Crontab  
- Vérifier le bon déroulement des sauvegardes grâce aux logs système
