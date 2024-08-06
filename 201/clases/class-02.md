# **Conceptos básicos de HTML, CSS y JS**

## Introducción a HTML

**1.¿Por qué es importante utilizar elementos semánticos en nuestro HTML?**

Le dan al texto estructura y significado, con eso los motores de búsqueda SEO y los lectores de pantalla puedan mostrarlo correctamente en tu página.

**2.¿Cuántos niveles de encabezado existen en HTML?**

Existen 6 niveles.

+ `<h1>`
+ `<h2>`
+ `<h3>`
+ `<h4>`
+ `<h5>`
+ `<h6>`

**3.¿Cuáles son algunos de los usos para los elementos `<sup>` y `<sub>`?**

+ **`<sup>`:** Super Indice y **`<sub>`:** Sub Indice, se pueden usar en formulas matemáticas, cuando queremos poner potencias en el navegador, en formulas químicas, etc.

**4.Al utilizar el elemento <abbr>, qué atributo se debe añadir para proporcionar una ampliación del término?**

Se debe añadir el atributo title.

## **Aprende CSS**

**1.¿De qué formas podemos añadir CSS a nuestro HTML?**

Existen 3 formas:

+ Hoja de estilo externo: vinculamos una hoja de estilo externa a nuestra página.
Ejemplo: `<link rel="stylesheet" href="styles.css" />`

+ Hoja de estilo interna: colocas tu CSS dentro de un elemento `<style>` de contenido dentro del elemento `<head>`del HTML.

+ Estilos en línea: son declaraciones CSS que afectan a un solo elemento, contenido dentro de un atributo de style. 
Ejemplo: `<h1 style="color: Pink ;background-color: White ;border: 1px solid black;">`
          ¡Bienvenidos a Pink Aura!
          `</h1>`
  
**2.¿Por qué deberíamos evitar utilizar estilos inline?**

Por que cuando tengas que actualizar algo, añadir un nuevo color o darle otra forma, tienes que hacerlo en todo el documento, en cada linea que utilizaste estilos inline,también mezcla tu información, lo que dificulta la lectura y la comprension del codigo. 

**3.Revisa el código a continuación y responde a las siguientes preguntas:**

**1.¿Qué representa el selector?**

Representa la aplicación de estilos a nuestro documento HTML. 

**2.¿Qué componentes son declaraciones CSS?**

El selector, las propiedades y los valores.

**3.¿Qué componentes se consideran propiedades?**

h2 {
     color: black;
     padding: 5px;
   }

# **Aprende JS**

**1.¿Qué tipo de dato es una secuencia de texto entre comillas simples?**

Tipo de dato String

**2.Enumera 4 tipos de operadores en JavaScript.**

* suma/concatena

* Operador de asignación

* Identidad/igualdad

* Negación, distinto (no igual)

**3.Describe un problema práctico que puedes resolver con una función.**

 La función alert(): hace aparecer una ventana emergente dentro de la ventana del navegador, pero necesitas asignarle una cadena como argumento para decirle qué mensaje se debe escribir en la ventana emergente.

# **Tomando decisiones en tu código — condicionales.**

**1.Si una declaración if comprueba un __ y si resulta ___, entonces el código se ejecutará.**

+ Condición  
+ Verdadera

**2.¿Cuál es el uso del else if?**

Se usa para agregar y detallar una nueva condición, si la primera condicion retorne falso, else if agrega la nueva condición.

**3.Enumera 3 tipos de operadores de comparación.**

+ Igual ( == )
+ No es igual ( != )
+ Mayor que(>)

**4.¿Cuál es la diferencia entre los operadores lógicos && y `||`?**

+ &&: permite encadenar dos o más expresiones, si todas son verdaderas retornará verdadero.

+ `||`: permite encadenar dos o más expresiones, basta que una sea verdadera para que retorne verdadero.