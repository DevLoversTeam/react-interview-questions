**Read in other languages: [English 🇺🇸](README.en.md),
[Polska 🇵🇱](README.pl.md), [German 🇩🇪](README.de.md), [French 🇫🇷](README.fr.md),
[Spanish 🇪🇸](README.es.md), [Українська 🇺🇦](README.md).**

<h1>
  React <img src="./assets/react.svg" width="40" height="40" />
</h1>

<h2>Najpopularniejsze pytania i odpowiedzi na rozmowie kwalifikacyjnej z React</h2>

<details>
<summary>1. Czym jest React?</summary>

#### React

React to biblioteka JavaScript do tworzenia interfejsów użytkownika. Główne
cechy:

1. **Podejście komponentowe:** UI jest dzielone na oddzielne komponenty, które
   można ponownie wykorzystywać.

2. **Virtual DOM:** Zapewnia wydajne aktualizowanie interfejsu, minimalizując
   manipulacje na rzeczywistym DOM.

3. **Deklaratywność:** Opisujesz, jak UI ma wyglądać w określonym stanie, a
   React dba o jego zgodność z tym opisem.

4. **Jednokierunkowy przepływ danych:** Dane są przekazywane z góry na dół przez
   propsy, co upraszcza kontrolę nad stanem.

React został stworzony przez Facebook i jest szeroko używany do tworzenia SPA
(Single Page Applications).

</details>

<details>
<summary>2. Wymień cechy React.</summary>

#### React

1. **Podejście komponentowe:** Kod jest podzielony na wielokrotnego użytku,
   niezależne komponenty.

2. **Wirtualny DOM (Virtual DOM):** Szybkie aktualizowanie interfejsu bez
   bezpośredniego manipulowania DOM.

3. **Jednokierunkowy przepływ danych:** Dane są przekazywane z komponentów
   nadrzędnych do podrzędnych przez propsy.

4. **JSX:** Rozszerzenie składni JavaScript do pisania UI w postaci kodu
   podobnego do XML.

5. **Stan i cykl życia:** Komponenty mogą przechowywać i zarządzać swoim stanem.

6. **React Hooks:** Dodają możliwość pracy ze stanem i efektami ubocznymi w
   komponentach funkcyjnych.

7. **Ekosystem:** Wspiera biblioteki takie jak React Router czy Redux do
   rozszerzania funkcjonalności.

8. **Przyjazny dla SEO (z Next.js):** Renderowanie po stronie serwera dla
   lepszego indeksowania.

9. **Tworzenie aplikacji mobilnych:** React Native pozwala budować aplikacje
   mobilne oparte na React.

10. **Open source:** Aktywne wsparcie społeczności.

</details>

<details>
<summary>3. Jakie są główne funkcje React?</summary>

#### React

#### Główne funkcje React:

1. **Podejście deklaratywne:** React pozwala tworzyć interaktywny interfejs,
   opisując, jak powinien wyglądać, a biblioteka sama optymalizuje aktualizacje
   DOM.

2. **Struktura komponentowa:** Aplikacja jest budowana z niezależnych,
   wielokrotnego użytku komponentów, które upraszczają rozwój, testowanie i
   utrzymanie.

3. **Wirtualny DOM:** React używa Virtual DOM do efektywnego aktualizowania
   rzeczywistego DOM, co znacząco poprawia wydajność.

4. **Jednokierunkowy przepływ danych:** Dane są przekazywane z komponentów
   nadrzędnych do podrzędnych przez propsy, co upraszcza zarządzanie stanem.

5. **Hooki (Hooks):** Pozwalają używać stanu i metod cyklu życia w komponentach
   funkcyjnych.

6. **JSX:** Rozszerzenie JavaScript do opisywania UI w składni podobnej do HTML.

7. **React Native:** Możliwość tworzenia natywnych aplikacji mobilnych z
   wykorzystaniem tych samych zasad co na webie.

8. **Ekosystem:** Duży zestaw bibliotek i narzędzi, takich jak React Router,
   Redux czy Context API.

9. **Wsparcie dla renderowania po stronie serwera (SSR):** Pozwala optymalizować
   SEO i przyspieszać początkowe ładowanie stron.

10. **Zarządzanie stanem:** Za pomocą `useState`, Context API, Redux lub innych
    bibliotek.

Te funkcje sprawiają, że React jest potężną i elastyczną biblioteką do tworzenia
nowoczesnych aplikacji.

</details>

<details>
<summary>4. Jakie są kluczowe zalety korzystania z React?</summary>

#### React

#### Kluczowe zalety korzystania z React

1. **Szybkość**: Dzięki Virtual DOM React minimalizuje interakcje z rzeczywistym
   DOM, co zwiększa wydajność.

2. **Podejście komponentowe**: Kod jest dzielony na komponenty wielokrotnego
   użytku, co upraszcza rozwój i utrzymanie.

3. **Jednokierunkowy przepływ danych**: Przepływ danych w React odbywa się w
   jednym kierunku (z góry na dół), co ułatwia debugowanie.

4. **Duża społeczność**: React ma ogromny ekosystem bibliotek, narzędzi i
   rozszerzeń.

5. **Zgodność z tworzeniem aplikacji mobilnych**: Korzystając z React Native,
   można tworzyć wieloplatformowe aplikacje mobilne.

6. **JSX**: Składnia, która pozwala pisać JavaScript razem z HTML, zwiększając
   czytelność kodu.

7. **Wsparcie hooków**: Ułatwia pracę ze stanem i cyklem życia w komponentach
   funkcyjnych.

8. **Przyjazność dla SEO**: Renderowanie po stronie serwera za pomocą narzędzi
   takich jak Next.js poprawia optymalizację SEO.

9. **Elastyczność**: React można zintegrować z dowolnym projektem lub
   frameworkiem bez większych zmian w kodzie.

10. **React DevTools**: Narzędzie do debugowania, które pozwala wygodnie
    analizować komponenty i stan aplikacji.

</details>

<details>
<summary>5. Czym jest JSX?</summary>

#### React

**JSX (JavaScript XML)** to składnia, która pozwala pisać struktury UI w postaci
kodu podobnego do XML wewnątrz JavaScript. JSX jest rozszerzeniem JavaScript i
jest używany w React do opisywania wyglądu interfejsu.

#### Główne cechy JSX:

1. **Składnia podobna do XML:** Przypomina HTML, ale jest używana w JavaScript.

```jsx
const element = Hello, world!;
```

2. **Osadzony JavaScript:** Możesz pisać kod JavaScript w nawiasach klamrowych
   `{}`.

```jsx
const name = 'Alice';
const element = Hello, {name}!;
```

3. **Transpilacja:** JSX jest kompilowany do zwykłego JavaScript przy użyciu
   bibliotek takich jak Babel.

```jsx
const element = Hello;
// Zamienia się na:
const element = React.createElement('h1', null, 'Hello');
```

4. **Atrybuty:** Używa się ich podobnie jak w HTML, ale zamiast `class` pisze
   się `className`, a zamiast `for` - `htmlFor`.

```jsx
const input = ;
```

5. **JSX zwraca drzewo elementów:** Wyrażenie JSX może zwrócić tylko jeden
   element główny. Użyj `<React.Fragment>` albo pustego tagu `<>` do grupowania.

```jsx
return <>Title Description</>;
```

#### Zalety:

- Wygodne tworzenie komponentów UI.
- Zrozumiała i czytelna składnia.
- Ścisła integracja z logiką JavaScript.

JSX nie jest obowiązkowy w React, ale jest szeroko używany ze względu na wygodę
i elastyczność.

</details>

<details>
<summary>6. Jaka jest różnica między stanem (state) a propsami (props)?</summary>

#### React

#### Różnica między stanem (state) a propsami (props)

| Kryterium             | State                                                           | Props                                                    |
| --------------------- | --------------------------------------------------------------- | -------------------------------------------------------- |
| **Przeznaczenie**     | Przechowuje wewnętrzny stan komponentu.                         | Przekazuje dane z komponentu nadrzędnego do podrzędnego. |
| **Zmienne?**          | Może się zmieniać wewnątrz komponentu.                          | Niezmienne (read-only).                                  |
| **Dostępność**        | Dostępny tylko w komponencie, w którym został zdefiniowany.     | Dostępny w komponencie podrzędnym przez atrybuty.        |
| **Inicjalizacja**     | Ustawiany w komponencie za pomocą `useState` lub konstruktora.  | Określany przez komponent nadrzędny.                     |
| **Zakres użycia**     | Do przechowywania dynamicznych danych, które mogą się zmieniać. | Do przekazywania stałych lub dynamicznych danych.        |
| **Kto nim zarządza?** | Komponent, w którym stan jest zdefiniowany.                     | Komponent nadrzędny.                                     |

</details>

<details>
<summary>7. Jaka jest różnica między elementem a komponentem?</summary>

#### React

#### Różnica między elementem a komponentem w React:

| Kryterium              | Element                                          | Komponent                                                                                            |
| ---------------------- | ------------------------------------------------ | ---------------------------------------------------------------------------------------------------- |
| **Definicja**          | Obiekt opisujący, jak ma wyglądać interfejs.     | Funkcja lub klasa, która zwraca elementy React.                                                      |
| **Typ**                | Niezmienny (immutable).                          | Wielokrotnego użytku i może mieć stan (state).                                                       |
| **Składnia tworzenia** | `React.createElement` albo JSX (`<div />`).      | Funkcja lub klasa (`function MyComponent() {}` albo `class MyComponent extends React.Component {}`). |
| **Przeznaczenie**      | Reprezentuje pojedynczy węzeł w DOM.             | Enkapsuluje logikę i strukturę interfejsu.                                                           |
| **Możliwość użycia**   | Używany do tworzenia UI na podstawowym poziomie. | Używany do budowania bardziej złożonych struktur z logiką biznesową.                                 |
| **Przykład**           | `<h1>Hello</h1>`                                 | `function Hello() { return <h1>Hello</h1>; }`                                                        |

Element to "klocek budulcowy", a komponent to "konstruktor" do tworzenia
złożonych interfejsów.

</details>

<details>
<summary>8. Jak tworzyć komponenty w React?</summary>

#### React

#### W React komponenty można tworzyć na dwa sposoby:

1. **Komponent funkcyjny:** To prosta funkcja, która zwraca elementy React.

```jsx
function Greeting(props) {
  return Hello, {props.name}!;
}

// Użycie:
;
```

2. **Komponent klasowy:** To klasa, która dziedziczy po `React.Component` i musi
   mieć metodę `render`.

```jsx
class Greeting extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Użycie:
;
```

#### Różnice:

- Komponenty funkcyjne są prostsze i lepiej nadają się do komponentów bez stanu.

- Komponenty klasowe są używane do bardziej złożonych komponentów z własnym
  stanem lub metodami cyklu życia.

**Uwaga:** Współczesne podejście zakłada używanie komponentów funkcyjnych z
hookami zamiast klasowych.

</details>

<details>
<summary>9. Czym jest stan (state) w React?</summary>

#### React

**Stan (state)** w React to obiekt używany do przechowywania danych, które mogą
zmieniać się w czasie i wpływają na renderowanie komponentu. Stan pozwala
komponentom React być dynamicznymi i reagować na zdarzenia, dane wprowadzane
przez użytkownika itd.

#### Cechy stanu:

1. **Lokalny dla komponentu:** Stan jest dostępny tylko w komponencie, w którym
   został zdefiniowany.

2. **Zmienia się asynchronicznie:** React grupuje wywołania `setState`, aby
   zoptymalizować renderowanie.

3. **Jest inicjalizowany w konstruktorze** (dla komponentów klasowych) albo
   przez `useState` (w komponentach funkcyjnych).

#### W komponentach klasowych:

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

#### W komponentach funkcyjnych (z hookiem `useState`):

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

#### Główne różnice między stanem a propsami:

- **State** jest lokalny dla komponentu i może się zmieniać.

- **Props** są przekazywane z zewnątrz i są niezmienne (immutable).

</details>

<details>
<summary>10. Czym są propsy (props) w React?</summary>

#### React

**Propsy (props)** w React to obiekt zawierający dane przekazywane z komponentu
nadrzędnego do podrzędnego. Służą do konfigurowania komponentów i są niezmienne
(immutable).

#### Cechy propsów:

1. **Są przekazywane z góry na dół** (unidirectional data flow) - z komponentu
   nadrzędnego do podrzędnego.

2. **Niezmienne** - komponent nie może zmieniać otrzymanych propsów.

3. **Dynamiczne** - wartości propsów mogą się zmieniać, jeśli zmieniają się dane
   w komponencie nadrzędnym.

#### Używanie propsów:

1. **W komponencie funkcyjnym:**

```jsx
function Welcome(props) {
  return Hello, {props.name}!;
}

// Użycie:
;
```

2. **W komponencie klasowym:**

```jsx
class Welcome extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Użycie:
;
```

#### Przekazywanie propsów:

```jsx
function App() {
  return (

  );
}
```

**Rezultat:**

```bash
Hello, Alice!
Hello, Bob!
```

#### Destrukturyzacja propsów:

```jsx
function Welcome({ name }) {
  return Hello, {name}!;
}
```

#### Domyślne wartości propsów:

```jsx
function Welcome({ name = 'Guest' }) {
  return Hello, {name}!;
}

// Użycie:
; // Wyświetli: Hello, Guest!
```

Propsy zapewniają komponentom React elastyczność i możliwość ponownego
wykorzystania.

</details>

<details>
<summary>11. Do czego służy atrybut key podczas renderowania list?</summary>

#### React

Atrybut `key` służy do identyfikowania elementów na listach podczas
renderowania.

#### Zastosowanie:

1. **_Optymalizacja aktualizacji:_** React używa `key`, aby wydajnie
   aktualizować interfejs, szybko określając, które elementy trzeba zmienić,
   dodać lub usunąć.

2. **_Zapobieganie zbędnym renderom:_** `key` pomaga uniknąć ponownego
   renderowania elementów, które się nie zmieniły.

3. **_Zachowanie stanu komponentów:_** Na przykład jeśli element listy zawiera
   formularz, `key` pozwala Reactowi zachować jego stan między aktualizacjami.

#### Prawidlowe uzycie:

- Wartość `key` musi być unikalna wśród elementów sąsiednich.

- Najlepiej używać stabilnych identyfikatorów, na przykład `id` z bazy danych.

- Nie zaleca się używania indeksu tablicy jako `key`, ponieważ może to prowadzić
  do błędów przy zmianie kolejności elementów.

```jsx
const items = ['Apple', 'Banana', 'Cherry'];
return (

    {items.map((item, index) => (
      {item} // Unikalny key dla każdego elementu
    ))}

);
```

</details>

<details>
<summary>12. Jak przekazywane są dane między komponentami w React?</summary>

#### React

W React dane są przekazywane między komponentami zgodnie z hierarchią w
następujący sposób:

#### Przekazywanie danych w dół (z komponentu nadrzędnego do podrzędnego)

Do przekazywania danych w dół używa się propsów. Komponent nadrzędny przekazuje
wartości lub funkcje do komponentu podrzędnego przez atrybuty.

**Przykład:**

```jsx
function ParentComponent() {
  const data = 'Hello from Parent';

  return;
}

function ChildComponent({ message }) {
  return { message };
}
```

`message` przekazuje wartość `data` do komponentu podrzędnego `ChildComponent`.

W komponencie podrzędnym dostęp do propsów uzyskuje się przez parametr funkcji
albo `this.props` w komponencie klasowym.

#### Przekazywanie danych w górę (z komponentu podrzędnego do nadrzędnego)

Dane są przekazywane w górę za pomocą funkcji callback. Komponent nadrzędny
przekazuje funkcję do podrzędnego, a ten wywołuje ją z odpowiednimi danymi.

**Przyklad:**

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

Komponent nadrzędny przekazuje funkcję `handleData` do propsa `sendData`.

Komponent podrzędny wywołuje `sendData`, przekazując wartość `data`.

#### Alternatywne podejścia w bardziej złożonych aplikacjach:

1. **Kontekst (Context API):**

Do przekazywania danych głęboko w hierarchii bez używania propsów.

Nadaje się do stanu globalnego, na przykład motywu lub języka interfejsu.

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

2. **Menedżery stanu (Redux, Zustand, MobX):** Do przekazywania danych w dużych
   aplikacjach przez jeden globalny stan.

3. **Custom Hooks:** Służą do współdzielenia logiki między komponentami.

</details>

<details>
<summary>13. Dlaczego React używa className zamiast atrybutu class?</summary>

#### React

W React używa się `className` zamiast `class`, ponieważ `class` jest
zastrzeżonym słowem kluczowym w JavaScript.

#### Powody:

1. **Unikanie konfliktów**: `class` jest używane do definiowania klas w
   JavaScript (`class MyComponent {}`), co mogłoby powodować błędy składni.

2. **Zgodność z JSX**: JSX jest rozszerzeniem składni JavaScript, dlatego użycie
   `className` pomaga uniknąć niejednoznaczności.

3. **Bezpośrednie odwzorowanie** w `document.createElement`: React przekształca
   JSX w wywołania `React.createElement`, a do ustawiania klas w elementach DOM
   używa `className`.

#### Przyklad:

```jsx
// Poprawny wariant w React

Hello;

// Niepoprawny wariant (błąd składni)

Hello;
```

Jest to standard Reacta, który zapewnia spójność i stabilność kodu.

</details>

<details>
<summary>14. Jakie są zasady i wyjątki dotyczące nazywania komponentów w React?</summary>

#### React

W React istnieje kilka ważnych zasad i wyjątków dotyczących nazywania
komponentów:

1. **Wielka litera na początku nazwy komponentu:** Nazwy komponentów muszą
   zaczynać się od wielkiej litery. To konieczne, aby React mógł odróżnić
   komponenty od standardowych elementów HTML.

Na przykład:

- Poprawnie: `<MyComponent />`
- Niepoprawnie: `<myComponent />`

2. **CamelCase:** Zaleca się używanie stylu CamelCase w nazwach komponentów.
   Oznacza to, że każde kolejne słowo w nazwie zaczyna się wielką literą:

- `MyComponent`
- `UserProfile`

3. **Nazwy nie powinny pokrywać się z elementami HTML:** Nie używaj nazw
   komponentów, które są takie same jak standardowe tagi HTML, takie jak `div`,
   `span`, `button` itd. Może to powodować konflikty i nieprzewidywalne
   zachowanie:

- Poprawnie: `<CustomButton />`
- Niepoprawnie: `<button />` (choć jest to element HTML, w React zostanie
  potraktowany jako standardowy tag HTML)

4. **Unikaj znaków specjalnych:** Nie używaj znaków specjalnych w nazwach
   komponentów, takich jak spacje, myślniki czy podkreślenia, ponieważ może to
   prowadzić do błędów składni:

- Poprawnie: `MyComponent`
- Niepoprawnie: `my_component`, `my-component`

5. **Komponenty funkcyjne a klasy:** Jeśli używasz klas do tworzenia
   komponentów, ich nazwy również muszą zaczynać się wielką literą:

- `class MyComponent extends React.Component {}`

Przestrzeganie tych zasad pomaga zapewnić poprawne działanie i czytelność kodu.

</details>

<details>
<summary>15. Jak pisać komentarze w React?</summary>

#### React

W React komentarze zapisuje się tak samo jak w JavaScript, ale istnieją pewne
niuanse, gdy chodzi o JSX.

1. **Komentarze w JavaScript (poza JSX)**

```javascript
// Komentarz jednolinijkowy

/*
Komentarz wielolinijkowy
*/
```

2. **Komentarze wewnątrz JSX**

- W JSX trzeba używać specjalnej składni, ponieważ JSX jest częścią JavaScript.

- Komentarze w JSX należy zapisywać wewnątrz nawiasów klamrowych `{}`:

```jsx
function MyComponent() {
  return (

      {/_ To jest komentarz wewnątrz JSX _/}
      Hello, world!

  );
}
```

- Komentarze w JSX muszą mieć postać `{/* komentarz */}`, w przeciwnym razie
  spowodują błędy.

- Mogą być używane tylko wewnątrz wyrażeń JSX.

3. **Komentarze w funkcjach i metodach**

- Do komentarzy wewnątrz funkcji lub metod można używać standardowych komentarzy
  JavaScript:

```jsx
function MyComponent() {
  // Tutaj renderujemy komponent
  return Hello, world!;
}
```

#### Wniosek:

- W JSX używaj `{/* komentarz */}`.

- W zwykłym JavaScript używaj `//` dla komentarzy jednolinijkowych i `/* ... */`
  dla wielolinijkowych.

</details>

<details>
<summary>16. Czym jest Virtual DOM w React?</summary>

#### React

**Virtual DOM** to wirtualna reprezentacja rzeczywistego DOM, której React używa
do wydajnego aktualizowania interfejsu.

#### Jak działa w React:

1. **Renderowanie w Virtual DOM:** Gdy zmienia się stan lub propsy komponentów,
   React aktualizuje Virtual DOM.

2. **Diffing:** React porównuje nowy Virtual DOM ze starą wersją, określając
   minimalny zestaw zmian.

3. **Aktualizacja rzeczywistego DOM:** Wykryte zmiany są stosowane do
   rzeczywistego DOM, co minimalizuje liczbę operacji.

#### Główna zaleta:

Optymalizacja aktualizacji DOM, co znacząco poprawia wydajność aplikacji.

</details>

<details>
<summary>17. Czym jest prop key i jaka jest korzyść z jego używania w tablicach elementów?</summary>

#### React

W React prop `key` służy do identyfikowania każdego elementu na liście lub w
tablicy, aby pomóc Reactowi wydajnie zarządzać renderowaniem podczas zmian lub
aktualizacji elementów listy. Jest to ważne dla optymalizacji procesu
renderowania, szczególnie wtedy, gdy lista się zmienia (elementy są dodawane,
usuwane albo modyfikowane).

#### Najważniejsze kwestie dotyczące `key`:

1. **Unikalność:** Każdy element na liście powinien mieć unikalny `key`. Dzięki
   temu React może śledzić, które elementy się zmieniają, są dodawane albo
   usuwane, a także zachowywać ich stan między renderami.

2. **Optymalizacja renderowania:** Użycie `key` pozwala Reactowi zminimalizować
   liczbę ponownych renderów, wykonując tylko niezbędne zmiany w DOM. Bez `key`
   React ma większy problem z wykrywaniem zmian, co może prowadzić do pełnego
   ponownego renderowania listy, nawet jeśli zmienił się tylko jeden element.

3. **Charakter `key`:** Prop `key` nie jest przekazywany do komponentu, więc nie
   można go używać do wyświetlania wartości w interfejsie. To wewnętrzna
   właściwość używana przez React do śledzenia elementów.

#### Przykład użycia `key` na liście:

```jsx
const items = ['apple', 'banana', 'cherry'];

function FruitList() {
  return (

      {items.map((item, index) => (
        {item} // Ważne: używaj unikalnego key
      ))}

  );
}
```

#### Znaczenie unikalności `key`:

- **Nieprawidłowe użycie:** Jeśli jako `key` używa się nieunikalnych wartości
  (na przykład tego samego indeksu), React nie będzie w stanie poprawnie śledzić
  zmian, co doprowadzi do błędów renderowania.

- **Idealny `key`:** Jeśli element ma unikalny identyfikator, na przykład `id`,
  to właśnie jego należy użyć jako `key` zamiast indeksu tablicy.

```jsx
const items = [
  { id: 1, name: 'apple' },
  { id: 2, name: 'banana' },
  { id: 3, name: 'cherry' },
];

function FruitList() {
  return (

      {items.map(item => (
        {item.name} // Lepiej używać unikalnych id
      ))}

  );
}
```

#### Zalety używania `key`:

- Poprawia wydajność renderowania.

- Pozwala Reactowi optymalnie aktualizować tylko zmienione elementy, a nie całą
  listę.

- Zapewnia poprawną obsługę stanu elementów podczas ich przenoszenia, usuwania
  lub aktualizacji.

Dlatego używanie `key` jest ważne dla efektywnej pracy z tablicami elementów w
React.

</details>

<details>
<summary>18. Czym jest renderowanie warunkowe w React?</summary>

#### React

Renderowanie warunkowe w React to proces, w którym komponent renderuje różną
zawartość w zależności od określonych warunków. Pozwala to dynamicznie zmieniać
widok komponentu na podstawie stanu, propsów lub innych czynników.

#### Główne podejścia do renderowania warunkowego:

1. **Operator `if`:** Można użyć standardowego operatora `if`, aby zdecydować,
   co ma zostać wyrenderowane.

```jsx
function Greeting(props) {
  if (props.isLoggedIn) {
    return Welcome back!;
  }
  return Please sign up.;
}
```

2. **Operator trójargumentowy:** Jest często używany do krótszych wyrażeń
   warunkowych.

```jsx
function Greeting(props) {
  return {props.isLoggedIn ? 'Welcome back!' : 'Please sign up.'};
}
```

3. **Logiczne AND (`&&`) do renderowania:** Można użyć operatora `&&`, aby
   renderować element tylko wtedy, gdy wyrażenie po lewej stronie jest
   prawdziwe.

```jsx
function Notifications(props) {
  return (

      {props.unreadMessages.length > 0 && (
        You have {props.unreadMessages.length} unread messages.
      )}

  );
}
```

Działa to tak: jeśli `props.unreadMessages.length` jest większe od 0, zostanie
wyświetlona wiadomość; w przeciwnym razie nie pojawi się nic.

4. **Użycie `return` z operatorem warunkowym:** Możesz używać `return` do
   renderowania warunkowego w zależności od różnych warunków, jak w przykładzie
   z `if` lub operatorem trójargumentowym.

#### Zalety renderowania warunkowego:

- Pozwala dynamicznie zmieniać zawartość zależnie od stanu lub propsów.

- Zwiększa elastyczność i umożliwia wyświetlanie różnej treści dla różnych
  użytkowników lub sytuacji.

#### Przykład:

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

Tutaj przycisk zmienia się w zależności od tego, czy użytkownik jest zalogowany.

</details>

<details>
<summary>19. Czym są fragmenty (Fragments) w React?</summary>

#### React

Fragmenty w React to sposób grupowania kilku elementów bez dodawania
niepotrzebnych elementów do DOM. Pozwalają zwrócić kilka elementów z komponentu
bez opakowującego elementu, takiego jak `div`, co pomaga uniknąć zbędnych
elementów mogących zaburzyć style lub strukturę dokumentu.

#### Jak używa się fragmentów?

1. **Bez fragmentów (z opakowaniem):**

```jsx
function MyComponent() {
  return (

      Title
      Some text

  );
}
```

W tym przykładzie zwracany jest jeden `div`, który otacza `h1` i `p`.

2. **Z fragmentami (bez opakowania):**

```jsx
function MyComponent() {
  return <>Title Some text</>;
}
```

Teraz `h1` i `p` renderują się bez dodatkowego kontenera, co pozwala zachować
czystość DOM.

#### Zalety:

- **Czysty DOM:** Można obyć się bez zbędnych opakowań w DOM.

- **Wygoda przy renderowaniu wielu elementów:** Możliwość zwrócenia kilku
  elementów z jednego komponentu bez potrzeby używania dodatkowych znaczników.

#### Składnia:

- Można używać pustych tagów `<>` i `</>`, które są skrótem dla
  `<React.Fragment></React.Fragment>`.

- Można też używać `React.Fragment`, jeśli trzeba dodać klucze, na przykład
  podczas renderowania list:

```jsx
{
  item.name;
}
{
  item.description;
}
```

#### Kiedy używać:

- Gdy trzeba wyrenderować kilka elementów bez dodatkowego opakowania w DOM.

- Gdy chcesz zachować strukturę komponentu bez naruszania stylów lub układu.

Fragmenty są bardzo przydatne do ograniczania liczby zbędnych elementów w DOM i
poprawy wydajności.

</details>

<details>
<summary>20. Czym jest uzgadnianie (Reconciliation)?</summary>

#### React

**Reconciliation** (uzgadnianie) to proces, którego React używa do
aktualizowania DOM w możliwie najbardziej efektywny sposób. Gdy stan lub propsy
komponentu się zmieniają, React oblicza minimalny zakres zmian, które trzeba
wprowadzić do rzeczywistego DOM, aby zsynchronizować go ze stanem wirtualnego
DOM.

#### Jak działa reconciliation?

1. **Porównanie starego i nowego Virtual DOM:**

- React przechowuje kopię poprzedniego Virtual DOM.
- Gdy zmienia się stan lub propsy, tworzony jest nowy Virtual DOM.
- React porównuje nowy Virtual DOM z poprzednią kopią, używając algorytmu
  diffing.

2. **Wykrywanie różnic (diffing):**

- React identyfikuje, które części drzewa uległy zmianie: nowe elementy, zmiany
  atrybutów albo usunięcia elementów.
- W tym celu używany jest algorytm zoptymalizowany do pracy na strukturach
  drzewiastych.

3. **Aktualizacja rzeczywistego DOM:**

- React stosuje zmiany tylko do tych części DOM, które trzeba zaktualizować,
  unikając pełnego ponownego renderu.

#### Główne zasady reconciliation:

- **Zachowanie węzłów tego samego poziomu:** Jeśli węzły mają ten sam typ, na
  przykład `<div>` pozostaje `<div>`, React zmienia tylko atrybuty i elementy
  potomne.
- **Ponowne wykorzystanie komponentów:** Jeśli komponent pozostaje ten sam,
  React ponownie wykorzystuje jego istniejącą instancję.
- **Klucze dla list:** Jeśli lista elementów jest renderowana z tablicy, React
  używa kluczy (`key` prop) do porównywania i zachowywania węzłów.

#### Przykład działania:

```jsx
function App({ isVisible }) {
  return isVisible ? Hello : Goodbye;
}
```

- Jeśli `isVisible` zmieni się z `true` na `false`, React usunie `<h1>` i
  zastąpi go `<p>`.

#### Znaczenie kluczy (`key` prop) dla list:

Klucze pomagają Reactowi poprawnie określać zmiany na listach. Na przykład:

```jsx

  {items.map(item => (
    {item.text}
  ))}

```

Bez unikalnych kluczy React nie będzie w stanie dokładnie określić, które
elementy listy uległy zmianie.

#### Zalety reconciliation:

- Zmniejszenie liczby operacji na DOM.
- Zwiększenie wydajności aplikacji.
- Płynna aktualizacja interfejsu użytkownika.

</details>

<details>
<summary>21. Jak zaktualizować stan komponentu?</summary>

#### React

W React stan komponentu aktualizuje się za pomocą metody `setState` w
komponentach klasowych albo `useState` w komponentach funkcyjnych.

#### Komponenty klasowe:

Stan aktualizuje się przez `this.setState()`.

#### Przyklad:

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

#### Komponenty funkcyjne:

Stan aktualizuje się przez funkcję otrzymaną z `useState`.

#### Przyklad:

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

#### Uwagi:

1. **Asynchroniczność:** `setState` i `useState` działają asynchronicznie. Aby
   zaktualizować stan na podstawie poprzedniej wartości, użyj podejścia
   funkcyjnego:

```jsx
this.setState(prevState => ({ count: prevState.count + 1 }));
setCount(prevCount => prevCount + 1);
```

2. **Nie aktualizuj stanu bezpośrednio:** Modyfikacja stanu bez użycia
   `setState` albo `useState` nie wywołuje ponownego renderowania.

</details>

<details>
<summary>22. Czym są wbudowane wyrażenia warunkowe?</summary>

#### React

**Wbudowane wyrażenia warunkowe** w JavaScript, w tym w React, to mechanizmy,
które pozwalają umieszczać warunki bezpośrednio w JSX w celu warunkowego
renderowania elementów lub komponentów. Dzięki temu kod staje się bardziej
zwarty i łatwiejszy do zrozumienia.

#### Główne metody:

1. **Operator warunkowy (operator trójargumentowy):** To jeden z najczęściej
   używanych sposobów warunkowego renderowania elementów w JSX. Ma następującą
   składnię:

```jsx
warunek ? wyrazenie_jesli_prawda : wyrazenie_jesli_falsz;
```

**Przyklad:**

```jsx
const isLoggedIn = true;

function App() {
  return {isLoggedIn ? Welcome, User! : Please log in};
}
```

2. **Logiczny operator AND (`&&`):** Ta metoda pozwala wyświetlić komponent lub
   element tylko wtedy, gdy warunek ma wartość `true`. Jeśli warunek nie jest
   spełniony, nic nie zostanie wyrenderowane.

**Przyklad:**

```jsx
const isUserAdmin = true;

function App() {
  return {isUserAdmin && You have admin privileges};
}
```

W tym przypadku `<p>You have admin privileges</p>` zostanie wyświetlone tylko
wtedy, gdy `isUserAdmin` ma wartość `true`.

3. **`if` przed zwróceniem JSX:** Można też używać zwykłych instrukcji `if`
   przed zwróceniem JSX, gdy warunek jest bardziej złożony albo gdy trzeba
   wykonać kilka działań warunkowych.

**Przyklad:**

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

**Zalety:**

- Wbudowane wyrażenia warunkowe pozwalają pisać czystszy i bardziej zwarty kod.

- Poprawiają czytelność i ograniczają potrzebę stosowania dodatkowych
  konstrukcji warunkowych.

#### Ważne:

- W React nie można używać instrukcji `if` bezpośrednio w JSX. Można jednak
  zastosować je przed zwróceniem JSX.

</details>

<details>
<summary>23. Jaka jest różnica między obsługą zdarzeń w HTML i React?</summary>

#### React

#### Różnica między obsługą zdarzeń w HTML i React:

| Kryterium                 | HTML                                                         | React                                                                   |
| ------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------- |
| **Powiązanie zdarzenia**  | Określane jako atrybut: `<button onclick="handler()">`.      | Używany jest zapis camelCase: `<button onClick={handler}>`.             |
| **Typ funkcji**           | Odwołanie do funkcji globalnej albo ciąg z kodem JavaScript. | Powiązanie z funkcją komponentu, zwykle metodą albo funkcją strzałkową. |
| **Dodawanie nasłuchu**    | Handlery dodaje się ręcznie przez `addEventListener`.        | React automatycznie zarządza powiązaniem przez wirtualny DOM.           |
| **Kontekst `this`**       | Trzeba ręcznie ustawiać kontekst, jeśli używa się klas.      | W komponentach funkcyjnych problem kontekstu `this` nie występuje.      |
| **Domyślne zachowanie**   | Trzeba jawnie wywołać `return false`, aby je zatrzymać.      | Używa się `event.preventDefault()`, aby zatrzymać domyślne zachowanie.  |
| **Zgodność**              | Obsługuje tylko rzeczywiste zdarzenia DOM.                   | Używa `SyntheticEvent`, czyli warstwy nad natywnymi zdarzeniami.        |
| **Wieloprzeglądarkowość** | Trzeba ręcznie uwzględniać różnice między przeglądarkami.    | React zapewnia zgodność między przeglądarkami dzięki `SyntheticEvent`.  |
| **Powiązanie kontekstu**  | Często wymaga użycia `bind`.                                 | W komponentach klasowych bywa potrzebny `bind`, w funkcyjnych nie.      |

#### Przyklad w HTML:

```html
Click me
```

#### Przyklad w React:

```jsx
function handleClick() {
  alert('Clicked!');
}

function App() {
  return Click me;
}
```

#### SyntheticEvent w React:

React używa warstwy nad natywnymi zdarzeniami, która normalizuje zachowanie
między różnymi przeglądarkami i poprawia wydajność.

</details>

<details>
<summary>24. Czym są zdarzenia syntetyczne w React?</summary>

#### React

**Zdarzenia syntetyczne (Synthetic Events)** w React to opakowania dla natywnych
zdarzeń DOM, które zapewniają jednolity interfejs do obsługi zdarzeń w różnych
przeglądarkach. React tworzy `SyntheticEvent` dla każdego zdarzenia, co pozwala
pracować ze zdarzeniami w ujednolicony sposób, zapewniając zgodność między
przeglądarkami i poprawiając wydajność.

#### Główne cechy:

1. **Wieloprzeglądarkowość:** `SyntheticEvent` abstrahuje różnice w obsłudze
   zdarzeń między przeglądarkami, zapewniając spójne zachowanie.

2. **Optymalizacja:** `SyntheticEvent` wykorzystuje pulę obiektów, co pozwala
   ograniczyć koszt tworzenia nowych obiektów zdarzeń.

3. **Jednorazowe użycie:** Po obsłudze zdarzenia obiekt `SyntheticEvent` "wraca"
   do puli i nie powinien być później używany. W przypadku operacji
   asynchronicznych trzeba zapisać dane zdarzenia w osobnej zmiennej.

4. **Interfejs:** `SyntheticEvent` ma takie same metody jak standardowe
   zdarzenia natywne, na przykład `preventDefault()` i `stopPropagation()`.

#### Przyklad użycia:

```jsx
function handleClick(event) {
  // SyntheticEvent udostępnia metodę preventDefault()
  event.preventDefault();
  console.log('Button clicked!');
}

function App() {
  return Click me;
}
```

W tym przykładzie `event` to `SyntheticEvent`, który działa podobnie do
zdarzenia natywnego, ale oferuje dodatkowe usprawnienia.

</details>

<details>
<summary>25. Jak obsługiwać zdarzenia w React?</summary>

#### React

W React obsługa zdarzeń działa podobnie do standardowego JavaScript, ale z
kilkoma różnicami. Zdarzenia w React są syntetyczne, co oznacza, że stanowią
warstwę abstrakcji nad rzeczywistymi zdarzeniami przeglądarki, zapewniając
zgodność między przeglądarkami.

#### Główne zasady obsługi zdarzeń w React:

1. **Zdarzenia syntetyczne:** Wszystkie zdarzenia w React są opakowane w obiekt
   **SyntheticEvent**, który stanowi wieloprzeglądarkową implementację
   standardowych zdarzeń DOM. Dzięki temu można obsługiwać zdarzenia tak samo we
   wszystkich przeglądarkach.

2. **Użycie camelCase dla zdarzeń:** W React nazwy zdarzeń zapisuje się w
   formacie camelCase zamiast standardowego zapisu małymi literami, na przykład
   `onClick` zamiast `onclick`.

3. **Przekazywanie funkcji jako handlerów zdarzeń:** Zdarzenia w React są
   obsługiwane za pomocą funkcji przekazywanych przez atrybuty komponentów.

#### Przyklad obsługi zdarzenia `click`:

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

#### Przyklad z komponentem funkcyjnym:

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

#### Cechy obsługi zdarzeń:

1. **Nie trzeba używać `addEventListener`:** W React nie ma potrzeby ręcznego
   dodawania ani usuwania handlerów zdarzeń. Biblioteka React zarządza tym
   automatycznie.

2. **Zachowanie kontekstu w metodach komponentów klasowych:** Jeśli metody
   komponentów klasowych są używane jako handlery zdarzeń, kontekst (`this`)
   trzeba powiązać za pomocą funkcji strzałkowych albo ręcznie w konstruktorze.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
    // Powiązanie metody
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

3. **Przekazywanie parametrów do handlera:** Jeśli trzeba przekazać dodatkowe
   argumenty do obsługi zdarzenia, można użyć funkcji strzałkowych albo funkcji
   z parametrami.

```jsx
function MyButton({ label }) {
  const handleClick = (event, label) => {
    console.log(label);
  };

  return <button onClick={event => handleClick(event, label)}>{label};
}
```

#### Obsługa zdarzeń w DOM:

Wszystkie zdarzenia w React działają zgodnie z zasadą delegowania zdarzeń, gdzie
jeden handler jest rejestrowany dla całego drzewa komponentów i przechodzi przez
mechanizm `React SyntheticEvent`.

</details>

<details>
<summary>26. Czym są zdarzenia wskaźnika (Pointer Events)?</summary>

#### React

#### Zdarzenia wskaźnika (Pointer Events) w React

**Pointer Events** to API, które łączy zdarzenia myszy, ekranu dotykowego i
rysika w jeden system obsługi zdarzeń.

#### Główne zdarzenia Pointer Events

| **Zdarzenie**       | **Opis**                                                                         |
| ------------------- | -------------------------------------------------------------------------------- |
| **onPointerDown**   | Uruchamia się przy naciśnięciu palcem, myszą albo rysikiem.                      |
| **onPointerUp**     | Uruchamia się przy zwolnieniu przycisku myszy, palca albo rysika.                |
| **onPointerMove**   | Wywoływane podczas ruchu wskaźnika nad elementem.                                |
| **onPointerEnter**  | Uruchamia się, gdy wskaźnik wchodzi w obszar elementu.                           |
| **onPointerLeave**  | Uruchamia się, gdy wskaźnik opuszcza obszar elementu.                            |
| **onPointerCancel** | Wywoływane, gdy przeglądarka anuluje zdarzenie, na przykład przy zmianie fokusu. |

#### Przyklad użycia w React

```jsx
const PointerExample = () => {
  const handlePointerDown = () => console.log('Wskaznik nacisniety');

  return (

      Kliknij tutaj

  );
};
```

Ten kod wypisze w konsoli `"Wskaznik nacisniety"` po naciśnięciu dowolnym
urządzeniem: myszą, dotykiem albo rysikiem.

</details>

<details>
<summary>27. Kiedy używać komponentu klasowego zamiast funkcyjnego?</summary>

#### React

Komponenty klasowe były używane wtedy, gdy potrzebna była jedna lub kilka z
poniższych funkcji:

1. **Praca ze stanem (`state`):** Dawniej komponenty funkcyjne nie obsługiwały
   lokalnego stanu, dlatego używano do tego klas. Dziś hooki, takie jak
   `useState` i `useReducer`, pozwalają komponentom funkcyjnym pracować ze
   stanem.

2. **Metody cyklu życia:** Klasy zapewniały dostęp do metod takich jak
   `componentDidMount`, `componentDidUpdate` i `componentWillUnmount`, które
   pozwalały zarządzać komponentem na różnych etapach jego istnienia. Obecnie
   najczęściej zastępuje to hook `useEffect`.

3. **Obsługa złożonej logiki:** Jeśli logika wymagała kilku metod i dostępu do
   właściwości przez `this`, klasy wydawały się naturalnym wyborem. Współcześnie
   takie zadania zwykle realizuje się za pomocą hooków, które pozwalają
   enkapsulować logikę.

#### Kiedy klasy nie są już potrzebne:

Od React 16.8 komponenty funkcyjne z hookami w dużej mierze zastąpiły potrzebę
używania komponentów klasowych. Dlatego w nowych projektach warto preferować
komponenty funkcyjne, a klasy zachowywać głównie do utrzymania starszego kodu.

</details>

<details>
<summary>28. Czym są komponenty bezstanowe (stateless components)?</summary>

#### React

Komponenty bezstanowe (`stateless components`) to komponenty, które nie
przechowują ani nie obsługują żadnego wewnętrznego stanu. Otrzymują dane przez
propsy i wyświetlają je w interfejsie użytkownika. Zazwyczaj są to komponenty
funkcyjne.

#### Cechy:

1. **Brak stanu:** Nie używają `this.state` i nie zmieniają swojego wewnętrznego
   stanu.

2. **Tylko renderowanie:** Po prostu otrzymują propsy i wyświetlają je jako
   elementy interfejsu.

3. **Prostota i przewidywalność:** Łatwiej je testować i utrzymywać, ponieważ
   nie trzeba śledzić zmian stanu.

#### Przyklad:

```jsx
// Stateless component
function Greeting(props) {
  return Hello, {props.name}!;
}

// Uzycie:
;
```

#### Zalety:

- **Prostota:** Są łatwiejsze do zrozumienia i utrzymania.

- **Optymalizacja wydajności:** Ponieważ te komponenty nie mają stanu, React
  może je aktualizować bardziej efektywnie.

#### Kiedy używać:

- Gdy komponent tylko wyświetla dane i nie wymaga zmian stanu.

</details>

<details>
<summary>29. Czym są komponenty stanowe (stateful components)?</summary>

#### React

**Komponenty stanowe** (`stateful components`) to komponenty, które przechowują
i zarządzają swoim wewnętrznym stanem. Używają `state` do przechowywania danych,
które mogą zmieniać się w czasie, a te zmiany wpływają na renderowanie
komponentu.

#### Cechy:

1. **Stan (`state`):** Używają `this.state` do przechowywania i zarządzania
   danymi, które mogą się zmieniać.

2. **Metody aktualizacji stanu:** Używają metody `this.setState()` do
   aktualizowania stanu.

3. **Cykl życia:** Mają dostęp do metod cyklu życia komponentu, takich jak
   `componentDidMount()`, `shouldComponentUpdate()` czy `componentDidUpdate()`.

#### Przyklad:

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

#### Zalety:

- **Dynamiczne komponenty:** Mogą zmieniać swoją zawartość i wygląd na podstawie
  zmian stanu.

- **Interaktywność:** Nadają się do tworzenia interaktywnych interfejsów, gdy
  trzeba aktualizować stan podczas interakcji użytkownika.

#### Kiedy używać:

Gdy komponent wymaga zarządzania wewnętrznym stanem, na przykład do
przechowywania danych wpisywanych w formularzu, licznika, wyboru i podobnych
wartości.

</details>

<details>
<summary>30. Czym są czyste komponenty (Pure Components)?</summary>

#### React

**Czyste komponenty (Pure Components)** to specjalne komponenty klasowe React,
które automatycznie optymalizują renderowanie. Wykonują płytkie porównanie
propsów i stanu, aby zapobiegać zbędnym aktualizacjom, jeśli wartości propsów
lub stanu się nie zmieniły.

#### Jak utworzyć czysty komponent?

Czysty komponent tworzy się przez dziedziczenie po `React.PureComponent`.

```jsx
import React, { PureComponent } from 'react';

class MyComponent extends PureComponent {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Uzycie:
;
```

#### Jak działa `PureComponent`?

- Wykonuje płytkie porównanie (`shallow comparison`) propsów i stanu w metodzie
  `shouldComponentUpdate`.

- Jeśli propsy i stan się nie zmieniły, komponent nie renderuje się ponownie.

#### Kiedy używać `PureComponent`?

- Gdy propsy i stan są prostymi strukturami, na przykład wartościami
  prymitywnymi albo płytkimi obiektami.

- Aby poprawić wydajność w komponentach, które często się aktualizują.

#### Ograniczenia:

1. **Głębokie porównanie:** `PureComponent` nie uwzględnia zmian wewnątrz
   zagnieżdżonych obiektów lub tablic. Na przykład jeśli aktualizujesz obiekt,
   ale referencja do niego pozostaje taka sama, komponent się nie zaktualizuje.

```jsx
this.setState({ data: { ...this.state.data, key: 'new value' } }); // Obejscie
```

2. **Nie działa z komponentami funkcyjnymi:** Alternatywą jest użycie
   `React.memo` do optymalizacji komponentów funkcyjnych.

```jsx
const MyComponent = React.memo(function MyComponent(props) {
  return Hello, {props.name}!;
});
```

</details>

<details>
<summary>31. Czym są komponenty wyższego rzędu (Higher-Order Components)?</summary>

#### React

**Komponent wyższego rzędu** to funkcja, która przyjmuje komponent jako argument
wejściowy i zwraca nowy komponent, rozszerzając jego funkcjonalność.

#### Składnia HOC:

```jsx
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

#### Cechy HOC:

1. **Przyjmuje komponent jako argument.**
2. **Zwraca nowy komponent z dodatkowymi właściwościami albo zachowaniem.**
3. **Pozwala ponownie wykorzystywać logikę w różnych komponentach.**

#### Przyklad użycia:

HOC do dodawania stanu do komponentu:

```jsx
import React, { useState } from 'react';

// HOC: dodaje logikę pracy ze stanem
function withCounter(WrappedComponent) {
  return function EnhancedComponent(props) {
    const [count, setCount] = useState(0);

    const increment = () => setCount(count + 1);

    return ;
  };
}

// Komponent, który zostanie rozszerzony
function Button({ count, increment }) {
  return Clicked {count} times;
}

// Uzycie HOC
const EnhancedButton = withCounter(Button);

export default EnhancedButton;
```

#### Praktyczne zastosowania HOC:

1. **Autoryzacja (Authentication):** Owijanie komponentów w celu sprawdzania
   uprawnień dostępu.

2. **Obsługa danych:** Podłączanie do API albo obsługa stanu.

3. **Logowanie:** Dodawanie rejestrowania działań komponentów.

#### Ograniczenia HOC:

- Może tworzyć głębokie zagnieżdżenia w drzewie komponentów, jeśli używa się
  zbyt wielu HOC.

- Utrudnia czytelność przez dodatkowe opakowywanie komponentów.

HOC to potężne narzędzie do ponownego wykorzystania logiki, ale w nowoczesnych
aplikacjach często zastępują je React Hooks.

</details>

<details>
<summary>32. Czym jest prop children?</summary>

#### React

#### Czym jest prop `children`?

`children` to specjalny prop w React, używany do przekazywania zagnieżdżonych
elementów albo komponentów do komponentu-opakowania.

#### Jak to działa?

Gdy przekazujesz zawartość między otwierającym i zamykającym tagiem komponentu,
ta zawartość jest automatycznie przekazywana jako wartość `props.children`.

#### Przyklad:

- **Komponent-opakowanie:**

```jsx
function Wrapper({ children }) {
  return { children };
}
```

- **Uzycie:**

```jsx
function App() {
  return (

      Hello, World!
      This is a paragraph inside the wrapper.

  );
}
```

- **Rezultat:**

```html
Hello, World! This is a paragraph inside the wrapper.
```

#### Kluczowe cechy `children`:

1. **Elastyczność:** Można przekazywać dowolny typ danych: tekst, JSX,
   komponenty albo tablice elementów.

2. **Ponowne wykorzystanie:** Komponent-opakowanie może dynamicznie wyświetlać
   różną zawartość.

3. **Strukturalność:** Pomaga tworzyć komponenty o zagnieżdżonej strukturze.

#### Użycie `children` z propsami funkcyjnymi:

Czasami `children` jest używane jako funkcja do dynamicznego przekazywania
danych:

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

#### Rezultat:

```html
Apple Banana Cherry
```

`children` to potężne narzędzie do tworzenia uniwersalnych i wielokrotnego
użytku komponentów w React.

</details>

<details>
<summary>33. Czym jest portal (Portal)?</summary>

#### React

**Portal (Portal)** w React to sposób renderowania elementów podrzędnych do
węzła DOM, który znajduje się poza hierarchią DOM komponentu nadrzędnego.

#### Jak działa:

React udostępnia portale przez metodę `ReactDOM.createPortal`, która przyjmuje
dwa argumenty:

1. **Element React**, który należy wyrenderować.

2. **Docelowy węzeł DOM**, do którego należy wstawić element.

#### Składnia:

```jsx
ReactDOM.createPortal(child, container);
```

- **`child`** to element React, który trzeba wyrenderować.

- **`container`** to węzeł DOM, do którego element zostanie wstawiony.

#### Przyklad użycia:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function Modal({ children }) {
  return ReactDOM.createPortal(
    {children},
    document.getElementById('modal-root') // Wezel docelowy
  );
}

function App() {
  return (

      Główna zawartość

        To jest zawartość okna modalnego


  );
}
```

#### Gdzie używa się portali:

- Okna modalne.

- Podpowiedzi (tooltips).

- Menu kontekstowe.

#### Cechy:

1. **Hierarchia zdarzeń:** Choć element jest renderowany poza hierarchią DOM,
   obsługa zdarzeń odbywa się zgodnie z hierarchią komponentów React. Na
   przykład zdarzenia `onClick` będą propagować się do komponentów nadrzędnych
   React.

2. **Elastyczność:** Portale pozwalają wstawiać elementy w miejsca, które nie
   pasują do bieżącej struktury DOM.

#### Zalety:

- Łatwe zarządzanie "pływającymi" elementami.
- Zachowanie kontekstu React nawet poza główną hierarchią DOM.

</details>

<details>

<summary>34. Jak działają portale (Portals) w React i jakie są ich zalety oraz główne zastosowania w UI?</summary>

#### React

**Portale (Portals)** w React pozwalają renderować elementy podrzędne do innej
części DOM zamiast do standardowego miejsca renderowania komponentu. Jest to
przydatne przy umieszczaniu elementów, które powinny znajdować się poza zwykłą
hierarchią DOM, na przykład okien modalnych, tooltipów albo elementów
wyskakujących.

#### Główne zalety portali:

- Pozwalają renderować elementy w innym miejscu DOM bez naruszania struktury
  komponentów React.

- Są przydatne wtedy, gdy trzeba renderować elementy ponad inną zawartością, na
  przykład okna modalne albo wyskakujące menu.

#### Jak działają portale:

- Portal pozwala wysłać zawartość do dowolnego miejsca DOM, nawet poza głównym
  kontenerem React.

#### Przyklad użycia portalu:

```jsx
import ReactDOM from 'react-dom';

const Modal = () => {
  return ReactDOM.createPortal(
    <div className="modal">
      <h1>To jest okno modalne</h1>
    </div>,
    document.getElementById('modal-root') // Miejsce w DOM, do którego renderujemy portal
  );
};

const App = () => {
  return (
    <div>
      <h1>Strona główna</h1>
      <Modal />
    </div>
  );
};
```

#### Kluczowe kwestie:

- `ReactDOM.createPortal()`: służy do tworzenia portalu. Pierwszy argument to
  zawartość renderowana, a drugi to element DOM, do którego ta zawartość jest
  wstawiana.

- Portale mogą być używane do okien modalnych, tooltipów, wyskakujących menu i
  innych elementów, które powinny być wyświetlane poza głównym drzewem
  komponentów.

#### Cechy:

- Chociaż elementy renderowane przez portale znajdują się poza główną hierarchią
  komponentów React, nadal mają dostęp do kontekstu, stanu i propsów swoich
  rodziców.

- Portale są przydatne, gdy elementy powinny być umieszczone "nad" inną
  zawartością albo na innym poziomie hierarchii DOM, na przykład gdy okno
  modalne nie powinno być ograniczane przez kontener rodzica.

Portale pozwalają zachować logikę komponentu i strukturę bez łamania zasad DOM,
co umożliwia tworzenie wygodnych i czystych komponentów UI.

</details>

<details>
<summary>35. Jakie są metody cyklu życia komponentu w React?</summary>

#### React

Metody cyklu życia komponentu w React służą do zarządzania różnymi etapami życia
komponentów: tworzeniem, aktualizacją i usuwaniem.

#### Główne fazy cyklu życia:

1. **Montowanie (Mounting):** Gdy komponent jest dodawany do DOM.

`constructor()`: Inicjalizacja stanu i powiązanie metod.

`static getDerivedStateFromProps(props, state)`: Aktualizacja stanu przed
renderowaniem, rzadko używana.

`render()`: Renderuje JSX do Virtual DOM.

`componentDidMount()`: Jest wywoływana zaraz po dodaniu komponentu do DOM. Używa
się jej do zapytań API i inicjalizacji bibliotek.

2. **Aktualizacja (Updating):** Gdy zmieniają się propsy albo stan.

`static getDerivedStateFromProps(props, state)`: Wywoływana przed każdym
renderowaniem.

`shouldComponentUpdate(nextProps, nextState)`: Określa, czy komponent powinien
zostać ponownie wyrenderowany. Domyślnie zwraca `true`.

`render()`: Wykonuje się w celu aktualizacji Virtual DOM.

`getSnapshotBeforeUpdate(prevProps, prevState)`: Pobiera stan przed zmianami, na
przykład pozycję scrolla.

`componentDidUpdate(prevProps, prevState, snapshot)`: Wywoływana po
aktualizacji. Służy do ponownych zapytań albo pracy z DOM.

3. **Odmontowanie (Unmounting):** Gdy komponent jest usuwany z DOM.

`componentWillUnmount()`: Służy do czyszczenia zasobów, na przykład timerów i
subskrypcji.

4. **Obsługa błędów (Error Handling):** Gdy komponent powoduje błąd.

`static getDerivedStateFromError(error)`: Pozwala zaktualizować stan po błędzie.

`componentDidCatch(error, info)`: Logowanie błędów.

#### Tabela metod:

| Faza               | Metoda                       | Opis                                      |
| ------------------ | ---------------------------- | ----------------------------------------- |
| **Montowanie**     | `constructor()`              | Inicjalizacja stanu i konfiguracja.       |
|                    | `getDerivedStateFromProps()` | Aktualizacja stanu przed renderem.        |
|                    | `render()`                   | Renderowanie JSX do Virtual DOM.          |
|                    | `componentDidMount()`        | Wykonuje się po dodaniu do DOM.           |
| **Aktualizacja**   | `getDerivedStateFromProps()` | Aktualizacja stanu przed renderem.        |
|                    | `shouldComponentUpdate()`    | Określa, czy potrzebny jest rerender.     |
|                    | `render()`                   | Aktualizuje Virtual DOM.                  |
|                    | `getSnapshotBeforeUpdate()`  | Pobiera migawkę stanu przed aktualizacją. |
|                    | `componentDidUpdate()`       | Wykonuje się po aktualizacji.             |
| **Odmontowanie**   | `componentWillUnmount()`     | Czyszczenie zasobów przed usunięciem.     |
| **Obsługa błędów** | `getDerivedStateFromError()` | Aktualizuje stan w razie błędu.           |
|                    | `componentDidCatch()`        | Logowanie błędów.                         |

#### Współczesne podejście:

W komponentach funkcyjnych zamiast metod cyklu życia używa się **hooków**:

- `useEffect` zastępuje `componentDidMount`, `componentDidUpdate` i
  `componentWillUnmount`.

- `useState` służy do zarządzania stanem.

</details>

<details>
<summary>36. Co robi metoda shouldComponentUpdate?</summary>

#### React

- `shouldComponentUpdate` to metoda cyklu życia w komponentach klasowych, która
  określa, czy komponent powinien zostać ponownie wyrenderowany.

#### Jak działa:

- Domyślnie zwraca `true`, co oznacza rerender przy każdej zmianie `state` albo
  `props`.

- Jeśli zwraca `false`, React nie wyrenderuje komponentu ponownie, nawet jeśli
  `props` albo `state` się zmieniły.

#### Przyklad użycia:

```jsx
class MyComponent extends React.Component {
  shouldComponentUpdate(nextProps, nextState) {
    return nextProps.value !== this.props.value; // Rerender tylko przy zmianie value
  }

  render() {
    return <div>{this.props.value}</div>;
  }
}
```

#### Alternatywa w komponentach funkcyjnych:

- Użyj `React.memo()` do memoizacji.

- `useMemo()` i `useCallback()` pomagają optymalizować rerendery.

</details>

<details>
<summary>37. Jak wykonać kod przed usunięciem komponentu z drzewa?</summary>

#### React

Aby wykonać kod przed usunięciem komponentu z drzewa w React, stosuje się
następujące podejścia:

1. **Komponenty klasowe:** `componentWillUnmount`

W komponentach klasowych istnieje metoda cyklu życia `componentWillUnmount`,
która jest wywoływana przed usunięciem komponentu.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Komponent zostanie usuniety');
  }

  render() {
    return <div>Moj komponent</div>;
  }
}
```

2. **Komponenty funkcyjne:** `useEffect` z funkcją czyszczącą

W komponentach funkcyjnych czyszczenie można wykonać w `useEffect`, zwracając
funkcję, która uruchomi się przed usunięciem komponentu.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Komponent zostanie usuniety');
    };
  }, []);

  return <div>Moj komponent</div>;
}
```

3. **Obsługa przed zamknięciem strony (`beforeunload`)**

Jeśli trzeba wykonać kod przed zamknięciem karty albo odświeżeniem strony:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Strona jest zamykana');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Wniosek

- `componentWillUnmount` dla komponentów klasowych.

- `useEffect` ze zwracaną funkcją dla komponentów funkcyjnych.

- `beforeunload` dla sytuacji, w których trzeba reagować na opuszczenie strony.

</details>

<details>
<summary>38. Dlaczego fragmenty (Fragment) są lepsze niż kontenerowe divy?</summary>

#### React

Fragmenty (`<React.Fragment>` albo `<>...</>`) są lepsze od kontenerowych
`<div>` w React z kilku powodów:

1. **Mniej zbędnego HTML**

- Fragmenty nie dodają dodatkowego elementu do DOM, co zmniejsza liczbę
  zagnieżdżonych tagów i poprawia wydajność.

```jsx
<>
  <h1>Title</h1>
  <p>Text</p>
</>
```

- Rezultat w DOM:

```html
<h1>Title</h1>
<p>Text</p>
```

- W przeciwieństwie do `<div>`, który dodawałby zbędne zagnieżdżenie:

```html
<div>
  <h1>Title</h1>
  <p>Text</p>
</div>
```

2. **Brak ubocznych efektów stylistycznych**

- Dodatkowy `<div>` może wpływać na style CSS i powodować niepożądane zmiany w
  układzie. Fragmenty tego unikają.

3. **Lepsza zgodność z tabelami**

- W `<table>` nie można bezpośrednio umieszczać `<div>`, ale można używać
  fragmentów:

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

- To działa poprawnie, podczas gdy `<div>` spowodowałby błąd.

4. **Optymalizacja wydajności**

- Mniej zbędnych węzłów w DOM oznacza szybsze renderowanie i mniejsze zużycie
  pamięci.

</details>

<details>
<summary>39. Czym są Hooki (Hooks) w React?</summary>

#### React

**Hooki React (Hooks)** to funkcje, które pozwalają używać stanu i innych
możliwości React bez pisania klas.

#### Główne typy hooków:

1. **useState** pozwala dodawać stan do komponentów funkcyjnych.

```jsx
const [state, setState] = useState(initialState);
```

2. **useEffect** pozwala wykonywać efekty uboczne, na przykład zapytania do API
   albo subskrypcje, w komponentach funkcyjnych.

```jsx
useEffect(() => {
  // kod efektu
}, [dependencies]); // zaleznosci
```

3. **useContext** daje dostęp do wartości kontekstu bez konieczności używania
   komponentu Consumer.

```jsx
const value = useContext(MyContext);
```

4. **useRef** pozwala tworzyć referencje do elementów DOM albo przechowywać
   wartości między renderami bez zmiany stanu.

```jsx
const myRef = useRef(initialValue);
```

5. **useReducer** to alternatywa dla `useState`, wygodna do zarządzania bardziej
   złożonym stanem przez reducery, podobnie jak w Redux.

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

6. **useMemo** optymalizuje obliczanie wartości, aby uniknąć niepotrzebnych
   ponownych obliczeń.

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

7. **useCallback** zwraca zmemowaną wersję funkcji, aby nie była tworzona od
   nowa przy każdym renderze.

```jsx
const memoizedCallback = useCallback(() => {
  // funkcja;
}, [dependencies]);
```

#### Główne zalety:

- **Komponenty funkcyjne:** Zamiast komponentów klasowych możesz używać
  komponentów funkcyjnych z hookami.

- **Lepsza czytelność:** Logikę można podzielić na kilka hooków, co zmniejsza
  ilość kodu i zwiększa modułowość.

- **Ponowne wykorzystanie logiki:** Hooki pozwalają używać tej samej logiki w
  różnych komponentach bez tworzenia złożonych hierarchii.

</details>

<details>
<summary>40. Jakie są zalety Hooków (Hooks) w React?</summary>

#### React

| **Zaleta**                         | **Opis**                                                                                        |
| ---------------------------------- | ----------------------------------------------------------------------------------------------- |
| **Mniej kodu**                     | Hooki pozwalają uniknąć klas i zmniejszyć objętość kodu.                                        |
| **Lepsza czytelność**              | Kod z hookami jest łatwiejszy do zrozumienia i utrzymania.                                      |
| **Ponowne wykorzystanie logiki**   | Custom Hooks pozwalają ponownie wykorzystywać logikę między komponentami.                       |
| **Uproszczone zarządzanie stanem** | Użycie `useState` i `useReducer` upraszcza zarządzanie stanem.                                  |
| **Elastyczność w użyciu efektów**  | `useEffect` pozwala wykonywać efekty uboczne bez potrzeby używania klasowych metod cyklu życia. |
| **Łatwiejsza migracja**            | Ułatwia przejście z komponentów klasowych na funkcyjne.                                         |

</details>

<details>
<summary>41. Jakie są wady Hooków (Hooks) w React?</summary>

#### React

| **Wada**                             | **Opis**                                                                                           |
| ------------------------------------ | -------------------------------------------------------------------------------------------------- |
| **Większa liczba rerenderów**        | Nieprawidłowe użycie hooków, szczególnie `useEffect`, może powodować zbędne rerendery.             |
| **Trudniejsze zrozumienie logiki**   | Logika komponentu może być rozproszona między kilkoma `useEffect`, co utrudnia debugowanie.        |
| **Brak jawnego cyklu życia**         | W przeciwieństwie do komponentów klasowych hooki nie mają wyraźnie wydzielonych metod cyklu życia. |
| **Możliwe problemy z optymalizacją** | Nieprawidłowe użycie `useCallback` i `useMemo` może prowadzić do nieefektywnego działania.         |
| **Złożoność w dużych projektach**    | W dużych aplikacjach hooki mogą utrudniać zarządzanie stanem i efektami ubocznymi.                 |

</details>

<details>
<summary>42. Jakie są zasady i ograniczenia używania Hooków (Hooks) w React?</summary>

#### React

| **Zasada**                                 | **Opis**                                                                                                                          |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| **Używanie tylko w funkcjach**             | Hooki można wywoływać tylko w komponentach funkcyjnych albo w custom hooks.                                                       |
| **Zachowanie kolejności wywołań**          | Hooków nie można wywoływać warunkowo (`if`, `for`, `while`), bo zaburzy to kolejność wywołań.                                     |
| **Wywołanie tylko na najwyższym poziomie** | Hooków nie można wywoływać wewnątrz zagnieżdżonych funkcji ani handlerów zdarzeń.                                                 |
| **Nazewnictwo custom hooks**               | Custom hooks powinny zaczynać się od `use`, na przykład `useAuth`.                                                                |
| **Przestrzeganie zasad zależności**        | W `useEffect`, `useMemo` i `useCallback` trzeba poprawnie wskazywać zależności (`[]`), aby uniknąć nieprzewidywalnego zachowania. |

</details>

<details>
<summary>43. Czym jest useReducer()?</summary>

#### React

`useReducer()` to hook w React, używany do zarządzania stanem w komponentach
funkcyjnych. Jest alternatywą dla `useState()`, która dobrze sprawdza się przy
bardziej złożonej logice aktualizacji stanu, szczególnie gdy zmiany zależą od
poprzedniego stanu.

#### Składnia:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` to funkcja, która przyjmuje `state` i `action`, a następnie zwraca
  nowy stan.

- `initialState` to stan początkowy.

- `dispatch` to funkcja do wywołania reducera z określoną `action`.

#### Przyklad:

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

#### Kiedy używać:

- Gdy stan ma złożoną logikę albo zależności.

- Gdy trzeba ujednolicić aktualizacje stanu przez `dispatch`.

- Dla większej skalowalności, na przykład przy użyciu w stanie globalnym.

</details>

<details>
<summary>44. Opowiedz o hookach useCallback(), useMemo(), useImperativeHandle() i useLayoutEffect()?</summary>

#### React

#### useCallback()

Memoizuje funkcję, aby nie była tworzona od nowa przy każdym renderze. Jest to
przydatne przy przekazywaniu callbacków do komponentów podrzędnych.

- **Przyklad:**

```jsx
import { useCallback } from 'react';

function MyComponent({ onClick }) {
  return <button onClick={onClick}>Kliknij</button>;
}

function Parent() {
  const handleClick = useCallback(() => {
    console.log('Klik');
  }, []); // Funkcja jest tworzona tylko raz

  return <MyComponent onClick={handleClick} />;
}
```

#### useMemo()

Memoizuje obliczenia, aby nie wykonywać ich ponownie przy każdym renderze, jeśli
zależności się nie zmieniły.

#### Przyklad:

```jsx
import { useMemo } from "react";

function ExpensiveCalculation({ num }) {
const result = useMemo(() => {
console.log("Obliczanie...");
return num \* 2;
}, [num]); // Wykonuje się tylko przy zmianie num

return <div>Wynik: {result}</div>;
}
```

#### useImperativeHandle()

Pozwala kontrolować zachowanie refa w komponencie podrzędnym. Używa się go razem
z `forwardRef()`.

#### Przyklad:

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
      <button onClick={() => inputRef.current.clear()}>Wyczysc</button>
    </div>
  );
}
```

#### useLayoutEffect()

Działa jak `useEffect()`, ale wykonuje się synchronicznie po zmianach w DOM.
Jest przydatny do pomiarów albo manipulacji DOM zanim przeglądarka narysuje
stronę.

- **Przyklad:**

```jsx
import { useLayoutEffect, useRef } from 'react';

function LayoutEffectExample() {
  const divRef = useRef();

  useLayoutEffect(() => {
    console.log('Szerokosc elementu:', divRef.current.offsetWidth);
  }, []);

  return (
    <div ref={divRef} style={{ width: '200px', height: '100px' }}>
      Element
    </div>
  );
}
```

#### Kiedy używać którego hooka?

- `useCallback()` służy do zapamiętywania funkcji.

- `useMemo()` służy do zapamiętywania obliczeń.

- `useImperativeHandle()` służy do kontrolowania refa komponentu podrzędnego.

- `useLayoutEffect()` stosuj wtedy, gdy trzeba coś zrobić przed wyświetleniem
  zmian w DOM, na przykład wykonać pomiar.

</details>

<details>
<summary>45. Jak zrealizować jednorazowe wykonanie operacji podczas początkowego renderowania?</summary>

#### React

Aby wykonać operację tylko raz podczas początkowego renderowania w komponentach
funkcyjnych, użyj `useEffect` z pustą tablicą zależności (`[]`):

#### Przyklad:

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    console.log('To wykona się tylko raz po zamontowaniu komponentu');
  }, []);

  return <div>Komponent</div>;
}
```

#### Wyjaśnienie:

- `useEffect(() => { /_ kod _/ }, [])` oznacza, że pusty array zależności
  uruchomi efekt tylko raz po pierwszym renderowaniu, czyli analogicznie do
  `componentDidMount` w komponentach klasowych.

#### Dodatkowo, na przykład subskrypcja i jej usunięcie:

```jsx
useEffect(() => {
  const interval = setInterval(() => {
    console.log('Dziala jednorazowy efekt');
  }, 1000);

  return () => clearInterval(interval); // Czyszczenie przy odmontowaniu
}, []);
```

To podejście jest przydatne przy inicjalizacji zapytań API, subskrypcji, timerów
i podobnych zadań.

</details>

<details>
<summary>46. Czym jest kontekst (Context)?</summary>

#### React

**Kontekst (Context)** w React to mechanizm przekazywania danych przez drzewo
komponentów bez potrzeby przekazywania ich przez propsy na każdym poziomie.

#### Jak działa kontekst:

1. **React.createContext()** służy do tworzenia kontekstu.

```jsx
const MyContext = React.createContext(defaultValue);
```

2. **Provider** to komponent, który udostępnia wartość kontekstu. Obejmuje część
   drzewa komponentów i przekazuje wartość w dół przez `value`.

```jsx
<MyContext.Provider value={}>
  <YourComponent />
</MyContext.Provider>
```

3. **Consumer** to komponent, który odbiera wartość kontekstu. Zwykle używa
   funkcji jako dziecka, które otrzymuje wartość kontekstu.

```jsx
<MyContext.Consumer>
{value => }
</MyContext.Consumer>
```

4. **useContext** to hook, który pozwala uzyskać dostęp do wartości kontekstu
   bez konieczności używania `Consumer`.

```jsx
const value = useContext(MyContext);
```

#### Kiedy używać:

- Gdy trzeba przekazywać dane między komponentami na różnych poziomach
  hierarchii, na przykład motyw, język albo użytkownika.

- Gdy nie chcesz przekazywać propsów przez kilka poziomów komponentów, bo może
  to niepotrzebnie komplikować kod.

#### Przyklad użycia:

```jsx
// Tworzenie kontekstu
const ThemeContext = React.createContext('light');

// Komponent udostępniający wartość kontekstu
function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedComponent />
    </ThemeContext.Provider>
  );
}

// Komponent pobierający wartość kontekstu
function ThemedComponent() {
  const theme = useContext(ThemeContext);
  return <div>The current theme is {theme}</div>;
}
```

#### Zalety:

- Wygoda w przekazywaniu wartości globalnych.

- Poprawia skalowalność aplikacji, zmniejszając liczbę przekazywanych propsów.

</details>

<details>
<summary>47. Jak w React działa mechanizm kontekstu (Context) do współdzielenia danych między komponentami?</summary>

#### React

Mechanizm **React Context** pozwala przekazywać dane między komponentami bez
konieczności przekazywania ich przez propsy na każdym poziomie. Jest to
przydatne dla danych globalnych, takich jak ustawienia motywu, uwierzytelnienie
użytkownika albo język.

#### Główne etapy pracy z kontekstem:

1. **Tworzenie kontekstu:** Do utworzenia kontekstu używa się
   `React.createContext()`. Zwraca on dwa komponenty:

- Provider to komponent, który przekazuje wartość kontekstu.

- Consumer to komponent, który odbiera wartość kontekstu.

```jsx
const MyContext = React.createContext();
```

2. **Udostępnianie kontekstu:** Używamy `Provider`, aby otoczyć komponenty,
   którym trzeba przekazać kontekst. W `Provider` wartość jest przekazywana
   przez prop `value`.

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

3. **Pobieranie kontekstu:** Używamy `Consumer` albo hooka `useContext`, aby
   uzyskać dostęp do wartości kontekstu.

- **Consumer:**

```jsx
const Child = () => (
  <MyContext.Consumer>{user => <div>{user}</div>}</MyContext.Consumer>
);
```

- **Hook `useContext` (zalecany w komponentach funkcyjnych):**

```jsx
const Child = () => {
  const user = useContext(MyContext);
  return <div>{user}</div>;
};
```

- **Zmiana kontekstu:** Aby zmienić wartość kontekstu, można użyć funkcji
  przekazanych przez `useState` albo innych metod zarządzania stanem.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <button onClick={() => setUser('Jane Doe')}>Change User</button>
      <Child />
    </MyContext.Provider>
  );
};
```

#### Kluczowe kwestie:

- Kontekst pozwala unikać `prop drilling`, czyli przekazywania propsów przez
  wiele komponentów.

- Jeśli wartość kontekstu się zmienia, wszystkie komponenty korzystające z tego
  kontekstu zostaną ponownie wyrenderowane.

- **useContext** jest wygodniejszym i nowocześniejszym sposobem pobierania
  wartości kontekstu niż `Consumer`.

Kontekst to potężne narzędzie, ale warto używać go głównie dla danych
globalnych. Do stanu lokalnego lepiej nadaje się zwykły state.

</details>

<details>
<summary>48. Czym jest prop drilling i jak go uniknąć?</summary>

#### React

**Prop Drilling** to przekazywanie propsów przez kilka poziomów zagnieżdżonych
komponentów, nawet jeśli są potrzebne tylko w głębiej położonym komponencie
potomnym. Utrudnia to utrzymanie kodu i obniża jego czytelność.

#### Przykład prop drilling:

```jsx
const Parent = () => {
  const user = { name: 'John' };
  return <Child user={user} />;
};

const Child = ({ user }) => {
  return <GrandChild user={user} />;
};

const GrandChild = ({ user }) => {
  return <p>Imie: {user.name}</p>;
};
```

Tutaj `user` jest przekazywany przez `Child`, chociaż ten komponent go nie
potrzebuje. To właśnie jest **prop drilling**.

#### Jak uniknąć prop drilling?

| **Metoda**                                           | **Opis**                                                            |
| ---------------------------------------------------- | ------------------------------------------------------------------- |
| **Context API**                                      | Pozwala przekazywać dane bezpośrednio do potrzebnych komponentów.   |
| **Zewnętrzne stany (Redux, Zustand, Jotai, Recoil)** | Służą do zarządzania globalnym stanem bez przekazywania propsów.    |
| **Komponenty z render props**                        | Pozwalają przekazywać funkcje zamiast propsów.                      |
| **Custom Hooks**                                     | Wynoszą logikę do osobnych funkcji dla dostępu do wspólnych danych. |

#### Przykład użycia Context API zamiast prop drilling

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
  return <p>Imie: {user.name}</p>;
};
```

Tutaj `user` jest dostępny bezpośrednio w `GrandChild`, bez zbędnego
przekazywania przez `Child`.

</details>

<details>
<summary>49. Czym jest Redux?</summary>

#### React

**Redux** to biblioteka do zarządzania stanem w aplikacjach JavaScript,
szczególnie popularna w React. Opiera się na koncepcji globalnego magazynu
(`store`), w którym przechowywany jest cały stan aplikacji, i pozwala zarządzać
nim przez przewidywalne zmiany.

#### Główne zasady Redux:

1. **Jedno źródło prawdy**: cały stan jest przechowywany w jednym globalnym
   `store`, co ułatwia śledzenie zmian.
2. **Stan jest tylko do odczytu**: nie można zmieniać stanu bezpośrednio, tylko
   przez `action`.
3. **Zmiany zachodzą przez czyste funkcje**: stan zmienia się za pomocą
   reducerów, które przyjmują bieżący stan i `action`, a następnie zwracają nowy
   stan.

#### Główne elementy Redux:

- **Store** to centralne miejsce przechowywania stanu.
- **Actions** to obiekty opisujące zamiar zmiany stanu.
- **Reducers** to czyste funkcje określające, jak zmienia się stan.
- **Dispatch** to metoda do wysyłania `action`.
- **Selectors** to funkcje do pobierania potrzebnych danych ze `store`.

Redux sprawdza się w dużych aplikacjach o złożonych przepływach danych, ale w
prostych projektach bywa często zbędny.

</details>

<details>
<summary>50. Jakie inne biblioteki do zarządzania stanem w React znasz poza Redux?</summary>

#### React

Poza Redux istnieje wiele bibliotek do zarządzania stanem w React:

1. **React Context API** to wbudowany mechanizm React do przekazywania stanu bez
   przerzucania propsów. Dobrze sprawdza się w małych i średnich aplikacjach.

2. **Zustand** jest prostszy i lżejszy od Redux, nie wymaga reducerów ani
   actions. Korzysta z bardziej bezpośredniego podejścia i działa przez hooki.

3. **Recoil** to biblioteka od Facebooka, która działa z atomami (`atoms`) i
   selektorami (`selectors`), pozwalając tworzyć elastyczny system stanu
   globalnego.

4. **Jotai** jest podobna do Recoil, ale prostsza. Używa atomów do
   przechowywania stanu i pozwala deklaratywnie nim zarządzać.

5. **MobX** oferuje reaktywne podejście do zarządzania stanem i działa przez
   obserwowalne wartości (`observables`). Jest wygodny przy pracy z obiektami i
   złożonymi strukturami.

6. **Effector** jest bardziej deklaratywny i często wydajniejszy od Redux.
   Opiera się na podejściu reaktywnym i ułatwia zarządzanie przepływami danych.

7. **XState** to biblioteka do pracy z maszynami stanów (`state machines`),
   dobrze nadająca się do złożonej logiki biznesowej.

Każda z nich ma własne zalety, a wybór zależy od złożoności projektu i wymagań
dotyczących wydajności.

</details>

<details>
<summary>51. Czym jest Redux Thunk?</summary>

#### React

**Redux Thunk** to middleware dla Redux, które pozwala wykonywać operacje
asynchroniczne, na przykład zapytania do API, przed wysłaniem zmian do `store`.

#### Jak działa:

Standardowo Redux pozwala przekazywać do `dispatch` tylko obiekty (`actions`).
Redux Thunk rozszerza tę możliwość, pozwalając przekazywać funkcje. Dzięki temu
można:

1. Wykonywać działania asynchroniczne przed zmianą stanu.

2. Uzyskiwać dostęp do `dispatch` i `getState` wewnątrz `thunk`.

#### Przyklad użycia:

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

Następnie wywołujemy ten `thunk`:

```jsx
dispatch(fetchData());
```

#### Kiedy używać:

- Do zapytań do API.
- Do opóźnień albo złożonej logiki przed aktualizacją store.
- Gdy trzeba wykonać kilka wywołań `dispatch` w ramach jednej akcji.

Jeśli aplikacja ma złożoną logikę asynchroniczną, warto rozważyć **Redux Saga**
albo **RTK Query** jako alternatywy.

</details>

<details>
<summary>52. Jak działa Redux Saga?</summary>

#### React

**Redux Saga** to middleware dla Redux, które używa generatorów (`function*`) do
zarządzania asynchronicznymi operacjami w aplikacji.

#### Jak działa:

1. **Nasłuchuje akcji** (`takeEvery`, `takeLatest`) i reaguje na nie.

2. **Wykonuje efekty uboczne**, takie jak zapytania do API, timery i podobne
   operacje.

3. **Wysyła nowe akcje** (`put`) do store.

#### Przyklad:

1. **Saga do pobierania danych z API:**

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

2. **Nasłuchiwanie akcji:**

```jsx
function* watchFetchData() {
  yield takeEvery('FETCH_REQUEST', fetchData);
}
```

3. **Uruchomienie sagi w `store`:**

```jsx
import createSagaMiddleware from 'redux-saga';
const sagaMiddleware = createSagaMiddleware();
const store = createStore(reducer, applyMiddleware(sagaMiddleware));
sagaMiddleware.run(watchFetchData);
```

#### Zalety Redux Saga:

- Zarządza złożoną logiką asynchroniczną.
- Ma wbudowaną obsługę anulowania (`takeLatest`).
- Oferuje rozbudowane operatory, takie jak `call`, `put`, `select` i `delay`.

**Redux Thunk** jest prostszy, ale przy bardziej złożonych scenariuszach
**Saga** bywa lepszym wyborem.

</details>

<details>
<summary>53. Czym jest React Fiber?</summary>

#### React

**React Fiber** to nowa architektura renderowania w React, wprowadzona od
wersji 16. Została zaprojektowana w celu poprawy wydajności, wsparcia
renderowania asynchronicznego oraz zapewnienia bardziej elastycznego zarządzania
aktualizacjami UI.

#### Kluczowe cechy React Fiber:

1. **Lepsza wydajność:** Fiber pozwala React przechowywać stan wykonywania
   renderowania, dzięki czemu można je przerywać i wznawiać w razie potrzeby.
   Jest to ważne w dużych aplikacjach, gdzie złożone obliczenia mogą spowalniać
   renderowanie.

2. **Renderowanie asynchroniczne:** React Fiber wspiera renderowanie
   asynchroniczne, co pozwala wykonywać render w częściach i poprawiać
   responsywność aplikacji, szczególnie w złożonych interfejsach. Dzięki temu
   renderowanie może odbywać się bez blokowania głównego wątku.

3. **Priorytety aktualizacji:** Fiber pozwala nadawać priorytet różnym typom
   aktualizacji, na przykład renderowanie animacji może mieć wyższy priorytet, a
   zmiany stanu niższy. Dzięki temu React skuteczniej zarządza złożonymi
   aktualizacjami.

4. **Dzielenie renderowania na podzadania:** W starszych wersjach React
   wszystkie zmiany były przetwarzane w jednym kroku. Fiber dzieli renderowanie
   na mniejsze podzadania, co pozwala React wykonywać pracę etapami i obsługiwać
   inne ważne operacje, na przykład zdarzenia, pomiędzy tymi etapami.

5. **Lepsze wsparcie animacji i przejść:** Dzięki renderowaniu asynchronicznemu
   React może skuteczniej zarządzać animacjami, co sprawia, że przejścia między
   stanami są płynniejsze i pozbawione opóźnień.

#### Jak działa React Fiber?

W starszych wersjach React cały proces renderowania był synchroniczny, od
początku do końca. Oznaczało to, że ciężkie obliczenia blokowały renderowanie
interfejsu. W React Fiber renderowanie zostało podzielone na małe zadania, które
mogą być wykonywane asynchronicznie. W razie potrzeby React może przerwać jedno
zadanie i dokończyć je później, nie blokując innych operacji, takich jak
aktualizacje UI albo obsługa zdarzeń.

#### Fiber pozwala React:

- Rozkładać renderowanie w czasie dla poprawy wydajności.

- Realizować asynchroniczne aktualizacje UI.

- Lepiej zarządzać priorytetami i obsługą ciężkich obliczeń, co jest szczególnie
  ważne w złożonych interfejsach i aplikacjach.

#### Zalety:

- Poprawa responsywności aplikacji.

- Możliwość wykonywania ciężkich operacji bez odczuwalnych opóźnień dla
  użytkownika.

- Lepsze zarządzanie animacjami i przejściami.

**React Fiber** to wewnętrzna zmiana, która odmieniła sposób działania React w
obszarze renderowania, poprawiając ogólną wydajność aplikacji.

</details>

<details>
<summary>54. Czym jest Lifting State Up w React?</summary>

#### React

**Lifting State Up** to podejście w React, w którym stan (`state`) jest
przenoszony do najbliższego wspólnego przodka komponentów, które muszą z niego
współkorzystać. Pozwala to stworzyć jedno źródło prawdy do zarządzania danymi
między komponentami.

#### Główna idea:

1. **Komponenty, które mają współdzielić dane, nie powinny każdy przechowywać
   własnego stanu.**

2. **Stan jest podnoszony do komponentu nadrzędnego, który przekazuje dane przez
   propsy komponentom podrzędnym.**

#### Jak to działa:

1. **Komponent nadrzędny przechowuje stan.**
2. **Przekazuje ten stan oraz funkcje do jego aktualizacji komponentom
   podrzędnym przez `props`.**

3. **Komponenty podrzędne informują rodzica o zmianach, używając przekazanych
   funkcji.**

#### Przyklad:

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

#### Zalety:

1. **Zapewnia jedno źródło prawdy dla stanu.**

2. **Ułatwia synchronizację danych między komponentami.**

3. **Sprawia, że komponenty stają się bardziej przewidywalne i łatwiejsze do
   ponownego wykorzystania.**

</details>

<details>
<summary>55. Czym są komponenty kontrolowane (Controlled Components)?</summary>

#### React

#### Komponenty kontrolowane (Controlled Components) w React

Komponenty kontrolowane to komponenty, w których **React kontroluje stan
formularza** przez `state`. Wartości pól formularza, takich jak `<input>`,
`<textarea>` czy `<select>`, są powiązane ze stanem komponentu, a zmiany są
obsługiwane przez zdarzenia.

#### Jak to działa:

1. **Komponent przechowuje wartości formularza w swoim `state`.**

2. **Zmiany wartości pól formularza są obsługiwane przez zdarzenie `onChange`.**

3. **Wartość formularza jest aktualizowana przy użyciu `setState`.**

#### Przyklad:

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [inputValue, setInputValue] = useState('');

  const handleChange = event => {
    setInputValue(event.target.value); // Aktualizujemy stan
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
          value={inputValue} // Wartosc jest kontrolowana przez state
          onChange={handleChange} // Obsługa zmian
        />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Główne zalety:

1. **Jedno źródło prawdy:** Wartość formularza jest zsynchronizowana ze stanem
   komponentu.

2. **Elastyczność:** Łatwo walidować i modyfikować dane formularza.

3. **Przejrzystość:** Stan formularza jest zrozumiały i przewidywalny.

#### Różnice względem komponentów niekontrolowanych:

- W komponentach kontrolowanych wartość formularza jest kontrolowana przez React
  za pomocą `state`.

- W komponentach niekontrolowanych wartość jest przechowywana w samym DOM, a
  dostęp do niej odbywa się przez `ref`.

#### Niekontrolowany przykład do porównania:

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

Komponenty kontrolowane zapewniają większą kontrolę i przewidywalność podczas
pracy z formularzami.

</details>

<details>
<summary>56. Czym są komponenty niekontrolowane (Uncontrolled Components)?</summary>

#### React

#### Komponenty niekontrolowane w React

Komponenty niekontrolowane (`Uncontrolled Components`) to komponenty, które
przechowują swój stan w DOM, a nie wewnątrz stanu komponentu React. Dostęp do
ich wartości uzyskuje się za pomocą **refów (`refs`)**.

#### Główne cechy:

1. **Stan jest zarządzany przez DOM:** wartości pól są przechowywane i
   aktualizowane bezpośrednio w DOM.

2. **Mniejsza integracja z React:** nie używają `useState` ani innych środków
   React do przechowywania stanu.

3. **Użycie refów:** do odczytania wartości pól formularza wykorzystuje się
   `ref`.

#### Przykład komponentu niekontrolowanego:

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const inputRef = useRef(null);

  const handleSubmit = event => {
    event.preventDefault();
    alert(`Wprowadzona wartosc: ${inputRef.current.value}`);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Imie:
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Wyslij</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### Kiedy używać komponentów niekontrolowanych:

- Gdy potrzebna jest minimalna integracja React z DOM.

- Gdy wartości formularza są obsługiwane przez biblioteki zewnętrzne.

- Gdy potrzebny jest prosty formularz bez złożonej logiki.

#### Zalety:

- Prosta implementacja dla prostych formularzy.

- Mniej kodu do zarządzania stanem.

#### Wady:

- Mniejsza kontrola nad wartościami.

- Trudniej zaimplementować walidację albo synchronizację danych.

- Podejście mniej zgodne z filozofią React.

</details>

<details>
<summary>57. Jak utworzyć formularz w React?</summary>

#### React

#### Tworzenie formularza w React

Formularze w React tworzy się za pomocą elementów `<form>` i odpowiednich
kontrolek, takich jak `<input>`, `<textarea>` czy `<select>`. Reaktywność
formularzy zapewniają komponenty kontrolowane albo niekontrolowane.

#### Formularz kontrolowany (Controlled Component)

Komponenty kontrolowane używają stanu (`state`) do śledzenia wartości pól
formularza.

#### Przyklad:

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

#### Cechy:

- Każde pole jest kontrolowane przez `state`.

- Łatwo synchronizować i przetwarzać dane formularza.

#### Formularz niekontrolowany (Uncontrolled Component)

Komponenty niekontrolowane używają refa (`ref`) do bezpośredniego dostępu do
elementów DOM.

#### Przyklad:

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

#### Cechy:

- Dostęp do wartości odbywa się przez `ref`.

- Nadaje się do prostych formularzy.

#### Najważniejsze kwestie:

1. **Formularz kontrolowany:**

- Używa `state`.

- Lepiej nadaje się do bardziej złożonych formularzy wymagających walidacji albo
  synchronizacji.

2. **Formularz niekontrolowany:**

- Używa `ref`.

- To prostsze podejście bez złożonej logiki zarządzania stanem.

Wybór podejścia zależy od złożoności formularza i potrzeb związanych z pracą z
jego polami.

</details>

<details>
<summary>58. Jak stosować walidację propsów w React?</summary>

#### React

Do sprawdzania propsów w React używa się **PropTypes**.

1. **Instalacja PropTypes, jeśli pakiet nie jest jeszcze zainstalowany**

```sh
npm install prop-types
```

2. **Użycie PropTypes w komponencie funkcyjnym:**

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

// Definicja PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Wartosci domyslne
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

3. **Użycie w komponencie klasowym:**

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

// Definicja PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Wartosci domyslne
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

#### Dostępne typy PropTypes:

- `PropTypes.string`
- `PropTypes.number`
- `PropTypes.bool`
- `PropTypes.array`
- `PropTypes.object`
- `PropTypes.func`
- `PropTypes.node` (JSX albo tekst)
- `PropTypes.element` (element React)
- `PropTypes.oneOf(['value1', 'value2'])` (lista dozwolonych wartości)
- `PropTypes.shape({ key: PropTypes.type })` (obiekt o określonej strukturze)

#### Wniosek:

PropTypes pomagają unikać błędów przez sprawdzanie typów propsów, ale w
TypeScript robi się to już na poziomie samego języka.

</details>

<details>
<summary>59. Czym React Router różni się od zwykłego routingu?</summary>

#### React

#### Różnica między React Router a zwykłym routingiem:

| Kryterium                     | React Router                                         | Zwykły routing (Server-Side Routing)         |
| ----------------------------- | ---------------------------------------------------- | -------------------------------------------- |
| **Typ routingu**              | Kliencki (SPA)                                       | Serwerowy (MPA)                              |
| **Przejście między stronami** | Bez przeładowania strony, JavaScript aktualizuje URL | Przeładowanie strony przy każdym przejściu   |
| **Szybkość**                  | Szybszy, bo nie wysyła ponownie żądania do serwera   | Wolniejszy przez nowe żądania HTTP           |
| **SEO**                       | Gorsze bez SSR, choć Next.js rozwiązuje problem      | Lepsze, bo treść jest ładowana z serwera     |
| **Obsługa danych**            | Dynamiczne renderowanie komponentów                  | Ładowanie HTML po stronie serwera            |
| **Konfiguracja**              | Wymaga React Router                                  | Korzysta ze standardowych możliwości serwera |

</details>

<details>
<summary>60. Jak przekazywać propsy w React Router?</summary>

#### React

Aby przekazywać propsy do komponentów przy użyciu **React Router**, można
skorzystać z kilku podejść:

1. **Użycie komponentu Route do przekazywania propsów:** Propsy można
   przekazywać przez komponent `Route` za pomocą `render` albo `children`.

**Przyklad:**

```jsx
import { Route } from 'react-router-dom';

<Route path="/profile" render={props => <Profile {...props} user="John" />} />;
```

Tutaj przekazujemy dodatkowe propsy do komponentu `Profile`.

2. **Użycie `useNavigate()` do przekazywania danych przez nawigację, za pomocą
   `state`:** Podczas przejścia na nową stronę można przekazać propsy przez
   `state`.

**Przyklad:**

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

**Odbieranie propsów w komponencie:**

```jsx
import { useLocation } from 'react-router-dom';

function Profile() {
  const location = useLocation();
  const user = location.state?.user;

  return <div>Welcome, {user}</div>;
}
```

3. **Użycie `useParams()` do dostępu do parametrów trasy:** Jeśli trzeba
   przekazać parametry przez URL, można użyć `useParams()`.

**Przyklad:**

```jsx
import { useParams } from 'react-router-dom';

function Profile() {
  const { id } = useParams();

  return <div>User ID: {id}</div>;
}
```

#### Wniosek:

- `render` albo `children` nadają się do bezpośredniego przekazywania propsów.

- `useNavigate()` i `state` pozwalają przekazywać dane między stronami.

- `useParams()` jest wygodny dla dynamicznych parametrów w URL.

</details>

<details>
<summary>61. Jakie są sposoby stylizacji komponentów w React?</summary>

#### React

#### Sposoby używania stylów w komponentach React:

1. **Style inline**: Style przekazuje się bezpośrednio jako obiekt przez atrybut
   `style`.

```jsx
function InlineStyle() {
  const style = {
    color: 'blue',
    fontSize: '20px',
  };

  return <h1 style={style}>Witaj, React!</h1>;
}
```

2. **Pliki CSS**: Używanie zwykłych plików CSS importowanych do komponentu.

```jsx
import './styles.css';

function CSSFile() {
  return <h1 className="heading">Witaj, React!</h1>;
}
```

```css
/* styles.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

3. **Moduły CSS**: Tworzą lokalnie izolowane style dla każdego komponentu.

```jsx
import styles from './styles.module.css';

function CSSModule() {
  return <h1 className={styles.heading}>Witaj, React!</h1>;
}
```

```css
/* styles.module.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

4. **Styled Components**: Użycie biblioteki `styled-components` do pisania
   stylów w JavaScript.

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
  return <Heading>Witaj, React!</Heading>;
}
```

5. **Emotion**: Alternatywna biblioteka do stylizacji, podobna do
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
  return <h1 css={style}>Witaj, React!</h1>;
}
```

6. **CSS-in-JS**: Tworzenie dynamicznych stylów w zwykłych plikach JavaScript.

```jsx
function CSSInJS({ isBlue }) {
  const style = {
    color: isBlue ? 'blue' : 'red',
    fontSize: '20px',
  };

  return <h1 style={style}>Witaj, React!</h1>;
}
```

7. **Tailwind CSS**: Framework klas narzędziowych do stylizacji komponentów.

```jsx
function TailwindExample() {
  return <h1 className="text-blue-500 text-2xl">Witaj, React!</h1>;
}
```

**Konfiguracja Tailwind CSS:** dodaj zależności i skonfiguruj projekt.

8. **Sass/SCSS**: Rozszerzony CSS z obsługą zmiennych, miksinów i zagnieżdżeń.

```bash
npm install sass
```

```jsx
import './styles.scss';

function SCSSExample() {
  return <h1 className="heading">Witaj, React!</h1>;
}
```

```scss
/* styles.scss */
.heading {
  color: blue;
  font-size: 20px;
}
```

#### Wybór sposobu zależy od:

- Skali projektu.

- Potrzeby izolacji stylów.

- Preferencji zespołu.

</details>

<details>
<summary>62. Na czym polega zaleta stylów modułowych (CSS Modules)?</summary>

#### React

**Zalety stylów modułowych (CSS Modules):**

1. **Lokalny scope**: style są stosowane tylko do danego komponentu, a nie
   globalnie. Zapobiega to konfliktom nazw klas i gwarantuje, że style nie
   wpływają na inne części aplikacji.

2. **Unikalne nazwy klas**: CSS Modules automatycznie generuje unikalne nazwy
   klas, co eliminuje ryzyko nadpisania stylów z innych komponentów.

3. **Łatwiejsze utrzymanie**: przy skalowaniu projektu pojawia się mniej
   problemów, ponieważ każdy komponent ma własne style, co sprawia, że kod jest
   bardziej uporządkowany i łatwiejszy do zrozumienia.

4. **Izolacja**: każdy komponent ma pełną izolację stylów, co ułatwia
   refaktoryzację i zmianę stylów bez wpływu na inne komponenty.

5. **Łatwiejsza integracja z JavaScript**: można używać dynamicznych stylów za
   pomocą JavaScript, zmieniając klasy zależnie od stanu komponentu.

Pozwala to utrzymać porządek w dużych aplikacjach i zmniejsza ryzyko błędów w
stylach.

</details>

<details>
<summary>63. Jakie podejścia znasz do optymalizacji wydajności aplikacji React?</summary>

#### React

#### Podejścia do optymalizacji wydajności aplikacji React:

1. **Memoizacja komponentów:**

- Używaj `React.memo` do memoizacji komponentów funkcyjnych, które nie zależą od
  częstych zmian propsów.
- Używaj `PureComponent` w komponentach klasowych.

2. **Memoizacja wartości i funkcji:**

- `useMemo` służy do obliczania wartości zależnych od określonych zależności.
- `useCallback` służy do memoizacji funkcji przekazywanych do komponentów
  podrzędnych.

3. **Optymalizacja renderowania list:**

Zawsze używaj unikalnego `key` dla elementów list. Unikaj ponownego renderowania
komponentów bez potrzeby.

4. **Dynamiczne ładowanie komponentów:**

- Używaj `React.lazy` do ładowania komponentów na żądanie.
- W połączeniu z `Suspense` pozwala to zoptymalizować ładowanie aplikacji.

5. **Kontrola rerenderów:**

- Używaj `shouldComponentUpdate` albo `React.memo`, aby ograniczać zbędne
  rendery.
- Używaj `React.Fragment` zamiast dodatkowych elementów opakowujących.

6. **Code splitting:**

- Wdrażaj `React.lazy` i dynamiczne importy, aby ładować kod modułów tylko
  wtedy, gdy jest potrzebny.

7. **Zarządzanie stanem:**

- Unikaj przechowywania globalnego stanu tam, gdzie nie jest to konieczne.
- Wynoś kosztowne operacje na stanie do kontekstu albo wyspecjalizowanych
  bibliotek, takich jak Redux czy Zustand.

8. **Wirtualizacja list:**

- Używaj bibliotek takich jak `react-window` albo `react-virtualized`, aby
  renderować tylko widoczne elementy listy.

9. **Optymalizacja obrazów:**

- Używaj leniwego ładowania (`lazy loading`) dla obrazów.
- Kompresuj i optymalizuj obrazy przed użyciem.

10. **Zmniejszanie liczby komponentów w DOM:**

- Unikaj nadmiernego zagnieżdżania komponentów.
- Usuwaj niepotrzebne elementy z DOM przy przejściach między stronami.

11. **Cache danych:**

- Używaj bibliotek cache'ujących, takich jak `SWR` czy `React Query`, do
  zarządzania danymi i ograniczania liczby zapytań do serwera.

12. **Używanie builda produkcyjnego:**

- Upewnij się, że aplikacja jest zbudowana w trybie produkcyjnym
  (`npm run build`).
- Używaj narzędzi takich jak `Webpack` do minimalizacji i optymalizacji kodu.

13. **Profilowanie aplikacji:**

- Używaj `React DevTools` do analizy wydajności.
- Wykrywaj wąskie gardła za pomocą zakładki `Profiler`.

14. **Optymalizacja CSS i stylów:**

- Używaj rozwiązań `CSS-in-JS`, takich jak `styled-components`, tylko tam, gdzie
  jest to potrzebne.
- Kompresuj style za pomocą `PostCSS` albo innych narzędzi.

Takie podejścia pomagają zmniejszyć opóźnienia, zwiększyć szybkość renderowania
i poprawić ogólną wydajność aplikacji.

</details>

<details>
<summary>64. Jaka jest różnica między memo a useMemo?</summary>

#### React

#### Różnica między memo a useMemo

| Kryterium            | memo                                                                    | useMemo                                             |
| -------------------- | ----------------------------------------------------------------------- | --------------------------------------------------- |
| **Co to jest?**      | Funkcja wyższego rzędu (HOC)                                            | Hook                                                |
| **Przeznaczenie**    | Zapobiega ponownemu renderowi komponentu, jeśli propsy się nie zmieniły | Zapamiętuje wynik obliczenia między renderami       |
| **Gdzie się używa?** | Opakowuje komponent                                                     | Wewnątrz komponentu                                 |
| **Przykład użycia**  | `export default memo(MyComponent);`                                     | `const value = useMemo(() => compute(), [deps]);`   |
| **Co cache'uje?**    | Cały komponent                                                          | Wynik funkcji                                       |
| **Kiedy stosować?**  | Gdy komponent renderuje się z tymi samymi propsami bez zmian            | Gdy obliczenie jest kosztowne i zależy od zmiennych |

#### Kiedy używać?

- `memo` stosuj wtedy, gdy komponent otrzymuje te same propsy i jego rerender
  nie jest potrzebny.

- `useMemo` stosuj wtedy, gdy chcesz zachować wynik obliczenia, aby nie liczyć
  go ponownie za każdym razem.

</details>

<details>
<summary>65. Dlaczego do setState() trzeba przekazywać funkcję?</summary>

#### React

Przekazanie funkcji do `setState()` jest potrzebne wtedy, gdy nowy stan zależy
od poprzedniego. Gwarantuje to poprawną aktualizację, ponieważ `setState()`
działa asynchronicznie i może grupować wywołania.

#### Przykład problemu:

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

Tutaj `count + 1` jest obliczane dwa razy z tą samą starą wartością `count`,
dlatego przycisk zwiększy wartość tylko o 1, a nie o 2.

#### Poprawne podejście:

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

Tutaj `setCount()` otrzymuje aktualną wartość `prevCount`, dlatego inkrementacja
działa poprawnie i zwiększa wartość o 2.

</details>

<details>
<summary>66. Jak refy (refs) w React są używane do interakcji z elementami DOM?</summary>

#### React

Refy (`refs`) w React służą do bezpośredniego uzyskiwania dostępu do elementów
DOM albo komponentów, z pominięciem standardowego mechanizmu propsów i stanu.

1. **Tworzenie refów:** Używasz `React.createRef()` do utworzenia refa.

```jsx
const myRef = React.createRef();
```

2. **Przypisanie refa do elementu:** Ref jest przekazywany do elementu DOM przez
   atrybut `ref`.

```jsx
<input ref={myRef} />
```

3. **Interakcja z DOM:** Ref daje dostęp do elementu DOM przez `.current`. Na
   przykład, aby ustawić fokus:

```jsx
myRef.current.focus();
```

4. **Ograniczenia:** Refy nie powinny być używane do zarządzania stanem. Służą
   tylko do interakcji z DOM wtedy, gdy jest to potrzebne, na przykład do
   ustawiania fokusu, zaznaczania tekstu albo obsługi animacji.

5. **Komponenty funkcyjne:** W React 16.8 i nowszych w komponentach funkcyjnych
   używa się `useRef`.

```jsx
const inputRef = useRef();
inputRef.current.focus();
```

</details>

<details>
<summary>67. Jak używać InnerHtml w React?</summary>

#### React

- W React do wstawiania treści HTML do DOM używa się atrybutu
  `dangerouslySetInnerHTML`. Pozwala on osadzić HTML bezpośrednio w komponencie,
  ale takie podejście może być niebezpieczne, stąd nazwa "dangerously", ponieważ
  umożliwia wstawienie surowego HTML, co może prowadzić do ataków XSS, jeśli
  dane nie zostały oczyszczone.

#### Przykład użycia `dangerouslySetInnerHTML`:

```jsx
const MyComponent = () => {
  const htmlContent = '<p>To jest <strong>HTML</strong> content.</p>';

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
};
```

#### Wyjaśnienie:

- `dangerouslySetInnerHTML` przyjmuje obiekt, w którym klucz `__html` zawiera
  ciąg kodu HTML.

- Pozwala to osadzać HTML wewnątrz komponentu, ale nie jest bezpieczne, jeśli
  treść pochodzi z niezaufanych źródeł.

#### Kiedy używać:

- Gdy masz pewność co do bezpieczeństwa danych, na przykład pochodzących z
  własnych serwerów.

- Gdy trzeba osadzić dynamiczną treść HTML, taką jak strony albo artykuły.

#### Ostrzeżenia:

- Bezpieczeństwo: nigdy nie używaj `dangerouslySetInnerHTML` do wstawiania
  danych otrzymanych od użytkownika albo z zewnętrznych źródeł bez wcześniejszej
  sanitizacji złośliwych skryptów.

- Do oczyszczania treści używaj bibliotek takich jak DOMPurify, aby uniknąć
  ataków XSS.

**Przykład oczyszczania danych przed wstawieniem:**

```jsx
import DOMPurify from 'dompurify';

const MyComponent = () => {
  const dirtyHtml = "<img src=x onerror=alert('XSS')>";
  const cleanHtml = DOMPurify.sanitize(dirtyHtml);

  return <div dangerouslySetInnerHTML={{ __html: cleanHtml }} />;
};
```

Dlatego `dangerouslySetInnerHTML` należy stosować ostrożnie i tylko wtedy, gdy
masz pewność co do bezpieczeństwa treści.

</details>

<details>
<summary>68. Czym jest ReactDOMServer?</summary>

#### React

**`ReactDOMServer`** to biblioteka wchodząca w skład React, używana do
renderowania komponentów React po stronie serwera, czyli do server-side
rendering (SSR). Pozwala generować kod HTML na serwerze i przekazywać go do
klienta, co może poprawić wydajność oraz SEO.

#### Główne metody:

1. **`ReactDOMServer.renderToString()`:** Renderuje elementy React do ciągu
   HTML. To podstawowa metoda generowania statycznego HTML dla początkowego
   ładowania strony.

```jsx
import ReactDOMServer from 'react-dom/server';
const html = ReactDOMServer.renderToString(<App />);
```

2. **`ReactDOMServer.renderToStaticMarkup()`:** Renderuje HTML bez dodatkowych
   atrybutów związanych z React, takich jak `data-reactroot`. Nadaje się do
   tworzenia całkowicie statycznych stron.

```jsx
const html = ReactDOMServer.renderToStaticMarkup(<App />);
```

3. **`ReactDOMServer.hydrate()`:** Używa się po stronie klienta do "hydracji"
   HTML wyrenderowanego na serwerze, czyli do podłączenia interaktywności do już
   istniejącego HTML.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

#### Zastosowanie:

- **SSR (Server-Side Rendering):** To podejście, w którym komponenty React są
  renderowane na serwerze, a nie w przeglądarce, co pozwala wysłać klientowi w
  pełni zbudowaną stronę HTML.

- **SEO:** Ponieważ serwer od razu wysyła treść HTML, wyszukiwarki mogą
  indeksować strony bez konieczności wykonywania JavaScript.

Dzięki temu `ReactDOMServer` pozwala tworzyć strony renderowane wstępnie, co
poprawia szybkość ładowania i może być korzystne dla SEO.

</details>

<details>
<summary>69. Do czego służy pakiet react-dom?</summary>

#### React

Pakiet `react-dom` służy do interakcji React z rzeczywistym DOM w aplikacjach
webowych. Główne funkcje:

1. **`ReactDOM.render()`:** Służy do renderowania komponentu do rzeczywistego
   DOM. To podstawowa metoda łącząca React z elementami HTML.

```jsx
ReactDOM.render(<App />, document.getElementById('root'));
```

2. **`ReactDOM.hydrate()`:** Służy do hydracji HTML wygenerowanego po stronie
   serwera, na przykład przy SSR. Dzięki temu React może przejąć kontrolę nad
   istniejącym HTML.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

3. **`ReactDOM.createPortal()`:** Pozwala renderować elementy podrzędne w innym
   miejscu DOM, poza zwykłą hierarchią komponentów. Często używa się tego do
   okien modalnych, tooltipów i elementów wyskakujących.

```jsx
ReactDOM.createPortal(<Modal />, document.getElementById('modal-root'));
```

4. **`ReactDOM.unmountComponentAtNode()`:** Usuwa komponent React z DOM.

```jsx
ReactDOM.unmountComponentAtNode(document.getElementById('root'));
```

5. **`ReactDOM.findDOMNode()`:** Daje dostęp do rzeczywistego elementu DOM
   komponentu. Jest używana rzadko, bo istnieją nowocześniejsze podejścia z
   użyciem refów.

- Ten pakiet jest niezbędny do pracy z rzeczywistym DOM, ale w większości
  przypadków po początkowej konfiguracji nie trzeba ręcznie wywoływać tych
  metod, ponieważ są one używane automatycznie przez narzędzia do kompilacji i
  renderowania.

</details>

<details>
<summary>70. Jak używać React.lazy i React.Suspense do uruchamiania kodu aplikacji?</summary>

#### React

`React.lazy` i `React.Suspense` służą do **dynamicznego ładowania komponentów**
w React, co pozwala realizować **podział kodu** (`code splitting`). Oznacza to,
że części kodu są ładowane tylko wtedy, gdy są potrzebne, co poprawia wydajność
aplikacji.

#### Jak to działa:

1. **`React.lazy()`** pozwala ładować komponent z opóźnieniem.

2. **`React.Suspense`** służy do opakowania części kodu, która nie została
   jeszcze załadowana, i pozwala wyświetlać zawartość zastępczą, na przykład
   loader, dopóki komponenty się nie załadują.

#### Przyklad:

1. **Dynamiczne ładowanie komponentu:** Najpierw utwórz komponent, który będzie
   ładowany dynamicznie.

```jsx
// Komponent ładowany dynamicznie
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Opakowanie za pomocą `React.Suspense`:** Następnie użyj `React.Suspense`,
   aby pokazać loader podczas ładowania komponentu.

```jsx
function App() {
  return (
    <div>
      <h1>Moja aplikacja</h1>

      {/* Opakowanie dla dynamicznie ładowanych komponentów */}
      <React.Suspense fallback={<div>Ladowanie...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Opis:**

- `React.lazy()` przyjmuje funkcję, która dynamicznie importuje moduł.

- `React.Suspense` opakuje komponent używający `React.lazy()` i pokaże zawartość
  zastępczą, w tym przypadku tekst "Ladowanie...", dopóki komponent się nie
  załaduje.

#### Zalety:

- Poprawia wydajność, ładując komponenty tylko wtedy, gdy są potrzebne.

- Zmniejsza rozmiar początkowego ładowania, ponieważ części aplikacji są
  ładowane na żądanie.

To podejście jest szczególnie przydatne w dużych aplikacjach, gdzie można
podzielić kod na części, aby skrócić czas ładowania strony.

</details>

<details>
<summary>71. Jakie są najlepsze praktyki bezpieczeństwa w React?</summary>

#### React

#### Najlepsze praktyki bezpieczeństwa w React:

1. **Zapobieganie XSS (Cross-Site Scripting):**

- Zawsze oczyszczaj dane pochodzące od użytkownika przed ich wyświetleniem w
  komponencie.
- Używaj JSX. React automatycznie escapuje dane wejściowe, ale nadal warto
  unikać `dangerouslySetInnerHTML`.
- Jeśli musisz użyć `dangerouslySetInnerHTML`, upewnij się, że treść została
  bezpiecznie oczyszczona.

2. **Unikaj wstrzykiwania kodu:**

- Nigdy nie przekazuj niesprawdzonych danych do `eval()`, `setTimeout()`,
  `setInterval()` ani innych funkcji wykonujących kod.
- Do dynamicznego importu używaj mechanizmów z wbudowaną kontrolą, na przykład
  `React.lazy()`.

3. **Bezpieczny dostęp do API:**

- Używaj HTTPS do ochrony danych przesyłanych przez sieć.
- Stosuj uwierzytelnianie, autoryzację oraz bezpieczne cookies, takie jak
  `HttpOnly` i `Secure`.

4. **Ochrona przed CSRF (Cross-Site Request Forgery):**

- Używaj tokenów CSRF do weryfikowania wszystkich żądań zmieniających dane na
  serwerze.
- Używaj flagi `SameSite` dla cookies, aby ograniczyć ich użycie do tego samego
  domenowego kontekstu.

5. **Kontrola dostępu:**

- Sprawdzaj, czy użytkownik ma uprawnienia do wykonania żądanej akcji przed
  wysłaniem żądania na serwer.
- Nie ufaj walidacji po stronie klienta. Ostateczne sprawdzenia muszą odbywać
  się po stronie serwera.

6. **Ochrona pól wejściowych:**

- Dla formularzy i pól przyjmujących dane od użytkownika ustawiaj ograniczenia
  dotyczące dozwolonych wartości.

7. **Aktualizowanie zależności:**

- Regularnie sprawdzaj i aktualizuj zależności, aby wykrywać potencjalne
  podatności. Używaj do tego `npm audit` albo innych narzędzi.

8. **Zarządzanie sekretami:**

- Nie przechowuj sekretów, takich jak klucze API czy hasła, w kodzie klienta.
  Powinny znajdować się na serwerze albo w bezpiecznych zmiennych
  środowiskowych.

9. **Stosowanie Content Security Policy (CSP):**

- Używaj CSP, aby zapobiegać wykonywaniu niepożądanych skryptów na stronie.

10. **Ochrona przed clickjackingiem:**

- Używaj nagłówków `X-Frame-Options` albo `Content-Security-Policy`, aby
  uniemożliwić osadzanie strony w `<iframe>` na innych witrynach.

Stosowanie tych praktyk pomaga ograniczyć ryzyko bezpieczeństwa w aplikacjach
React.

</details>

<details>
<summary>72. Jak obsługiwać błędy w React za pomocą Error Boundary?</summary>

#### React

**Error Boundaries** w React pozwalają przechwytywać błędy w komponentach
podczas renderowania, w metodach cyklu życia i w konstruktorach, a następnie
obsługiwać je bez całkowitego zatrzymania aplikacji.

#### Najważniejsze kwestie:

- Error Boundary to komponent, który opakowuje inne komponenty i może
  przechwytywać błędy pojawiające się w ich kodzie.

- **Error Boundaries** przechwytują tylko błędy występujące w ich potomkach. Nie
  przechwytują błędów wewnątrz samego Error Boundary.

#### Jak zaimplementować Error Boundary:

1. **Tworzenie Error Boundary:** Aby utworzyć Error Boundary, trzeba
   zaimplementować dwie metody:

- `static getDerivedStateFromError(error)` aktualizuje stan po wystąpieniu
  błędu.

- `componentDidCatch(error, info)` pozwala rejestrować błędy, na przykład
  wysyłać je na serwer.

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }

  static getDerivedStateFromError(error) {
    // Aktualizujemy stan, aby pokazać zapasowy UI
    return { hasError: true, error };
  }

  componentDidCatch(error, info) {
    // Logika rejestrowania błędów, na przykład na serwer
    console.error('Error caught:', error, info);
  }

  render() {
    if (this.state.hasError) {
      // Pokazujemy zapasowy UI, jeśli wystąpił błąd
      return <h1>Coś poszło nie tak.</h1>;
    }

    return this.props.children;
  }
}
```

2. **Użycie Error Boundary:** Owijamy komponenty, które mogą powodować błędy, w
   `ErrorBoundary`.

```jsx
const App = () => {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
};
```

3. **Zapasowy interfejs:** Gdy wystąpi błąd, w ErrorBoundary można pokazać
   zapasowy interfejs, na przykład komunikat o błędzie, przycisk ponowienia
   próby albo działania naprawcze.

#### Ważne kwestie:

- Error Boundary nie przechwytuje błędów w handlerach zdarzeń, na przykład
  `onClick`, w kodzie asynchronicznym, timerach czy zapytaniach sieciowych. W
  takich przypadkach używaj `try-catch` albo innych mechanizmów.

- Jeśli błąd wystąpi wewnątrz samego Error Boundary, nie zostanie przez niego
  przechwycony.

**Error Boundaries** są przydatne dla stabilności aplikacji, ponieważ pozwalają
przechwytywać i obsługiwać błędy bez zatrzymywania całej aplikacji.

</details>

<details>
<summary>73. Czym jest odwrócenie dziedziczenia (Inheritance Inversion)?</summary>

#### React

- **Odwrócenie dziedziczenia (Inheritance Inversion)** to sytuacja, w której
  klasa, która powinna być bazowa, faktycznie zależy od swoich potomków albo
  traci kontrolę nad logiką, która powinna należeć do hierarchii dziedziczenia.

#### Problemy związane z odwróceniem dziedziczenia

- Naruszenie zasady Liskov Substitution Principle, czyli LSP.

- Trudno zmieniać albo rozszerzać klasę bazową bez wpływu na wszystkich jej
  potomków.

- Wzrost złożoności przez wzajemne zależności.

#### Przykład złej praktyki

```js
class Parent {
  method() {
    throw new Error('Metoda musi być zaimplementowana w klasie potomnej');
  }
}

class Child extends Parent {
  method() {
    return 'Implementacja w klasie potomnej';
  }
}
```

Tutaj klasa bazowa nie ma własnej logiki i zmusza potomków do implementowania
zachowania, co jest oznaką odwrócenia dziedziczenia.

#### Alternatywa: kompozycja zamiast dziedziczenia

```js
class Behavior {
  method() {
    return 'Implementacja bez odwrócenia';
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

To podejście usuwa zależność klasy nadrzędnej od potomków, dzięki czemu kod
staje się bardziej elastyczny.

</details>

<details>
<summary>74. Czym jest polling i jak zaimplementować go w React?</summary>

#### React

**Polling** to okresowe wysyłanie żądań do serwera w celu pobrania
zaktualizowanych danych. Jest to przydatne, gdy serwer nie obsługuje WebSockets
ani Server-Sent Events, a klient musi otrzymywać nowe informacje bez
przeładowywania strony.

#### Implementacja pollingu w React

Polling można zaimplementować przez `setInterval`, `setTimeout` albo z użyciem
hooków React, takich jak `useEffect`.

1. **Użycie `setInterval`**

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

    fetchData(); // Wykonaj od razu po załadowaniu

    const interval = setInterval(fetchData, 5000); // Polling co 5 sekund

    return () => clearInterval(interval); // Czyszczenie przy odmontowaniu
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Ladowanie...'}</div>;
};
```

- `fetchData()` pobiera dane z serwera.
- `setInterval` uruchamia polling co 5 sekund.
- `clearInterval` zatrzymuje polling przy odmontowaniu.

2. **Użycie `setTimeout` dla dynamicznego interwału**

Jeśli serwer ma ograniczenia dotyczące liczby żądań, lepiej użyć `setTimeout`,
aby uniknąć nakładania się żądań.

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
        console.error('Blad zapytania', error);
      } finally {
        if (isMounted) setTimeout(fetchData, 5000);
      }
    };

    fetchData();

    return () => {
      isMounted = false; // Zapobiega aktualizacji stanu po odmontowaniu
    };
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Ladowanie...'}</div>;
};
```

Tutaj `setTimeout` jest wywoływany dopiero po zakończeniu poprzedniego żądania,
co pozwala uniknąć ich nakładania się.

#### Wniosek

- `setInterval` nadaje się do stałego pollingu, ale może powodować nakładanie
  się żądań.
- `setTimeout` daje większą kontrolę i lepiej sprawdza się przy adaptacyjnym
  pollingu.
- Przy większym obciążeniu warto rozważyć WebSockets albo Server-Sent Events.

</details>

<details>
<summary>75. Jak zaimplementować dwukierunkowe wiązanie danych w React?</summary>

#### React

W React dwukierunkowe wiązanie danych realizuje się przez **komponenty
kontrolowane** (`controlled components`), gdzie stan komponentu (`state`) jest
zsynchronizowany z polem wejściowym (`input`).

#### Przykład implementacji

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
      <p>Wprowadzona wartosc: {value}</p>
    </div>
  );
};

export default TwoWayBinding;
```

#### Jak to działa?

1. **`value`** przechowuje aktualny stan wprowadzonej wartości.

2. **`onChange`** aktualizuje stan przy zmianie `input`.

3. **Zaktualizowane `value`** jest wyświetlane w interfejsie, zapewniając
   dwukierunkowe powiązanie.

To podejście pozwala kontrolować wprowadzone dane, wykonywać walidację i
przetwarzanie przed aktualizacją stanu.

</details>

<details>
<summary>76. Czym jest odwrotny przepływ danych (Reverse Data Flow) w React?</summary>

#### React

Odwrotny przepływ danych (`Reverse Data Flow`) w React oznacza przekazywanie
zmian stanu z komponentu podrzędnego do komponentu nadrzędnego. Jest to
przeciwieństwo zwykłego przepływu danych, w którym komponent nadrzędny
przekazuje propsy komponentowi podrzędnemu.

#### W React odwrotny przepływ danych zwykle realizuje się przez:

1. **Funkcje callback:**

- Komponent podrzędny wywołuje callback przekazany przez propsy, aby
  poinformować komponent nadrzędny o zmianach swojego stanu albo wykonać
  określone działania.

- Na przykład przy aktualizacji wartości w komponencie podrzędnym można wywołać
  funkcję z komponentu nadrzędnego, która zaktualizuje stan.

2. **Przykład:**

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

- W tym przykładzie komponent podrzędny przekazuje wartość do nadrzędnego przez
  funkcję `onValueChange`, co realizuje odwrotny przepływ danych.

</details>

<details>
<summary>77. Czym jest mutacja stanu i jak jej zapobiegać?</summary>

#### React

Mutacja stanu to bezpośrednia zmiana obiektu albo tablicy przechowującej stan
bez utworzenia kopii. W React prowadzi to do nieprzewidywalnych rezultatów,
ponieważ React nie wie, że stan się zmienił, i nie wyrenderuje komponentu
ponownie.

#### Aby zapobiegać mutacji stanu, należy:

1. **Tworzyć kopie danych** przed ich zmianą, na przykład dla tablic i obiektów:

- Dla tablic: `setItems([...items, newItem])`
- Dla obiektów: `setUser({ ...user, name: 'John' })`

2. **Używać metod, które nie mutują danych**, takich jak `map()`, `filter()`,
   `reduce()` dla tablic albo `Object.assign()` dla obiektów.

Pozwala to React poprawnie śledzić zmiany i ponownie renderować komponenty.

 </details>

<details>
<summary>78. Czym jest tryb ścisły (Strict Mode) w React i jakie ma zalety?</summary>

#### React

**Strict Mode** to specjalne narzędzie React do wykrywania potencjalnych
problemów w kodzie. Nie wpływa na działanie w produkcji, ale pomaga poprawić
jakość kodu podczas developmentu.

Aktywuje się go przez opakowanie komponentów w `<React.StrictMode>`:

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

#### Zalety Strict Mode

| **Funkcja**                                      | **Opis**                                                                                                                 |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------ |
| **Wykrywanie niebezpiecznych metod cyklu życia** | Ostrzega o przestarzałych metodach, takich jak `componentWillMount`, `componentWillReceiveProps`, `componentWillUpdate`. |
| **Podwójne wywołanie funkcji w developmentcie**  | Pomaga wykrywać efekty uboczne w `useEffect` i innych hookach.                                                           |
| **Ostrzeganie o przestarzałym API**              | Wskazuje stare konteksty i niebezpieczne wzorce.                                                                         |
| **Wykrywanie nieprzewidywalnego zachowania**     | Na przykład wywołuje `useEffect` dwa razy, aby sprawdzić poprawność czyszczenia efektów.                                 |

#### Czy warto go używać?

Tak, jeśli chcesz unikać problemów już na etapie developmentu. Może być trochę
irytujący przez podwójny render, ale pomaga znajdować ukryte błędy w kodzie.

</details>

<details>
<summary>79. Jakie są zalecane sposoby sprawdzania typów statycznych?</summary>

#### React

1. **TypeScript:** Najpopularniejsze i najbardziej kompletne podejście do
   statycznego typowania w JavaScript i React. TypeScript dodaje ścisłe typy do
   kodu i pozwala sprawdzać je na etapie kompilacji.

2. **PropTypes:** Wbudowany mechanizm do sprawdzania typów propsów w
   komponentach React. Służy do walidacji typów w czasie działania. Nie daje
   statycznego typowania podczas kompilacji, ale pozwala sprawdzać propsy przy
   uruchomionej aplikacji.

```jsx
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};
```

3. **Flow:** Inny mechanizm statycznego typowania w JavaScript. Jest mniej
   popularny niż TypeScript, ale również pozwala dodawać typy i sprawdzać je na
   etapie kompilacji.

4. **ESLint z pluginami do typów:** Można używać ESLint z pluginami do
   sprawdzania typów, na przykład `eslint-plugin-flowtype` albo
   `eslint-plugin-typescript`, ale nie daje to takiej głębokości typowania jak
   TypeScript.

Polecam używać **TypeScript**, ponieważ dobrze integruje się z React i innymi
narzędziami oraz zapewnia pełne statyczne typowanie na etapie kompilacji.

</details>

<details>
<summary>80. Jak zaimplementować animację w React?</summary>

#### React

1. **Animacje CSS:** Najprostszy sposób to użycie standardowych animacji CSS
   albo przejść.

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

2. **React Transition Group:** Do bardziej złożonych przejść animacyjnych między
   komponentami. Ten pakiet pozwala sterować animacją podczas dodawania albo
   usuwania komponentów.

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

3. **Framer Motion:** To potężna biblioteka do animacji, która pozwala
   realizować złożone animacje w React.

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

4. **React Spring:** Do animacji opartych na fizyce, które pozwalają tworzyć
   animacje z bardziej realistycznym ruchem.

```jsx
import { useSpring, animated } from 'react-spring';

const props = useSpring({ opacity: 1, from: { opacity: 0 } });

<animated.div style={props}>Hello</animated.div>;
```

5. **Style inline i JavaScript:** Można używać `setState` i zmieniać style na
   podstawie stanu komponentu.

```jsx
const [opacity, setOpacity] = useState(0);

useEffect(() => {
  setOpacity(1);
}, []);

return <div style={{ opacity }}>Hello</div>;
```

W przypadku bardziej złożonych efektów animacyjnych warto używać **Framer
Motion** albo **React Spring**, ponieważ te biblioteki dają więcej możliwości i
ułatwiają sterowanie złożonymi animacjami.

</details>

<details>
<summary>81. Jakie są najpopularniejsze pakiety do animacji w React?</summary>

#### React

#### Popularne pakiety do animacji w React:

1. **Framer Motion** to jeden z najpopularniejszych pakietów do animacji w
   React. Jest prosty w użyciu, obsługuje animacje i przejścia, działa z
   drag-and-drop, a także oferuje rozbudowane API do tworzenia złożonych
   animacji.

2. **React Spring** to biblioteka do tworzenia animacji opartych na fizyce.
   Korzysta z właściwości takich jak sprężystość i tarcie. Dobrze sprawdza się
   przy złożonych animacjach i interakcjach.

3. **GSAP (GreenSock Animation Platform)** to potężna biblioteka do animacji,
   która działa nie tylko z React, ale też z innymi frameworkami. Słynie z
   szybkości i możliwości tworzenia bardzo złożonych animacji.

4. **React Transition Group** to podstawowa biblioteka do animowania przejść w
   React. Pozwala tworzyć animacje wejścia, wyjścia i zmian stanu komponentów,
   dając dużą elastyczność w definiowaniu przejść.

5. **Lottie for React** pozwala łatwo osadzać animacje stworzone w After Effects
   w formacie JSON. Nadaje się do złożonych animacji, takich jak ikony albo
   elementy interaktywne.

</details>

<details>
<summary>82. React DevTools: jak używać do debugowania?</summary>

#### React

1. **Instalacja React DevTools**

- Jeśli używasz `Chrome` albo `Firefox`, po prostu zainstaluj rozszerzenie
  `React Developer Tools`:
  - Chrome Web Store
  - Firefox Add-ons

- Jeśli debugujesz `Electron`, `React Native` albo inne niestandardowe
  środowisko, zainstaluj:

```sh
npm install -g react-devtools
react-devtools
```

2. **Główne zakładki i ich zastosowanie**

- `Components`: podgląd struktury komponentów, stanu i propsów.
- `Profiler`: analiza wydajności i wykrywanie zbędnych renderów.

3. **Debugowanie propsów i stanu**

- Otwórz zakładkę `Components`.
- Wybierz komponent i zobaczysz jego `props`, `state` oraz `context`.
- Możesz edytować `state` i `props` bezpośrednio w `DevTools`, aby testować
  zmianę zachowania.

4. **Wykrywanie zbędnych renderów**

- W zakładce `Profiler` kliknij `Record`, wykonaj interakcję, a potem kliknij
  `Stop`.
- Sprawdź oznaczenia kolorystyczne:
  - **Czerwony** oznacza kosztowny render.
  - **Żółty** oznacza średni koszt.
  - **Niebieski** oznacza lekki render.
- Optymalizuj komponenty za pomocą `React.memo()`, `useMemo()` i
  `useCallback()`.

5. **Narzędzia do debugowania Context API**

- Jeśli używasz React Context, możesz sprawdzić jego wartości w DevTools.
- Wybierz komponent korzystający z `useContext()` i znajdź zakładkę `Context`.

6. **Debugowanie renderu w Strict Mode**

- Jeśli `React DevTools` pokazuje, że komponent renderuje się dwa razy, sprawdź
  `StrictMode` w `index.js`:

```jsx
<React.StrictMode>
  <App />
</React.StrictMode>
```

- Nie powoduje błędów sam w sobie, a jedynie pomaga wykryć potencjalne problemy.

7. **Inspekcja hooków**

- DevTools pozwala zobaczyć stan hooków, takich jak `useState`, `useEffect` i
  `useReducer`.
- W zakładce `Components` wybierz komponent, aby zobaczyć stan `useState`.

#### Wniosek:

**React DevTools** to potężne narzędzie do debugowania stanu, propsów,
wydajności i kontekstu. Używaj `Profiler` do optymalizacji oraz `Components` do
śledzenia zmian w stanie i propsach.

</details>

<details>
<summary>83. Jakie są najpopularniejsze lintery do React?</summary>

#### React

#### Najpopularniejsze lintery do React:

1. **ESLint** to najpopularniejszy linter dla `JavaScript`, który wspiera
   `React` przez plugin `eslint-plugin-react`. Sprawdza styl kodu, wykrywa błędy
   i może działać razem z narzędziami takimi jak `Prettier`.

2. **Prettier** to narzędzie do automatycznego formatowania kodu, często używane
   razem z `ESLint`, aby zapewnić spójny styl kodu.

3. **TSLint** to linter dla `TypeScript`, który można było używać również z
   `React`, chociaż obecnie jest wypierany przez `ESLint` ze względu na większą
   elastyczność i lepsze wsparcie.

Te narzędzia pomagają utrzymywać wysoką jakość kodu i zapobiegać błędom w dużych
projektach.

</details>

<details>
<summary>84. Czym jest Next.js?</summary>

#### React

**Next.js** to framework oparty na React, który dostarcza gotowe rozwiązania do
server-side rendering (SSR), static site generation (SSG), tras API, routingu,
optymalizacji wydajności i SEO.

#### Główne możliwości:

- **Renderowanie hybrydowe:** wsparcie dla SSR, SSG i ISR.
- **Automatyczny routing:** pliki w `pages/` automatycznie stają się trasami.
- **Trasy API:** tworzenie endpointów serwerowych w plikach `pages/api/*`.
- **Optymalizacja wydajności:** automatyczny code splitting i zmniejszanie
  bundla.
- **Wsparcie App Router:** nowe podejście oparte na React Server Components i
  katalogu `app/` zamiast `pages/`.
- **Wbudowane wsparcie dla Tailwind, TypeScript, ESLint i innych technologii**.

Jest używany do tworzenia wydajnych aplikacji webowych, blogów, rozwiązań
e-commerce i złożonych interfejsów.

</details>

<details>
<summary>85. Jakie są główne różnice między Next.js a React?</summary>

#### React

#### Główne różnice między Next.js a React:

| **Kryterium**                        | **React**                                           | **Next.js**                                                                        |
| ------------------------------------ | --------------------------------------------------- | ---------------------------------------------------------------------------------- |
| **Typ**                              | Biblioteka do tworzenia UI                          | Framework oparty na React                                                          |
| **Renderowanie**                     | Tylko klienckie (CSR)                               | Obsługuje CSR, SSR, SSG i ISR                                                      |
| **Routing**                          | Realizowany ręcznie, na przykład przez React Router | Routing oparty na plikach (`pages/` albo `app/`)                                   |
| **SEO**                              | Słabsze wsparcie przez CSR                          | Dobre wsparcie SEO dzięki SSR i SSG                                                |
| **Trasy API**                        | Brak                                                | Wbudowana możliwość tworzenia endpointów API (`pages/api/`)                        |
| **Cache**                            | Brak wbudowanych mechanizmów                        | ISR pozwala aktualizować strony bez pełnej regeneracji                             |
| **Optymalizacja wydajności**         | Wymaga rozwiązań zewnętrznych                       | Wbudowane optymalizacje, takie jak code splitting i automatyczne ładowanie obrazów |
| **Wsparcie komponentów serwerowych** | Zależy od konfiguracji                              | Wbudowane wsparcie React Server Components (`app/`)                                |

#### Wniosek:

- **React** dobrze nadaje się do SPA renderowanych po stronie klienta.

- **Next.js** lepiej sprawdza się w projektach wymagających SEO, renderowania
  hybrydowego i wysokiej wydajności aplikacji webowych.

</details>

<details>
<summary>86. Do czego służy React Helmet Async?</summary>

#### React

**React Helmet Async** to zoptymalizowana wersja **React Helmet**, używana do
dynamicznej aktualizacji `<head>` w aplikacjach React, czyli meta tagów,
tytułów, Open Graph i podobnych elementów.

#### Po co jest potrzebny?

1. **Optymalizacja SEO**: pozwala zmieniać tytuły stron, meta opisy i słowa
   kluczowe.

2. **Dynamiczny `<head>`**: umożliwia zmianę tagów dla każdej strony bez
   przeładowania.

3. **Wsparcie SSR (Server-Side Rendering)**: w przeciwieństwie do zwykłego React
   Helmet, ta wersja poprawnie działa w aplikacjach SSR bez problemów z
   asynchronicznością.

#### Przyklad użycia:

```jsx
import { Helmet } from 'react-helmet-async';

function MyComponent() {
  return (
    <Helmet>
      <title>Strona główna</title>
      <meta name="description" content="To jest opis strony głównej" />
    </Helmet>
  );
}
```

#### SSR (Next.js, Express)

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

#### Dlaczego jest lepszy od `react-helmet`?

- Obsługuje SSR bez błędów związanych z asynchronicznością.
- Jest lżejszy i szybszy.
- Nie powoduje problemów w `StrictMode`.

#### Wniosek:

Jeśli potrzebujesz SEO w React z SSR, warto używać `react-helmet-async`.

</details>

<details>
<summary>87. Czym jest komponent rozproszony (Distributed Component)?</summary>

#### React

**Komponent rozproszony (Distributed Component)** to koncepcja, w której
komponent jest dzielony na kilka niezależnych części, mogących renderować się
albo wykonywać logikę osobno, ale działających razem.

#### Przykłady realizacji:

1. **Code splitting**

- Komponenty ładują się tylko wtedy, gdy są potrzebne, co zmniejsza początkowy
  rozmiar bundla.

```jsx
import { lazy, Suspense } from 'react';

const LazyComponent = lazy(() => import('./LazyComponent'));

function App() {
  return (
    <Suspense fallback={<div>Ladowanie...</div>}>
      <LazyComponent />
    </Suspense>
  );
}
```

2. **Komponenty kontenerowe (Container-Presentational Pattern)**

- Rozdziela logikę, czyli kontener, od prezentacji, czyli komponentu
  prezentacyjnego.

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
  return <div>{data ? JSON.stringify(data) : 'Ladowanie...'}</div>;
}

function App() {
  return (
    <DataContainer>{data => <Presentational data={data} />}</DataContainer>
  );
}
```

3. **Mikrofrontendy (Micro Frontends)**

- Wykorzystanie oddzielnych autonomicznych komponentów w różnych częściach
  aplikacji.
- Na przykład różne zespoły rozwijają odrębne części dużego projektu w `React`,
  `Vue` albo `Angular` i integrują je razem.

#### Kiedy używać:

- Do optymalizacji wydajności, na przykład przez lazy loading.

- Aby uprościć utrzymanie kodu przez rozdzielenie logiki.

- W skalowalnych aplikacjach, na przykład opartych na mikrofrontendach.

</details>

<details>
<summary>88. Czym jest komponent przełączający (Switching Component)?</summary>

#### React

**Komponent przełączający (Switching Component)** w React to wzorzec, w którym
komponent dynamicznie renderuje jeden ze swoich komponentów podrzędnych na
podstawie określonego warunku. Stosuje się go wtedy, gdy trzeba wyświetlać różne
komponenty zależnie od stanu, trasy albo otrzymanych danych.

#### Przykład 1: przełączanie na podstawie stanu

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

- `type` określa, który komponent zostanie wyświetlony.

#### Przykład 2: użycie z React Router

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

- Tutaj `Routes` działa jak komponent przełączający, renderując odpowiedni
  komponent zależnie od adresu URL.

#### Przykład 3: warunkowe renderowanie przez obiekt

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

- To czystszy wariant bez użycia `switch`.

Komponenty przełączające upraszczają logikę i sprawiają, że kod staje się
czytelniejszy, gdy trzeba warunkowo renderować różne komponenty.

</details>

<details>
<summary>89. Czym jest Reselect i jak działa?</summary>

#### React

**Reselect** to biblioteka do tworzenia wydajnych selektorów w Redux. Pomaga
optymalizować pobieranie danych ze stanu i unikać niepotrzebnych renderów
komponentów dzięki memoizacji.

#### Jak działa Reselect?

Reselect używa **memoizacji**, aby ponownie wykorzystywać wyniki obliczeń, jeśli
dane wejściowe się nie zmieniły.

1. **Przyjmuje input selektory**, które pobierają dane ze stanu.

2. **Oblicza wartość** na podstawie otrzymanych danych.

3. **Cache'uje wynik**, aby nie wykonywać obliczeń przy tych samych danych
   wejściowych.

#### Przyklad użycia:

```jsx
import { createSelector } from 'reselect';

// Input selector pobiera wszystkich użytkowników
const selectUsers = state => state.users;

// Input selector pobiera aktywny filtr
const selectFilter = state => state.filter;

// Zmemoizowany selector filtruje użytkowników
export const selectFilteredUsers = createSelector(
  [selectUsers, selectFilter],
  (users, filter) => users.filter(user => user.role === filter)
);
```

- Bez Reselect komponent sprawdzałby całą tablicę `users` przy każdym renderze.
- Z Reselect selector wykonuje się tylko wtedy, gdy `users` albo `filter` się
  zmieniają.

#### Zalety Reselect:

- Zmniejsza liczbę zbędnych wywołań `mapStateToProps`.
- Unika niepotrzebnych renderów komponentów.
- Łatwo integruje się z Redux.
- Poprawia wydajność.

</details>

<details>
<summary>90. Jakie typy danych może zwrócić render?</summary>

#### React

Metoda `render()` w React może zwracać:

1. **JSX albo element React**

```jsx
render() {
return <div>Hello, World!</div>;
}
```

2. **Tablicę elementów, czyli renderowanie fragmentaryczne**

```jsx
render() {
return [
<li key="1">Item 1</li>,
<li key="2">Item 2</li>
];
}
```

3. **Fragmenty (`React.Fragment`)**

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

4. **`null`, czyli nic nie renderować**

```jsx
render() {
return null;
}
```

5. **Wartości boolowskie, które są ignorowane**

```jsx
render() {
return false; // Nic się nie wyświetli
}
```

6. **Wartości tekstowe, renderowane jako tekst**

```jsx
render() {
return "Hello, World!";
}
```

7. **Portale, czyli renderowanie do elementu DOM poza komponentem nadrzędnym**

```jsx
import { createPortal } from "react-dom";

render() {
return createPortal(<div>Modal</div>, document.getElementById("modal-root"));
}
```

#### Wniosek:

Najczęściej zwraca się JSX albo elementy React, ale można też zwracać tablice,
fragmenty, `null`, tekst albo renderować przez portale.

</details>

<details>
<summary>91. Jak React obsługuje lub ogranicza użycie propsów określonego typu?</summary>

#### React

React ogranicza użycie propsów określonego typu za pomocą `PropTypes` albo
`TypeScript`.

1. **Użycie PropTypes, czyli wbudowanego sprawdzania typów**

```jsx
import PropTypes from 'prop-types';

const MyComponent = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Wiek: {age}</p>
      <p>{isActive ? 'Aktywny' : 'Nieaktywny'}</p>
    </div>
  );
};

// Definicja typów propsów
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isActive: PropTypes.bool,
};
```

- `PropTypes.string.isRequired` oznacza obowiązkowy prop `name`.
- `PropTypes.number` oznacza, że `age` musi być liczbą.
- `PropTypes.bool` oznacza, że `isActive` musi być wartością boolowską.

Jeśli zostaną przekazane niepoprawne typy, React pokaże ostrzeżenie w konsoli,
ale tylko w trybie development.

2. **Użycie TypeScript, czyli ścisła kontrola na etapie kompilacji**

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
      <p>Wiek: {age}</p>
      <p>{isActive ? 'Aktywny' : 'Nieaktywny'}</p>
    </div>
  );
};
```

- `name: string` oznacza obowiązkowy prop tekstowy.
- `age?: number` oznacza opcjonalny prop liczbowy.
- `isActive: boolean` oznacza obowiązkowy prop typu boolean.

TypeScript zgłosi błąd jeszcze przed uruchomieniem kodu, jeśli zostaną
przekazane nieprawidłowe propsy.

#### Co wybrać?

| **Metoda**     | **Zalety**                                | **Wady**                                        |
| -------------- | ----------------------------------------- | ----------------------------------------------- |
| **PropTypes**  | Proste, działa w JavaScript               | Sprawdza tylko w runtime, słabsza kontrola      |
| **TypeScript** | Ścisłe typowanie, wcześniej wykrywa błędy | Wymaga kompilacji, ma bardziej złożoną składnię |

Jeśli projekt używa **TypeScript**, **PropTypes** zwykle nie są potrzebne. Jeśli
to **JavaScript**, **PropTypes** zapewniają podstawową walidację.

</details>

<details>
<summary>92. Jaka jest różnica między renderowaniem a montowaniem?</summary>

#### React

Różnica między renderowaniem a montowaniem w React

| **Proces**                   | **Opis**                                                                                                                                                                                                |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Montowanie (Mounting)**    | Komponent jest tworzony i dodawany do DOM po raz pierwszy. Wywoływane są `constructor`, `render`, `componentDidMount` w klasach albo `useEffect` z pustą tablicą zależności w komponentach funkcyjnych. |
| **Renderowanie (Rendering)** | Następuje wywołanie `render()` albo ponowne wywołanie komponentu funkcyjnego w celu zaktualizowania zawartości. Dzieje się to przy zmianie `state`, `props` albo po wywołaniu `forceUpdate()`.          |

#### Przykład montowania

```jsx
useEffect(() => {
  console.log('Komponent został zamontowany');
}, []); // Wykona się raz przy montowaniu
```

#### Przykład renderowania

```jsx
const [count, setCount] = useState(0);

useEffect(() => {
  console.log('Komponent został wyrenderowany');
}); // Wykona się przy każdym renderze

return <button onClick={() => setCount(count + 1)}>+</button>;
```

Tutaj render zachodzi przy każdej zmianie `count`.

</details>

<details>
<summary>93. Czym jest reaktywny przepływ danych (reactive data flow) w React?</summary>

#### React

**Reaktywny przepływ danych (Reactive Data Flow) w React** oznacza, że zmiany
stanu albo propsów komponentu automatycznie prowadzą do aktualizacji UI bez
konieczności ręcznego wywoływania renderu.

#### Główne zasady:

1. **Jednokierunkowy przepływ danych**: React przekazuje dane z góry na dół,
   czyli od komponentów nadrzędnych do podrzędnych.

2. **Deklaratywność**: opisujemy, co ma być wyrenderowane, a React sam zarządza
   aktualizacją.

3. **Automatyczna aktualizacja**: jeśli `state` albo `props` się zmieniają,
   React renderuje ponownie tylko zmienione części.

#### Przykład reaktywnej aktualizacji:

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Licznik: {count}</p>
      <button onClick={() => setCount(count + 1)}>Zwiększ</button>
    </div>
  );
}
```

#### Jak to działa?

- `useState` tworzy stan `count`.

- Po kliknięciu `setCount(count + 1)` aktualizuje stan.

- React automatycznie renderuje komponent ponownie z nowymi danymi.

#### Czy React jest całkowicie reaktywny?

- Nie. W przeciwieństwie do frameworków takich jak Svelte albo Solid.js, React
  nie aktualizuje DOM przy bezpośredniej zmianie zmiennej. Używa Virtual DOM i
  uruchamia ponowny render przy zmianie `state` albo `props`.

#### Wniosek:

- Reaktywny przepływ danych w React oznacza, że UI aktualizuje się automatycznie
  przy zmianie stanu, ale z wykorzystaniem Virtual DOM i batchowania
  aktualizacji dla optymalizacji.

</details>

<details>
<summary>94. Czy React jest reaktywny?</summary>

#### React

React nie jest w pełni reaktywną biblioteką, jak na przykład Vue albo Svelte. Ma
jednak pewne cechy, które upodabniają go do reaktywnych frameworków:

1. **Automatyczna aktualizacja UI**: React automatycznie aktualizuje interfejs,
   gdy zmienia się stan albo propsy komponentu, co przypomina podejście
   reaktywne. Dzieje się to przez proces renderowania i porównywania zmian.

2. **Komponenty funkcyjne i hooki**: Użycie hooków takich jak `useState` i
   `useEffect` daje efekt reaktywności, gdzie zmiany w stanie albo propsach
   prowadzą do ponownego renderowania komponentów.

3. **Częściowa reaktywność**: React renderuje ponownie tylko te komponenty,
   których stan albo propsy się zmieniły. To jest podejście reaktywne, ale w
   przeciwieństwie do innych frameworków React nie używa automatycznych
   obserwatorów zależności.

Podsumowując, React wykorzystuje pewne reaktywne zasady, ale nie jest w pełni
reaktywnym frameworkiem.

</details>

<details>
<summary>95. Jakie znasz sposoby implementacji drag-and-drop w React?</summary>

#### React

Drag-and-drop w React można zrealizować na kilka sposobów:

- **Użycie HTML5 API** (`onDragStart`, `onDrop`)

- **Biblioteki** (`react-dnd`, `dnd-kit`)

1. **Użycie natywnego Drag-and-Drop API**

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

- Prosty wariant, bez zewnętrznych bibliotek.
- Ograniczona kontrola, brak wsparcia dla bardziej złożonych przypadków.

2. **Użycie `react-dnd`, czyli bardziej rozbudowanego wariantu**

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

- Elastyczny, wspiera złożone przypadki.
- Ułatwia pracę z elementami zagnieżdżonymi.
- Dodaje zależność do projektu.

3. **Użycie `dnd-kit`, czyli prostego i nowoczesnego wariantu**

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

- Nowoczesne API, lżejsze od `react-dnd`.
- Prosty w użyciu.
- Obsługuje sortowanie (`sortable`).

#### Wniosek:

- Jeśli potrzebujesz czegoś prostego, wybierz **HTML5 Drag-and-Drop API**.

- Jeśli potrzebujesz elastycznej kontroli, wybierz **react-dnd**.

- Jeśli chcesz nowoczesne i lekkie rozwiązanie, wybierz **dnd-kit**.

</details>

<details>
<summary>96. Jak wyrenderować kod HTML w komponencie React?</summary>

#### React

Użyj `dangerouslySetInnerHTML`, ale zachowaj ostrożność. Może to prowadzić do
ataków XSS, jeśli wstawiasz niesanitizowane dane.

#### Przyklad:

```jsx
function MyComponent() {
  const htmlContent = "<p style='color: red;'>To jest kod HTML</p>";

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
}
```

Jeśli pracujesz z danymi dynamicznymi, koniecznie sanitizuj je przed
wstawieniem.

</details>

<details>
<summary>97. Jak dodać klasę warunkowo w React?</summary>

#### React

W React warunkowe dodawanie klas do elementów zwykle realizuje się przez atrybut
`className` oraz użycie operatora trójargumentowego albo funkcji określających
warunki.

#### Główne podejścia:

1. **Operator trójargumentowy**

```jsx
function MyComponent({ isActive }) {
  return (
    <div className={isActive ? 'active-class' : 'inactive-class'}>Hello</div>
  );
}
```

- Jeśli `isActive` ma wartość `true`, do elementu zostanie dodana klasa
  `active-class`.
- W przeciwnym razie zostanie użyta `inactive-class`.

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

- `base-class` jest dodawana zawsze.
- Jeśli `isHighlighted` ma wartość `true`, zostanie dodana także
  `highlighted-class`.

3. **Biblioteka `clsx`**

- `clsx` pomaga pracować z klasami w bardziej elegancki sposób.

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

- `clsx` pozwala łatwo dodawać kilka klas na podstawie warunków.

4. **Biblioteka `classnames`**

- Jest podobna do `clsx`, ale oferuje więcej możliwości.

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

5. **Wyniesienie logiki do osobnej funkcji**

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

- Logika określania klas staje się bardziej czytelna i może być ponownie użyta.

#### Wniosek:

- Dla prostych przypadków wystarczy operator trójargumentowy albo template
  strings.

- Dla bardziej złożonych warunków lepiej używać bibliotek `clsx` albo
  `classnames`, które poprawiają wygodę i czytelność kodu.

</details>

<details>
<summary>98. Jak wykonać kod przed usunięciem komponentu z drzewa?</summary>

#### React

Aby wykonać kod przed usunięciem komponentu z drzewa w React, stosuje się
następujące podejścia:

1. **Komponenty klasowe:** `componentWillUnmount`

- W komponentach klasowych istnieje metoda cyklu życia `componentWillUnmount`,
  która jest wywoływana przed usunięciem komponentu.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Komponent zostanie usuniety');
  }

  render() {
    return <div>Moj komponent</div>;
  }
}
```

2. **Komponenty funkcyjne:** `useEffect` z czyszczeniem

- W komponentach funkcyjnych czyszczenie można wykonać w `useEffect`, zwracając
  funkcję, która uruchomi się przed usunięciem komponentu.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Komponent zostanie usuniety');
    };
  }, []);

  return <div>Moj komponent</div>;
}
```

3. **Obsługa przed zamknięciem strony (`beforeunload`)**

- Jeśli trzeba wykonać kod przed zamknięciem karty albo odświeżeniem strony:

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('Strona jest zamykana');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Wniosek

- `componentWillUnmount` dla komponentów klasowych.

- `useEffect` ze zwracaną funkcją dla komponentów funkcyjnych.

- `beforeunload` dla przypadków, w których trzeba reagować na opuszczenie
  strony.

</details>

<details>
<summary>99. Czym jest useReducer()?</summary>

#### React

- `useReducer()` to hook w React, używany do zarządzania stanem w komponentach
  funkcyjnych. Jest alternatywą dla `useState()`, która dobrze sprawdza się przy
  złożonej logice aktualizacji stanu, szczególnie gdy zmiany zależą od
  poprzedniego stanu.

#### Składnia:

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` to funkcja przyjmująca `state` i `action`, a następnie zwracająca
  nowy stan.

- `initialState` to stan początkowy.

- `dispatch` to funkcja wywołująca reducer z określoną `action`.

#### Przyklad:

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

#### Kiedy używać:

- Gdy stan ma złożoną logikę albo zależności.

- Gdy trzeba ujednolicić aktualizację stanu przez `dispatch`.

- Dla większej skalowalności, na przykład przy stanie globalnym.

</details>

<details>
<summary>100. Jak używać React.lazy i React.Suspense do uruchamiania kodu aplikacji?</summary>

#### React

`React.lazy` i `React.Suspense` służą do **dynamicznego ładowania komponentów**
w React, co pozwala realizować **code splitting**. Oznacza to, że części kodu są
ładowane tylko wtedy, gdy są potrzebne, co poprawia wydajność aplikacji.

#### Jak to działa:

1. `React.lazy()` pozwala odroczone ładować komponent.

2. `React.Suspense` służy do opakowania części kodu, która nie została jeszcze
   załadowana, i pozwala pokazywać zawartość zastępczą, na przykład loader,
   dopóki komponenty się nie załadują.

#### Przyklad:

1. **Dynamiczne ładowanie komponentu:**

- Najpierw utwórz komponent, który będzie ładowany dynamicznie.

```jsx
// Komponent ładowany dynamicznie
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Opakowanie z `React.Suspense`:**

- Teraz użyj `React.Suspense`, aby pokazać loader podczas ładowania komponentu.

```jsx
function App() {
  return (
    <div>
      <h1>Moja aplikacja</h1>

      {/* Opakowanie dla dynamicznie ładowanych komponentów */}
      <React.Suspense fallback={<div>Ladowanie...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Opis:**

- `React.lazy()` przyjmuje funkcję dynamicznie importującą moduł.

- `React.Suspense` opakuje komponent używający `React.lazy()` i pokaże zawartość
  zastępczą, w tym przypadku tekst "Ladowanie...", dopóki komponent się nie
  załaduje.

#### Zalety:

- Poprawia wydajność, ładując komponenty tylko wtedy, gdy są potrzebne.

- Zmniejsza rozmiar początkowego ładowania, ponieważ części aplikacji są
  ładowane na żądanie.

To podejście jest szczególnie przydatne w dużych aplikacjach, gdzie można
podzielić kod na części, aby skrócić czas ładowania strony.

</details>

<details>
<summary>101. Jakie podejścia stosuje się do wykonywania zapytań HTTP w React?</summary>

#### React

#### Podejścia do wykonywania zapytań HTTP w React

React nie ma wbudowanego API do wykonywania zapytań HTTP, ale można używać
bibliotek zewnętrznych albo standardowych mechanizmów JavaScript. Oto główne
podejścia:

1. **Użycie Fetch API**

- To standardowe narzędzie do wykonywania zapytań HTTP w JavaScript.

**Przyklad:**

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

2. **Użycie Axios**

- Biblioteka do wykonywania zapytań HTTP z prostszą składnią i wbudowanym
  wsparciem dla interceptorów.

**Przyklad:**

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

- Biblioteka do zarządzania stanem danych pobieranych przez HTTP. Obsługuje
  cache, ponowne próby i odświeżanie danych.

**Przyklad:**

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

- Do pracy z GraphQL API używa się Apollo Client.

**Przyklad:**

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

- Możesz tworzyć własne hooki do ponownego wykorzystania logiki zapytań.

**Przyklad:**

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

#### Wybór podejścia zależy od potrzeb:

- **Fetch API:** do prostych zapytań.

- **Axios:** jeśli potrzebna jest większa elastyczność, na przykład interceptory
  albo timeouty.

- **React Query:** do zarządzania cache danych.

- **GraphQL/Apollo Client:** jeśli API jest oparte na GraphQL.

- **Custom Hooks:** do ponownego użycia logiki zapytań.

</details>

<details>
<summary>102. Jaka jest różnica między createElement a cloneElement?</summary>

#### React

| **Metoda**            | **Opis**                                                                                     | **Główne zastosowanie**                                                      |
| --------------------- | -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| `React.createElement` | Tworzy nowy element React. Przyjmuje typ elementu, propsy i elementy potomne jako argumenty. | Służy do tworzenia elementów React od zera, zwykle podczas renderowania JSX. |
| `React.cloneElement`  | Klonuje istniejący element React, pozwalając zmienić jego propsy albo elementy potomne.      | Służy do tworzenia zmodyfikowanych kopii już istniejących elementów React.   |

#### Przykłady:

`React.createElement`

```jsx
const element = React.createElement(
  'div',
  { className: 'example' },
  'Привіт, React!'
);
```

Rezultat: tworzony jest `<div class="example">Witaj, React!</div>`.

`React.cloneElement`

```jsx
const originalElement = <button className="primary">Kliknij</button>;

const clonedElement = React.cloneElement(originalElement, {
  className: 'secondary',
});
```

Rezultat: klon `<button class="secondary">Kliknij</button>` ze zmienioną klasą.

#### Różnica:

- `createElement` tworzy całkowicie nowy element.

- `cloneElement` działa na podstawie już istniejącego elementu i pozwala
  zmieniać jego właściwości albo zawartość.

</details>

<details>
<summary>103. Czy funkcja lazy obsługuje eksport nazwany?</summary>

#### React

- Nie, funkcja `React.lazy` nie obsługuje eksportu nazwanego. Działa tylko z
  eksportem domyślnym. Jeśli masz moduł z eksportem nazwanym i chcesz użyć go z
  `React.lazy`, trzeba stworzyć opakowanie, które wyeksportuje odpowiedni
  komponent jako `default`.

#### Przykład opakowania:

```jsx
// Eksport nazwany
export const MyComponent = () => {
  return <div>Hello, World!</div>;
};

// Використання React.lazy
const LazyComponent = React.lazy(() =>
  import('./MyComponent').then(module => ({ default: module.MyComponent }))
);

export default LazyComponent;
```

- Tutaj jawnie wskazujemy, że `module.MyComponent` ma zostać użyty jako eksport
  domyślny.

</details>

<details>
<summary>104. Jakie są zalety React?</summary>

#### React

#### Zalety React

1. **Wysoka wydajność**

- Użycie **Virtual DOM** minimalizuje aktualizacje prawdziwego **DOM**, dzięki
  czemu renderowanie jest szybsze.

2. **Podejście komponentowe**

- Aplikacja składa się z **wielokrotnego użytku komponentów**, co ułatwia
  development i utrzymanie.

3. **Jednokierunkowy przepływ danych (Unidirectional Data Flow)**

- Dane są przekazywane w dół hierarchii komponentów, co upraszcza śledzenie
  zmian stanu.

4. **Wsparcie hooków (Hooks)**

- `useState`, `useEffect`, `useMemo` i inne hooki pozwalają zarządzać stanem i
  efektami w komponentach funkcyjnych bez użycia klas.

5. **Server-side rendering (SSR) i static site generation (SSG)**

- Z Next.js można poprawić SEO i wydajność aplikacji.

6. **Elastyczność i ekosystem**

- React można łączyć z **Redux**, **Zustand**, **MobX**, **React Query** i
  wieloma innymi narzędziami.

- Obsługuje **React Native** do tworzenia aplikacji mobilnych.

7. **Rozbudowane możliwości debugowania**

- **React DevTools** pozwala podglądać strukturę komponentów, stan i propsy w
  czasie rzeczywistym.

8. **Aktywna społeczność i wsparcie Facebooka**

- Duży wybór bibliotek i gotowych rozwiązań oraz szybki rozwój frameworka.

React to elastyczne, wydajne i nowoczesne narzędzie do tworzenia aplikacji
webowych.

</details>

<details>
<summary>105. Jakie są ograniczenia React?</summary>

#### React

1. **Duża liczba rerenderów:** Jeśli komponenty są źle zoptymalizowane, może to
   prowadzić do nadmiernych rerenderów i pogorszenia wydajności.

2. **Konieczność zarządzania stanem:** Bez odpowiedniego zarządzania stanem
   aplikacja może stać się trudna w utrzymaniu.

3. **Jednokierunkowy przepływ danych:** Dane płyną tylko w jednym kierunku, co
   może utrudniać przekazywanie ich przez wiele poziomów komponentów.

4. **Reaktywność:** React aktualizuje DOM przez Virtual DOM, ale w bardzo dużych
   i dynamicznych aplikacjach nie zawsze jest to najefektywniejsze rozwiązanie.

5. **Zależność od JavaScript:** Bez JavaScript po stronie klienta wsparcie jest
   ograniczone.

6. **Krzywa nauki dla początkujących:** Choć podstawowe koncepcje React są
   proste, dobre opanowanie hooków, kontekstu i optymalizacji może być trudne.

7. **Narzędzia zewnętrzne:** Chociaż istnieje wiele narzędzi, ich integracja w
   dużych projektach może być skomplikowana.

</details>

<details>
<summary>106. Do czego służy metoda registerServiceWorker() w React?</summary>

#### React

`registerServiceWorker()` był używany do rejestracji Service Workera w Create
React App, zanim został usunięty z CRA w wersji 4.

#### Przeznaczenie:

- Cache'owanie zasobów do trybu offline

- Przyspieszanie ładowania aplikacji

- Aktualizowanie zasobów w tle

#### Przykład użycia, przed CRA 4:

```javascript
import { register } from './serviceWorker';

register();
```

- Po usunięciu z CRA Service Worker trzeba konfigurować ręcznie przez
  `navigator.serviceWorker.register()`.

- W **React 19** nie ma wbudowanego `registerServiceWorker()`, ponieważ został
  usunięty już wcześniej razem z Create React App 4. Jeśli potrzebujesz Service
  Workera, rejestruj go ręcznie.

Wniosek: w nowoczesnych projektach ten mechanizm nie jest już aktualny i Service
Worker trzeba skonfigurować samodzielnie.

</details>

<details>
<summary>107. Czym są zdarzenia syntetyczne (SyntheticEvent) w React?</summary>

#### React

- **SyntheticEvent** w React to warstwa nad natywnymi zdarzeniami przeglądarki,
  która zapewnia zgodność między przeglądarkami i poprawia wydajność.

#### Cechy SyntheticEvent:

- Działa tak samo we wszystkich przeglądarkach.

- Wykorzystuje pooling zdarzeń, co ogranicza utrzymywanie zbędnych obiektów w
  pamięci.

- Wszystkie zdarzenia są znormalizowane i mają te same właściwości niezależnie
  od przeglądarki.

#### Przyklad użycia:

```jsx
function MyComponent() {
  const handleClick = event => {
    console.log(event.type); // "click"
    console.log(event.nativeEvent); // Oryginalne zdarzenie przeglądarki
  };

  return <button onClick={handleClick}>Kliknij</button>;
}
```

#### Główne metody:

- `event.preventDefault()` zapobiega domyślnemu zachowaniu.

- `event.stopPropagation()` zatrzymuje propagację zdarzenia.

- `event.persist()` wyłącza pooling, aby zdarzenie nie zostało wyczyszczone.

</details>

<details>
<summary>108. Jakie są techniki optymalizacji wydajności w React?</summary>

#### React

#### Techniki optymalizacji wydajności w React:

1. **Memoizacja komponentów**

- Używaj `React.memo()` do zapobiegania zbędnym rerenderom.
- `useMemo()` stosuj do cache'owania obliczeń.
- `useCallback()` używaj do zachowania stabilności funkcji.

2. **Optymalizacja rerenderów**

- Unikaj zbędnych stanów (`useState`) i propsów.
- W komponentach klasowych używaj `shouldComponentUpdate` albo
  `React.PureComponent`.
- Optymalizuj kontekst (`Context API`) i nie przekazuj zbędnych wartości.
- Używaj selectorów, takich jak `Reselect`, `Zustand` albo `Jotai`, aby
  minimalizować aktualizacje.

3. **Wirtualizacja list**

- `react-window` i `react-virtualized` służą do renderowania tylko widocznych
  elementów.

4. **Cache i debounce**

- `useMemo()` i `useCallback()` stosuj przy kosztownych obliczeniach.
- Debounce (`lodash.debounce`) albo throttling (`lodash.throttle`) wykorzystuj
  przy danych wejściowych użytkownika.

5. **Lazy loading**

- `React.lazy()` i `Suspense` stosuj do podziału kodu.
- Używaj dynamicznego importu modułów przez `import()`.

6. **Unikanie zbędnych efektów w useEffect**

- Poprawnie przekazuj zależności.
- Używaj `useRef` do przechowywania wartości bez rerenderu.

7. **Optymalizacja obrazów**

- Używaj `next/image` w Next.js.
- Optymalizuj rozmiary i formaty, takie jak `WebP` i `AVIF`.

8. **Optymalizacja React Router**

- Używaj `React.lazy()` dla stron.
- Unikaj zbędnych rerenderów przez poprawną aktualizację stanu.

9. **Rozdzielanie stanu**

- Używaj lokalnego stanu tam, gdzie nie jest potrzebny globalny.
- Wynoś zmiany globalne do `Redux`, `Zustand` albo `Recoil`.

10. **Użycie Web Workers**

- Do ciężkich obliczeń, aby nie blokować głównego wątku.

</details>

<details>
<summary>109. Czy można używać async/await w React?</summary>

#### React

- Tak, można używać `async/await` w React, ale warto pamiętać o kilku rzeczach:

1. **Użycie w komponentach:** `async/await` nie powinno być używane bezpośrednio
   w `render()` ani jako samo ciało komponentu. Można go jednak używać w
   handlerach zdarzeń albo wewnątrz hooków, na przykład `useEffect`.

2. **Obsługa zapytań asynchronicznych:**

- Używaj `async/await` wewnątrz funkcji wywoływanych w hookach, na przykład:

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

3. **Obsługa błędów:** pamiętaj o użyciu `try/catch` do przechwytywania błędów
   przy zapytaniach asynchronicznych:

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

Podsumowując, `async/await` można i warto stosować do operacji asynchronicznych
w React, ale trzeba robić to we właściwym miejscu w strukturze komponentu.

</details>

<details>
<summary>110. Jaka jest historia ewolucji React?</summary>

#### React

Oto krótka historia ewolucji React:

1. **2011**

- React został stworzony w Facebooku na potrzeby wewnętrzne. Opracował go
  inżynier Jordan Walke, aby rozwiązać problem wydajnej aktualizacji interfejsu.

2. **2013**

- Facebook udostępnił React jako bibliotekę open source. Początkowo społeczność
  podchodziła do niej sceptycznie z powodu użycia JSX, który wydawał się
  nietypowy.

3. **2015**

- Wydano React 0.14, rozdzielając `React` i `ReactDOM`, co uczyniło bibliotekę
  bardziej modułową.

- Facebook zaprezentował React Native, który pozwolił tworzyć natywne aplikacje
  mobilne z użyciem React.

4. **2016**

- Wydano React 15. Główne aktualizacje dotyczyły poprawy wydajności dzięki
  nowemu silnikowi renderowania.

5. **2017**

- Wydano React 16 z architekturą Fiber, która poprawiła wydajność i wprowadziła
  wsparcie dla renderowania asynchronicznego.

- Dodano wsparcie dla portali i **Error Boundaries**.

6. **2018**

- Facebook przedstawił React Hooks, które pozwoliły używać stanu i metod cyklu
  życia w komponentach funkcyjnych. Była to duża zmiana w sposobie budowania
  komponentów.

7. **2019**

- Wydano React 16.8 z oficjalnym wsparciem dla hooków.

- Eksperymentalnie rozwijano Concurrent Mode.

8. **2020**

- Wydano React 17. Głównym celem było uproszczenie stopniowej aktualizacji React
  w dużych projektach.

- Dodano wsparcie dla nowoczesnych narzędzi i nowych możliwości pracy z JSX.

9. **2022**

- Wydano React 18. Najważniejszymi nowościami były Concurrent Rendering oraz API
  `useTransition` i `useDeferredValue`, poprawiające wydajność dynamicznych
  aplikacji.

10. **2024**

- Wydano React 19.

- Ulepszono server-side rendering i React Server Components.

- Dodano wsparcie dla nowej funkcji `use`.

- Ulepszono system formularzy, obsługę błędów renderowania oraz składnię JSX bez
  konieczności `import React`.

- Rozwinięto React Compiler do automatycznej optymalizacji wydajności.

#### Główne zmiany w trakcie ewolucji:

- Od komponentów klasowych do funkcyjnych z hookami.

- Wsparcie dla server-side rendering (SSR).

- Concurrent Mode dla płynniejszej aktualizacji interfejsu.

- Integracja React z tworzeniem aplikacji mobilnych przez React Native.

React pozostał popularny dzięki wysokiej wydajności, wygodzie użycia i stałemu
rozwojowi wspieranemu przez Meta.

</details>

<details>
<summary>111. Jakie nowości dodano w React 19?</summary>

#### React

React 19 wprowadził szereg istotnych zmian ukierunkowanych na poprawę wydajności
i wygody pracy programistów. Oto najważniejsze nowości:

1. **Nowy system renderowania:** Wprowadzono renderowanie asynchroniczne, które
   pozwala React skuteczniej zarządzać aktualizacjami interfejsu i poprawiać
   interakcję z użytkownikiem.

2. **React Compiler:** Nowy kompilator automatycznie optymalizuje ponowne
   rendery, ograniczając zbędne aktualizacje i zwiększając wydajność aplikacji.

3. **Actions API:** To nowe podejście do zarządzania stanem i mutacjami danych
   po stronie serwera, upraszczające obsługę efektów ubocznych i zapytań do
   danych.

4. **Ulepszona mechanika Suspense:** Daje programistom większą kontrolę nad
   asynchronicznym ładowaniem danych, ułatwiając zarządzanie hydratacją
   komponentów i stanami fallback.

5. **Hook `use`:** Nowy hook upraszczający pracę z danymi asynchronicznymi i
   poprawiający wsparcie dla komponentów serwerowych.

6. **Natywne wsparcie metatagów:** Teraz `meta`, `title`, `link` i inne metatagi
   są wspierane bez dodatkowych bibliotek, co upraszcza zarządzanie SEO i
   zasobami.

- Te nowości czynią React 19 potężniejszym i wygodniejszym narzędziem dla
  programistów, poprawiając zarówno wydajność aplikacji, jak i komfort pracy.

</details>

<details>
<summary>112. Co zalecają twórcy React po wycofaniu Create React App?</summary>

#### React

Po zakończeniu wsparcia dla Create React App w lutym 2025 roku programistom
zaleca się używanie nowoczesnych frameworków do tworzenia nowych aplikacji
React. Frameworki te wspierają renderowanie po stronie klienta (CSR) oraz
aplikacje jednostronicowe (SPA), które można wdrażać na CDN albo statycznych
hostingach bez potrzeby utrzymywania serwera.

#### Zalecane frameworki:

1. **Next.js:** Oferuje rozbudowane możliwości, takie jak server-side rendering
   i generowanie statycznych stron, zapewniając wysoką wydajność i dobre SEO.

2. **React Router:** Umożliwia tworzenie SPA z dynamicznym routingiem, dzięki
   czemu łatwo zarządzać nawigacją w aplikacji.

3. **Expo:** Upraszcza rozwój aplikacji React Native, dostarczając narzędzia do
   tworzenia wieloplatformowych aplikacji mobilnych z użyciem JavaScript i
   React.

</details>

<details>
<summary>113. Jak działa hook useDeferredValue w React?</summary>

#### React

`useDeferredValue` to hook React, który pojawił się w React 18 jako część
Concurrent Mode. Pozwala odraczać aktualizacje określonych wartości, takich jak
stan czy propsy, obniżając ich priorytet i umożliwiając Reactowi najpierw zająć
się ważniejszymi zadaniami interfejsu.

Jest to bardzo przydatne wtedy, gdy wartość często się zmienia, a aktualizacja
interfejsu przy każdej zmianie jest kosztowna.

##### Do czego używa się `useDeferredValue`?

- Aby unikać opóźnień i zacięć w złożonych aplikacjach, gdzie szybkość reakcji
  interfejsu ma znaczenie.
- Aby poprawić interakcję użytkownika, szczególnie gdy zmienia się dużo danych,
  na przykład przy wyszukiwaniu, filtrowaniu albo renderowaniu dużych list.
- Aby zapewnić płynność animacji i przejść między stanami.

##### Jak to działa?

Hook `useDeferredValue` przyjmuje wartość i zwraca jej odroczoną wersję:

```jsx
const deferredValue = useDeferredValue(value);
```

- React od razu aktualizuje krytyczne, priorytetowe zmiany.
- Odroczona wartość (`deferredValue`) jest aktualizowana asynchronicznie po tym,
  jak React obsłuży pilniejsze zadania.
- Jeśli aktualizacje głównej wartości następują zbyt szybko, React może pominąć
  niektóre wartości pośrednie i przejść od razu do ostatniej.

##### Przykład użycia:

Załóżmy, że istnieje komponent z polem wyszukiwania i dużą listą, którą trzeba
filtrować podczas wpisywania tekstu.

###### Bez użycia `useDeferredValue`:

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
        placeholder="Szukaj..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

Może to powodować przycięcia, jeśli lista jest bardzo duża, ponieważ przy każdym
wpisanym znaku React natychmiast przelicza przefiltrowane wyniki.

###### Z użyciem `useDeferredValue`:

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
        placeholder="Szukaj..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

W tym wariancie:

- Wprowadzanie danych przez użytkownika pozostaje szybkie i płynne.
- Filtrowanie listy odbywa się asynchronicznie, po tym jak użytkownik przestanie
  pisać albo gdy zmniejszy się intensywność zmian.
- Dzięki temu interfejs pozostaje responsywny.

##### Cechy działania:

- `useDeferredValue` nie ustawia konkretnego czasu opóźnienia, w przeciwieństwie
  do debounce. Pozwala Reactowi automatycznie określić moment aktualizacji w
  zależności od obciążenia interfejsu.
- Wartość zwrócona przez `useDeferredValue` może być opóźniona względem głównego
  stanu, co trzeba uwzględnić w logice aplikacji.

##### Zalety użycia:

- Zmniejsza obciążenie procesora podczas aktywnych interakcji.
- Zapewnia stabilny FPS i płynny UI.
- Czyni UX bardziej komfortowym i przewidywalnym, szczególnie w dużych i
  złożonych aplikacjach.

##### Kiedy najlepiej używać `useDeferredValue`?

- Listy z dużą liczbą elementów.
- Formularze z aktywnym filtrowaniem i autouzupełnianiem.
- Wszystkie przypadki, gdy częste aktualizacje interfejsu mogą pogarszać
  doświadczenie użytkownika.

</details>
