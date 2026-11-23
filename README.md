# One Piece Card Collection

Catalogue de fans non officiel pour rechercher des cartes One Piece Card Game et suivre sa collection.

## Fonctionnalités disponibles

- Interface en français, anglais et japonais.
- Catalogue avec recherche par nom ou numéro.
- Filtres par extension/deck, couleur, type, rareté, version et possession.
- Versions normales, parallèles et réimpressions lorsqu'elles existent dans les sources de données.
- Catalogue DON!! séparé, avec ses variantes disponibles.
- Cases de possession individuelles et statistiques par langue.
- Comptes par lien e-mail sécurisé via Supabase.
- Synchronisation Cloud des collections des comptes connectés.
- Import et export JSON pour sauvegarder ou transférer une collection.
- Application web progressive (PWA) installable sur les appareils compatibles.

## Synchronisation et sauvegardes

Les collections Cloud sont associées au compte connecté. Sur un appareil qui contient déjà une collection locale, le site demande confirmation avant de l'importer ou de la remplacer par la collection Cloud. Si l'utilisateur refuse, la collection locale est conservée et la synchronisation est mise en pause pour cette session.

Il est recommandé d'exporter régulièrement une sauvegarde JSON depuis le menu Options. La PWA n'est pas une publication sur Google Play ou l'Apple App Store.

## Sources des données

- Français et anglais : [Punk Records](https://github.com/buhbbl/punk-records).
- Japonais et DON!! : [Koala Kollect](https://github.com/hotavocado/koala-kollect-data).
- Les sources sont communautaires. Une URL d'image présente dans une base ne garantit pas que l'image sera toujours accessible.

Les index français et anglais recensés dans le projet contiennent respectivement 3 144 et 5 118 versions. OP-18 compte 152 entrées dans chaque index. La source japonaise recensée contient 4 997 versions jusqu'à OP-17 ; OP-18 japonais n'y est pas présent. Ces nombres sont des instantanés de la base et peuvent évoluer. Ils ne constituent pas une garantie d'exhaustivité de toutes les cartes, variantes et promotions.

## Déploiement

Le dépôt publie le site avec GitHub Pages depuis la branche `main`.

Site : https://murbrique0-dot.github.io/one-piece-card-collection.ch/

## Limites et transparence

- Le bouton de paiement est désactivé : aucun paiement ni abonnement n'est actuellement activé.
- L'indication d'essai de 10 jours est informative ; elle ne bloque pas l'accès après expiration.
- Les comptes et collections privées sont gérés par Supabase avec des règles d'accès côté base de données. Le catalogue et les fichiers publics du site restent accessibles publiquement.
- Les liens Cardmarket ouvrent une recherche par numéro de carte ; il faut vérifier la langue et la version exacte sur Cardmarket.
- Les données et illustrations peuvent être soumises aux conditions de leurs fournisseurs et ayants droit.

## Droits

Projet de fans non officiel, sans affiliation avec Bandai. One Piece Card Game, ses noms, personnages et illustrations appartiennent à Bandai, Eiichiro Oda, Shueisha et aux autres ayants droit. Le projet ne doit pas laisser croire qu'il est officiel ou approuvé par Bandai. Toute commercialisation doit faire l'objet d'une vérification des droits et autorisations applicables.
