[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/aRQGnba4)
# Expresiones Regulares (regex)

## Investiga: 

- qué son las expresiones regulares?
   Son patrones de búsqueda de texto utilizados para encontrar, coincidir o manipular cadenas de caracteres en funciones de procesamiento de texto. se definen mediante una sintaxis especializada 


- Qué problema resuelven? Por qué es importante conocerlas?
  Permiten buscar patrones específicos dentro de grandes cantidades de datos.
  Facilitan la filtración de información relevante, como direcciones de correo electrónico, números de teléfono, fechas, etc.
  Se utilizan para validar que la entrada del usuario cumple con un formato específico, como un número de teléfono o una dirección de correo electrónico válidos.
  Facilitan la manipulación de cadenas de texto al permitir la sustitución o modificación de fragmentos específicos de texto.
  Ayudan en la manipulación de datos en archivos de texto, como la extracción de información clave o la transformación de datos.Ayudan en la manipulación de datos en archivos de texto, como la extracción de información clave o la transformación de datos.
  Y ENTRE OTRAS MUCHAS MAS

## Ejercicio 1:

Escribe las expresiones regulares correctas para validar:

- un email 
^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$
- un número de teléfono (español)
^(\+34|0034|34)?[6-9]\d{8}$
- un DNI
^[0-9]{8}[TRWAGMYFPDXBNJZSQVHLCKE]$

## Ejercicio 2:

Crea un formulario de contacto y utiliza el atributo `pattern` de los elementos `input` para validar los campos usando expresiones regulares. El formulario debe incluir: nombre, apellidos, dni, número de teléfono, email, dni y dirección.

Nota: puedes hacerlo añadiendo un archivo `index.html` en este repositorio.


## Referencias

- [Expresiones Regulares en Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions)
- [Online Regex Editor](https://regex101.com/)