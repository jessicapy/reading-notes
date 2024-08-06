# Descripción del problema, Objetos y el DOM.

## Conceptos básicos de los objetos JavaScript.

**1. ¿Cómo le describirías un objeto a un amigo sin conocimiento técnico con el que creciste?**

Imagina un objeto como una caja que guarda información sobre algo, como un libro, una persona o una mascota. Cada caja tiene compartimentos para diferentes datos, como el título del libro, el nombre de la persona o la edad de la mascota. Además, la caja puede tener "acciones" que se pueden realizar, como abrir el libro, llamar a la persona o jugar con la mascota.

Los objetos son como las cajas que organizan información y permiten que hagamos cosas con ella.

**2. ¿Cuáles son algunas de las ventajas de crear objetos literales?**

+ Disminuyen la cantidad de código repetido.

+ Permiten definir propiedades con una amplia variedad de tipos de datos, incluyendo cadenas de texto, números, booleanos, funciones u otros objetos.

+ Permitecrear objetos de forma rápida y sencilla.

+ Tiene una sintaxis simple.

**3. ¿En qué se diferencian los objetos de los arrays?**

 Los objetos se utlizan para representar cosas únicas pero con múltiples características y los arrays se utilizan para representar listas de cosas múltiples.

**4. Da un ejemplo acerca de los momentos en los que necesitarías utilizar bracket notation para acceder a la propiedad de un objeto en vez de dot notation.**

 Cuando necesitas registrar el nombre y la edad de una persona.
```js
      person["age"];
      person["name"]["first"];

      const person = {
           name: ["Bob", "Smith"],
           age: 32,
      };
```

**5. Evalúa el siguiente código. ¿A qué se refiere el término this y cuál es la ventaja de utilizarlo?**

```js
       const dog = {
           name: 'Spot',
           age: 2,
           color: 'white with black spots',
           humanAge: function (){
          console.log(`${this.name} is ${this.age*7} in human years`);
        }
      }
```

This se refiere al objeto actual en el que se está escribiendo el código, por lo que en este caso this es equivalente a person. 

La ventaja de usar this es que si crea más de un objeto literal te  permite utilizar la misma definición de método para cada objeto que cree.

## Introducción al DOM.

**1. ¿Qué es el DOM?**

Modelo de objeto de documento (DOM). Es una interfaz de programación para los documentos HTML y XML. 
Es una representación orientada al objeto de la página web y puede ser modificado con un lenguaje de script como JavaScript.

**2. Describe brevemente la relación entre el DOM y JavaScript.**

 DOM proporciona la estructura y JavaScript las herramientas para interactuar y modificar esa estructura en tiempo real.

## Marcadores y Repaso.

**1. ¿Por qué parece tan difícil programar?**

Porque no seguimos los 4 pasos fundamentales:

+ Entender bien el problema
+ Diseñar un método para resolverlo (algoritmo)
+ Escribir el programa en un lenguaje concreto
+ Depuración y pruebas.

  Avece nos parece muy difícil realizar estos pasos que intentamos saltearnos los 2 primeros pasos y luego lo intentemos compilar una y otra vez y el programa no funione, eso nos terminará frustando y hará que programgar sea difícil.
  
**2. ¿Cuál es la diferencia entre valores primitivos y referencias a objetos en JavaScript?**

Los valores primitivos no se pueden cambiar (inmutables ), pero las referencias a objetos se pueden cambiar(mutables).