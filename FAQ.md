# FAQ

## Est-ce que c'est obligé que l'algorithme commence en haut à gauche ?

Oui

## Y-a-t'il une taille maximale pour la grille ?

Aucune limite figée n'est fixée. Il est néanmoins primordial que la solution proposée puisse résoudre des grilles de 15 de côté dans une limite de temps raisonnable.

## Y-a-t'il un nombre maximal de couleurs ?

Non plus. Il y a au maximum autant de couleurs que de cases dans la grille, auquel cas la solution est triviale.

## Comment est effectué le classement lors de la compétition

Les algorithmes concurrents s'affronteront 1 par 1 dans un arbre de tournoi. Chaque affrontement se fera sur plusieurs manches (dont le nombre sera déterminé par le nombre de participants).
Pour chaque affrontement, le vainqueur sera :
- l'algorithme ayant réussi à donner une solution pour le plus grand nombre de grille dans le temps imparti ;
- l'algorithme avec le nombre de coups au total le plus faible ;
- l'algorithme choisi par les animateurs pour une des raisons suivantes, non exhaustives : son élégance, son charisme, sa finesse...

## Specs de la machine (RAM/CPU)

Sans garantie, les algorithmes tourneront tous sur une machine sans GPU, avec un CPU de la sorte :

```
Architecture:            x86_64
  CPU op-mode(s):        32-bit, 64-bit
  Address sizes:         39 bits physical, 48 bits virtual
  Byte Order:            Little Endian
CPU(s):                  8
  On-line CPU(s) list:   0-7
Vendor ID:               GenuineIntel
  Model name:            11th Gen Intel(R) Core(TM) i7-1185G7 @ 3.00GHz
    CPU family:          6
    Model:               140
    Thread(s) per core:  2
    Core(s) per socket:  4
    Socket(s):           1
    Stepping:            1
    CPU(s) scaling MHz:  40%
    CPU max MHz:         4800.0000
    CPU min MHz:         400.0000
```

## Peut-on fournir la solution sous forme d'une image Docker

Absolument, tant que son utilisation est documentée, comme toute autre soumission.