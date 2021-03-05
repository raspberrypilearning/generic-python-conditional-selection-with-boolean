- Una declaración estándar `if` en Python comprueba una sola condición. Por ejemplo:

```python
x = 5
if x > 0:
    print('x es mayor que cero')
```

- Pero a veces es posible que desees verificar más de una condición. En tales casos, puedes usar operadores lógicos en tu código.

- El operador `y` comprueba si se han cumplido dos condiciones. Por ejemplo:

```python
x = 5
if x > 0 and x < 10:
    print('x es un valor entre 0 y 10')
```

- Mientras `x` sea cualquier número dentro del grupo - `1,2,3,4,5,6,7,8,9`, la condición será verdadera.

- Puedes usar el operador `or` para comprobar si cualquiera de las condiciones es verdadera.

```python
x = 5
if x > 0 or x < 10:
    print('x existe')
```

- En este caso, la condición será verdadera siempre y cuando `x` sea mayor que `0`, o si es menor que `10`.
