---
title: "StackLab — Politique de confidentialité"
---

[English version →](en.html)

# Politique de confidentialité — StackLab

**Dernière mise à jour : 1er novembre 2026**

StackLab est une application de suivi de collection de métaux précieux, développée par StackWar. Cette politique décrit ce que l'application fait de vos données — et surtout ce qu'elle n'en fait pas.

## L'essentiel en cinq phrases

- **Votre collection reste sur votre téléphone.** StackLab n'a ni compte, ni serveur qui stocke votre collection, ni synchronisation cloud.
- **Aucune analyse d'usage, aucun traceur, aucune publicité, aucune vente de données.**
- **L'application contacte deux services :** notre service de cours de l'or et de l'argent, qui ne reçoit rien de vous ; et RevenueCat, le prestataire qui valide les achats de la Boutique, qui reçoit un **identifiant technique anonyme** et vos **données d'achat** — jamais votre collection.
- **Le paiement est traité par Apple ou Google.** StackLab ne reçoit ni numéro de carte, ni coordonnées bancaires, ni votre nom.
- **Vos sauvegardes sont chiffrées**, et ne quittent votre appareil que si vous les partagez vous-même.

## Ce que l'application stocke, sur votre appareil uniquement

- **Votre collection** : objets, prix d'achat, quantités, dates, notes, organisation en labs et en coffres. Stockée dans une base de données locale, dans l'espace privé de l'application.
- **Vos photos d'objets** : enregistrées dans le stockage privé de l'application. Elles ne sont jamais envoyées nulle part et ne font l'objet d'aucune analyse ou reconnaissance d'image. Le cadrage d'une photo est réalisé entièrement sur l'appareil.
- **Votre code PIN** (si vous activez le verrouillage) et **les clés de vos sauvegardes** : conservés dans le stockage sécurisé du système — Android Keystore sur Android, trousseau sur iPhone. Ils y sont marqués « cet appareil uniquement » : ni synchronisés vers un cloud, ni inclus dans une sauvegarde. Ils ne quittent jamais l'appareil.
- **Vos réglages** : devise, unité de poids, langue, préférences de sauvegarde.
- **Vos droits d'accès** (Gratuit, Silver, Gold, Ambassador) : une copie locale de ce que vous possédez, pour que l'application fonctionne hors ligne. Elle n'entre dans aucune sauvegarde et ne voyage jamais dans un fichier.
- **L'historique public des cours** : les cours quotidiens de l'or et de l'argent, identiques pour tout le monde. Ce n'est pas une donnée personnelle — elle ne dit rien de ce que vous possédez.

## Ce qui transite par le réseau

### 1. Les cours des métaux

L'application interroge notre service de prix pour obtenir les cours actuels et historiques de l'or et de l'argent. Ces requêtes :

- ne contiennent **aucun identifiant** — ni de vous, ni de votre appareil, ni de votre collection ;
- comme toute connexion internet, rendent votre **adresse IP** techniquement visible du service. Il ne s'en sert que pour limiter le nombre de requêtes par appareil, en mémoire, et l'oublie après dix minutes d'inactivité ; il ne journalise ni votre adresse ni le contenu de vos demandes. Ce service est hébergé chez Render (États-Unis), qui peut tenir ses propres journaux de connexion, selon sa politique ;
- transitent en HTTPS.

Si vous refusez toute connexion, l'application reste utilisable : seuls les cours en direct sont indisponibles.

### 2. Les achats de la Boutique — RevenueCat

Depuis la version 1.0.0 (build 12), StackLab propose des achats intégrés (Silver, puis Gold). Pour valider ces achats et les retrouver après une réinstallation, l'application utilise **RevenueCat** (RevenueCat, Inc., États-Unis), un prestataire spécialisé qui agit pour notre compte, sur nos instructions.

**Ce que RevenueCat reçoit, dès le premier lancement de l'application :**

- un **identifiant technique anonyme**, généré par le logiciel de RevenueCat au premier lancement, propre à cette installation et sans lien avec votre nom, votre e-mail ou votre compte de magasin. Vous pouvez le lire et le copier dans la Boutique ;
- vos **données d'achat** : identifiants des produits achetés, reçu Apple ou jeton d'achat Google que RevenueCat vérifie auprès du magasin, prix et devise de la transaction, date, statut (actif, remboursé) ;
- des **informations techniques** : plateforme et version du système, version de l'application, langue et devise de l'appareil ;
- votre **adresse IP**, techniquement visible lors de chaque appel, comme pour toute connexion. Lorsque le pays de transaction n'est pas disponible, RevenueCat peut utiliser l'adresse IP pour estimer le pays et indique ne pas conserver cette adresse après cette détermination.

**Ce que RevenueCat ne reçoit jamais :** votre collection, vos objets, leurs quantités et prix d'achat, vos photos, vos labs et coffres, votre tableau de bord, vos sauvegardes, votre code PIN, votre nom, votre e-mail, votre numéro de téléphone, un identifiant publicitaire. Nous n'activons aucune option d'attribution, de marketing ou de collecte d'identifiants d'appareil.

**À quoi cela sert :** faire fonctionner la Boutique (prouver un achat, activer vos droits, les restaurer sur un nouvel appareil, retirer un droit remboursé) ; prévenir la fraude ; et nous donner des **statistiques de ventes agrégées** (nombre d'achats, revenus), sans profil individuel. Base légale : l'exécution du contrat d'achat et notre intérêt légitime à sécuriser les ventes.

**Où et combien de temps :** RevenueCat héberge ces données aux États-Unis, dans le cadre de son accord de traitement des données. Elles sont conservées tant que votre fiche anonyme existe chez RevenueCat ; vous pouvez en demander la suppression (voir plus bas).

**Codes et avantages :** un code promotionnel se rachète chez Apple ou Google, qui appliquent leurs propres conditions ; StackLab ne reçoit que le droit qui en résulte. Un avantage que nous accordons directement (par exemple pendant la bêta) est attaché à votre identifiant technique anonyme : le magasin ne le restaure pas, et une réinstallation le perd.

### 3. Apple et Google

Le paiement lui-même — carte, facturation, remboursement, reçu nominatif — est traité par l'App Store ou par Google Play, sous leurs propres politiques de confidentialité. **StackLab ne reçoit jamais vos coordonnées bancaires, ni votre nom, ni l'adresse e-mail de votre compte de magasin.** Un achat se retrouve avec « Restaurer mes achats » sur la même plateforme et le même compte de magasin ; un achat Apple ne vaut pas sur Android, et réciproquement.

### Ce qui ne transite pas

Aucun compte, aucune synchronisation, aucun outil d'analyse d'usage, aucun rapport de plantage automatique, aucune publicité. Si cela change un jour, ce sera indiqué ici **avant** l'activation, et sans jamais inclure de données de collection.

## Vos sauvegardes

- Les sauvegardes automatiques restent **dans l'espace privé de l'application**, sur votre appareil.
- Les copies que vous exportez sont **chiffrées** avec des clés générées aléatoirement sur votre appareil (ChaCha20-Poly1305 pour une copie complète, AES-256-GCM pour une copie de données seules). Vous seul détenez le kit de récupération qui permet de les ouvrir ailleurs.
- Une copie ne quitte l'appareil que **par votre geste explicite** de partage, vers la destination que vous choisissez. Ce que devient cette copie chez ce destinataire (par exemple votre espace cloud personnel) relève de la politique de ce service, pas de la nôtre.
- **Sur Android**, StackLab est **exclu de la sauvegarde cloud et du transfert automatique entre appareils** : rien ne part vers Google Drive à votre insu.
- **Sur iPhone**, cette exclusion n'existe pas : si vous avez activé la sauvegarde iCloud, elle emporte les données de l'application comme celles de vos autres applications, chiffrées par Apple. Votre code PIN et vos clés, eux, en sont exclus.
- **Vos photos peuvent partir avec votre sauvegarde.** Au moment de l'export, vous choisissez : une copie complète, vos photos comprises, ou une copie légère, données seules. Avant toute restauration, l'application vous dit ce que le fichier contient. Les photos voyagent chiffrées, dans le même fichier, et ne transitent par aucun serveur.
- **Vos droits d'accès ne sont pas dans la sauvegarde** : ils se retrouvent par « Restaurer mes achats », pas par un fichier.

## Ce que nous ne faisons pas

- Pas de compte utilisateur, pas d'inscription.
- Pas de collecte de données d'usage, pas d'outil d'analyse, pas de traceur publicitaire, pas de suivi entre applications.
- Pas de vente ni de partage de données à des fins commerciales. RevenueCat, Apple et Google ne reçoivent que ce qui est décrit ci-dessus, pour faire fonctionner les achats.
- Pas de rapport de plantage automatique dans la version actuelle.

Note : comme pour toute application distribuée par Google Play ou l'App Store, Google et Apple peuvent nous transmettre des **statistiques agrégées et anonymes** (installations, plantages) issues des appareils dont les utilisateurs ont accepté de partager ces données avec eux. Nous n'y avons aucun accès individuel.

## Permissions

- **Appareil photo / photos** : demandée uniquement au moment où vous ajoutez une photo, jamais avant. Un refus affiche un message clair et n'empêche rien d'autre.
- **Face ID / empreinte** : demandée uniquement si vous choisissez de déverrouiller l'application autrement que par le code. La vérification est faite par le système ; l'application n'en reçoit que le résultat.

## Si vous nous écrivez

Quand vous nous contactez (e-mail, Discord de la bêta), nous recevons ce que vous nous envoyez : votre adresse ou votre pseudonyme, votre message, et, si vous le joignez, votre identifiant technique anonyme et un code d'incident. Nous n'utilisons ces informations que pour traiter votre demande. L'application peut préparer un brouillon d'e-mail avec le code d'incident, l'identifiant et la version de l'application : **c'est vous qui le relisez et l'envoyez**, et il ne contient jamais de données de collection.

**Programme bêta.** Si vous nous envoyez votre identifiant technique anonyme pour recevoir un avantage, nous le notons dans un registre privé minimal (pseudonyme ou contact, plateforme, identifiant, date), tenu par l'éditeur seul, jamais publié ni transmis. Il est effacé au plus tard à la clôture du programme bêta. Partagez cet identifiant en message privé, jamais dans un salon public. Discord applique sa propre politique de confidentialité.

## Suppression de vos données et vos droits

Vos données vous appartiennent et leur suppression aussi :

- depuis les réglages, **« Tout supprimer »** efface votre collection : labs, coffres, objets, instantanés de valeur et photos. Vos clés de sauvegarde et votre kit de récupération sont **volontairement conservés**, pour que les copies déjà exportées restent ouvrables. Vos achats ne sont pas touchés : ils vous appartiennent ;
- **désactiver le verrouillage** supprime votre code PIN ;
- **l'effacement automatique**, si vous l'avez activé, va plus loin : après trop d'essais de code faux, il détruit aussi les clés de sauvegarde, le kit de récupération et les sauvegardes présentes sur l'appareil ;
- **désinstaller l'application** efface ses données locales, y compris la copie locale de vos droits et l'identifiant technique anonyme. Sur iPhone, le code PIN et les clés restent toutefois dans le trousseau du téléphone — c'est le comportement d'iOS pour toute application. Vos achats se retrouvent avec « Restaurer mes achats » ;
- **vos données d'achat chez RevenueCat** : écrivez-nous avec votre identifiant technique anonyme (visible dans la Boutique) et nous demandons leur suppression chez RevenueCat. Cette suppression efface la fiche anonyme et son historique chez RevenueCat ; elle n'annule aucun achat chez Apple ou Google, et un achat reste restaurable par votre compte de magasin. Pour un remboursement, adressez-vous à Apple ou à Google ;
- il n'existe **aucune copie de votre collection côté serveur** — nous ne pouvons pas la voir, donc nous ne pouvons pas la conserver.

Vous disposez d'un droit d'accès, de rectification, d'effacement et d'opposition sur les données qui vous concernent, dans les conditions du Règlement général sur la protection des données. Vous pouvez aussi saisir l'autorité de contrôle de votre pays (en France, la CNIL).

## Public concerné

StackLab est une application de gestion de patrimoine destinée aux adultes. Elle ne s'adresse pas aux enfants.

## Modifications de cette politique

Toute évolution de l'application qui changerait ce qui précède sera reflétée ici avant sa mise en service. La date de dernière mise à jour figure en tête de ce document.

## Contact

Pour toute question sur cette politique ou sur vos données : **stacklabs.app@gmail.com**

## Mentions légales

- **Éditeur et responsable du traitement** : Mounir Izem, entrepreneur individuel exerçant sous le nom commercial StackWar, France. StackLab est un produit édité par StackWar.
- **Adresse professionnelle** : 163 rue du Président François Mitterrand, Résidence Les Arcades, bâtiment A1, 91160 Longjumeau, France
- **Contact** : stacklabs.app@gmail.com
- **Hébergeur de cette page** : GitHub Pages — GitHub, Inc., San Francisco, États-Unis.
- **Hébergeur du service de cours des métaux** : Render (États-Unis).
- **Sous-traitant des achats** : RevenueCat, Inc. (États-Unis), agissant sur nos instructions.
