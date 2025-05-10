# Laboratoire de Détection d'Incidents de Sécurité avec Wazuh

Ce projet a pour but la mise en place d’un laboratoire personnel permettant de détecter des incidents de sécurité à l’aide de la plateforme Wazuh. Il a été conçu pour enrichir mon CV en démontrant mes compétences en cybersécurité, surveillance des systèmes et administration de machines virtuelles.

## Architecture du Laboratoire

Le laboratoire repose sur deux machines virtuelles :

- **Serveur Wazuh** : installé sur **Parrot OS**.
- **Machine attaquée (agent Wazuh)** : exécutée sous **NixOS**.

## Objectifs

- Déployer un serveur Wazuh fonctionnel pour la surveillance de systèmes.
- Configurer un agent Wazuh sur une machine cible.
- Simuler et détecter différents types d’incidents de sécurité.
- Collecter et analyser les alertes dans l’interface Kibana.

## Étapes de mise en place

1. **Installation de Ubuntu (VM1)** : 
   - Mise à jour du système.
   - Installation de Wazuh Manager et Elasticsearch.
   - Configuration de l’interface web (Kibana).

2. **Installation de NixOS (VM2)** :
   - Configuration réseau pour communication avec le serveur.
   - Installation de l’agent Wazuh.
   - Enregistrement auprès du serveur Wazuh.

3. **Tests et simulations d’incidents** :
   - Commandes suspectes.
   - Connexions SSH anormales.
   - Création de fichiers sensibles.
   - Attaques réseau simulées (scan, brute force…).
   - Règles personnalisées utiles 

## Outils utilisés

- **Wazuh** (manager, agent)
- **Elasticsearch**
- **Kibana**
- **VirtualBox** / **QEMU** (au choix pour les VMs)
- **Ubuntu** 
- **NixOS**

## Capture d’écran & démonstrations



## Auteur

Projet réalisé par *othmane * dans le cadre d’un apprentissage personnel en cybersécurité et surveillance système. 

