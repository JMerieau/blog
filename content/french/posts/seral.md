+++
title = "Projet Seral"
description = ""
type = ["posts","post"]
tags = [
    "homelab",
    "souverain",
    "securite",
]
date = "2023-04-12"
categories = [
    "adminsys",
]
series = ["Seral"]
[ author ]
  name = "Julien Mérieau"
+++

Dans la mythologies romaines, les lares sont des dieux domestiques qui protègent le foyer et la famille. Le nom de ce projet 'Seral' en est un anagramme !

Ce projet a été imaginé dans le but d'avoir un appartement connecté pour faciliter ma vie, allumer les lumières, avoir des routines pour le coucher ou lever de soleil, gérer mon électroménager voire ma consommation d'électricité.

### Contexte
Le problème de notre époque de 'digitalisation' 🙃 est la surconnexion de nos équipements à internet. Cela nous expose à plusieurs problèmes:
- En cas de perte d'internet, on perd le contrôle de nos équipements
- Une tierce-partie peut contrôler nos équipements
- Des données personnelles peuvent être exfiltrées par certains équipements (caméras, microphones, GPS, environnement WiFi/Bluetooth, mot de passe WiFi, LIDAR sur des robots aspirateurs...)
- Les équipements pourraient être utilisés pour effectuer des attaques (DDoS notamment)
- Le vendeur de l'équipement peut le mettre à jour Over The Air (OTA) et ajouter du code malveillant (probable en cas de compromission ou de guerre avec des pays comme la Chine ou les US)
- Les équipements peuvent être des points d'entrée sur le réseau ou pivots pour compromettre des équipements plus sensibles (routeur, ordinateur...), beaucoup d'attaques sont possibles sur le réseau

Tout est une question de confiance, malheureusement, il n'est pas rare de voir passer des fuites de données personnelles suite à des compromissions ou des scandales au sujet de la collecte de données.

Personnellement, je n'ai aucune confiance envers les entreprises qui vendent des équipements connectés non opensource. D'où l'existence de ce projet.

### Principes
- **Vie privée** - Aucune donnée personnelle ne devrait être partagée à des tiers.
- **Sécurité** -  Les équipements connectés doivent être isolés.
- **Facilité** - Aucune maintenance ne devrait être requise et les équipements doivent être facilement utilisables.

### Parties
- Réseau: Mise en place d'un firewall et d'équipement pour remplacer le routeur 🖊️
- WiFi: Déploiement de plusieurs WiFi pour isoler les équipements à risque 🖊️
- Accès à distance: Déploiement d'un VPN pour accéder au réseau à distance 🖊️
- Serveur: Mise en place d'un serveur Proxmox pour gérer la domotique et avoir son homelab 🖊️
- Surveillance: Surveiller certaines parties du réseau à risque ⌛
- Robot aspirateur: Réappropriation d'un robot aspirateur propriétaire ⌛
- Caméra: Réappropriation d'une caméra de surveillance propriétaire ⌛
- Assistant: Déploiement d'un assistant vocal ⌛