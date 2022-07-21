- pas de dépendance de fwk 
- dependence fwk de test
- un test fonctionnel pour commencer (oui dans le domaine)
	- il test toute une fonctionnlité mais uniquement dans le domaine


Interface => contrat, limite le couplage
 dans un package **api** qui permet de rentrer dans le domain
 dans un package **spi** qui permet d'appeller les couches techniques (sortie)

Type d'entrée et sortie du domaine sont toujours des objects du metier !

=> anti-corruption layer

 > Stub dans le code de prod ! **why ?**  
 >  ![[Screenshot 2022-09-15 at 15.03.35.png]]
 
 