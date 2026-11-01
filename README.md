# zabbix-infrastructure-monitoring
Supervision d'une infrastructure Windows/Linux avec Zabbix 


## Présentation

Projet pratique réalisé dans le cadre de ma formation à SUPINFO (module Introduction aux systèmes et réseaux).

L'objectif était de déployer une solution de supervision Zabbix afin de surveiller un serveur Web IIS sous Windows Server 2025 et une machine cliente Debian 13.

## Environnement technique

- VMware Workstation

- Debian 13

- Windows Server 2025 et IIS

- Zabbix 7.4 et Zabbix Agent

- MariaDB, Nginx et PHP


## Réalisations

- Création et configuration de trois machines virtuelles sur un réseau NAT VMware.
- Configuration des adresses IP statiques et vérification de la connectivité.
- Installation et configuration du serveur Zabbix sur Debian.
- Déploiement des agents Zabbix sur Windows Server et Debian.
- Configuration des hôtes et des modèles de supervision Windows/Linux.
- Création de quatre triggers personnalisés pour surveiller le service IIS, la disponibilité ICMP, la charge CPU et l'espace disque.
- Réalisation de tests d'incident et de rétablissement pour le service IIS et la disponibilité ICMP.

## Résultats

Les tests ont confirmé que Zabbix détecte l'arrêt du service IIS et l'indisponibilité de la machine Debian, puis signale automatiquement le retour à un fonctionnement normal.

## Documentation

Le rapport PDF joint présente l'architecture, les principales étapes de configuration, des captures d'écran et les résultats des tests.
📄 [Consulter le rapport technique (PDF)](pSYNE_Zabbix_Vladyslav_Shpakov.pdf)
