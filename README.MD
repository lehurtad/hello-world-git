# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
-----------
-----------

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o stronge** de la primer forma.
- formato __bold o stronge__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar **formato italico**, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista Ordenanada. 
2. Esto es un item de lista Ordenanada.
3. Esto es un item de lista Ordenanada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="https://www.google.com/">Esto es un link HTML</a>
- [Esto es un link de Markdown](https://www.google.com/)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets
Codigo en JSON
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
Codigo en JavaScript
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
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Burgos   | 428345    |
| Tomas  | Hurtado  | 324567    | 

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.