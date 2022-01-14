# Markdown
![logo-md]

---

# ¿Qué es Markdown?

**_Markdown_** es un **lenguaje de marcado ligero** creado en _2004_ con el que puedes agregar formato a documentos de texto plano. 📜

La clave del diseño de**_Markdown_** es la **facilidad de lectura**, que hace que el lenguaje sea fácilmente interpretado.

Cuando creas documentos **_Markdown_**, agregas el formato escribiendo los símbolos que conforman la sintaxis de **_Markdown_**, sin que exista una interfaz gráfica. Puedes agregar elementos en formato **_Markdown_** a cualquier archivo de texto plano mediante cualquier editor de texto. Aunque también puedes utilizar editores específicos para escribir y visualizar el resultado a la vez.

**_Markdown_** ha sido diseñado para que el texto también resulte legible sin ser renderizado.

Más adelante, cuando el documento se procese mediante una herramienta compatible, el texto junto con la sintaxis **_Markdown_** se exportará a otro tipo de archivo, que podrá ser de algún formato como por ejemplo **_HTML_** o **_PDF_**.

---
# Ejemplos de sintaxis

## Common MarkDown

### Saltos de línea

Los *saltos de línea* se generan cuando se encuentran **dos espacios** juntos:

```markdown
"Quien fue a Santiago,  
perdió su clase de redes"
```

### Citas
Para citar solo es necesario escribir una **cuña** `>` antes del texto:

> La vida es muy corta para aprender alemán.
>> -Tad Marburg

```markdown
> La vida es muy corta para aprender alemán.
>> -Tad Marburg
```

---

### Encabezados

Se generan cuando se encuentra **una almohadilla** antes del texto:

```markdown
# Encabezado nivel h1
## Encabezado nivel h2
### Encabezado nivel h3
#### Encabezado nivel h4
##### Encabezado nivel h5
###### Encabezado nivel h6
```

También los podemos crear añadiendo una línea de **=** para los de _nivel 1_ y **-** para los de _nivel 2_:

```markdown
Encabezado h1
===============
Encabezado h2
---------------
```
![h1h2]

---
### Código

Se utilizan **tres acentos graves** para identificar código, seguidos del leguaje de programación para identificar el marcado correcto del mismo:

````html
```html
<!DOCTYPE html>
<html>
<head>
  <title>Tutorial Markdown</title>
</head>
</html>
```
````
También podemos añadir código como `<html>` dentro de una línea utilizando un solo acento grave para marcarlo:
```
`<html>`
```

### Separadores
Para insertar una línea separadora podemos incluir `***` o `---` y obtendríamos:
***


---
### Formatos

Podemos incluir _cursivas_, **negritas**, ***ambas***, ~~texto tachado~~ e incluso ~~***todo junto***~~

```markdown
|                                Código Markdown                                |
| :---------------------------------------------------------------------------: |
|                                                                               |
|                                                                               |
|                                   _cursiva_                                   |
|                                                                               |
|                                  **negrita**                                  |
|                                                                               |
|                            **_cursiva y negrita_**                            |
|                                                                               |
|                                  ~~tachado~~                                  |
|                                                                               |
|                            ~~*cursiva y tachado*~~                            |
|                                                                               |
|                            ~~**negrita tachado**~~                            |
|                                                                               |
|                     ~~**_cursiva, negrita y tachado_**~~                      |
|                                                                               |
|                                                                               |
| _____________________________________________________________________________ |
```

---
Podemos utilzar `*` o `_` indistintamente siendo siempre dobles para **negrita** y
simples para *cursiva* por ejemplo:

**Esto es un texto en negrita** __y esto también lo es__  

*Esto es un texto en cursiva* _y esto también lo es_

>>MD Code:

```markdown
**Esto es un texto en negrita** __y esto también lo es__

*Esto es un texto en cursiva* _y esto también lo es_
```

*cursiva*  **negrita**  ***negrita y cursiva***  ~~tachado~~ 

```markdown
|                                Código Markdown                                |
| :---------------------------------------------------------------------------: |
|                                                                               |
|         *cursiva*  **negrita**  **_negrita y cursiva_**  ~~tachado~~          |
|                                                                               |
|         _cursiva_  __negrita__  __*negrita y cursiva*__  ~~tachado~~          |
|                                                                               |
| _____________________________________________________________________________ |
```

---

### Listas

#### Desordenadas

  + Puedes crear listas con los símbolos +, -, o *
  + Y también sublistas agregando 2 espacios:
    - Cada marcador creará un nuevo elemento:
      * No importa que marcador
      + utilices por que solo
      - tiene encuenta 
      - los subniveles
  + Es muy fácil

```markdown
<!-- Código Markdown -->
  + Puedes crear listas con los símbolos +, -, o *
  + Y también sublistas agregando 2 espacios:
    - Cada marcador creará un nuevo elemento:
      * No importa que marcador
      + utilices por que solo
      - tiene encuenta 
      - los subniveles
  + Es muy fácil
```
---

#### Ordenadas

1. Elemento 1
2. Elemento 2
3. Elemento 3
4. Elemento 4
   - Sub-elemento 4.1
   - Sub-elemento 4.2
      1. Sub-elemento 4.2.1
      2. Sub-elemento 4.2.2
5. Elemento 5

```markdown
<!-- Código Markdown -->
1. Elemento 1
2. Elemento 2
3. Elemento 3
4. Elemento 4
   - Sub-elemento 4.1
   - Sub-elemento 4.2
      1. Sub-elemento 4.2.1
      2. Sub-elemento 4.2.2
5. Elemento 5
```
---

### Tablas

Para agregar tablas Markdown debes definir las cabeceras de columna mediante al menos tres guiones `---` que se situarán por debajo del texto de la cabecera. Para separar las diferentes cabeceras tendrás que usar un símbolo de tubería `|`:

```markdown
| Cabecera 1 | Cabecera 2 |
| ---------- | ---------- |
| Elem 1, 1  | Elem 1, 2  |
| Elem 1, 2  | Elem 2, 2  |
```

Cuyo resultado obtendríamos

| Cabecera 1 | Cabecera 2 |
| ---------- | ---------- |
| Elem 1, 1  | Elem 1, 2  |
| Elem 1, 2  | Elem 2, 2  |

Para crear la estructura de la tabla podemos usar un generador como este:

[https://www.tablesgenerator.com/markdown_tables](https://www.tablesgenerator.com/markdown_tables)

---
### Enlaces
Muchos de los procesadores de **MD** convertirán _automáticamente_ el texto https://www.google.es en un hipervínculo para conseguir mostarlo como texto tenemos que indicarlo expresamente `https://www.google.es` con la siguiente notación

```markdown
`https://www.google.es`
```

Si por el contrario pretendemos enlazar una palabra o frase concreta cualquier otro sitio web debemos seguir la siguiente estructura


[https://www.wikipedia.com](https://www.wikipedia.com)  
[Wikipedia](https://www.wikipedia.com)

```markdown
[https://www.wikipedia.com](https://www.wikipedia.com)  
[Wikipedia](https://www.wikipedia.com)
```


---
### Imágenes
---
### Referencias
---

### Listas de tareas

También podemos crear una lista de tareas en la que nos permite marcar determinados elementos

- [x] Primera tarea
- [ ] Segunda tarea
- [ ] Tercera tarea

```markdown
- [x] Primera tarea
- [ ] Segunda tarea
- [ ] Tercera tarea
```
---

### Emojis
Existen dos formas de añadir emojis a nuestros documentos `.md`
1) Copiando y pegando el emoji
   - Si entramos en [emojipedia](https://emojipedia.org/) podemos copiar directamente el emoji que deseemos incluir en nuestro documento `.md`
     - 🎵🎷🎹🔥

2) `*`Usando los shortcodes
   - A cada emoji le corresponde un código para su rápida localización este código se llama shortcode y comienzan y terminan con **dos puntos** por ejemplo `:emoji:` 

        Me encanta tu sonrisa :smile:, pero eres más lento que una tortuga :turtle:. 

        ```markdown
        Me encanta tu sonrisa :smile:, pero eres más lento que una tortuga :turtle:.
        ```
    Podemos encontrar una lista completa con todos los shortcodes en [GitHub](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

3) `*`Usando solo texto `:)` y obtendremos :)

`*`Este método no funciona en todos los procesadores de **MD**

---

### Nota al pie




### Abreviaturas

La especificación HTML es mantenida por el W3C.

*[HTML]: Hyper Text Markup Language  
*[W3C]:  World Wide Web Consortium  


---

[logo-md]: https://upload.wikimedia.org/wikipedia/commons/4/48/Markdown-mark.svg "Markdown"
