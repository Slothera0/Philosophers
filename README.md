# Philosophers

Exercices d'introduction au threads en C de 42.
L'objectif est de permettre à différents threads de coexister ensemble sans communiquer alors qu'ils ont un nombre limité de ressources entre eux :
Chaque thread représente un philosophe assis autour d'une table ronde qui a 2 besoin, manger et dormir, le reste du temps il pense.
Pour manger un philosophe a besoin de tenir 2 fourchettes le problème étant le nombre limité de fourchettes, seulement une entre chaque philosophe.
Le projet consiste donc à permettre à chaqu'un des threads de se maintenir en vie en mangeant régulièrement sans pour autant monopoliser les fourchettes dont leurs voisins ont aussi besoin et ceux sans communiquer.
