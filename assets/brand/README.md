# Marque Djelify : fichiers du logo

Logo **provisoire** de Djelify, édité par Lynoric SARL. C'est exactement le dessin affiché dans l'en-tête de ce site (`assets/favicon.svg`) ; rien n'a été redessiné. Le dépôt de la marque à l'OAPI et un logo définitif viendront plus tard : ces fichiers seront alors remplacés.

## Fichiers

| Fichier | Contenu | Usage |
| --- | --- | --- |
| `icon.svg` | Marque seule, fond blanc plein, 1024 × 1024 | Source vectorielle de l'icône |
| `icon-1024.png` | Marque seule, 1024 × 1024, fond blanc plein, sans transparence | Icône d'application (Meta, magasins) |
| `icon-512.png` | Idem, 512 × 512 | Icône moyenne |
| `icon-180.png` | Idem, 180 × 180 | Icône d'écran d'accueil (Apple) |
| `logo-horizontal.svg` / `.png` | Marque + mot « Djelify », fond transparent, 1200 px de large | Sur fond clair uni |
| `logo-horizontal-white.svg` / `.png` | Idem sur fond blanc plein | Partout où la transparence n'est pas acceptée |

Dans les icônes, la marque occupe 80 % du côté : il reste une marge de 10 % de chaque côté, pour qu'un recadrage en cercle ou en carré arrondi ne l'entame pas. Le mot est converti en tracés : aucun fichier n'a besoin de la police pour s'afficher.

## Couleurs (jetons du thème clair)

| Élément | Jeton | Valeur |
| --- | --- | --- |
| Carré arrondi | `indigo` | `#2E3A8C` |
| Point | `kola` | `#E3A21A` |
| Forme du « d » | `surface-raised` | `#FFFFFF` |
| Mot « Djelify » | `ink` | `#161A2E` |

Sur le site en thème sombre, les mêmes jetons changent de valeur (le carré devient `#9AA7FF`, par exemple). Hors du site, on utilise uniquement les fichiers ci-dessus.

## Construction

- Marque : carré de 32 unités, rayon des angles 9 ; point de rayon 4,5 centré en (21,5 ; 10,5) ; « d » fait de deux barres de 4 unités d'épaisseur aux bouts arrondis.
- Mot : Bricolage Grotesque, graisse 700, interlettrage −0,02 em, à une hauteur de 24 pour une marque de 28 ; espace de 8 entre la marque et le mot ; mot centré verticalement sur la marque.

## Zone de protection

Autour du logo horizontal, laissez vide au moins **le diamètre du point kola** (9/32 du côté de la marque) : aucun texte, bord ni image dans cet espace. Les fichiers `logo-horizontal*` incluent déjà cette marge ; les icônes incluent leur marge de 10 %.

Taille minimale : marque de 16 px de côté à l'écran, logo horizontal de 96 px de large.

## Interdits

- Ne pas déformer : toujours garder les proportions (pas d'étirement, pas d'écrasement).
- Ne pas changer les couleurs, ni ajouter d'ombre, de contour, de dégradé ou d'effet.
- Ne pas faire pivoter, ne pas recadrer la marque, ne pas réarranger la marque et le mot.
- Ne pas redessiner le mot dans une autre police ni le récrire à la main.
- Ne pas poser le logo transparent sur une photo ou un fond chargé : utiliser la version fond blanc.
