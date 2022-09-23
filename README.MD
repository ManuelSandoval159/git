# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline 1
-----------

Underline 2
==========


# formatos de enfasis
- formato *italica primer forma.*
- formato _italica segunda forma._
- formato **bold o strong.** primer forma
- formato __bold o strong.__ segunda forma
- formato ~~tachado~~ , normal.

# Listas

1. Esto es un item de lista ordenada.  
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links

- <a href="http://google.com">Link Html</a>
- [link en Markdown](http://www.google.com) 
- [link al index](index.html) 

# Imagenes
![Logo github](https://th.bing.com/th/id/R.79309b751fc01736ea1cc3d786b25651?rik=rurHNX620eLm%2fA&pid=ImgRaw&r=0)

# Code Snippets
- Codigo en JSON
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

- Codigo en JavaScript
```Javascript
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
| Manuel | Sandoval | 45454     |
| x | x | x |


# Citas
Cita: 
> cita

cita 2:
>cita 2

# lineas divisoras

texto dividido por guiones

----
texto dividido por asteriscos

***

texto dividido por guiones bajos

_____