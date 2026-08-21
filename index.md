---
title: "StackLab — Politique de confidentialité"
---

[English version →](en.html)

# Politique de confidentialité — StackLab

**Dernière mise à jour : 21 août 2026**

StackLab est une application de suivi de collection de métaux précieux, développée par StackWar. Cette politique décrit ce que l'application fait de vos données — et surtout ce qu'elle n'en fait pas.

## L'essentiel en quatre phrases

- **Vos données restent sur votre téléphone.** StackLab n'a ni compte, ni serveur qui stocke votre collection, ni synchronisation cloud.
- **Nous ne collectons rien.** Aucune analyse d'usage, aucun traceur, aucune publicité, aucun identifiant.
- **Le seul appel réseau de l'application récupère les cours de l'or et de l'argent**, et ne transporte aucune information sur vous ni sur votre collection.
- **Vos sauvegardes sont chiffrées**, et ne quittent votre appareil que si vous les partagez vous-même.

## Ce que l'application stocke, sur votre appareil uniquement

- **Votre collection** : objets, prix d'achat, quantités, dates, notes, organisation en collections. Stockée dans une base de données locale, dans l'espace privé de l'application.
- **Vos photos d'objets** : enregistrées dans le stockage privé de l'application. Elles ne sont jamais envoyées nulle part et ne font l'objet d'aucune analyse ou reconnaissance d'image. Le cadrage d'une photo est réalisé entièrement sur l'appareil.
- **Votre code PIN** (si vous activez le verrouillage) : conservé dans le stockage sécurisé du système (Android Keystore). Il ne quitte jamais l'appareil.
- **Vos réglages** : devise, unité de poids, langue, préférences de sauvegarde.
- **L'historique public des cours** : les cours quotidiens de l'or et de l'argent, identiques pour tout le monde. Ce n'est pas une donnée personnelle — elle ne dit rien de ce que vous possédez.

## Ce qui transite par le réseau

**Une seule chose : les demandes de cours.** L'application interroge notre service de prix pour obtenir les cours actuels et historiques de l'or et de l'argent. Ces requêtes :

- ne contiennent **aucun identifiant** — ni de vous, ni de votre appareil, ni de votre collection ;
- comme toute connexion internet, transmettent votre **adresse IP** au serveur ; nous ne la relions à rien et notre service ne journalise pas le contenu des demandes d'historique ;
- transitent en HTTPS.

Si vous refusez toute connexion, l'application reste utilisable : seuls les cours en direct sont indisponibles.

## Vos sauvegardes

- Les sauvegardes automatiques restent **dans l'espace privé de l'application**, sur votre appareil.
- Les copies que vous exportez sont **chiffrées (AES-256-GCM)** avec des clés générées aléatoirement sur votre appareil. Vous seul détenez le kit de récupération qui permet de les ouvrir ailleurs.
- Une copie ne quitte l'appareil que **par votre geste explicite** de partage, vers la destination que vous choisissez. Ce que devient cette copie chez ce destinataire (par exemple votre espace cloud personnel) relève de la politique de ce service, pas de la nôtre.
- StackLab est **exclu de la sauvegarde cloud Android et du transfert automatique entre appareils** : rien ne part vers Google Drive à votre insu.
- Limite à connaître : **les photos ne sont pas incluses dans les copies de sauvegarde** dans la version actuelle.

## Ce que nous ne faisons pas

- Pas de compte utilisateur, pas d'inscription.
- Pas de collecte de données d'usage, pas d'outil d'analyse, pas de traceur publicitaire.
- Pas de vente, de partage ou de transmission de données à des tiers — nous n'avons rien à vendre : nous ne détenons rien.
- Pas de rapport de plantage automatique dans la version actuelle. Si cela change un jour, ce sera indiqué ici **avant** l'activation, et sans jamais inclure de données de collection.

Note : comme pour toute application distribuée par Google Play, Google peut nous transmettre des **statistiques agrégées et anonymes** (installations, plantages) issues des appareils dont les utilisateurs ont accepté ce partage avec Google. Nous n'y avons aucun accès individuel.

## Permissions

- **Appareil photo / photos** : demandée uniquement au moment où vous ajoutez une photo, jamais avant. Un refus affiche un message clair et n'empêche rien d'autre.

## Suppression de vos données

Vos données vous appartiennent et leur suppression aussi :

- l'application propose une suppression complète depuis les réglages ;
- désinstaller l'application efface l'ensemble de ses données locales ;
- il n'existe **aucune copie côté serveur** à supprimer — nous ne pouvons pas voir vos données, donc nous ne pouvons pas les conserver.

## Public concerné

StackLab est une application de gestion de patrimoine destinée aux adultes. Elle ne s'adresse pas aux enfants.

## Modifications de cette politique

Toute évolution de l'application qui changerait ce qui précède sera reflétée ici avant sa mise en service. La date de dernière mise à jour figure en tête de ce document.

## Contact

Pour toute question sur cette politique ou sur vos données : **stacklabs.app@gmail.com**
