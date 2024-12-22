<div align="center">

# `linux`

<h3>
    Linux est un système d'exploitation open-source. Ce dépôt propose une introduction à ses commandes, à son système de fichiers et aux tâches d'administration de base.
</h3>

<!-- Badges -->

![GitHub Repo stars](https://img.shields.io/github/stars/nemo256/linux?style=for-the-badge)
![Maintenance](https://shields.io/maintenance/yes/2024?style=for-the-badge)
![License](https://shields.io/github/license/nemo256/linux?style=for-the-badge)

<!-- Demo image -->

![Demo](demo.png)

</div>

<!-- TABLE OF CONTENTS -->

## Table des Matières

- [Présentation de Linux 🌐](#présentation-de-linux)

  - [Qu’est-ce que Linux ?](#quest-ce-que-linux)
  - [Pourquoi choisir Linux ?](#pourquoi-choisir-linux)

- [Introduction aux Fondamentaux de Linux 🛠️](#introduction-aux-fondamentaux-de-linux)

  - [Installation de Linux](#installation-de-linux)
  - [Découverte de l’Environnement](#découverte-de-lenvironnement)
  - [Introduction au Terminal](#introduction-au-terminal)

- [Commandes Essentielles sous Linux 📜](#commandes-essentielles-sous-linux)

  - [Navigation dans le Système de Fichiers](#navigation-dans-le-système-de-fichiers)
  - [Gestion des Fichiers et Répertoires](#gestion-des-fichiers-et-répertoires)
  - [Lecture et Modification des Fichiers](#lecture-et-modification-des-fichiers)

- [Architecture et Organisation du Système de Fichiers 📂](#architecture-et-organisation-du-système-de-fichiers)

  - [Hiérarchie des Répertoires](#hiérarchie-des-répertoires)
  - [Permissions et Propriétés des Fichiers](#permissions-et-propriétés-des-fichiers)

- [Gestion des Logiciels et des Paquets 📦](#gestion-des-logiciels-et-des-paquets)

  - [Installation et Suppression de Logiciels](#installation-et-suppression-de-logiciels)
  - [Mise à Jour et Maintenance du Système](#mise-à-jour-et-maintenance-du-système)

- [Administration des Utilisateurs et des Groupes 👤](#administration-des-utilisateurs-et-des-groupes)

  - [Création et Gestion des Comptes](#création-et-gestion-des-comptes)
  - [Gestion des Groupes et des Permissions](#gestion-des-groupes-et-des-permissions)

- [Concepts de Base en Réseaux 🌐](#concepts-de-base-en-réseaux)

  - [Configuration Réseau](#configuration-réseau)
  - [Commandes Réseaux Courantes](#commandes-réseaux-courantes)

- [Supervision et Analyse du Système 📊](#supervision-et-analyse-du-système)

  - [Gestion des Processus](#gestion-des-processus)
  - [Surveillance des Performances](#surveillance-des-performances)

- [Introduction au Scripting Shell 💻](#introduction-au-scripting-shell)

  - [Écriture de Scripts Simples](#écriture-de-scripts-simples)
  - [Utilisation des Variables et Boucles](#utilisation-des-variables-et-boucles)

- [Ateliers Pratiques et Applications Réelles 🛠️](#ateliers-pratiques-et-applications-réelles)
  - [Exercices Dirigés](#exercices-dirigés)
  - [Création d’un Projet Linux Personnel](#création-dun-projet-linux-personnel)

# Présentation de Linux 🌐

## Qu’est-ce que Linux ?

Linux est un système d'exploitation open-source créé par Linus Torvalds en 1991. Il est utilisé dans divers domaines, des serveurs aux appareils mobiles, grâce à sa stabilité, sa sécurité et sa flexibilité. Linux est distribué sous une licence libre, permettant à chacun de modifier et redistribuer son code.

## Pourquoi choisir Linux ?

- **Open Source et Gratuit** : Linux est gratuit à utiliser, à modifier et à distribuer, ce qui permet à chacun de l’adapter à ses besoins.
- **Stabilité et Fiabilité** : Linux est reconnu pour sa stabilité, ce qui en fait un choix idéal pour les serveurs et les systèmes nécessitant une disponibilité continue. Cependant, certaines distributions Linux, comme Arch Linux, peuvent ne pas être aussi stables, car elles privilégient les dernières mises à jour. En revanche, des distributions comme Debian sont largement reconnues pour leur stabilité et leur fiabilité, adaptées aux environnements critiques.
- **Sécurité** : Linux offre une sécurité robuste grâce à des permissions strictes, des mises à jour régulières et un contrôle d'accès finement configuré. Cependant, la sécurité peut aussi dépendre de l'utilisateur. Un mauvais usage des droits administratifs peut compromettre un système, même sous Linux.
- **Communauté et Support** : La communauté Linux est très active et vaste, offrant un support continu à travers des forums, des guides et des documentations. Comparée aux communautés d'autres systèmes d'exploitation comme Windows ou macOS, la communauté Linux se distingue par son approche collaborative, ouverte et orientée vers l'innovation. Les utilisateurs peuvent trouver de l'aide sur des ressources comme [Arch Wiki](https://wiki.archlinux.org) pour Arch Linux et [Debian Documentation](https://www.debian.org/doc) pour Debian.
- **Meilleur choix pour les Développeurs** : Pour les développeurs, Linux est souvent la meilleure option en raison de sa compatibilité avec une multitude d'outils de développement, de sa flexibilité et de son accès direct à des ressources système. Linux permet une personnalisation poussée et dispose d'un environnement puissant pour le développement de logiciels, de serveurs et d'applications web.
- **Flexibilité** : Il peut fonctionner sur une large gamme de matériel, des anciens ordinateurs aux serveurs modernes.
- **Opportunité d'Apprentissage** : Utiliser Linux permet d'approfondir sa compréhension des systèmes d'exploitation et de la gestion de système.

## License 📑

- Please read [linux/LICENSE](https://github.com/nemo256/linux/blob/master/LICENSE)
