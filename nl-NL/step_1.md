- Een standaard `if` instructie in Python controleert op een enkele voorwaarde. Bijvoorbeeld:

```python
x = 5
if x > 0:
    print('x is groter dan nul')
```

- Maar soms wil je misschien op meer dan één voorwaarde controleren. In dergelijke gevallen kun je logische operatoren in je code gebruiken.

- De operator `and` controleert of aan beide voorwaarden is voldaan. Bijvoorbeeld:

```python
x = 5
if x > 0 and x < 10:
    print('x is tussen 0 en 10')
```

- Zolang `x` een willekeurig getal binnen de groep is - `1,2,3,4,5,6,7,8,9`, blijft de voorwaarde waar.

- Je kunt de operator `or` gebruiken om te controleren of aan één van beide voorwaarden is voldaan.

```python
x = 5
if x > 0 or x < 10:
    print('x bestaat')
```

- In dit geval blijft de voorwaarde waar zolang `x` groter is dan `0`of kleiner is dan `10`.
