<!-- HEADINGS -->   

# Ejemplo1
## Ejemplo2
### Ejemplo 3
#### Ejemplo 4
##### Ejemplo 5
###### Ejemplo 6

<!-- Italic -->  
this is an *italic* text

<!-- Strong -->  
this is an **strong** text

<!-- strickethrough -->  
este es un ~~texto~~ tachado 

<!-- UL Lista desordenada-->  

* ls Lista los archivos y directorios dentro del directorio de trabajo
    * ls 2
* mkdirtouch Crea un nuevo directorio
* touch Crea un archivo vacio
* cd Cambia de directorio.
* pwd Muestra el directorio actual de trabajo
* cat Muestra el contenido del archivo en pantalla en forma continua
* man Muestra el manual de un comando
  

<!-- OL Lista desordenada--> 

1. HTML
    1. HTML 5
2. CSS
3. JAVASCRIPT

[w3scool.com](https://www.w3schools.com/)

[w3scool.com](https://www.w3schools.com/ "Tutoriales Programación")

> this is a quote

---
___


`console.log("for i in {1..5}")`

```javascript
#!/bin/bash

for i in {1..5}
do
    #obtiene una cantidad aleatoria de número de lineas entre 1 y 20
    lineas=$(shuf -i 1-20 -n 1)
    #llama con curl a lipsum.com y le pasa como parámetro la cantidad de líneas
    lorem=$(curl -s https://www.lipsum.com/feed/xml\?amount\=$lineas | sed -n '/<lipsum>/,/<\/lipsum>/p' | sed -e 's/<lipsum>//g' -e 's/<\/lipsum>//g'
)   
    #crea un archivo con el contenido de la variable lorem
    echo "$lorem" >> loremipsum-$i.txt
donebash 

```
```python
print("Hello wordl")
```

```html
<h1>hello world<h1>
    <h1>Hola mundo<h1>
```




<!-- Ejemplo de Tabla -->   
| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Row 1    | Cell 2   | Cell 3   |
| Row 2    | Cell 5   | Cell 6   |
| Row 3    | Cell 8   | Cell 9   |


<!-- Cargar imagen con url -->   
![visual studio code logo](data:image/png;base64,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)



<!-- Cargar imagen localmente --> 
![visual studio code logo](XSantex.png "Xsantex")


<!-- Check de marcado --> 
* [x] marcado
* [] sin marcar
* [x] marcado
* [] task 2
  




