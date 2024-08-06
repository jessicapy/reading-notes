#  Listas en HTML, Control de flujo en JS, y CSS: Box Model

### Listas Ordenadas y No ordenadas 

**1.¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?**

Cuando necesites agrupar elementos que no tienen un orden numérico y su orden en la lista no tiene sentido y se muestran con viñetas.

**2.¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?**

Para cambiar el estilo bullet se utiliza la propiedad de estilos de css list-style-type.

**3.¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?**

+ Lista ordenada: cuando tienes una lista de elementos que se deben colocar en un orden concreto.
  
Ejemplo: Pasos de una receta.

+ lista no ordenada: cuando quieres agrupar elementos relacionados sin ningún orden en concreto.

Ejemplo: Los alumnos del aula de 3B son : Ana, Juan, Luz, Pedro, etc.

**4.Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada.**

+ Usando el tipo de número romano

  `<ol type="i">`
  
  `<li>Introducción</li>`
  
  `<li>Lista de personal</li>`
  
  `<li>Conclusion</li>`
  
  `</ol>`
  
  Se mostraría de esta manera:
  
  <ol type="i">
  <li>Introducción </li>
  <li>Lista de personal</li>
  <li>Conclusion</li>
  </ol>

+ Usando el atributo de inicio

  `<p>`Lugares de finalización de las concursantes que no están en el círculo de ganadores:`</p>`

  `<ol start="4">`
  
  `<li>Santiago Perez</li>`
  
  `<li>Luana Martinez</li>`
  
  `<li>Alejandro Flores</li>`
  
  `</ol>`

  1. Santiago Perez
  2. Luana Martinez
  3. Alejandro Flores

### Aprende CSS

**1.Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?**

**Margin:** cambia la posición de un elemento en relación con el diseño de la página, espacio invisible que hay alrededor de la caja. Se puede controlar todos los márgenes de un elemento a la vez usando la propiedad margin según el lado que desee.

+ margin-top: establece el área del margen en la parte superior de un elemento.

+ margin-right: establece el margen derecho de un elemento.

+ margin-bottom: establece el espacio requerido en la parte inferior de un elemento.

+ margin-left: establece el área de margen en el lado izquierdo de un elemento.

**Padding:** se encuentra entre el borde y el área de contenido, no puede tomar valores negativos, por lo que el valor debe ser 0 o positivo. Se usa para mantener el contenido alejado del borde.

+ padding-top: establece el espacio de relleno requerido en la parte superior del elemento.

+ padding-right: establece el ancho del área de relleno a la derecha de un elemento.

+ padding-bottom: establece el espacio de relleno requerido en la parte inferior del elemento.

+ padding-left: establece el espacio de relleno requerido en la parte superior del elemento.

**2.Enumera y describe las cuatro partes de un box del elementos HTML según el box model.**

1. El contenido de la caja o Content box:
El área donde se muestra el contenido y se cambia de tamaño con width y height.

2. El relleno de la caja o Padding box:
Es el espacio en blanco alrededor del contenido; se puede cambiar de tamaño usando la propiedad padding y otras propiedades relacionadas.

3. El borde de la caja o Border box:
Envuelve el contenido y el de relleno, se puede cambiar su tamaño y estilo utilizando la propiedad border y otras propiedades relacionadas.

4. El margen de la caja o Margin box:
Es la capa más externa. Envuelve el contenido, el relleno y el borde como espacio en blanco entre la caja y otros elementos, se puede cambiar su tamaño usando la propiedad margin y otras propiedades relacionadas.

### Aprende JS

**1.¿Qué tipos de datos puedes almacenar en un Array?**

Se puede almacenar varios tipos de datos como: cadenas, números, objetos e incluso otras matrices. También se puede mezclar tipos de datos en una sola matriz.

**2.¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?**

`const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`

Sí, es un array válido por Javascript, para poder acceder a sus valores almacenados tenemos que escribir el nombre de nuestro array, y luego insertar entre corchetes la posición del elemento al que queremos acceder.

**3.Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.**

1. Asignación: x = y
Asigna el valor de Y a X.

2. Asignación de adición: 	x += y
Suma el valor de Y al valor de X; almacena el resultado en X.

3. Asignación de resta: x -= y
Resta el valor de Y del valor de X; almacena el resultado en X.

4. Asignación de multiplicación: x *= y
Multiplica el valor de X por el valor de Y; almacena el resultado en X.

5. Asignación de división: 	x /= y
Divide el valor de X por el valor Y; almacena el resultado en X.

**4.Lee el código a continuación, evalúa la última expresión y explica cuál sería el resultado y por qué.**

`let a = 10;`

`let b = 'dog';`

`let c = false;`

 // evalúa esto
 
`(a + c) + b;`

El resultado que mostraría sería 10dog.

Por qué  cuando son números, conecta el número + el string, false es un bool y pasaría a ser 0 por lo cuál muestra  ese resultado. 

**5.Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.**

Ejemplo:

Supongamos que estamos construyendo una aplicación de registro de usuarios. Queremos mostrar un mensaje personalizado según la edad del usuario:

`let edad = 18;`
`if (edad >= 18) {`
`   console.log("Eres mayor de edad");`
`} else {`
`    console.log("Eres menor de edad");`
`}`

En este caso, la expresión edad >= 18 evalúa si la variable edad es mayor o igual a 18. Si es verdadera, muestra “Eres mayor de edad”; de lo contrario, muestra “Eres menor de edad” en la consola. Así, las declaraciones condicionales nos ayudan a adaptar el comportamiento de nuestro programa según diferentes situaciones.