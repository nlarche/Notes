# Complexité logicielle
-  Essentielle => logique metier
-  Obligatoire => technique dont on ne peut pas se passer
- Accidentelle => inutile et couteuse


## La complexité accidentelle 

Est celle que l'on voudrait éviter, réduire => c'est la dette technique

- Culte du cargo (faire pareil que google par ex)
- Model anémique 
- Manque de bonne pratique
- Erosion et vétusté logicielle
- over-enginerring
- couplage fort

le couplage amène la fragilité


## Equation du couplage

Complexité essentiel + Complexité obligatoire = (Complexité accidentelle) * (Complexité accidentelle)

>*Exemple de couplage => controle des droits utilisateurs dans les controllers alors que c'est du metier (annotation spring par ex)*




