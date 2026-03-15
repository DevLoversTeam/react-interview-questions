**Read in other languages: [English 🇺🇸](README.en.md),
[Polska 🇵🇱](README.pl.md), [German 🇩🇪](README.de.md), [French 🇫🇷](README.fr.md),
[Spanish 🇪🇸](README.es.md), [Ukrainian 🇺🇦](README.md).**
<h1>
  React <img src="./assets/react.svg" width="40" height="40" />
</h1>

<h2>Las preguntas y respuestas mas populares en entrevistas sobre React</h2>

<details>
<summary>1. Que es React?</summary>

#### React

React es una biblioteca de JavaScript para crear interfaces de usuario.
Caracteristicas principales:

1. **Enfoque basado en componentes:** la interfaz se divide en componentes
   independientes que pueden reutilizarse.

2. **DOM virtual:** permite actualizar la interfaz de forma eficiente,
   minimizando las manipulaciones del DOM real.

3. **Naturaleza declarativa:** describes como debe verse la interfaz en un
   estado determinado, y React se encarga de mantenerla sincronizada.

4. **Flujo de datos unidireccional:** los datos se transmiten de arriba hacia
   abajo mediante props, lo que facilita el control del estado.

React fue creado por Facebook y se usa ampliamente para desarrollar SPA
(Single Page Applications).

</details>

<details>
<summary>2. Enumera las caracteristicas de React.</summary>

#### React

1. **Enfoque basado en componentes:** el codigo se divide en componentes
   reutilizables e independientes.

2. **DOM virtual:** actualizacion rapida de la interfaz sin manipular
   directamente el DOM.

3. **Flujo de datos unidireccional:** los datos se transmiten de los
   componentes padre a los hijos mediante props.

4. **JSX:** extension de la sintaxis de JavaScript para escribir interfaces en
   forma de codigo similar a XML.

5. **Estado y ciclo de vida:** los componentes pueden almacenar y gestionar su
   propio estado.

6. **React Hooks:** anaden capacidades para trabajar con estado y efectos
   secundarios en componentes funcionales.

7. **Ecosistema:** admite bibliotecas como React Router y Redux para ampliar
   la funcionalidad.

8. **Amigable con SEO con Next.js:** el renderizado del lado del servidor
   mejora la indexacion.

9. **Desarrollo movil:** React Native permite crear aplicaciones moviles
   basadas en React.

10. **Codigo abierto:** cuenta con un fuerte apoyo de la comunidad.

</details>

<details>
<summary>3. Cuales son las funciones principales de React?</summary>

#### React

#### Funciones principales de React:

1. **Enfoque declarativo:** React permite crear interfaces interactivas
   describiendo como deben verse, mientras la biblioteca optimiza las
   actualizaciones del DOM.

2. **Estructura basada en componentes:** la aplicacion se construye a partir de
   componentes independientes y reutilizables, lo que simplifica el desarrollo,
   las pruebas y el mantenimiento.

3. **DOM virtual:** React usa el DOM virtual para actualizar el DOM real de
   forma eficiente, lo que mejora notablemente el rendimiento.

4. **Flujo de datos unidireccional:** los datos se pasan de los componentes
   padre a los hijos mediante props, lo que simplifica la gestion del estado.

5. **Hooks:** permiten usar estado y metodos del ciclo de vida en componentes
   funcionales.

6. **JSX:** extension de JavaScript para describir la interfaz con una sintaxis
   similar a HTML.

7. **React Native:** permite crear aplicaciones moviles nativas usando los
   mismos principios que en la web.

8. **Ecosistema:** amplio conjunto de bibliotecas y herramientas como React
   Router, Redux y Context API.

9. **Soporte de renderizado del lado del servidor (SSR):** ayuda a optimizar el
   SEO y acelerar la carga inicial de las paginas.

10. **Gestion del estado:** mediante `useState`, Context API, Redux u otras
    bibliotecas.

Estas funciones convierten a React en una biblioteca potente y flexible para
crear aplicaciones modernas.

</details>

<details>
<summary>4. Cuales son las ventajas clave de usar React?</summary>

#### React

#### Ventajas clave de usar React

1. **Velocidad**: gracias al DOM virtual, React minimiza la interaccion con el
   DOM real, lo que mejora el rendimiento.

2. **Enfoque basado en componentes**: el codigo se divide en componentes
   reutilizables, lo que facilita el desarrollo y el mantenimiento.

3. **Flujo de datos en una sola direccion**: en React, los datos fluyen de
   arriba hacia abajo, lo que facilita la depuracion.

4. **Gran comunidad**: React tiene un enorme ecosistema de bibliotecas,
   herramientas y extensiones.

5. **Compatibilidad con el desarrollo movil**: con React Native se pueden crear
   aplicaciones moviles multiplataforma.

6. **JSX**: sintaxis que permite escribir JavaScript junto con una estructura
   similar a HTML, mejorando la legibilidad.

7. **Soporte de hooks**: simplifica el trabajo con el estado y el ciclo de vida
   en componentes funcionales.

8. **Compatibilidad con SEO**: el renderizado del lado del servidor con
   herramientas como Next.js mejora la optimizacion para buscadores.

9. **Flexibilidad**: React puede integrarse en casi cualquier proyecto o
   framework sin grandes cambios en el codigo.

10. **React DevTools**: herramienta de depuracion que permite inspeccionar
    comodamente los componentes y el estado de la aplicacion.

</details>

<details>
<summary>5. Que es JSX?</summary>

#### React

**JSX (JavaScript XML)** es una sintaxis que permite escribir estructuras de
interfaz como codigo similar a XML dentro de JavaScript. JSX es una extension
de JavaScript y se usa en React para describir como se ve la interfaz.

#### Caracteristicas principales de JSX:

1. **Sintaxis similar a XML:** se parece a HTML, pero se usa dentro de
   JavaScript.

```jsx
const element = Hello, world!;
```

2. **JavaScript incrustado:** puedes escribir codigo JavaScript dentro de llaves
   `{}`.

```jsx
const name = 'Alice';
const element = Hello, {name}!;
```

3. **Transpilacion:** JSX se compila a JavaScript normal usando bibliotecas
   como Babel.

```jsx
const element = Hello;
// Se convierte en:
const element = React.createElement('h1', null, 'Hello');
```

4. **Atributos:** se usan de forma similar a HTML, pero en lugar de `class` se
   escribe `className`, y en lugar de `for`, `htmlFor`.

```jsx
const input = ;
```

5. **JSX devuelve un arbol de elementos:** una expresion JSX solo puede
   devolver un elemento raiz. Para agrupar, usa `<React.Fragment>` o el tag
   vacio `<>`.

```jsx
return <>Title Description</>;
```

#### Ventajas:

- Creacion comoda de componentes de interfaz.
- Sintaxis clara y legible.
- Integracion estrecha con la logica de JavaScript.

JSX no es obligatorio en React, pero se usa ampliamente por su comodidad y
flexibilidad.

</details>

<details>
<summary>6. Cual es la diferencia entre state y props?</summary>

#### React

#### Diferencia entre state y props

| Criterio | State | Props |
| -------- | ----- | ----- |
| **Proposito** | Almacena el estado interno del componente. | Transmite datos del componente padre al hijo. |
| **Mutabilidad** | Puede cambiar dentro del componente. | Es inmutable, de solo lectura. |
| **Disponibilidad** | Solo esta disponible en el componente donde se define. | Esta disponible en el componente hijo a traves de atributos. |
| **Inicializacion** | Se establece con `useState` o en el constructor. | La define el componente padre. |
| **Ambito de uso** | Para guardar datos dinamicos que pueden cambiar. | Para pasar datos fijos o dinamicos. |
| **Quien lo controla** | El componente donde se define el state. | El componente padre. |

</details>

<details>
<summary>7. Cual es la diferencia entre un elemento y un componente?</summary>

#### React

#### Diferencia entre un elemento y un componente en React:

| Criterio | Elemento | Componente |
| -------- | -------- | ---------- |
| **Definicion** | Objeto que describe como debe verse la interfaz. | Funcion o clase que devuelve elementos React. |
| **Tipo** | Inmutable. | Reutilizable y puede tener estado. |
| **Sintaxis de creacion** | `React.createElement` o JSX (`<div />`). | Funcion o clase (`function MyComponent() {}` o `class MyComponent extends React.Component {}`). |
| **Proposito** | Representa un nodo individual del DOM. | Encapsula la logica y la estructura de la interfaz. |
| **Uso** | Se usa para crear UI en un nivel basico. | Se usa para construir estructuras mas complejas con logica de negocio. |
| **Ejemplo** | `<h1>Hello</h1>` | `function Hello() { return <h1>Hello</h1>; }` |

Un elemento es un "bloque de construccion", mientras que un componente es un
"constructor" para crear interfaces mas complejas.

</details>

<details>
<summary>8. Como se crean componentes en React?</summary>

#### React

#### En React, los componentes pueden crearse de dos formas:

1. **Componente funcional:** es una funcion simple que devuelve elementos
   React.

```jsx
function Greeting(props) {
  return Hello, {props.name}!;
}

// Uso:
;
```

2. **Componente de clase:** es una clase que hereda de `React.Component` y debe
   tener un metodo `render`.

```jsx
class Greeting extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Uso:
;
```

#### Diferencias:

- Los componentes funcionales son mas simples y se adaptan mejor a componentes
  sin estado complejo.

- Los componentes de clase se usan en componentes mas complejos con estado
  propio o metodos de ciclo de vida.

**Nota:** el enfoque moderno consiste en usar componentes funcionales con hooks
en lugar de componentes de clase.

</details>

<details>
<summary>9. Que es el state en React?</summary>

#### React

El **state** en React es un objeto o valor usado para almacenar datos que
pueden cambiar con el tiempo y afectar al renderizado del componente. El state
permite que los componentes sean dinamicos y reaccionen a eventos, entradas del
usuario y otros cambios.

#### Caracteristicas del state:

1. **Local al componente:** el state solo esta disponible en el componente
   donde se define.

2. **Cambia de forma asincrona:** React agrupa llamadas como `setState` para
   optimizar el renderizado.

3. **Se inicializa en el constructor** en componentes de clase o mediante
   `useState` en componentes funcionales.

#### En componentes de clase:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        Count: {this.state.count}
        Increment

    );
  }
}
```

#### En componentes funcionales con el hook `useState`:

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (

      Count: {count}
      <button onClick={() => setCount(count + 1)}>Increment

  );
}
```

#### Diferencias principales entre state y props:

- **State** es local al componente y puede cambiar.

- **Props** se reciben desde fuera y son inmutables.

</details>

<details>
<summary>10. Que son las props en React?</summary>

#### React

Las **props** en React son un objeto que contiene datos transmitidos del
componente padre al componente hijo. Se usan para configurar componentes y son
inmutables.

#### Caracteristicas de las props:

1. **Se pasan de arriba hacia abajo** dentro del flujo de datos unidireccional,
   del componente padre al hijo.

2. **Son inmutables**: el componente no puede modificar las props recibidas.

3. **Son dinamicas**: sus valores pueden cambiar si cambian los datos en el
   componente padre.

#### Uso de las props:

1. **En un componente funcional:**

```jsx
function Welcome(props) {
  return Hello, {props.name}!;
}

// Uso:
;
```

2. **En un componente de clase:**

```jsx
class Welcome extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Uso:
;
```

#### Paso de props:

```jsx
function App() {
  return (

  );
}
```

**Resultado:**

```bash
Hello, Alice!
Hello, Bob!
```

#### Desestructuracion de props:

```jsx
function Welcome({ name }) {
  return Hello, {name}!;
}
```

#### Valores por defecto de las props:

```jsx
function Welcome({ name = 'Guest' }) {
  return Hello, {name}!;
}

// Uso:
; // Mostrara: Hello, Guest!
```

Las props aportan flexibilidad y reutilizacion a los componentes React.

</details>

<details>
<summary>11. Por que es necesario el atributo key al renderizar listas?</summary>

#### React

El atributo `key` se utiliza para identificar elementos en listas durante el
renderizado.

#### Funcion:

1. **_Optimizacion de actualizaciones:_** React utiliza `key` para actualizar
   la interfaz de forma eficiente, identificando rapidamente que elementos debe
   modificar, anadir o eliminar.

2. **_Prevencion de renders innecesarios:_** `key` ayuda a evitar el rerender
   de elementos que no cambiaron.

3. **_Conservacion del estado de los componentes:_** por ejemplo, si un
   elemento de la lista contiene un formulario, `key` permite a React mantener
   su estado entre actualizaciones.

#### Uso correcto:

- El valor de `key` debe ser unico entre elementos hermanos.

- Lo ideal es usar identificadores estables, por ejemplo un `id` de una base de
  datos.

- No se recomienda usar el indice del array como `key`, ya que eso puede causar
  errores cuando cambia el orden de los elementos.

```jsx
const items = ['Apple', 'Banana', 'Cherry'];
return (

    {items.map((item, index) => (
      {item} // Key unica para cada elemento
    ))}

);
```

</details>

<details>
<summary>12. Como se transmiten los datos entre componentes en React?</summary>

#### React

En React, los datos se transmiten entre componentes segun la jerarquia de la
siguiente manera:

#### Paso de datos hacia abajo, del componente padre al hijo

Para transmitir datos hacia abajo se usan las props. El componente padre pasa
valores o funciones al componente hijo mediante atributos.

**Ejemplo:**

```jsx
function ParentComponent() {
  const data = 'Hello from Parent';

  return;
}

function ChildComponent({ message }) {
  return { message };
}
```

`message` transmite el valor `data` al componente hijo `ChildComponent`.

En el componente hijo, las props se reciben a traves de los parametros de la
funcion o mediante `this.props` en un componente de clase.

#### Paso de datos hacia arriba, del componente hijo al padre

Los datos se transmiten hacia arriba mediante funciones callback. El componente
padre pasa una funcion al hijo, y el hijo la ejecuta con los datos necesarios.

**Ejemplo:**

```jsx
function ParentComponent() {
  const handleData = childData => {
    console.log('Data from child:', childData);
  };

  return ;
}

function ChildComponent({ sendData }) {
  const data = 'Hello from Child';

  return <button onClick={() => sendData(data)}>Send Data;
}
```

El componente padre pasa la funcion `handleData` en la prop `sendData`.

El componente hijo llama a `sendData` pasando el valor `data`.

#### Enfoques alternativos para aplicaciones complejas:

1. **Contexto (Context API):**

Para transmitir datos a traves de muchos niveles sin pasar props manualmente.

Es adecuado para estado global, por ejemplo el tema o el idioma de la
interfaz.

```jsx
const MyContext = React.createContext();

function ParentComponent() {
  const data = 'Hello from Context';

  return (

  );
}

function ChildComponent() {
  const contextData = React.useContext(MyContext);

  return {contextData};
}
```

2. **Gestores de estado como Redux, Zustand o MobX:** para transmitir datos en
   aplicaciones grandes mediante un estado global compartido.

3. **Custom Hooks:** se utilizan para reutilizar logica entre componentes.

</details>

<details>
<summary>13. Por que React usa className en lugar del atributo class?</summary>

#### React

En React se usa `className` en lugar de `class` porque `class` es una palabra
reservada en JavaScript.

#### Razones:

1. **Evitar conflictos:** `class` se utiliza en JavaScript para definir clases,
   como en `class MyComponent {}`, lo que podria provocar errores de sintaxis.

2. **Compatibilidad con JSX:** como JSX es una extension sintactica de
   JavaScript, `className` ayuda a evitar ambiguedades.

3. **Correspondencia directa** con `document.createElement`: React transforma
   JSX en llamadas a `React.createElement`, y `className` se usa para asignar
   clases en elementos del DOM.

#### Ejemplo:

```jsx
// Variante correcta en React

Hello;

// Variante incorrecta, con error de sintaxis

Hello;
```

Este es el estandar de React y garantiza coherencia y estabilidad en el codigo.

</details>

<details>
<summary>14. Que reglas y excepciones existen para nombrar componentes en React?</summary>

#### React

En React existen varias reglas y particularidades importantes sobre el nombre
de los componentes:

1. **Mayuscula inicial:** los nombres de los componentes deben empezar con
   mayuscula. Esto es obligatorio para que React pueda distinguirlos de los
   elementos HTML estandar.

Por ejemplo:

- Correcto: `<MyComponent />`
- Incorrecto: `<myComponent />`

2. **CamelCase o PascalCase:** se recomienda usar este estilo para los nombres
   de componentes, es decir, cada palabra empieza con mayuscula:

- `MyComponent`
- `UserProfile`

3. **Los nombres no deben coincidir con elementos HTML:** no uses nombres como
   `div`, `span` o `button`, porque eso puede causar conflictos o comportamientos
   inesperados:

- Correcto: `<CustomButton />`
- Incorrecto: `<button />`, ya que React lo tratara como una etiqueta HTML
  normal

4. **Evitar caracteres especiales:** no uses espacios, guiones, guiones bajos
   u otros simbolos especiales en los nombres, ya que pueden producir errores
   de sintaxis:

- Correcto: `MyComponent`
- Incorrecto: `my_component`, `my-component`

5. **Componentes funcionales y de clase:** si usas clases para componentes,
   tambien deben empezar con mayuscula:

- `class MyComponent extends React.Component {}`

Seguir estas reglas ayuda a garantizar el funcionamiento correcto y la claridad
del codigo.

</details>

<details>
<summary>15. Como se escriben comentarios en React?</summary>

#### React

En React, los comentarios se escriben igual que en JavaScript, pero hay algunos
detalles importantes cuando se trata de JSX.

1. **Comentarios en JavaScript, fuera de JSX**

```javascript
// Comentario de una linea

/*
Comentario multilinea
*/
```

2. **Comentarios dentro de JSX**

- En JSX hay que usar una sintaxis especial, porque JSX forma parte de
  JavaScript.

- Los comentarios en JSX deben escribirse dentro de llaves `{}`:

```jsx
function MyComponent() {
  return (

      {/_ Este es un comentario dentro de JSX _/}
      Hello, world!

  );
}
```

- Los comentarios en JSX deben tener la forma `{/* comentario */}` o provocaran
  errores.

- Solo pueden usarse dentro de expresiones JSX.

3. **Comentarios en funciones y metodos**

- Dentro de funciones o metodos pueden usarse comentarios normales de
  JavaScript:

```jsx
function MyComponent() {
  // Aqui renderizamos el componente
  return Hello, world!;
}
```

#### Conclusion:

- En JSX usa `{/* comentario */}`.

- En JavaScript normal, usa `//` para comentarios de una linea y `/* ... */`
  para comentarios multilinea.

</details>

<details>
<summary>16. Que es el DOM virtual en React?</summary>

#### React

El **DOM virtual** es una representacion virtual del DOM real que React utiliza
para actualizar la interfaz de forma eficiente.

#### Como funciona en React:

1. **Renderizado en el DOM virtual:** cuando cambian el estado o las props,
   React actualiza el DOM virtual.

2. **Diffing:** React compara el nuevo DOM virtual con la version anterior para
   determinar el conjunto minimo de cambios.

3. **Actualizacion del DOM real:** los cambios detectados se aplican al DOM
   real, minimizando la cantidad de manipulaciones.

#### Ventaja principal:

La optimizacion de las actualizaciones del DOM mejora notablemente el
rendimiento de las aplicaciones.

</details>

<details>
<summary>17. Que es la prop key y cual es la ventaja de usarla en arrays de elementos?</summary>

#### React

En React, la prop `key` se utiliza para identificar cada elemento de una lista
o array y ayudar a React a gestionar de forma eficiente el renderizado cuando
los elementos cambian o se actualizan. Esto es importante para optimizar el
proceso de renderizado, especialmente cuando se anaden, eliminan o reordenan
elementos.

#### Puntos principales sobre `key`:

1. **Unicidad:** cada elemento de la lista debe tener un `key` unico. Esto
   permite a React saber que elementos cambian, se anaden o se eliminan, y
   tambien conservar su estado entre renders.

2. **Optimizacion del renderizado:** usar `key` permite a React minimizar la
   cantidad de rerenders y aplicar solo los cambios necesarios en el DOM. Sin
   `key`, React tiene mas dificultades para seguir los cambios y puede volver a
   renderizar toda la lista aunque solo haya cambiado un elemento.

3. **Naturaleza de key:** la prop `key` no se pasa al componente, por lo que no
   puede usarse para mostrar valores en la interfaz. Es una propiedad interna
   que React utiliza para rastrear elementos.

#### Ejemplo de uso de `key` en una lista:

```jsx
const items = ['apple', 'banana', 'cherry'];

function FruitList() {
  return (

      {items.map((item, index) => (
        {item} // Importante: usar una key unica
      ))}

  );
}
```

#### Importancia de la unicidad de `key`:

- **Uso incorrecto:** si se usan valores no unicos como `key`, por ejemplo el
  mismo indice, React no podra seguir correctamente los cambios y eso puede
  provocar errores de renderizado.

- **Key ideal:** si existe un identificador unico, como un `id`, debe usarse
  como `key` en lugar del indice del array.

```jsx
const items = [
  { id: 1, name: 'apple' },
  { id: 2, name: 'banana' },
  { id: 3, name: 'cherry' },
];

function FruitList() {
  return (

      {items.map(item => (
        {item.name} // Es mejor usar ids unicos
      ))}

  );
}
```

#### Ventajas de usar `key`:

- Mejora el rendimiento del renderizado.

- Permite a React actualizar solo los elementos modificados en lugar de toda la
  lista.

- Garantiza una gestion correcta del estado de los elementos cuando se mueven,
  eliminan o actualizan.

En resumen, usar `key` es fundamental para trabajar eficientemente con arrays
de elementos en React.

</details>

<details>
<summary>18. Que es el renderizado condicional en React?</summary>

#### React

El renderizado condicional en React es el proceso mediante el cual un
componente muestra contenido diferente segun determinadas condiciones. Esto
permite cambiar dinamicamente la interfaz en funcion del estado, las props u
otros factores.

#### Enfoques principales del renderizado condicional:

1. **Operador `if`:** se puede usar el operador `if` estandar para decidir que
   renderizar.

```jsx
function Greeting(props) {
  if (props.isLoggedIn) {
    return Welcome back!;
  }
  return Please sign up.;
}
```

2. **Operador ternario:** suele usarse para expresiones condicionales mas
   cortas.

```jsx
function Greeting(props) {
  return {props.isLoggedIn ? 'Welcome back!' : 'Please sign up.'};
}
```

3. **Operador logico AND (`&&`):** puede usarse para renderizar un elemento
   solo si la expresion situada a la izquierda es verdadera.

```jsx
function Notifications(props) {
  return (

      {props.unreadMessages.length > 0 && (
        You have {props.unreadMessages.length} unread messages.
      )}

  );
}
```

Esto funciona asi: si `props.unreadMessages.length` es mayor que 0, se
mostrara el mensaje; en caso contrario no se renderizara nada.

4. **Uso de `return` con logica condicional:** puedes usar `return` para
   renderizar condicionalmente, como en los ejemplos con `if` o con el operador
   ternario.

#### Ventajas del renderizado condicional:

- Permite cambiar el contenido de forma dinamica segun el estado o las props.

- Mejora la flexibilidad y permite mostrar contenido distinto segun el usuario
  o la situacion.

#### Ejemplo:

```jsx
function UserStatus(props) {
  return (

      {props.isLoggedIn ? (
        Log Out
      ) : (
        Log In
      )}

  );
}
```

Aqui el boton cambia segun si el usuario ha iniciado sesion o no.

</details>

<details>
<summary>19. Que son los fragmentos en React?</summary>

#### React

Los fragmentos en React son una forma de agrupar varios elementos sin anadir
nodos extra al DOM. Permiten devolver varios elementos desde un componente sin
envolverlos en un `div`, lo que ayuda a evitar elementos innecesarios que
podrian afectar los estilos o la estructura del documento.

#### Como se usan los fragmentos?

1. **Sin fragmentos, con contenedor:**

```jsx
function MyComponent() {
  return (

      Title
      Some text

  );
}
```

En este ejemplo se devuelve un `div` que envuelve a `h1` y `p`.

2. **Con fragmentos, sin contenedor:**

```jsx
function MyComponent() {
  return <>Title Some text</>;
}
```

Ahora `h1` y `p` se renderizan sin un contenedor adicional, lo que mantiene el
DOM mas limpio.

#### Ventajas:

- **DOM mas limpio:** permite evitar contenedores innecesarios.

- **Comodidad para renderizar varios elementos:** permite devolver varios
  elementos desde un mismo componente sin usar nodos extra.

#### Sintaxis:

- Se pueden usar las etiquetas vacias `<>` y `</>`, que son una forma abreviada
  de `<React.Fragment></React.Fragment>`.

- Tambien se puede usar `React.Fragment` cuando es necesario anadir claves, por
  ejemplo al renderizar listas:

```jsx
{
  item.name;
}
{
  item.description;
}
```

#### Cuando usarlos:

- Cuando necesitas renderizar varios elementos sin un contenedor adicional en
  el DOM.

- Cuando quieres mantener la estructura del componente sin afectar estilos o
  maquetacion.

Los fragmentos son muy utiles para reducir elementos innecesarios en el DOM y
mejorar el rendimiento.

</details>

<details>
<summary>20. Que es la reconciliacion (Reconciliation)?</summary>

#### React

La **reconciliacion** es el proceso que React utiliza para actualizar el DOM de
la forma mas eficiente posible. Cuando cambian el estado o las props de un
componente, React calcula los cambios minimos necesarios en el DOM real para
sincronizarlo con el DOM virtual.

#### Como funciona la reconciliacion?

1. **Comparacion del DOM virtual anterior y el nuevo:**

- React conserva una copia del DOM virtual anterior.
- Cuando cambian el estado o las props, se crea un nuevo DOM virtual.
- React compara el nuevo DOM virtual con la copia anterior mediante el algoritmo
  de diffing.

2. **Deteccion de diferencias (diffing):**

- React identifica que partes del arbol cambiaron, como elementos nuevos,
  cambios en atributos o eliminaciones.
- Para ello utiliza un algoritmo optimizado para trabajar con estructuras en
  arbol.

3. **Actualizacion del DOM real:**

- React aplica cambios solo a las partes del DOM que realmente deben
  actualizarse, evitando un rerender completo.

#### Principios principales de la reconciliacion:

- **Conservacion de nodos del mismo tipo:** si dos nodos tienen el mismo tipo,
  por ejemplo `<div>` sigue siendo `<div>`, React solo actualiza atributos e
  hijos.
- **Reutilizacion de componentes:** si el componente sigue siendo el mismo,
  React reutiliza la instancia existente.
- **Claves en listas:** si una lista se renderiza desde un array, React usa
  claves (`key`) para comparar y preservar nodos.

#### Ejemplo:

```jsx
function App({ isVisible }) {
  return isVisible ? Hello : Goodbye;
}
```

- Si `isVisible` cambia de `true` a `false`, React eliminara `<h1>` y lo
  sustituira por `<p>`.

#### Importancia de las claves (`key`) en las listas:

Las claves ayudan a React a identificar correctamente los cambios en listas.
Por ejemplo:

```jsx

  {items.map(item => (
    {item.text}
  ))}

```

Sin claves unicas, React no podra determinar con precision que elementos de la
lista cambiaron.

#### Ventajas de la reconciliacion:

- Reduce la cantidad de operaciones sobre el DOM.
- Mejora el rendimiento de las aplicaciones.
- Hace mas fluida la actualizacion de la interfaz de usuario.

</details>

<details>
<summary>21. Como se actualiza el estado de un componente?</summary>

#### React

En React, el estado de un componente se actualiza mediante el metodo
`setState` en componentes de clase o con `useState` en componentes
funcionales.

#### Componentes de clase:

El estado se actualiza con `this.setState()`.

#### Ejemplo:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        Count: {this.state.count}
        Increment

    );
  }
}
```

#### Componentes funcionales:

El estado se actualiza mediante la funcion obtenida de `useState`.

#### Ejemplo:

```jsx
import React, { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  const increment = () => {
    setCount(count + 1);
  };

  return (

      Count: {count}
      Increment

  );
}
```

#### Notas:

1. **Asincronia:** `setState` y `useState` funcionan de forma asincrona. Para
   actualizar el estado a partir del valor anterior, usa el enfoque funcional:

```jsx
this.setState(prevState => ({ count: prevState.count + 1 }));
setCount(prevCount => prevCount + 1);
```

2. **No actualices el estado directamente:** modificar el estado sin usar
   `setState` o `useState` no provoca un nuevo renderizado.

</details>

<details>
<summary>22. Que son las expresiones condicionales incrustadas?</summary>

#### React

Las **expresiones condicionales incrustadas** en JavaScript, especialmente en
React, son mecanismos que permiten insertar condiciones directamente en JSX
para renderizar elementos o componentes de forma condicional. Esto hace que el
codigo sea mas compacto y facil de entender.

#### Metodos principales:

1. **Operador condicional, o ternario:** es una de las formas mas comunes de
   hacer renderizado condicional en JSX. Su sintaxis es la siguiente:

```jsx
condicion ? expresion_si_verdadero : expresion_si_falso;
```

**Ejemplo:**

```jsx
const isLoggedIn = true;

function App() {
  return {isLoggedIn ? Welcome, User! : Please log in};
}
```

2. **Operador logico AND (`&&`):** este metodo permite mostrar un componente o
   elemento solo cuando la condicion es verdadera. Si no se cumple, no se
   renderiza nada.

**Ejemplo:**

```jsx
const isUserAdmin = true;

function App() {
  return {isUserAdmin && You have admin privileges};
}
```

En este caso, `<p>You have admin privileges</p>` se mostrara solo si
`isUserAdmin` es `true`.

3. **`if` antes de devolver JSX:** tambien pueden usarse condiciones `if`
   normales antes de retornar JSX cuando la logica es mas compleja o cuando hay
   que realizar varias acciones condicionales.

**Ejemplo:**

```jsx
function App() {
  let content;
  if (isLoggedIn) {
    content = Welcome back!;
  } else {
    content = Please sign in.;
  }

  return {content};
}
```

**Ventajas:**

- Las expresiones condicionales incrustadas permiten escribir un codigo mas
  limpio y compacto.

- Mejoran la legibilidad y reducen el uso de estructuras condicionales
  adicionales.

#### Importante:

- En React no se pueden usar instrucciones `if` directamente dentro de JSX, pero
  si pueden utilizarse antes del `return`.

</details>

<details>
<summary>23. Cual es la diferencia entre el manejo de eventos en HTML y en React?</summary>

#### React

#### Diferencia entre el manejo de eventos en HTML y en React:

| Criterio | HTML | React |
| -------- | ---- | ----- |
| **Vinculacion del evento** | Se indica como atributo: `<button onclick="handler()">`. | Se usa camelCase: `<button onClick={handler}>`. |
| **Tipo de funcion** | Referencia a una funcion global o cadena con codigo JavaScript. | Vinculacion a una funcion del componente, normalmente metodo o funcion flecha. |
| **Adicion de listeners** | Los controladores se agregan manualmente con `addEventListener`. | React gestiona la vinculacion automaticamente mediante el DOM virtual. |
| **Contexto `this`** | Debe establecerse manualmente si se usa en clases. | En componentes funcionales no hay ese problema; en clases sigue siendo necesario gestionarlo. |
| **Comportamiento por defecto** | A menudo se usa `return false` para detener el comportamiento. | Se usa `event.preventDefault()` para impedirlo. |
| **Compatibilidad** | Maneja solo eventos reales del DOM. | Usa `SyntheticEvent`, una envoltura sobre eventos nativos. |
| **Compatibilidad entre navegadores** | Hay que tener en cuenta manualmente las diferencias entre navegadores. | React proporciona compatibilidad entre navegadores mediante `SyntheticEvent`. |
| **Vinculacion de contexto** | A menudo requiere `bind`. | En componentes de clase puede requerir `bind`; en funcionales, no. |

#### Ejemplo en HTML:

```html
Click me
```

#### Ejemplo en React:

```jsx
function handleClick() {
  alert('Clicked!');
}

function App() {
  return Click me;
}
```

#### SyntheticEvent en React:

React utiliza una envoltura sobre eventos nativos que normaliza el
comportamiento entre navegadores y mejora la coherencia.

</details>

<details>
<summary>24. Que son los eventos sinteticos en React?</summary>

#### React

Los **eventos sinteticos** en React son envolturas de los eventos nativos del
DOM que proporcionan una interfaz uniforme para manejarlos en distintos
navegadores. React crea un `SyntheticEvent` para cada evento, lo que permite
trabajar con ellos de forma estandarizada y con compatibilidad entre
navegadores.

#### Caracteristicas principales:

1. **Compatibilidad entre navegadores:** `SyntheticEvent` abstrae las
   particularidades de cada navegador y ofrece un comportamiento uniforme.

2. **Optimizacion:** historicamente, `SyntheticEvent` utilizaba pooling de
   objetos para reducir el coste de crear nuevos eventos.

3. **Uso controlado:** tras manejar el evento, conviene extraer los datos
   necesarios si van a usarse de forma asincrona.

4. **Interfaz:** `SyntheticEvent` tiene los mismos metodos que los eventos
   nativos estandar, como `preventDefault()` y `stopPropagation()`.

#### Ejemplo de uso:

```jsx
function handleClick(event) {
  // SyntheticEvent permite acceder al metodo preventDefault()
  event.preventDefault();
  console.log('Button clicked!');
}

function App() {
  return Click me;
}
```

En este ejemplo, `event` es un `SyntheticEvent` que funciona de forma similar a
un evento nativo, pero con una interfaz unificada.

</details>

<details>
<summary>25. Como se manejan los eventos en React?</summary>

#### React

En React, el manejo de eventos funciona de forma parecida a JavaScript
estandar, pero con algunas diferencias. Los eventos en React son sinteticos, es
decir, una abstraccion sobre los eventos reales del navegador que garantiza
compatibilidad entre navegadores.

#### Principios basicos del manejo de eventos en React:

1. **Eventos sinteticos:** todos los eventos en React estan envueltos en un
   objeto **SyntheticEvent**, que es una implementacion compatible entre
   navegadores de los eventos DOM estandar.

2. **Uso de camelCase:** en React los eventos se escriben en camelCase en lugar
   de minusculas, por ejemplo `onClick` en vez de `onclick`.

3. **Paso de funciones como manejadores:** los eventos se manejan mediante
   funciones que se pasan a traves de los atributos del componente.

#### Ejemplo de manejo del evento `click`:

```jsx
import React, { Component } from 'react';

class MyButton extends Component {
  handleClick = () => {
    alert('Button clicked!');
  };

  render() {
    return Click Me;
  }
}

export default MyButton;
```

#### Ejemplo con un componente funcional:

```jsx
import React, { useState } from 'react';

function MyButton() {
  const [count, setCount] = useState(0);

  const handleClick = () => {
    setCount(count + 1);
  };

  return Clicked {count} times;
}

export default MyButton;
```

#### Particularidades del manejo de eventos:

1. **No hace falta usar `addEventListener`:** en React no es necesario agregar
   ni eliminar listeners manualmente. La biblioteca lo gestiona
   automaticamente.

2. **Conservacion del contexto en componentes de clase:** si los metodos de un
   componente de clase se usan como manejadores, el contexto `this` debe
   vincularse mediante funciones flecha o manualmente en el constructor.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
    // Vinculacion del metodo
    this.handleClick = this.handleClick.bind(this);
  }

  handleClick() {
    this.setState({ count: this.state.count + 1 });
  }

  render() {
    return (

        Clicked {this.state.count} times

    );
  }
}
```

3. **Paso de parametros al manejador:** si necesitas enviar argumentos
   adicionales al manejador del evento, puedes usar funciones flecha o
   funciones con parametros.

```jsx
function MyButton({ label }) {
  const handleClick = (event, label) => {
    console.log(label);
  };

  return <button onClick={event => handleClick(event, label)}>{label};
}
```

#### Manejo de eventos en el DOM:

Todos los eventos en React funcionan segun el principio de delegacion de
eventos, donde un solo manejador central sirve para todo el arbol de
componentes y pasa a traves de `SyntheticEvent`.

</details>

<details>
<summary>26. Que son los Pointer Events?</summary>

#### React

#### Pointer Events en React

Los **Pointer Events** son una API que unifica los eventos del raton, la
pantalla tactil y el lapiz optico en un solo sistema de manejo.

#### Principales Pointer Events

| **Evento** | **Descripcion** |
| ---------- | --------------- |
| **onPointerDown** | Se dispara al presionar con el dedo, el raton o el lapiz. |
| **onPointerUp** | Se dispara al soltar el boton del raton, el dedo o el lapiz. |
| **onPointerMove** | Se ejecuta cuando el puntero se mueve sobre el elemento. |
| **onPointerEnter** | Se dispara cuando el puntero entra en los limites del elemento. |
| **onPointerLeave** | Se dispara cuando el puntero sale de los limites del elemento. |
| **onPointerCancel** | Se ejecuta cuando el navegador cancela el evento, por ejemplo al cambiar el foco. |

#### Ejemplo de uso en React

```jsx
const PointerExample = () => {
  const handlePointerDown = () => console.log('Puntero presionado');

  return (

      Haz clic aqui

  );
};
```

Este codigo mostrara `"Puntero presionado"` en la consola al pulsar con
cualquier dispositivo, ya sea raton, pantalla tactil o lapiz.

</details>

<details>
<summary>27. Cuando usar un componente de clase en lugar de uno funcional?</summary>

#### React

Los componentes de clase se usaban cuando se necesitaba una o varias de estas
funciones:

1. **Trabajo con state:** antes, los componentes funcionales no soportaban
   estado local, por lo que se usaban clases. Hoy en dia, hooks como
   `useState` y `useReducer` permiten gestionar estado en componentes
   funcionales.

2. **Metodos del ciclo de vida:** las clases daban acceso a metodos como
   `componentDidMount`, `componentDidUpdate` y `componentWillUnmount` para
   controlar el componente en distintas etapas. Hoy esto se resuelve con
   `useEffect`.

3. **Manejo de logica compleja:** si la logica necesitaba varios metodos y
   acceso a propiedades mediante `this`, las clases parecian una opcion
   natural. El enfoque moderno usa hooks para encapsular esa logica.

#### Cuando las clases ya no son necesarias:

Desde React 16.8, los componentes funcionales con hooks han sustituido en gran
medida la necesidad de componentes de clase. Por eso, en proyectos nuevos se
prefieren los componentes funcionales. Las clases suelen quedar para mantener
codigo heredado.

</details>

<details>
<summary>28. Que son los componentes sin estado (stateless components)?</summary>

#### React

Los componentes sin estado son componentes que no almacenan ni gestionan ningun
estado interno. Solo reciben datos mediante props y los muestran en la
interfaz. Normalmente son componentes funcionales.

#### Caracteristicas:

1. **Sin estado:** no usan `this.state` ni modifican su estado interno.

2. **Solo renderizado:** simplemente reciben props y las muestran como
   elementos de interfaz.

3. **Simplicidad y previsibilidad:** son mas faciles de probar y mantener,
   porque no hay cambios de estado que seguir.

#### Ejemplo:

```jsx
// Stateless component
function Greeting(props) {
  return Hello, {props.name}!;
}

// Uso:
;
```

#### Ventajas:

- **Simplicidad:** son mas faciles de entender y mantener.

- **Optimizacion del rendimiento:** al no tener estado, React puede
  actualizarlos de manera mas eficiente.

#### Cuando usarlos:

- Cuando el componente solo muestra datos y no necesita gestionar cambios.

</details>

<details>
<summary>29. Que son los componentes con estado (stateful components)?</summary>

#### React

Los **componentes con estado** son componentes que almacenan y gestionan su
estado interno. Utilizan `state` para guardar datos que pueden cambiar con el
tiempo, y esos cambios afectan al renderizado del componente.

#### Caracteristicas:

1. **State:** utilizan `this.state` para almacenar y gestionar datos que pueden
   cambiar.

2. **Metodos para actualizar el estado:** usan `this.setState()` para cambiar
   el estado.

3. **Ciclo de vida:** tienen acceso a metodos del ciclo de vida como
   `componentDidMount()`, `shouldComponentUpdate()` y `componentDidUpdate()`.

#### Ejemplo:

```jsx
// Stateful component
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      count: 0,
    };
  }

  increment = () => {
    this.setState({ count: this.state.count + 1 });
  };

  render() {
    return (

        {this.state.count}
        Increment

    );
  }
}
```

#### Ventajas:

- **Componentes dinamicos:** pueden cambiar su contenido y aspecto segun los
  cambios de estado.

- **Interactividad:** son adecuados para interfaces interactivas donde hay que
  actualizar el estado en respuesta a acciones del usuario.

#### Cuando usarlos:

Cuando el componente necesita gestionar un estado interno, por ejemplo para
guardar datos introducidos en un formulario, un contador, una seleccion, etc.

</details>

<details>
<summary>30. Que son los componentes puros (Pure Components)?</summary>

#### React

Los **componentes puros** son componentes especiales de clase en React que
optimizan automaticamente el renderizado. Realizan una comparacion superficial
de props y estado para evitar actualizaciones innecesarias si los valores no
cambiaron.

#### Como se crea un componente puro?

Un componente puro se crea heredando de `React.PureComponent`.

```jsx
import React, { PureComponent } from 'react';

class MyComponent extends PureComponent {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Uso:
;
```

#### Como funciona `PureComponent`?

- Realiza una comparacion superficial (`shallow comparison`) de las props y del
  estado en `shouldComponentUpdate`.

- Si las props y el estado no cambiaron, el componente no vuelve a renderizarse.

#### Cuando usar `PureComponent`?

- Cuando las props y el estado son estructuras simples, como valores
  primitivos u objetos poco profundos.

- Para mejorar el rendimiento en componentes que se actualizan con frecuencia.

#### Limitaciones:

1. **No hace comparacion profunda:** `PureComponent` no detecta cambios dentro
   de objetos o arrays anidados. Por ejemplo, si actualizas un objeto pero la
   referencia sigue siendo la misma, el componente no se actualizara.

```jsx
this.setState({ data: { ...this.state.data, key: 'new value' } }); // Solucion alternativa
```

2. **No funciona con componentes funcionales:** la alternativa es usar
   `React.memo` para optimizarlos.

```jsx
const MyComponent = React.memo(function MyComponent(props) {
  return Hello, {props.name}!;
});
```

</details>

<details>
<summary>31. Que son los componentes de orden superior (Higher-Order Components)?</summary>

#### React

Un **componente de orden superior** es una funcion que recibe un componente
como argumento y devuelve un nuevo componente, ampliando su funcionalidad.

#### Sintaxis de un HOC:

```jsx
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

#### Caracteristicas de un HOC:

1. **Recibe un componente como argumento.**
2. **Devuelve un nuevo componente con propiedades o comportamiento
   adicionales.**
3. **Permite reutilizar logica en distintos componentes.**

#### Ejemplo de uso:

HOC para anadir estado a un componente:

```jsx
import React, { useState } from 'react';

// HOC: anade logica de estado
function withCounter(WrappedComponent) {
  return function EnhancedComponent(props) {
    const [count, setCount] = useState(0);

    const increment = () => setCount(count + 1);

    return ;
  };
}

// Componente que sera ampliado
function Button({ count, increment }) {
  return Clicked {count} times;
}

// Uso del HOC
const EnhancedButton = withCounter(Button);

export default EnhancedButton;
```

#### Casos reales de uso de HOC:

1. **Autorizacion y autenticacion:** envolver componentes para comprobar
   permisos de acceso.

2. **Procesamiento de datos:** conexion a APIs o manejo de estado.

3. **Registro:** anadir seguimiento de acciones de los componentes.

#### Limitaciones de los HOC:

- Pueden crear anidaciones profundas en el arbol de componentes si se usan en
  exceso.

- Pueden dificultar la lectura del codigo debido a tantas envolturas.

Los HOC son una herramienta potente para reutilizar logica, pero en
aplicaciones modernas a menudo se reemplazan por React Hooks.

</details>

<details>
<summary>32. Que es la prop children?</summary>

#### React

#### Que es la prop `children`?

`children` es una prop especial de React que se usa para pasar elementos o
componentes anidados a un componente contenedor.

#### Como funciona?

Cuando colocas contenido entre la etiqueta de apertura y de cierre de un
componente, ese contenido se pasa automaticamente como `props.children`.

#### Ejemplo:

- **Componente contenedor:**

```jsx
function Wrapper({ children }) {
  return { children };
}
```

- **Uso:**

```jsx
function App() {
  return (

      Hello, World!
      This is a paragraph inside the wrapper.

  );
}
```

- **Resultado:**

```html
Hello, World! This is a paragraph inside the wrapper.
```

#### Caracteristicas clave de `children`:

1. **Flexibilidad:** se puede pasar cualquier tipo de dato, como texto, JSX,
   componentes o arrays de elementos.

2. **Reutilizacion:** el componente contenedor puede mostrar dinamicamente
   distinto contenido.

3. **Estructura:** ayuda a crear componentes con una estructura anidada.

#### Uso de `children` con props funcionales:

A veces `children` se usa como una funcion para pasar datos de forma dinamica:

```jsx
function List({ items, children }) {
  return {items.map(item => children(item))};
}

function App() {
  return (
    <List items={['Apple', 'Banana', 'Cherry']}>
      {item => {item}}

  );
}
```

#### Resultado:

```html
Apple Banana Cherry
```

`children` es una herramienta potente para crear componentes genericos y
reutilizables en React.

</details>

<details>
<summary>33. Que es un portal (Portal)?</summary>

#### React

Un **portal** en React es una forma de renderizar elementos hijos en un nodo
del DOM que se encuentra fuera de la jerarquia DOM del componente padre.

#### Como funciona:

React proporciona portales mediante el metodo `ReactDOM.createPortal`, que
recibe dos argumentos:

1. **El elemento React** que debe renderizarse.

2. **El nodo DOM de destino** donde se insertara el elemento.

#### Sintaxis:

```jsx
ReactDOM.createPortal(child, container);
```

- **`child`**: el elemento React que se debe renderizar.

- **`container`**: el nodo DOM donde se insertara el elemento.

#### Ejemplo de uso:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function Modal({ children }) {
  return ReactDOM.createPortal(
    {children},
    document.getElementById('modal-root') // Nodo de destino
  );
}

function App() {
  return (

      Contenido principal

        Este es el contenido de la ventana modal


  );
}
```

#### Donde se usan los portales:

- Ventanas modales.

- Tooltips.

- Menus contextuales.

#### Particularidades:

1. **Jerarquia de eventos:** aunque el elemento se renderiza fuera de la
   jerarquia del DOM, el manejo de eventos sigue la jerarquia de componentes de
   React. Por ejemplo, los eventos `onClick` seguiran subiendo hacia los
   componentes padre de React.

2. **Flexibilidad:** los portales permiten insertar elementos en lugares que no
   encajan en la estructura DOM actual.

#### Ventajas:

- Facilitan la gestion de elementos "flotantes".
- Conservan el contexto de React incluso fuera de la jerarquia principal del
  DOM.

</details>

<details>

<summary>34. Como funcionan los portales en React y cuales son sus ventajas y usos principales en el desarrollo de UI?</summary>

#### React

Los **portales** en React permiten renderizar elementos hijos en otra parte del
DOM en lugar del lugar habitual del componente. Esto es util para colocar
elementos que deben estar fuera de la jerarquia DOM normal, como ventanas
modales, tooltips o elementos flotantes.

#### Ventajas principales de los portales:

- Permiten renderizar elementos en otra zona del DOM sin romper la estructura
  de componentes de React.

- Son utiles cuando hay que renderizar elementos por encima de otro contenido,
  por ejemplo ventanas modales o menus emergentes.

#### Como funcionan los portales:

- Un portal permite enviar contenido a cualquier lugar del DOM, incluso fuera
  del contenedor raiz de React.

#### Ejemplo de uso de un portal:

```jsx
import ReactDOM from 'react-dom';

const Modal = () => {
  return ReactDOM.createPortal(
    <div className="modal">
      <h1>Esta es una ventana modal</h1>
    </div>,
    document.getElementById('modal-root') // Lugar del DOM donde se renderiza el portal
  );
};

const App = () => {
  return (
    <div>
      <h1>Pagina principal</h1>
      <Modal />
    </div>
  );
};
```

#### Puntos clave:

- `ReactDOM.createPortal()` se usa para crear un portal. El primer argumento es
  el contenido que se renderiza y el segundo es el elemento DOM donde se
  inserta.

- Los portales pueden usarse para ventanas modales, tooltips, menus emergentes
  y otros elementos que deben mostrarse fuera del arbol principal de
  componentes.

#### Particularidades:

- Aunque los elementos renderizados mediante portales estan fuera de la
  jerarquia principal de componentes de React, siguen teniendo acceso al
  contexto, al estado y a las props de sus componentes padre.

- Los portales son utiles cuando ciertos elementos deben situarse "por encima"
  de otro contenido o en otro nivel de la jerarquia DOM, por ejemplo una
  ventana modal que no debe quedar limitada por el contenedor padre.

Los portales permiten conservar la logica y la estructura del componente sin
romper las reglas del DOM, lo que ayuda a crear componentes de UI limpios y
comodos.

</details>

<details>
<summary>35. Cuales son los metodos del ciclo de vida de un componente en React?</summary>

#### React

Los metodos del ciclo de vida de un componente en React se usan para gestionar
las distintas etapas de su existencia: creacion, actualizacion y eliminacion.

#### Fases principales del ciclo de vida:

1. **Montaje (Mounting):** cuando el componente se agrega al DOM.

`constructor()`: inicializacion del estado y vinculacion de metodos.

`static getDerivedStateFromProps(props, state)`: actualizacion del estado antes
del render, usada rara vez.

`render()`: renderiza JSX en el DOM virtual.

`componentDidMount()`: se llama justo despues de agregar el componente al DOM.
Se usa para peticiones API o inicializacion de bibliotecas.

2. **Actualizacion (Updating):** cuando cambian las props o el estado.

`static getDerivedStateFromProps(props, state)`: se llama antes de cada render.

`shouldComponentUpdate(nextProps, nextState)`: controla si el componente debe
volver a renderizarse. Devuelve `true` por defecto.

`render()`: se ejecuta para actualizar el DOM virtual.

`getSnapshotBeforeUpdate(prevProps, prevState)`: obtiene una instantanea antes
de los cambios, por ejemplo la posicion del scroll.

`componentDidUpdate(prevProps, prevState, snapshot)`: se llama despues de la
actualizacion. Se usa para nuevas peticiones o para trabajar con el DOM.

3. **Desmontaje (Unmounting):** cuando el componente se elimina del DOM.

`componentWillUnmount()`: se usa para limpiar recursos, por ejemplo timers o
suscripciones.

4. **Manejo de errores (Error Handling):** cuando el componente provoca un
error.

`static getDerivedStateFromError(error)`: permite actualizar el estado tras un
error.

`componentDidCatch(error, info)`: registro de errores.

#### Tabla de metodos:

| Fase | Metodo | Descripcion |
| ---- | ------ | ----------- |
| **Montaje** | `constructor()` | Inicializacion del estado y configuracion. |
| | `getDerivedStateFromProps()` | Actualiza el estado antes del render. |
| | `render()` | Renderiza JSX en el DOM virtual. |
| | `componentDidMount()` | Se ejecuta despues de agregar el componente al DOM. |
| **Actualizacion** | `getDerivedStateFromProps()` | Actualiza el estado antes del render. |
| | `shouldComponentUpdate()` | Determina si hace falta volver a renderizar. |
| | `render()` | Actualiza el DOM virtual. |
| | `getSnapshotBeforeUpdate()` | Obtiene una instantanea antes de actualizar. |
| | `componentDidUpdate()` | Se ejecuta despues de la actualizacion. |
| **Desmontaje** | `componentWillUnmount()` | Limpia recursos antes de eliminar el componente. |
| **Manejo de errores** | `getDerivedStateFromError()` | Actualiza el estado cuando hay un error. |
| | `componentDidCatch()` | Registra errores. |

#### Enfoque moderno:

En los componentes funcionales, en lugar de metodos del ciclo de vida se usan
**hooks**:

- `useEffect` sustituye a `componentDidMount`, `componentDidUpdate` y
  `componentWillUnmount`.

- `useState` para gestionar el estado.

</details>

<details>
<summary>36. Que hace el metodo shouldComponentUpdate?</summary>

#### React

- `shouldComponentUpdate` es un metodo del ciclo de vida en componentes de
  clase que determina si el componente debe volver a renderizarse.

#### Como funciona:

- Por defecto devuelve `true`, lo que significa que habra rerender con cualquier
  cambio en `state` o `props`.

- Si devuelve `false`, React no volvera a renderizar el componente aunque hayan
  cambiado las props o el estado.

#### Ejemplo de uso:

```jsx
class MyComponent extends React.Component {
  shouldComponentUpdate(nextProps, nextState) {
    return nextProps.value !== this.props.value; // Rerender solo si cambia value
  }

  render() {
    return <div>{this.props.value}</div>;
  }
}
```

#### Alternativa en componentes funcionales:

- Usa `React.memo()` para memoizacion.

- `useMemo()` y `useCallback()` ayudan a optimizar los rerenders.

</details>

<details>
<summary>37. Como ejecutar codigo antes de eliminar un componente del arbol?</summary>

#### React

Para ejecutar codigo antes de eliminar un componente del arbol en React, se
utilizan estos enfoques:

1. **Componentes de clase:** `componentWillUnmount`

En componentes de clase existe el metodo del ciclo de vida
`componentWillUnmount`, que se llama antes de eliminar el componente.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('El componente sera eliminado');
  }

  render() {
    return <div>Mi componente</div>;
  }
}
```

2. **Componentes funcionales:** `useEffect` con limpieza

En componentes funcionales, la limpieza puede hacerse dentro de `useEffect`
devolviendo una funcion que se ejecutara antes de eliminar el componente.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('El componente sera eliminado');
    };
  }, []);

  return <div>Mi componente</div>;
}
```

3. **Manejo antes de cerrar la pagina (`beforeunload`)**

Si necesitas ejecutar codigo antes de cerrar la pestana o recargar la pagina:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('La pagina se esta cerrando');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Conclusion

- `componentWillUnmount` para componentes de clase.

- `useEffect` con `return` para componentes funcionales.

- `beforeunload` para los casos en que hay que reaccionar al salir de la
  pagina.

</details>

<details>
<summary>38. Por que los fragmentos son mejores que los div contenedores?</summary>

#### React

Los fragmentos (`<React.Fragment>` o `<>...</>`) son mejores que los `<div>`
contenedores en React por varias razones:

1. **Reduccion de HTML innecesario**

- Los fragmentos no anaden un elemento extra al DOM, lo que reduce la cantidad
  de etiquetas anidadas y mejora el rendimiento.

```jsx
<>
  <h1>Title</h1>
  <p>Text</p>
</>
```

- Resultado en el DOM:

```html
<h1>Title</h1>
<p>Text</p>
```

- A diferencia de un `<div>`, que anadiria una anidacion innecesaria:

```html
<div>
  <h1>Title</h1>
  <p>Text</p>
</div>
```

2. **Ausencia de efectos secundarios de estilo**

- Un `<div>` adicional puede afectar a los estilos CSS y provocar cambios no
  deseados en la maquetacion. Los fragmentos evitan eso.

3. **Mejor compatibilidad con tablas**

- Dentro de `<table>` no se puede insertar directamente un `<div>`, pero si se
  pueden usar fragmentos:

```jsx
<>
  <tr>
    <td>Row 1</td>
  </tr>
  <tr>
    <td>Row 2</td>
  </tr>
</>
```

- Esto funciona correctamente, mientras que un `<div>` provocaria un error.

4. **Optimizacion del rendimiento**

- Menos nodos innecesarios en el DOM -> renderizado mas rapido y menor consumo
  de memoria.

</details>

<details>
<summary>39. Que son los Hooks en React?</summary>

#### React

Los **Hooks de React** son funciones que te permiten usar estado y otras
capacidades de React sin escribir clases.

#### Tipos principales de hooks:

1. **useState** permite anadir estado a los componentes funcionales.

```jsx
const [state, setState] = useState(initialState);
```

2. **useEffect** permite ejecutar efectos secundarios, por ejemplo peticiones a
   APIs o suscripciones, en componentes funcionales.

```jsx
useEffect(() => {
  // codigo del efecto
}, [dependencies]); // dependencias
```

3. **useContext** da acceso a los valores del contexto sin necesidad de usar el
   componente `Consumer`.

```jsx
const value = useContext(MyContext);
```

4. **useRef** permite crear referencias a elementos del DOM o conservar valores
   entre renders sin cambiar el estado.

```jsx
const myRef = useRef(initialValue);
```

5. **useReducer** es una alternativa a `useState`, util para manejar estados
   mas complejos mediante reducers, de forma parecida a Redux.

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

6. **useMemo** optimiza el calculo de valores para evitar recomputaciones
   innecesarias.

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

7. **useCallback** devuelve una version memorizada de una funcion para que no
   se vuelva a crear en cada render.

```jsx
const memoizedCallback = useCallback(() => {
  // funcion;
}, [dependencies]);
```

#### Ventajas principales:

- **Componentes funcionales:** en lugar de componentes de clase, puedes usar
  componentes funcionales con hooks.

- **Mejor legibilidad:** la logica puede dividirse en varios hooks, lo que
  reduce la cantidad de codigo y mejora la modularidad.

- **Reutilizacion de logica:** los hooks permiten reutilizar logica en distintos
  componentes sin crear jerarquias complejas.

</details>

<details>
<summary>40. Cuales son las ventajas de los Hooks en React?</summary>

#### React

| **Ventaja** | **Descripcion** |
| ----------- | --------------- |
| **Menos codigo** | Los hooks permiten evitar las clases y reducir el volumen de codigo. |
| **Mejor legibilidad** | El codigo con hooks es mas facil de entender y mantener. |
| **Reutilizacion de logica** | Los custom hooks permiten reutilizar logica entre componentes. |
| **Gestion del estado simplificada** | El uso de `useState` y `useReducer` hace mas sencillo el manejo del estado. |
| **Flexibilidad al usar efectos** | `useEffect` permite ejecutar efectos secundarios sin necesidad de metodos de ciclo de vida de clase. |
| **Migracion mas sencilla** | Facilita la transicion de componentes de clase a componentes funcionales. |

</details>

<details>
<summary>41. Cuales son las desventajas de los Hooks en React?</summary>

#### React

| **Desventaja** | **Descripcion** |
| -------------- | --------------- |
| **Mayor numero de rerenders** | El uso incorrecto de hooks, especialmente `useEffect`, puede provocar rerenders innecesarios. |
| **Logica mas dificil de seguir** | La logica del componente puede quedar dispersa entre varios `useEffect`, lo que complica el debug. |
| **Falta de un ciclo de vida explicito** | A diferencia de los componentes de clase, los hooks no tienen metodos de ciclo de vida claramente separados. |
| **Posibles problemas de optimizacion** | El uso incorrecto de `useCallback` y `useMemo` puede llevar a un comportamiento ineficiente. |
| **Complejidad en proyectos grandes** | En aplicaciones grandes, los hooks pueden complicar la gestion del estado y de los efectos secundarios. |

</details>

<details>
<summary>42. Cuales son las reglas y restricciones para usar Hooks en React?</summary>

#### React

| **Regla** | **Descripcion** |
| --------- | --------------- |
| **Uso solo en funciones** | Los hooks solo pueden llamarse dentro de componentes funcionales o de custom hooks. |
| **Mantener el orden de llamadas** | No se pueden llamar hooks de forma condicional (`if`, `for`, `while`), porque se romperia el orden de ejecucion. |
| **Llamada solo en el nivel superior** | Los hooks no deben llamarse dentro de funciones anidadas ni manejadores de eventos. |
| **Nombre de los custom hooks** | Los custom hooks deben empezar por `use`, por ejemplo `useAuth`. |
| **Respeto de las dependencias** | En `useEffect`, `useMemo` y `useCallback`, las dependencias (`[]`) deben declararse correctamente para evitar comportamientos inesperados. |

</details>

<details>
<summary>43. Que es useReducer()?</summary>

#### React

`useReducer()` es un hook de React que se usa para gestionar el estado en
componentes funcionales. Es una alternativa a `useState()` adecuada para
logicas de actualizacion mas complejas, especialmente cuando los cambios
dependen del estado anterior.

#### Sintaxis:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer`: funcion que recibe `state` y `action` y devuelve el nuevo estado.

- `initialState`: estado inicial.

- `dispatch`: funcion para ejecutar el reducer con una `action` concreta.

#### Ejemplo:

```jsx
import { useReducer } from 'react';

const initialState = { count: 0 };

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return { count: state.count + 1 };
    case 'decrement':
      return { count: state.count - 1 };
    default:
      return state;
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);

  return (
    <div>
      <p>Count: {state.count}</p>
      <button onClick={() => dispatch({ type: 'increment' })}>+</button>
      <button onClick={() => dispatch({ type: 'decrement' })}>-</button>
    </div>
  );
}
```

#### Cuando usarlo:

- Cuando el estado tiene una logica compleja o varias dependencias.

- Cuando necesitas unificar las actualizaciones del estado mediante `dispatch`.

- Para una mejor escalabilidad, por ejemplo al usar estado global.

</details>

<details>
<summary>44. Que hacen los hooks useCallback(), useMemo(), useImperativeHandle() y useLayoutEffect()?</summary>

#### React

#### `useCallback()`

Memoriza una funcion para que no se vuelva a crear en cada render. Es util para
pasar callbacks a componentes hijos.

- **Ejemplo:**

```jsx
import { useCallback } from 'react';

function MyComponent({ onClick }) {
  return <button onClick={onClick}>Haz clic</button>;
}

function Parent() {
  const handleClick = useCallback(() => {
    console.log('Clic');
  }, []); // La funcion se crea una sola vez

  return <MyComponent onClick={handleClick} />;
}
```

#### `useMemo()`

Memoriza un calculo para no repetirlo en cada render si las dependencias no han
cambiado.

#### Ejemplo:

```jsx
import { useMemo } from "react";

function ExpensiveCalculation({ num }) {
const result = useMemo(() => {
console.log("Calculando...");
return num \* 2;
}, [num]); // Solo se ejecuta si cambia num

return <div>Resultado: {result}</div>;
}
```

#### `useImperativeHandle()`

Permite controlar el comportamiento de una ref en un componente hijo. Se usa
junto con `forwardRef()`.

#### Ejemplo:

```jsx
import { useRef, useImperativeHandle, forwardRef } from 'react';

const CustomInput = forwardRef((props, ref) => {
  const inputRef = useRef();

  useImperativeHandle(ref, () => ({
    focus: () => inputRef.current.focus(),
    clear: () => (inputRef.current.value = ''),
  }));

  return <input ref={inputRef} {...props} />;
});

function Parent() {
  const inputRef = useRef();

  return (
    <div>
      <CustomInput ref={inputRef} />
      <button onClick={() => inputRef.current.focus()}>Enfocar</button>
      <button onClick={() => inputRef.current.clear()}>Limpiar</button>
    </div>
  );
}
```

#### `useLayoutEffect()`

Funciona como `useEffect()`, pero se ejecuta de forma sincronica despues de los
cambios en el DOM. Es util para medir o manipular el DOM antes de que el
navegador pinte la pagina.

- **Ejemplo:**

```jsx
import { useLayoutEffect, useRef } from 'react';

function LayoutEffectExample() {
  const divRef = useRef();

  useLayoutEffect(() => {
    console.log('Ancho del elemento:', divRef.current.offsetWidth);
  }, []);

  return (
    <div ref={divRef} style={{ width: '200px', height: '100px' }}>
      Elemento
    </div>
  );
}
```

#### Cuando usar cada hook?

- `useCallback()` para memorizar funciones.

- `useMemo()` para memorizar calculos.

- `useImperativeHandle()` para controlar la ref de un componente hijo.

- `useLayoutEffect()` cuando hace falta hacer algo antes de que se muestren los
  cambios en el DOM, por ejemplo una medicion.

</details>

<details>
<summary>45. Como ejecutar una operacion una sola vez durante el render inicial?</summary>

#### React

Para ejecutar una operacion solo una vez durante el render inicial en un
componente funcional, usa `useEffect` con un array de dependencias vacio
(`[]`):

#### Ejemplo:

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    console.log('Esto se ejecutara solo una vez despues del montaje del componente');
  }, []);

  return <div>Componente</div>;
}
```

#### Explicacion:

- `useEffect(() => { /* codigo */ }, [])`: un array de dependencias vacio
  significa que el efecto se ejecutara solo una vez despues del primer render,
  de manera similar a `componentDidMount` en componentes de clase.

#### Adicionalmente, por ejemplo para suscripcion y limpieza:

```jsx
useEffect(() => {
  const interval = setInterval(() => {
    console.log('Se esta ejecutando un efecto de una sola vez');
  }, 1000);

  return () => clearInterval(interval); // Limpieza al desmontar
}, []);
```

Este enfoque es util para inicializar peticiones API, suscripciones, timers y
cosas similares.

</details>

<details>
<summary>46. Que es el contexto (Context)?</summary>

#### React

El **contexto** en React es un mecanismo para transmitir datos a traves del
arbol de componentes sin necesidad de pasarlos mediante props en cada nivel.

#### Como funciona el contexto:

1. **React.createContext()** se usa para crear un contexto.

```jsx
const MyContext = React.createContext(defaultValue);
```

2. **Provider** es el componente que proporciona el valor del contexto.
   Envuelve parte del arbol de componentes y transmite el valor hacia abajo a
   traves de `value`.

```jsx
<MyContext.Provider value={}>
  <YourComponent />
</MyContext.Provider>
```

3. **Consumer** es el componente que consume el valor del contexto. Suele usar
   una funcion como hijo que recibe ese valor.

```jsx
<MyContext.Consumer>
{value => }
</MyContext.Consumer>
```

4. **useContext** es un hook que permite acceder al valor del contexto sin usar
   `Consumer`.

```jsx
const value = useContext(MyContext);
```

#### Cuando usarlo:

- Cuando necesitas transmitir datos entre componentes situados en distintos
  niveles de la jerarquia, por ejemplo tema, idioma o usuario.

- Cuando no quieres pasar props por varios niveles de componentes, lo cual
  puede complicar el codigo.

#### Ejemplo de uso:

```jsx
// Creacion del contexto
const ThemeContext = React.createContext('light');

// Componente que proporciona el valor del contexto
function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedComponent />
    </ThemeContext.Provider>
  );
}

// Componente que consume el valor del contexto
function ThemedComponent() {
  const theme = useContext(ThemeContext);
  return <div>The current theme is {theme}</div>;
}
```

#### Ventajas:

- Comodidad al transmitir valores globales.

- Mejora la escalabilidad de la aplicacion al reducir la cantidad de props que
  deben pasarse.

</details>

<details>
<summary>47. Como funciona el mecanismo Context en React para compartir datos entre componentes?</summary>

#### React

El mecanismo **React Context** permite pasar datos entre componentes sin tener
que transmitirlos mediante props en cada nivel. Esto es util para datos
globales como la configuracion del tema, la autenticacion del usuario o el
idioma.

#### Pasos principales para trabajar con contexto:

1. **Creacion del contexto:** para crear un contexto se usa
   `React.createContext()`. Esto devuelve dos componentes:

- `Provider`, el componente que transmite el valor del contexto.

- `Consumer`, el componente que recibe el valor del contexto.

```jsx
const MyContext = React.createContext();
```

2. **Proporcionar el contexto:** usamos `Provider` para envolver los
   componentes que deben recibir el contexto. El valor se pasa mediante la prop
   `value`.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <Child />
    </MyContext.Provider>
  );
};
```

3. **Obtener el contexto:** se usa `Consumer` o el hook `useContext` para
   acceder al valor.

- **Consumer:**

```jsx
const Child = () => (
  <MyContext.Consumer>{user => <div>{user}</div>}</MyContext.Consumer>
);
```

- **Hook `useContext`, recomendado en componentes funcionales:**

```jsx
const Child = () => {
  const user = useContext(MyContext);
  return <div>{user}</div>;
};
```

- **Cambio del contexto:** para cambiar su valor pueden usarse funciones
  provenientes de `useState` u otros metodos de gestion del estado.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <button onClick={() => setUser('Jane Doe')}>Cambiar usuario</button>
      <Child />
    </MyContext.Provider>
  );
};
```

#### Puntos clave:

- El contexto permite evitar el `prop drilling`, es decir, pasar props a traves
  de muchos componentes.

- Si cambia el valor del contexto, todos los componentes que lo consumen se
  volveran a renderizar.

- **useContext** es una forma mas comoda y moderna de obtener el valor del
  contexto que `Consumer`.

El contexto es una herramienta potente, pero conviene usarla solo para datos
globales. Para estado local, es mejor utilizar el state normal.

</details>

<details>
<summary>48. Que es el prop drilling y como evitarlo?</summary>

#### React

El **prop drilling** consiste en pasar props a traves de varios niveles de
componentes anidados, aunque solo las necesite un componente mas profundo en la
jerarquia. Esto complica el mantenimiento del codigo y lo hace menos legible.

#### Ejemplo de prop drilling:

```jsx
const Parent = () => {
  const user = { name: 'John' };
  return <Child user={user} />;
};

const Child = ({ user }) => {
  return <GrandChild user={user} />;
};

const GrandChild = ({ user }) => {
  return <p>Nombre: {user.name}</p>;
};
```

Aqui `user` se pasa a traves de `Child`, aunque ese componente no lo necesita.
Eso es precisamente **prop drilling**.

#### Como evitar el prop drilling?

| **Metodo** | **Descripcion** |
| ---------- | --------------- |
| **Context API** | Permite pasar datos directamente a los componentes que los necesitan. |
| **Estados externos (Redux, Zustand, Jotai, Recoil)** | Se usan para gestionar estado global sin pasar props manualmente. |
| **Render Props** | Permiten pasar funciones en lugar de props tradicionales. |
| **Custom Hooks** | Extraen la logica en funciones separadas para acceder a datos compartidos. |

#### Ejemplo de uso de Context API en lugar de prop drilling

```jsx
import { createContext, useContext } from 'react';

const UserContext = createContext();

const Parent = () => {
  const user = { name: 'John' };
  return (
    <UserContext.Provider value={user}>
      <GrandChild />
    </UserContext.Provider>
  );
};

const GrandChild = () => {
  const user = useContext(UserContext);
  return <p>Nombre: {user.name}</p>;
};
```

Aqui `user` esta disponible directamente en `GrandChild`, sin pasar
innecesariamente por `Child`.

</details>

<details>
<summary>49. Que es Redux?</summary>

#### React

**Redux** es una biblioteca para gestionar el estado en aplicaciones
JavaScript, especialmente popular en React. Se basa en la idea de un almacen
global (`store`) donde se guarda todo el estado de la aplicacion y permite
gestionarlo mediante cambios predecibles.

#### Principios basicos de Redux:

1. **Una unica fuente de verdad:** todo el estado se guarda en un solo `store`
   global, lo que facilita seguir los cambios.
2. **El estado es de solo lectura:** no se puede modificar directamente, solo a
   traves de una `action`.
3. **Los cambios se hacen mediante funciones puras:** el estado cambia por medio
   de reducers, que reciben el estado actual y una `action` y devuelven un
   nuevo estado.

#### Elementos principales de Redux:

- **Store:** almacen unico del estado.
- **Actions:** objetos que describen la intencion de cambiar el estado.
- **Reducers:** funciones puras que definen como cambia el estado.
- **Dispatch:** metodo para enviar una `action`.
- **Selectors:** funciones para obtener los datos necesarios desde el `store`.

Redux es adecuado para aplicaciones grandes con flujos de datos complejos, pero
en proyectos sencillos suele ser excesivo.

</details>

<details>
<summary>50. Que otras bibliotecas de gestion de estado en React conoces aparte de Redux?</summary>

#### React

Ademas de Redux, existen muchas bibliotecas para gestionar el estado en React:

1. **React Context API** es un mecanismo integrado de React para compartir
   estado sin prop drilling. Va bien para aplicaciones pequenas y medianas.

2. **Zustand** es mas simple y ligero que Redux, no requiere reducers ni
   actions. Usa un enfoque imperativo y funciona con hooks.

3. **Recoil** es una biblioteca de Facebook que trabaja con atomos y selectores,
   permitiendo crear un sistema flexible de estado global.

4. **Jotai** es parecida a Recoil, pero mas simple. Usa atomos para almacenar
   el estado y permite gestionarlo de forma declarativa.

5. **MobX** ofrece un enfoque reactivo para la gestion del estado y funciona
   mediante observables. Es comodo para trabajar con objetos y estructuras
   complejas.

6. **Effector** es mas declarativo y a menudo mas eficiente que Redux. Esta
   construido sobre un enfoque reactivo y facilita la gestion de los flujos de
   datos.

7. **XState** es una biblioteca para trabajar con maquinas de estado, muy
   adecuada para logica de negocio compleja.

Cada una tiene sus propias ventajas, y la eleccion depende de la complejidad
del proyecto y de los requisitos de rendimiento.

</details>

<details>
<summary>51. Que es Redux Thunk?</summary>

#### React

**Redux Thunk** es un middleware para Redux que permite ejecutar operaciones
asincronas (por ejemplo, solicitudes a una API) antes de enviar cambios al
`store`.

#### Como funciona:

Por defecto, Redux solo permite pasar objetos (actions) a `dispatch`. Redux
Thunk amplia esta capacidad y permite pasar funciones. Esto hace posible:

1. Ejecutar acciones asincronas antes de cambiar el estado.

2. Obtener acceso a `dispatch` y `getState` dentro del `thunk`.

#### Ejemplo de uso:

```jsx
const fetchData = () => {
  return async dispatch => {
    dispatch({ type: 'FETCH_START' });

    try {
      const response = await fetch('https://api.example.com/data');
      const data = await response.json();
      dispatch({ type: 'FETCH_SUCCESS', payload: data });
    } catch (error) {
      dispatch({ type: 'FETCH_ERROR', error });
    }
  };
};
```

Despues llamamos a este `thunk`:

```jsx
dispatch(fetchData());
```

#### Cuando usarlo:

- Para solicitudes a API.
- Para retrasos o logica compleja antes de actualizar el store.
- Cuando necesitas ejecutar varios `dispatch` dentro de una sola accion.

Si la aplicacion tiene una logica asincrona compleja, conviene considerar
**Redux Saga** o **RTK Query** como alternativas.

</details>

<details>
<summary>52. Como funciona Redux Saga?</summary>

#### React

**Redux Saga** es un middleware para Redux que utiliza generadores
(`function*`) para gestionar solicitudes asincronas en la aplicacion.

#### Como funciona:

1. **Escucha acciones** (`takeEvery`, `takeLatest`) y reacciona a ellas.

2. **Ejecuta efectos secundarios** (solicitudes a API, temporizadores, etc.).

3. **Despacha nuevas acciones** (`put`) al store.

#### Ejemplo:

1. **Saga para obtener datos desde una API:**

```jsx
import { call, put, takeEvery } from 'redux-saga/effects';

function* fetchData() {
  try {
    const response = yield call(fetch, 'https://api.example.com/data');
    const data = yield response.json();
    yield put({ type: 'FETCH_SUCCESS', payload: data });
  } catch (error) {
    yield put({ type: 'FETCH_ERROR', error });
  }
}
```

2. **Escucha de acciones:**

```jsx
function* watchFetchData() {
  yield takeEvery('FETCH_REQUEST', fetchData);
}
```

3. **Ejecucion de la saga en el `store`:**

```jsx
import createSagaMiddleware from 'redux-saga';
const sagaMiddleware = createSagaMiddleware();
const store = createStore(reducer, applyMiddleware(sagaMiddleware));
sagaMiddleware.run(watchFetchData);
```

#### Ventajas de Redux Saga:

- Gestiona logica asincrona compleja.
- Manejo integrado de cancelaciones (`takeLatest`).
- Operadores potentes (`call`, `put`, `select`, `delay`).

**Redux Thunk** es mas simple, pero para escenarios complejos **Saga** suele
ser una mejor opcion.

</details>

<details>
<summary>53. Que es React Fiber?</summary>

#### React

**React Fiber** es la nueva arquitectura de renderizado en React, introducida a
partir de la version 16. Fue diseñada para mejorar el rendimiento, admitir el
renderizado asincrono y ofrecer una gestion mas flexible de las actualizaciones
de la interfaz.

#### Caracteristicas clave de React Fiber:

1. **Mejor rendimiento:** Fiber permite a React conservar el estado de
   ejecucion del render, lo que hace posible interrumpir y reanudar el
   renderizado cuando sea necesario. Esto es importante en aplicaciones grandes,
   donde los calculos complejos pueden ralentizar el renderizado.

2. **Renderizado asincrono:** React Fiber admite renderizado asincrono, lo que
   permite renderizar por partes y mejora la capacidad de respuesta de la
   aplicacion, especialmente en interfaces complejas. Gracias a esto, el
   renderizado puede realizarse sin bloquear el hilo principal.

3. **Prioridad de actualizaciones:** Fiber permite dar prioridad a distintos
   tipos de actualizaciones (por ejemplo, el renderizado de animaciones puede
   tener alta prioridad, mientras que los cambios de estado pueden tener baja
   prioridad). Esto permite a React gestionar actualizaciones complejas de forma
   mas eficiente.

4. **Division del renderizado en subtareas:** En versiones anteriores de React,
   todos los cambios se procesaban en un solo paso. Fiber divide el renderizado
   en subtareas mas pequenas, lo que permite a React trabajar por etapas y
   atender otras operaciones importantes (por ejemplo, el manejo de eventos)
   entre una etapa y otra.

5. **Mejor soporte para animaciones y transiciones:** Gracias al renderizado
   asincrono, React puede gestionar mejor las animaciones, haciendo que las
   transiciones entre estados sean fluidas y sin retrasos.

#### Como funciona React Fiber?

En versiones antiguas de React, todo el proceso de renderizado era sincronico:
de principio a fin. Eso significaba que los calculos pesados bloqueaban el
renderizado de la interfaz. En React Fiber, el renderizado se divide en tareas
pequenas que pueden ejecutarse de forma asincrona. Si es necesario, React puede
interrumpir una tarea y continuarla mas tarde, sin bloquear otras operaciones
(como actualizaciones de la interfaz o manejo de eventos).

#### Fiber permite a React:

- Distribuir la ejecucion del renderizado para mejorar el rendimiento.

- Implementar actualizaciones asincronas de la interfaz.

- Gestionar mejor las prioridades y el procesamiento de calculos pesados, lo
  cual es especialmente importante en interfaces y aplicaciones complejas.

#### Ventajas:

- Mejora la capacidad de respuesta de las aplicaciones.

- Permite procesar operaciones pesadas sin retrasos visibles para el usuario.

- Mejor gestion de animaciones y transiciones.

**React Fiber** es una actualizacion interna que cambio la forma en que React
trabaja con el renderizado, mejorando el rendimiento general de las
aplicaciones.

</details>

<details>
<summary>54. Que es Lifting State Up en React?</summary>

#### React

**Lifting State Up** es un enfoque en React en el que el estado (`state`) se
eleva hasta el ancestro comun mas cercano de los componentes que necesitan
compartir ese estado. Esto permite establecer una unica fuente de verdad para
gestionar los datos entre componentes.

#### Idea principal:

1. **Los componentes que necesitan compartir datos no deberian tener cada uno
   su propio estado por separado.**

2. **El estado se eleva al componente padre, que transmite los datos a los
   componentes hijos mediante props.**

#### Como funciona:

1. **El componente padre almacena el estado.**
2. **Transmite el estado y las funciones para actualizarlo a sus componentes
   hijos mediante `props`.**

3. **Los componentes hijos notifican al padre sobre los cambios utilizando las
   funciones recibidas.**

#### Ejemplo:

```jsx
import React, { useState } from 'react';

function TemperatureInput({ temperature, onTemperatureChange }) {
  return (
    <fieldset>
      <legend>Enter temperature in Celsius:</legend>
      <input
        type="number"
        value={temperature}
        onChange={e => onTemperatureChange(e.target.value)}
      />
    </fieldset>
  );
}

function BoilingVerdict({ celsius }) {
  return celsius >= 100 ? (
    <p>The water will boil.</p>
  ) : (
    <p>The water won't boil.</p>
  );
}

function Calculator() {
  const [temperature, setTemperature] = useState('');

  return (
    <div>
      <TemperatureInput
        temperature={temperature}
        onTemperatureChange={setTemperature}
      />
      <BoilingVerdict celsius={parseFloat(temperature)} />
    </div>
  );
}

export default Calculator;
```

#### Ventajas:

1. **Proporciona una unica fuente de verdad para el estado.**

2. **Facilita la sincronizacion de datos entre componentes.**

3. **Hace que los componentes sean mas predecibles y reutilizables.**

</details>

<details>
<summary>55. Que son los componentes controlados (Controlled Components)?</summary>

#### React

#### Componentes controlados (Controlled Components) en React

Los componentes controlados son componentes en los que **React controla el
estado del formulario** mediante `state`. Los valores de los campos del
formulario (por ejemplo, `<input>`, `<textarea>`, `<select>`) se vinculan al
estado del componente, y los cambios se procesan mediante eventos.

#### Como funciona:

1. **El componente almacena el valor del formulario en su `state`.**

2. **Los cambios en los campos del formulario se procesan mediante el evento
   `onChange`.**

3. **El valor del formulario se actualiza usando `setState`.**

#### Ejemplo:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [inputValue, setInputValue] = useState('');

  const handleChange = event => {
    setInputValue(event.target.value); // Actualizamos el estado
  };

  const handleSubmit = event => {
    event.preventDefault();
    console.log('Submitted value:', inputValue);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Enter text:
        <input
          type="text"
          value={inputValue} // El valor es controlado por el state
          onChange={handleChange} // Manejo de cambios
        />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Ventajas principales:

1. **Una sola fuente de verdad:** El valor del formulario esta sincronizado con
   el estado del componente.

2. **Flexibilidad:** Es facil validar y modificar los datos del formulario.

3. **Transparencia:** El estado del formulario es claro y predecible.

#### Diferencias con los componentes no controlados:

- En los componentes controlados, React gestiona el valor del formulario
  mediante `state`.

- En los componentes no controlados, el valor se almacena en el propio DOM y se
  accede a el mediante `ref`.

#### Ejemplo no controlado para comparar:

```jsx
function UncontrolledForm() {
  const inputRef = React.useRef();

  const handleSubmit = event => {
    event.preventDefault();
    console.log('Submitted value:', inputRef.current.value);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Enter text:
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}
```

Los componentes controlados ofrecen mayor control y previsibilidad al trabajar
con formularios.

</details>

<details>
<summary>56. Que son los componentes no controlados (Uncontrolled Components)?</summary>

#### React

#### Componentes no controlados en React

Los componentes no controlados (Uncontrolled Components) son componentes que
almacenan su estado en el DOM, y no en el estado interno del componente de
React. El acceso a los valores de estos componentes se realiza mediante
**refs**.

#### Caracteristicas principales:

1. **El estado lo gestiona el DOM:** los valores de los campos se almacenan y
   actualizan directamente en el DOM.

2. **Menor integracion con React:** no utilizan `useState` ni otras
   herramientas de React para almacenar el estado.

3. **Uso de refs:** se utiliza un `ref` para acceder al valor de los campos del
   formulario.

#### Ejemplo de componente no controlado:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const inputRef = useRef(null);

  const handleSubmit = event => {
    event.preventDefault();
    alert(`Valor introducido: ${inputRef.current.value}`);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Nombre:
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Enviar</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### Cuando usar componentes no controlados:

- Si se necesita una integracion minima de React con el DOM.

- Si los valores del formulario son procesados por bibliotecas de terceros.

- Si se necesita un formulario sencillo sin logica compleja.

#### Ventajas:

- Simplicidad de implementacion para formularios sencillos.

- Menos codigo para gestionar el estado.

#### Desventajas:

- Menor control sobre los valores.

- Es mas dificil implementar validacion o sincronizacion de datos.

- Es un enfoque menos orientado a React.

</details>

<details>
<summary>57. Como crear un formulario en React?</summary>

#### React

#### Creacion de un formulario en React

Los formularios en React se crean usando el elemento `<form>` y controles
relacionados, como `<input>`, `<textarea>` y `<select>`. La reactividad del
formulario se logra con componentes controlados o no controlados.

#### Formulario controlado (Controlled Component)

Los componentes controlados utilizan el estado (`state`) para seguir el valor
de los campos del formulario.

#### Ejemplo:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [name, setName] = useState('');
  const [email, setEmail] = useState('');

  const handleSubmit = e => {
    e.preventDefault();
    console.log('Submitted:', { name, email });
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input
          type="text"
          value={name}
          onChange={e => setName(e.target.value)}
        />
      </label>
      <br />
      <label>
        Email:
        <input
          type="email"
          value={email}
          onChange={e => setEmail(e.target.value)}
        />
      </label>
      <br />
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Caracteristicas:

- Cada campo se controla mediante `state`.

- Es facil sincronizar y procesar los datos del formulario.

#### Formulario no controlado (Uncontrolled Component)

Los componentes no controlados usan un `ref` para acceder directamente a los
elementos del DOM.

#### Ejemplo:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const nameRef = useRef();
  const emailRef = useRef();

  const handleSubmit = e => {
    e.preventDefault();
    console.log('Submitted:', {
      name: nameRef.current.value,
      email: emailRef.current.value,
    });
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input type="text" ref={nameRef} />
      </label>
      <br />
      <label>
        Email:
        <input type="email" ref={emailRef} />
      </label>
      <br />
      <button type="submit">Submit</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### Caracteristicas:

- El acceso a los valores se realiza mediante `ref`.

- Es adecuado para formularios sencillos.

#### Puntos principales:

1. **Formulario controlado:**

- Usa `state`.

- Es mas adecuado para formularios complejos que requieren validacion o
  sincronizacion.

2. **Formulario no controlado:**

- Usa `ref`.

- Es un enfoque simple sin logica compleja de gestion del estado.

La eleccion del enfoque depende de la complejidad del formulario y de las
necesidades de interaccion con sus campos.

</details>

<details>
<summary>58. Como aplicar la validacion de props en React?</summary>

#### React

Para validar props en React se utiliza **PropTypes**.

1. **Instalacion de PropTypes (si aun no esta instalado)**

```sh
npm install prop-types
```

2. **Uso de PropTypes en un componente funcional:**

```jsx
import React from 'react';
import PropTypes from 'prop-types';

function UserCard({ name, age, isAdmin }) {
  return (
    <div>
      <h2>{name}</h2>
      <p>Age: {age}</p>
      {isAdmin && <p>Admin Access</p>}
    </div>
  );
}

// Definicion de PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Valores por defecto
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

3. **Uso en un componente de clase:**

```jsx
import React from 'react';
import PropTypes from 'prop-types';

class UserCard extends React.Component {
  render() {
    const { name, age, isAdmin } = this.props;
    return (
      <div>
        <h2>{name}</h2>
        <p>Age: {age}</p>
        {isAdmin && <p>Admin Access</p>}
      </div>
    );
  }
}

// Definicion de PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Valores por defecto
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

#### Tipos de PropTypes disponibles:

- `PropTypes.string`
- `PropTypes.number`
- `PropTypes.bool`
- `PropTypes.array`
- `PropTypes.object`
- `PropTypes.func`
- `PropTypes.node` (JSX o texto)
- `PropTypes.element` (elemento de React)
- `PropTypes.oneOf(['value1', 'value2'])` (lista de valores permitidos)
- `PropTypes.shape({ key: PropTypes.type })` (objeto con una estructura
  especifica)

#### Conclusion:

PropTypes ayuda a evitar errores al verificar los tipos de las props, aunque en
TypeScript esto se resuelve a nivel del propio lenguaje.

</details>

<details>
<summary>59. En que se diferencia React Router del enrutamiento tradicional?</summary>

#### React

#### Diferencia entre React Router y el enrutamiento tradicional:

| Criterio                   | React Router                                   | Enrutamiento tradicional (Server-Side Routing)     |
| -------------------------- | ---------------------------------------------- | -------------------------------------------------- |
| **Tipo de enrutamiento**   | Del lado del cliente (SPA)                     | Del lado del servidor (MPA)                        |
| **Cambio entre paginas**   | Sin recargar la pagina (JS actualiza la URL)   | Recarga la pagina en cada navegacion               |
| **Velocidad**              | Mas rapido, porque no vuelve a consultar al servidor | Mas lento debido a nuevas solicitudes HTTP   |
| **SEO**                    | Peor sin SSR (pero Next.js resuelve esto)      | Mejor, porque el contenido llega desde el servidor |
| **Procesamiento de datos** | Renderizado dinamico de componentes            | Carga de HTML desde el servidor                    |
| **Configuracion**          | Requiere React Router                          | Usa capacidades estandar del servidor              |

</details>

<details>
<summary>60. Como pasar props en React Router?</summary>

#### React

Para pasar props a componentes al usar **React Router**, existen varios
enfoques:

1. **Usar el componente Route para pasar props:** Se pueden pasar props a
   traves del componente `Route` usando `render` o `children`.

**Ejemplo:**

```jsx
import { Route } from 'react-router-dom';

<Route path="/profile" render={props => <Profile {...props} user="John" />} />;
```

Aqui pasamos props adicionales al componente `Profile`.

2. **Usar `useNavigate()` para pasar datos durante la navegacion (mediante
   `state`):** Al navegar a una nueva pagina, se pueden pasar datos a traves de
   `state`.

**Ejemplo:**

```jsx
import { useNavigate } from 'react-router-dom';

function Home() {
  const navigate = useNavigate();

  function goToProfile() {
    navigate('/profile', { state: { user: 'John' } });
  }

  return <button onClick={goToProfile}>Go to Profile</button>;
}
```

**Recepcion de props en el componente:**

```jsx
import { useLocation } from 'react-router-dom';

function Profile() {
  const location = useLocation();
  const user = location.state?.user;

  return <div>Welcome, {user}</div>;
}
```

3. **Usar `useParams()` para acceder a los parametros de la ruta:** Si se
   necesitan pasar parametros a traves de la URL, se puede usar `useParams()`.

**Ejemplo:**

```jsx
import { useParams } from 'react-router-dom';

function Profile() {
  const { id } = useParams();

  return <div>User ID: {id}</div>;
}
```

#### Conclusion:

- `render` o `children` son adecuados para pasar props directamente.

- `useNavigate()` y `state` permiten pasar datos entre paginas.

- `useParams()` es util para parametros dinamicos en la URL.

</details>

<details>
<summary>61. Formas de aplicar estilos en componentes de React?</summary>

#### React

#### Formas de usar estilos en componentes de React:

1. **Estilos inline** Los estilos se pasan directamente en forma de objeto
   mediante el atributo `style`.

```jsx
function InlineStyle() {
  const style = {
    color: 'blue',
    fontSize: '20px',
  };

  return <h1 style={style}>Hola, React!</h1>;
}
```

2. **Archivos CSS** Uso de archivos CSS normales importados en el componente.

```jsx
import './styles.css';

function CSSFile() {
  return <h1 className="heading">Hola, React!</h1>;
}
```

```css
/* styles.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

3. **CSS Modules** Crean estilos localmente aislados para cada componente.

```jsx
import styles from './styles.module.css';

function CSSModule() {
  return <h1 className={styles.heading}>Hola, React!</h1>;
}
```

```css
/* styles.module.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

4. **Styled Components** Uso de la biblioteca `styled-components` para escribir
   estilos en JavaScript.

```bash
npm install styled-components
```

```jsx
import styled from 'styled-components';

const Heading = styled.h1`
  color: blue;
  font-size: 20px;
`;

function StyledComponent() {
  return <Heading>Hola, React!</Heading>;
}
```

5. **Emotion** Biblioteca alternativa de estilos, similar a
   `styled-components`.

```bash
npm install @emotion/react @emotion/styled
```

```jsx
/**_ @jsxImportSource @emotion/react */
import { css } from '@emotion/react';

const style = css`
  color: blue;
  font-size: 20px;
`;

function EmotionStyle() {
  return <h1 css={style}>Hola, React!</h1>;
}
```

6. **CSS-in-JS** Creacion de estilos dinamicos en archivos JavaScript comunes.

```jsx
function CSSInJS({ isBlue }) {
  const style = {
    color: isBlue ? 'blue' : 'red',
    fontSize: '20px',
  };

  return <h1 style={style}>Hola, React!</h1>;
}
```

7. **Tailwind CSS** Framework de clases utilitarias para estilizar componentes.

```jsx
function TailwindExample() {
  return <h1 className="text-blue-500 text-2xl">Hola, React!</h1>;
}
```

**Configuracion de Tailwind CSS:** agrega las dependencias y ajusta la
configuracion.

8. **Sass/SCSS** CSS ampliado con soporte para variables, mixins y anidacion.

```bash
npm install sass
```

```jsx
import './styles.scss';

function SCSSExample() {
  return <h1 className="heading">Hola, React!</h1>;
}
```

```scss
/* styles.scss */
.heading {
  color: blue;
  font-size: 20px;
}
```

#### La eleccion del metodo depende de:

- La escala del proyecto.

- La necesidad de aislamiento de estilos.

- Las preferencias del equipo.

</details>

<details>
<summary>62. Cual es la ventaja de los estilos modulares (CSS Modules)?</summary>

#### React

**Ventajas de los estilos modulares (CSS Modules):**

1. **Scope local**: los estilos se aplican solo al componente y no de forma
   global. Esto evita conflictos entre clases y garantiza que los estilos no
   afecten otras partes de la aplicacion.

2. **Nombres de clase unicos**: CSS Modules genera automaticamente nombres de
   clase unicos, lo que elimina el riesgo de sobrescribir estilos de otros
   componentes.

3. **Mantenimiento mas sencillo**: hay menos problemas al escalar el proyecto,
   porque cada componente tiene sus propios estilos, lo que hace que el codigo
   sea mas organizado y facil de entender.

4. **Aislamiento**: cada componente tiene aislamiento total de estilos, lo que
   facilita el refactor y los cambios sin afectar otros componentes.

5. **Integracion mas facil con JavaScript**: puedes usar estilos dinamicos con
   JavaScript, cambiando clases segun el estado del componente.

Esto ayuda a mantener el orden en aplicaciones grandes y reduce la probabilidad
de errores en los estilos.

</details>

<details>
<summary>63. Que enfoques conoces para optimizar el rendimiento de aplicaciones React?</summary>

#### React

#### Enfoques para optimizar el rendimiento de aplicaciones React:

1. **Memoizacion de componentes:**

- Usa `React.memo` para memorizar componentes funcionales que no dependen de
  actualizaciones frecuentes de props.
- Usa `PureComponent` para componentes de clase.

2. **Memoizacion de valores y funciones:**

- `useMemo`: para calcular valores que dependen de ciertas dependencias.
- `useCallback`: para memorizar funciones que se pasan a componentes hijos.

3. **Optimizacion del renderizado de listas:**

Usa siempre una `key` unica para los elementos de las listas. Evita renderizados
innecesarios de componentes.

4. **Carga dinamica de componentes:**

- Usa `React.lazy` para cargar componentes bajo demanda.
- En combinacion con `Suspense`, esto permite optimizar la carga de la
  aplicacion.

5. **Control del rerenderizado:**

- Usa `shouldComponentUpdate` o `React.memo` para reducir renderizados
  innecesarios.
- Usa `React.Fragment` en lugar de elementos contenedores extra.

6. **Division de codigo (Code Splitting):**

- Implementa `React.lazy` e importaciones dinamicas para cargar el codigo de los
  modulos solo cuando sea necesario.

7. **Gestion del estado:**

- Evita almacenar estado global para componentes que no lo necesitan.
- Lleva las operaciones complejas de estado a contexto o a bibliotecas
  especializadas como Redux o Zustand.

8. **Virtualizacion de listas:**

- Usa bibliotecas como `react-window` o `react-virtualized` para renderizar solo
  los elementos visibles de las listas.

9. **Optimizacion de imagenes:**

- Usa carga diferida (`lazy loading`) para imagenes.
- Comprime y optimiza las imagenes antes de usarlas.

10. **Reducir la cantidad de componentes en el DOM:**

- Evita el anidamiento excesivo de componentes.
- Elimina elementos innecesarios del DOM al cambiar entre paginas.

11. **Cacheo de datos:**

- Usa bibliotecas de cache como `SWR` o `React Query` para gestionar datos y
  reducir solicitudes al servidor.

12. **Uso de build de produccion:**

- Asegurate de que la aplicacion se construya en modo produccion
  (`npm run build`).
- Usa herramientas como `Webpack` para minificar y optimizar el codigo.

13. **Profiling de la aplicacion:**

- Usa `React DevTools` para analizar el rendimiento.
- Detecta cuellos de botella con la pestaña `Profiler`.

14. **Optimizacion de CSS y estilos:**

- Usa soluciones `CSS-in-JS` (por ejemplo, `styled-components`) solo donde sea
  necesario.
- Comprime los estilos con `PostCSS` u otras herramientas.

Estos enfoques ayudan a reducir retrasos, mejorar la velocidad de renderizado y
elevar el rendimiento general de la aplicacion.

</details>

<details>
<summary>64. Cual es la diferencia entre memo y useMemo?</summary>

#### React

#### Diferencia entre memo y useMemo

| Criterio                 | memo                                                              | useMemo                                                |
| ------------------------ | ----------------------------------------------------------------- | ------------------------------------------------------ |
| **Que es?**              | Funcion de orden superior (HOC)                                   | Hook                                                   |
| **Proposito**            | Evita rerenderizar el componente si las props no cambiaron        | Memoriza el resultado de un calculo entre renders      |
| **Donde se usa?**        | Envuelve un componente                                            | Dentro del componente                                  |
| **Ejemplo de uso**       | `export default memo(MyComponent);`                               | `const value = useMemo(() => compute(), [deps]);`      |
| **Que almacena?**        | Todo el componente                                                | El resultado de una funcion                            |
| **Cuando aplicarlo?**    | Si el componente se renderiza con las mismas props sin cambios    | Si el calculo es costoso y depende de variables        |

#### Cuando usarlo?

- `memo`: cuando el componente recibe las mismas props y no necesita
  rerenderizarse.

- `useMemo`: cuando necesitas conservar el resultado de un calculo para no
  repetirlo en cada render.

</details>

<details>
<summary>65. Por que hay que pasar una funcion a setState()?</summary>

#### React

Pasar una funcion a `setState()` es necesario cuando el nuevo estado depende del
estado anterior. Esto garantiza una actualizacion correcta, ya que `setState()`
se ejecuta de forma asincrona y puede agrupar llamadas.

#### Ejemplo con problema:

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  function increment() {
    setCount(count + 1);
    setCount(count + 1);
  }

  return <button onClick={increment}>{count}</button>;
}
```

Aqui `count + 1` se calcula dos veces con el mismo valor anterior de `count`,
por eso el boton aumentara el valor solo en 1 y no en 2.

#### Enfoque correcto:

```jsx
function Counter() {
  const [count, setCount] = useState(0);

  function increment() {
    setCount(prevCount => prevCount + 1);
    setCount(prevCount => prevCount + 1);
  }

  return <button onClick={increment}>{count}</button>;
}
```

Aqui `setCount()` recibe el valor actual de `prevCount`, por lo que el
incremento funciona correctamente y aumenta el valor en 2.

</details>

<details>
<summary>66. Como se usan los refs en React para interactuar con elementos del DOM?</summary>

#### React

Los refs en React se utilizan para acceder directamente a elementos del DOM o a
componentes, evitando el mecanismo estandar de props y estado.

1. **Creacion de refs:** Usa `React.createRef()` para crear un ref.

```jsx
const myRef = React.createRef();
```

2. **Asociacion del ref al elemento:** El ref se pasa al elemento del DOM
   mediante el atributo `ref`.

```jsx
<input ref={myRef} />
```

3. **Interaccion con el DOM:** El ref da acceso al elemento del DOM a traves de
   `.current`. Por ejemplo, para establecer el foco:

```jsx
myRef.current.focus();
```

4. **Limitaciones:** Los refs no deben usarse para gestionar el estado. Estan
   pensados solo para interactuar con el DOM cuando es necesario (por ejemplo,
   para foco, seleccion de texto o animaciones).

5. **Componentes funcionales:** En React 16.8 y superior, para componentes
   funcionales se usa `useRef`.

```jsx
const inputRef = useRef();
inputRef.current.focus();
```

</details>

<details>
<summary>67. Como usar InnerHtml en React?</summary>

#### React

- En React, para insertar contenido HTML en el DOM se usa el atributo
  `dangerouslySetInnerHTML`. Esto permite insertar HTML directamente en el
  componente, pero este enfoque puede ser peligroso, de ahi el nombre
  "dangerously", ya que permite incrustar HTML sin procesar, lo que puede
  provocar ataques XSS si los datos no estan saneados.

#### Ejemplo de uso de `dangerouslySetInnerHTML`:

```jsx
const MyComponent = () => {
  const htmlContent = '<p>Este es contenido <strong>HTML</strong>.</p>';

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
};
```

#### Explicacion:

- `dangerouslySetInnerHTML` recibe un objeto en el que la clave `__html`
  contiene una cadena de codigo HTML.

- Esto permite insertar HTML dentro del componente, pero no es seguro si el
  contenido proviene de fuentes no confiables.

#### Cuando usarlo:

- Si estas seguro de la seguridad de los datos (por ejemplo, si vienen de tus
  propios servidores).

- Cuando necesitas incrustar contenido HTML dinamico, como paginas o articulos
  en HTML.

#### Advertencias:

- Seguridad: nunca uses `dangerouslySetInnerHTML` para insertar datos recibidos
  de usuarios o de fuentes externas sin limpiarlos antes de scripts maliciosos.

- Para limpiar el contenido, usa bibliotecas como `DOMPurify` y asi evitar
  ataques XSS.

**Ejemplo de limpieza de datos antes de insertarlos:**

```jsx
import DOMPurify from 'dompurify';

const MyComponent = () => {
  const dirtyHtml = "<img src=x onerror=alert('XSS')>";
  const cleanHtml = DOMPurify.sanitize(dirtyHtml);

  return <div dangerouslySetInnerHTML={{ __html: cleanHtml }} />;
};
```

En resumen, `dangerouslySetInnerHTML` debe usarse con cuidado y solo cuando
estes seguro de la seguridad del contenido.

</details>

<details>
<summary>68. Que es ReactDOMServer?</summary>

#### React

**`ReactDOMServer`** es una biblioteca incluida en React que se utiliza para
renderizar componentes de React en el servidor, es decir, para el renderizado
del lado del servidor (SSR). Esto permite generar HTML en el servidor y
enviarlo al cliente, lo que puede mejorar el rendimiento y el SEO.

#### Metodos principales:

1. **`ReactDOMServer.renderToString()`:** Renderiza elementos de React en una
   cadena HTML. Este es el metodo principal para generar HTML estatico para la
   carga inicial de la pagina.

```jsx
import ReactDOMServer from 'react-dom/server';
const html = ReactDOMServer.renderToString(<App />);
```

2. **`ReactDOMServer.renderToStaticMarkup()`:** Renderiza HTML sin atributos
   adicionales relacionados con React, como `data-reactroot`. Es adecuado para
   crear paginas completamente estaticas.

```jsx
const html = ReactDOMServer.renderToStaticMarkup(<App />);
```

3. **`ReactDOMServer.hydrate()`:** Se usa en el lado del cliente para
   "hidratar" el HTML renderizado en el servidor, es decir, para adjuntar la
   interactividad al HTML ya existente.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

#### Uso:

- **SSR (Server-Side Rendering):** Es un enfoque en el que los componentes de
  React se renderizan en el servidor y no en el navegador, lo que permite
  enviar una pagina HTML completamente formada al cliente.

- **SEO:** Como el servidor envia el contenido HTML de inmediato, los motores
  de busqueda pueden indexar las paginas sin necesidad de ejecutar JavaScript.

De este modo, `ReactDOMServer` permite crear paginas prerenderizadas, lo que
mejora la velocidad de carga y puede ser util para el SEO.

</details>

<details>
<summary>69. Para que se utiliza el paquete react-dom?</summary>

#### React

El paquete `react-dom` se utiliza para la interaccion de React con el DOM real
en aplicaciones web. Funciones principales:

1. **`ReactDOM.render()`:** Se usa para renderizar un componente en el DOM real.
   Es el metodo principal que conecta React con los elementos HTML.

```jsx
ReactDOM.render(<App />, document.getElementById('root'));
```

2. **`ReactDOM.hydrate()`:** Se utiliza para hidratar HTML renderizado en el
   servidor (por ejemplo, para SSR). Esto permite que React tome el control del
   HTML ya existente.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

3. **`ReactDOM.createPortal()`:** Permite renderizar elementos hijos en otro
   lugar del DOM, fuera de la jerarquia habitual de componentes. Se usa a
   menudo para ventanas modales, tooltips y elementos emergentes.

```jsx
ReactDOM.createPortal(<Modal />, document.getElementById('modal-root'));
```

4. **`ReactDOM.unmountComponentAtNode()`:** Elimina un componente de React del
   DOM.

```jsx
ReactDOM.unmountComponentAtNode(document.getElementById('root'));
```

5. **`ReactDOM.findDOMNode()`:** Da acceso al elemento real del DOM de un
   componente (se usa poco, porque existen enfoques mas modernos mediante refs).

- Este paquete es necesario para trabajar con el DOM real, pero en la mayoria
  de los casos, despues de la configuracion inicial, no necesitas llamar a
  estos metodos manualmente, ya que suelen usarse automaticamente mediante
  herramientas de compilacion y renderizado.

</details>

<details>
<summary>70. Como usar React.lazy y React.Suspense para cargar codigo en la aplicacion?</summary>

#### React

`React.lazy` y `React.Suspense` se usan para la **_carga dinamica de
componentes_** en React, lo que permite implementar **_division de codigo_**
(`code splitting`). Esto significa que partes del codigo se cargan solo cuando
son necesarias, mejorando asi el rendimiento de la aplicacion.

#### Como funciona:

1. **`React.lazy()`** permite cargar un componente de forma diferida.

2. **`React.Suspense`** se utiliza para envolver una parte del codigo que aun no
   esta cargada, y permite mostrar contenido de reserva (por ejemplo, un loader)
   mientras los componentes se cargan.

#### Ejemplo:

1. **Carga dinamica del componente:** Primero crea un componente que se cargara
   dinamicamente.

```jsx
// Componente cargado dinamicamente
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Wrapper con `React.Suspense`:** Ahora usa `React.Suspense` para mostrar un
   loader mientras el componente se esta cargando.

```jsx
function App() {
  return (
    <div>
      <h1>Mi aplicacion</h1>

      {/* Wrapper para componentes cargados dinamicamente */}
      <React.Suspense fallback={<div>Cargando...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Descripcion:**

- `React.lazy()` recibe una funcion que importa dinamicamente un modulo.

- `React.Suspense` envuelve el componente que usa `React.lazy()` y muestra
  contenido de reserva (en este caso, el texto "Cargando...") mientras el
  componente no termina de cargarse.

#### Ventajas:

- Mejora el rendimiento, cargando componentes solo cuando es necesario.

- Reduce el tamano de la carga inicial, ya que partes de la aplicacion se
  cargan bajo demanda.

Este enfoque es especialmente util en aplicaciones grandes, donde se puede
dividir el codigo en partes para reducir el tiempo de carga de la pagina.

</details>

<details>
<summary>71. Cuales son las mejores practicas de seguridad en React?</summary>

#### React

#### Mejores practicas de seguridad en React:

1. **Prevencion de XSS (Cross-Site Scripting):**

- Limpia siempre los datos que llegan del usuario antes de mostrarlos en el
  componente.
- Usa JSX (React escapa automaticamente las entradas, pero conviene evitar
  `dangerouslySetInnerHTML`).
- Si necesitas usar `dangerouslySetInnerHTML`, asegurate de que el contenido
  este correctamente saneado.

2. **Evita inyecciones de codigo:**

- Nunca pases datos no verificados a `eval()`, `setTimeout()`, `setInterval()`
  u otras funciones que ejecutan codigo.
- Para importaciones dinamicas, usa herramientas con control incorporado, como
  `React.lazy()`.

3. **Acceso seguro a la API:**

- Usa HTTPS para proteger los datos transmitidos por la red.
- Usa autenticacion, autorizacion y cookies seguras (`HTTPOnly`, `Secure`).

4. **Proteccion contra CSRF (Cross-Site Request Forgery):**

- Usa tokens CSRF para verificar todas las solicitudes que modifican datos en el
  servidor.
- Usa la bandera `SameSite` en cookies para limitar su acceso al mismo dominio.

5. **Control de acceso:**

- Verifica si el usuario tiene permisos para ejecutar la accion solicitada antes
  de enviar la peticion al servidor.
- No confies en las validaciones del cliente. La comprobacion final siempre debe
  hacerse en el servidor.

6. **Proteccion en campos editables abiertos:**

- Para formularios y campos que reciben datos del usuario, establece
  restricciones sobre los valores permitidos.

7. **Actualizacion de dependencias:**

- Revisa y actualiza regularmente las dependencias para detectar posibles
  vulnerabilidades. Usa `npm audit` u otras herramientas para ello.

8. **Gestion de secretos:**

- No guardes secretos (claves API, contrasenas, etc.) en el codigo del cliente.
  Deben almacenarse en el servidor o en entornos seguros como variables de
  entorno.

9. **Uso de Content Security Policy (CSP):**

- Usa CSP para impedir la ejecucion de scripts no deseados en tu sitio.

10. **Proteccion contra Clickjacking:**

- Usa las cabeceras `X-Frame-Options` o `Content-Security-Policy` para evitar
  que tu sitio se incruste en un `<iframe>` de otros sitios web.

Seguir estas practicas ayuda a reducir los riesgos de seguridad en aplicaciones
React.

</details>

<details>
<summary>72. Como manejar errores en React con Error Boundary?</summary>

#### React

Los **Error Boundaries** en React permiten capturar errores en componentes
durante el renderizado, en metodos del ciclo de vida y en constructores, y
gestionarlos sin detener por completo la aplicacion.

#### Puntos principales:

- Un Error Boundary es un componente que envuelve otros componentes y puede
  capturar errores que ocurren en su codigo.

- Los **Error Boundaries** solo capturan errores ocurridos en sus descendientes.
  No capturan errores dentro del propio Error Boundary.

#### Como implementar un Error Boundary:

1. **Crear el Error Boundary:** Para crear un Error Boundary, debes implementar
   dos metodos:

- `static getDerivedStateFromError(error)`: actualiza el estado cuando ocurre un
  error.

- `componentDidCatch(error, info)`: permite registrar errores (por ejemplo,
  enviarlos al servidor).

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }

  static getDerivedStateFromError(error) {
    // Actualizamos el estado para mostrar una UI de reserva
    return { hasError: true, error };
  }

  componentDidCatch(error, info) {
    // Logica para registrar errores (por ejemplo, en el servidor)
    console.error('Error caught:', error, info);
  }

  render() {
    if (this.state.hasError) {
      // Mostramos una UI de reserva si ocurre un error
      return <h1>Algo salio mal.</h1>;
    }

    return this.props.children;
  }
}
```

2. **Uso del Error Boundary:** Envuelve con `ErrorBoundary` los componentes que
   pueden producir errores.

```jsx
const App = () => {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
};
```

3. **Interfaz de reserva:** Cuando ocurre un error, en el Error Boundary se
   puede mostrar una interfaz alternativa (por ejemplo, un mensaje de error, un
   boton para reintentar o incluso acciones para recuperar la aplicacion).

#### Puntos importantes:

- Un Error Boundary no captura errores en manejadores de eventos (por ejemplo,
  `onClick`), codigo asincrono, temporizadores o peticiones de red. Para esos
  casos, usa `try...catch` u otros mecanismos.

- Si el error ocurre dentro del propio Error Boundary, no sera capturado.

Los **Error Boundaries** son utiles para la estabilidad de la aplicacion,
porque permiten interceptar y gestionar errores sin detener toda la aplicacion.

</details>

<details>
<summary>73. Que es la inversion de herencia (Inheritance Inversion)?</summary>

#### React

- **La inversion de herencia (Inheritance Inversion)** es una situacion en la
  que una clase que deberia ser base pasa a depender de sus descendientes o
  pierde el control sobre la logica que deberia pertenecer a la jerarquia de
  herencia.

#### Problemas de la inversion de herencia

- Viola el principio de sustitucion de Liskov (LSP).

- Es dificil cambiar o ampliar la clase base sin afectar a todos sus
  descendientes.

- Aumenta la complejidad debido a las interdependencias.

#### Ejemplo de mala practica

```js
class Parent {
  method() {
    throw new Error('El metodo debe implementarse en el descendiente');
  }
}

class Child extends Parent {
  method() {
    return 'Implementacion en el descendiente';
  }
}
```

Aqui la clase base no tiene su propia logica y obliga a los descendientes a
implementar el comportamiento, lo cual es una senal de inversion de herencia.

#### Alternativa: composicion en lugar de herencia

```js
class Behavior {
  method() {
    return 'Implementacion sin inversion';
  }
}

class Parent {
  constructor() {
    this.behavior = new Behavior();
  }

  method() {
    return this.behavior.method();
  }
}
```

Este enfoque elimina la dependencia de la clase padre respecto de sus
descendientes y hace el codigo mas flexible.

</details>

<details>
<summary>74. Que es el polling? Como implementarlo en React?</summary>

#### React

**Polling** es el envio periodico de solicitudes al servidor para obtener datos
actualizados. Es util cuando el servidor no admite WebSockets o Server-Sent
Events, y el cliente necesita recibir nueva informacion sin recargar la pagina.

#### Implementacion de polling en React

El polling puede implementarse con `setInterval`, `setTimeout` o utilizando
hooks de React (`useEffect`).

1. **Uso de `setInterval`**

```jsx
import { useState, useEffect } from 'react';

const PollingComponent = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    const fetchData = async () => {
      const response = await fetch('https://api.example.com/data');
      const result = await response.json();
      setData(result);
    };

    fetchData(); // Ejecutar inmediatamente al cargar

    const interval = setInterval(fetchData, 5000); // Polling cada 5 segundos

    return () => clearInterval(interval); // Limpieza al desmontar
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Cargando...'}</div>;
};
```

- `fetchData()` obtiene datos del servidor.
- `setInterval` lanza el polling cada 5 segundos.
- `clearInterval` detiene el polling al desmontar el componente.

2. **Uso de `setTimeout` para un intervalo dinamico**

Si el servidor tiene limites de solicitudes, es mejor usar `setTimeout` para
evitar superposicion de peticiones.

```jsx
const PollingComponent = () => {
  const [data, setData] = useState(null);

  useEffect(() => {
    let isMounted = true;

    const fetchData = async () => {
      try {
        const response = await fetch('https://api.example.com/data');
        const result = await response.json();
        if (isMounted) setData(result);
      } catch (error) {
        console.error('Error de solicitud', error);
      } finally {
        if (isMounted) setTimeout(fetchData, 5000);
      }
    };

    fetchData();

    return () => {
      isMounted = false; // Evita actualizar el estado despues del desmontaje
    };
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Cargando...'}</div>;
};
```

Aqui `setTimeout` se llama solo despues de que finaliza la solicitud anterior,
lo que evita superposiciones.

#### Conclusion

- `setInterval` es adecuado para polling constante, pero puede provocar
  superposicion de solicitudes.
- `setTimeout` ofrece mas control y es mejor para un polling adaptable.
- En caso de cargas altas, conviene considerar WebSockets o Server-Sent Events.

</details>

<details>
<summary>75. Como implementar el enlace bidireccional de datos en React?</summary>

#### React

En React, el enlace bidireccional de datos se implementa mediante
**componentes controlados** (`controlled components`), donde el estado del
componente (`state`) se sincroniza con el campo de entrada (`input`).

#### Ejemplo de implementacion

```jsx
import { useState } from 'react';

const TwoWayBinding = () => {
  const [value, setValue] = useState('');

  return (
    <div>
      <input
        type="text"
        value={value}
        onChange={e => setValue(e.target.value)}
      />
      <p>Valor introducido: {value}</p>
    </div>
  );
};

export default TwoWayBinding;
```

#### Como funciona?

1. **`value`** almacena el estado actual del valor introducido.

2. **`onChange`** actualiza el estado cuando cambia el `input`.

3. **El `value` actualizado** se muestra en la interfaz, garantizando el enlace
   bidireccional.

Este enfoque permite controlar los datos introducidos, validarlos y procesarlos
antes de actualizar el estado.

</details>

<details>
<summary>76. Que es el flujo inverso de datos (Reverse Data Flow) en React?</summary>

#### React

El flujo inverso de datos (Reverse Data Flow) en React significa transferir
cambios de estado desde un componente hijo hacia el componente padre. Es lo
opuesto al flujo de datos habitual, donde el componente padre pasa props al
hijo.

#### En React, el flujo inverso de datos normalmente se implementa mediante:

1. **Funciones callback:**

- El componente hijo llama a un callback que recibe a traves de props para
  informar al componente padre sobre cambios en su estado o para ejecutar alguna
  accion.

- Por ejemplo, al actualizar un valor en el componente hijo, se puede llamar a
  una funcion del componente padre que actualiza el estado.

2. **Ejemplo:**

```jsx
function Parent() {
  const [value, setValue] = useState('');

  const handleChange = newValue => {
    setValue(newValue);
  };

  return <Child onValueChange={handleChange} />;
}

function Child({ onValueChange }) {
  return <input type="text" onChange={e => onValueChange(e.target.value)} />;
}
```

- En este ejemplo, el componente hijo pasa el valor al padre mediante la funcion
  `onValueChange`, implementando asi el flujo inverso de datos.

</details>

<details>
<summary>77. Que es la mutacion del estado y como evitarla?</summary>

#### React

La mutacion del estado es la modificacion directa de un objeto o arreglo que
almacena el estado, sin crear una copia. En React esto provoca resultados
impredecibles, porque React no sabe que el estado cambio y no volvera a
renderizar el componente.

#### Para evitar la mutacion del estado, hay que:

1. **Crear copias de los datos** antes de modificarlos. Por ejemplo, para
   arreglos y objetos:

- Para arreglos: `setItems([...items, newItem])`
- Para objetos: `setUser({...user, name: 'John'})`

2. **Usar metodos que no mutan los datos**, como `map()`, `filter()`,
   `reduce()` para arreglos, o `Object.assign()` para objetos.

Esto permite a React rastrear correctamente los cambios y rerenderizar los
componentes.

 </details>

<details>
<summary>78. Que es el modo estricto (Strict Mode) de React? Cuales son sus ventajas?</summary>

#### React

**Strict Mode** es una herramienta especial de React para detectar posibles
problemas en el codigo. No afecta el funcionamiento en produccion, pero ayuda a
mejorar la calidad del codigo durante el desarrollo.

Se activa envolviendo componentes en `<React.StrictMode>`:

```jsx
import React from 'react';
import ReactDOM from 'react-dom/client';
import App from './App';

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);
```

#### Ventajas de Strict Mode

| **Funcion**                                   | **Descripcion**                                                                                         |
| ---------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Deteccion de metodos de ciclo de vida inseguros** | Advierte sobre metodos obsoletos (`componentWillMount`, `componentWillReceiveProps`, `componentWillUpdate`). |
| **Llama funciones dos veces durante el desarrollo** | Ayuda a encontrar efectos secundarios en `useEffect` y otros hooks.                                   |
| **Advierte sobre APIs obsoletas**             | Senala contextos antiguos (`contextType`) y patrones inseguros.                                        |
| **Detecta comportamientos impredecibles**     | Por ejemplo, ejecuta `useEffect` dos veces para comprobar la limpieza correcta de efectos.             |

#### Vale la pena usarlo?

Si, si quieres evitar problemas ya en la etapa de desarrollo. Puede resultar un
poco molesto por el doble renderizado, pero ayuda a encontrar errores ocultos
en el codigo.

</details>

<details>
<summary>79. Cuales son las formas recomendadas de comprobar tipos estaticos?</summary>

#### React

1. **TypeScript:** Es el enfoque mas popular y completo para tipado estatico en
   JavaScript/React. TypeScript agrega tipos estrictos al codigo, permitiendo
   comprobarlos en tiempo de compilacion.

2. **PropTypes:** Mecanismo integrado para validar tipos de props en
   componentes React. Se usa para verificar tipos en tiempo de ejecucion. No
   ofrece tipado estatico en compilacion, pero permite validar props durante la
   ejecucion de la aplicacion.

```jsx
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};
```

3. **Flow:** Otro mecanismo de tipado estatico para JavaScript. Flow es menos
   popular que TypeScript, pero tambien permite agregar tipos y verificarlos en
   tiempo de compilacion.

4. **ESLint con plugins de tipado:** Se puede usar ESLint con plugins para
   comprobar tipos (por ejemplo, `eslint-plugin-flowtype` o
   `eslint-plugin-typescript`), pero esto no ofrece la misma profundidad de
   tipado que TypeScript.

Recomiendo usar **TypeScript**, ya que se integra bien con React y otras
herramientas y proporciona tipado estatico completo en compilacion.

</details>

<details>
<summary>80. Como implementar animacion en React?</summary>

#### React

1. **Animaciones CSS:** La forma mas simple es usar animaciones o transiciones
   CSS estandar.

```jsx

<div className="my-element">Hello</div>

<style jsx>{`
  .my-element {
    animation: fadeIn 1s ease-in-out;
  }

  @keyframes fadeIn {
    0% { opacity: 0; }
    100% { opacity: 1; }
  }
`}</style>
```

2. **React Transition Group:** Para transiciones de animacion mas complejas
   entre componentes. Este paquete permite controlar la animacion durante la
   insercion o eliminacion de componentes.

```jsx

import { CSSTransition } from 'react-transition-group';

<CSSTransition in={isVisible} timeout={300} classNames="fade" unmountOnExit>
  <div>Content</div>
</CSSTransition>

<style jsx>{`
  .fade-enter {
    opacity: 0;
  }
  .fade-enter-active {
    opacity: 1;
    transition: opacity 300ms;
  }
  .fade-exit {
    opacity: 1;
  }
  .fade-exit-active {
    opacity: 0;
    transition: opacity 300ms;
  }
`}</style>
```

3. **Framer Motion:** Es una biblioteca potente para animaciones que permite
   crear animaciones complejas en React.

```jsx
import { motion } from 'framer-motion';

<motion.div
  animate={{ opacity: 1 }}
  initial={{ opacity: 0 }}
  transition={{ duration: 1 }}
>
  Hello
</motion.div>;
```

4. **React Spring:** Para animaciones basadas en fisica, que permiten crear
   movimientos mas realistas.

```jsx
import { useSpring, animated } from 'react-spring';

const props = useSpring({ opacity: 1, from: { opacity: 0 } });

<animated.div style={props}>Hello</animated.div>;
```

5. **Estilos inline y JavaScript:** Se puede usar `setState` y cambiar estilos
   segun el estado del componente.

```jsx
const [opacity, setOpacity] = useState(0);

useEffect(() => {
  setOpacity(1);
}, []);

return <div style={{ opacity }}>Hello</div>;
```

Para efectos de animacion mas complejos, se recomienda usar **Framer Motion** o
**React Spring**, porque estas bibliotecas ofrecen mas posibilidades y facilitan
la gestion de animaciones avanzadas.

</details>

<details>
<summary>81. Cuales son los paquetes de animacion mas populares en React?</summary>

#### React

#### Paquetes populares de animacion en React:

1. **Framer Motion** es uno de los paquetes de animacion mas populares para
   React. Es facil de usar, admite animaciones y transiciones, funciona con
   drag-and-drop y ademas ofrece una API potente para crear animaciones
   complejas.

2. **React Spring** es una biblioteca para crear animaciones basadas en
   fisica. Usa propiedades como elasticidad y friccion. Encaja bien para
   animaciones complejas e interacciones avanzadas.

3. **GSAP (GreenSock Animation Platform)** es una biblioteca potente para
   animaciones que funciona no solo con React, sino tambien con otros
   frameworks. Es conocida por su velocidad y por permitir animaciones muy
   complejas.

4. **React Transition Group** es una biblioteca basica para animaciones de
   transicion en React. Permite crear animaciones de entrada, salida y cambios
   de estado de componentes, ofreciendo flexibilidad para definir transiciones.

5. **Lottie for React** permite incrustar facilmente animaciones creadas en
   After Effects en formato JSON. Es util para animaciones complejas, como
   iconos o elementos interactivos.

</details>

<details>
<summary>82. React DevTools: como usarlo para depuracion?</summary>

#### React

1. **Instalacion de React DevTools**

- Si usas `Chrome` o `Firefox`, simplemente instala la extension
  `React Developer Tools`:
  - Chrome Web Store
  - Firefox Add-ons

- Si depuras en `Electron`, `React Native` u otro entorno no estandar, instala:

```sh
npm install -g react-devtools
react-devtools
```

2. **Pestanas principales y su uso**

- ⚛ **Components** → ver la estructura de los componentes, el estado y las
  props.
- ⚡ **Profiler** → analizar el rendimiento y detectar renderizados
  innecesarios.

3. **Depuracion de props y estado**

- Abre la pestana `Components`.
- Selecciona un componente y veras sus `props`, `state` y `context`.
- Puedes editar `state` y `props` directamente en `DevTools` para probar cambios
  de comportamiento.

4. **Deteccion de renderizados innecesarios**

- En la pestana `Profiler`, pulsa `Record`, realiza una interaccion y luego
  pulsa `Stop`.
- Revisa la codificacion por colores:
  - **Rojo** → render costoso.
  - **Amarillo** → coste medio.
  - **Azul** → render ligero.
- Optimiza componentes con `React.memo()`, `useMemo()` y `useCallback()`.

5. **Herramientas para depurar Context API**

- Si usas React Context, puedes inspeccionar su valor en DevTools.
- Elige un componente que use `useContext()` y busca la pestana `Context`.

6. **Depuracion del render en Strict Mode**

- Si `React DevTools` muestra que un componente se renderiza dos veces, revisa
  `StrictMode` en `index.js`:

```jsx
<React.StrictMode>
  <App />
</React.StrictMode>
```

- No provoca bugs por si mismo, solo ayuda a detectar problemas potenciales.

7. **Inspeccion de hooks**

- DevTools permite ver el estado de hooks como `useState`, `useEffect` y
  `useReducer`.
- En la pestana `Components`, selecciona un componente y veras el estado de
  `useState`.

#### Conclusion:

**React DevTools** es una herramienta potente para depurar estado, props,
rendimiento y contexto. Usa `Profiler` para optimizar y `Components` para
seguir cambios en estado y props.

</details>

<details>
<summary>83. Cuales son los linters mas populares para React?</summary>

#### React

#### Linters mas populares para React:

1. **ESLint** es el linter mas extendido para `JavaScript`, y soporta `React`
   mediante el plugin `eslint-plugin-react`. Verifica estilo de codigo, detecta
   errores y puede trabajar junto con otras herramientas como `Prettier` para
   el formateo.

2. **Prettier** es una herramienta de formateo automatico de codigo. A menudo
   se usa junto con `ESLint` para mantener un estilo uniforme.

3. **TSLint** es un linter para `TypeScript` que tambien puede usarse con
   `React`, aunque hoy en dia se esta sustituyendo activamente por `ESLint` por
   su mayor flexibilidad y soporte.

Estas herramientas ayudan a mantener un alto nivel de calidad del codigo y a
prevenir errores en proyectos grandes.

</details>

<details>
<summary>84. Que es Next.js?</summary>

#### React

**Next.js** es un framework de React que ofrece soluciones listas para
renderizado del lado del servidor (SSR), generacion estatica (SSG), rutas API,
enrutamiento, optimizacion del rendimiento y SEO.

#### Funcionalidades principales:

- **Renderizado hibrido:** soporte para SSR, SSG e ISR (regeneracion
  incremental).
- **Enrutamiento automatico:** los archivos en `pages/` se convierten
  automaticamente en rutas.
- **Rutas API:** creacion de endpoints de servidor en archivos `pages/api/*`.
- **Optimizacion del rendimiento:** division automatica de codigo y reduccion
  del bundle.
- **Soporte para App Router:** nuevo enfoque basado en React Server Components y
  `app/` en lugar de `pages/`.
- **Soporte integrado para Tailwind, TypeScript, ESLint y otras tecnologias**.

Se usa para crear aplicaciones web de alto rendimiento, blogs, soluciones de
e-commerce e interfaces complejas.

</details>

<details>
<summary>85. Cuales son las principales diferencias entre Next.js y React?</summary>

#### React

#### Principales diferencias entre Next.js y React:

| **Criterio**                           | **React**                               | **Next.js**                                                             |
| -------------------------------------- | --------------------------------------- | ------------------------------------------------------------------------ |
| **Tipo**                               | Biblioteca para crear UI                | Framework basado en React                                                |
| **Renderizado**                        | Solo del lado del cliente (CSR)         | Soporta CSR, SSR, SSG, ISR                                               |
| **Enrutamiento**                       | Se implementa manualmente con React Router | Enrutamiento por archivos (`pages/` o `app/`)                         |
| **SEO**                                | Soporte debil por CSR                   | Buen soporte SEO (SSR, SSG)                                              |
| **Rutas API**                          | No                                      | Posibilidad integrada de crear endpoints API (`pages/api/`)             |
| **Cacheo**                             | Sin mecanismos integrados               | ISR permite actualizar paginas sin regeneracion completa                 |
| **Optimizacion del rendimiento**       | Uso de soluciones externas              | Optimizaciones integradas (code splitting, carga automatica de imagenes) |
| **Soporte de componentes de servidor** | Depende de la configuracion             | Soporte integrado para React Server Components (`app/`)                  |

#### Conclusion:

- **React** es adecuado para SPA renderizadas en el cliente.

- **Next.js** es mas adecuado para proyectos optimizados para SEO, renderizado
  hibrido y aplicaciones web de alto rendimiento.

</details>

<details>
<summary>86. Para que sirve React Helmet Async?</summary>

#### React

**React Helmet Async** es una version optimizada de **React Helmet** que se usa
para actualizar dinamicamente el `<head>` (metaetiquetas, titulos, Open Graph,
etc.) en aplicaciones React.

#### Para que se necesita?

1. **Optimizacion SEO**: permite cambiar titulos de paginas, meta descripciones
   y palabras clave.

2. **`<head>` dinamico**: se pueden modificar etiquetas para cada pagina sin
   recargarla.

3. **Soporte SSR (Server-Side Rendering)**: a diferencia de React Helmet
   clasico, esta version funciona correctamente en aplicaciones SSR sin
   problemas de asincronia.

#### Ejemplo de uso:

```jsx
import { Helmet } from 'react-helmet-async';

function MyComponent() {
  return (
    <Helmet>
      <title>Pagina principal</title>
      <meta name="description" content="Esta es la descripcion de la pagina principal" />
    </Helmet>
  );
}
```

#### SSR(Next.js, Express);

```jsx
import { HelmetProvider, Helmet } from 'react-helmet-async';

const helmetContext = {};
const html = renderToString(
  <HelmetProvider context={helmetContext}>
    <App />
  </HelmetProvider>
);
const { helmet } = helmetContext;

const finalHtml = `

  <html>
    <head>
      ${helmet.title.toString()}
      ${helmet.meta.toString()}
    </head>
    <body>${html}</body>
  </html>
`;
```

#### Por que es mejor que `react-helmet`?

- Soporta SSR sin errores de asincronia.
- Es mas ligero y rapido.
- No genera problemas en `StrictMode`.

#### Conclusion:

Si necesitas SEO en React con SSR, conviene usar `react-helmet-async`.

</details>

<details>
<summary>87. Que es un componente distribuido (Distributed Component)?</summary>

#### React

Un **componente distribuido (Distributed Component)** es un concepto en el que
un componente se divide en varias partes independientes que pueden renderizarse
o ejecutar logica por separado, pero funcionan juntas.

#### Ejemplos de implementacion:

1. **Code Splitting**

- Los componentes se cargan solo cuando se necesitan, reduciendo el tamano
  inicial del bundle.

```jsx
import { lazy, Suspense } from 'react';

const LazyComponent = lazy(() => import('./LazyComponent'));

function App() {
  return (
    <Suspense fallback={<div>Cargando...</div>}>
      <LazyComponent />
    </Suspense>
  );
}
```

2. **Componentes contenedor (Container-Presentational Pattern)**

- Separa la logica (contenedor) de la presentacion (componente presentacional).

```jsx
function DataContainer({ children }) {
  const [data, setData] = useState(null);

  useEffect(() => {
    fetch('/api/data')
      .then(res => res.json())
      .then(setData);
  }, []);

  return children(data);
}

function Presentational({ data }) {
  return <div>{data ? JSON.stringify(data) : 'Cargando...'}</div>;
}

function App() {
  return (
    <DataContainer>{data => <Presentational data={data} />}</DataContainer>
  );
}
```

3. **Micro frontends**

- Uso de componentes autonomos separados en distintas partes de la aplicacion.
- Por ejemplo, distintos equipos desarrollan partes separadas de un gran
  proyecto (`React`, `Vue`, `Angular`) y luego las integran.

#### Cuando usarlo:

- Para optimizar el rendimiento (carga diferida).

- Para simplificar el mantenimiento del codigo (separacion de logica).

- Para aplicaciones escalables (micro frontends).

</details>

<details>
<summary>88. Que es un componente conmutador (Switching Component)?</summary>

#### React

Un **componente conmutador (Switching Component)** en React es un patron en el
que un componente renderiza dinamicamente uno de sus componentes hijos en
funcion de una determinada condicion. Se usa cuando hay que mostrar distintos
componentes segun el estado, la ruta o los datos recibidos.

#### Ejemplo 1: cambio segun el estado

```jsx
const SwitchingComponent = ({ type }) => {
  switch (type) {
    case 'success':
      return <SuccessMessage />;
    case 'error':
      return <ErrorMessage />;
    default:
      return <DefaultMessage />;
  }
};
```

```jsx
const App = () => {
  return <SwitchingComponent type="success" />;
};
```

- `type` define que componente se mostrara.

#### Ejemplo 2: uso con React Router

```jsx
import { Route, Routes } from 'react-router-dom';

const App = () => {
  return (
    <Routes>
      <Route path="/" element={<Home />} />
      <Route path="/about" element={<About />} />
      <Route path="\*" element={<NotFound />} />
    </Routes>
  );
};
```

- Aqui `Routes` actua como componente conmutador para renderizar el componente
  adecuado segun la URL.

#### Ejemplo 3: renderizado condicional mediante objeto

```jsx
const components = {
  success: SuccessMessage,
  error: ErrorMessage,
  default: DefaultMessage,
};

const SwitchingComponent = ({ type }) => {
  const Component = components[type] || components.default;
  return <Component />;
};
```

- Esta es una variante mas limpia sin `switch`.

Los componentes conmutadores simplifican la logica y hacen el codigo mas
legible cuando es necesario renderizar condicionalmente distintos componentes.

</details>

<details>
<summary>89. Que es Reselect y como funciona?</summary>

#### React

**Reselect** es una biblioteca para crear selectores eficientes en Redux. Ayuda
a optimizar la obtencion de datos desde el estado y a evitar renderizados
innecesarios de componentes mediante memoizacion.

#### Como funciona Reselect?

Reselect usa **memoizacion** para reutilizar resultados de calculos si los
datos de entrada no han cambiado.

1. **Recibe selectores de entrada**, que obtienen datos del estado.

2. **Calcula un valor** a partir de esos datos.

3. **Guarda en cache el resultado** para no repetir calculos con las mismas
   entradas.

#### Ejemplo de uso:

```jsx
import { createSelector } from 'reselect';

// Selector de entrada que obtiene todos los usuarios
const selectUsers = state => state.users;

// Selector de entrada que obtiene el filtro activo
const selectFilter = state => state.filter;

// Selector memoizado que filtra usuarios
export const selectFilteredUsers = createSelector(
  [selectUsers, selectFilter],
  (users, filter) => users.filter(user => user.role === filter)
);
```

- Sin Reselect, el componente revisaria todo el arreglo `users` en cada render.
- Con Reselect, el selector se ejecuta solo cuando cambian `users` o `filter`.

#### Ventajas de Reselect:

- Reduce la cantidad de llamadas innecesarias a `mapStateToProps`.
- Evita renderizados innecesarios de componentes.
- Se combina facilmente con Redux.
- Mejora el rendimiento.

</details>

<details>
<summary>90. Que tipos de datos puede devolver render?</summary>

#### React

El metodo `render()` en React puede devolver:

1. **JSX o un elemento React**

```jsx
render() {
return <div>Hello, World!</div>;
}
```

2. **Un arreglo de elementos (renderizado fragmentado)**

```jsx
render() {
return [
<li key="1">Item 1</li>,
<li key="2">Item 2</li>
];
}
```

3. **Fragmentos (`React.Fragment`)**

```jsx
render() {
return (
<>
<h1>Title</h1>
<p>Description</p>
</>
);
}
```

4. **`null` (no renderizar nada)**

```jsx
render() {
return null;
}
```

5. **Valores booleanos (se ignoran)**

```jsx
render() {
return false; // No se mostrara nada
}
```

6. **Valores de texto (se renderizan como texto)**

```jsx
render() {
return "Hello, World!";
}
```

7. **Portales (render en un elemento DOM fuera del componente padre)**

```jsx
import { createPortal } from "react-dom";

render() {
return createPortal(<div>Modal</div>, document.getElementById("modal-root"));
}
```

#### Conclusion:

La opcion principal es JSX o elementos React, pero tambien se pueden devolver
arreglos, fragmentos, `null`, texto o renderizar mediante portales.

</details>

<details>
<summary>91. Como React maneja o limita el uso de props de un tipo determinado?</summary>

#### React

React limita el uso de props de un tipo determinado mediante `PropTypes` o
`TypeScript`.

1. **Uso de PropTypes (verificacion de tipos integrada)**

```jsx
import PropTypes from 'prop-types';

const MyComponent = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Edad: {age}</p>
      <p>{isActive ? 'Activo' : 'Inactivo'}</p>
    </div>
  );
};

// Definicion de tipos de props
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isActive: PropTypes.bool,
};
```

- `PropTypes.string.isRequired`: la prop `name` es obligatoria.
- `PropTypes.number`: `age` debe ser un numero.
- `PropTypes.bool`: `isActive` debe ser un valor booleano.

Si se pasan tipos incorrectos, React mostrara una advertencia en la consola
(solo en modo de desarrollo).

2. **Uso de TypeScript (verificacion estricta en tiempo de compilacion)**

```tsx
type MyComponentProps = {
  name: string;
  age?: number;
  isActive: boolean;
};

const MyComponent: React.FC<MyComponentProps> = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Edad: {age}</p>
      <p>{isActive ? 'Activo' : 'Inactivo'}</p>
    </div>
  );
};
```

- `name: string`: prop de tipo string obligatoria.
- `age?: number`: prop numerica opcional.
- `isActive: boolean`: prop booleana obligatoria.

TypeScript genera un error incluso antes de ejecutar el codigo si se pasan
props incorrectas.

#### Que elegir?

| **Metodo**     | **Ventajas**                            | **Desventajas**                           |
| -------------- | --------------------------------------- | ----------------------------------------- |
| **PropTypes**  | Simple, funciona en JavaScript          | Solo verifica en runtime, menor seguridad |
| **TypeScript** | Tipado estricto, detecta errores antes  | Requiere compilacion, sintaxis mas compleja |

Si el proyecto usa **TypeScript**, normalmente **PropTypes** no hace falta. Si
usas **JavaScript**, **PropTypes** proporciona una validacion basica.

</details>

<details>
<summary>92. Cual es la diferencia entre renderizado y montaje?</summary>

#### React

Diferencia entre renderizado y montaje en React

| **Proceso**               | **Descripcion**                                                                                                                                                                                     |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Montaje (Mounting)**    | El componente se crea y se agrega al DOM por primera vez. Se llaman `constructor`, `render`, `componentDidMount` (en clases) o `useEffect` con un arreglo de dependencias vacio (en componentes funcionales). |
| **Renderizado (Rendering)** | Se ejecuta `render()` o una nueva llamada del componente funcional para actualizar el contenido. Ocurre cuando cambian `state`, `props` o cuando se llama a `forceUpdate()`.                    |

#### Ejemplo de montaje

```jsx
useEffect(() => {
  console.log('Componente montado');
}, []); // Se ejecuta una vez al montar
```

#### Ejemplo de renderizado

```jsx
const [count, setCount] = useState(0);

useEffect(() => {
  console.log('El componente se renderizo');
}); // Se ejecuta en cada render

return <button onClick={() => setCount(count + 1)}>+</button>;
```

Aqui el render ocurre cada vez que cambia `count`.

</details>

<details>
<summary>93. Que es el flujo reactivo de datos (reactive data flow) en React?</summary>

#### React

El **flujo reactivo de datos (Reactive Data Flow) en React** significa que los
cambios en el estado o en las props de un componente provocan automaticamente
una actualizacion de la UI sin necesidad de forzar manualmente un rerender.

#### Principios principales:

1. **Flujo de datos unidireccional**: React pasa los datos de arriba hacia abajo
   (de componentes padre a hijo).

2. **Declaratividad**: describimos que hay que renderizar y React se encarga de
   la actualizacion.

3. **Actualizacion automatica**: si cambian `state` o `props`, React vuelve a
   renderizar solo las partes modificadas.

#### Ejemplo de actualizacion reactiva:

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Contador: {count}</p>
      <button onClick={() => setCount(count + 1)}>Aumentar</button>
    </div>
  );
}
```

#### Como funciona?

- `useState` crea el estado `count`.

- Al hacer clic, `setCount(count + 1)` actualiza el estado.

- React rerenderiza automaticamente el componente con los nuevos datos.

#### React es completamente reactivo?

- No. A diferencia de frameworks "reactivos" como Svelte o Solid.js, React no
  actualiza el DOM al cambiar una variable directamente. Usa Virtual DOM y
  dispara rerenders cuando cambian `state` o `props`.

#### Conclusion:

- El flujo reactivo de datos en React significa que la UI se actualiza
  automaticamente cuando cambia el estado, pero usando Virtual DOM y batching de
  actualizaciones para optimizar.

</details>

<details>
<summary>94. Es React reactivo?</summary>

#### React

React no es una biblioteca puramente reactiva como, por ejemplo, Vue o Svelte.
Sin embargo, React tiene algunas caracteristicas que lo hacen parecido a los
frameworks reactivos:

1. **Actualizacion automatica de UI**: React actualiza la interfaz
   automaticamente cuando cambia el estado (`state`) o las props del
   componente, lo que recuerda a los enfoques reactivos. Esto ocurre a traves
   del proceso de renderizado y comparacion de cambios.

2. **Componentes funcionales y hooks**: El uso de hooks como `useState` y
   `useEffect` crea un efecto de reactividad, donde cambios en el estado o en
   las props provocan nuevos renders.

3. **Reactividad parcial**: React rerenderiza solo los componentes cuyo estado o
   props cambiaron. Esto se acerca a la reactividad, pero a diferencia de otros
   frameworks, React no gestiona dependencias o valores mediante observadores
   automaticos.

En resumen, React tiene algunos principios reactivos, pero no es un framework
totalmente reactivo.

</details>

<details>
<summary>95. Que formas de implementar drag-and-drop en React conoces?</summary>

#### React

El drag-and-drop en React puede implementarse de varias maneras:

- **Usando la API de HTML5** (`onDragStart`, `onDrop`)

- **Bibliotecas** (`react-dnd`, `dnd-kit`)

1. **Uso de la API nativa de Drag-and-Drop**

```jsx
import { useState } from 'react';

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const onDragStart = (e, index) => {
    e.dataTransfer.setData('text/plain', index);
  };

  const onDrop = (e, targetIndex) => {
    const sourceIndex = e.dataTransfer.getData('text/plain');
    const newItems = [...items];
    const [movedItem] = newItems.splice(sourceIndex, 1);
    newItems.splice(targetIndex, 0, movedItem);
    setItems(newItems);
  };

  return (
    <ul>
      {items.map((item, index) => (
        <li
          key={index}
          draggable
          onDragStart={e => onDragStart(e, index)}
          onDragOver={e => e.preventDefault()}
          onDrop={e => onDrop(e, index)}
          style={{ padding: '10px', border: '1px solid black', margin: '5px' }}
        >
          {item}
        </li>
      ))}
    </ul>
  );
}

export default DragAndDrop;
```

- Es simple y no requiere bibliotecas externas.
- Tiene control limitado y no soporta casos complejos.

2. **Uso de `react-dnd` (opcion mas potente)**

```bash
   npm install react-dnd react-dnd-html5-backend
```

```jsx
import { DndProvider, useDrag, useDrop } from 'react-dnd';
import { HTML5Backend } from 'react-dnd-html5-backend';
import { useState } from 'react';

const ItemType = 'ITEM';

function DraggableItem({ item, index, moveItem }) {
  const [{ isDragging }, drag] = useDrag({
    type: ItemType,
    item: { index },
    collect: monitor => ({
      isDragging: monitor.isDragging(),
    }),
  });

  const [, drop] = useDrop({
    accept: ItemType,
    hover: draggedItem => {
      if (draggedItem.index !== index) {
        moveItem(draggedItem.index, index);
        draggedItem.index = index;
      }
    },
  });

  return (
    <div
      ref={node => drag(drop(node))}
      style={{
        padding: '10px',
        margin: '5px',
        border: '1px solid black',
        backgroundColor: isDragging ? 'lightgray' : 'white',
      }}
    >
      {item}
    </div>
  );
}

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const moveItem = (from, to) => {
    const updatedItems = [...items];
    const [movedItem] = updatedItems.splice(from, 1);
    updatedItems.splice(to, 0, movedItem);
    setItems(updatedItems);
  };

  return (
    <DndProvider backend={HTML5Backend}>
      {items.map((item, index) => (
        <DraggableItem
          key={index}
          item={item}
          index={index}
          moveItem={moveItem}
        />
      ))}
    </DndProvider>
  );
}

export default DragAndDrop;
```

- Es flexible y soporta casos complejos.
- Facilita el trabajo con elementos anidados.
- Agrega una dependencia extra.

3. **Uso de `dnd-kit` (opcion simple y moderna)**

```bash
   npm install @dnd-kit/core @dnd-kit/sortable
```

```jsx
import { DndContext, closestCenter } from '@dnd-kit/core';
import { SortableContext, useSortable, arrayMove } from '@dnd-kit/sortable';
import { useState } from 'react';

function SortableItem({ id }) {
  const { attributes, listeners, setNodeRef, transform, transition } =
    useSortable({ id });

  return (
    <div
      ref={setNodeRef}
      {...attributes}
      {...listeners}
      style={{
        padding: '10px',
        margin: '5px',
        border: '1px solid black',
        backgroundColor: 'white',
        transform: transform ? `translateY(${transform.y}px)` : undefined,
        transition,
      }}
    >
      {id}
    </div>
  );
}

function DragAndDrop() {
  const [items, setItems] = useState(['Item 1', 'Item 2', 'Item 3']);

  const onDragEnd = ({ active, over }) => {
    if (active.id !== over.id) {
      setItems(items => {
        const oldIndex = items.indexOf(active.id);
        const newIndex = items.indexOf(over.id);
        return arrayMove(items, oldIndex, newIndex);
      });
    }
  };

  return (
    <DndContext collisionDetection={closestCenter} onDragEnd={onDragEnd}>
      <SortableContext items={items}>
        {items.map(id => (
          <SortableItem key={id} id={id} />
        ))}
      </SortableContext>
    </DndContext>
  );
}

export default DragAndDrop;
```

- API moderno, mas ligero que `react-dnd`.
- Facil de usar.
- Soporta ordenacion (`sortable`).

#### Conclusion:

- Si necesitas algo simple → **HTML5 Drag-and-Drop API**.

- Si necesitas control flexible → **react-dnd**.

- Si quieres una opcion moderna y ligera → **dnd-kit**.

</details>

<details>
<summary>96. Como renderizar codigo HTML en un componente React?</summary>

#### React

Usa `dangerouslySetInnerHTML`, pero con cuidado: puede provocar ataques XSS si
insertas datos no saneados.

#### Ejemplo:

```jsx
function MyComponent() {
  const htmlContent = "<p style='color: red;'>Este es codigo HTML</p>";

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
}
```

Si trabajas con datos dinamicos, sanealos obligatoriamente antes de insertarlos.

</details>

<details>
<summary>97. Como agregar una clase condicionalmente en React?</summary>

#### React

En React, la adicion condicional de clases a elementos normalmente se hace con
el atributo `className` y usando un operador ternario o funciones para definir
las condiciones.

#### Enfoques principales:

1. **Operador ternario**

```jsx
function MyComponent({ isActive }) {
  return (
    <div className={isActive ? 'active-class' : 'inactive-class'}>Hello</div>
  );
}
```

- Si `isActive` es `true`, se agregara la clase `active-class`.
- En caso contrario, `inactive-class`.

2. **Template strings**

```jsx
function MyComponent({ isHighlighted }) {
  return (
    <div className={`base-class ${isHighlighted ? 'highlighted-class' : ''}`}>
      Hello
    </div>
  );
}
```

- Siempre se agrega `base-class`.
- Si `isHighlighted` es `true`, tambien se agrega `highlighted-class`.

3. **Biblioteca `clsx`**

- `clsx` ayuda a trabajar con clases de forma mas elegante.

```bash
npm install clsx
```

```jsx
import clsx from 'clsx';

function MyComponent({ isActive, isDisabled }) {
  return (
    <div
      className={clsx('base-class', {
        'active-class': isActive,
        'disabled-class': isDisabled,
      })}
    >
      Hello
    </div>
  );
}
```

- `clsx` permite agregar facilmente varias clases en funcion de condiciones.

4. **Biblioteca `classnames`**

- Es similar a `clsx`, pero ofrece mas posibilidades.

```bash
npm install classnames
```

```jsx
import classNames from 'classnames';

function MyComponent({ isActive, isDisabled }) {
  return (
    <div
      className={classNames('base-class', {
        'active-class': isActive,
        'disabled-class': isDisabled,
      })}
    >
      Hello
    </div>
  );
}
```

5. **Extraer la logica a una funcion separada**

```jsx
function getClassName(isActive, isDisabled) {
  let className = 'base-class';
  if (isActive) className += ' active-class';
  if (isDisabled) className += ' disabled-class';
  return className;
}

function MyComponent({ isActive, isDisabled }) {
  return <div className={getClassName(isActive, isDisabled)}>Hello</div>;
}
```

- La logica de composicion de clases se vuelve mas legible y reutilizable.

#### Conclusion:

- Para casos simples, basta con usar el operador ternario o template strings.

- Para condiciones complejas, es mejor usar `clsx` o `classnames`, que mejoran
  la comodidad y la legibilidad del codigo.

</details>

<details>
<summary>98. Como ejecutar codigo antes de eliminar un componente del arbol?</summary>

#### React

Para ejecutar codigo antes de eliminar un componente del arbol en React, se
usan estos enfoques:

1. **Componentes de clase:** `componentWillUnmount`

- En componentes de clase existe el metodo de ciclo de vida
  `componentWillUnmount`, que se llama antes de eliminar el componente.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('El componente sera eliminado');
  }

  render() {
    return <div>Mi componente</div>;
  }
}
```

2. **Componentes funcionales:** `useEffect` con limpieza

- En componentes funcionales, la limpieza puede hacerse en `useEffect`,
  devolviendo una funcion que se ejecutara antes de eliminar el componente.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('El componente sera eliminado');
    };
  }, []);

  return <div>Mi componente</div>;
}
```

3. **Manejo antes de cerrar la pagina (`beforeunload`)**

- Si necesitas ejecutar codigo antes de cerrar la pestana o recargar la pagina:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('La pagina se esta cerrando');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Conclusion

- `componentWillUnmount`: para componentes de clase.

- `useEffect` con `return`: para componentes funcionales.

- `beforeunload`: para casos en los que hay que reaccionar a la salida de la
  pagina.

</details>

<details>
<summary>99. Que es useReducer()?</summary>

#### React

- `useReducer()` es un hook de React que se utiliza para gestionar estado en
  componentes funcionales. Es una alternativa a `useState()`, adecuada para
  logicas de actualizacion de estado mas complejas, especialmente cuando los
  cambios dependen del estado anterior.

#### Sintaxis:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer`: una funcion que recibe `state` y `action` y devuelve un nuevo
  estado.

- `initialState`: el estado inicial.

- `dispatch`: funcion para invocar al reducer con una `action`.

#### Ejemplo:

```jsx
import { useReducer } from 'react';

const initialState = { count: 0 };

function reducer(state, action) {
  switch (action.type) {
    case 'increment':
      return { count: state.count + 1 };
    case 'decrement':
      return { count: state.count - 1 };
    default:
      return state;
  }
}

function Counter() {
  const [state, dispatch] = useReducer(reducer, initialState);

  return (
    <div>
      <p>Count: {state.count}</p>
      <button onClick={() => dispatch({ type: 'increment' })}>+</button>
      <button onClick={() => dispatch({ type: 'decrement' })}>-</button>
    </div>
  );
}
```

#### Cuando usarlo:

- Cuando el estado tiene logica o dependencias complejas.

- Cuando necesitas unificar las actualizaciones de estado mediante `dispatch`.

- Por escalabilidad, por ejemplo al usar estado global.

</details>

<details>
<summary>100. Como usar React.lazy y React.Suspense para cargar codigo de la aplicacion?</summary>

#### React

`React.lazy` y `React.Suspense` se utilizan para la **_carga dinamica de
componentes_** en React, lo que permite implementar **_division de codigo_**
(`code splitting`). Esto significa que partes del codigo se cargan solo cuando
son necesarias, mejorando asi el rendimiento de la aplicacion.

#### Como funciona:

1. `React.lazy()` permite cargar un componente de forma diferida.

2. `React.Suspense` se usa para envolver una parte del codigo que aun no esta
   cargada y permite mostrar contenido de reserva (por ejemplo, un loader)
   mientras se cargan los componentes.

#### Ejemplo:

1. **Carga dinamica del componente:**

- Primero crea un componente que se cargara de forma dinamica.

```jsx
// Componente cargado dinamicamente
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Wrapper con `React.Suspense`:**

- Ahora usa `React.Suspense` para mostrar un loader mientras el componente se
  carga.

```jsx
function App() {
  return (
    <div>
      <h1>Mi aplicacion</h1>

      {/* Wrapper para componentes cargados dinamicamente */}
      <React.Suspense fallback={<div>Cargando...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Descripcion:**

- `React.lazy()` recibe una funcion que importa dinamicamente un modulo.

- `React.Suspense` envuelve el componente que usa `React.lazy()` y muestra
  contenido de reserva (en este caso, el texto "Cargando...") hasta que el
  componente termine de cargarse.

#### Ventajas:

- Mejora el rendimiento cargando componentes solo cuando son necesarios.

- Reduce el tamano de la carga inicial, ya que partes de la aplicacion se
  cargan bajo demanda.

Este enfoque es especialmente util en aplicaciones grandes, donde se puede
dividir el codigo en partes para reducir el tiempo de carga de la pagina.

</details>

<details>
<summary>101. Que enfoques se utilizan para hacer solicitudes HTTP en React?</summary>

#### React

#### Enfoques para realizar solicitudes HTTP en React

React no tiene una API integrada para hacer solicitudes HTTP, pero puedes usar
bibliotecas de terceros o herramientas estandar de JavaScript. Estos son los
enfoques principales:

1. **Uso de Fetch API**

- Herramienta estandar para hacer solicitudes HTTP en JavaScript.

**Ejemplo:**

```jsx
import React, { useEffect, useState } from 'react';

function FetchExample() {
  const [data, setData] = useState([]);
  const [error, setError] = useState(null);

  useEffect(() => {
    fetch('https://jsonplaceholder.typicode.com/posts')
      .then(response => {
        if (!response.ok) {
          throw new Error('Network response was not ok');
        }
        return response.json();
      })
      .then(data => setData(data))
      .catch(error => setError(error.message));
  }, []);

  return (
    <div>
      {error ? (
        <p>Error: {error}</p>
      ) : (
        <ul>
          {data.map(post => (
            <li key={post.id}>{post.title}</li>
          ))}
        </ul>
      )}
    </div>
  );
}

export default FetchExample;
```

2. **Uso de Axios**

- Biblioteca para hacer solicitudes HTTP con una sintaxis mas simple y soporte
  integrado para interceptores.

**Ejemplo:**

```jsx
import React, { useEffect, useState } from 'react';
import axios from 'axios';

function AxiosExample() {
  const [data, setData] = useState([]);
  const [error, setError] = useState(null);

  useEffect(() => {
    axios
      .get('https://jsonplaceholder.typicode.com/posts')
      .then(response => setData(response.data))
      .catch(error => setError(error.message));
  }, []);

  return (
    <div>
      {error ? (
        <p>Error: {error}</p>
      ) : (
        <ul>
          {data.map(post => (
            <li key={post.id}>{post.title}</li>
          ))}
        </ul>
      )}
    </div>
  );
}

export default AxiosExample;
```

3. **React Query (TanStack Query)**

- Biblioteca para gestionar el estado de los datos obtenidos mediante
  solicitudes HTTP. Soporta cache, reintentos y actualizacion de datos.

**Ejemplo:**

```jsx
import React from 'react';
import { useQuery } from 'react-query';
import axios from 'axios';

function ReactQueryExample() {
  const { data, error, isLoading } = useQuery('posts', async () => {
    const response = await axios.get(
      'https://jsonplaceholder.typicode.com/posts'
    );
    return response.data;
  });

  if (isLoading) return <p>Loading...</p>;
  if (error) return <p>Error: {error.message}</p>;

  return (
    <ul>
      {data.map(post => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  );
}

export default ReactQueryExample;
```

4. **GraphQL (Apollo Client)**

- Para trabajar con una API GraphQL se usa Apollo Client.

**Ejemplo:**

```jsx
import React from 'react';
import { useQuery, gql } from '@apollo/client';

const GET_POSTS = gql`
  query GetPosts {
    posts {
      id
      title
    }
  }
`;

function ApolloExample() {
  const { loading, error, data } = useQuery(GET_POSTS);

  if (loading) return <p>Loading...</p>;
  if (error) return <p>Error: {error.message}</p>;

  return (
    <ul>
      {data.posts.map(post => (
        <li key={post.id}>{post.title}</li>
      ))}
    </ul>
  );
}

export default ApolloExample;
```

5. **Custom Hooks**

- Puedes crear tus propios hooks para reutilizar la logica de las solicitudes.

**Ejemplo:**

```jsx
import { useState, useEffect } from 'react';

function useFetch(url) {
  const [data, setData] = useState(null);
  const [error, setError] = useState(null);
  const [loading, setLoading] = useState(true);

  useEffect(() => {
    fetch(url)
      .then(response => response.json())
      .then(data => {
        setData(data);
        setLoading(false);
      })
      .catch(error => {
        setError(error.message);
        setLoading(false);
      });
  }, [url]);

  return { data, error, loading };
}

export default useFetch;
```

#### La eleccion del enfoque depende de tus necesidades:

- **Fetch API:** para solicitudes simples.

- **Axios:** si necesitas mas flexibilidad (interceptores, timeouts).

- **React Query:** para gestionar cache de datos.

- **GraphQL/Apollo Client:** si la API esta construida con GraphQL.

- **Custom Hooks:** para reutilizar la logica de las solicitudes.

</details>

<details>
<summary>102. Cual es la diferencia entre createElement y cloneElement?</summary>

#### React

| **Metodo**            | **Descripcion**                                                                             | **Uso principal**                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| `React.createElement` | Crea un nuevo elemento React. Recibe el tipo de elemento, props y elementos hijos como argumentos. | Se usa para crear elementos React desde cero, normalmente durante el renderizado JSX. |
| `React.cloneElement`  | Clona un elemento React existente, permitiendo cambiar sus props o elementos hijos.         | Se usa para crear copias modificadas de elementos React ya existentes.                  |

#### Ejemplos:

`React.createElement`

```jsx
const element = React.createElement(
  'div',
  { className: 'example' },
  'Hola, React!'
);
```

Resultado: se crea `<div class="example">Hola, React!</div>`.

`React.cloneElement`

```jsx
const originalElement = <button className="primary">Haz clic</button>;

const clonedElement = React.cloneElement(originalElement, {
  className: 'secondary',
});
```

Resultado: un clon `<button class="secondary">Haz clic</button>` con la clase
cambiada.

#### Diferencia:

- `createElement`: crea un elemento completamente nuevo.

- `cloneElement`: trabaja sobre un elemento ya existente, permitiendo modificar
  sus propiedades o contenido.

</details>

<details>
<summary>103. La funcion lazy admite exportaciones nombradas?</summary>

#### React

- No, la funcion `React.lazy` no admite exportaciones nombradas. Solo funciona
  con exportaciones por defecto. Si tienes un modulo con una exportacion
  nombrada y quieres usarlo con `React.lazy`, necesitas crear un wrapper que
  exporte el componente necesario por defecto.

#### Ejemplo de wrapper:

```jsx
// Exportacion nombrada
export const MyComponent = () => {
  return <div>Hello, World!</div>;
};

// Uso de React.lazy
const LazyComponent = React.lazy(() =>
  import('./MyComponent').then(module => ({ default: module.MyComponent }))
);

export default LazyComponent;
```

- Aqui indicamos explicitamente que `module.MyComponent` debe usarse como
  exportacion por defecto.

</details>

<details>
<summary>104. Cuales son las ventajas de React?</summary>

#### React

#### Ventajas de React

1. **Alto rendimiento**

- El uso de **_Virtual DOM_** minimiza las actualizaciones del **_DOM_** real,
  haciendo el renderizado mas rapido.

2. **Enfoque basado en componentes**

- La aplicacion se compone de **_componentes reutilizables_**, lo que simplifica
  el desarrollo y el mantenimiento.

3. **Flujo de datos unidireccional (Unidirectional Data Flow)**

- Los datos se transmiten hacia abajo en la jerarquia de componentes, lo que
  facilita el seguimiento de cambios de estado.

4. **Soporte para hooks**

- `useState`, `useEffect`, `useMemo` y otros permiten gestionar estado y efectos
  en componentes funcionales sin usar clases.

5. **Renderizado del lado del servidor (SSR) y generacion estatica (SSG)**

- Con Next.js se puede optimizar el SEO y mejorar el rendimiento de las
  aplicaciones.

6. **Flexibilidad y ecosistema**

- React puede usarse junto con **_Redux_**, **_Zustand_**, **_MobX_**,
  **_React Query_**, etc.

- Soporta **_React Native_** para crear aplicaciones moviles.

7. **Capacidades avanzadas de depuracion**

- **_React DevTools_** permite ver la estructura de componentes, el estado y las
  props en tiempo real.

8. **Comunidad activa y respaldo de Facebook**

- Gran variedad de bibliotecas y soluciones listas, y evolucion rapida del
  framework.

React es una herramienta flexible, productiva y moderna para el desarrollo de
aplicaciones web.

</details>

<details>
<summary>105. Cuales son las limitaciones de React?</summary>

#### React

1. **Gran cantidad de rerenders:** Si los componentes no estan bien optimizados,
   esto puede provocar rerenders excesivos y empeorar el rendimiento.

2. **Necesidad de gestionar el estado:** Sin una gestion correcta del estado, la
   aplicacion puede volverse dificil de mantener.

3. **Flujo de datos unidireccional:** Los datos fluyen en una sola direccion,
   lo que puede complicar su transmision a traves de varios niveles de
   componentes.

4. **Reactividad:** React actualiza el DOM a traves del Virtual DOM, pero esto
   puede ser ineficiente en aplicaciones grandes y muy dinamicas.

5. **Dependencia de JavaScript:** Tiene mal soporte sin JavaScript en el lado
   del cliente.

6. **Curva de aprendizaje para principiantes:** Aunque los conceptos de React
   son bastante simples, dominar correctamente hooks, contextos y optimizacion
   puede ser dificil.

7. **Herramientas de terceros:** Aunque existe una gran cantidad de
   herramientas, integrarlas puede ser dificil en proyectos grandes.

</details>

<details>
<summary>106. Para que servia el metodo registerServiceWorker() en React?</summary>

#### React

`registerServiceWorker()` se utilizaba para registrar un Service Worker en
Create React App (antes de que se eliminara de CRA en la version 4).

#### Proposito:

- Cacheo de recursos para modo offline

- Aceleracion de la carga de la aplicacion

- Actualizacion en segundo plano de recursos

#### Ejemplo de uso (antes de CRA 4):

```javascript
import { register } from './serviceWorker';

register();
```

- Despues de eliminarse de CRA, el Service Worker debe configurarse manualmente
  mediante `navigator.serviceWorker.register()`.

- En **React 19** no existe `registerServiceWorker()` integrado, ya que fue
  eliminado mucho antes. Si necesitas un Service Worker, debes registrarlo
  manualmente.

Conclusion: en React 19 este metodo ya no es actual, y el Service Worker debe
configurarse manualmente.

</details>

<details>
<summary>107. Que son los eventos sinteticos (SyntheticEvent) en React?</summary>

#### React

- **SyntheticEvent** en React es un envoltorio sobre los eventos nativos del
  navegador que proporciona compatibilidad entre navegadores y mejora el
  rendimiento.

#### Caracteristicas de SyntheticEvent:

- Funciona de la misma manera en todos los navegadores.

- Utiliza event pooling, lo que evita mantener objetos innecesarios en memoria.

- Todos los eventos estan normalizados y tienen las mismas propiedades sin
  importar el navegador.

#### Ejemplo de uso:

```jsx
function MyComponent() {
  const handleClick = event => {
    console.log(event.type); // "click"
    console.log(event.nativeEvent); // Evento original del navegador
  };

  return <button onClick={handleClick}>Haz clic</button>;
}
```

#### Metodos principales:

- `event.preventDefault()`: evita el comportamiento por defecto.

- `event.stopPropagation()`: detiene la propagacion del evento.

- `event.persist()`: desactiva el pooling para que el evento no se reinicie.

</details>

<details>
<summary>108. Que tecnicas se usan para optimizar el rendimiento en React?</summary>

#### React

#### Tecnicas de optimizacion del rendimiento en React:

1. **Memoizacion de componentes**

- Usa `React.memo()` para evitar rerenders innecesarios.
- `useMemo()` para cachear calculos.
- `useCallback()` para mantener la estabilidad de funciones.

2. **Optimizacion del rerender**

- Evita estados (`useState`) y props innecesarios.
- Usa `shouldComponentUpdate` y `React.PureComponent` en componentes de clase.
- Optimiza el contexto (`Context API`): no pases valores innecesarios.
- Usa selectores (`Reselect`, `Zustand`, `Jotai`) para minimizar
  actualizaciones.

3. **Virtualizacion de listas**

- `react-window`, `react-virtualized` para mostrar solo los elementos visibles.

4. **Cacheo y debounce**

- `useMemo()` y `useCallback()` para calculos costosos.
- Debounce (`lodash.debounce`) o throttling (`lodash.throttle`) para la entrada
  del usuario.

5. **Carga diferida (Lazy Loading)**

- `React.lazy()` + `Suspense` para division de codigo.
- Importacion dinamica de modulos (`import()`).

6. **Evitar efectos innecesarios en useEffect**

- Pasa correctamente las dependencias.
- Usa `useRef` para guardar valores sin rerenderizar.

7. **Optimizacion de imagenes**

- Usa `next/image` en Next.js.
- Optimiza tamanos y formatos (`WebP`, `AVIF`).

8. **Optimizacion de React Router**

- Usa `React.lazy()` para paginas.
- Evita rerenders innecesarios actualizando correctamente el estado.

9. **Separacion del estado**

- Usa estado local donde no haga falta uno global.
- Lleva cambios globales a `Redux/Zustand/Recoil`.

10. **Uso de Web Workers**

- Para calculos pesados, evitando bloquear el hilo principal.

</details>

<details>
<summary>109. Es posible usar async/await en React?</summary>

#### React

- Si, se puede usar `async/await` en React, pero hay algunos puntos importantes
  a tener en cuenta:

1. **Uso dentro de componentes:** `async/await` no debe usarse directamente en
   los propios componentes ni en metodos del ciclo de vida como `render()`. Sin
   embargo, si puede usarse en manejadores de eventos o en hooks como
   `useEffect`.

2. **Herramientas para solicitudes asincronas:**

- Usa `async/await` dentro de funciones llamadas desde hooks, por ejemplo:

```jsx
useEffect(() => {
  const fetchData = async () => {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  };
  fetchData();
}, []);
```

3. **Manejo de errores:** no olvides usar `try/catch` para manejar errores en
   solicitudes asincronas:

```jsx
const fetchData = async () => {
  try {
    const response = await fetch('https://api.example.com');
    const data = await response.json();
    setData(data);
  } catch (error) {
    console.error('Error fetching data:', error);
  }
};
```

Asi pues, `async/await` se puede y se debe usar para operaciones asincronas en
React, pero hay que organizar correctamente su uso dentro de los componentes.

</details>

<details>
<summary>110. Cual es la historia de la evolucion de React?</summary>

#### React

A continuacion, una breve historia de la evolucion de React:

1. **2011**

- React fue creado en Facebook para necesidades internas. Lo desarrollo el
  ingeniero Jordan Walke para resolver el problema de actualizar interfaces de
  manera eficiente.

2. **2013**

- Facebook libero React como biblioteca open source. Al principio la comunidad
  la recibio con escepticismo debido al uso de JSX, que parecia poco habitual.

3. **2015**

- Se lanzo React 0.14: React y ReactDOM se separaron, lo que hizo la biblioteca
  mas modular.

- Facebook presento React Native, que permitio crear aplicaciones moviles
  nativas con React.

4. **2016**

- Se lanzo React 15. Las actualizaciones principales se centraron en mejorar el
  rendimiento mediante un nuevo motor de renderizado.

5. **2017**

- Se lanzo React 16 (Fiber). Fiber se convirtio en una nueva arquitectura que
  aporto mejor rendimiento y soporte para renderizado asincrono.

- Se agrego soporte para portales y **Error Boundaries**.

6. **2018**

- Facebook presento React Hooks, que permitieron usar estado y metodos del ciclo
  de vida en componentes funcionales. Esto cambio de forma radical la manera de
  crear componentes.

7. **2019**

- Se lanzo React 16.8 con soporte oficial para hooks.

- Se mejoro la eficiencia de Concurrent Mode (experimental).

8. **2020**

- Se lanzo React 17. El objetivo principal fue simplificar la actualizacion
  gradual de React en proyectos grandes.

- Se agrego soporte para herramientas modernas y nuevas capacidades para
  trabajar con JSX.

9. **2022**

- Se lanzo React 18. Las novedades principales fueron Concurrent Rendering y
  nuevas APIs como `useTransition` y `useDeferredValue`, que mejoran el
  rendimiento en aplicaciones dinamicas.

10. **2024**

- Se lanzo React 19.

- Se actualizo el renderizado del lado del servidor (RSC).

- Soporte para la nueva funcion `use`.

- Mejora del sistema de formularios, del manejo de errores de renderizado y del
  uso de JSX sin `import React`.

- React Compiler actualizado para optimizar automaticamente el rendimiento.

#### Principales cambios a lo largo de su evolucion:

- De componentes de clase a componentes funcionales con hooks.

- Soporte para renderizado del lado del servidor (SSR).

- Concurrent Mode para actualizaciones de interfaz mas fluidas.

- Integracion de React con el desarrollo movil mediante React Native.

React ha seguido siendo popular gracias a su alto rendimiento, facilidad de uso
y respaldo continuo de Facebook.

</details>

<details>
<summary>111. Que novedades se agregaron en React 19?</summary>

#### React

React 19 introdujo una serie de actualizaciones importantes orientadas a
mejorar el rendimiento y la comodidad del desarrollo. Estas son las novedades
principales:

1. **Nuevo sistema de renderizado:** se introdujo renderizado asincrono, lo que
   permite a React gestionar mejor las actualizaciones de la interfaz y mejorar
   la interaccion con el usuario.

2. **React Compiler:** el nuevo compilador optimiza automaticamente los
   rerenders, reduciendo actualizaciones innecesarias y aumentando el
   rendimiento de las aplicaciones.

3. **Actions API:** es un nuevo enfoque para gestionar estado y mutaciones de
   datos en el servidor, simplificando el manejo de efectos secundarios y de
   solicitudes de datos.

4. **Mecanica mejorada de Suspense:** ofrece a los desarrolladores un control
   mas fino sobre la carga asincrona de datos, facilitando la hidratacion de
   componentes y los estados fallback.

5. **Hook `use`:** un nuevo hook que simplifica el trabajo con datos asincronos
   y mejora el soporte para componentes de servidor.

6. **Soporte nativo para metatags:** ahora `meta`, `title`, `link` y otras
   metatags se admiten sin bibliotecas adicionales, lo que simplifica la
   gestion de SEO y recursos.

- Estas novedades hacen que React 19 sea una herramienta mas potente y comoda
  para los desarrolladores, mejorando tanto el rendimiento de las aplicaciones
  como la experiencia de desarrollo.

</details>

<details>
<summary>112. Que recomiendan usar los desarrolladores de React despues de que Create React App quedara obsoleto?</summary>

#### React

Despues de que Create React App dejara de tener soporte en febrero de 2025, se
recomienda a los desarrolladores usar frameworks modernos para crear nuevas
aplicaciones React. Estos frameworks soportan renderizado del lado del cliente
(CSR) y aplicaciones de una sola pagina (SPA), que pueden desplegarse en CDN o
en servicios de hosting estatico sin necesidad de un servidor propio.

#### Frameworks recomendados:

1. **Next.js:** ofrece capacidades potentes, como renderizado del lado del
   servidor y generacion de sitios estaticos, proporcionando alto rendimiento y
   optimizacion SEO.

2. **React Router:** permite crear SPA con enrutamiento dinamico, facilitando
   la gestion de la navegacion en la aplicacion.

3. **Expo:** simplifica el desarrollo de aplicaciones React Native,
   proporcionando herramientas para crear aplicaciones moviles multiplataforma
   con JavaScript y React.

</details>

<details>
<summary>113. Como funciona el hook useDeferredValue en React?</summary>

#### React

`useDeferredValue` es un hook de React que aparecio en React 18 como parte de
Concurrent Mode. Permite aplazar la actualizacion de ciertos valores (estado o
props), reduciendo su prioridad y dando a React la posibilidad de actualizar la
interfaz con tareas mas importantes primero.

Esto es muy util si un valor cambia con frecuencia y actualizar la interfaz en
cada cambio consume muchos recursos.

##### Para que se usa `useDeferredValue`?

- Para evitar retrasos y bloqueos en aplicaciones complejas donde la velocidad
  de respuesta de la interfaz es importante.
- Para mejorar la experiencia del usuario, especialmente cuando cambian muchos
  datos (busqueda, filtrado, renderizado de listas grandes).
- Para garantizar transiciones y animaciones mas fluidas.

##### Como funciona?

El hook `useDeferredValue` recibe un valor y devuelve su version diferida:

```jsx
const deferredValue = useDeferredValue(value);
```

- React actualiza de inmediato los cambios criticos (prioritarios).
- El valor diferido (`deferredValue`) se actualiza de forma asincrona despues de
  que React procese las tareas mas urgentes.
- Si las actualizaciones del valor principal ocurren demasiado rapido, React
  puede omitir algunos valores intermedios e ir directamente al ultimo.

##### Ejemplo de uso:

Imaginemos un componente con un campo de busqueda y una lista grande que debe
filtrarse mientras el usuario escribe.

###### Sin usar `useDeferredValue`:

```jsx
import { useState, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(query));
  }, [items, query]);

  return (
    <>
      <input
        value={query}
        onChange={e => setQuery(e.target.value)}
        placeholder="Buscar..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

Esto puede causar ralentizaciones si la lista es muy grande, ya que React
recalcula inmediatamente los resultados filtrados con cada caracter introducido.

###### Usando `useDeferredValue`:

```jsx
import { useState, useDeferredValue, useMemo } from 'react';

function SearchList({ items }) {
  const [query, setQuery] = useState('');
  const deferredQuery = useDeferredValue(query);

  const filteredItems = useMemo(() => {
    return items.filter(item => item.includes(deferredQuery));
  }, [items, deferredQuery]);

  return (
    <>
      <input
        value={query}
        onChange={e => setQuery(e.target.value)}
        placeholder="Buscar..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

En esta variante:

- La entrada del usuario sigue siendo inmediata y fluida.
- El filtrado de la lista se realiza de forma asincrona (despues de que el
  usuario deje de escribir o cuando disminuya la intensidad de los cambios).
- Como resultado, la interfaz sigue respondiendo bien.

##### Caracteristicas de funcionamiento:

- `useDeferredValue` no fija un tiempo de retraso concreto (a diferencia de
  debounce). Permite a React determinar automaticamente el momento de
  actualizacion segun la carga de la interfaz.
- El valor obtenido con `useDeferredValue` puede ir "por detras" del estado
  principal, y eso debe tenerse en cuenta en la logica de la aplicacion.

##### Ventajas de uso:

- Reduce la carga del procesador durante interacciones activas.
- Mantiene un FPS estable y una interfaz fluida.
- Hace que la UX sea mas comoda y predecible, especialmente en aplicaciones
  grandes y complejas.

##### Cuando conviene usar `useDeferredValue`?

- Listas con una gran cantidad de elementos.
- Formularios con filtrado activo y autocompletado.
- Todos los casos en los que actualizaciones frecuentes de la interfaz pueden
  generar una mala experiencia para el usuario.

</details>
