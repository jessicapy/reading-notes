# *Clase 02: Lecturas: State y Props*

## **Responde**

**1. Según el diagrama, ¿qué sucede primero, el ‘render’ o el ‘componentDidMount’?**

En React, el método componentDidMount se ejecuta después del primer ciclo de renderizado. Es decir, primero ocurre el render, y luego, inmediatamente después, se invoca componentDidMount.

**2. ¿Qué es lo primero que sucede en el ciclo de vida de React?**

En el ciclo de vida de un componente de React, primero ocurre el render. Luego, inmediatamente después, se ejecuta el método componentDidMount. Este último es útil para realizar tareas como llamadas a APIs o configuraciones iniciales una vez que el componente ha sido montado.

**3. Coloca las siguientes cosas en el orden en que suceden: componentDidMount, render, constructor, componentWillUnmount, React Updates**

1. Constructor: Este método se llama cuando se crea una instancia del componente. Aquí es donde se inicializan los estados y se enlazan los métodos.
2. Render: El método `render` se ejecuta para generar la representación visual del componente en el DOM.
3. React Updates: Durante las actualizaciones, se ejecutan varios métodos, como `shouldComponentUpdate`, `componentWillUpdate` y `render`.
4. ComponentDidMount: Este método se llama después del primer renderizado, una vez que el componente ha sido montado en el DOM.
5. ComponentWillUnmount: Se ejecuta justo antes de que el componente sea eliminado del DOM.

**4. ¿Qué hace el componentDidMount?**

El método componentDidMount en React se ejecuta después del primer ciclo de renderizado. Es útil para realizar tareas como llamadas a APIs o configuraciones iniciales una vez que el componente ha sido montado.

**5. ¿Qué tipo de cosas puedes enviar mediante props?**

Mediante **props** en React, puedes enviar diferentes tipos de datos y valores desde un componente padre a un componente hijo. Algunos ejemplos comunes de lo que puedes enviar mediante props son:

1. Datos primitivos: Puedes pasar números, cadenas de texto, booleanos, etc.
2. Funciones: Puedes enviar funciones como props para que el componente hijo las utilice.
3. Objetos o arreglos: Puedes pasar objetos o arreglos como props.
4. Componentes: Sí, incluso puedes pasar componentes como props, lo que se conoce como "composición de componentes".

**6. ¿Cuál es la mayor diferencia entre props y state?**

¡Buena pregunta! En el contexto de **React**, tanto `props` como `state` son fundamentales, pero tienen diferentes propósitos:

1. Props (Propiedades):
   - Son **datos inmutables** que se pasan de un componente padre a un componente hijo.
   - Se utilizan para **comunicar información** de un componente superior a sus descendientes.
   - Los `props` se definen en el componente padre y se acceden en el componente hijo.
   - Ejemplo: Si tienes un componente `Mensaje` y quieres pasarle un texto específico, puedes hacerlo mediante `props`.

2. State (Estado):
   - Representa **datos mutables** que pertenecen a un componente y pueden cambiar con el tiempo.
   - Se utiliza para **almacenar información local** dentro de un componente.
   - El `state` se inicializa en el constructor del componente y se actualiza mediante `setState`.
   - Ejemplo: Si tienes un contador en un componente `Contador`, puedes usar el `state` para rastrear su valor.

En resumen, `props` se utiliza para pasar datos de arriba hacia abajo en la jerarquía de componentes, mientras que `state` se utiliza para gestionar datos internos dentro de un componente.

**7. ¿Cuándo volvemos a renderizar nuestra aplicación?**

En **React**, la renderización ocurre en los siguientes casos:

1. Inicialización:
   - Cuando se crea un componente por primera vez, se llama al método `render()` para generar su representación en el DOM.

2. Actualización del estado o props:
   - Si el `state` o los `props` de un componente cambian, React vuelve a llamar al método `render()` para actualizar la interfaz de usuario.

3. Métodos del ciclo de vida:
   - Durante el ciclo de vida del componente, hay otros métodos (como `componentDidUpdate`, `shouldComponentUpdate`, etc.) que pueden provocar una nueva renderización.

4. Forzado manualmente:
   - Puedes forzar una renderización manualmente llamando a `this.forceUpdate()` en un componente.

En resumen, React decide cuándo volver a renderizar un componente en función de los cambios en el estado, los props y los métodos del ciclo de vida.

**8. ¿Qué tipo de cosas puedes enviar mediante props?**

1. Datos del usuario:
   - Información como el nombre, correo electrónico, preferencias o configuraciones específicas del usuario.

2. Valores de entrada de formularios:
   - Cuando un usuario completa un formulario (por ejemplo, un campo de búsqueda o un formulario de registro), puedes almacenar los valores en el `state`.

3. Estado de carga o error:
   - Puedes usar el `state` para rastrear si una solicitud de API está en curso o si se ha producido un error.

4. Visibilidad de elementos:
   - Si deseas mostrar u ocultar ciertos elementos en función de alguna condición (por ejemplo, un menú desplegable), puedes usar el `state` para controlar su visibilidad.

5. Contadores y valores calculados:
   - Si necesitas rastrear la cantidad de clics, elementos en una lista o cualquier otro valor calculado, el `state` es útil.

Recuerda que el `state` debe usarse con moderación y solo para datos que afectan la representación visual del componente.