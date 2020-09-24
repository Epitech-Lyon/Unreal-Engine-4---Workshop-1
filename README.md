# Unreal Engine Workshop - Partie 1


## Introduction

Bonjour, et bienvenue à tous sur ce Post-Workshop. L'on m'a demandé de vous retranscrire ce Workshop pour pouvoir le reproduire de votre côté. Il évoluera certainement au fur et à mesure de vos retours si des choses sont à corriger par la suite. 

Ni une, ni deux, rentrons dans le vif du sujet !


## Prérequis

- Installer Unreal Engine 4.20 (ou une autre version ultérieure)
- Une souris, c'est plus simple pour naviguer en 3D, la manette fonctionne aussi
- Clavier en QWERTY (Juste passer la langue en ENG suffit pour travailler simplement, ou alors, amusez-vous à modifier les options de l’éditeur ou encore importez un preset Français)


## Résumé de l'Unreal Engine Workshop - Partie 1

En premier, nous allons découvrir l'**Epic Games Launcher**, le cœur d'**Unreal Engine**. Si vous avez l'habitude de l'utiliser pour Fortnite, tant mieux, mais peu de gens regarde la partie **Unreal Engine**. 
Nous allons donc y jeter un œil.

Ensuite, nous regarderons l'**Éditeur**, sa façon de fonctionner, ainsi que l'agencement de ses fonctionnalités.
Vous apprendrez à le modifier à votre convenance, l'utiliser, et à vous poser les bonnes questions.

Vous découvrirez aussi que l'**Unreal Engine** n'est pas seulement un moteur de jeu, mais bien une suite pouvant s'adapter à vos besoins : cinéma, architecture, robotique, intelligence artificielle, réalité augmentée et virtuelle…

Par la suite, nous passerons à notre premier projet en commençant par les bases de l'**Éditeur** en créant notre première maison. D'une pièce au départ, elle s'agrandira par la suite selon votre envie.
Pour cela, nous apprendrons à utiliser les **Materials**, simplement, en les appliquant sur des **Meshes**.
Nous apprendrons aussi à mettre de la lumière dans nos **Scenes** et nous créerons un **Landscape** pour y poser notre maison.

Après avoir pris en main l'**Éditeur**, nous allons débuter la programmation. Ici, pas de **C++** pour que le cours soit accessible à tous, mais de la programmation visuelle : des **Blueprints**.
Premièrement, nous réaliserons une porte automatique s'ouvrant en passant devant. Pour cela, nous apprendrons à importer les **Assets** fourni par Epic Games, ceux du **Launcher**, mais aussi les votre !

Nous parlerons aussi de **Git**, et de comment l'utiliser pour l'**Unreal Engine** !

Pour terminer, je vous laisserai découvrir les **Blueprints** plus en profondeur avec quelques pistes !

## Epic Games Launcher
### **Onglet Unreal Engine (Anciennement Communauté)**
Une fois téléchargé, et installé, vous devriez arriver sur une fenêtre similaire, si non, cliquez sur Unreal Engine dans le choix de la catégorie :
<div align="center">
<a id="EGL_1"><img src="ressources_readme/EGL_1.jpg" width="700" height="" /></a>
</div>
<br />
Pour le moment, rien de bien compliqué sur cette page ! Vous pouvez y retrouver les news importante en premier plan, les liens de news, channel YouTube d'Unreal, le StackOverflow d'Epic, le Forum et la Roadmap (pas la peine de développer une feature si une qui arrive vous convient ! :smirk:)
En dessous, vous pourrez retrouver les informations récentes, et sur la droite, les projets de la communauté ! D'où son ancien nom : Communauté.

### **Onglet Apprendre**
Le second onglet, l'onglet Apprendre, regroupe pas mal de choses !
<div align="center">
<a id="EGL_1"><img src="ressources_readme/EGL_2.jpg" width="700" height="" /></a>
</div>
<br/>
- <a href="https://docs.unrealengine.com/en-US/index.html">Documentation</a> : Comme son nom l'indique, vous trouverez toute la Documentation de l'Éditeur. Allant simplement de la création de votre premier projet, au scripting de l'éditeur, en passant par la création de test unitaire ou la modification du moteur ! Vous pourrez tout trouver ici.<br/>
- <a href="https://learn.unrealengine.com/home/dashboard">Unreal Online Learning</a> : Anciennement Unreal Academy, ce sont des MOOC. Des cours en ligne vidéo quoi, tout simplement. Très utile pour maîtriser certaines fonction de l'éditeur, ou juste pour apprendre. Pas mal de contenu spécialisé (Quixel, Procedural, Blueprints…)<br/>
- <a href="https://forums.unrealengine.com/unreal-engine/announcements-and-releases/1745504-a-new-community-hosted-unreal-engine-wiki">Community Wiki</a> : Devenu poussière, il est peut être en train de renaître de ses cendres grâce à quelques efforts de la communauté.<br/>
- Le reste sont des Quick Start Guide, ainsi que des projets template pour se familiariser avec des features ou notions.<br/>

### Onglet Marché
Le troisième onglet, sûrement celui qui fera couler le plus d'encre... Le Marché !
<div align="center">
<a id="EGL_1"><img src="ressources_readme/EGL_3.jpg" width="700" height="" /></a>
</div>
