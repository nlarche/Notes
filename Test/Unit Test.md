- Diminue les regressions pendant les refactos
- Diminue le tend de dev et augmente la productivity
- Ameliore l'archtecture et le design à travers la testablilité

> **le TU doivent être couplés au comportement plutôt qu'à la structure du code.**


#### Structural coupling
les tests visent l'implémentation
Une classe de test par classe de code de prod
On teste une classe en isolation
toutes ces dépendances sont mockées

+ il y a de code prod + il y a de code de tests => maintenance compliqué

Peut entrainer des faux positifs quand les dépencdances sont refactorées

#### Behavioral Coupling
Couplé au comportement du system
tests sont couplés au system API (facade) qui expose le comportement
Sans être couplé à toutes les classes internes

- Taille du code de test et du code de prod non corrélé. Taille des tests corrélé par la complcité comportementale





