# 🔁 TD – Mise en place d’une redondance réseau avec UCARP sous Linux

---

## 🧠 Objectif pédagogique du Lab

Ce TP a pour but de mettre en œuvre une solution de **haute disponibilité réseau (HA)** en utilisant l’outil **UCARP** sous Linux.  
L’objectif est d’assurer la continuité de service d’une adresse IP virtuelle même en cas de panne d’un des serveurs.

---

## 🎯 Objectifs pédagogiques — BTS SIO

| Bloc | Compétence visée |
|------|------------------|
| **B2.1** | Déployer un service réseau avec mécanisme de tolérance aux pannes |
| **B3.2** | Configurer et administrer un environnement Linux |
| **B3.4** | Mettre en place une solution de redondance (failover) |
| **B4.1** | Diagnostiquer et tester la résilience d’un service réseau |

---

## 🖥️ Contexte technique

Trois machines Linux ont été utilisées :

- 🖥️ **PC1 (toi)** : rôle **MASTER UCARP**
- 🖥️ **PC2 & PC3 (collègues)** : rôle **SLAVE UCARP**

Chaque machine devait être configurée avec :

- La **même adresse IP virtuelle**
- Le **même masque de sous-réseau**
- La **même gateway**
- Le **même mot de passe UCARP**
- Le même **VHID (Virtual Host ID)**

Le fonctionnement repose sur un protocole permettant de transférer automatiquement l’IP virtuelle d’un serveur à un autre en cas de panne.

---

## 📚 Documentation utilisée

🔗 https://doc.ubuntu-fr.org/ucarp

---

## ⚙️ Installation & configuration

Chaque machine a reçu :

- L'installation d’UCARP :  
  ```bash
  sudo apt install ucarp
