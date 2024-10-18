# Le problème du voyageur de commerce (Travelling Salesman Problem, TSP)
C'est un problème classique en optimisation combinatoire. Il consiste à trouver le plus court chemin qu'un voyageur peut emprunter pour visiter un ensemble de villes exactement une fois chacune, puis revenir à son point de départ. 
Ce problème est particulièrement difficile à résoudre car le nombre de solutions possibles croît de manière exponentielle avec le nombre de villes.
Le TSP a des applications pratiques dans des domaines tels que la logistique, la planification des itinéraires, et la gestion de la chaîne d'approvisionnement.

## Objectis du projet
Je me concentre sur la résolution du problème du voyageur de commerce, où chaque trajet entre les villes est associé à un coût spécifique. 
Mon objectif est d'optimiser ce problème en appliquant la métaheuristique de l'algorithme génétique pour trouver la solution la plus efficace.
![Uploading image.png…]()

## L'algorithme génétique
L'algorithme génétique est une méthode d'optimisation inspirée des principes de l'évolution naturelle, tels que la sélection, le croisement et la mutation. Il fonctionne en créant une population de solutions candidates (appelées "individus") à un problème donné. Ces individus évoluent au fil des générations pour améliorer leur qualité.

1. **Initialisation** : Une population initiale de solutions est générée de manière aléatoire.
2. **Évaluation** : Chaque individu est évalué selon une fonction de fitness qui mesure la qualité de la solution.
3. **Sélection** : Les meilleurs individus sont sélectionnés pour se reproduire.
4. **Croisement (Crossover)** : Les individus sélectionnés sont croisés pour échanger des segments de leurs solutions et produire une nouvelle génération.
5. **Mutation** : Certaines solutions subissent des modifications aléatoires pour maintenir la diversité génétique.
6. **Répétition** : Le processus est répété sur plusieurs générations jusqu'à ce qu'une solution optimale ou satisfaisante soit trouvée.

L'algorithme génétique est efficace pour les problèmes complexes, car il explore un grand espace de solutions et peut éviter les minima locaux.
