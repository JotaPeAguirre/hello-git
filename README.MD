# Version de curso
Versión actual: v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline 1
------------------

Underline 2
==================

# Formatos de Enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~. 
- Aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachado~~. 

# Listas
1. esto es un item
2. esto es un item
3. esto es un item
- Esto es item lista desordenada
- Esto es item lista desordenada
- Esto es item lista desordenada

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://google.com)
- [Esto es un link al Index](index.html)

# Imagenes
![Logo GitHub](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

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

Codigo en Javascript
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
| Nombre | Apellido | Documento|
|--------|----------|----------|
|Juan Pablo| Aguirre|12345|
|Jose Luis| Sierra|54321|

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se realaciona con la cita anterior:
> Esto es otra cita

# Lineas Divisoras
Esto es un texto dividido por guiones medios

---
Esto es un texto dividido por asteriscos

***

Esto es un texto dividido por guiones bajos

___

# Saltos de Línea
Esto es nuestro primer parrafo

Esto es nuestro segundo parrafo