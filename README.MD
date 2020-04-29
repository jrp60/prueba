# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabcera H4
##### Cabcera H5
###### Cabcera H6

# Underlines
Underline 1
------

Underline 2 
==========

# Formatos de enfasis 
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~

# Listas 
1. Esto es un item de lista ordenada 
2. Esto es un item de lista ordenada 
3. Esto es un item de lista ordenada 

- Esto es un item de lista desordenada 
- Esto es un item de lista desordenada 
- Esto es un item de lista desordenada 

# Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link Markdown](http://www.google.com) 
- [Esto es un link al index](index.html) 

# Imagenes 
![Logo Github](https://2.bp.blogspot.com/-9bw6QEeMEt8/U1QHyr2tNNI/AAAAAAAAB24/GcTaHej8130xuQoKHQPKYG35yBzOVV4pgCKgB/s1600/github_login_icon.png)

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
| Maxi | Burgos | 344462
| Tomas | Tompson | 344411

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior
> Esto es otra cita.

# Lineas divisorias
Esto es un texto que sera dividido 

---
Esto es otro texto dividido

***
Esto es otro texto dividido

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
