Otra cosa que queremos hacer con las listas es saber en qué posición se encuentra un elemento. Para ello utilizamos la función `list.index` de la siguiente manera:

```python
ム list.index(["a", "la", "grande", "le", "puse", "cuca"], "grande")
2
ム dias_laborales = ["lunes", "martes", "miercoles", "jueves", "viernes"]
ムlist.index(dias_laborales, "lunes")
0
```

Como ves, lo curioso de esta función es que pareciera devolver siempre uno menos de lo esperado. Por ejemplo, la palabra `"grande"` aparece tercera, no segunda; y `"lunes"` es el primer día laboral, no el cero. ¿Quienes crearon Python se equivocaron? :confused:

¡No! :sweat_smile: Se trata de que en Python, al igual que en muchos lenguajes, las posiciones de las listas arrancan en 0: el primer elemento está en la posición 0, el segundo en la 1, el tercero en la 2, y así.

> ¿Y qué sucede si le pasás como argumento a `list.index` un elemento que no tiene? ¡Averigualo!
>
> Probá lo siguiente:
>
> ```python
> ムlist.index(dias_laborales, "osvaldo")
> ```
