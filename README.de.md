**Read in other languages: [English 🇺🇸](README.en.md),
[Polska 🇵🇱](README.pl.md), [German 🇩🇪](README.de.md), [French 🇫🇷](README.fr.md),
[Spanish 🇪🇸](README.es.md), [Українська 🇺🇦](README.md).**

<h1>
  React <img src="./assets/react.svg" width="40" height="40" />
</h1>

<h2>Die beliebtesten Fragen und Antworten im React-Vorstellungsgespraech</h2>

<details>
<summary>1. Was ist React?</summary>

#### React

React ist eine JavaScript-Bibliothek zum Erstellen von Benutzeroberflaechen. Die
wichtigsten Eigenschaften:

1. **Komponentenbasierter Ansatz:** Die UI wird in einzelne Komponenten
   aufgeteilt, die wiederverwendet werden koennen.

2. **Virtual DOM:** Ermoeglicht effiziente Aktualisierungen der
   Benutzeroberflaeche, indem Manipulationen am echten DOM minimiert werden.

3. **Deklarativitaet:** Du beschreibst, wie die UI in einem bestimmten Zustand
   aussehen soll, und React sorgt fuer die entsprechende Darstellung.

4. **Einseitiger Datenfluss:** Daten werden ueber Props von oben nach unten
   weitergegeben, was die Kontrolle ueber den Zustand vereinfacht.

React wurde von Facebook entwickelt und wird breit fuer die Entwicklung von SPA
(Single Page Applications) eingesetzt.

</details>

<details>
<summary>2. Zaehlen Sie die Besonderheiten von React auf.</summary>

#### React

1. **Komponentenbasierter Ansatz:** Der Code ist in wiederverwendbare,
   voneinander unabhaengige Komponenten aufgeteilt.

2. **Virtuelles DOM:** Schnelle Aktualisierung der Benutzeroberflaeche ohne
   direkte Manipulation des DOM.

3. **Einseitiger Datenfluss:** Daten werden von Elternkomponenten ueber Props an
   Kindkomponenten weitergegeben.

4. **JSX:** Eine Syntaxerweiterung von JavaScript, mit der UI in Form von
   XML-aehnlichem Code geschrieben werden kann.

5. **State und Lebenszyklus:** Komponenten koennen ihren eigenen Zustand
   speichern und verwalten.

6. **React Hooks:** Erweitern funktionale Komponenten um State und Side Effects.

7. **Oekosystem:** Unterstuetzt Bibliotheken wie React Router oder Redux zur
   Erweiterung der Funktionalitaet.

8. **SEO-freundlich, etwa mit Next.js:** Serverseitiges Rendering verbessert die
   Indexierung.

9. **Mobile Entwicklung:** React Native ermoeglicht die Erstellung mobiler
   Anwendungen auf Basis von React.

10. **Open Source:** Aktive Unterstuetzung durch die Community.

</details>

<details>
<summary>3. Was sind die wichtigsten Funktionen von React?</summary>

#### React

#### Die wichtigsten Funktionen von React:

1. **Deklarativer Ansatz:** React erlaubt es, interaktive Oberflaechen zu
   erstellen, indem beschrieben wird, wie sie aussehen sollen, waehrend die
   Bibliothek die DOM-Aktualisierung selbst optimiert.

2. **Komponentenstruktur:** Eine Anwendung wird aus unabhaengigen,
   wiederverwendbaren Komponenten aufgebaut, was Entwicklung, Tests und Wartung
   vereinfacht.

3. **Virtuelles DOM:** React nutzt das Virtual DOM fuer effiziente
   Aktualisierungen des echten DOM, was die Performance deutlich verbessert.

4. **Einseitiger Datenfluss:** Daten werden ueber Props von Eltern- an
   Kindkomponenten weitergegeben, was das State-Management vereinfacht.

5. **Hooks:** Erlauben die Nutzung von State und Lebenszykluslogik in
   funktionalen Komponenten.

6. **JSX:** Eine Erweiterung von JavaScript zur Beschreibung der UI in einer
   HTML-aehnlichen Syntax.

7. **React Native:** Die Moeglichkeit, native mobile Anwendungen nach denselben
   Prinzipien wie Webanwendungen zu entwickeln.

8. **Oekosystem:** Eine grosse Auswahl an Bibliotheken und Werkzeugen wie React
   Router, Redux und Context API.

9. **Unterstuetzung fuer serverseitiges Rendering (SSR):** Ermoeglicht bessere
   SEO-Werte und schnelleres initiales Laden von Seiten.

10. **State-Management:** Mit `useState`, Context API, Redux oder anderen
    Bibliotheken.

Diese Funktionen machen React zu einer leistungsstarken und flexiblen Bibliothek
fuer moderne Anwendungen.

</details>

<details>
<summary>4. Was sind die wichtigsten Vorteile der Verwendung von React?</summary>

#### React

#### Wichtige Vorteile der Verwendung von React

1. **Geschwindigkeit:** Dank des Virtual DOM minimiert React Interaktionen mit
   dem echten DOM, was die Performance verbessert.

2. **Komponentenbasierter Ansatz:** Der Code wird in wiederverwendbare
   Komponenten aufgeteilt, was Entwicklung und Wartung vereinfacht.

3. **Einseitige Datenweitergabe:** Der Datenfluss in React erfolgt nur in eine
   Richtung, naemlich von oben nach unten, was das Debugging erleichtert.

4. **Grosse Community:** React verfuegt ueber ein riesiges Oekosystem aus
   Bibliotheken, Werkzeugen und Erweiterungen.

5. **Kompatibilitaet mit mobiler Entwicklung:** Mit React Native lassen sich
   plattformuebergreifende mobile Apps entwickeln.

6. **JSX:** Eine Syntax, die das Schreiben von JavaScript zusammen mit
   HTML-aehnlichem Markup erlaubt und die Lesbarkeit des Codes verbessert.

7. **Hooks-Unterstuetzung:** Vereinfacht die Arbeit mit State und Lebenszyklus
   in funktionalen Komponenten.

8. **SEO-Freundlichkeit:** Serverseitiges Rendering mit Werkzeugen wie Next.js
   verbessert die Suchmaschinenoptimierung.

9. **Flexibilitaet:** React kann ohne groessere Codeaenderungen in nahezu jedes
   Projekt oder Framework integriert werden.

10. **React DevTools:** Ein Debugging-Werkzeug, mit dem Komponenten und
    Anwendungszustand bequem analysiert werden koennen.

</details>

<details>
<summary>5. Was ist JSX?</summary>

#### React

**JSX (JavaScript XML)** ist eine Syntax, mit der UI-Strukturen in Form von
XML-aehnlichem Code innerhalb von JavaScript geschrieben werden koennen. JSX ist
eine Erweiterung von JavaScript und wird in React genutzt, um zu beschreiben,
wie eine Benutzeroberflaeche aussieht.

#### Die wichtigsten Besonderheiten von JSX:

1. **XML-aehnliche Syntax:** Sie erinnert an HTML, wird jedoch in JavaScript
   verwendet.

```jsx
const element = Hello, world!;
```

2. **Eingebettetes JavaScript:** JavaScript-Code kann in geschweiften Klammern
   `{}` geschrieben werden.

```jsx
const name = 'Alice';
const element = Hello, {name}!;
```

3. **Transformation:** JSX wird mit Werkzeugen wie Babel in normales JavaScript
   kompiliert.

```jsx
const element = Hello;
// Wird umgewandelt in:
const element = React.createElement('h1', null, 'Hello');
```

4. **Attribute:** Sie werden wie in HTML verwendet, aber statt `class` schreibt
   man `className`, und statt `for` verwendet man `htmlFor`.

```jsx
const input = ;
```

5. **JSX gibt einen Elementbaum zurueck:** Ein JSX-Ausdruck kann nur ein
   Wurzelelement zurueckgeben. Zum Gruppieren kann `<React.Fragment>` oder `<>`
   verwendet werden.

```jsx
return <>Title Description</>;
```

#### Vorteile:

- Bequeme Erstellung von UI-Komponenten.
- Klare und gut lesbare Syntax.
- Enge Integration mit JavaScript-Logik.

JSX ist in React nicht verpflichtend, wird aber wegen seiner Bequemlichkeit und
Flexibilitaet sehr haeufig verwendet.

</details>

<details>
<summary>6. Was ist der Unterschied zwischen State und Props?</summary>

#### React

#### Unterschied zwischen State und Props

| Kriterium                 | State                                                      | Props                                                     |
| ------------------------- | ---------------------------------------------------------- | --------------------------------------------------------- |
| **Zweck**                 | Speichert den internen Zustand einer Komponente.           | Uebergibt Daten von einer Eltern- an eine Kindkomponente. |
| **Veraenderbarkeit**      | Kann innerhalb der Komponente geaendert werden.            | Ist unveraenderlich, also read-only.                      |
| **Verfuegbarkeit**        | Nur in der Komponente verfuegbar, in der er definiert ist. | In der Kindkomponente ueber Attribute verfuegbar.         |
| **Initialisierung**       | Wird per `useState` oder im Konstruktor gesetzt.           | Wird von der Elternkomponente festgelegt.                 |
| **Verwendungsbereich**    | Fuer dynamische Daten, die sich aendern koennen.           | Fuer die Uebergabe fester oder dynamischer Daten.         |
| **Wer kontrolliert ihn?** | Die Komponente, in der der State definiert ist.            | Die Elternkomponente.                                     |

</details>

<details>
<summary>7. Was ist der Unterschied zwischen einem Element und einer Komponente?</summary>

#### React

#### Unterschied zwischen einem Element und einer Komponente in React:

| Kriterium                   | Element                                               | Komponente                                                                                                |
| --------------------------- | ----------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| **Definition**              | Ein Objekt, das beschreibt, wie die UI aussehen soll. | Eine Funktion oder Klasse, die React-Elemente zurueckgibt.                                                |
| **Typ**                     | Unveraenderlich, also immutable.                      | Wiederverwendbar und kann einen eigenen State besitzen.                                                   |
| **Erstellungssyntax**       | `React.createElement` oder JSX wie `<div />`.         | Funktion oder Klasse wie `function MyComponent() {}` oder `class MyComponent extends React.Component {}`. |
| **Zweck**                   | Repraesentiert einen einzelnen Knoten im DOM.         | Kapselt Logik und Struktur der Benutzeroberflaeche.                                                       |
| **Verwendungsmoeglichkeit** | Wird fuer die grundlegende Erstellung von UI genutzt. | Wird fuer komplexere Strukturen mit eigener Logik verwendet.                                              |
| **Beispiel**                | `<h1>Hello</h1>`                                      | `function Hello() { return <h1>Hello</h1>; }`                                                             |

Ein Element ist ein "Baustein", waehrend eine Komponente ein "Baukasten" fuer
komplexe Benutzeroberflaechen ist.

</details>

<details>
<summary>8. Wie erstellt man Komponenten in React?</summary>

#### React

#### In React lassen sich Komponenten auf zwei Arten erstellen:

1. **Funktionale Komponente:** Das ist eine einfache Funktion, die
   React-Elemente zurueckgibt.

```jsx
function Greeting(props) {
  return Hello, {props.name}!;
}

// Verwendung:
;
```

2. **Klassenkomponente:** Das ist eine Klasse, die von `React.Component` erbt
   und zwingend eine `render`-Methode besitzt.

```jsx
class Greeting extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Verwendung:
;
```

#### Unterschiede:

- Funktionale Komponenten sind einfacher und eignen sich besser fuer Komponenten
  ohne eigenen State.

- Klassenkomponenten werden fuer komplexere Komponenten mit eigenem State oder
  Lebenszyklusmethoden verwendet.

**Hinweis:** Der moderne Ansatz setzt auf funktionale Komponenten mit Hooks
anstelle von Klassenkomponenten.

</details>

<details>
<summary>9. Was ist State in React?</summary>

#### React

**State** in React ist ein Objekt, das zum Speichern von Daten verwendet wird,
die sich im Laufe der Zeit aendern koennen und das Rendering einer Komponente
beeinflussen. State ermoeglicht React-Komponenten, dynamisch auf Ereignisse,
Benutzereingaben und andere Aenderungen zu reagieren.

#### Eigenschaften von State:

1. **Lokal fuer die Komponente:** State ist nur in der Komponente verfuegbar, in
   der er definiert ist.

2. **Aendert sich asynchron:** React fasst `setState`-Aufrufe zusammen, um das
   Rendering zu optimieren.

3. **Wird im Konstruktor initialisiert** bei Klassenkomponenten oder ueber
   `useState` bei funktionalen Komponenten.

#### In Klassenkomponenten:

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

#### In funktionalen Komponenten mit dem Hook `useState`:

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

#### Die wichtigsten Unterschiede zwischen State und Props:

- **State** ist lokal fuer die Komponente und kann sich aendern.

- **Props** werden von aussen uebergeben und sind unveraenderlich.

</details>

<details>
<summary>10. Was sind Props in React?</summary>

#### React

**Props** in React sind ein Objekt, das Daten enthaelt, die von einer
Elternkomponente an eine Kindkomponente uebergeben werden. Sie dienen der
Konfiguration von Komponenten und sind unveraenderlich.

#### Eigenschaften von Props:

1. **Werden von oben nach unten weitergegeben** im Sinne des unidirectional data
   flow, also von der Elternkomponente zur Kindkomponente.

2. **Unveraenderlich:** Eine Komponente kann empfangene Props nicht veraendern.

3. **Dynamisch:** Der Wert von Props kann sich aendern, wenn sich die Daten in
   der Elternkomponente aendern.

#### Verwendung von Props:

1. **In einer funktionalen Komponente:**

```jsx
function Welcome(props) {
  return Hello, {props.name}!;
}

// Verwendung:
;
```

2. **In einer Klassenkomponente:**

```jsx
class Welcome extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Verwendung:
;
```

#### Uebergabe von Props:

```jsx
function App() {
  return (

  );
}
```

**Ergebnis:**

```bash
Hello, Alice!
Hello, Bob!
```

#### Destrukturierung von Props:

```jsx
function Welcome({ name }) {
  return Hello, {name}!;
}
```

#### Standardwerte fuer Props:

```jsx
function Welcome({ name = 'Guest' }) {
  return Hello, {name}!;
}

// Verwendung:
; // Gibt aus: Hello, Guest!
```

Props verleihen React-Komponenten Flexibilitaet und Wiederverwendbarkeit.

</details>

<details>
<summary>11. Wozu dient das Attribut key beim Rendern von Listen?</summary>

#### React

Das Attribut `key` wird verwendet, um Elemente in Listen waehrend des Renderns
zu identifizieren.

#### Zweck:

1. **_Optimierung von Updates:_** React verwendet `key`, um die
   Benutzeroberflaeche effizient zu aktualisieren und schnell zu bestimmen,
   welche Elemente geaendert, hinzugefuegt oder entfernt werden muessen.

2. **_Vermeidung unnoetiger Renderings:_** `key` hilft dabei, erneutes Rendern
   unveraenderter Elemente zu vermeiden.

3. **_Erhalt des Komponentenstatus:_** Wenn ein Listenelement beispielsweise ein
   Formular enthaelt, ermoeglicht `key`, dessen Zustand zwischen Updates zu
   bewahren.

#### Richtige Verwendung:

- Der Wert von `key` muss unter gleichrangigen Elementen eindeutig sein.

- Am besten eignen sich stabile Identifikatoren, zum Beispiel eine `id` aus der
  Datenbank.

- Es wird nicht empfohlen, den Index eines Arrays als `key` zu verwenden, da
  dies bei einer Aenderung der Reihenfolge zu Fehlern fuehren kann.

```jsx
const items = ['Apple', 'Banana', 'Cherry'];
return (

    {items.map((item, index) => (
      {item} // Eindeutiger key fuer jedes Element
    ))}

);
```

</details>

<details>
<summary>12. Wie werden Daten zwischen Komponenten in React weitergegeben?</summary>

#### React

In React werden Daten zwischen Komponenten entlang der Hierarchie wie folgt
weitergegeben:

#### Datenweitergabe nach unten, also von der Eltern- zur Kindkomponente

Fuer die Weitergabe von Daten nach unten werden Props verwendet. Die
Elternkomponente uebergibt Werte oder Funktionen ueber Attribute an die
Kindkomponente.

**Beispiel:**

```jsx
function ParentComponent() {
  const data = 'Hello from Parent';

  return;
}

function ChildComponent({ message }) {
  return { message };
}
```

`message` uebergibt den Wert `data` an die Kindkomponente `ChildComponent`.

In der Kindkomponente erfolgt der Zugriff auf Props ueber die Funktionsparameter
oder ueber `this.props` in einer Klassenkomponente.

#### Datenweitergabe nach oben, also von der Kind- zur Elternkomponente

Daten werden nach oben ueber Callback-Funktionen weitergegeben. Die
Elternkomponente uebergibt eine Funktion an die Kindkomponente, und diese ruft
sie mit den benoetigten Daten auf.

**Beispiel:**

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

Die Elternkomponente uebergibt die Funktion `handleData` ueber das Prop
`sendData`.

Die Kindkomponente ruft `sendData` auf und uebergibt dabei den Wert `data`.

#### Alternative Ansaetze fuer komplexe Anwendungen:

1. **Kontext, also Context API:**

Zur Weitergabe von Daten tief in der Hierarchie ohne Props.

Geeignet fuer globalen State, zum Beispiel fuer ein Theme oder die
Oberflaechensprache.

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

2. **State-Manager wie Redux, Zustand oder MobX:** Fuer die Weitergabe von Daten
   in grossen Anwendungen ueber einen zentralen globalen State.

3. **Custom Hooks:** Werden verwendet, um Logik zwischen Komponenten gemeinsam
   zu nutzen.

</details>

<details>
<summary>13. Warum verwendet React className statt des Attributs class?</summary>

#### React

In React wird `className` anstelle von `class` verwendet, weil `class` ein
reserviertes Schluesselwort in JavaScript ist.

#### Gruende:

1. **Vermeidung von Konflikten:** `class` wird in JavaScript zur Definition von
   Klassen verwendet, zum Beispiel `class MyComponent {}`, was sonst zu
   Syntaxproblemen fuehren koennte.

2. **Kompatibilitaet mit JSX:** Da JSX eine Syntaxerweiterung von JavaScript
   ist, hilft `className`, Mehrdeutigkeiten zu vermeiden.

3. **Direkte Abbildung in `document.createElement`:** React wandelt JSX in
   `React.createElement`-Aufrufe um, und zum Setzen von Klassen in DOM-Elementen
   wird `className` verwendet.

#### Beispiel:

```jsx
// Korrekte Variante in React

Hello;

// Falsche Variante, fuehrt zu einem Syntaxfehler

Hello;
```

Das ist ein React-Standard, der Stabilitaet und Konsistenz im Code
gewahrleistet.

</details>

<details>
<summary>14. Welche Besonderheiten gelten bei der Benennung von React-Komponenten?</summary>

#### React

In React gibt es mehrere wichtige Regeln und Besonderheiten bei der Benennung
von Komponenten:

1. **Grossbuchstaben fuer Komponenten:** Komponentennamen muessen mit einem
   Grossbuchstaben beginnen. Nur so kann React Komponenten von normalen
   HTML-Elementen unterscheiden.

Zum Beispiel:

- Richtig: `<MyComponent />`
- Falsch: `<myComponent />`

2. **CamelCase:** Es wird empfohlen, fuer Komponentennamen CamelCase zu
   verwenden. Das bedeutet, dass jedes neue Wort mit einem Grossbuchstaben
   beginnt:

- `MyComponent`
- `UserProfile`

3. **Namen sollten nicht mit HTML-Elementen uebereinstimmen:** Verwende keine
   Komponentennamen, die identisch mit HTML-Tags wie `div`, `span` oder `button`
   sind. Das kann zu Konflikten und unerwartetem Verhalten fuehren:

- Richtig: `<CustomButton />`
- Falsch: `<button />`, da dies in React als normales HTML-Element behandelt
  wird

4. **Sonderzeichen vermeiden:** Verwende keine Sonderzeichen in
   Komponentennamen, zum Beispiel Leerzeichen, Bindestriche oder Unterstriche,
   da dies zu Syntaxfehlern fuehren kann:

- Richtig: `MyComponent`
- Falsch: `my_component`, `my-component`

5. **Funktionale Komponenten versus Klassen:** Wenn du Klassen fuer Komponenten
   verwendest, muessen auch diese Namen mit einem Grossbuchstaben beginnen:

- `class MyComponent extends React.Component {}`

Die Einhaltung dieser Regeln hilft dabei, korrekte Funktion und gute
Verstaendlichkeit des Codes sicherzustellen.

</details>

<details>
<summary>15. Wie schreibt man Kommentare in React?</summary>

#### React

In React werden Kommentare genauso wie in JavaScript geschrieben, allerdings
gibt es einige Besonderheiten bei JSX.

1. **Kommentare in JavaScript, also ausserhalb von JSX**

```javascript
// Einzeiliger Kommentar

/*
Mehrzeiliger Kommentar
*/
```

2. **Kommentare innerhalb von JSX**

- In JSX muss eine besondere Syntax verwendet werden, da JSX Teil von JavaScript
  ist.

- Kommentare in JSX muessen innerhalb von geschweiften Klammern `{}` stehen:

```jsx
function MyComponent() {
  return (

      {/_ Das ist ein Kommentar innerhalb von JSX _/}
      Hello, world!

  );
}
```

- Kommentare in JSX muessen die Form `{/* Kommentar */}` haben, sonst fuehren
  sie zu Fehlern.

- Sie koennen nur innerhalb von JSX-Ausdruecken verwendet werden.

3. **Kommentare in Funktionen und Methoden**

- Fuer Kommentare innerhalb von Funktionen oder Methoden koennen normale
  JavaScript-Kommentare verwendet werden:

```jsx
function MyComponent() {
  // Hier rendern wir die Komponente
  return Hello, world!;
}
```

#### Fazit:

- In JSX verwende `{/* Kommentar */}`.

- In normalem JavaScript stehen `//` fuer einzeilige und `/* ... */` fuer
  mehrzeilige Kommentare.

</details>

<details>
<summary>16. Was ist das Virtual DOM in React?</summary>

#### React

**Virtual DOM** ist eine virtuelle Darstellung des echten DOM, die React fuer
effiziente Aktualisierungen der Benutzeroberflaeche verwendet.

#### Wie es in React funktioniert:

1. **Rendern im Virtual DOM:** Wenn sich State oder Props einer Komponente
   aendern, aktualisiert React das Virtual DOM.

2. **Diffing:** React vergleicht das neue Virtual DOM mit der vorherigen Version
   und ermittelt die minimale Menge an Aenderungen.

3. **Aktualisierung des echten DOM:** Die erkannten Aenderungen werden auf das
   echte DOM angewendet, wodurch die Anzahl der Manipulationen minimiert wird.

#### Hauptvorteil:

Die Optimierung von DOM-Aktualisierungen verbessert die Performance von
Anwendungen erheblich.

</details>

<details>
<summary>17. Was ist das Prop key und welcher Vorteil ergibt sich bei seiner Verwendung in Element-Arrays?</summary>

#### React

In React wird das Prop `key` verwendet, um jedes Element in Listen oder Arrays
zu identifizieren und React dabei zu helfen, Renderings bei Aenderungen oder
Aktualisierungen der Liste effizient zu verwalten. Das ist besonders wichtig
fuer die Optimierung des Renderprozesses, wenn sich eine Liste veraendert, also
wenn Elemente hinzugefuegt, entfernt oder umsortiert werden.

#### Die wichtigsten Punkte zu `key`:

1. **Eindeutigkeit:** Jedes Element in einer Liste muss einen eindeutigen `key`
   haben. Dadurch kann React verfolgen, welche Elemente geaendert, hinzugefuegt
   oder entfernt werden, und ihren Zustand zwischen Renderings beibehalten.

2. **Optimierung des Renderns:** Die Verwendung von `key` erlaubt es React, die
   Anzahl der erneuten Renderings zu minimieren und nur notwendige Aenderungen
   im DOM vorzunehmen. Ohne `key` faellt es React schwerer, Veraenderungen
   nachzuvollziehen, was dazu fuehren kann, dass die ganze Liste erneut
   gerendert wird, selbst wenn sich nur ein einziges Element geaendert hat.

3. **Natur von `key`:** Das Prop `key` wird nicht an die Komponente selbst
   weitergereicht und kann deshalb nicht fuer die Darstellung in der UI
   verwendet werden. Es ist eine interne Eigenschaft, die React zum Verfolgen
   von Elementen nutzt.

#### Beispiel fuer die Verwendung von `key` in einer Liste:

```jsx
const items = ['apple', 'banana', 'cherry'];

function FruitList() {
  return (

      {items.map((item, index) => (
        {item} // Wichtig: einen eindeutigen key verwenden
      ))}

  );
}
```

#### Warum die Eindeutigkeit von `key` wichtig ist:

- **Falsche Verwendung:** Wenn als `key` nicht eindeutige Werte wie zum Beispiel
  derselbe Index verwendet werden, kann React Aenderungen nicht korrekt
  nachverfolgen, was zu Renderfehlern fuehren kann.

- **Idealer key:** Wenn ein Element einen eindeutigen Identifikator wie etwa
  eine `id` hat, sollte dieser statt des Array-Index als `key` verwendet werden.

```jsx
const items = [
  { id: 1, name: 'apple' },
  { id: 2, name: 'banana' },
  { id: 3, name: 'cherry' },
];

function FruitList() {
  return (

      {items.map(item => (
        {item.name} // Am besten eindeutige ids verwenden
      ))}

  );
}
```

#### Vorteile der Verwendung von `key`:

- Verbessert die Rendering-Performance.

- Erlaubt React, nur geaenderte Elemente und nicht die gesamte Liste optimal zu
  aktualisieren.

- Gewaehrleistet die korrekte Behandlung des Zustands von Elementen beim
  Verschieben, Entfernen oder Aktualisieren.

Damit ist die Verwendung von `key` fuer den effizienten Umgang mit
Element-Arrays in React sehr wichtig.

</details>

<details>
<summary>18. Was ist bedingtes Rendern in React?</summary>

#### React

Bedingtes Rendern in React ist ein Prozess, bei dem eine Komponente je nach
bestimmten Bedingungen unterschiedliche Inhalte rendert. Dadurch kann die
Darstellung einer Komponente dynamisch anhand von State, Props oder anderen
Faktoren veraendert werden.

#### Die wichtigsten Ansaetze fuer bedingtes Rendern:

1. **Der `if`-Operator:** Der normale `if`-Operator kann verwendet werden, um zu
   entscheiden, was gerendert werden soll.

```jsx
function Greeting(props) {
  if (props.isLoggedIn) {
    return Welcome back!;
  }
  return Please sign up.;
}
```

2. **Der ternare Operator:** Fuer kuerzere bedingte Ausdruecke wird haeufig der
   ternare Operator verwendet.

```jsx
function Greeting(props) {
  return {props.isLoggedIn ? 'Welcome back!' : 'Please sign up.'};
}
```

3. **Logisches UND `&&` beim Rendern:** Der logische Operator `&&` kann
   verwendet werden, um ein Element nur dann zu rendern, wenn der Ausdruck auf
   der linken Seite wahr ist.

```jsx
function Notifications(props) {
  return (

      {props.unreadMessages.length > 0 && (
        You have {props.unreadMessages.length} unread messages.
      )}

  );
}
```

Das funktioniert so: Wenn `props.unreadMessages.length` groesser als 0 ist, wird
die Nachricht angezeigt, andernfalls wird nichts dargestellt.

4. **Verwendung von `return` mit einem bedingten Operator:** Du kannst `return`
   fuer bedingtes Rendern auf Basis verschiedener Bedingungen nutzen, wie im
   Beispiel mit `if` oder dem ternaren Operator.

#### Vorteile des bedingten Renderns:

- Erlaubt es, Inhalte dynamisch anhand von State oder Props zu veraendern.

- Verbessert die Flexibilitaet und die Moeglichkeit, unterschiedliche Inhalte
  fuer verschiedene Nutzer oder Situationen darzustellen.

#### Beispiel:

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

Hier veraendert sich der Button je nachdem, ob der Benutzer eingeloggt ist oder
nicht.

</details>

<details>
<summary>19. Was sind Fragmente (Fragments) in React?</summary>

#### React

Fragmente in React sind eine Moeglichkeit, mehrere Elemente zu gruppieren, ohne
zusaetzliche Elemente in das DOM einzufuegen. Sie erlauben es, mehrere Elemente
aus einer Komponente ohne Wrapper wie `div` zurueckzugeben, wodurch unnoetige
Elemente vermieden werden, die das Styling oder die Dokumentstruktur stoeren
koennten.

#### Wie werden Fragmente verwendet?

1. **Ohne Fragmente, also mit Wrapper:**

```jsx
function MyComponent() {
  return (

      Title
      Some text

  );
}
```

In diesem Beispiel wird ein einzelnes `div` zurueckgegeben, das `h1` und `p`
umhuellt.

2. **Mit Fragmenten, also ohne Wrapper:**

```jsx
function MyComponent() {
  return <>Title Some text</>;
}
```

Jetzt werden `h1` und `p` ohne zusaetzlichen Container gerendert, wodurch das
DOM sauberer bleibt.

#### Vorteile:

- **Sauberes DOM:** Unnoetige Wrapper im DOM koennen vermieden werden.

- **Komfort beim Rendern mehrerer Elemente:** Mehrere Elemente koennen aus einer
  Komponente zurueckgegeben werden, ohne zusaetzliche HTML-Elemente verwenden zu
  muessen.

#### Syntax:

- Es koennen die leeren Tags `<>` und `</>` verwendet werden, die eine Kurzform
  von `<React.Fragment></React.Fragment>` sind.

- Man kann auch `React.Fragment` verwenden, wenn Keys benoetigt werden, zum
  Beispiel beim Rendern von Listen:

```jsx
{
  item.name;
}
{
  item.description;
}
```

#### Wann sollte man Fragmente verwenden?

- Wenn mehrere Elemente ohne zusaetzlichen Wrapper im DOM gerendert werden
  sollen.

- Wenn die Struktur einer Komponente erhalten bleiben soll, ohne das Styling
  oder Layout zu stoeren.

Fragmente sind sehr nuetzlich, um unnoetige DOM-Elemente zu reduzieren und die
Performance zu verbessern.

</details>

<details>
<summary>20. Was ist Reconciliation?</summary>

#### React

**Reconciliation** ist der Prozess, den React verwendet, um das DOM auf die
effizienteste Weise zu aktualisieren. Wenn sich State oder Props einer
Komponente aendern, berechnet React die minimalen Aenderungen, die am echten DOM
vorgenommen werden muessen, um es mit dem Zustand des Virtual DOM zu
synchronisieren.

#### Wie funktioniert Reconciliation?

1. **Vergleich des alten und neuen Virtual DOM:**

- React speichert eine Kopie des vorherigen Virtual DOM.
- Wenn sich State oder Props aendern, wird ein neues Virtual DOM erzeugt.
- React vergleicht das neue Virtual DOM mit der vorherigen Kopie, also durch den
  sogenannten Diffing-Algorithmus.

2. **Erkennen von Unterschieden, also Diffing:**

- React erkennt, welche Teile des Baums sich veraendert haben, also neue
  Elemente, geaenderte Attribute oder entfernte Elemente.
- Dafuer wird ein Algorithmus verwendet, der fuer baumartige Strukturen
  optimiert ist.

3. **Aktualisierung des echten DOM:**

- React wendet Aenderungen nur auf die Teile des DOM an, die wirklich
  aktualisiert werden muessen, und vermeidet so ein vollstaendiges erneutes
  Rendern.

#### Grundprinzipien der Reconciliation:

- **Erhalt von Knoten desselben Typs:** Wenn Knoten denselben Typ haben, etwa
  `<div>` bleibt `<div>`, aendert React nur Attribute und Kindelemente.
- **Wiederverwendung von Komponenten:** Wenn eine Komponente dieselbe bleibt,
  verwendet React die vorhandene Instanz erneut.
- **Keys bei Listen:** Wenn eine Liste aus einem Array gerendert wird, nutzt
  React die Keys, also das Prop `key`, zum Vergleichen und Beibehalten von
  Knoten.

#### Beispiel:

```jsx
function App({ isVisible }) {
  return isVisible ? Hello : Goodbye;
}
```

- Wenn sich `isVisible` von `true` auf `false` aendert, entfernt React `<h1>`
  und ersetzt es durch `<p>`.

#### Bedeutung von Keys bei Listen:

Keys helfen React, Aenderungen in Listen korrekt zu erkennen. Zum Beispiel:

```jsx

  {items.map(item => (
    {item.text}
  ))}

```

Ohne eindeutige Keys kann React nicht exakt feststellen, welche Listenelemente
sich geaendert haben.

#### Vorteile der Reconciliation:

- Reduzierung der Anzahl von DOM-Operationen.
- Verbesserung der Anwendungsperformance.
- Reibungslose Aktualisierung der Benutzeroberflaeche.

</details>

<details>
<summary>21. Wie aktualisiert man den Zustand einer Komponente?</summary>

#### React

In React wird der Zustand einer Komponente mit der Methode `setState` in
Klassenkomponenten oder mit `useState` in funktionalen Komponenten aktualisiert.

#### Klassenkomponenten:

Der Zustand wird ueber `this.setState()` aktualisiert.

#### Beispiel:

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

#### Funktionale Komponenten:

Der Zustand wird ueber die Funktion aktualisiert, die von `useState`
zurueckgegeben wird.

#### Beispiel:

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

#### Hinweise:

1. **Asynchronitaet:** `setState` und `useState` arbeiten asynchron. Um den
   Zustand auf Grundlage des vorherigen Werts zu aktualisieren, sollte der
   funktionale Ansatz verwendet werden:

```jsx
this.setState(prevState => ({ count: prevState.count + 1 }));
setCount(prevCount => prevCount + 1);
```

2. **Den Zustand nicht direkt aktualisieren:** Eine Aenderung des Zustands ohne
   `setState` oder `useState` loest kein erneutes Rendern aus.

</details>

<details>
<summary>22. Was sind Inline-Bedingungsausdruecke?</summary>

#### React

**Inline-Bedingungsausdruecke** in JavaScript, insbesondere in React, sind
Mechanismen, mit denen Bedingungen direkt in JSX eingebettet werden koennen, um
Elemente oder Komponenten bedingt zu rendern. Dadurch wird der Code kompakter
und leichter verstaendlich.

#### Die wichtigsten Methoden:

1. **Bedingungsoperator (ternarer Operator):** Dies ist eine der
   gebraeuchlichsten Methoden fuer bedingtes Rendern von Elementen in JSX. Die
   Syntax lautet:

```jsx
Bedingung ? Ausdruck_wenn_wahr : Ausdruck_wenn_falsch;
```

**Beispiel:**

```jsx
const isLoggedIn = true;

function App() {
  return {isLoggedIn ? Welcome, User! : Please log in};
}
```

2. **Logischer UND-Operator (&&):** Mit dieser Methode wird eine Komponente oder
   ein Element nur dann angezeigt, wenn die Bedingung `true` ist. Wenn die
   Bedingung nicht erfuellt ist, wird nichts gerendert.

**Beispiel:**

```jsx
const isUserAdmin = true;

function App() {
  return {isUserAdmin && You have admin privileges};
}
```

In diesem Fall wird `<p>You have admin privileges</p>` nur angezeigt, wenn
`isUserAdmin` den Wert `true` hat.

3. **IF vor dem Zurueckgeben von JSX:** Gewoehnliche `if`-Anweisungen koennen
   ebenfalls vor dem `return` von JSX verwendet werden, wenn die Bedingung
   komplexer ist oder mehrere Aktionen noetig sind.

**Beispiel:**

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

**Vorteile:**

- Inline-Bedingungsausdruecke ermoeglichen saubereren und kompakteren Code.

- Sie verbessern die Lesbarkeit und reduzieren den Einsatz zusaetzlicher
  bedingter Konstruktionen.

#### Wichtig:

- In React koennen `if`-Anweisungen nicht direkt in JSX verwendet werden. Sie
  lassen sich jedoch vor dem `return` von JSX einsetzen.

</details>

<details>
<summary>23. Was ist der Unterschied zwischen der Ereignisbehandlung in HTML und React?</summary>

#### React

#### Unterschiede zwischen der Ereignisbehandlung in HTML und React:

| Kriterium                        | HTML                                                                          | React                                                                                       |
| -------------------------------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **Ereignisbindung**              | Wird als Attribut angegeben: `<button onclick="handler()">`.                  | Verwendet camelCase: `<button onClick={handler}>`.                                          |
| **Funktionstyp**                 | Verweis auf eine globale Funktion oder eine Zeichenkette mit JavaScript-Code. | Bindung an eine Komponentenfunktion, meist eine Methode oder Pfeilfunktion.                 |
| **Hinzufuegen von Listenern**    | Handler werden manuell ueber `addEventListener` hinzugefuegt.                 | React verwaltet die Bindung automatisch ueber das Virtual DOM.                              |
| **`this`-Kontext**               | Muss bei Klassen oft manuell gesetzt werden.                                  | In funktionalen Komponenten bleibt der Kontext korrekt, in Klassen kann `bind` noetig sein. |
| **Standardverhalten**            | Oft wird `return false` verwendet, um Standardverhalten zu stoppen.           | Es wird `event.preventDefault()` verwendet.                                                 |
| **Kompatibilitaet**              | Verarbeitet nur echte DOM-Ereignisse.                                         | Verwendet `SyntheticEvent` als Wrapper um native Ereignisse.                                |
| **Cross-Browser-Unterstuetzung** | Browserunterschiede muessen manuell beruecksichtigt werden.                   | React sorgt ueber `SyntheticEvent` fuer browseruebergreifende Konsistenz.                   |
| **Kontextbindung**               | Erfordert haeufig `bind`.                                                     | In Klassenkomponenten oft noetig, in funktionalen Komponenten nicht.                        |

#### Beispiel in HTML:

```html
Click me
```

#### Beispiel in React:

```jsx
function handleClick() {
  alert('Clicked!');
}

function App() {
  return Click me;
}
```

#### SyntheticEvent in React:

React verwendet einen Wrapper um native Ereignisse, der das Verhalten in
verschiedenen Browsern vereinheitlicht und die Performance verbessert.

</details>

<details>
<summary>24. Was sind synthetische Ereignisse in React?</summary>

#### React

**Synthetische Ereignisse (Synthetic Events)** in React sind Wrapper fuer native
DOM-Ereignisse, die eine einheitliche Schnittstelle fuer die Ereignisbehandlung
in verschiedenen Browsern bereitstellen. React erstellt fuer jedes Ereignis ein
`SyntheticEvent`, sodass Ereignisse einheitlich verarbeitet werden koennen, mit
browseruebergreifender Kompatibilitaet und besserer Performance.

#### Hauptmerkmale:

1. **Cross-Browser-Kompatibilitaet:** `SyntheticEvent` abstrahiert
   browserspezifische Unterschiede und sorgt fuer ein einheitliches Verhalten.

2. **Optimierung:** `SyntheticEvent` verwendet Objekt-Pooling, wodurch der
   Aufwand fuer das Erzeugen neuer Ereignisobjekte reduziert wird.

3. **Einmalige Verwendung:** Nach der Verarbeitung wird das `SyntheticEvent` in
   den Pool zurueckgegeben und kann danach nicht weiterverwendet werden. Bei
   asynchronen Operationen sollte das Ereignis deshalb separat gespeichert
   werden.

4. **Schnittstelle:** `SyntheticEvent` besitzt dieselben Methoden wie native
   Standardereignisse, zum Beispiel `preventDefault()` und `stopPropagation()`.

#### Anwendungsbeispiel:

```jsx
function handleClick(event) {
  // SyntheticEvent bietet Zugriff auf preventDefault()
  event.preventDefault();
  console.log('Button clicked!');
}

function App() {
  return Click me;
}
```

In diesem Beispiel ist `event` ein `SyntheticEvent`, das aehnlich wie ein
natives Ereignis funktioniert, aber zusaetzliche Vorteile bietet.

</details>

<details>
<summary>25. Wie verarbeitet man Ereignisse in React?</summary>

#### React

In React funktioniert die Ereignisbehandlung aehnlich wie in normalem
JavaScript, weist jedoch einige Unterschiede auf. Ereignisse in React sind
synthetisch, das heisst, sie bilden eine Abstraktion ueber die echten
Browser-Ereignisse und sorgen fuer browseruebergreifende Kompatibilitaet.

#### Grundprinzipien der Ereignisbehandlung in React:

1. **Synthetische Ereignisse:** Alle Ereignisse in React sind in ein Objekt vom
   Typ **SyntheticEvent** eingebettet, das eine browseruebergreifende
   Implementierung standardisierter DOM-Ereignisse darstellt. Dadurch koennen
   Ereignisse in allen Browsern einheitlich verarbeitet werden.

2. **Verwendung von camelCase fuer Ereignisse:** In React werden Ereignisnamen
   im camelCase-Format geschrieben, zum Beispiel `onClick` statt `onclick`.

3. **Uebergabe von Funktionen als Event-Handler:** Ereignisse in React werden
   mit Funktionen verarbeitet, die ueber Komponentenattribute uebergeben werden.

#### Beispiel fuer die Verarbeitung eines `click`-Ereignisses:

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

#### Beispiel mit einer funktionalen Komponente:

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

#### Besonderheiten der Ereignisbehandlung:

1. **`addEventListener` ist nicht noetig:** In React muessen Event-Handler nicht
   manuell hinzugefuegt oder entfernt werden. Das wird automatisch von React
   verwaltet.

2. **Erhalt des Kontexts in Methoden von Klassenkomponenten:** Wenn Methoden
   einer Klassenkomponente als Event-Handler verwendet werden, muss der Kontext
   `this` entweder ueber Pfeilfunktionen oder manuell im Konstruktor gebunden
   werden.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
    // Methodenbindung
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

3. **Uebergabe von Parametern an einen Handler:** Wenn zusaetzliche Argumente an
   einen Event-Handler uebergeben werden muessen, koennen Pfeilfunktionen oder
   Funktionen mit Parametern verwendet werden.

```jsx
function MyButton({ label }) {
  const handleClick = (event, label) => {
    console.log(label);
  };

  return <button onClick={event => handleClick(event, label)}>{label};
}
```

#### Ereignisbehandlung im DOM:

Alle Ereignisse in React basieren auf Event-Delegation: Ein Handler wird fuer
den gesamten Komponentenbaum registriert und ueber `React SyntheticEvent`
weitergeleitet.

</details>

<details>
<summary>26. Was sind Pointer Events?</summary>

#### React

#### Pointer Events in React

**Pointer Events** sind eine API, die Maus-, Touch- und Stift-Ereignisse in
einem einheitlichen Ereignissystem zusammenfassen.

#### Die wichtigsten Pointer Events

| **Ereignis**        | **Beschreibung**                                                                              |
| ------------------- | --------------------------------------------------------------------------------------------- |
| **onPointerDown**   | Wird ausgeloest, wenn mit Finger, Maus oder Stift gedrueckt wird.                             |
| **onPointerUp**     | Wird ausgeloest, wenn die Maus-, Finger- oder Stift-Eingabe losgelassen wird.                 |
| **onPointerMove**   | Wird beim Bewegen des Zeigers ueber einem Element ausgeloest.                                 |
| **onPointerEnter**  | Wird ausgeloest, wenn der Zeiger in den Bereich eines Elements eintritt.                      |
| **onPointerLeave**  | Wird ausgeloest, wenn der Zeiger den Bereich eines Elements verlaesst.                        |
| **onPointerCancel** | Wird ausgeloest, wenn der Browser das Ereignis abbricht, zum Beispiel bei einem Fokuswechsel. |

#### Anwendungsbeispiel in React

```jsx
const PointerExample = () => {
  const handlePointerDown = () => console.log('Pointer wurde gedrueckt');

  return (

      Klicke hier

  );
};
```

Dieser Code gibt `"Pointer wurde gedrueckt"` in der Konsole aus, wenn mit einem
beliebigen Eingabegeraet gedrueckt wird, also mit Maus, Touch oder Stift.

</details>

<details>
<summary>27. Wann sollte man eine Klassenkomponente statt einer funktionalen Komponente verwenden?</summary>

#### React

Klassenkomponenten wurden frueher verwendet, wenn eine oder mehrere der
folgenden Funktionen benoetigt wurden:

1. **Arbeit mit dem Zustand (State):** Frueher unterstuetzten funktionale
   Komponenten keinen lokalen Zustand, daher wurden dafuer Klassen verwendet.
   Heute erlauben Hooks wie `useState` und `useReducer` auch funktionalen
   Komponenten die Arbeit mit State.

2. **Lifecycle-Methoden:** Klassen boten Zugriff auf Methoden wie
   `componentDidMount`, `componentDidUpdate` und `componentWillUnmount`, um eine
   Komponente in verschiedenen Phasen ihres Lebenszyklus zu steuern. Heute wird
   dies meist mit dem Hook `useEffect` geloest.

3. **Verarbeitung komplexer Logik:** Wenn die Logik mehrere Methoden und den
   Zugriff auf Eigenschaften ueber `this` erforderte, waren Klassen frueher die
   naheliegende Wahl. Heute uebernehmen Hooks diese Aufgabe und kapseln Logik
   sauber.

#### Wann Klassen meist nicht mehr noetig sind:

Seit React 16.8 haben funktionale Komponenten mit Hooks den Bedarf an
Klassenkomponenten weitgehend ersetzt. In neuen Projekten sollten daher in der
Regel funktionale Komponenten bevorzugt werden. Klassen werden heute meist nur
noch fuer die Pflege von Legacy-Code verwendet.

</details>

<details>
<summary>28. Was sind zustandslose Komponenten (stateless components)?</summary>

#### React

Zustandslose Komponenten (stateless components) sind Komponenten, die keinen
internen Zustand speichern oder verwalten. Sie erhalten Daten nur ueber Props
und stellen sie als UI dar. Solche Komponenten sind in der Regel funktional.

#### Merkmale:

1. **Kein Zustand:** Sie verwenden kein `this.state` und aendern keinen internen
   Zustand.

2. **Nur Rendering:** Sie empfangen Props und geben diese als UI-Elemente aus.

3. **Einfachheit und Vorhersehbarkeit:** Sie lassen sich leichter testen und
   warten, da keine Zustandsaenderungen verfolgt werden muessen.

#### Beispiel:

```jsx
// Zustandslose Komponente
function Greeting(props) {
  return Hello, {props.name}!;
}

// Verwendung:
;
```

#### Vorteile:

- **Einfachheit:** Leichter zu verstehen und zu warten.

- **Performance-Optimierung:** Da diese Komponenten keinen Zustand haben, kann
  React sie oft effizienter aktualisieren.

#### Wann verwendet man sie?

- Wenn eine Komponente nur Daten anzeigt und keine eigenen Veraenderungen
  verwalten muss.

</details>

<details>
<summary>29. Was sind zustandsbehaftete Komponenten (stateful components)?</summary>

#### React

**Zustandsbehaftete Komponenten** (stateful components) sind Komponenten, die
ihren internen Zustand speichern und verwalten. Sie verwenden State, um Daten
abzulegen, die sich im Laufe der Zeit aendern koennen, und diese Aenderungen
beeinflussen das Rendering der Komponente.

#### Merkmale:

1. **Zustand (State):** Sie verwenden `this.state`, um veraenderliche Daten zu
   speichern und zu verwalten.

2. **Methoden zur Zustandsaktualisierung:** Fuer Updates wird `this.setState()`
   verwendet.

3. **Lebenszyklus:** Sie haben Zugriff auf Lifecycle-Methoden wie
   `componentDidMount()`, `shouldComponentUpdate()` und `componentDidUpdate()`.

#### Beispiel:

```jsx
// Zustandsbehaftete Komponente
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

#### Vorteile:

- **Dynamische Komponenten:** Sie koennen Inhalt und Darstellung anhand von
  Zustandsaenderungen anpassen.

- **Interaktivitaet:** Sie eignen sich fuer interaktive Oberflaechen, bei denen
  der Zustand auf Benutzeraktionen reagieren muss.

#### Wann verwendet man sie?

Wenn eine Komponente ihren internen Zustand verwalten muss, zum Beispiel fuer
Formulareingaben, Zaehler, Auswahlen und aehnliche Daten.

</details>

<details>
<summary>30. Was sind Pure Components?</summary>

#### React

**Pure Components** sind spezielle React-Klassenkomponenten, die das Rendering
automatisch optimieren. Sie fuehren einen flachen Vergleich von Props und State
durch, um unnoetige Aktualisierungen zu verhindern, wenn sich diese Werte nicht
geaendert haben.

#### Wie erstellt man eine Pure Component?

Eine Pure Component wird durch Vererbung von `React.PureComponent` erstellt.

```jsx
import React, { PureComponent } from 'react';

class MyComponent extends PureComponent {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Verwendung:
;
```

#### Wie funktioniert `PureComponent`?

- Fuehrt in `shouldComponentUpdate` einen flachen Vergleich
  (`shallow comparison`) von Props und State durch.

- Wenn sich Props und State nicht geaendert haben, wird die Komponente nicht
  erneut gerendert.

#### Wann sollte `PureComponent` verwendet werden?

- Wenn Props und State einfache Strukturen sind, also primitive Werte oder
  flache Objekte.

- Zur Verbesserung der Performance in Komponenten, die haeufig aktualisiert
  werden.

#### Einschraenkungen:

1. **Kein tiefer Vergleich:** `PureComponent` erkennt keine Aenderungen
   innerhalb verschachtelter Objekte oder Arrays. Wenn sich zum Beispiel der
   Inhalt eines Objekts aendert, die Referenz aber gleich bleibt, wird die
   Komponente nicht aktualisiert.

```jsx
this.setState({ data: { ...this.state.data, key: 'new value' } }); // Workaround
```

2. **Funktioniert nicht mit funktionalen Komponenten:** Als Alternative kann
   `React.memo` zur Optimierung funktionaler Komponenten verwendet werden.

```jsx
const MyComponent = React.memo(function MyComponent(props) {
  return Hello, {props.name}!;
});
```

</details>

<details>
<summary>31. Was sind Higher-Order Components?</summary>

#### React

Eine **Higher-Order Component** ist eine Funktion, die eine Komponente als
Argument entgegennimmt und eine neue Komponente zurueckgibt, die ihre
Funktionalitaet erweitert.

#### HOC-Syntax:

```jsx
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

#### Eigenschaften von HOCs:

1. **Nimmt eine Komponente als Argument entgegen.**
2. **Gibt eine neue Komponente mit zusaetzlichen Eigenschaften oder Verhalten
   zurueck.**
3. **Ermoeglicht die Wiederverwendung von Logik in verschiedenen Komponenten.**

#### Anwendungsbeispiel:

Ein HOC zum Hinzufuegen von State zu einer Komponente:

```jsx
import React, { useState } from 'react';

// HOC: fuegt Logik fuer den Zustand hinzu
function withCounter(WrappedComponent) {
  return function EnhancedComponent(props) {
    const [count, setCount] = useState(0);

    const increment = () => setCount(count + 1);

    return ;
  };
}

// Komponente, die erweitert wird
function Button({ count, increment }) {
  return Clicked {count} times;
}

// Verwendung des HOC
const EnhancedButton = withCounter(Button);

export default EnhancedButton;
```

#### Reale Einsatzszenarien fuer HOCs:

1. **Authentifizierung:** Komponenten werden umhuellt, um Zugriffsrechte zu
   pruefen.

2. **Datenverarbeitung:** Anbindung an APIs oder Verarbeitung von State.

3. **Logging:** Protokollierung von Komponentenaktionen.

#### Einschraenkungen von HOCs:

- Sie koennen tiefe Verschachtelungen im Komponentenbaum erzeugen, wenn zu viele
  HOCs eingesetzt werden.

- Sie koennen die Lesbarkeit durch mehrfaches Umhuellen von Komponenten
  verschlechtern.

HOCs sind ein leistungsfaehiges Werkzeug zur Wiederverwendung von Logik, werden
in modernen Anwendungen jedoch haeufig durch React Hooks ersetzt.

</details>

<details>
<summary>32. Was ist das `children`-Prop?</summary>

#### React

#### Was ist das `children`-Prop?

`children` ist ein spezielles Prop in React, das verwendet wird, um
verschachtelte Elemente oder Komponenten an eine Wrapper-Komponente zu
uebergeben.

#### Wie funktioniert es?

Wenn Inhalt zwischen den oeffnenden und schliessenden Tags einer Komponente
platziert wird, wird dieser Inhalt automatisch als `props.children`
weitergegeben.

#### Beispiel:

- **Wrapper-Komponente:**

```jsx
function Wrapper({ children }) {
  return { children };
}
```

- **Verwendung:**

```jsx
function App() {
  return (

      Hello, World!
      This is a paragraph inside the wrapper.

  );
}
```

- **Ergebnis:**

```html
Hello, World! This is a paragraph inside the wrapper.
```

#### Wichtige Eigenschaften von `children`:

1. **Flexibilitaet:** Es koennen beliebige Datentypen uebergeben werden, etwa
   Text, JSX, Komponenten oder Arrays von Elementen.

2. **Wiederverwendbarkeit:** Eine Wrapper-Komponente kann dynamisch
   unterschiedlichen Inhalt rendern.

3. **Struktur:** Hilft beim Aufbau von Komponenten mit verschachtelter Struktur.

#### Verwendung von `children` mit Funktionen als Props:

Manchmal wird `children` als Funktion verwendet, um Daten dynamisch
weiterzugeben:

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

#### Ergebnis:

```html
Apple Banana Cherry
```

`children` ist ein leistungsfaehiges Werkzeug zum Erstellen universeller und
wiederverwendbarer Komponenten in React.

</details>

<details>
<summary>33. Was ist ein Portal?</summary>

#### React

Ein **Portal** in React ist eine Moeglichkeit, Kindelemente in einen DOM-Knoten
zu rendern, der sich ausserhalb der DOM-Hierarchie der Elternkomponente
befindet.

#### Wie funktioniert es?

React stellt Portale ueber die Methode `ReactDOM.createPortal` bereit, die zwei
Argumente entgegennimmt:

1. **Das React-Element**, das gerendert werden soll.

2. **Der Ziel-DOM-Knoten**, in den das Element eingefuegt werden soll.

#### Syntax:

```jsx
ReactDOM.createPortal(child, container);
```

- **`child`** ist das React-Element, das gerendert werden soll.

- **`container`** ist der DOM-Knoten, in den das Element eingefuegt wird.

#### Anwendungsbeispiel:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function Modal({ children }) {
  return ReactDOM.createPortal(
    {children},
    document.getElementById('modal-root') // Zielknoten
  );
}

function App() {
  return (

      Hauptinhalt

        Dies ist der Inhalt des Modalfensters


  );
}
```

#### Wo werden Portale verwendet?

- Modalfenster.

- Tooltips.

- Kontextmenues.

#### Besonderheiten:

1. **Ereignishierarchie:** Obwohl das Element ausserhalb der DOM-Hierarchie
   gerendert wird, erfolgt die Ereignisverarbeitung weiterhin gemaess der
   React-Komponenten-Hierarchie. Beispielsweise steigen `onClick`-Ereignisse zu
   den uebergeordneten React-Komponenten auf.

2. **Flexibilitaet:** Portale erlauben das Einfuegen von Elementen an Stellen,
   die nicht in die aktuelle DOM-Struktur passen.

#### Vorteile:

- Einfache Verwaltung von "schwebenden" Elementen.
- Der React-Kontext bleibt auch ausserhalb der Haupt-DOM-Hierarchie erhalten.

</details>

<details>

<summary>34. Wie funktionieren Portale in React, und welche Vorteile sowie typischen Anwendungen haben sie in der UI-Entwicklung?</summary>

#### React

**Portale** in React ermoeglichen es, Kindelemente in einen anderen Bereich des
DOM zu rendern, statt an die uebliche Renderposition der Komponente. Das ist
nuetzlich fuer Elemente, die ausserhalb der gewohnten DOM-Hierarchie platziert
werden muessen, zum Beispiel Modalfenster, Tooltips oder Popups.

#### Die wichtigsten Vorteile von Portalen:

- Sie erlauben das Rendern von Elementen an einem anderen Ort im DOM, ohne die
  Struktur der React-Komponenten zu verletzen.

- Sie sind besonders nuetzlich, wenn Elemente ueber anderem Inhalt angezeigt
  werden muessen, zum Beispiel Modalfenster oder aufklappbare Menues.

#### Wie funktionieren Portale?

- Ein Portal ermoeglicht es, Inhalt an beliebiger Stelle im DOM zu platzieren,
  sogar ausserhalb des React-Wurzelcontainers.

#### Beispiel fuer die Verwendung eines Portals:

```jsx
import ReactDOM from 'react-dom';

const Modal = () => {
  return ReactDOM.createPortal(
    <div className="modal">
      <h1>Dies ist ein Modalfenster</h1>
    </div>,
    document.getElementById('modal-root') // Stelle im DOM fuer das Portal
  );
};

const App = () => {
  return (
    <div>
      <h1>Hauptseite</h1>
      <Modal />
    </div>
  );
};
```

#### Wichtige Punkte:

- `ReactDOM.createPortal()` wird zum Erstellen eines Portals verwendet. Das
  erste Argument ist der zu rendernde Inhalt, das zweite ein DOM-Element, in das
  dieser Inhalt eingefuegt wird.

- Portale koennen fuer Modalfenster, Tooltips, Pop-up-Menues und andere Elemente
  verwendet werden, die ausserhalb des Haupt-Komponentenbaums dargestellt werden
  sollen.

#### Besonderheiten:

- Obwohl Elemente, die ueber Portale gerendert werden, ausserhalb der
  eigentlichen React-Hierarchie im DOM erscheinen, behalten sie weiterhin
  Zugriff auf Kontext, State und Props ihrer Elternkomponenten.

- Portale sind besonders hilfreich, wenn Elemente "ueber" anderem Inhalt oder
  auf einer anderen Ebene der DOM-Hierarchie platziert werden muessen, etwa ein
  Modalfenster, das nicht durch den Elterncontainer begrenzt sein soll.

Portale erlauben es, Komponentenlogik und Struktur beizubehalten, ohne gegen
DOM-Regeln zu verstossen, und helfen so beim Aufbau sauberer UI-Komponenten.

</details>

<details>
<summary>35. Welche Lifecycle-Methoden gibt es fuer Komponenten in React?</summary>

#### React

Lifecycle-Methoden von Komponenten in React dienen dazu, verschiedene Phasen des
Komponentenlebens zu steuern: Erzeugung, Aktualisierung und Entfernung.

#### Die wichtigsten Lifecycle-Phasen:

1. **Mounting:** Wenn eine Komponente dem DOM hinzugefuegt wird.

`constructor()`: Initialisierung des Zustands und Binden von Methoden.

`static getDerivedStateFromProps(props, state)`: Aktualisiert den Zustand vor
dem Rendern, wird aber selten verwendet.

`render()`: Rendert JSX in das Virtual DOM.

`componentDidMount()`: Wird direkt nach dem Einfuegen in das DOM aufgerufen.
Wird fuer API-Anfragen oder die Initialisierung von Bibliotheken verwendet.

2. **Updating:** Wenn sich Props oder State aendern.

`static getDerivedStateFromProps(props, state)`: Wird vor jedem Rendern
aufgerufen.

`shouldComponentUpdate(nextProps, nextState)`: Steuert, ob eine Komponente
erneut gerendert werden soll. Standardmaessig wird `true` zurueckgegeben.

`render()`: Wird fuer die Aktualisierung des Virtual DOM ausgefuehrt.

`getSnapshotBeforeUpdate(prevProps, prevState)`: Erfasst einen Snapshot vor den
Aenderungen, zum Beispiel die Scrollposition.

`componentDidUpdate(prevProps, prevState, snapshot)`: Wird nach dem Update
aufgerufen. Wird fuer Nachladevorgaenge oder DOM-Arbeit verwendet.

3. **Unmounting:** Wenn die Komponente aus dem DOM entfernt wird.

`componentWillUnmount()`: Wird zum Bereinigen von Ressourcen verwendet, zum
Beispiel Timern oder Abonnements.

4. **Fehlerbehandlung:** Wenn eine Komponente einen Fehler ausloest.

`static getDerivedStateFromError(error)`: Erlaubt das Aktualisieren des Zustands
nach einem Fehler.

`componentDidCatch(error, info)`: Protokolliert Fehler.

#### Methodentabelle:

| Phase                | Methode                      | Beschreibung                                    |
| -------------------- | ---------------------------- | ----------------------------------------------- |
| **Mounting**         | `constructor()`              | Initialisiert Zustand und Einrichtung.          |
|                      | `getDerivedStateFromProps()` | Aktualisiert Zustand vor dem Rendern.           |
|                      | `render()`                   | Rendert JSX in das Virtual DOM.                 |
|                      | `componentDidMount()`        | Wird nach dem Einfuegen in das DOM ausgefuehrt. |
| **Updating**         | `getDerivedStateFromProps()` | Aktualisiert Zustand vor dem Rendern.           |
|                      | `shouldComponentUpdate()`    | Bestimmt, ob ein erneutes Rendern noetig ist.   |
|                      | `render()`                   | Aktualisiert das Virtual DOM.                   |
|                      | `getSnapshotBeforeUpdate()`  | Liefert einen Snapshot vor dem Update.          |
|                      | `componentDidUpdate()`       | Wird nach dem Update ausgefuehrt.               |
| **Unmounting**       | `componentWillUnmount()`     | Bereinigt Ressourcen vor dem Entfernen.         |
| **Fehlerbehandlung** | `getDerivedStateFromError()` | Aktualisiert den Zustand bei Fehlern.           |
|                      | `componentDidCatch()`        | Protokolliert Fehler.                           |

#### Moderner Ansatz:

In funktionalen Komponenten werden statt Lifecycle-Methoden **Hooks** verwendet:

- `useEffect` ersetzt `componentDidMount`, `componentDidUpdate` und
  `componentWillUnmount`.

- `useState` dient der Zustandsverwaltung.

</details>

<details>
<summary>36. Was macht die Methode `shouldComponentUpdate`?</summary>

#### React

- `shouldComponentUpdate` ist eine Lifecycle-Methode in Klassenkomponenten, die
  festlegt, ob eine Komponente erneut gerendert werden soll.

#### Wie funktioniert sie?

- Standardmaessig gibt sie `true` zurueck, was bedeutet, dass bei jeder
  Aenderung von `state` oder `props` erneut gerendert wird.

- Wenn sie `false` zurueckgibt, rendert React die Komponente nicht erneut,
  selbst wenn sich `props` oder `state` geaendert haben.

#### Anwendungsbeispiel:

```jsx
class MyComponent extends React.Component {
  shouldComponentUpdate(nextProps, nextState) {
    return nextProps.value !== this.props.value; // Re-Render nur bei Aenderung von value
  }

  render() {
    return <div>{this.props.value}</div>;
  }
}
```

#### Alternative in funktionalen Komponenten:

- Verwende `React.memo()` zur Memoisierung.

- `useMemo()` und `useCallback()` helfen dabei, Re-Render zu optimieren.

</details>

<details>
<summary>37. Wie fuehrt man Code aus, bevor eine Komponente aus dem Baum entfernt wird?</summary>

#### React

Um Code auszufuehren, bevor eine Komponente in React aus dem Baum entfernt wird,
werden folgende Ansaetze verwendet:

1. **Klassenkomponenten:** `componentWillUnmount`

Bei Klassenkomponenten gibt es die Lifecycle-Methode `componentWillUnmount`, die
vor dem Entfernen der Komponente aufgerufen wird.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Die Komponente wird entfernt');
  }

  render() {
    return <div>Meine Komponente</div>;
  }
}
```

2. **Funktionale Komponenten:** `useEffect` mit Cleanup

In funktionalen Komponenten kann die Bereinigung mit `useEffect` erfolgen, indem
eine Funktion zurueckgegeben wird, die vor dem Entfernen der Komponente
ausgefuehrt wird.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Die Komponente wird entfernt');
    };
  }, []);

  return <div>Meine Komponente</div>;
}
```

3. **Behandlung vor dem Schliessen der Seite (`beforeunload`)**

Wenn Code vor dem Schliessen eines Tabs oder vor dem Neuladen der Seite
ausgefuehrt werden muss:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Die Seite wird geschlossen');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Fazit

- `componentWillUnmount` fuer Klassenkomponenten.

- `useEffect` mit `return` fuer funktionale Komponenten.

- `beforeunload` fuer Faelle, in denen auf das Verlassen der Seite reagiert
  werden muss.

</details>

<details>
<summary>38. Warum sind Fragmente besser als umschliessende `div`-Container?</summary>

#### React

Fragmente (`<React.Fragment>` oder `<>...</>`) sind in React aus mehreren
Gruenden besser als umschliessende `<div>`-Container:

1. **Weniger unnoetiges HTML**

- Fragmente fuegen dem DOM kein zusaetzliches Element hinzu, wodurch die Zahl
  verschachtelter Tags sinkt und die Performance verbessert wird.

```jsx
<>
  <h1>Title</h1>
  <p>Text</p>
</>
```

- Ergebnis im DOM:

```html
<h1>Title</h1>
<p>Text</p>
```

- Im Unterschied zu einem `<div>`, das eine zusaetzliche Verschachtelung
  erzeugen wuerde:

```html
<div>
  <h1>Title</h1>
  <p>Text</p>
</div>
```

2. **Keine unerwuenschten Styling-Nebeneffekte**

- Ein zusaetzliches `<div>` kann CSS-Stile beeinflussen und unerwuenschte
  Layoutaenderungen verursachen. Fragmente vermeiden dieses Problem.

3. **Bessere Kompatibilitaet mit Tabellen**

- In einer `<table>` kann kein `<div>` direkt verschachtelt werden, Fragmente
  hingegen schon:

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

- Das funktioniert korrekt, waehrend ein `<div>` einen Fehler verursachen
  wuerde.

4. **Performance-Optimierung**

- Weniger unnoetige DOM-Knoten bedeuten schnelleres Rendern und geringeren
  Speicherverbrauch.

</details>

<details>
<summary>39. Was sind Hooks in React?</summary>

#### React

**React Hooks** sind Funktionen, mit denen State und andere React-Funktionen
ohne das Schreiben von Klassen verwendet werden koennen.

#### Die wichtigsten Hook-Typen:

1. **useState** ermoeglicht das Hinzufuegen von State zu funktionalen
   Komponenten.

```jsx
const [state, setState] = useState(initialState);
```

2. **useEffect** ermoeglicht das Ausfuehren von Side Effects, zum Beispiel
   API-Anfragen oder Subscriptions, in funktionalen Komponenten.

```jsx
useEffect(() => {
  // Effekt-Code
}, [dependencies]); // Abhaengigkeiten
```

3. **useContext** ermoeglicht den Zugriff auf Kontextwerte ohne die Verwendung
   einer Consumer-Komponente.

```jsx
const value = useContext(MyContext);
```

4. **useRef** erlaubt das Erstellen von Referenzen auf DOM-Elemente oder das
   Speichern von Werten zwischen Render-Vorgaengen, ohne State zu aendern.

```jsx
const myRef = useRef(initialValue);
```

5. **useReducer** ist eine Alternative zu `useState` und eignet sich fuer die
   Verwaltung komplexerer Zustandslogik mit Reducern, aehnlich wie bei Redux.

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

6. **useMemo** optimiert Wertberechnungen, um unnoetige Neuberechnungen zu
   vermeiden.

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

7. **useCallback** gibt eine memoisierten Version einer Funktion zurueck, damit
   sie nicht bei jedem Rendern neu erstellt wird.

```jsx
const memoizedCallback = useCallback(() => {
  // Funktion;
}, [dependencies]);
```

#### Die wichtigsten Vorteile:

- **Funktionale Komponenten:** Statt Klassenkomponenten koennen funktionale
  Komponenten mit Hooks verwendet werden.

- **Bessere Lesbarkeit:** Die Logik kann auf mehrere Hooks verteilt werden,
  wodurch der Code kuerzer und modularer wird.

- **Wiederverwendung von Logik:** Hooks erlauben die Wiederverwendung von Logik
  in verschiedenen Komponenten, ohne komplexe Hierarchien aufzubauen.

</details>

<details>
<summary>40. Welche Vorteile haben Hooks in React?</summary>

#### React

| **Vorteil**                        | **Beschreibung**                                                              |
| ---------------------------------- | ----------------------------------------------------------------------------- |
| **Weniger Code**                   | Hooks machen Klassen oft ueberfluessig und reduzieren die Code-Menge.         |
| **Bessere Lesbarkeit**             | Code mit Hooks ist haeufig leichter zu verstehen und zu warten.               |
| **Wiederverwendung von Logik**     | Custom Hooks erlauben das Teilen von Logik zwischen Komponenten.              |
| **Einfachere Zustandsverwaltung**  | `useState` und `useReducer` machen State-Management uebersichtlicher.         |
| **Flexibler Einsatz von Effekten** | `useEffect` ermoeglicht Side Effects ohne klassenbasierte Lifecycle-Methoden. |
| **Einfachere Migration**           | Erleichtert den Wechsel von Klassenkomponenten zu funktionalen Komponenten.   |

</details>

<details>
<summary>41. Welche Nachteile haben Hooks in React?</summary>

#### React

| **Nachteil**                             | **Beschreibung**                                                                                             |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| **Mehr Re-Render**                       | Falsche Verwendung von Hooks, besonders `useEffect`, kann unnoetige Re-Render verursachen.                   |
| **Schwierigeres Verstaendnis der Logik** | Die Logik einer Komponente kann sich auf mehrere `useEffect`-Aufrufe verteilen und das Debugging erschweren. |
| **Kein expliziter Lifecycle**            | Im Unterschied zu Klassenkomponenten haben Hooks keine klar abgegrenzten Lifecycle-Methoden.                 |
| **Moegliche Optimierungsprobleme**       | Eine falsche Nutzung von `useCallback` und `useMemo` kann zu ineffizientem Verhalten fuehren.                |
| **Komplexitaet in grossen Projekten**    | In umfangreichen Anwendungen koennen Hooks die Verwaltung von State und Side Effects erschweren.             |

</details>

<details>
<summary>42. Welche Regeln und Einschraenkungen gelten fuer Hooks in React?</summary>

#### React

| **Regel**                           | **Beschreibung**                                                                                                                          |
| ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **Nur in Funktionen verwenden**     | Hooks duerfen nur in funktionalen Komponenten oder in Custom Hooks aufgerufen werden.                                                     |
| **Aufrufreihenfolge beibehalten**   | Hooks duerfen nicht bedingt in `if`, `for` oder `while` aufgerufen werden, da sonst die Reihenfolge der Aufrufe zerstoert wird.           |
| **Nur auf oberster Ebene aufrufen** | Hooks duerfen nicht innerhalb verschachtelter Funktionen oder Event-Handler aufgerufen werden.                                            |
| **Benennung von Custom Hooks**      | Custom Hooks muessen mit `use` beginnen, zum Beispiel `useAuth`.                                                                          |
| **Abhaengigkeiten korrekt angeben** | In `useEffect`, `useMemo` und `useCallback` muessen Abhaengigkeiten korrekt angegeben werden, um unvorhersehbares Verhalten zu vermeiden. |

</details>

<details>
<summary>43. Was ist `useReducer()`?</summary>

#### React

`useReducer()` ist ein Hook in React, der zur Zustandsverwaltung in funktionalen
Komponenten verwendet wird. Er ist eine Alternative zu `useState()` und eignet
sich besonders fuer komplexe Logik zur Zustandsaktualisierung, vor allem wenn
Aenderungen vom vorherigen Zustand abhaengen.

#### Syntax:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` ist eine Funktion, die `state` und `action` entgegennimmt und einen
  neuen Zustand zurueckgibt.

- `initialState` ist der Anfangszustand.

- `dispatch` ist eine Funktion, mit der der Reducer mit einer bestimmten
  `action` aufgerufen wird.

#### Beispiel:

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

#### Wann sollte man es verwenden?

- Wenn der Zustand komplexe Logik oder Abhaengigkeiten hat.

- Wenn Zustandsaenderungen ueber `dispatch` vereinheitlicht werden sollen.

- Fuer bessere Skalierbarkeit, zum Beispiel bei globalem State.

</details>

<details>
<summary>44. Was machen die Hooks `useCallback()`, `useMemo()`, `useImperativeHandle()` und `useLayoutEffect()`?</summary>

#### React

#### `useCallback()`

Memoisiert eine Funktion, damit sie nicht bei jedem Rendern neu erstellt wird.
Das ist nuetzlich, wenn Callbacks an Kindkomponenten weitergegeben werden.

- **Beispiel:**

```jsx
import { useCallback } from 'react';

function MyComponent({ onClick }) {
  return <button onClick={onClick}>Klick</button>;
}

function Parent() {
  const handleClick = useCallback(() => {
    console.log('Klick');
  }, []); // Die Funktion wird nur einmal erstellt

  return <MyComponent onClick={handleClick} />;
}
```

#### `useMemo()`

Memoisiert Berechnungen, damit sie nicht bei jedem Rendern erneut ausgefuehrt
werden, solange sich die Abhaengigkeiten nicht geaendert haben.

#### Beispiel:

```jsx
import { useMemo } from "react";

function ExpensiveCalculation({ num }) {
const result = useMemo(() => {
console.log("Berechnung...");
return num \* 2;
}, [num]); // Wird nur bei Aenderung von num ausgefuehrt

return <div>Ergebnis: {result}</div>;
}
```

#### `useImperativeHandle()`

Erlaubt die Steuerung des Verhaltens einer `ref` in einer Kindkomponente. Wird
zusammen mit `forwardRef()` verwendet.

#### Beispiel:

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
      <button onClick={() => inputRef.current.focus()}>Fokus</button>
      <button onClick={() => inputRef.current.clear()}>Leeren</button>
    </div>
  );
}
```

#### `useLayoutEffect()`

Funktioniert wie `useEffect()`, wird aber synchron nach DOM-Aenderungen
ausgefuehrt. Das ist nuetzlich fuer Messungen oder DOM-Manipulationen, bevor der
Browser die Seite zeichnet.

- **Beispiel:**

```jsx
import { useLayoutEffect, useRef } from 'react';

function LayoutEffectExample() {
  const divRef = useRef();

  useLayoutEffect(() => {
    console.log('Breite des Elements:', divRef.current.offsetWidth);
  }, []);

  return (
    <div ref={divRef} style={{ width: '200px', height: '100px' }}>
      Element
    </div>
  );
}
```

#### Wann sollte welcher Hook verwendet werden?

- `useCallback()` fuer das Memoisieren von Funktionen.

- `useMemo()` fuer das Memoisieren von Berechnungen.

- `useImperativeHandle()` fuer die Steuerung einer `ref` in der Kindkomponente.

- `useLayoutEffect()` wenn vor der sichtbaren Darstellung von DOM-Aenderungen
  noch etwas ausgefuehrt werden muss, etwa eine Messung.

</details>

<details>
<summary>45. Wie fuehrt man eine Operation nur einmal beim ersten Rendern aus?</summary>

#### React

Um in funktionalen Komponenten eine Operation nur einmal beim ersten Rendern
auszufuehren, verwendet man `useEffect` mit einem leeren Abhaengigkeitsarray
(`[]`):

#### Beispiel:

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    console.log(
      'Das wird nur einmal nach dem Mounten der Komponente ausgefuehrt'
    );
  }, []);

  return <div>Komponente</div>;
}
```

#### Erklaerung:

- `useEffect(() => { /* code */ }, [])` bedeutet mit leerem Abhaengigkeitsarray,
  dass der Effekt nur einmal nach dem ersten Rendern startet. Das ist
  vergleichbar mit `componentDidMount` in Klassenkomponenten.

#### Zusaetzlich, zum Beispiel fuer Subscribe/Unsubscribe:

```jsx
useEffect(() => {
  const interval = setInterval(() => {
    console.log('Ein einmaliger Effekt ist aktiv');
  }, 1000);

  return () => clearInterval(interval); // Cleanup beim Unmount
}, []);
```

Dieser Ansatz ist nuetzlich fuer die Initialisierung von API-Anfragen,
Subscriptions, Timern und aehnlichen Vorgaengen.

</details>

<details>
<summary>46. Was ist Context?</summary>

#### React

**Context** in React ist ein Mechanismus zur Weitergabe von Daten durch den
Komponentenbaum, ohne diese Daten auf jeder Ebene ueber Props weiterreichen zu
muessen.

#### Wie funktioniert Context?

1. **`React.createContext()`** wird zum Erstellen eines Context verwendet.

```jsx
const MyContext = React.createContext(defaultValue);
```

2. **Provider** ist eine Komponente, die den Context-Wert bereitstellt. Sie
   umschliesst einen Teil des Komponentenbaums und gibt den Wert ueber `value`
   nach unten weiter.

```jsx
<MyContext.Provider value={}>
  <YourComponent />
</MyContext.Provider>
```

3. **Consumer** ist eine Komponente, die den Context-Wert konsumiert. In der
   Regel verwendet sie eine Funktion als Child, die den Wert entgegennimmt.

```jsx
<MyContext.Consumer>
{value => }
</MyContext.Consumer>
```

4. **`useContext`** ist ein Hook, der den Zugriff auf den Context-Wert
   ermoeglicht, ohne `Consumer` zu verwenden.

```jsx
const value = useContext(MyContext);
```

#### Wann sollte man Context verwenden?

- Wenn Daten zwischen Komponenten auf verschiedenen Ebenen der Hierarchie
  weitergegeben werden muessen, zum Beispiel Theme, Sprache oder Benutzer.

- Wenn Props nicht ueber mehrere Komponentenebenen hinweg gereicht werden
  sollen, weil das den Code unnoetig verkompliziert.

#### Beispiel:

```jsx
// Context erstellen
const ThemeContext = React.createContext('light');

// Komponente, die den Context-Wert bereitstellt
function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedComponent />
    </ThemeContext.Provider>
  );
}

// Komponente, die den Context-Wert verwendet
function ThemedComponent() {
  const theme = useContext(ThemeContext);
  return <div>Das aktuelle Theme ist {theme}</div>;
}
```

#### Vorteile:

- Bequeme Weitergabe globaler Werte.

- Verbessert die Skalierbarkeit einer Anwendung, weil weniger Props
  weitergereicht werden muessen.

</details>

<details>
<summary>47. Wie funktioniert der Context-Mechanismus in React fuer die gemeinsame Weitergabe von Daten zwischen Komponenten?</summary>

#### React

Der Mechanismus **React Context** erlaubt die Weitergabe von Daten zwischen
Komponenten, ohne sie auf jeder Ebene ueber Props weiterreichen zu muessen. Das
ist besonders nuetzlich fuer globale Daten wie Theme-Einstellungen,
Benutzerauthentifizierung oder Sprache.

#### Die wichtigsten Schritte bei der Arbeit mit Context:

1. **Context erstellen:** Zur Erstellung wird `React.createContext()` verwendet.
   Dadurch entstehen zwei Komponenten:

- `Provider`, eine Komponente, die den Context-Wert weitergibt.

- `Consumer`, eine Komponente, die den Context-Wert empfaengt.

```jsx
const MyContext = React.createContext();
```

2. **Context bereitstellen:** Mit `Provider` werden die Komponenten umschlossen,
   denen der Context zur Verfuegung stehen soll. Der Wert wird ueber das Prop
   `value` uebergeben.

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

3. **Context lesen:** Zum Zugriff auf den Context-Wert werden `Consumer` oder
   der Hook `useContext` verwendet.

- **Consumer:**

```jsx
const Child = () => (
  <MyContext.Consumer>{user => <div>{user}</div>}</MyContext.Consumer>
);
```

- **`useContext`-Hook, empfohlen in funktionalen Komponenten:**

```jsx
const Child = () => {
  const user = useContext(MyContext);
  return <div>{user}</div>;
};
```

- **Context aendern:** Um den Context-Wert zu aendern, koennen Funktionen
  verwendet werden, die ueber `useState` oder andere Methoden der
  Zustandsverwaltung bereitgestellt werden.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <button onClick={() => setUser('Jane Doe')}>Benutzer wechseln</button>
      <Child />
    </MyContext.Provider>
  );
};
```

#### Wichtige Punkte:

- Context hilft dabei, `prop drilling` zu vermeiden, also das Weiterreichen von
  Props durch viele Komponenten.

- Wenn sich der Context-Wert aendert, werden alle Komponenten, die diesen
  Context verwenden, erneut gerendert.

- **`useContext`** ist im Vergleich zu `Consumer` der bequemere und modernere
  Weg, den Context-Wert abzurufen.

Context ist ein leistungsfaehiges Werkzeug, sollte aber vor allem fuer globale
Daten verwendet werden. Fuer lokalen Zustand eignet sich normaler State haeufig
besser.

</details>

<details>
<summary>48. Was ist Prop Drilling und wie vermeidet man es?</summary>

#### React

**Prop Drilling** bezeichnet das Weiterreichen von Props ueber mehrere Ebenen
verschachtelter Komponenten hinweg, obwohl diese Werte eigentlich nur in einer
tief liegenden Kindkomponente benoetigt werden. Das erschwert die Wartung und
verschlechtert die Lesbarkeit des Codes.

#### Beispiel fuer Prop Drilling:

```jsx
const Parent = () => {
  const user = { name: 'John' };
  return <Child user={user} />;
};

const Child = ({ user }) => {
  return <GrandChild user={user} />;
};

const GrandChild = ({ user }) => {
  return <p>Name: {user.name}</p>;
};
```

Hier wird `user` ueber `Child` weitergegeben, obwohl `Child` ihn nicht selbst
benoetigt. Genau das ist **Prop Drilling**.

#### Wie vermeidet man Prop Drilling?

| **Methode**                                                       | **Beschreibung**                                                                    |
| ----------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **Context API**                                                   | Ermoeglicht die direkte Weitergabe von Daten an die benoetigten Komponenten.        |
| **Externe State-Loesungen wie Redux, Zustand, Jotai oder Recoil** | Werden zur Verwaltung globalen Zustands ohne Props-Weitergabe verwendet.            |
| **Render Props**                                                  | Erlauben die Uebergabe von Funktionen anstelle von Props.                           |
| **Custom Hooks**                                                  | Lagern Logik in eigene Funktionen aus, um gemeinsamen Datenzugriff bereitzustellen. |

#### Beispiel fuer Context API statt Prop Drilling

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
  return <p>Name: {user.name}</p>;
};
```

Hier ist `user` direkt in `GrandChild` verfuegbar, ohne unnoetige Weitergabe
ueber `Child`.

</details>

<details>
<summary>49. Was ist Redux?</summary>

#### React

**Redux** ist eine Bibliothek zur Zustandsverwaltung in JavaScript-Anwendungen
und ist besonders im React-Umfeld beliebt. Sie basiert auf dem Konzept eines
globalen Speichers (`store`), in dem der gesamte Anwendungszustand liegt, und
ermoeglicht vorhersehbare Zustandsaenderungen.

#### Grundprinzipien von Redux:

1. **Single Source of Truth**: Der gesamte Zustand wird in einem globalen
   `store` gespeichert, was das Nachverfolgen von Aenderungen vereinfacht.
2. **State ist schreibgeschuetzt**: Der Zustand darf nicht direkt veraendert
   werden, sondern nur ueber eine `action`.
3. **Aenderungen erfolgen durch pure functions**: Der Zustand wird mit Reducern
   veraendert, also Funktionen, die den aktuellen Zustand und eine `action`
   erhalten und einen neuen Zustand zurueckgeben.

#### Zentrale Elemente von Redux:

- **Store** ist das zentrale Zustandsspeicherobjekt.
- **Actions** sind Objekte, die eine beabsichtigte Zustandsaenderung
  beschreiben.
- **Reducers** sind pure Funktionen, die definieren, wie sich der Zustand
  aendert.
- **Dispatch** ist die Methode zum Senden einer `action`.
- **Selectors** sind Funktionen zum Abrufen benoetigter Daten aus dem `store`.

Redux eignet sich fuer grosse Anwendungen mit komplexen Datenfluessen, ist fuer
einfache Projekte jedoch oft ueberdimensioniert.

</details>

<details>
<summary>50. Welche weiteren Bibliotheken zur Zustandsverwaltung in React kennst du neben Redux?</summary>

#### React

Neben Redux gibt es viele weitere Bibliotheken zur Zustandsverwaltung in React:

1. **React Context API** ist ein eingebauter React-Mechanismus zur Weitergabe
   von Zustand ohne Props-Weitergabe. Er eignet sich gut fuer kleine und
   mittlere Anwendungen.

2. **Zustand** ist einfacher und leichter als Redux, benoetigt keine Reducer und
   Actions, arbeitet mit einem imperativen Ansatz und verwendet Hooks.

3. **Recoil** ist eine Bibliothek von Facebook, die mit Atomen (`atoms`) und
   Selektoren (`selectors`) arbeitet und damit ein flexibles System fuer
   globalen Zustand ermoeglicht.

4. **Jotai** aehnelt Recoil, ist aber einfacher. Die Bibliothek verwendet Atome
   zur Speicherung von Zustand und erlaubt eine deklarative Steuerung.

5. **MobX** verfolgt einen reaktiven Ansatz zur Zustandsverwaltung und arbeitet
   mit Observables. Es eignet sich gut fuer Objekte und komplexe Strukturen.

6. **Effector** ist deklarativer und oft effizienter als Redux. Die Bibliothek
   basiert auf einem reaktiven Ansatz und erleichtert das Management von
   Datenfluessen.

7. **XState** ist eine Bibliothek fuer State Machines und eignet sich gut fuer
   komplexe Geschaeftslogik.

Jede dieser Bibliotheken hat eigene Staerken. Die Wahl haengt von der
Komplexitaet des Projekts und den Anforderungen an die Performance ab.

</details>

<details>
<summary>51. Was ist Redux Thunk?</summary>

#### React

**Redux Thunk** ist eine Middleware fuer Redux, die es ermoeglicht, asynchrone
Operationen wie API-Anfragen auszufuehren, bevor Aenderungen an den `store`
gesendet werden.

#### Wie funktioniert es?

Normalerweise erlaubt Redux, an `dispatch` nur Objekte, also `actions`, zu
uebergeben. Redux Thunk erweitert diese Moeglichkeit und erlaubt auch die
Uebergabe von Funktionen. Dadurch kann man:

1. Asynchrone Aktionen vor der Zustandsaenderung ausfuehren.

2. Innerhalb eines `thunk` auf `dispatch` und `getState` zugreifen.

#### Anwendungsbeispiel:

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

Danach wird dieser `thunk` aufgerufen:

```jsx
dispatch(fetchData());
```

#### Wann sollte man es verwenden?

- Fuer API-Anfragen.
- Fuer Verzoegerungen oder komplexe Logik vor dem Aktualisieren des Stores.
- Wenn mehrere `dispatch`-Aufrufe innerhalb einer Aktion noetig sind.

Wenn eine Anwendung komplexe asynchrone Logik enthaelt, koennen **Redux Saga**
oder **RTK Query** bessere Alternativen sein.

</details>

<details>
<summary>52. Wie funktioniert Redux Saga?</summary>

#### React

**Redux Saga** ist eine Middleware fuer Redux, die Generatoren (`function*`) zur
Steuerung asynchroner Prozesse in einer Anwendung verwendet.

#### Wie funktioniert es?

1. **Sie hoert auf Actions** wie `takeEvery` oder `takeLatest` und reagiert
   darauf.

2. **Sie fuehrt Side Effects aus**, zum Beispiel API-Anfragen oder Timer.

3. **Sie dispatcht neue Actions** mit `put` in den Store.

#### Beispiel:

1. **Saga zum Laden von Daten aus einer API:**

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

2. **Action-Listener:**

```jsx
function* watchFetchData() {
  yield takeEvery('FETCH_REQUEST', fetchData);
}
```

3. **Starten der Saga im `store`:**

```jsx
import createSagaMiddleware from 'redux-saga';
const sagaMiddleware = createSagaMiddleware();
const store = createStore(reducer, applyMiddleware(sagaMiddleware));
sagaMiddleware.run(watchFetchData);
```

#### Vorteile von Redux Saga:

- Geeignet fuer komplexe asynchrone Logik.
- Eingebaute Behandlung von Abbruechen mit `takeLatest`.
- Leistungsstarke Operatoren wie `call`, `put`, `select` und `delay`.

**Redux Thunk** ist einfacher, aber fuer komplexere Szenarien ist **Saga**
haeufig besser geeignet.

</details>

<details>
<summary>53. Was ist React Fiber?</summary>

#### React

**React Fiber** ist die neue Rendering-Architektur von React, die mit Version 16
eingefuehrt wurde. Sie wurde entwickelt, um die Performance zu verbessern,
asynchrones Rendering zu unterstuetzen und eine flexiblere Steuerung von
UI-Updates zu ermoeglichen.

#### Wichtige Eigenschaften von React Fiber:

1. **Verbesserte Performance:** Fiber erlaubt es React, den Fortschritt eines
   Render-Vorgangs zu speichern. Dadurch kann das Rendern unterbrochen und
   spaeter fortgesetzt werden. Das ist besonders wichtig in grossen Anwendungen,
   in denen aufwendige Berechnungen das Rendering verlangsamen koennen.

2. **Asynchrones Rendering:** React Fiber unterstuetzt asynchrones Rendering,
   sodass in Teilabschnitten gerendert werden kann. Das verbessert die
   Reaktionsfaehigkeit der Anwendung, insbesondere bei komplexen Interfaces, da
   der Haupt-Thread nicht blockiert wird.

3. **Priorisierung von Updates:** Fiber erlaubt es, verschiedenen Arten von
   Updates unterschiedliche Prioritaeten zuzuweisen. Zum Beispiel koennen
   Animationen hoehere Prioritaet erhalten als normale State-Updates. Dadurch
   kann React komplexe Aktualisierungen effizienter verarbeiten.

4. **Aufteilung des Renderings in Teilaufgaben:** In aelteren React-Versionen
   wurden alle Aenderungen in einem Schritt verarbeitet. Fiber zerlegt das
   Rendering in kleinere Aufgaben, sodass React schrittweise arbeiten und
   zwischendurch andere wichtige Aufgaben wie Event-Verarbeitung erledigen kann.

5. **Bessere Unterstuetzung fuer Animationen und Uebergaenge:** Durch
   asynchrones Rendering kann React Animationen effizienter steuern, wodurch
   Zustandswechsel fluessiger und ohne merkliche Verzoegerungen ablaufen.

#### Wie funktioniert React Fiber?

In aelteren React-Versionen war der gesamte Rendering-Prozess synchron, also vom
Anfang bis zum Ende blockierend. Aufwendige Berechnungen konnten deshalb die
Darstellung der Benutzeroberflaeche verlangsamen. In React Fiber wird das
Rendering in kleine Aufgaben aufgeteilt, die asynchron ausgefuehrt werden
koennen. Wenn noetig, kann React eine Aufgabe unterbrechen und spaeter
fortsetzen, ohne andere Vorgaenge wie UI-Updates oder Event-Verarbeitung zu
blockieren.

#### Fiber ermoeglicht React:

- Das Rendering aufzuteilen, um die Performance zu verbessern.

- Asynchrone UI-Updates umzusetzen.

- Prioritaeten und aufwendige Berechnungen besser zu verwalten, was vor allem in
  komplexen Interfaces wichtig ist.

#### Vorteile:

- Schnellere Reaktion von Anwendungen.

- Aufwendige Operationen koennen ohne wahrnehmbare Verzoegerungen fuer Nutzer
  verarbeitet werden.

- Besseres Management von Animationen und Uebergaengen.

**React Fiber** ist eine interne Ueberarbeitung, die veraendert hat, wie React
mit Rendering umgeht, und damit die Gesamtperformance von Anwendungen
verbessert.

</details>

<details>
<summary>54. Was bedeutet Lifting State Up in React?</summary>

#### React

**Lifting State Up** ist ein Ansatz in React, bei dem der Zustand (`state`) zur
naechsten gemeinsamen Elternkomponente verschoben wird, wenn mehrere Komponenten
denselben Zustand gemeinsam nutzen muessen. Dadurch entsteht eine einzige
zuverlaessige Datenquelle fuer diese Komponenten.

#### Grundidee:

1. **Komponenten, die Daten gemeinsam nutzen, sollten nicht jeweils einen
   eigenen separaten Zustand haben.**

2. **Der Zustand wird in eine Elternkomponente verschoben, die die Daten ueber
   Props an ihre Kinder weitergibt.**

#### Wie funktioniert das?

1. **Die Elternkomponente speichert den Zustand.**
2. **Sie uebergibt den Zustand und Funktionen zu seiner Aktualisierung ueber
   `props` an ihre Kindkomponenten.**

3. **Die Kindkomponenten melden Aenderungen ueber die uebergebenen Funktionen an
   die Elternkomponente zurueck.**

#### Beispiel:

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

#### Vorteile:

1. **Es sorgt fuer eine einzige Datenquelle fuer den Zustand.**

2. **Es erleichtert die Synchronisierung von Daten zwischen Komponenten.**

3. **Es macht Komponenten vorhersehbarer und besser wiederverwendbar.**

</details>

<details>
<summary>55. Was sind Controlled Components?</summary>

#### React

#### Controlled Components in React

Controlled Components sind Komponenten, bei denen **React den Zustand eines
Formulars** ueber `state` steuert. Die Werte von Formularfeldern wie `<input>`,
`<textarea>` oder `<select>` sind an den Zustand der Komponente gebunden, und
Aenderungen werden ueber Ereignisse verarbeitet.

#### Wie funktioniert das?

1. **Die Komponente speichert den Formularwert in ihrem `state`.**

2. **Aenderungen an den Formularfeldern werden ueber `onChange` verarbeitet.**

3. **Der Formularwert wird mit `setState` oder dem entsprechenden State-Setter
   aktualisiert.**

#### Beispiel:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [inputValue, setInputValue] = useState('');

  const handleChange = event => {
    setInputValue(event.target.value); // Zustand aktualisieren
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
          value={inputValue} // Wert wird ueber state gesteuert
          onChange={handleChange} // Aenderungen verarbeiten
        />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Hauptvorteile:

1. **Single Source of Truth:** Der Formularwert ist mit dem Zustand der
   Komponente synchronisiert.

2. **Flexibilitaet:** Formulardaten lassen sich leicht validieren und anpassen.

3. **Transparenz:** Der Formularzustand ist klar und vorhersehbar.

#### Unterschied zu Uncontrolled Components:

- Bei Controlled Components wird der Formularwert von React ueber `state`
  gesteuert.

- Bei Uncontrolled Components liegt der Wert im DOM selbst und wird ueber `ref`
  ausgelesen.

#### Uncontrolled-Beispiel zum Vergleich:

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

Controlled Components bieten mehr Kontrolle und eine bessere Vorhersehbarkeit
bei der Arbeit mit Formularen.

</details>

<details>
<summary>56. Was sind Uncontrolled Components?</summary>

#### React

#### Uncontrolled Components in React

Uncontrolled Components sind Komponenten, die ihren Zustand im DOM statt im
internen Zustand einer React-Komponente speichern. Auf ihre Werte greift man
ueber **Refs** zu.

#### Hauptmerkmale:

1. **Der Zustand wird vom DOM verwaltet:** Feldwerte werden direkt im DOM
   gespeichert und aktualisiert.

2. **Weniger Integration mit React:** Sie verwenden weder `useState` noch andere
   React-Mittel zur Speicherung des Zustands.

3. **Verwendung von Refs:** Fuer den Zugriff auf Formularwerte wird `ref`
   verwendet.

#### Beispiel fuer eine Uncontrolled Component:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const inputRef = useRef(null);

  const handleSubmit = event => {
    event.preventDefault();
    alert(`Eingegebener Wert: ${inputRef.current.value}`);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Name:
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Senden</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### Wann sollte man Uncontrolled Components verwenden?

- Wenn nur minimale React-Integration mit dem DOM noetig ist.

- Wenn Formularwerte von externen Bibliotheken verarbeitet werden.

- Wenn ein einfaches Formular ohne komplexe Logik benoetigt wird.

#### Vorteile:

- Einfache Umsetzung fuer simple Formulare.

- Weniger Code fuer Zustandsverwaltung.

#### Nachteile:

- Weniger Kontrolle ueber die Werte.

- Validierung oder Datensynchronisierung sind schwieriger umzusetzen.

- Ein weniger React-orientierter Ansatz.

</details>

<details>
<summary>57. Wie erstellt man ein Formular in React?</summary>

#### React

#### Erstellung eines Formulars in React

Formulare in React werden mit dem Element `<form>` und passenden Controls wie
`<input>`, `<textarea>` oder `<select>` erstellt. Die Reaktivitaet wird durch
Controlled oder Uncontrolled Components erreicht.

#### Controlled Form

Controlled Components verwenden `state`, um die Werte der Formularfelder zu
verfolgen.

#### Beispiel:

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

#### Eigenschaften:

- Jedes Feld wird ueber `state` gesteuert.

- Formulardaten lassen sich leicht synchronisieren und verarbeiten.

#### Uncontrolled Form

Uncontrolled Components verwenden `ref` fuer den direkten Zugriff auf
DOM-Elemente.

#### Beispiel:

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

#### Eigenschaften:

- Auf die Werte wird ueber `ref` zugegriffen.

- Geeignet fuer einfache Formulare.

#### Die wichtigsten Punkte:

1. **Controlled Form:**

- Verwendet `state`.

- Eignet sich besser fuer komplexe Formulare, die Validierung oder
  Synchronisierung benoetigen.

2. **Uncontrolled Form:**

- Verwendet `ref`.

- Ein einfacher Ansatz ohne komplexe Zustandslogik.

Die Wahl des Ansatzes haengt von der Komplexitaet des Formulars und den
Anforderungen an die Interaktion mit den Feldern ab.

</details>

<details>
<summary>58. Wie verwendet man Props-Validierung in React?</summary>

#### React

Zur Validierung von Props in React werden **PropTypes** verwendet.

1. **PropTypes installieren, falls noch nicht vorhanden**

```sh
npm install prop-types
```

2. **Verwendung von PropTypes in einer funktionalen Komponente:**

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

// PropTypes definieren
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Standardwerte
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

3. **Verwendung in einer Klassenkomponente:**

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

// PropTypes definieren
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Standardwerte
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

#### Verfuegbare PropTypes:

- `PropTypes.string`
- `PropTypes.number`
- `PropTypes.bool`
- `PropTypes.array`
- `PropTypes.object`
- `PropTypes.func`
- `PropTypes.node` fuer JSX oder Text
- `PropTypes.element` fuer ein React-Element
- `PropTypes.oneOf(['value1', 'value2'])` fuer eine Liste erlaubter Werte
- `PropTypes.shape({ key: PropTypes.type })` fuer ein Objekt mit bestimmter
  Struktur

#### Fazit:

PropTypes helfen dabei, Fehler durch Typpruefung von Props zu vermeiden. In
TypeScript wird dies jedoch bereits auf Sprachebene abgedeckt.

</details>

<details>
<summary>59. Worin unterscheidet sich React Router von normalem Routing?</summary>

#### React

#### Unterschied zwischen React Router und klassischem Routing:

| Kriterium             | React Router                                                        | Klassisches Routing (Server-Side Routing)    |
| --------------------- | ------------------------------------------------------------------- | -------------------------------------------- |
| **Art des Routings**  | Client-seitig (SPA)                                                 | Server-seitig (MPA)                          |
| **Seitenwechsel**     | Ohne Seitenneuladung, JavaScript aktualisiert die URL               | Bei jedem Wechsel wird die Seite neu geladen |
| **Geschwindigkeit**   | Schneller, da kein neuer Serveraufruf fuer jede Seite notwendig ist | Langsamer durch neue HTTP-Anfragen           |
| **SEO**               | Ohne SSR schwaecher, aber mit Next.js loesbar                       | Besser, da Inhalte direkt vom Server kommen  |
| **Datenverarbeitung** | Dynamisches Rendern von Komponenten                                 | Laden von HTML vom Server                    |
| **Einrichtung**       | React Router wird benoetigt                                         | Nutzt Standardfunktionen des Servers         |

</details>

<details>
<summary>60. Wie uebergibt man Props in React Router?</summary>

#### React

Um Props an Komponenten bei der Verwendung von **React Router** zu uebergeben,
gibt es mehrere Ansaetze:

1. **Verwendung der `Route`-Komponente zur Props-Uebergabe:** Props koennen
   ueber die Komponente `Route` mit `render` oder `children` uebergeben werden.

**Beispiel:**

```jsx
import { Route } from 'react-router-dom';

<Route path="/profile" render={props => <Profile {...props} user="John" />} />;
```

Hier werden zusaetzliche Props an die Komponente `Profile` uebergeben.

2. **Verwendung von `useNavigate()` zur Datenuebergabe ueber Navigation mit
   `state`:** Beim Wechsel auf eine neue Seite koennen Daten ueber `state`
   uebergeben werden.

**Beispiel:**

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

**Empfangen der Props in der Komponente:**

```jsx
import { useLocation } from 'react-router-dom';

function Profile() {
  const location = useLocation();
  const user = location.state?.user;

  return <div>Welcome, {user}</div>;
}
```

3. **Verwendung von `useParams()` fuer den Zugriff auf Routenparameter:** Wenn
   Parameter ueber die URL uebergeben werden sollen, kann `useParams()`
   verwendet werden.

**Beispiel:**

```jsx
import { useParams } from 'react-router-dom';

function Profile() {
  const { id } = useParams();

  return <div>User ID: {id}</div>;
}
```

#### Fazit:

- `render` oder `children` eignen sich fuer die direkte Props-Uebergabe.

- `useNavigate()` und `state` erlauben die Datenuebergabe zwischen Seiten.

- `useParams()` ist praktisch fuer dynamische Parameter in der URL.

</details>

<details>
<summary>61. Welche Moeglichkeiten zur Stilgestaltung gibt es in React-Komponenten?</summary>

#### React

#### Moeglichkeiten zur Verwendung von Styles in React-Komponenten:

1. **Inline-Styles:** Styles werden direkt als Objekt ueber das Attribut `style`
   uebergeben.

```jsx
function InlineStyle() {
  const style = {
    color: 'blue',
    fontSize: '20px',
  };

  return <h1 style={style}>Hallo, React!</h1>;
}
```

2. **CSS-Dateien:** Gewoehnliche CSS-Dateien werden in die Komponente
   importiert.

```jsx
import './styles.css';

function CSSFile() {
  return <h1 className="heading">Hallo, React!</h1>;
}
```

```css
/* styles.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

3. **CSS-Module:** Erzeugen lokal isolierte Styles fuer jede Komponente.

```jsx
import styles from './styles.module.css';

function CSSModule() {
  return <h1 className={styles.heading}>Hallo, React!</h1>;
}
```

```css
/* styles.module.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

4. **Styled Components:** Verwendung der Bibliothek `styled-components`, um
   Styles in JavaScript zu schreiben.

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
  return <Heading>Hallo, React!</Heading>;
}
```

5. **Emotion:** Eine alternative Styling-Bibliothek, aehnlich wie
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
  return <h1 css={style}>Hallo, React!</h1>;
}
```

6. **CSS-in-JS:** Erstellung dynamischer Styles in gewoehnlichen
   JavaScript-Dateien.

```jsx
function CSSInJS({ isBlue }) {
  const style = {
    color: isBlue ? 'blue' : 'red',
    fontSize: '20px',
  };

  return <h1 style={style}>Hallo, React!</h1>;
}
```

7. **Tailwind CSS:** Ein Utility-First-Framework zur Stilgestaltung von
   Komponenten.

```jsx
function TailwindExample() {
  return <h1 className="text-blue-500 text-2xl">Hallo, React!</h1>;
}
```

**Einrichtung von Tailwind CSS:** Fuege die Abhaengigkeiten hinzu und
konfiguriere das Projekt.

8. **Sass/SCSS:** Erweiterte CSS-Syntax mit Unterstuetzung fuer Variablen,
   Mixins und Verschachtelung.

```bash
npm install sass
```

```jsx
import './styles.scss';

function SCSSExample() {
  return <h1 className="heading">Hallo, React!</h1>;
}
```

```scss
/* styles.scss */
.heading {
  color: blue;
  font-size: 20px;
}
```

#### Die Wahl der Methode haengt ab von:

- Der Groesse des Projekts.

- Dem Bedarf an Style-Isolation.

- Den Vorlieben des Teams.

</details>

<details>
<summary>62. Worin liegt der Vorteil von CSS-Modulen?</summary>

#### React

**Vorteile von CSS-Modulen:**

1. **Lokaler Geltungsbereich:** Styles gelten nur fuer die jeweilige Komponente
   und nicht global. Das verhindert Klassenkonflikte und sorgt dafuer, dass
   Styles keine anderen Teile der Anwendung beeinflussen.

2. **Eindeutige Klassennamen:** CSS-Module erzeugen automatisch eindeutige
   Klassennamen, wodurch das Risiko von Style-Ueberschreibungen minimiert wird.

3. **Einfachere Wartung:** Beim Skalieren eines Projekts entstehen weniger
   Probleme, weil jede Komponente ihre eigenen Styles hat. Dadurch bleibt der
   Code organisierter und leichter verstaendlich.

4. **Isolation:** Jede Komponente besitzt komplett isolierte Styles, was
   Refactoring und Style-Aenderungen ohne Nebenwirkungen erleichtert.

5. **Einfachere Integration mit JavaScript:** Dynamische Styles lassen sich
   ueber JavaScript umsetzen, indem Klassen je nach Komponentenstatus gewechselt
   werden.

Das hilft, Ordnung in grossen Anwendungen zu halten und die Wahrscheinlichkeit
von Styling-Fehlern zu verringern.

</details>

<details>
<summary>63. Welche Ansaetze kennst du zur Optimierung der Performance von React-Anwendungen?</summary>

#### React

#### Ansaetze zur Optimierung der Performance von React-Anwendungen:

1. **Memoisierung von Komponenten:**

- Verwende `React.memo` fuer funktionale Komponenten, die nicht haeufig
  geaenderte Props erhalten.
- Verwende `PureComponent` bei Klassenkomponenten.

2. **Memoisierung von Werten und Funktionen:**

- `useMemo` fuer berechnete Werte, die von bestimmten Abhaengigkeiten abhaengen.
- `useCallback` fuer Funktionen, die an Kindkomponenten uebergeben werden.

3. **Optimierung des Listen-Renderings:**

Verwende immer einen eindeutigen `key` fuer Elemente in Listen. Vermeide
unnuetiges erneutes Rendern von Komponenten.

4. **Dynamisches Laden von Komponenten:**

- Verwende `React.lazy`, um Komponenten bei Bedarf zu laden.
- In Kombination mit `Suspense` laesst sich damit das Laden der Anwendung
  optimieren.

5. **Kontrolle ueber Re-Render:**

- Verwende `shouldComponentUpdate` oder `React.memo`, um unnoetige Renderings zu
  reduzieren.
- Nutze `React.Fragment` statt zusaetzlicher Wrapper-Elemente.

6. **Code Splitting:**

- Setze `React.lazy` und dynamische Importe ein, um Modulcode nur dann zu laden,
  wenn er gebraucht wird.

7. **Zustandsverwaltung:**

- Vermeide globalen State fuer Komponenten, die ihn nicht brauchen.
- Verlagere aufwendige Zustandslogik in Context oder spezialisierte Bibliotheken
  wie Redux oder Zustand.

8. **Listen-Virtualisierung:**

- Verwende Bibliotheken wie `react-window` oder `react-virtualized`, um nur
  sichtbare Listenelemente zu rendern.

9. **Bildoptimierung:**

- Verwende Lazy Loading fuer Bilder.
- Komprimiere und optimiere Bilder vor dem Einsatz.

10. **Weniger Komponenten im DOM:**

- Vermeide uebermaessige Verschachtelung von Komponenten.
- Entferne unnoetige DOM-Elemente bei Seitenwechseln.

11. **Caching von Daten:**

- Verwende Caching-Bibliotheken wie `SWR` oder `React Query`, um Daten besser zu
  verwalten und Serveranfragen zu reduzieren.

12. **Verwendung eines Production-Builds:**

- Stelle sicher, dass die Anwendung im Production-Modus gebaut wird, zum
  Beispiel mit `npm run build`.
- Verwende Werkzeuge wie `Webpack` zur Minimierung und Optimierung des Codes.

13. **Profiling der Anwendung:**

- Verwende `React DevTools`, um die Performance zu analysieren.
- Finde Engpaesse mit dem Tab `Profiler`.

14. **Optimierung von CSS und Styles:**

- Verwende CSS-in-JS-Loesungen wie `styled-components` nur dort, wo sie wirklich
  gebraucht werden.
- Minimiere Styles mit `PostCSS` oder anderen Tools.

Diese Ansaetze helfen dabei, Verzoegerungen zu reduzieren, die
Rendering-Geschwindigkeit zu erhoehen und die Gesamtperformance der Anwendung zu
verbessern.

</details>

<details>
<summary>64. Was ist der Unterschied zwischen `memo` und `useMemo`?</summary>

#### React

#### Unterschied zwischen `memo` und `useMemo`

| Kriterium                         | `memo`                                                                              | `useMemo`                                                          |
| --------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **Was ist das?**                  | Higher-Order Function bzw. HOC                                                      | Hook                                                               |
| **Zweck**                         | Verhindert erneutes Rendern einer Komponente, wenn sich Props nicht geaendert haben | Speichert das Ergebnis einer Berechnung zwischen Render-Vorgaengen |
| **Wo wird es verwendet?**         | Umhuellt eine Komponente                                                            | Innerhalb einer Komponente                                         |
| **Beispiel**                      | `export default memo(MyComponent);`                                                 | `const value = useMemo(() => compute(), [deps]);`                  |
| **Was wird gecacht?**             | Die gesamte Komponente                                                              | Das Ergebnis einer Funktion                                        |
| **Wann sollte man es einsetzen?** | Wenn eine Komponente mit denselben Props ohne Aenderungen erneut gerendert wird     | Wenn eine Berechnung teuer ist und von bestimmten Werten abhaengt  |

#### Wann verwendet man was?

- `memo`, wenn eine Komponente dieselben Props erhaelt und kein erneuter Render
  noetig ist.

- `useMemo`, wenn das Ergebnis einer Berechnung gespeichert werden soll, damit
  es nicht bei jedem Rendern neu berechnet wird.

</details>

<details>
<summary>65. Warum sollte man an `setState()` eine Funktion uebergeben?</summary>

#### React

Eine Funktion sollte an `setState()` uebergeben werden, wenn der neue Zustand
vom vorherigen Zustand abhaengt. Das sorgt fuer korrekte Updates, weil
`setState()` asynchron arbeitet und mehrere Aufrufe gebuendelt werden koennen.

#### Beispiel mit einem Problem:

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

Hier wird `count + 1` zweimal mit demselben alten Wert von `count` berechnet.
Deshalb erhoeht sich der Wert nur um 1 statt um 2.

#### Richtiger Ansatz:

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

Hier erhaelt `setCount()` den aktuellen Wert `prevCount`, daher funktioniert das
Inkrement korrekt und erhoeht den Wert um 2.

</details>

<details>
<summary>66. Wie werden Refs in React zur Interaktion mit DOM-Elementen verwendet?</summary>

#### React

Refs in React werden verwendet, um direkt auf DOM-Elemente oder Komponenten
zuzugreifen und dabei den normalen Mechanismus ueber Props und State zu umgehen.

1. **Erstellen von Refs:** Verwende `React.createRef()`, um eine Ref zu
   erzeugen.

```jsx
const myRef = React.createRef();
```

2. **Verknuepfung der Ref mit einem Element:** Die Ref wird ueber das Attribut
   `ref` an ein DOM-Element gebunden.

```jsx
<input ref={myRef} />
```

3. **Interaktion mit dem DOM:** Ueber `.current` erhaelt man Zugriff auf das
   DOM-Element. Zum Beispiel, um den Fokus zu setzen:

```jsx
myRef.current.focus();
```

4. **Einschraenkungen:** Refs sollten nicht zur Zustandsverwaltung verwendet
   werden. Sie sind nur fuer direkte DOM-Interaktion gedacht, etwa fuer Fokus,
   Textauswahl oder Animationen.

5. **Funktionale Komponenten:** Seit React 16.8 wird in funktionalen Komponenten
   `useRef` verwendet.

```jsx
const inputRef = useRef();
inputRef.current.focus();
```

</details>

<details>
<summary>67. Wie verwendet man Inner HTML in React?</summary>

#### React

- In React wird zum Einfuegen von HTML-Inhalt in das DOM das Attribut
  `dangerouslySetInnerHTML` verwendet. Damit kann HTML direkt in eine Komponente
  eingesetzt werden. Dieser Ansatz ist jedoch riskant, weshalb er "dangerously"
  heisst: Rohes HTML kann zu XSS-Angriffen fuehren, wenn die Daten nicht
  bereinigt wurden.

#### Beispiel fuer `dangerouslySetInnerHTML`:

```jsx
const MyComponent = () => {
  const htmlContent = '<p>Das ist <strong>HTML</strong>-Inhalt.</p>';

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
};
```

#### Erklaerung:

- `dangerouslySetInnerHTML` erwartet ein Objekt, bei dem der Schluessel `__html`
  den HTML-String enthaelt.

- Das erlaubt das Einbetten von HTML in einer Komponente, ist aber unsicher,
  wenn der Inhalt aus unvertrauten Quellen stammt.

#### Wann sollte man es verwenden?

- Wenn die Sicherheit der Daten gewaehrleistet ist, zum Beispiel bei Inhalten
  vom eigenen Server.

- Wenn dynamischer HTML-Inhalt eingebettet werden muss, etwa Seiten oder Artikel
  mit HTML.

#### Warnhinweise:

- Sicherheit: Verwende `dangerouslySetInnerHTML` niemals fuer Daten von Nutzern
  oder externen Quellen, ohne sie vorher von schaedlichen Skripten zu
  bereinigen.

- Zur Bereinigung des Inhalts koennen Bibliotheken wie `DOMPurify` verwendet
  werden, um XSS-Angriffe zu vermeiden.

**Beispiel fuer die Bereinigung vor dem Einfuegen:**

```jsx
import DOMPurify from 'dompurify';

const MyComponent = () => {
  const dirtyHtml = "<img src=x onerror=alert('XSS')>";
  const cleanHtml = DOMPurify.sanitize(dirtyHtml);

  return <div dangerouslySetInnerHTML={{ __html: cleanHtml }} />;
};
```

`dangerouslySetInnerHTML` sollte also nur mit Vorsicht und nur dann verwendet
werden, wenn die Sicherheit des Inhalts gewaehrleistet ist.

</details>

<details>
<summary>68. Was ist ReactDOMServer?</summary>

#### React

**`ReactDOMServer`** ist eine Bibliothek aus dem React-Umfeld, die zum Rendern
von React-Komponenten auf dem Server verwendet wird, also fuer Server-Side
Rendering (SSR). Dadurch kann HTML bereits auf dem Server erzeugt und an den
Client gesendet werden, was Performance und SEO verbessern kann.

#### Wichtige Methoden:

1. **`ReactDOMServer.renderToString()`:** Rendert React-Elemente in einen
   HTML-String. Das ist die Hauptmethode zur Erzeugung statischen HTML fuer das
   erste Laden der Seite.

```jsx
import ReactDOMServer from 'react-dom/server';
const html = ReactDOMServer.renderToString(<App />);
```

2. **`ReactDOMServer.renderToStaticMarkup()`:** Rendert HTML ohne zusaetzliche
   React-spezifische Attribute wie `data-reactroot`. Das eignet sich fuer
   vollstaendig statische Seiten.

```jsx
const html = ReactDOMServer.renderToStaticMarkup(<App />);
```

3. **`ReactDOMServer.hydrate()`:** Wird auf der Client-Seite verwendet, um
   serverseitig gerendertes HTML zu "hydrieren", also mit React-Interaktivitaet
   zu versehen.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

#### Einsatzgebiete:

- **SSR (Server-Side Rendering):** React-Komponenten werden auf dem Server statt
  im Browser gerendert, sodass eine fertige HTML-Seite an den Client gesendet
  werden kann.

- **SEO:** Weil der Server direkt HTML liefert, koennen Suchmaschinen Seiten
  indexieren, ohne JavaScript ausfuehren zu muessen.

`ReactDOMServer` ermoeglicht also vorgenerierte Seiten, was die Ladezeit
verbessern kann und fuer SEO nuetzlich ist.

</details>

<details>
<summary>69. Wofuer wird das Paket `react-dom` verwendet?</summary>

#### React

Das Paket `react-dom` wird verwendet, damit React mit dem echten DOM in
Webanwendungen arbeiten kann. Die wichtigsten Funktionen sind:

1. **`ReactDOM.render()`:** Wird verwendet, um eine Komponente in das echte DOM
   zu rendern. Das ist die grundlegende Methode, die React mit HTML-Elementen
   verbindet.

```jsx
ReactDOM.render(<App />, document.getElementById('root'));
```

2. **`ReactDOM.hydrate()`:** Wird fuer die Hydration serverseitig gerenderten
   HTML verwendet, zum Beispiel bei SSR. Dadurch uebernimmt React die Kontrolle
   ueber bereits vorhandenes HTML.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

3. **`ReactDOM.createPortal()`:** Erlaubt das Rendern von Kindelementen an einer
   anderen Stelle im DOM ausserhalb der normalen Komponenten-Hierarchie. Das
   wird haeufig fuer Modalfenster, Tooltips oder Popups verwendet.

```jsx
ReactDOM.createPortal(<Modal />, document.getElementById('modal-root'));
```

4. **`ReactDOM.unmountComponentAtNode()`:** Entfernt eine React-Komponente aus
   dem DOM.

```jsx
ReactDOM.unmountComponentAtNode(document.getElementById('root'));
```

5. **`ReactDOM.findDOMNode()`:** Gibt Zugriff auf das echte DOM-Element einer
   Komponente. Diese Methode wird heute selten verwendet, weil Refs die
   modernere Loesung sind.

- Dieses Paket ist fuer die Arbeit mit dem echten DOM noetig. In den meisten
  Faellen muessen diese Methoden jedoch nicht manuell aufgerufen werden, da sie
  von Build- und Rendering-Werkzeugen automatisch genutzt werden.

</details>

<details>
<summary>70. Wie verwendet man `React.lazy` und `React.Suspense`, um Anwendungscode zu laden?</summary>

#### React

`React.lazy` und `React.Suspense` werden in React fuer das **dynamische Laden
von Komponenten** verwendet. Dadurch kann **Code Splitting** umgesetzt werden.
Das bedeutet, dass Teile des Codes nur dann geladen werden, wenn sie wirklich
benoetigt werden, was die Performance der Anwendung verbessert.

#### Wie funktioniert das?

1. **`React.lazy()`** erlaubt das verzegerte Laden einer Komponente.

2. **`React.Suspense`** umhuellt Code, der noch nicht geladen wurde, und zeigt
   waehrenddessen einen Fallback-Inhalt an, zum Beispiel einen Loader.

#### Beispiel:

1. **Dynamisches Laden einer Komponente:** Zuerst wird eine Komponente
   definiert, die dynamisch geladen werden soll.

```jsx
// Dynamisch geladene Komponente
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Wrapper mit `React.Suspense`:** Danach wird `React.Suspense` verwendet, um
   waehrend des Ladens einen Loader anzuzeigen.

```jsx
function App() {
  return (
    <div>
      <h1>Meine Anwendung</h1>

      {/* Wrapper fuer dynamisch geladene Komponenten */}
      <React.Suspense fallback={<div>Laden...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Beschreibung:**

- `React.lazy()` erwartet eine Funktion, die ein Modul dynamisch importiert.

- `React.Suspense` umhuellt die Komponente, die `React.lazy()` verwendet, und
  zeigt einen Fallback an, in diesem Fall den Text "Laden...", bis die
  Komponente verfuegbar ist.

#### Vorteile:

- Verbessert die Performance, weil Komponenten nur bei Bedarf geladen werden.

- Verkleinert das initiale Ladevolumen, weil Teile der Anwendung erst bei Bedarf
  geladen werden.

Dieser Ansatz ist besonders in grossen Anwendungen nuetzlich, in denen der Code
in Teile aufgeteilt werden kann, um die Ladezeit der Seite zu verkleinern.

</details>

<details>
<summary>71. Was sind die besten Sicherheitspraktiken in React?</summary>

#### React

#### Beste Sicherheitspraktiken in React:

1. **XSS verhindern (Cross-Site Scripting):**

- Bereinige Daten von Nutzern immer, bevor sie in einer Komponente angezeigt
  werden.
- Verwende JSX. React escaped Eingaben automatisch, dennoch sollte
  `dangerouslySetInnerHTML` moeglichst vermieden werden.
- Wenn `dangerouslySetInnerHTML` noetig ist, muss der Inhalt sicher bereinigt
  sein.

2. **Code-Injektionen vermeiden:**

- Uebergib ungepruefte Daten niemals an `eval()`, `setTimeout()`,
  `setInterval()` oder andere Funktionen, die Code ausfuehren.
- Verwende fuer dynamische Importe kontrollierte Mechanismen wie `React.lazy()`.

3. **Sicherer API-Zugriff:**

- Verwende HTTPS, um Daten bei der Uebertragung zu schuetzen.
- Nutze Authentifizierung, Autorisierung und sichere Cookies wie `HttpOnly` und
  `Secure`.

4. **Schutz vor CSRF (Cross-Site Request Forgery):**

- Verwende CSRF-Tokens fuer alle Anfragen, die Daten auf dem Server aendern.
- Nutze das Cookie-Flag `SameSite`, um den Zugriff auf dieselbe Domain zu
  beschraenken.

5. **Zugriffskontrolle:**

- Pruefe vor dem Senden einer Anfrage an den Server, ob der Benutzer die
  noetigen Rechte hat.
- Verlasse dich nicht auf Pruefungen im Client. Die endgueltige Kontrolle muss
  immer auf dem Server stattfinden.

6. **Schutz bei offenen Eingabefeldern:**

- Lege fuer Formulare und Eingabefelder, die Nutzerdaten annehmen, klare
  Einschraenkungen fuer erlaubte Werte fest.

7. **Abhaengigkeiten aktualisieren:**

- Pruefe und aktualisiere Abhaengigkeiten regelmaessig, um moegliche
  Sicherheitsluecken zu erkennen. Nutze dafuer `npm audit` oder aehnliche
  Werkzeuge.

8. **Umgang mit Geheimnissen:**

- Speichere keine Geheimnisse wie API-Schluessel oder Passwoerter im
  Client-Code. Sie gehoeren auf den Server oder in Umgebungsvariablen.

9. **Content Security Policy (CSP) verwenden:**

- Verwende CSP, um die Ausfuehrung unerwuenschter Skripte auf deiner Seite zu
  verhindern.

10. **Schutz vor Clickjacking:**

- Verwende Header wie `X-Frame-Options` oder `Content-Security-Policy`, um zu
  verhindern, dass deine Seite in ein `<iframe>` auf fremden Websites
  eingebettet wird.

Die Einhaltung dieser Praktiken hilft, Sicherheitsrisiken in React-Anwendungen
zu verringern.

</details>

<details>
<summary>72. Wie behandelt man Fehler in React mit Error Boundaries?</summary>

#### React

**Error Boundaries** in React ermoeglichen es, Fehler in Komponenten waehrend
des Renderns, in Lifecycle-Methoden und in Konstruktoren abzufangen und zu
behandeln, ohne die gesamte Anwendung abstuerzen zu lassen.

#### Wichtige Punkte:

- Eine Error Boundary ist eine Komponente, die andere Komponenten umschliesst
  und Fehler in deren Code abfangen kann.

- **Error Boundaries** fangen nur Fehler in ihren Nachkommen ab. Fehler in der
  Error Boundary selbst werden nicht abgefangen.

#### Wie implementiert man eine Error Boundary?

1. **Erstellen einer Error Boundary:** Dafuer muessen zwei Methoden
   implementiert werden:

- `static getDerivedStateFromError(error)` aktualisiert den Zustand, wenn ein
  Fehler auftritt.

- `componentDidCatch(error, info)` erlaubt es, Fehler zu protokollieren, etwa
  durch das Senden an einen Server.

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }

  static getDerivedStateFromError(error) {
    // Zustand aktualisieren, um eine Fallback-UI anzuzeigen
    return { hasError: true, error };
  }

  componentDidCatch(error, info) {
    // Logik fuer Fehlerprotokollierung, zum Beispiel an einen Server
    console.error('Error caught:', error, info);
  }

  render() {
    if (this.state.hasError) {
      // Fallback-UI anzeigen, wenn ein Fehler aufgetreten ist
      return <h1>Etwas ist schiefgelaufen.</h1>;
    }

    return this.props.children;
  }
}
```

2. **Verwendung der Error Boundary:** Komponenten, die Fehler ausloesen koennen,
   werden mit `ErrorBoundary` umschlossen.

```jsx
const App = () => {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
};
```

3. **Fallback-UI:** Wenn ein Fehler auftritt, kann die Error Boundary einen
   Fallback anzeigen, etwa eine Fehlermeldung, einen Retry-Button oder andere
   Wiederherstellungsaktionen.

#### Wichtige Hinweise:

- Eine Error Boundary faengt keine Fehler in Event-Handlern wie `onClick`, in
  asynchronem Code, Timern oder Netzwerkanfragen ab. Dafuer sollten `try-catch`
  oder andere Mechanismen verwendet werden.

- Tritt der Fehler in der Error Boundary selbst auf, wird er nicht abgefangen.

**Error Boundaries** verbessern die Stabilitaet einer Anwendung, weil sie Fehler
auffangen und behandeln koennen, ohne die gesamte App zu stoppen.

</details>

<details>
<summary>73. Was ist Inheritance Inversion?</summary>

#### React

- **Inheritance Inversion** bezeichnet eine Situation, in der eine Klasse, die
  eigentlich die Basisklasse sein sollte, faktisch von ihren Nachkommen abhaengt
  oder die Kontrolle ueber Logik verliert, die in der Vererbungshierarchie
  liegen sollte.

#### Probleme der Inheritance Inversion

- Verletzt das Liskov Substitution Principle (LSP).

- Es wird schwierig, die Basisklasse zu aendern oder zu erweitern, ohne alle
  Nachkommen zu beeinflussen.

- Die Komplexitaet steigt durch gegenseitige Abhaengigkeiten.

#### Beispiel fuer schlechte Praxis

```js
class Parent {
  method() {
    throw new Error('Die Methode muss im Nachkommen implementiert werden');
  }
}

class Child extends Parent {
  method() {
    return 'Implementierung im Nachkommen';
  }
}
```

Hier besitzt die Basisklasse keine eigene Logik und zwingt Nachkommen dazu, das
Verhalten zu implementieren. Das ist ein Zeichen fuer Inheritance Inversion.

#### Alternative: Komposition statt Vererbung

```js
class Behavior {
  method() {
    return 'Implementierung ohne Inversion';
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

Dieser Ansatz beseitigt die Abhaengigkeit der Elternklasse von ihren Nachkommen
und macht den Code flexibler.

</details>

<details>
<summary>74. Was ist Polling und wie setzt man es in React um?</summary>

#### React

**Polling** bezeichnet das periodische Senden von Anfragen an den Server, um
aktualisierte Daten zu erhalten. Das ist nuetzlich, wenn der Server weder
WebSockets noch Server-Sent Events unterstuetzt, der Client aber trotzdem neue
Informationen ohne Seitenneuladung erhalten soll.

#### Umsetzung von Polling in React

Polling kann mit `setInterval`, `setTimeout` oder mit React-Hooks wie
`useEffect` umgesetzt werden.

1. **Verwendung von `setInterval`**

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

    fetchData(); // Sofort beim Laden ausfuehren

    const interval = setInterval(fetchData, 5000); // Polling alle 5 Sekunden

    return () => clearInterval(interval); // Cleanup beim Unmount
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Laden...'}</div>;
};
```

- `fetchData()` laedt Daten vom Server.
- `setInterval` startet das Polling alle 5 Sekunden.
- `clearInterval` stoppt das Polling beim Unmount.

2. **Verwendung von `setTimeout` fuer ein dynamisches Intervall**

Wenn der Server Anfrage-Limits hat, ist `setTimeout` oft besser geeignet, um
ueberlappende Anfragen zu vermeiden.

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
        console.error('Anfragefehler', error);
      } finally {
        if (isMounted) setTimeout(fetchData, 5000);
      }
    };

    fetchData();

    return () => {
      isMounted = false; // Verhindert State-Updates nach dem Unmount
    };
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Laden...'}</div>;
};
```

Hier wird `setTimeout` erst nach Abschluss der vorherigen Anfrage ausgefuehrt,
was ueberschneidende Requests verhindert.

#### Fazit

- `setInterval` eignet sich fuer konstantes Polling, kann aber zu
  ueberschneidenden Anfragen fuehren.
- `setTimeout` bietet mehr Kontrolle und eignet sich besser fuer adaptives
  Polling.
- Bei hohem Lastaufkommen sollten WebSockets oder Server-Sent Events in Betracht
  gezogen werden.

</details>

<details>
<summary>75. Wie setzt man in React eine bidirektionale Datenbindung um?</summary>

#### React

In React wird bidirektionale Datenbindung mit **Controlled Components**
umgesetzt. Dabei wird der Zustand (`state`) einer Komponente mit einem
Eingabefeld (`input`) synchronisiert.

#### Beispiel:

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
      <p>Eingegebener Wert: {value}</p>
    </div>
  );
};

export default TwoWayBinding;
```

#### Wie funktioniert das?

1. **`value`** speichert den aktuellen Zustand des eingegebenen Werts.

2. **`onChange`** aktualisiert den Zustand, wenn sich das Eingabefeld aendert.

3. **Der aktualisierte `value`** wird in der UI angezeigt und sorgt so fuer die
   bidirektionale Bindung.

Dieser Ansatz ermoeglicht die Kontrolle ueber Eingaben sowie Validierung und
Verarbeitung vor der Aktualisierung des Zustands.

</details>

<details>
<summary>76. Was ist Reverse Data Flow in React?</summary>

#### React

Reverse Data Flow in React bedeutet, dass Zustandsaenderungen von einer
Kindkomponente zur Elternkomponente weitergegeben werden. Das ist das Gegenteil
des normalen Datenflusses, bei dem die Elternkomponente Props an das Kind
uebergibt.

#### In React wird Reverse Data Flow meist so umgesetzt:

1. **Callback-Funktionen:**

- Die Kindkomponente ruft einen Callback auf, der ihr ueber Props uebergeben
  wurde, um die Elternkomponente ueber Zustandsaenderungen zu informieren oder
  Aktionen auszufuehren.

- Wenn sich zum Beispiel ein Wert in der Kindkomponente aendert, kann eine
  Funktion der Elternkomponente aufgerufen werden, die den Zustand aktualisiert.

2. **Beispiel:**

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

- In diesem Beispiel gibt die Kindkomponente den Wert ueber die Funktion
  `onValueChange` an die Elternkomponente weiter. Das ist Reverse Data Flow.

</details>

<details>
<summary>77. Was ist State-Mutation und wie vermeidet man sie?</summary>

#### React

State-Mutation bedeutet, dass ein Objekt oder Array, das den Zustand speichert,
direkt veraendert wird, ohne zuvor eine Kopie zu erstellen. In React fuehrt das
zu unvorhersehbarem Verhalten, weil React die Aenderung nicht erkennt und die
Komponente nicht erneut rendert.

#### Um State-Mutationen zu vermeiden, sollte man:

1. **Kopien der Daten erstellen**, bevor sie geaendert werden. Zum Beispiel bei
   Arrays und Objekten:

- Fuer Arrays: `setItems([...items, newItem])`
- Fuer Objekte: `setUser({...user, name: 'John'})`

2. **Nicht-mutierende Methoden verwenden**, etwa `map()`, `filter()` oder
   `reduce()` fuer Arrays beziehungsweise `Object.assign()` fuer Objekte.

So kann React Aenderungen korrekt erkennen und Komponenten neu rendern.

 </details>

<details>
<summary>78. Was ist der Strict Mode in React und welche Vorteile hat er?</summary>

#### React

**Strict Mode** ist ein spezielles React-Werkzeug zum Erkennen potenzieller
Probleme im Code. Im Production-Betrieb hat er keine Auswirkungen, hilft aber
waehrend der Entwicklung, die Codequalitaet zu verbessern.

Er wird aktiviert, indem Komponenten mit `<React.StrictMode>` umschlossen
werden:

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

#### Vorteile des Strict Mode

| **Funktion**                                             | **Beschreibung**                                                                                               |
| -------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| **Erkennt unsichere Lifecycle-Methoden**                 | Warnt vor veralteten Methoden wie `componentWillMount`, `componentWillReceiveProps` und `componentWillUpdate`. |
| **Ruft Funktionen waehrend der Entwicklung doppelt auf** | Hilft, Side Effects in `useEffect` und anderen Hooks zu finden.                                                |
| **Warnt vor veralteten APIs**                            | Weist auf alte Kontexte wie `contextType` und unsichere Muster hin.                                            |
| **Erkennt unvorhersehbares Verhalten**                   | Zum Beispiel wird `useEffect` doppelt aufgerufen, um das Cleanup zu pruefen.                                   |

#### Sollte man ihn verwenden?

Ja, wenn Probleme schon in der Entwicklungsphase vermieden werden sollen. Der
doppelte Render kann etwas stoeren, hilft aber dabei, versteckte Fehler im Code
zu finden.

</details>

<details>
<summary>79. Welche empfohlenen Wege gibt es zur Pruefung statischer Typen?</summary>

#### React

1. **TypeScript:** Der populaerste und vollstaendigste Ansatz fuer statische
   Typisierung in JavaScript und React. TypeScript fuegt dem Code strenge Typen
   hinzu und erlaubt Typpruefung bereits waehrend der Kompilierung.

2. **PropTypes:** Ein eingebauter Mechanismus zur Pruefung von Prop-Typen in
   React-Komponenten. Er validiert Typen zur Laufzeit. Das ist keine statische
   Typisierung zur Compile-Zeit, aber dennoch eine zusaetzliche Absicherung.

```jsx
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};
```

3. **Flow:** Ein weiteres System fuer statische Typisierung in JavaScript. Flow
   ist weniger populaer als TypeScript, erlaubt aber ebenfalls das Hinzufuegen
   und Pruefen von Typen zur Compile-Zeit.

4. **ESLint mit Typisierungs-Plugins:** ESLint kann mit Plugins wie
   `eslint-plugin-flowtype` oder `eslint-plugin-typescript` zur Typpruefung
   verwendet werden, bietet aber nicht dieselbe Tiefe wie TypeScript.

Empfohlen wird **TypeScript**, weil es sich gut in React und andere Werkzeuge
integriert und eine vollwertige statische Typisierung bei der Kompilierung
ermoeglicht.

</details>

<details>
<summary>80. Wie implementiert man Animationen in React?</summary>

#### React

1. **CSS-Animationen:** Der einfachste Weg ist die Verwendung normaler
   CSS-Animationen oder Transitions.

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

2. **React Transition Group:** Fuer komplexere Uebergaenge zwischen Komponenten.
   Dieses Paket hilft bei der Animation beim Hinzufuegen oder Entfernen von
   Komponenten.

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

3. **Framer Motion:** Eine leistungsstarke Bibliothek fuer Animationen, mit der
   sich komplexe Effekte in React umsetzen lassen.

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

4. **React Spring:** Fuer physikbasierte Animationen mit realistischen
   Bewegungen.

```jsx
import { useSpring, animated } from 'react-spring';

const props = useSpring({ opacity: 1, from: { opacity: 0 } });

<animated.div style={props}>Hello</animated.div>;
```

5. **Inline-Styles und JavaScript:** Mit `setState` oder State-Settern koennen
   Styles in Abhaengigkeit vom Zustand geaendert werden.

```jsx
const [opacity, setOpacity] = useState(0);

useEffect(() => {
  setOpacity(1);
}, []);

return <div style={{ opacity }}>Hello</div>;
```

Fuer komplexere Animationseffekte werden **Framer Motion** oder **React Spring**
empfohlen, weil diese Bibliotheken mehr Moeglichkeiten bieten und schwierige
Animationen leichter steuerbar machen.

</details>

<details>
<summary>81. Welche populaersten Animationspakete gibt es fuer React?</summary>

#### React

#### Beliebte Animationspakete in React:

1. **Framer Motion** ist eines der populaersten Pakete fuer Animationen in
   React. Es ist leicht zu verwenden, unterstuetzt Animationen und Uebergaenge,
   funktioniert mit Drag-and-Drop und bietet eine leistungsfaehige API fuer
   komplexe Animationen.

2. **React Spring** ist eine Bibliothek fuer physikbasierte Animationen. Sie
   arbeitet mit Eigenschaften wie Federung und Reibung und eignet sich gut fuer
   komplexe Animationen und Interaktionen.

3. **GSAP (GreenSock Animation Platform)** ist eine leistungsstarke
   Animationsbibliothek, die nicht nur mit React, sondern auch mit anderen
   Frameworks arbeitet. Sie ist fuer ihre Geschwindigkeit und die Moeglichkeit
   bekannt, sehr komplexe Animationen zu erstellen.

4. **React Transition Group** ist eine zentrale Bibliothek fuer
   Uebergangsanimationen in React. Sie erlaubt Animationen fuer Ein- und
   Austritte sowie Zustandswechsel von Komponenten und bietet dabei flexible
   Steuerung.

5. **Lottie for React** ermoeglicht das einfache Einbinden von in After Effects
   erstellten Animationen im JSON-Format. Es eignet sich fuer komplexe
   Animationen wie Icons oder interaktive Elemente.

</details>

<details>
<summary>82. React DevTools: Wie verwendet man sie zum Debugging?</summary>

#### React

1. **Installation von React DevTools**

- Wenn du `Chrome` oder `Firefox` verwendest, installiere einfach die
  Erweiterung `React Developer Tools`:
  - Chrome Web Store
  - Firefox Add-ons

- Wenn du mit `Electron`, `React Native` oder einer anderen nicht
  standardmaessigen Umgebung arbeitest, installiere:

```sh
npm install -g react-devtools
react-devtools
```

2. **Wichtige Tabs und ihre Verwendung**

- `Components`: Ansicht der Komponentenstruktur, des Zustands und der Props.
- `Profiler`: Analyse der Performance und Erkennung unnoetiger Re-Render.

3. **Debugging von Props und State**

- Oeffne den Tab `Components`.
- Waehle eine Komponente aus. Dort siehst du ihre `props`, `state` und
  `context`.
- `state` und `props` koennen direkt in den DevTools angepasst werden, um
  Verhaltensaenderungen zu testen.

4. **Erkennen unnoetiger Renderings**

- Klicke im Tab `Profiler` auf `Record`, fuehre eine Interaktion aus und druecke
  dann `Stop`.
- Achte auf die Farbmarkierung:
  - **Rot** steht fuer teure Renderings.
  - **Gelb** steht fuer mittlere Kosten.
  - **Blau** steht fuer leichte Renderings.
- Optimiere Komponenten mit `React.memo()`, `useMemo()` und `useCallback()`.

5. **Werkzeuge fuer das Debugging der Context API**

- Wenn React Context verwendet wird, kann sein Wert in den DevTools geprueft
  werden.
- Waehle eine Komponente mit `useContext()` aus und oeffne den Tab `Context`.

6. **Render-Debugging im Strict Mode**

- Wenn `React DevTools` zeigt, dass eine Komponente zweimal rendert, pruefe den
  `StrictMode` in `index.js`:

```jsx
<React.StrictMode>
  <App />
</React.StrictMode>
```

- Das verursacht keine Bugs, sondern hilft nur beim Erkennen potenzieller
  Probleme.

7. **Inspektion von Hooks**

- DevTools zeigt den Zustand von Hooks wie `useState`, `useEffect` und
  `useReducer`.
- Im Tab `Components` kann nach Auswahl einer Komponente der Zustand von
  `useState` eingesehen werden.

#### Fazit:

**React DevTools** ist ein leistungsstarkes Werkzeug zum Debuggen von State,
Props, Performance und Context. Verwende `Profiler` zur Optimierung und
`Components`, um Aenderungen an State und Props nachzuverfolgen.

</details>

<details>
<summary>83. Welche populaersten Linter gibt es fuer React?</summary>

#### React

#### Die populaersten Linter fuer React:

1. **ESLint** ist der am weitesten verbreitete Linter fuer `JavaScript` und
   unterstuetzt `React` ueber das Plugin `eslint-plugin-react`. Er prueft den
   Codestil, weist auf Fehler hin und kann zusammen mit Werkzeugen wie
   `Prettier` genutzt werden.

2. **Prettier** ist ein Werkzeug zum automatischen Formatieren von Code und wird
   oft zusammen mit `ESLint` verwendet, um einen einheitlichen Stil
   sicherzustellen.

3. **TSLint** ist ein Linter fuer `TypeScript`, der auch mit `React` verwendet
   werden kann. Heute wird er jedoch weitgehend durch `ESLint` ersetzt, weil
   dieses flexibler ist und besser unterstuetzt wird.

Diese Werkzeuge helfen, eine hohe Codequalitaet aufrechtzuerhalten und Fehler in
grossen Projekten zu vermeiden.

</details>

<details>
<summary>84. Was ist Next.js?</summary>

#### React

**Next.js** ist ein React-Framework, das fertige Loesungen fuer
Server-Side-Rendering (SSR), statische Generierung (SSG), API-Routes, Routing,
Performance-Optimierung und SEO bietet.

#### Hauptfunktionen:

- **Hybrides Rendering:** Unterstuetzung fuer SSR, SSG und ISR.
- **Automatisches Routing:** Dateien in `pages/` werden automatisch zu Routen.
- **API-Routes:** Erstellung von Server-Endpunkten in Dateien unter
  `pages/api/*`.
- **Performance-Optimierung:** automatisches Code Splitting und kleinere
  Bundles.
- **Unterstuetzung fuer den App Router:** neuer Ansatz mit React Server
  Components und `app/` statt `pages/`.
- **Integrierte Unterstuetzung fuer Tailwind, TypeScript, ESLint und weitere
  Technologien**.

Es wird fuer performante Webanwendungen, Blogs, E-Commerce-Loesungen und
komplexe Interfaces eingesetzt.

</details>

<details>
<summary>85. Was sind die wichtigsten Unterschiede zwischen Next.js und React?</summary>

#### React

#### Wichtigste Unterschiede zwischen Next.js und React:

| **Kriterium**                             | **React**                                      | **Next.js**                                                     |
| ----------------------------------------- | ---------------------------------------------- | --------------------------------------------------------------- |
| **Typ**                                   | Bibliothek zum Erstellen von UIs               | Framework auf Basis von React                                   |
| **Rendering**                             | Nur clientseitig (CSR)                         | Unterstuetzt CSR, SSR, SSG und ISR                              |
| **Routing**                               | Muss manuell mit React Router umgesetzt werden | Dateibasiertes Routing mit `pages/` oder `app/`                 |
| **SEO**                                   | Schwaechere Unterstuetzung durch CSR           | Gute SEO-Unterstuetzung durch SSR und SSG                       |
| **API-Routes**                            | Keine                                          | Eingebaute Moeglichkeit fuer API-Endpunkte unter `pages/api/`   |
| **Caching**                               | Keine eingebauten Mechanismen                  | ISR erlaubt Aktualisierung ohne vollstaendige Neugenerierung    |
| **Performance-Optimierung**               | Meist ueber Drittloesungen                     | Eingebaute Optimierungen wie Code Splitting und Bildoptimierung |
| **Unterstuetzung fuer Server Components** | Abhaengig von der Konfiguration                | Integrierte Unterstuetzung mit `app/`                           |

#### Fazit:

- **React** eignet sich gut fuer SPAs, die im Client gerendert werden.

- **Next.js** eignet sich besser fuer SEO-optimierte Projekte, hybrides
  Rendering und performante Webanwendungen.

</details>

<details>
<summary>86. Wofuer braucht man React Helmet Async?</summary>

#### React

**React Helmet Async** ist eine optimierte Version von **React Helmet**, die zum
dynamischen Aktualisieren des `<head>` in React-Anwendungen verwendet wird, also
fuer Meta-Tags, Titel, Open Graph und aehnliche Inhalte.

#### Wofuer wird es verwendet?

1. **SEO-Optimierung:** Titel, Meta-Beschreibungen und Schluesselwoerter koennen
   dynamisch gesetzt werden.

2. **Dynamischer `<head>`:** Tags koennen fuer jede Seite ohne Neuladung
   geaendert werden.

3. **SSR-Unterstuetzung:** Im Gegensatz zu normalem React Helmet funktioniert
   diese Version korrekt in SSR-Anwendungen ohne Probleme mit Asynchronitaet.

#### Anwendungsbeispiel:

```jsx
import { Helmet } from 'react-helmet-async';

function MyComponent() {
  return (
    <Helmet>
      <title>Startseite</title>
      <meta
        name="description"
        content="Dies ist die Beschreibung der Startseite"
      />
    </Helmet>
  );
}
```

#### SSR (Next.js, Express):

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

#### Warum ist es besser als `react-helmet`?

- Unterstuetzt SSR ohne Asynchronitaetsfehler.
- Ist leichter und schneller.
- Verursacht keine Probleme im `StrictMode`.

#### Fazit:

Wenn SEO in React mit SSR wichtig ist, sollte `react-helmet-async` verwendet
werden.

</details>

<details>
<summary>87. Was ist eine Distributed Component?</summary>

#### React

Eine **Distributed Component** ist ein Konzept, bei dem eine Komponente in
mehrere unabhaengige Teile aufgeteilt wird, die getrennt rendern oder Logik
ausfuehren koennen, aber zusammenarbeiten.

#### Beispiele fuer die Umsetzung:

1. **Code Splitting**

- Komponenten werden nur bei Bedarf geladen, wodurch die anfängliche
  Bundle-Groesse sinkt.

```jsx
import { lazy, Suspense } from 'react';

const LazyComponent = lazy(() => import('./LazyComponent'));

function App() {
  return (
    <Suspense fallback={<div>Laden...</div>}>
      <LazyComponent />
    </Suspense>
  );
}
```

2. **Container-Komponenten (Container-Presentational Pattern)**

- Trennt Logik, also den Container, von der Darstellung, also der
  praesentationalen Komponente.

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
  return <div>{data ? JSON.stringify(data) : 'Laden...'}</div>;
}

function App() {
  return (
    <DataContainer>{data => <Presentational data={data} />}</DataContainer>
  );
}
```

3. **Micro Frontends**

- Verwendung getrennter autonomer Komponenten in verschiedenen Teilen einer
  Anwendung.
- Zum Beispiel entwickeln unterschiedliche Teams einzelne Teile eines grossen
  Projekts in `React`, `Vue` oder `Angular` und integrieren sie gemeinsam.

#### Wann sollte man es verwenden?

- Zur Performance-Optimierung, etwa durch Lazy Loading.

- Um die Wartung des Codes zu vereinfachen, indem Logik getrennt wird.

- Fuer skalierbare Anwendungen, zum Beispiel mit Micro Frontends.

</details>

<details>
<summary>88. Was ist eine Switching Component?</summary>

#### React

Eine **Switching Component** in React ist ein Muster, bei dem eine Komponente
dynamisch eine ihrer Kindkomponenten anhand einer bestimmten Bedingung rendert.
Das ist nuetzlich, wenn je nach Zustand, Route oder empfangenen Daten
unterschiedliche Komponenten angezeigt werden sollen.

#### Beispiel 1: Umschalten auf Basis des Zustands

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

- `type` bestimmt, welche Komponente angezeigt wird.

#### Beispiel 2: Verwendung mit React Router

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

- Hier fungiert `Routes` als Switching Component, die abhaengig von der URL die
  passende Komponente rendert.

#### Beispiel 3: Bedingtes Rendern ueber ein Objekt

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

- Das ist eine sauberere Variante ohne `switch`.

Switching Components vereinfachen die Logik und machen den Code besser lesbar,
wenn unterschiedliche Komponenten bedingt gerendert werden muessen.

</details>

<details>
<summary>89. Was ist Reselect und wie funktioniert es?</summary>

#### React

**Reselect** ist eine Bibliothek zum Erstellen effizienter Selektoren in Redux.
Sie hilft dabei, das Auslesen von Daten aus dem Zustand zu optimieren und
unnoetige Renderings von Komponenten durch Memoisierung zu vermeiden.

#### Wie funktioniert Reselect?

Reselect verwendet **Memoisierung**, um Ergebnisse von Berechnungen erneut zu
verwenden, solange sich die Eingangsdaten nicht geaendert haben.

1. **Nimmt Input-Selektoren entgegen**, die Daten aus dem Zustand holen.

2. **Berechnet Werte** auf Basis dieser Daten.

3. **Cached das Ergebnis**, damit die Berechnung bei identischen Eingangswerten
   nicht erneut ausgefuehrt wird.

#### Beispiel:

```jsx
import { createSelector } from 'reselect';

// Input-Selektor: alle Benutzer
const selectUsers = state => state.users;

// Input-Selektor: aktiver Filter
const selectFilter = state => state.filter;

// Memoisierter Selektor filtert Benutzer
export const selectFilteredUsers = createSelector(
  [selectUsers, selectFilter],
  (users, filter) => users.filter(user => user.role === filter)
);
```

- Ohne Reselect wuerde die Komponente das gesamte Array `users` bei jedem
  Rendern erneut pruefen.
- Mit Reselect wird der Selektor nur ausgefuehrt, wenn sich `users` oder
  `filter` aendern.

#### Vorteile von Reselect:

- Reduziert ueberfluessige Aufrufe von `mapStateToProps`.
- Vermeidet unnoetige Renderings von Komponenten.
- Laesst sich leicht mit Redux kombinieren.
- Verbessert die Performance.

</details>

<details>
<summary>90. Welche Datentypen kann `render` zurueckgeben?</summary>

#### React

Die Methode `render()` in React kann Folgendes zurueckgeben:

1. **JSX oder ein React-Element**

```jsx
render() {
return <div>Hello, World!</div>;
}
```

2. **Ein Array von Elementen**

```jsx
render() {
return [
<li key="1">Item 1</li>,
<li key="2">Item 2</li>
];
}
```

3. **Fragmente (`React.Fragment`)**

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

4. **`null`**, also nichts rendern

```jsx
render() {
return null;
}
```

5. **Boolesche Werte**, die ignoriert werden

```jsx
render() {
return false; // Es wird nichts angezeigt
}
```

6. **Textwerte**, die als Text gerendert werden

```jsx
render() {
return "Hello, World!";
}
```

7. **Portale**, also Rendern in ein DOM-Element ausserhalb der Elternkomponente

```jsx
import { createPortal } from "react-dom";

render() {
return createPortal(<div>Modal</div>, document.getElementById("modal-root"));
}
```

#### Fazit:

Der gaengigste Fall sind JSX oder React-Elemente. Moeglich sind aber auch
Arrays, Fragmente, `null`, Text oder Rendern ueber Portale.

</details>

<details>
<summary>91. Wie verarbeitet oder beschraenkt React die Verwendung von Props eines bestimmten Typs?</summary>

#### React

React beschraenkt die Verwendung von Props bestimmter Typen mit `PropTypes` oder
`TypeScript`.

1. **Verwendung von PropTypes, also eingebauter Typpruefung**

```jsx
import PropTypes from 'prop-types';

const MyComponent = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Alter: {age}</p>
      <p>{isActive ? 'Aktiv' : 'Inaktiv'}</p>
    </div>
  );
};

// Prop-Typen definieren
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isActive: PropTypes.bool,
};
```

- `PropTypes.string.isRequired` bedeutet, dass `name` erforderlich ist.
- `PropTypes.number` bedeutet, dass `age` eine Zahl sein muss.
- `PropTypes.bool` bedeutet, dass `isActive` ein boolescher Wert sein muss.

Wenn ungueltige Typen uebergeben werden, zeigt React eine Warnung in der Konsole
an, allerdings nur im Entwicklungsmodus.

2. **Verwendung von TypeScript, also strenger Pruefung zur Compile-Zeit**

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
      <p>Alter: {age}</p>
      <p>{isActive ? 'Aktiv' : 'Inaktiv'}</p>
    </div>
  );
};
```

- `name: string` ist ein erforderliches String-Prop.
- `age?: number` ist ein optionales numerisches Prop.
- `isActive: boolean` ist ein erforderliches boolesches Prop.

TypeScript meldet bereits vor dem Start des Codes einen Fehler, wenn falsche
Props uebergeben werden.

#### Was sollte man waehlen?

| **Methode**    | **Vorteile**                                | **Nachteile**                                 |
| -------------- | ------------------------------------------- | --------------------------------------------- |
| **PropTypes**  | Einfach, funktioniert in JavaScript         | Prueft nur zur Laufzeit, geringere Sicherheit |
| **TypeScript** | Strenge Typisierung, erkennt Fehler frueher | Benoetigt Kompilierung, komplexere Syntax     |

Wenn das Projekt auf **TypeScript** basiert, sind **PropTypes** meist nicht
noetig. In **JavaScript** bieten **PropTypes** eine grundlegende Absicherung.

</details>

<details>
<summary>92. Was ist der Unterschied zwischen Rendering und Mounting?</summary>

#### React

Unterschied zwischen Rendering und Mounting in React

| **Prozess**   | **Beschreibung**                                                                                                                                                                                                                         |
| ------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mounting**  | Eine Komponente wird erzeugt und zum ersten Mal dem DOM hinzugefuegt. Dabei werden `constructor`, `render` und `componentDidMount` bei Klassen oder `useEffect` mit leerem Abhaengigkeitsarray bei funktionalen Komponenten ausgefuehrt. |
| **Rendering** | `render()` oder die funktionale Komponente wird aufgerufen, um Inhalte zu aktualisieren. Das geschieht bei Aenderungen von `state`, `props` oder durch `forceUpdate()`.                                                                  |

#### Beispiel fuer Mounting

```jsx
useEffect(() => {
  console.log('Komponente wurde gemountet');
}, []); // Wird einmal beim Mounting ausgefuehrt
```

#### Beispiel fuer Rendering

```jsx
const [count, setCount] = useState(0);

useEffect(() => {
  console.log('Komponente wurde gerendert');
}); // Wird bei jedem Rendern ausgefuehrt

return <button onClick={() => setCount(count + 1)}>+</button>;
```

Hier findet das Rendering jedes Mal statt, wenn sich `count` aendert.

</details>

<details>
<summary>93. Was ist Reactive Data Flow in React?</summary>

#### React

**Reactive Data Flow in React** bedeutet, dass Aenderungen an State oder Props
einer Komponente automatisch zu einem UI-Update fuehren, ohne dass ein Re-Render
manuell ausgeloest werden muss.

#### Grundprinzipien:

1. **Einseitiger Datenfluss:** React gibt Daten von Eltern- zu Kindkomponenten
   weiter.

2. **Deklarativitaet:** Man beschreibt, was gerendert werden soll, und React
   kuemmert sich um die Aktualisierung.

3. **Automatische Aktualisierung:** Wenn sich `state` oder `props` aendern,
   rendert React nur die betroffenen Teile neu.

#### Beispiel fuer ein reaktives Update:

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Zaehler: {count}</p>
      <button onClick={() => setCount(count + 1)}>Erhoehen</button>
    </div>
  );
}
```

#### Wie funktioniert das?

- `useState` erstellt den Zustand `count`.

- Beim Klick aktualisiert `setCount(count + 1)` den Zustand.

- React rendert die Komponente automatisch mit den neuen Daten neu.

#### Ist React vollstaendig reaktiv?

- Nein. Anders als reaktive Frameworks wie Svelte oder Solid.js aktualisiert
  React das DOM nicht direkt bei einer Variablenaenderung. Es nutzt das Virtual
  DOM und startet einen Re-Render bei Aenderungen an `state` oder `props`.

#### Fazit:

- Reactive Data Flow in React bedeutet also automatische UI-Aktualisierung bei
  Zustandsaenderungen, allerdings mit Virtual DOM und gebuendelten Updates zur
  Optimierung.

</details>

<details>
<summary>94. Ist React reaktiv?</summary>

#### React

React ist keine rein reaktive Bibliothek wie etwa Vue oder Svelte. Dennoch hat
React einige Eigenschaften, die es reaktiven Frameworks aehnlich machen:

1. **Automatisches UI-Update:** React aktualisiert die Oberflaeche automatisch,
   wenn sich `state` oder Props aendern. Das erinnert an reaktive Ansaetze und
   geschieht ueber Rendering und Vergleich von Aenderungen.

2. **Funktionale Komponenten und Hooks:** Hooks wie `useState` und `useEffect`
   erzeugen einen reaktiven Effekt, bei dem Aenderungen an State oder Props zu
   erneutem Rendering fuehren.

3. **Teilweise Reaktivitaet:** React rendert nur die Komponenten neu, deren
   State oder Props sich geaendert haben. Anders als andere Frameworks arbeitet
   React jedoch nicht mit automatischen Beobachtern fuer Abhaengigkeiten.

React folgt also teilweise reaktiven Prinzipien, ist aber kein vollstaendig
reaktives Framework.

</details>

<details>
<summary>95. Welche Moeglichkeiten kennst du, Drag-and-Drop in React umzusetzen?</summary>

#### React

Drag-and-Drop kann in React auf verschiedene Arten umgesetzt werden:

- **Mit der HTML5-API** (`onDragStart`, `onDrop`)

- **Mit Bibliotheken** wie `react-dnd` oder `dnd-kit`

1. **Verwendung der nativen Drag-and-Drop-API**

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

- Einfach und ohne Fremdbibliotheken.
- Bietet aber weniger Kontrolle und eignet sich schlecht fuer komplexe Faelle.

2. **Verwendung von `react-dnd`, also die leistungsstaerkere Variante**

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

- Flexibel und fuer komplexe Faelle geeignet.
- Erleichtert die Arbeit mit verschachtelten Elementen.
- Fuegt allerdings eine zusaetzliche Abhaengigkeit hinzu.

3. **Verwendung von `dnd-kit`, also die moderne und einfachere Variante**

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

- Modernes API und leichter als `react-dnd`.
- Einfach zu benutzen.
- Unterstuetzt Sortierung (`sortable`).

#### Fazit:

- Fuer einfache Faelle: **HTML5 Drag-and-Drop-API**.

- Fuer flexible Kontrolle: **react-dnd**.

- Fuer eine moderne und leichte Loesung: **dnd-kit**.

</details>

<details>
<summary>96. Wie rendert man HTML-Code in einer React-Komponente?</summary>

#### React

Verwende `dangerouslySetInnerHTML`, aber mit Vorsicht, denn unsauber bereinigte
Daten koennen zu XSS-Angriffen fuehren.

#### Beispiel:

```jsx
function MyComponent() {
  const htmlContent = "<p style='color: red;'>Das ist HTML-Code</p>";

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
}
```

Wenn mit dynamischen Daten gearbeitet wird, muessen diese vor dem Einfuegen
unbedingt bereinigt werden.

</details>

<details>
<summary>97. Wie fuegt man in React bedingt eine CSS-Klasse hinzu?</summary>

#### React

In React erfolgt das bedingte Hinzufuegen von CSS-Klassen meist ueber das
Attribut `className` zusammen mit einem ternaren Operator oder Hilfsfunktionen
fuer Bedingungen.

#### Die wichtigsten Ansaetze:

1. **Ternarer Operator**

```jsx
function MyComponent({ isActive }) {
  return (
    <div className={isActive ? 'active-class' : 'inactive-class'}>Hello</div>
  );
}
```

- Wenn `isActive` den Wert `true` hat, wird `active-class` hinzugefuegt.
- Andernfalls `inactive-class`.

2. **Template Strings**

```jsx
function MyComponent({ isHighlighted }) {
  return (
    <div className={`base-class ${isHighlighted ? 'highlighted-class' : ''}`}>
      Hello
    </div>
  );
}
```

- `base-class` wird immer hinzugefuegt.
- Wenn `isHighlighted` `true` ist, kommt zusaetzlich `highlighted-class` hinzu.

3. **Bibliothek `clsx`**

- `clsx` erleichtert die Arbeit mit Klassen deutlich.

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

- Mit `clsx` lassen sich mehrere Klassen einfach anhand von Bedingungen
  hinzufuegen.

4. **Bibliothek `classnames`**

- Aehnlich wie `clsx`, aber mit noch mehr Moeglichkeiten.

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

5. **Auslagern der Logik in eine eigene Funktion**

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

- Die Logik zur Bestimmung von Klassen wird lesbarer und wiederverwendbar.

#### Fazit:

- Fuer einfache Faelle reichen ternare Operatoren oder Template Strings.

- Fuer komplexere Bedingungen sind `clsx` oder `classnames` besser geeignet,
  weil sie den Code bequemer und lesbarer machen.

</details>

<details>
<summary>98. Wie fuehrt man Code aus, bevor eine Komponente aus dem Baum entfernt wird?</summary>

#### React

Um Code auszufuehren, bevor eine Komponente in React aus dem Baum entfernt wird,
verwendet man folgende Ansaetze:

1. **Klassenkomponenten:** `componentWillUnmount`

- Bei Klassenkomponenten gibt es die Lifecycle-Methode `componentWillUnmount`,
  die vor dem Entfernen der Komponente aufgerufen wird.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Komponente wird entfernt');
  }

  render() {
    return <div>Meine Komponente</div>;
  }
}
```

2. **Funktionale Komponenten:** `useEffect` mit Cleanup

- In funktionalen Komponenten kann das Cleanup mit `useEffect` umgesetzt werden,
  indem eine Funktion zurueckgegeben wird, die vor dem Entfernen der Komponente
  ausgefuehrt wird.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Komponente wird entfernt');
    };
  }, []);

  return <div>Meine Komponente</div>;
}
```

3. **Behandlung vor dem Schliessen der Seite (`beforeunload`)**

- Wenn Code vor dem Schliessen eines Tabs oder vor dem Neuladen der Seite
  ausgefuehrt werden soll:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Seite wird geschlossen');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Fazit

- `componentWillUnmount` fuer Klassenkomponenten.

- `useEffect` mit `return` fuer funktionale Komponenten.

- `beforeunload` fuer Faelle, in denen auf das Verlassen der Seite reagiert
  werden muss.

</details>

<details>
<summary>99. Was ist `useReducer()`?</summary>

#### React

- `useReducer()` ist ein Hook in React zur Zustandsverwaltung in funktionalen
  Komponenten. Er ist eine Alternative zu `useState()` und eignet sich fuer
  komplexe Logik bei Zustandsupdates, besonders wenn Aenderungen vom vorherigen
  Zustand abhaengen.

#### Syntax:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` ist eine Funktion, die `state` und `action` entgegennimmt und einen
  neuen Zustand zurueckgibt.

- `initialState` ist der Anfangszustand.

- `dispatch` ist die Funktion, mit der der Reducer mit einer bestimmten `action`
  aufgerufen wird.

#### Beispiel:

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

#### Wann sollte man es verwenden?

- Wenn der Zustand komplexe Logik oder viele Abhaengigkeiten hat.

- Wenn Zustandsupdates ueber `dispatch` vereinheitlicht werden sollen.

- Fuer bessere Skalierbarkeit, zum Beispiel bei globalem State.

</details>

<details>
<summary>100. Wie verwendet man `React.lazy` und `React.Suspense`, um Anwendungscode zu laden?</summary>

#### React

`React.lazy` und `React.Suspense` werden in React fuer das **dynamische Laden
von Komponenten** verwendet. Dadurch laesst sich **Code Splitting** umsetzen.
Das bedeutet, dass Teile des Codes nur dann geladen werden, wenn sie gebraucht
werden, was die Performance der Anwendung verbessert.

#### Wie funktioniert das?

1. `React.lazy()` erlaubt das verzoegerte Laden einer Komponente.

2. `React.Suspense` umhuellt Code, der noch nicht geladen wurde, und zeigt
   waehrenddessen einen Fallback an, etwa einen Loader.

#### Beispiel:

1. **Dynamisches Laden einer Komponente:**

- Zuerst wird eine Komponente definiert, die dynamisch geladen werden soll.

```jsx
// Dynamisch geladene Komponente
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Wrapper mit `React.Suspense`:**

- Danach wird `React.Suspense` verwendet, um waehrend des Ladens einen Loader
  anzuzeigen.

```jsx
function App() {
  return (
    <div>
      <h1>Meine Anwendung</h1>

      {/* Wrapper fuer dynamisch geladene Komponenten */}
      <React.Suspense fallback={<div>Laden...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Beschreibung:**

- `React.lazy()` erwartet eine Funktion, die ein Modul dynamisch importiert.

- `React.Suspense` umhuellt die Komponente, die `React.lazy()` verwendet, und
  zeigt einen Fallback an, in diesem Fall den Text "Laden...", bis die
  Komponente geladen ist.

#### Vorteile:

- Verbessert die Performance, weil Komponenten nur bei Bedarf geladen werden.

- Verkleinert das initiale Ladevolumen, weil Teile der Anwendung erst bei Bedarf
  geladen werden.

Dieser Ansatz ist besonders in grossen Anwendungen nuetzlich, in denen der Code
in Teile aufgeteilt werden kann, um die Ladezeit der Seite zu verkleinern.

</details>

<details>
<summary>101. Welche Ansaetze werden fuer HTTP-Anfragen in React verwendet?</summary>

#### React

#### Ansaetze fuer HTTP-Anfragen in React

React besitzt keine eingebaute API fuer HTTP-Anfragen, aber es koennen
Drittbibliotheken oder Standardmittel von JavaScript verwendet werden. Die
wichtigsten Ansaetze sind:

1. **Verwendung der Fetch API**

- Das Standardwerkzeug fuer HTTP-Anfragen in JavaScript.

**Beispiel:**

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

2. **Verwendung von Axios**

- Eine Bibliothek fuer HTTP-Anfragen mit einfacherem Syntax und eingebauter
  Unterstuetzung fuer Interceptors.

**Beispiel:**

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

- Eine Bibliothek zur Verwaltung von Daten, die per HTTP geladen wurden. Sie
  unterstuetzt Caching, Retries und Datenaktualisierung.

**Beispiel:**

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

4. **GraphQL mit Apollo Client**

- Fuer die Arbeit mit einer GraphQL-API wird Apollo Client verwendet.

**Beispiel:**

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

- Eigene Hooks koennen erstellt werden, um Request-Logik wiederzuverwenden.

**Beispiel:**

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

#### Die Wahl des Ansatzes haengt von den Anforderungen ab:

- **Fetch API:** fuer einfache Anfragen.

- **Axios:** wenn mehr Flexibilitaet benoetigt wird, etwa Interceptors oder
  Timeouts.

- **React Query:** fuer Daten-Caching und Server-State-Management.

- **GraphQL/Apollo Client:** wenn die API auf GraphQL basiert.

- **Custom Hooks:** fuer die Wiederverwendung von Request-Logik.

</details>

<details>
<summary>102. Was ist der Unterschied zwischen `createElement` und `cloneElement`?</summary>

#### React

| **Methode**           | **Beschreibung**                                                                                       | **Hauptanwendung**                                                                       |
| --------------------- | ------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------- |
| `React.createElement` | Erstellt ein neues React-Element. Nimmt den Elementtyp, Props und Kindelemente als Argumente entgegen. | Wird verwendet, um React-Elemente von Grund auf zu erzeugen, meist beim Rendern von JSX. |
| `React.cloneElement`  | Klont ein vorhandenes React-Element und erlaubt das Aendern von Props oder Kindelementen.              | Wird verwendet, um veraenderte Kopien bereits existierender React-Elemente zu erzeugen.  |

#### Beispiele:

`React.createElement`

```jsx
const element = React.createElement(
  'div',
  { className: 'example' },
  'Hallo, React!'
);
```

Ergebnis: Es wird `<div class="example">Hallo, React!</div>` erstellt.

`React.cloneElement`

```jsx
const originalElement = <button className="primary">Klick</button>;

const clonedElement = React.cloneElement(originalElement, {
  className: 'secondary',
});
```

Ergebnis: ein Klon `<button class="secondary">Klick</button>` mit geaenderter
Klasse.

#### Unterschied:

- `createElement` erstellt ein vollstaendig neues Element.

- `cloneElement` arbeitet auf Grundlage eines bereits vorhandenen Elements und
  erlaubt das Aendern seiner Eigenschaften oder Inhalte.

</details>

<details>
<summary>103. Unterstuetzt die Funktion `lazy` benannten Export?</summary>

#### React

- Nein, `React.lazy` unterstuetzt keinen benannten Export. Es arbeitet nur mit
  Default-Exports. Wenn ein Modul nur einen benannten Export besitzt und mit
  `React.lazy` genutzt werden soll, muss ein Wrapper erstellt werden, der die
  gewuenschte Komponente als Default exportiert.

#### Beispiel fuer einen Wrapper:

```jsx
// Benannter Export
export const MyComponent = () => {
  return <div>Hello, World!</div>;
};

// Verwendung von React.lazy
const LazyComponent = React.lazy(() =>
  import('./MyComponent').then(module => ({ default: module.MyComponent }))
);

export default LazyComponent;
```

- Hier wird explizit angegeben, dass `module.MyComponent` als Default-Export
  verwendet werden soll.

</details>

<details>
<summary>104. Welche Vorteile hat React?</summary>

#### React

#### Vorteile von React

1. **Hohe Performance**

- Durch das **Virtual DOM** werden Aktualisierungen des echten DOM minimiert,
  was das Rendering beschleunigt.

2. **Komponentenbasierter Ansatz**

- Eine Anwendung besteht aus **wiederverwendbaren Komponenten**, was Entwicklung
  und Wartung vereinfacht.

3. **Einseitiger Datenfluss**

- Daten werden innerhalb der Komponenten-Hierarchie nach unten weitergegeben,
  was das Nachverfolgen von Zustandsaenderungen erleichtert.

4. **Unterstuetzung von Hooks**

- `useState`, `useEffect`, `useMemo` und andere Hooks ermoeglichen die
  Verwaltung von Zustand und Effekten in funktionalen Komponenten ohne Klassen.

5. **Server-Side Rendering und statische Generierung**

- Mit Next.js lassen sich SEO optimieren und die Performance von Anwendungen
  verbessern.

6. **Flexibilitaet und Oekosystem**

- React kann zusammen mit **Redux**, **Zustand**, **MobX**, **React Query** und
  anderen Loesungen eingesetzt werden.

- Es unterstuetzt **React Native** fuer mobile Anwendungen.

7. **Erweiterte Debugging-Moeglichkeiten**

- **React DevTools** erlaubt das Betrachten von Komponentenstruktur, Zustand und
  Props in Echtzeit.

8. **Aktive Community und Unterstuetzung durch Facebook**

- Es gibt eine grosse Auswahl an Bibliotheken und fertigen Loesungen sowie eine
  schnelle Weiterentwicklung des Oekosystems.

React ist ein flexibles, performantes und modernes Werkzeug fuer die Entwicklung
von Webanwendungen.

</details>

<details>
<summary>105. Welche Einschraenkungen hat React?</summary>

#### React

1. **Viele Re-Render:** Wenn Komponenten schlecht optimiert sind, kann das zu
   uebermaessigen Re-Rendern und damit zu schlechterer Performance fuehren.

2. **Notwendigkeit der Zustandsverwaltung:** Ohne gutes State-Management kann
   eine Anwendung schwer wartbar werden.

3. **Einseitiger Datenfluss:** Daten fliessen nur in eine Richtung, was die
   Weitergabe ueber viele Komponentenebenen erschweren kann.

4. **Reaktivitaet:** React aktualisiert das DOM ueber das Virtual DOM, was bei
   grossen und sehr dynamischen Anwendungen ineffizient sein kann.

5. **Abhaengigkeit von JavaScript:** Ohne JavaScript auf der Client-Seite ist
   die Unterstuetzung eingeschraenkt.

6. **Lernaufwand fuer Einsteiger:** Obwohl die Grundideen einfach sind, kann es
   schwierig sein, Hooks, Context und Optimierung sauber zu beherrschen.

7. **Drittanbieter-Werkzeuge:** Es gibt viele Tools, aber ihre Integration kann
   in grossen Projekten komplex werden.

</details>

<details>
<summary>106. Wofuer war die Methode `registerServiceWorker()` in React gedacht?</summary>

#### React

`registerServiceWorker()` wurde in Create React App verwendet, um einen Service
Worker zu registrieren, bevor diese Funktion in CRA 4 entfernt wurde.

#### Zweck:

- Caching von Ressourcen fuer den Offline-Modus

- Schnellere Ladezeiten der Anwendung

- Hintergrundaktualisierung von Ressourcen

#### Beispiel (vor CRA 4):

```javascript
import { register } from './serviceWorker';

register();
```

- Nach der Entfernung aus CRA muessen Service Worker manuell ueber
  `navigator.serviceWorker.register()` eingerichtet werden.

- In **React 19** gibt es kein eingebautes `registerServiceWorker()` mehr, da es
  schon frueher entfernt wurde. Wenn ein Service Worker gebraucht wird, muss er
  manuell registriert werden.

Fazit: In React 19 ist diese Methode nicht mehr aktuell und Service Worker
muessen eigenstaendig konfiguriert werden.

</details>

<details>
<summary>107. Was sind Synthetic Events in React?</summary>

#### React

- **SyntheticEvent** in React ist ein Wrapper um native Browser-Ereignisse, der
  browseruebergreifende Kompatibilitaet sicherstellt und die Performance
  verbessert.

#### Eigenschaften von SyntheticEvent:

- Funktioniert in allen Browsern einheitlich.

- Verwendet Event Pooling, um unnoetige Objekte im Speicher zu vermeiden.

- Alle Ereignisse werden normalisiert und besitzen unabhaengig vom Browser
  dieselben Eigenschaften.

#### Beispiel:

```jsx
function MyComponent() {
  const handleClick = event => {
    console.log(event.type); // "click"
    console.log(event.nativeEvent); // Originales Browser-Ereignis
  };

  return <button onClick={handleClick}>Klick</button>;
}
```

#### Wichtige Methoden:

- `event.preventDefault()` verhindert das Standardverhalten.

- `event.stopPropagation()` stoppt das Bubbling des Ereignisses.

- `event.persist()` deaktiviert das Pooling, damit das Ereignis nicht
  zurueckgesetzt wird.

</details>

<details>
<summary>108. Welche Techniken gibt es zur Performance-Optimierung in React?</summary>

#### React

#### Techniken zur Performance-Optimierung in React:

1. **Memoisierung von Komponenten**

- Verwende `React.memo()`, um unnoetige Re-Render zu vermeiden.
- Nutze `useMemo()` zum Cachen von Berechnungen.
- Verwende `useCallback()` fuer stabile Funktionsreferenzen.

2. **Optimierung von Re-Rendern**

- Vermeide unnoetigen State und ueberfluessige Props.
- Nutze `shouldComponentUpdate` oder `React.PureComponent` bei
  Klassenkomponenten.
- Optimiere `Context`, indem keine ueberfluessigen Werte uebergeben werden.
- Verwende Selektoren wie in `Reselect`, `Zustand` oder `Jotai`, um Updates zu
  minimieren.

3. **Virtualisierung von Listen**

- Bibliotheken wie `react-window` oder `react-virtualized`, um nur sichtbare
  Elemente zu rendern.

4. **Caching und Debounce**

- `useMemo()` und `useCallback()` fuer aufwendige Berechnungen.
- Debounce mit `lodash.debounce` oder Throttling mit `lodash.throttle` fuer
  Benutzereingaben.

5. **Lazy Loading**

- `React.lazy()` zusammen mit `Suspense` fuer Code Splitting.
- Dynamische Importe mit `import()`.

6. **Vermeidung unnoetiger Effekte in `useEffect`**

- Gib Abhaengigkeiten korrekt an.
- Verwende `useRef`, um Werte ohne Re-Render zu speichern.

7. **Bildoptimierung**

- Verwende in Next.js `next/image`.
- Optimiere Groessen und Formate wie `WebP` oder `AVIF`.

8. **Optimierung von React Router**

- Verwende `React.lazy()` fuer Seiten.
- Vermeide unnoetige Re-Render durch saubere Zustandsupdates.

9. **Aufteilung des Zustands**

- Nutze lokalen State dort, wo kein globaler Zustand noetig ist.
- Lagere globale Aenderungen in `Redux`, `Zustand` oder `Recoil` aus.

10. **Verwendung von Web Workers**

- Fuer aufwendige Berechnungen, damit der Haupt-Thread nicht blockiert wird.

</details>

<details>
<summary>109. Kann man async/await in React verwenden?</summary>

#### React

- Ja, `async/await` kann in React verwendet werden, aber einige Punkte sollten
  beachtet werden:

1. **Verwendung in Komponenten:** `async/await` kann nicht direkt in Komponenten
   selbst oder in Lifecycle-Methoden wie `render()` verwendet werden. Es kann
   jedoch in Event-Handlern oder Hooks wie `useEffect` eingesetzt werden.

2. **Mittel fuer asynchrone Anfragen:**

- `async/await` sollte innerhalb von Funktionen verwendet werden, die in Hooks
  aufgerufen werden, zum Beispiel:

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

3. **Fehlerbehandlung:** Fuer asynchrone Anfragen sollte immer `try/catch`
   verwendet werden:

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

`async/await` kann und sollte also fuer asynchrone Operationen in React
verwendet werden, muss aber innerhalb von Komponenten korrekt organisiert sein.

</details>

<details>
<summary>110. Wie verlief die Entwicklungsgeschichte von React?</summary>

#### React

Hier ist eine kurze Geschichte der Entwicklung von React:

1. **2011**

- React wurde bei Facebook fuer interne Anforderungen entwickelt. Der Ingenieur
  Jordan Walke schuf es, um das Problem effizienter Oberflaechenaktualisierung
  zu loesen.

2. **2013**

- Facebook veroeffentlichte React als Open-Source-Bibliothek. Anfangs reagierte
  die Community skeptisch, vor allem wegen JSX, das ungewoehnlich wirkte.

3. **2015**

- React 0.14 wurde veroeffentlicht. Dabei wurden React und ReactDOM getrennt,
  was die Bibliothek modularer machte.

- Facebook stellte React Native vor, wodurch native mobile Apps mit React
  entwickelt werden konnten.

4. **2016**

- React 15 erschien. Die wichtigsten Neuerungen betrafen Leistungsverbesserungen
  durch eine ueberarbeitete Rendering-Engine.

5. **2017**

- React 16 mit Fiber wurde veroeffentlicht. Fiber wurde zur neuen Architektur
  und brachte bessere Performance sowie Unterstuetzung fuer asynchrones
  Rendering.

- Unterstuetzung fuer Portale und Error Boundaries wurde hinzugefuegt.

6. **2018**

- Facebook stellte React Hooks vor. Damit konnten State und Lifecycle-Logik in
  funktionalen Komponenten genutzt werden, was die Art der Komponentenerstellung
  grundlegend veraenderte.

7. **2019**

- React 16.8 wurde mit offizieller Hook-Unterstuetzung veroeffentlicht.

- Die Effizienz des experimentellen Concurrent Mode wurde verbessert.

8. **2020**

- React 17 erschien. Das Hauptziel war es, schrittweise Upgrades in grossen
  Projekten zu erleichtern.

- Moderne Werkzeuge und neue Moeglichkeiten fuer JSX wurden besser unterstuetzt.

9. **2022**

- React 18 wurde veroeffentlicht. Zu den wichtigsten Neuerungen gehoerten
  Concurrent Rendering sowie die APIs `useTransition` und `useDeferredValue`,
  die die Performance dynamischer Anwendungen verbessern.

10. **2024**

- React 19 wurde veroeffentlicht.

- Das Server Rendering mit React Server Components wurde erweitert.

- Unterstuetzung fuer die neue `use`-Funktion wurde hinzugefuegt.

- Formulare, Fehlerbehandlung beim Rendern und JSX ohne `import React` wurden
  verbessert.

- Der React Compiler wurde fuer automatische Performance-Optimierung
  weiterentwickelt.

#### Wichtige Veraenderungen im Verlauf der Entwicklung:

- Von Klassenkomponenten hin zu funktionalen Komponenten mit Hooks.

- Unterstuetzung fuer Server-Side Rendering.

- Concurrent Mode fuer fluessigere UI-Aktualisierungen.

- Integration mit mobiler Entwicklung ueber React Native.

React blieb dank hoher Performance, guter Nutzbarkeit und kontinuierlicher
Unterstuetzung durch Facebook populaer.

</details>

<details>
<summary>111. Welche Neuerungen wurden in React 19 eingefuehrt?</summary>

#### React

React 19 brachte eine Reihe bedeutender Neuerungen, die auf bessere Performance
und eine angenehmere Entwicklung abzielen. Die wichtigsten sind:

1. **Neues Rendering-System:** Asynchrones Rendering wurde weiter ausgebaut,
   sodass React UI-Aktualisierungen effizienter steuern und die Interaktion
   verbessern kann.

2. **React Compiler:** Der neue Compiler optimiert Re-Render automatisch,
   reduziert unnoetige Updates und verbessert damit die Performance von
   Anwendungen.

3. **Actions API:** Ein neuer Ansatz fuer Zustandsaenderungen und
   Datenmutationen auf dem Server, der den Umgang mit Side Effects und
   Datenanfragen vereinfacht.

4. **Verbesserte Suspense-Mechanik:** Sie gibt Entwicklern feinere Kontrolle
   ueber asynchrones Laden von Daten und erleichtert die Steuerung von Hydration
   und Fallback-Zustaenden.

5. **Hook `use`:** Ein neuer Hook, der den Umgang mit asynchronen Daten
   vereinfacht und die Unterstuetzung fuer Server Components verbessert.

6. **Native Unterstuetzung fuer Meta-Tags:** `meta`, `title`, `link` und andere
   Tags werden nun ohne Zusatzbibliotheken unterstuetzt, was SEO- und
   Ressourcenverwaltung vereinfacht.

- Diese Neuerungen machen React 19 zu einem leistungsstaerkeren und
  komfortableren Werkzeug fuer Entwickler und verbessern sowohl die
  App-Performance als auch die Developer Experience.

</details>

<details>
<summary>112. Was empfehlen React-Entwickler, nachdem Create React App als deprecated gilt?</summary>

#### React

Seit dem Ende der Unterstuetzung fuer Create React App im Februar 2025 wird
Entwicklern empfohlen, moderne Frameworks fuer neue React-Anwendungen zu
verwenden. Diese Frameworks unterstuetzen clientseitiges Rendering und
Single-Page-Anwendungen, die sich auf CDNs oder statischen Hosting-Diensten ohne
eigenen Server bereitstellen lassen.

#### Empfohlene Frameworks:

1. **Next.js:** Bietet leistungsstarke Funktionen wie Server-Side Rendering und
   statische Seitengenerierung und sorgt fuer gute Performance und SEO.

2. **React Router:** Ermoeglicht den Aufbau von SPAs mit dynamischem Routing und
   erleichtert die Navigation innerhalb der Anwendung.

3. **Expo:** Vereinfacht die Entwicklung von React-Native-Anwendungen und bietet
   Werkzeuge fuer plattformuebergreifende mobile Apps mit JavaScript und React.

</details>

<details>
<summary>113. Wie funktioniert der Hook `useDeferredValue` in React?</summary>

#### React

`useDeferredValue` ist ein React-Hook, der mit React 18 im Zusammenhang mit
Concurrent Features eingefuehrt wurde. Er erlaubt es, Aktualisierungen
bestimmter Werte, etwa von State oder Props, aufzuschieben, ihren Prioritaets-
grad zu senken und React so zuerst wichtigere UI-Aufgaben erledigen zu lassen.

Das ist besonders hilfreich, wenn sich ein Wert haeufig aendert und ein
sofortiges UI-Update bei jeder Aenderung viel Rechenleistung kostet.

##### Wofuer wird `useDeferredValue` verwendet?

- Um Verzoegerungen und Ruckler in komplexen Anwendungen zu vermeiden, wenn
  schnelle UI-Reaktionen wichtig sind.
- Um die Benutzerinteraktion zu verbessern, besonders bei Suchfeldern, Filterung
  oder grossen Listen.
- Um Animationen und Uebergaenge fluessiger zu halten.

##### Wie funktioniert es?

Der Hook `useDeferredValue` nimmt einen Wert entgegen und gibt eine
aufgeschobene Version davon zurueck:

```jsx
const deferredValue = useDeferredValue(value);
```

- React aktualisiert kritische, also prioritaere, Aenderungen sofort.
- Der aufgeschobene Wert `deferredValue` wird asynchron aktualisiert, nachdem
  dringendere Aufgaben bearbeitet wurden.
- Wenn sich der Ursprungswert sehr schnell aendert, kann React Zwischenwerte
  ueberspringen und direkt zum neuesten Wert springen.

##### Anwendungsbeispiel:

Angenommen, es gibt eine Komponente mit einem Suchfeld und einer grossen Liste,
die waehrend der Eingabe gefiltert werden soll.

###### Ohne `useDeferredValue`:

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
        placeholder="Suche..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

Das kann zu Rucklern fuehren, wenn die Liste sehr gross ist, weil React bei
jeder Eingabe sofort alle gefilterten Ergebnisse neu berechnet.

###### Mit `useDeferredValue`:

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
        placeholder="Suche..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

In dieser Variante:

- Die Eingabe des Benutzers bleibt direkt und fluessig.
- Die Listenfilterung erfolgt asynchron, nachdem dringlichere Updates erledigt
  wurden.
- Dadurch bleibt die Benutzeroberflaeche reaktionsfaehig.

##### Besondere Eigenschaften:

- `useDeferredValue` legt keine feste Verzoegerungszeit fest wie ein Debounce.
  Stattdessen entscheidet React selbst anhand der aktuellen Belastung, wann das
  Update ausgefuehrt wird.
- Der mit `useDeferredValue` erhaltene Wert kann dem eigentlichen Zustand
  hinterherlaufen, was in der Logik der Anwendung beruecksichtigt werden muss.

##### Vorteile:

- Reduziert die CPU-Last waehrend intensiver Interaktionen.
- Sorgt fuer stabilere FPS und eine fluessigere UI.
- Macht die Nutzererfahrung angenehmer und vorhersehbarer, besonders in grossen
  und komplexen Anwendungen.

##### Wann sollte `useDeferredValue` bevorzugt eingesetzt werden?

- Bei Listen mit sehr vielen Elementen.
- Bei Formularen mit aktiver Filterung oder Autovervollstaendigung.
- In allen Faellen, in denen haeufige UI-Updates die Nutzererfahrung
  verschlechtern koennen.

</details>
