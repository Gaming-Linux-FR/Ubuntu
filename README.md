## Table des matières
---
0. [Choisir Ubuntu LTS ou latest](#LTS-ou-latest?)
1. [Création d'une clé usb bootable](#Création-du-support-usb)
2. [Démarrage sur la clé](#Démarrer-sur-la-clé-usb)
3. [Installation d'ubuntu]()
4. [Installation de steam]()
5. [Installation de Heroic]()
6. [Installation de Lutris]()
7. [Installation d'OBS]()
8. [Installation de KDEnlive]()
9. [Les snaps, bonnes pratiques]()
10. [Installation de Goverlay]()
   
# Installation Ubuntu de A à Z

### LTS-ou-latest? Telle est la question !

Choisir son ISO Ubuntu, est la première étape à réaliser en vue de son installation.

Or sans compter les spins, Ubuntu dispose de deux ISO différentes qui vous seront proposées. 

D'un côté vous aurez le choix de la version LTS qui dispose d'un support plus long sur 5 ans avec une mise à niveau possible tout les deux ans.
Et de l'autre, une latest qui dispose d'un support plus court de neuf mois seulement avec une mise à jour tout les six mois.

Ci-dessous quelques différences recensées : 

<p align="center">
  <img width="800" src="https://github.com/Gaming-Linux-FR/Ubuntu/assets/101025517/d2017f33-1012-4cb9-98a9-04f328b12124" alt="lts-or-latest">
</p>

A noter que d'après Ubuntu, 95% des users choisissent Ubuntu LTS, ce qui a pour effet, que LTS a globalement une meilleure compatibilité avec les applications tiers. 

Une fois, votre choix fait, pour télécharger Ubuntu, c'est à cette adresse : [Lien vers le téléchargement de Ubuntu](https://ubuntu.com/download/desktop)

### Création-du-support-usb

Pour créer une clé usb qui va accueillir Ubuntu, il vous faudra donc une clé usb ! de 8 Go ou + et télécharger l'outil [BalenaEtcher](https://etcher.balena.io/#download-etcher), disponible sur Windows, Mac & Linux. 
Cet outil va vous permettre en quelques clics de transformer votre clé usb de stockage en un support d'installation Ubuntu.

Une fois Balena Etcher lancé vous tomberez sur cette fenêtre.

![BalenaEtcher_1](https://github.com/DidicGLF/Ubuntu/assets/163353265/83b23cc2-55d2-4ea7-9b20-eb3b89960155)

Cliquez ensuite sur "Flash from file" et sélectionner l'image ISO que vous avez téléchargé un peu plus tôt.

Le logiciel vous demande ensuite de choisir sur quel support vous souhaitez copier cette image.

![BalenaEtcher_2](https://github.com/DidicGLF/Ubuntu/assets/163353265/08d9e033-ff13-47c7-b0c6-3c93a5c7cf5e)

Cliquez sur "Select target".

![BalenaEtcher_3](https://github.com/DidicGLF/Ubuntu/assets/163353265/54764bf0-4709-47ad-acc3-00d3d4b15b25)

Sur cette fenêtre, Balena Etcher vous invite à choisir le support, ici une clé de 16gb.
Une fois la case cochée appuyez sur "Select 1"

![BalenaEtcher_4](https://github.com/DidicGLF/Ubuntu/assets/163353265/e15fc296-c742-45b3-8643-e6d147da50d4)

Cliquez sur Flash pour lancer la procédure. La durée de l'opération dépendra de la vitesse de votre support USB

![BalenaEtcher_5](https://github.com/DidicGLF/Ubuntu/assets/163353265/053198ec-84ef-4216-8666-483eb48dde46)

Voilà le support USB est prêt nous pouvons passer à l'étape suivante.

### Démarrer-sur-la-clé-usb

