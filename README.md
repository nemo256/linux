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

- **Open Source et Gratuit** : Linux est gratuit et modifiable, ce qui permet de l'adapter à ses besoins.
- **Stabilité et Fiabilité** : Linux est stable, mais certaines distributions comme Arch Linux peuvent être moins stables, contrairement à Debian qui est reconnu pour sa fiabilité.
- **Sécurité** : Linux offre une sécurité robuste, mais cela dépend aussi de l'utilisateur et de la gestion des permissions.
- **Communauté et Support** : La communauté Linux est active et propose des ressources utiles comme [Arch Wiki](https://wiki.archlinux.org) et [Debian Wiki](https://wiki.debian.org) pour l'aide et la documentation.
- **Meilleur choix pour les Développeurs** : Linux est très apprécié des développeurs grâce à ses outils et sa flexibilité.
- **Flexibilité** : Linux fonctionne sur une large gamme de matériel, des anciens ordinateurs aux serveurs modernes.
- **Opportunité d'Apprentissage** : Utiliser Linux permet de mieux comprendre le fonctionnement des systèmes d'exploitation.

# Introduction aux Fondamentaux de Linux 🛠️

## Installation de Linux

L'installation de Linux peut être simple et se faire en plusieurs étapes. Voici comment procéder :

1. **Choisissez une distribution Linux** : Nous vous recommandons [Ubuntu](https://ubuntu.com/download) pour les débutants. C’est une distribution populaire avec une grande communauté.
2. **Téléchargez l’image ISO** : Allez sur le site d'Ubuntu et téléchargez le fichier ISO pour commencer l'installation.
3. **Préparez votre matériel** : Vous pouvez installer Ubuntu directement sur votre ordinateur ou utiliser une machine virtuelle comme [VirtualBox](https://www.virtualbox.org/).
4. **Suivez les instructions d'installation** : Si vous choisissez Ubuntu, consultez le [guide officiel d'installation](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview) pour vous aider tout au long du processus.

Voici deux images utiles pour visualiser l'installation :

![Ubuntu](./images/ubuntu.png){: width="300" height="200"} + ![VirtualBox](./images/virtualbox.png){: width="300" height="200"}

## Découverte de l’Environnement

Une fois installé, vous découvrirez un environnement graphique ou un bureau, selon la distribution choisie. Vous pourrez explorer les applications disponibles et vous familiariser avec les paramètres de votre système.

## Introduction au Terminal

Le terminal est un outil puissant dans Linux, permettant d'exécuter des commandes pour interagir directement avec le système. Apprendre à utiliser le terminal est essentiel pour une gestion avancée et un contrôle complet de votre système Linux.

## License 📑

- Please read [linux/LICENSE](https://github.com/nemo256/linux/blob/master/LICENSE)
