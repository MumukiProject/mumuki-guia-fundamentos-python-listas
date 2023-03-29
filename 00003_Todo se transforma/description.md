Las listas son muy útiles para contener múltiples elementos. ¡Pero hay más! También podemos agregarle elementos en cualquier momento, utilizando el procedimiento `list.append`, que toma dos parámetros: la lista y el elemento. Por ejemplo:

```python
ム discos = ["Serú Girán", "Artaud", "Almendra", "Quebrado"]
ム len(discos)
4
ム list.append(discos, "Vida")
ム len(discos)
5
```

Como vemos, `list.append` agrega un elemento a la lista, lo cual hace que su tamaño aumente. ¿Pero en qué parte de la lista lo agrega? ¿Al principio? ¿Al final? ¿En el medio? :thinking:

> Averigualo vos: inspeccioná en la consola qué elementos contiene `libros`, agregale `"Fundación"` y volvé a inspeccionar `libros`.
>
> Además existe un procedimiento `list.remove`, que toma por parámetro una lista y un elemento de ella. Investigá en la consola qué hace. :eyes:
>
>Cuando termines, escribí `listo()`.