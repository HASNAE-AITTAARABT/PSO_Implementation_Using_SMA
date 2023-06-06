#  Parallel and distributed implementation of PSO using SMA
L'algorithme PSO, ou Optimisation par Essaim de Particules, est une technique d'optimisation heuristique inspirée du comportement social des oiseaux en essaim.
 Voici comment il fonctionne étape par étape :
 
 
Initialisation : Un certain nombre de solutions possibles, appelées "particules", sont générées et placées aléatoirement dans l'espace des solutions. 
Chaque particule représente une solution potentielle au problème d'optimisation.


Évaluation : La "fitness" de chaque particule (c'est-à-dire sa qualité en tant que solution au problème) est évaluée à l'aide d'une fonction d'évaluation ou de coût.

Mise à jour des meilleures positions : Chaque particule conserve en mémoire la meilleure position qu'elle a atteinte jusqu'à présent (c'est-à-dire la position avec la meilleure fitness). 
C'est la "meilleure position personnelle" ou pBest. De plus, la meilleure position atteinte par l'ensemble de l'essaim est également enregistrée. C'est la "meilleure position globale" ou gBest.


Mouvement des particules : Chaque particule se déplace ensuite dans l'espace des solutions. La direction et la distance du mouvement de chaque particule dépendent de sa meilleure position personnelle (pBest) et de la meilleure position globale (gBest). 
Plus précisément, chaque particule tente de se rapprocher de ces deux positions. Cela est généralement accompli par une combinaison linéaire de la position actuelle de la particule,
de la différence entre sa pBest et sa position actuelle, et de la différence entre la gBest et sa position actuelle.


Répétition : Les étapes 2 à 4 sont répétées jusqu'à ce qu'une condition d'arrêt soit atteinte. Cette condition peut être un nombre maximal d'itérations, un temps de calcul maximal, ou une amélioration minimale de la fitness entre les itérations.


Ainsi, l'ensemble de l'essaim converge progressivement vers la meilleure solution trouvée, c'est-à-dire vers la position avec la meilleure fitness.
L'algorithme PSO est donc une méthode de recherche globale qui tente de trouver la solution optimale en explorant l'ensemble de l'espace des solutions.


![image](https://github.com/HASNAE-AITTAARABT/PSO_Implementation_Using_SMA/assets/100070887/59afba3b-ca45-4bbf-af8d-780d145e95b9)

