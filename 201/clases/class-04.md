# Enlaces en HTML, Funciones en JS, e Introducción al CSS: Layout.

### Crea Hipervínculos.

**1.Para crear un enlace básico, ¿en qué elemento colocamos el texto u otro contenido?**

En el elemento ancla <a>.

 `<a href="https://www.mozilla.org/es-ES/">la página de inicio de Mozilla</a>.`

**2.¿Qué información contiene el atributo href?**

Contiene la dirección web hacia dónde queremos que apunte el enlace.

**3.¿Cuáles son algunas de las formas en las que podemos asegurarnos de que los enlaces a nuestras páginas sean accesibles a todos los lectores?**

+ Redacción clara del enlace.

+ Utiliza enlaces relativos siempre que sea posible.

+ Indica claramente los recursos en HTML.

+ Utiliza el atributo downloadal enlazar una descarga.

## CSS Layout.

### CSS: Layout: Normal Flow CSS: Layout: Positioning.

**1.¿A qué se refiere con “normal flow”?**

Se refiere a la forma en que se presentan los elementos de la página web si no cambias su comparación.

**2.¿Cuáles son algunas de las diferencias entre los elementos block-level e inline?**

+ Los elementos block-level respetan todas las propiedades del modelo de caja (width, height, margin, padding, border, background, float, clear, overflow). Esto significa que puedes ajustar su tamaño y espacio de manera precisa.

+ Los elementos block-level ocupan todo el ancho disponible de su contenedor y siempre comienzan en una nueva línea.

+ Los elementos inline solo respetan las propiedades horizontales del modelo de caja (padding-left, padding-right, margin-left, margin-right, border-left, border-right).

+ Ls elementos inline no inician en una nueva línea y solo ocupan el ancho necesario para su contenido. Esto permite que varios elementos inline estén en la misma línea.

+ En los elementos inlne el tamaño se determina por el contenido.

**3.El ___ positioning es la posición por defecto de todos los elementos en html.**

Static positioning

**4.Nombra algunas ventajas de utilizar absolute positioning en un elemento.**

+ Permite colocar un elemento en una ubicación exacta dentro de su contenedor relativo.

+ Facilita la creación de efectos visuales como menús desplegables, modales, pop-ups y tooltips.

+ No afectan ni son afectados por la disposición de otros elementos en el flujo.

+ Diseño adaptable y preciso.
  
**5.¿Cuál es una diferencia clave entre fixed positioning y absolute positioning?**

El posicionamiento absoluto fija un elemento en su lugar en relación con su ancestro posicionado más cercano (el bloque contenedor inicial si no lo hay), el posicionamiento fijo generalmente fija un elemento en lugar en relación con la parte visible de la ventana gráfica. 

## Aprende  JS.

### Funciones.

**1.Describe la diferencia entre una declaración de función y una invocación de función.**

Diferencia:

Declaración de función crea una nueva función con el nombre dado, son elevadas al inicio de su ámbito, por lo que puedes llamar a la función antes de su declaración en el código y solo establece lo que la función hará cuando se invoque.

La Invocación de función ejecuta el bloque de código definido dentro de esa función, los argumentos pasados a la función reemplazan los parámetros definidos en el la declaración de la función y puede devolver un valor (si la función usa return) o simplemente ejecutar su bloque de código.

**2.¿Cuál es la diferencia entre un parameter y un argument?**

Parámetro: Es una variable definida en la firma de una función o método. Representa un espacio reservado para recibir un valor cuando se llama a la función.

Argumento: Es el valor real que se pasa al llamar a una función. En el ejemplo anterior, “Juan” es el argumento que se pasa al parámetro “nombre”.