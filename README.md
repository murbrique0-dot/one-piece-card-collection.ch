# One Piece Card Collection

Catalogue gratuit pour suivre sa collection One Piece Card Game.

## Fonctionnalités

- Langues : français, anglais, japonais, chinois (Hong Kong), chinois (Taïwan) et thaï.
- Recherche par nom, numéro, extension et rareté.
- Filtres par extension/deck, type, rareté et cartes possédées/manquantes.
- Versions normales, parallèles et réimpressions affichées séparément quand elles sont présentes dans la source.
- Une case « Je possède » par version ; les DON!! restent des cartes simples à cocher.
- Sauvegarde locale dans le navigateur, export JSON et import JSON.
- Collection séparée par langue pour éviter qu'une carte cochée en anglais soit automatiquement cochée en français.

## Sources et fraîcheur des données

Les données françaises, anglaises, chinoises (Hong Kong et Taïwan) et thaïlandaises utilisent [Punk Records](https://github.com/buhbbl/punk-records), un catalogue structuré généré à partir des listes officielles de One Piece Card Game. Les manifests de ces langues étaient générés le 20 novembre 2026 et leurs catalogues comprennent OP-18 et les decks jusqu'à ST-36.

La source japonaise utilisée actuellement est l'ancienne copie [Kuroro1990/OPTCG](https://github.com/Kuroro1990/OPTCG), car la branche japonaise de Punk Records est vide au moment de cette mise à jour. Cette copie japonaise s'arrête à OP-15 et ne comprend donc pas les sorties japonaises les plus récentes. Le choix japonais est conservé pour ne pas afficher un catalogue vide, mais il n'est pas à jour.

Les variantes sont séparées uniquement lorsqu'elles existent dans la base source (par exemple les identifiants suffixés `_p1`, `_p2` ou `_r1`). Cela ne garantit pas que chaque illustration promotionnelle, Manga, DON!! ou variante de chaque région soit déjà répertoriée. Les images sont chargées depuis les serveurs officiels ; certaines peuvent être indisponibles ou changer d'adresse.

## Sauvegarde

Les coches sont stockées localement dans le navigateur et l'appareil utilisés. Elles ne sont pas synchronisées automatiquement entre appareils. Utilise « Exporter ma collection » pour créer une sauvegarde JSON, puis « Importer une sauvegarde » pour la restaurer.

## Mise en ligne gratuite

Le dépôt contient un workflow GitHub Actions dans `.github/workflows/deploy.yml`. GitHub Pages publie automatiquement le site après chaque mise à jour sur la branche `main`.

Site : https://murbrique0-dot.github.io/one-piece-card-collection.ch/

## Droits et transparence

Projet de fans non officiel, sans vente de cartes ni affiliation avec Bandai. Les noms, textes et illustrations restent la propriété de leurs ayants droit. La structure de données Punk Records est publiée sous sa propre licence ; consulte son dépôt pour les conditions de réutilisation.
