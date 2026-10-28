VERSION 6 EXACTE LTR - REVISION 3.9

Correctif de duplication :
- la capture confirmait deux lignes violettes pour Allées Seydou Nourou Tall ;
- la première était la géométrie de secours affichée immédiatement ;
- la seconde était la géométrie exacte way/395950807 chargée en arrière-plan ;
- avant d'ajouter une géométrie exacte, la carte retire désormais toute géométrie existante portant le même identifiant logique ;
- une seule ligne violette reste affichée.

Le correctif protège également les autres axes contre les doublons. Toutes les optimisations de la R3.8 sont conservées.
