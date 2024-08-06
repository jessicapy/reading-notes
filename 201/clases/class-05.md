# Imágenes, Color, Texto.

## Medios en HTML

**1. ¿Cuál es un caso práctico del atributo alt en una página web?**

Cuando colocamos mal el nombre del archivo o su ruta, el navegador nos mostrará el texto alternativo que escribimos y asi nos daremos cuenta del error. 

**2. ¿Cómo puedes mejorar la accesibilidad de las imágenes en un documento HTML?**

Podemos mejorarla añadiendo:
+ Texto alternativo `<alt>`

+ Anchura y altura

+ Título de imágenes.

**3. Da un ejemplo en el que el elemento figure sería útil en un documento HTML.**

```js 
<figure>
  <img
      src="images/flores.jpg"
      alt="Rosas rojas"
      width="400"
      height="341" />
    <figcaption>
      Rosas rosas se entregan el 21 de marzo a la persona que te gusta.
    </figcaption>
  </figure>
```

El elemento figure proporciona un contenedor semántico para las figuras y vincular claramente la figura con el pie.
Esta encapsulando el contenido independiente de la imágen que es referenciado en el contenido principal del documento.
El elemento `<figcaption>` dice al navegador, que el texto que contiene describe la imagen que está contenida en el elemento `<figure>`.

**4. Describe la diferencia entre una imágen gif y una imágen svg, imagina que se lo estás explicando a una persona mayor de tu comunidad.**

Una imagen git  tiene buenas animaciones cortas y gráficos simples, pero limitadas en calidad y pueden ser grandes en tamaño.
A diferencia de una imagen svg son claros y nítidos a cualquier tamaño, generalmente no son animados pero son muy versátiles y ligeros y son archivos pequeños en tamaño.

**5. ¿Qué tipo de imagen usarías para mostrar una captura de pantalla en tu página web y por qué?**

Utilizaría un PNG, por que utiliza compresión sin pérdidas, admite altas profundidades de color y admite transparencia alfa total.

## Aprende CSS.

**1. Describe la diferencia entre un color de primer plano y un color de fondo de un elemento HTML, imagina que estás hablando con una personas sin conocimientos técnicos.**

+ **Color de Primer Plano:** El color del contenido principal de un elemento HTML, se usa la propiedad `color`.
+ **Color de Fondo:**  El color detrás del contenido principal, se usa la propiedad `background-color`.

  **Ejemplo:**

```js
          <div style="color: rojo; background-color: amarillo;">
                Este mensaje es de color rojo sobre fondo amarillo.
          </div>
```

**2. Tu amigo te pide que le des un retoque a su blog. ¿Cómo utilizarías color para darle carácter a su blog?**

Primero agregaría una clase a los elementos nesesarios de html. Luego añadíria estilos con las propiedades background-color, color, border, padding, margin, text-align, display, text-decoration,  etc. En cada clase de los elementos según correponda.

**3. ¿Qué debes tener en cuenta al escoger tipos de letra para un documento HTML?**

+ Familia de tipos de letras

+ Color

+ Tipos de letra seguros para la web

+ Fuentes predeterminadas

+ Listas de tipos de letra

+ Tamaño de la letra

+ Estilo y cuerpo del tipo de letra, efectos y decoración del texto

+ Textos sombreados

+ Sombras múltiples

**4. ¿Cuál es la relación entre font-size, font-weight, y font-style con los elementos de texto en HTML?**

+  font-size se usa para definir el tamaño de la letra.

+  font-weight se usa para definir el peso de la letra.

+  font-style define el aspecto de una familia tipográfica. 

**5. Describe dos formas de añadir espaciado alrededor de los caracteres mostrados en un elemento h1.**

+ letter-spacing: establece el comportamiento del espaciado horizontal entre caracteres de texto.
+  word-spacing: establece la longitud del espacio entre palabras y entre etiquetas.