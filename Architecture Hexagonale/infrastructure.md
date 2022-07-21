- controller, accès bdd
- dépend des Fwks


Trick Spring pour injecter le domain dans l'infra sans mettre d'annotation spring dans le domain
ici il utilise des anotations custom (package ddd) pour réfercener ces classes
![[Screenshot 2022-09-15 at 15.12.57.png]]

Ne pas exposer les objets du metier à l'exterieur -> il faut des Resources, pour ne pas avoir de couplage avec nos consomateurs