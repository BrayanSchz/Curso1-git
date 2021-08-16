# Version del curso
Versión actual v1.2.2

# Cabeceras

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines 

Underline 1
--------------

Underline 2
--------------
--------------

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~formato tachado~~, formato normal.
---------------
- Esto es un *formato italico*, esto es un **formato bold** y este es un ~~formato tachado~~.

# Listas
1. Esto es un item de listas ordenadas.
2. Esto es un item de listas ordenadas.
3. Esto es un item de listas ordenadas.
- Esto es un item de listas desordenadas.
- Esto es un item de listas desordenadas.
- Esto es un item de listas desordenadas.

# Links
- <a href="https://www.google.com/">Esto es un link HTML</a>
- [Esto es un link en MarkDown](https://www.google.com/)

# Imagenes
![logo Github](https://image.flaticon.com/icons/png/512/25/25231.png)

# Code Snippets
Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código JS
```JavaScript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido Paterno | Apellido Materno |
| ------ | ---------------- | ---------------- |
| Brayan Manuel | Sánchez | Rodríguez |
| Alfredo | Cruz | Rodríguez |

# Citas
Esto es un texto referente a una cita que se pondrá a continuación:
> Esto es una cita 

Esto es un texto fuera de la cita
> Esto es otra cita

# Líneas divisoras
Esto es un texto que será dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Este es otro texto dividido por guiones bajos.

___

# Saltos de línea entre parrafos
Esto es el primer parrafo.

Esto es el segundo parrafo.

Esto es el tercer parrafo.