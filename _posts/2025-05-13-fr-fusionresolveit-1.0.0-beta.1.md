---
layout: post
title: FusionResolveIT 1.0.0-beta.1
categories: news
lang: fr
---

Je suis très heureux de vous annoncer la sortie de la première version BETA de FusionResolveIT 1.0.0.

**ATTENTION, cette version n'est pas à utiliser en production.**

Cette version *BETA* sert à tester différentes parties afin d'avoir les premiers retours sur des problèmes de design ou sur des fonctionnalités.

Les informations et procédure d'installation / migration sont consultables [sur le site de documentation](https://documentation.fusionresolveit.org/administrators/).

Pour tout problème, je vous invite à créer une issue [sur github](https://github.com/fusionresolveit/Issues/issues).
Si vous avez une remarque, essayez de proposer une solution dans la mesure du possible.


Voici la liste des choses à tester :

* le design général de l'application (disposition, couleurs...)
* la partie SSO, testée avec Keycloak mais pas essayée avec les autres (par exemple Azure...)
* les tickets (création, vie du ticket, clôture)
* les bookmarks du menu
* la disposition du menu, est-ce que la répartition semble fluide pour naviguer ?
* les articles de base de connaissance (Knowledge base articles) + visualisation sur la page d'accueil
* l'inventaire FusionInventory, avec cette [documentation](https://documentation.fusionresolveit.org/End-user%20guide/fusioninventory/). Focus uniquement sur : 
   * le système d'exploitation
   * le CPU
   * la mémoire
   * les logiciels
* la migration depuis UNIQUEMENT GSIT ou GLPI 9.5.x (pas les versions 9.4 et précédentes, ni les versions 10.x)
* les entités et profiles

Pour télécharger, aller [dans la partie release de github](https://github.com/fusionresolveit/FusionResolveIT/releases/tag/1.0.0-beta.1).


Merci à tous pour l'aide précieuse que vous allez apporter en testant \o/
