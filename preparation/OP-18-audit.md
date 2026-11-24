# Audit OP-18 — 24 novembre 2026

## Résultat des données françaises et anglaises

Source utilisée par le site : dépôt Punk Records, fichiers de données produit :

- Anglais : `english/data/569118.json`
- Français : `french/data/622118.json`

Contrôles exécutés sur les deux fichiers :

| Contrôle | Anglais | Français |
|---|---:|---:|
| Entrées du produit | 159 | 159 |
| Identifiants uniques | 159 | 159 |
| Identifiants du type OP18-xxx | 152 | 152 |
| Cartes de base OP18-001 à OP18-119 | 119 | 119 |
| Numéros de base manquants | 0 | 0 |
| Identifiants dupliqués | 0 | 0 |
| Entrées sans champ image | 0 | 0 |

Les 7 entrées supplémentaires utilisent les numéros d'origine de cartes réimprimées/spéciales : deux variantes OP17-119 et les cartes OP13-012, OP13-113, OP17-040, ST24-004 et ST34-004. Elles font partie du produit OP-18 sans avoir un nouveau numéro OP18.

Le fichier produit contient 159 entrées au total, ce qui correspond au décompte de 119 cartes de base et 40 variantes/spéciales indiqué dans les listes de référence consultées le 24 novembre 2026.

## Limite importante sur les images

Le contrôle confirme que chaque entrée contient un champ URL d'image. Il ne prouve pas que les 159 fichiers image répondent tous encore en HTTP ni qu'ils s'affichent sur chaque appareil. Ce test visuel/réseau reste à faire sur le site.

## Japonais

Le site charge le japonais depuis les quatre fichiers JSONL de Koala Kollect. Vérification de l'historique GitHub le 24 novembre 2026 :\n\n| Fichier source japonais | Dernier commit visible |\n|---|---|\n| `data/card_observations/jp.jsonl` | 22 octobre 2026 |\n| `data/printings/jp.jsonl` | 8 octobre 2026 |\n| `data/products/jp.jsonl` | 15 octobre 2026 |\n| `data/printing_products/jp.jsonl` | 15 octobre 2026 |\n\nLe dépôt a bien reçu un commit de maintien le 21 novembre, mais les quatre fichiers utilisés par le site n'ont pas été actualisés après la sortie japonaise d'OP-18 (21 novembre). Le catalogue OP-18 japonais reste donc non confirmé et ne peut pas être considéré comme complet. Il faudra attendre une source japonaise à jour, puis comparer les 119 cartes de base et les variantes avant intégration. Aucune donnée japonaise n'a été ajoutée dans cet audit.

## Conclusion

- Français : les 119 cartes de base et les entrées variantes/spéciales disponibles dans le fichier produit sont présentes.
- Anglais : même résultat.
- Japonais : non confirmé ; source actuelle trop ancienne pour garantir OP-18.
- Aucune carte, image ou fiche OP-18 du site n'a été modifiée pendant cet audit.
