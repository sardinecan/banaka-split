# Banaka-split
Banaka-split contient un notebook Julia présentant deux méthodes pour scinder des images accessibles depuis [Nakala](https://nakala.fr/).
----------

## Prérequis
- Julia [https://julialang.org/](https://julialang.org/)
- un fichier `credentials.csv` comportant deux colonnes `user` et `apikey`. Exemple avec une clé publique fonctionnelle avec l'[API Test Nakala](https://apitest.nakala.fr/):
  
| user    | apikey |
| -------- | ------- |
| tnakala  | 01234567-89ab-cdef-0123-456789abcdef  |

## Méthodes

- `split()` scinde les images en deux.
- `spliiit()` à recours à la segmentation afin de recadrer les images par l'intermédiaire de l'API IIIF de Nakala.