# *Clase 01: Lecturas: Introducción a React y los Componentes*

## **Responde**

**1. ¿Qué es un “componente”?**

Un componente en React es una pieza reutilizable de la interfaz de usuario. Los componentes pueden ser tan simples como un botón o tan complejos como una barra de navegación. Cada componente en React es una función o una clase que puede tener su propio estado y lógica, y se puede combinar con otros componentes para construir aplicaciones más grandes y complejas.

**2. ¿Cuáles son las características de un componente?**

Las características principales de un componente en React son:

- Reutilizabilidad: Los componentes pueden ser reutilizados en diferentes partes de la aplicación, lo que facilita el mantenimiento y la escalabilidad del código.
- Encapsulamiento: Cada componente maneja su propio estado y lógica, lo que permite que diferentes partes de la aplicación funcionen de manera independiente.
- Composición: Los componentes pueden ser combinados para formar interfaces de usuario más complejas. Un componente puede contener otros componentes.
- Propiedades (Props): Los componentes pueden recibir datos a través de propiedades, lo que permite la comunicación entre componentes.
- Estado (State): Los componentes pueden tener su propio estado interno, que puede cambiar con el tiempo y afectar la representación del componente.
- Ciclo de vida: Los componentes tienen métodos de ciclo de vida que permiten ejecutar código en diferentes etapas de su existencia, como cuando se montan, actualizan o desmontan.

**3. ¿Cuáles son las ventajas de utilizar una arquitectura basada en componentes?**

Utilizar una arquitectura basada en componentes en React ofrece varias ventajas significativas:

- Mantenibilidad: Al dividir la interfaz de usuario en componentes pequeños y manejables, el código se vuelve más fácil de entender, mantener y actualizar.
- Reutilización: Los componentes pueden ser reutilizados en diferentes partes de la aplicación o incluso en diferentes proyectos, lo que ahorra tiempo y esfuerzo.
- Aislamiento: Cada componente maneja su propio estado y lógica, lo que reduce el riesgo de que los cambios en una parte de la aplicación afecten a otras partes.
- Composición: Los componentes pueden ser combinados para crear interfaces de usuario complejas de manera modular, facilitando la construcción y el diseño de aplicaciones.
- Pruebas: Los componentes individuales pueden ser probados de manera aislada, lo que mejora la calidad del código y facilita la detección de errores.
- Desarrollo Colaborativo: En equipos de desarrollo, diferentes miembros pueden trabajar en diferentes componentes de manera simultánea sin interferir en el trabajo de los demás.
- Rendimiento: React optimiza la actualización de la interfaz de usuario mediante un proceso llamado “reconciliación”, que minimiza las operaciones costosas en el DOM.

**4. ¿Qué significa “props”?**

En React, “props” (abreviatura de “properties”) son un mecanismo para pasar datos de un componente a otro. Los props permiten que los componentes sean más dinámicos y reutilizables al permitirles recibir datos y comportamientos desde sus componentes padres.

**5. ¿Cómo se utilizan los props en React?**

**Definir los Props en el Componente Padre**: Cuando utilizas un componente hijo dentro de un componente padre, puedes pasarle props como atributos HTML.

```jsx
function App() {
  return <Greeting name="Alice" />;
}
```

**Recibir los Props en el Componente Hijo**: En el componente hijo, puedes acceder a los props a través del objeto `props` en componentes funcionales o `this.props` en componentes de clase.

**Componente Funcional**:
```jsx
function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}
```

**Componente de Clase**:
```jsx
class Greeting extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}!</h1>;
  }
}
```

**Usar los Props en el Componente Hijo**: Dentro del componente hijo, puedes usar los props para personalizar la salida del componente.

```jsx
function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}
```

**Pasar Funciones como Props**: También puedes pasar funciones como props para manejar eventos o realizar acciones en el componente hijo.

```jsx
function App() {
  const handleClick = () => {
    alert('Button clicked!');
  };

  return <Button onClick={handleClick} />;
}

function Button(props) {
  return <button onClick={props.onClick}>Click me</button>;
}
```

**6. ¿Cuál es el flujo de los props?**

En React, los **props** (abreviatura de "properties") son una forma de pasar datos de un componente padre a un componente hijo. Aquí tienes un resumen del flujo de los props:

**Definición en el componente padre**: Los props se definen en el componente padre y se pasan al componente hijo como atributos de JSX.
   ```jsx
   function App() {
     return (
       <div>
         <Header title="Mi Aplicación" />
       </div>
     );
   }
   ```

**Recepción en el componente hijo**: El componente hijo recibe los props como un objeto y puede acceder a ellos usando `props.nombreDelProp`.
   ```jsx
   function Header(props) {
     return (
       <h1>{props.title}</h1>
     );
   }
   ```

**Uso de destructuring**: Para hacer el código más limpio, puedes usar destructuring para extraer los props directamente.
   ```jsx
   function Header({ title }) {
     return (
       <h1>{title}</h1>
     );
   }
   ```

**Props son de solo lectura**: Los props son inmutables, lo que significa que el componente hijo no puede modificar los props que recibe. Si necesitas cambiar los datos, debes hacerlo en el componente padre y pasar los datos actualizados nuevamente como props⁴.

**Flujo unidireccional**: El flujo de datos en React es unidireccional, es decir, los datos fluyen de los componentes padres a los hijos. Esto ayuda a mantener la lógica de la aplicación clara y predecible⁴.
