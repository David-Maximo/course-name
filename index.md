# Encabezados
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

## Insertar imagen
![Fotografía de la galaxia de Andrómeda](https://upload.wikimedia.org/wikipedia/commons/5/57/M31bobo.jpg)

## Código
```python
# Función de muestra
def Muestra(N, e, Z, p):
    """
    Devuelve el tamaño de la muestra de una población.
    >>> Población = 135 => Muestra = 100
    """
    n = (
        (Z**2 * N * p * (1 - p)) /
        (e**2 * (N - 1) + Z**2 * p * (1 - p))
    )
    return n

# Función de población
def Pobacion(n, e, Z, p):
    """
    Devuelve el tamaño de la población con base en el tamaño de la muestra.
    >>> Muestra = 100 => Población = 135
    """
    N = (
        (n * e**2 - Z**2 * n * p * (1 - p)) /
        (n * e**2 - Z**2 * p * (1 - p))
    )
    return N
```

## Lista de tareas
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world
