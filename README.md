# PSFPN M1S2
Projet : Implantation de l’attaque générique contre le chiffrement double

Il s’agit de programmer, en C, l’algorithme de recherche de collision parallèle et de s’en servir pour réaliser l’attaque contre le chiffrement double. Plutôt que le DES, on utilisera par exemple le système de chiffrement par bloc RC5, qui permet de choisir la taille de la clef, et donc de faire tourner l’attaque « en pratique » avec de petites clefs. Une parallélisation sur plusieurs machines est attendue. L’implantation doit, dans la mesure du possible, être « haute-performance ».

Le résultat du projet, outre le code lui-même, consiste à faire apparaître tous les problèmes théoriques ou pratiques qui pourraient survenir (probabilité de succès, gestion du volume de données, communications, facteurs limitant les performances, etc.), et de parvenir à une estimation du temps de calcul nécessaire à la réalisation de l’attaque sur le double-DES.

L'algorithme implémenté est basé sur l’algorithme de recherche de collisions parallèle de van Oorschot et Wiener.

Référence. https://people.scs.carleton.ca/~paulv/papers/JoC97.pdf
