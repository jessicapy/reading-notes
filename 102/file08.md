# **Programación con Javascript: Operadores y bucles**

Los operadores en JavaScript son como pequeños ayudantes que hacen cosas por nosotros. Aquí tienes algunos ejemplos:

**Operadores de suma (+)**: Imagina que tienes 2 manzanas y tu amigo te da 3 manzanas más. Ahora tienes 2 + 3 = 5 manzanas. Aquí, el signo más (+) es un operador de suma.
**Operadores de resta (-)**: Si tienes 5 manzanas y comes 2, te quedan 5 - 2 = 3 manzanas. Aquí, el signo menos (-) es un operador de resta.

Ahora, hablemos de los bucles. Los bucles son como un juego de “Simon dice”. Si Simon dice “da 5 saltos”, saltas 5 veces. En JavaScript, un bucle te permite hacer algo una y otra vez hasta que se cumpla una condición. Aquí tienes un ejemplo de un bucle:

for (var i = 0; i < 5; i++) {
    console.log("¡Estoy saltando!");
}

En este código, la variable i comienza en 0. Mientras i sea menor que 5, el código dentro del bucle se ejecutará y verás el mensaje “¡Estoy saltando!” en la consola. Cada vez que el código dentro del bucle se ejecuta, i aumenta en 1 (i++), por lo que el mensaje se imprimirá 5 veces.

## **Responde**

**1. ¿Qué es una “expresión” en JavaScript?**

Una “expresión” en JavaScript es cualquier unidad de código que se puede evaluar y produce un valor. Piensa en ello como una pequeña máquina que toma algunas piezas, hace algo con ellas y luego escupe algo.

Por ejemplo, si tienes dos números, puedes usar un operador para crear una expresión que produzca un nuevo número. Aquí tienes un ejemplo:

var suma = 5 + 7; // "5 + 7" es una expresión que se evalúa a 12

En este caso, 5 + 7 es una expresión que se evalúa a 12. La variable suma ahora contiene el valor 12.

**2. ¿Por qué usaríamos un bucle en nuestro código?**

**Para evitar la repetición de código:** Imagina que quieres decir “¡Hola!” 100 veces. Sin un bucle, tendrías que escribir la misma línea de código 100 veces. Pero con un bucle, puedes escribir unas pocas líneas de código que se ejecutan 100 veces.

**Para recorrer elementos:** Si tienes una lista de elementos, como una lista de tus juguetes favoritos, puedes usar un bucle para recorrer cada elemento de la lista y hacer algo con él, como imprimir su nombre.

**Para automatizar tareas:** Los bucles pueden realizar tareas automáticamente hasta que se cumpla una condición. Por ejemplo, podrías tener un bucle que siga pidiendo al usuario que ingrese una contraseña hasta que ingrese la correcta.

**3. ¿Cuándo deja de ejecutarse un bucle for?**

Un bucle "for" en JavaScript deja de ejecutarse cuando su condición de control ya no se cumple.

**4. ¿Cuántas veces se ejecutará un bucle “ while “?**

Un bucle while en JavaScript se ejecutará tantas veces como sea necesario hasta que su condición de control ya no se cumpla.