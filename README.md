# One Piece Card Collection

Catalogue de fans pour suivre sa collection One Piece Card Game.

## Fonctionnalités du site

- Langues disponibles dans l'interface : français, anglais et japonais uniquement.
- Recherche par nom, numéro, extension et rareté.
- Filtres par extension/deck, couleur, type, rareté et cartes possédées/manquantes.
- Compteurs de cartes possédées, total répertorié et pourcentage pour la langue sélectionnée.
- Versions normales, parallèles et réimpressions lorsqu'elles sont présentes dans la source de données.
- Catalogue DON!! ajouté séparément ; les noms DON!! restent en anglais.
- Une case « Je possède » par version.
- Sauvegarde locale dans le navigateur, export JSON et import JSON.
- Interface adaptée aux écrans mobiles et ajoutable à l'écran d'accueil (PWA).

## Limites actuelles à connaître

- Les coches sont enregistrées localement dans le navigateur et sur l'appareil utilisé. Elles ne se synchronisent pas encore automatiquement entre plusieurs téléphones.
- Le site ne possède pas encore de création de compte, d'essai de 10 jours, de paiement ou d'abonnement. Ces fonctions nécessitent un service backend et une intégration de paiement sécurisée ; elles ne sont pas activées par le simple affichage des tarifs.
- Le catalogue japonais provient actuellement d'une source communautaire plus ancienne et peut être moins à jour que les catalogues français et anglais.
- Les images sont chargées depuis des sources externes. Certaines illustrations peuvent manquer ou être temporairement indisponibles.
- La présence de toutes les cartes, variantes Manga, parallèles et promos doit encore être vérifiée extension par extension ; le site ne doit pas être présenté comme exhaustif tant que cet audit n'est pas terminé.

## Sources

- Données principales : [Punk Records](https://github.com/buhbbl/punk-records).
- DON!! : [Koala Kollect](https://github.com/hotavocado/koala-kollect-data).

## Application mobile

Le site est préparé comme une PWA installable sur les appareils compatibles. Cela ne constitue pas encore une publication sur Google Play ou l'Apple App Store. La prochaine étape applicative sera de l'emballer avec Capacitor, puis de mettre en place les comptes, la sauvegarde Cloud et les achats/abonnements via les systèmes de paiement adaptés aux stores.

## Mise en ligne

Le dépôt publie le site avec GitHub Pages sur la branche `main`.

Site : https://murbrique0-dot.github.io/one-piece-card-collection.ch/

## Droits et transparence

Projet de fans non officiel, sans affiliation avec Bandai. Les noms et illustrations restent la propriété de leurs ayants droit. Avant toute commercialisation, il faut vérifier les licences et autorisations applicables aux bases de données, images, marques et éléments de propriété intellectuelle. Le projet ne doit pas laisser croire qu'il est officiel ou approuvé par Bandai.

## Modèle commercial envisagé (pas encore actif)

Le modèle discuté pour une future application est : 10 jours d'essai après la première connexion au compte, puis 5 CHF pour le premier mois d'abonnement, puis 0,50 CHF par mois. Aucun paiement n'est actuellement collecté par ce site. La facturation, les comptes, la résiliation et la synchronisation doivent être développés et testés avant toute annonce commerciale.