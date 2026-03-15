**Read in other languages: [English 🇺🇸](README.en.md),
[Polska 🇵🇱](README.pl.md), [German 🇩🇪](README.de.md), [French 🇫🇷](README.fr.md),
[Ukrainien 🇺🇦](README.md).**

<h1>
  React <img src="./assets/react.svg" width="40" height="40" />
</h1>

<h2>Les questions et reponses les plus populaires en entretien React</h2>

<details>
<summary>1. Qu'est-ce que React ?</summary>

#### React

React est une bibliotheque JavaScript destinee a la creation d'interfaces
utilisateur.
Caracteristiques principales :

1. **Approche orientee composants :** l'interface est decoupee en composants
   distincts reutilisables.

2. **DOM virtuel :** il permet une mise a jour efficace de l'interface en
   reduisant les manipulations du DOM reel.

3. **Nature declarative :** on decrit l'apparence de l'interface dans un etat
   donne, et React se charge de la maintenir coherente.

4. **Flux de donnees a sens unique :** les donnees sont transmises du haut vers
   le bas via les props, ce qui facilite la gestion de l'etat.

React a ete cree par Facebook et est largement utilise pour le developpement
des SPA (Single Page Applications).

</details>

<details>
<summary>2. Enumerez les particularites de React.</summary>

#### React

1. **Approche orientee composants :** le code est divise en composants
   independants et reutilisables.

2. **DOM virtuel :** mise a jour rapide de l'interface sans manipulation
   directe du DOM.

3. **Flux de donnees unidirectionnel :** les donnees sont transmises des
   composants parents vers les composants enfants via les props.

4. **JSX :** extension de syntaxe JavaScript permettant d'ecrire l'interface
   sous forme de code proche du XML.

5. **Etat et cycle de vie :** les composants peuvent stocker et gerer leur
   propre etat.

6. **Hooks React :** ils permettent de gerer l'etat et les effets secondaires
   dans les composants fonctionnels.

7. **Ecosysteme :** React prend en charge des bibliotheques telles que React
   Router ou Redux pour etendre les fonctionnalites.

8. **Compatible SEO avec Next.js :** le rendu cote serveur ameliore
   l'indexation.

9. **Developpement mobile :** React Native permet de creer des applications
   mobiles basees sur React.

10. **Open source :** prise en charge active par la communaute.

</details>

<details>
<summary>3. Quelles sont les fonctions principales de React ?</summary>

#### React

#### Fonctions principales de React :

1. **Approche declarative :** React permet de creer une interface interactive
   en decrivant ce qu'elle doit afficher, tandis que la bibliotheque optimise
   elle-meme les mises a jour du DOM.

2. **Structure en composants :** l'application est construite a partir de
   composants independants et reutilisables, ce qui facilite le developpement,
   les tests et la maintenance.

3. **DOM virtuel :** React utilise le DOM virtuel pour mettre a jour
   efficacement le DOM reel, ce qui ameliore nettement les performances.

4. **Flux de donnees unidirectionnel :** les donnees sont transmises des
   composants parents aux composants enfants via les props, ce qui simplifie la
   gestion de l'etat.

5. **Hooks :** ils permettent d'utiliser l'etat et les mecanismes du cycle de
   vie dans les composants fonctionnels.

6. **JSX :** extension de JavaScript permettant de decrire l'interface avec
   une syntaxe proche du HTML.

7. **React Native :** possibilite de creer des applications mobiles natives en
   appliquant les memes principes que pour le web.

8. **Ecosysteme :** vaste ensemble de bibliotheques et d'outils, comme React
   Router, Redux ou Context API.

9. **Prise en charge du rendu cote serveur (SSR) :** permet d'optimiser le SEO
   et d'accelerer le chargement initial des pages.

10. **Gestion de l'etat :** au moyen de `useState`, Context API, Redux ou
    d'autres bibliotheques.

Ces fonctions font de React une bibliotheque puissante et flexible pour creer
des applications modernes.

</details>

<details>
<summary>4. Quels sont les principaux avantages de l'utilisation de React ?</summary>

#### React

#### Principaux avantages de React

1. **Vitesse :** grace au DOM virtuel, React reduit les interactions avec le
   DOM reel, ce qui ameliore les performances.

2. **Approche par composants :** le code est divise en composants
   reutilisables, ce qui simplifie le developpement et la maintenance.

3. **Transmission des donnees dans un seul sens :** les donnees circulent dans
   une seule direction, du haut vers le bas, ce qui facilite le debogage.

4. **Grande communaute :** React dispose d'un vaste ecosysteme de
   bibliotheques, d'outils et d'extensions.

5. **Compatibilite avec le developpement mobile :** avec React Native, il est
   possible de creer des applications mobiles multiplateformes.

6. **JSX :** une syntaxe qui permet d'ecrire JavaScript avec du balisage de
   type HTML, ce qui ameliore la lisibilite du code.

7. **Prise en charge des Hooks :** ils simplifient la gestion de l'etat et du
   cycle de vie dans les composants fonctionnels.

8. **Compatibilite SEO :** le rendu cote serveur avec des outils comme
   Next.js ameliore le referencement.

9. **Souplesse :** React peut etre integre dans n'importe quel projet ou
   framework sans modifications majeures du code.

10. **React DevTools :** outil de debogage pratique pour analyser les
    composants et l'etat de l'application.

</details>

<details>
<summary>5. Qu'est-ce que JSX ?</summary>

#### React

**JSX (JavaScript XML)** est une syntaxe qui permet d'ecrire des structures
d'interface sous forme de code proche du XML a l'interieur de JavaScript. JSX
est une extension de JavaScript utilisee dans React pour decrire l'apparence de
l'interface.

#### Caracteristiques principales de JSX :

1. **Syntaxe proche du XML :** elle ressemble au HTML, mais s'utilise dans
   JavaScript.

```jsx
const element = Hello, world!;
```

2. **JavaScript integre :** il est possible d'ecrire du code JavaScript entre
   accolades `{}`.

```jsx
const name = 'Alice';
const element = Hello, {name}!;
```

3. **Compilation :** JSX est compile en JavaScript classique a l'aide
   d'outils comme Babel.

```jsx
const element = Hello;
// Est transforme en :
const element = React.createElement('h1', null, 'Hello');
```

4. **Attributs :** ils s'utilisent comme en HTML, mais on ecrit `className`
   au lieu de `class`, et `htmlFor` au lieu de `for`.

```jsx
const input = ;
```

5. **JSX retourne un arbre d'elements :** une expression JSX ne peut retourner
   qu'un seul element racine. Pour grouper plusieurs elements, on utilise
   `<React.Fragment>` ou les balises vides `<>`.

```jsx
return <>Title Description</>;
```

#### Avantages :

- Creation pratique de composants d'interface.
- Syntaxe claire et lisible.
- Integration etroite avec la logique JavaScript.

JSX n'est pas obligatoire dans React, mais il est largement utilise pour sa
commodite et sa souplesse.

</details>

<details>
<summary>6. Quelle est la difference entre l'etat (state) et les props ?</summary>

#### React

#### Difference entre l'etat (state) et les props

| Critere | State | Props |
| ------- | ----- | ----- |
| **Role** | Stocke l'etat interne du composant. | Transmet des donnees du composant parent au composant enfant. |
| **Mutabilite** | Peut etre modifie a l'interieur du composant. | Est immuable en lecture seule. |
| **Disponibilite** | Disponible uniquement dans le composant ou il est defini. | Disponible dans le composant enfant via ses attributs. |
| **Initialisation** | Est defini dans le composant via `useState` ou le constructeur. | Est defini par le composant parent. |
| **Usage** | Sert a stocker des donnees dynamiques susceptibles de changer. | Sert a transmettre des donnees fixes ou dynamiques. |
| **Qui le controle ?** | Le composant dans lequel le state est defini. | Le composant parent. |

</details>

<details>
<summary>7. Quelle est la difference entre un element et un composant ?</summary>

#### React

#### Difference entre un element et un composant dans React :

| Critere | Element | Composant |
| ------- | ------- | ---------- |
| **Definition** | Objet qui decrit l'apparence de l'interface. | Fonction ou classe qui retourne des elements React. |
| **Type** | Immuable. | Reutilisable et peut posseder un etat. |
| **Syntaxe de creation** | `React.createElement` ou JSX (`<div />`). | Fonction ou classe (`function MyComponent() {}` ou `class MyComponent extends React.Component {}`). |
| **Role** | Represente un noeud unique dans le DOM. | Encapsule la logique et la structure de l'interface. |
| **Utilisation** | Sert a creer l'interface au niveau de base. | Sert a construire des structures plus complexes avec logique metier. |
| **Exemple** | `<h1>Hello</h1>` | `function Hello() { return <h1>Hello</h1>; }` |

L'element est un "bloc de construction", tandis que le composant est un
"constructeur" servant a creer des interfaces plus complexes.

</details>

<details>
<summary>8. Comment creer des composants dans React ?</summary>

#### React

#### Dans React, les composants peuvent etre crees de deux manieres :

1. **Composant fonctionnel :** c'est une fonction simple qui retourne des
   elements React.

```jsx
function Greeting(props) {
  return Hello, {props.name}!;
}

// Utilisation :
;
```

2. **Composant de classe :** c'est une classe qui herite de `React.Component`
   et qui doit obligatoirement contenir une methode `render`.

```jsx
class Greeting extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Utilisation :
;
```

#### Differences :

- Les composants fonctionnels sont plus simples et conviennent mieux aux
  composants sans etat.

- Les composants de classe sont utilises pour des composants plus complexes
  ayant leur propre etat ou des methodes de cycle de vie.

**Remarque :** l'approche moderne privilegie les composants fonctionnels avec
Hooks plutot que les composants de classe.

</details>

<details>
<summary>9. Qu'est-ce que l'etat (state) dans React ?</summary>

#### React

**L'etat (state)** dans React est un objet utilise pour stocker des donnees
qui peuvent changer avec le temps et influencent le rendu du composant. L'etat
permet aux composants React d'etre dynamiques et de reagir aux evenements, aux
entrees utilisateur, etc.

#### Caracteristiques de l'etat :

1. **Local au composant :** l'etat n'est disponible que dans le composant ou
   il est defini.

2. **Change de maniere asynchrone :** React regroupe les appels a `setState`
   pour optimiser le rendu.

3. **Est initialise dans le constructeur** pour les composants de classe ou via
   `useState` pour les composants fonctionnels.

#### Dans les composants de classe :

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

#### Dans les composants fonctionnels avec le Hook `useState` :

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

#### Principales differences entre l'etat et les props :

- **State** est local au composant et peut changer.

- **Props** sont transmises de l'exterieur et sont immuables.

</details>

<details>
<summary>10. Que sont les props dans React ?</summary>

#### React

**Les props** dans React sont un objet contenant les donnees transmises du
composant parent au composant enfant. Elles servent a configurer les composants
et sont immuables.

#### Caracteristiques des props :

1. **Sont transmises du haut vers le bas** selon un flux de donnees
   unidirectionnel, du composant parent au composant enfant.

2. **Sont immuables :** un composant ne peut pas modifier les props recues.

3. **Sont dynamiques :** leurs valeurs peuvent changer si les donnees du
   composant parent changent.

#### Utilisation des props :

1. **Dans un composant fonctionnel :**

```jsx
function Welcome(props) {
  return Hello, {props.name}!;
}

// Utilisation :
;
```

2. **Dans un composant de classe :**

```jsx
class Welcome extends React.Component {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Utilisation :
;
```

#### Transmission des props :

```jsx
function App() {
  return (

  );
}
```

**Resultat :**

```bash
Hello, Alice!
Hello, Bob!
```

#### Destructuration des props :

```jsx
function Welcome({ name }) {
  return Hello, {name}!;
}
```

#### Valeurs par defaut des props :

```jsx
function Welcome({ name = 'Guest' }) {
  return Hello, {name}!;
}

// Utilisation :
; // Affichera : Hello, Guest!
```

Les props donnent aux composants React de la souplesse et un fort potentiel de
reutilisation.

</details>

<details>
<summary>11. A quoi sert l'attribut `key` lors du rendu des listes ?</summary>

#### React

L'attribut `key` est utilise pour identifier les elements dans les listes lors
du rendu.

#### Role :

1. **_Optimisation des mises a jour :_** React utilise `key` pour mettre a jour
   l'interface plus efficacement, en identifiant rapidement les elements a
   modifier, ajouter ou supprimer.

2. **_Prevention des rendus inutiles :_** `key` aide a eviter le re-rendu des
   elements qui n'ont pas change.

3. **_Conservation de l'etat des composants :_** par exemple, si un element de
   liste contient un formulaire, `key` permet a React d'en conserver l'etat
   entre les mises a jour.

#### Utilisation correcte :

- La valeur de `key` doit etre unique parmi les elements au meme niveau.

- Il est preferable d'utiliser des identifiants stables, par exemple un `id`
  provenant d'une base de donnees.

- Il n'est pas recommande d'utiliser l'index d'un tableau comme `key`, car
  cela peut provoquer des erreurs lorsque l'ordre des elements change.

```jsx
const items = ['Apple', 'Banana', 'Cherry'];
return (

    {items.map((item, index) => (
      {item} // Key unique pour chaque element
    ))}

);
```

</details>

<details>
<summary>12. Comment les donnees sont-elles transmises entre les composants dans React ?</summary>

#### React

Dans React, les donnees sont transmises entre les composants selon la
hierarchie, de la maniere suivante :

#### Transmission des donnees vers le bas, du composant parent au composant enfant

Pour transmettre des donnees vers le bas, on utilise les props. Le composant
parent transmet des valeurs ou des fonctions au composant enfant via des
attributs.

**Exemple :**

```jsx
function ParentComponent() {
  const data = 'Hello from Parent';

  return;
}

function ChildComponent({ message }) {
  return { message };
}
```

`message` transmet la valeur `data` au composant enfant `ChildComponent`.

Dans le composant enfant, les props sont accessibles via les parametres de la
fonction ou via `this.props` dans un composant de classe.

#### Transmission des donnees vers le haut, du composant enfant au composant parent

Les donnees sont transmises vers le haut a l'aide de fonctions de rappel. Le
composant parent transmet une fonction au composant enfant, qui l'appelle avec
les donnees necessaires.

**Exemple :**

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

Le composant parent transmet la fonction `handleData` via la prop `sendData`.

Le composant enfant appelle `sendData` en lui transmettant la valeur `data`.

#### Approches alternatives pour les applications complexes :

1. **Context (Context API) :**

Pour transmettre des donnees en profondeur dans la hierarchie sans passer par
les props.

Convient a l'etat global, par exemple un theme ou la langue de l'interface.

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

2. **Gestionnaires d'etat comme Redux, Zustand ou MobX :** pour transmettre
   des donnees dans de grandes applications via un etat global unique.

3. **Hooks personnalises :** utilises pour partager de la logique entre les
   composants.

</details>

<details>
<summary>13. Pourquoi React utilise-t-il `className` au lieu de l'attribut `class` ?</summary>

#### React

Dans React, on utilise `className` au lieu de `class`, car `class` est un mot
cle reserve en JavaScript.

#### Raisons :

1. **Eviter les conflits :** `class` est utilise en JavaScript pour definir
   des classes, par exemple `class MyComponent {}`, ce qui pourrait provoquer
   des erreurs de syntaxe.

2. **Compatibilite avec JSX :** JSX est une extension syntaxique de
   JavaScript, et l'utilisation de `className` permet d'eviter les
   ambiguities.

3. **Correspondance directe avec `document.createElement` :** React transforme
   le JSX en appels `React.createElement`, et `className` est utilise pour
   definir les classes sur les elements du DOM.

#### Exemple :

```jsx
// Variante correcte dans React

Hello;

// Variante incorrecte, provoquant une erreur de syntaxe

Hello;
```

C'est une convention standard de React qui garantit la stabilite et la
coherence du code.

</details>

<details>
<summary>14. Quelles sont les regles et exceptions pour nommer les composants React ?</summary>

#### React

Dans React, il existe plusieurs regles et particularites importantes concernant
le nommage des composants :

1. **Majuscule initiale pour les composants :** les noms de composants doivent
   commencer par une majuscule. C'est indispensable pour que React puisse les
   distinguer des elements HTML standards.

Par exemple :

- Correct : `<MyComponent />`
- Incorrect : `<myComponent />`

2. **CamelCase :** il est recommande d'utiliser le style CamelCase pour les
   noms de composants, c'est-a-dire que chaque nouveau mot commence par une
   majuscule :

- `MyComponent`
- `UserProfile`

3. **Les noms ne doivent pas coincider avec des elements HTML :** il ne faut
   pas utiliser des noms identiques a ceux des balises HTML standards comme
   `div`, `span` ou `button`, car cela peut creer des conflits et un
   comportement inattendu :

- Correct : `<CustomButton />`
- Incorrect : `<button />`, car React l'interprete comme une balise HTML
  classique

4. **Eviter les caracteres speciaux :** n'utilisez pas de caracteres speciaux
   dans les noms de composants, comme les espaces, tirets ou underscores, car
   cela peut entrainer des erreurs de syntaxe :

- Correct : `MyComponent`
- Incorrect : `my_component`, `my-component`

5. **Composants fonctionnels et composants de classe :** si vous utilisez des
   classes pour vos composants, leurs noms doivent egalement commencer par une
   majuscule :

- `class MyComponent extends React.Component {}`

Le respect de ces regles contribue au bon fonctionnement du code et a sa
lisibilite.

</details>

<details>
<summary>15. Comment ecrire des commentaires dans React ?</summary>

#### React

Dans React, les commentaires s'ecrivent comme en JavaScript, mais il existe
quelques particularites lorsqu'il s'agit de JSX.

1. **Commentaires en JavaScript, en dehors de JSX**

```javascript
// Commentaire sur une ligne

/*
Commentaire multiligne
*/
```

2. **Commentaires a l'interieur de JSX**

- Dans JSX, il faut utiliser une syntaxe speciale, puisque JSX fait partie de
  JavaScript.

- Les commentaires dans JSX doivent etre ecrits a l'interieur d'accolades
  `{}` :

```jsx
function MyComponent() {
  return (

      {/_ Ceci est un commentaire dans JSX _/}
      Hello, world!

  );
}
```

- Les commentaires dans JSX doivent avoir la forme `{/* commentaire */}`,
  sinon ils provoquent des erreurs.

- Ils ne peuvent etre utilises qu'a l'interieur d'expressions JSX.

3. **Commentaires dans les fonctions et les methodes**

- A l'interieur des fonctions ou des methodes, on peut utiliser les
  commentaires JavaScript standards :

```jsx
function MyComponent() {
  // Ici nous rendons le composant
  return Hello, world!;
}
```

#### Conclusion :

- Dans JSX, utilisez `{/* commentaire */}`.

- En JavaScript classique, utilisez `//` pour les commentaires sur une ligne
  et `/* ... */` pour les commentaires multilignes.

</details>

<details>
<summary>16. Qu'est-ce que le DOM virtuel dans React ?</summary>

#### React

Le **DOM virtuel** est une representation virtuelle du DOM reel que React
utilise pour mettre a jour l'interface de maniere efficace.

#### Comment cela fonctionne dans React :

1. **Rendu dans le DOM virtuel :** lorsque l'etat ou les props d'un composant
   changent, React met a jour le DOM virtuel.

2. **Diffing :** React compare le nouveau DOM virtuel a l'ancienne version afin
   de determiner l'ensemble minimal de changements.

3. **Mise a jour du DOM reel :** les changements detectes sont appliques au DOM
   reel, ce qui reduit au minimum le nombre de manipulations.

#### Principal avantage :

L'optimisation des mises a jour du DOM ameliore nettement les performances des
applications.

</details>

<details>
<summary>17. Qu'est-ce que la prop `key` et quel est l'avantage de son utilisation dans les tableaux d'elements ?</summary>

#### React

Dans React, la prop `key` sert a identifier chaque element dans une liste ou un
tableau afin d'aider React a gerer efficacement les rendus lorsque la liste est
modifiee ou mise a jour. C'est essentiel pour optimiser le rendu, en
particulier lorsque des elements sont ajoutes, supprimes ou reordonnes.

#### Points essentiels concernant `key` :

1. **Unicite :** chaque element d'une liste doit avoir une `key` unique. Cela
   permet a React de suivre les elements modifies, ajoutes ou supprimes, ainsi
   que de conserver leur etat entre les rendus.

2. **Optimisation du rendu :** l'utilisation de `key` permet a React de
   minimiser le nombre de re-rendus en effectuant uniquement les changements
   necessaires dans le DOM. Sans `key`, React a plus de difficulte a suivre les
   modifications, ce qui peut entrainer un re-rendu complet de la liste, meme
   si un seul element a change.

3. **Nature de `key` :** la prop `key` n'est pas transmise au composant, on ne
   peut donc pas l'utiliser pour l'affichage dans l'interface. C'est une
   propriete interne utilisee par React pour suivre les elements.

#### Exemple d'utilisation de `key` dans une liste :

```jsx
const items = ['apple', 'banana', 'cherry'];

function FruitList() {
  return (

      {items.map((item, index) => (
        {item} // Important : utiliser une key unique
      ))}

  );
}
```

#### Importance de l'unicite de `key` :

- **Mauvaise utilisation :** si des valeurs non uniques sont utilisees comme
  `key`, par exemple le meme index, React ne pourra pas suivre correctement les
  changements, ce qui provoquera des erreurs de rendu.

- **Key ideale :** si un element possede un identifiant unique, par exemple un
  `id`, celui-ci doit etre utilise comme `key` a la place de l'index du
  tableau.

```jsx
const items = [
  { id: 1, name: 'apple' },
  { id: 2, name: 'banana' },
  { id: 3, name: 'cherry' },
];

function FruitList() {
  return (

      {items.map(item => (
        {item.name} // Mieux vaut utiliser des id uniques
      ))}

  );
}
```

#### Avantages de l'utilisation de `key` :

- Ameliore les performances du rendu.

- Permet a React de mettre a jour uniquement les elements modifies au lieu de
  rerendre toute la liste.

- Garantit une bonne gestion de l'etat des elements lorsqu'ils sont deplaces,
  supprimes ou mis a jour.

Ainsi, l'utilisation de `key` est essentielle pour travailler efficacement avec
des tableaux d'elements dans React.

</details>

<details>
<summary>18. Qu'est-ce que le rendu conditionnel dans React ?</summary>

#### React

Le rendu conditionnel dans React est un mecanisme par lequel un composant
affiche un contenu different selon certaines conditions. Cela permet de faire
varier dynamiquement l'affichage en fonction de l'etat, des props ou d'autres
facteurs.

#### Principales approches du rendu conditionnel :

1. **Instruction `if` :** on peut utiliser l'instruction `if` classique pour
   decider quoi rendre.

```jsx
function Greeting(props) {
  if (props.isLoggedIn) {
    return Welcome back!;
  }
  return Please sign up.;
}
```

2. **Operateur ternaire :** il est souvent employe pour des expressions
   conditionnelles plus courtes.

```jsx
function Greeting(props) {
  return {props.isLoggedIn ? 'Welcome back!' : 'Please sign up.'};
}
```

3. **Operateur logique ET (`&&`) :** on peut l'utiliser pour rendre un element
   uniquement si l'expression a gauche est vraie.

```jsx
function Notifications(props) {
  return (

      {props.unreadMessages.length > 0 && (
        You have {props.unreadMessages.length} unread messages.
      )}

  );
}
```

Cela fonctionne ainsi : si `props.unreadMessages.length` est superieur a 0, le
message est affiche, sinon rien n'est rendu.

4. **Utilisation de `return` avec un operateur conditionnel :** il est possible
   d'utiliser `return` pour faire du rendu conditionnel, comme dans les
   exemples avec `if` ou l'operateur ternaire.

#### Avantages du rendu conditionnel :

- Permet de modifier dynamiquement le contenu en fonction de l'etat ou des
  props.

- Ameliore la souplesse et permet d'afficher un contenu different selon les
  utilisateurs ou les situations.

#### Exemple :

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

Ici, le bouton change selon que l'utilisateur est connecte ou non.

</details>

<details>
<summary>19. Que sont les fragments dans React ?</summary>

#### React

Les fragments dans React sont un moyen de regrouper plusieurs elements sans
ajouter d'elements inutiles au DOM. Ils permettent de retourner plusieurs
elements depuis un composant sans les envelopper dans un `div`, ce qui aide a
eviter des noeuds supplementaires susceptibles de perturber les styles ou la
structure du document.

#### Comment les fragments sont-ils utilises ?

1. **Sans fragment, avec un conteneur :**

```jsx
function MyComponent() {
  return (

      Title
      Some text

  );
}
```

Dans cet exemple, un seul `div` est retourne et enveloppe `h1` et `p`.

2. **Avec des fragments, sans conteneur :**

```jsx
function MyComponent() {
  return <>Title Some text</>;
}
```

Cette fois, `h1` et `p` sont rendus sans conteneur supplementaire, ce qui
permet de garder un DOM plus propre.

#### Avantages :

- **DOM plus propre :** on peut eviter les wrappers inutiles dans le DOM.

- **Praticite pour rendre plusieurs elements :** on peut retourner plusieurs
  elements depuis un meme composant sans devoir ajouter d'elements
  supplementaires.

#### Syntaxe :

- On peut utiliser les balises vides `<>` et `</>`, qui sont une forme abregee
  de `<React.Fragment></React.Fragment>`.

- On peut aussi utiliser `React.Fragment` lorsqu'il faut ajouter des cles, par
  exemple lors du rendu de listes :

```jsx
{
  item.name;
}
{
  item.description;
}
```

#### Quand les utiliser ?

- Lorsqu'il faut rendre plusieurs elements sans wrapper supplementaire dans le
  DOM.

- Lorsqu'on souhaite conserver la structure du composant sans perturber les
  styles ni la mise en page.

Les fragments sont tres utiles pour reduire le nombre d'elements inutiles dans
le DOM et ameliorer les performances.

</details>

<details>
<summary>20. Qu'est-ce que la reconciliation ?</summary>

#### React

La **reconciliation** est le processus utilise par React pour mettre a jour le
DOM de la maniere la plus efficace possible. Lorsque l'etat ou les props d'un
composant changent, React calcule les modifications minimales a apporter au DOM
reel afin de le synchroniser avec le DOM virtuel.

#### Comment fonctionne la reconciliation ?

1. **Comparaison de l'ancien et du nouveau DOM virtuel :**

- React conserve une copie du DOM virtuel precedent.
- Lorsqu'un state ou des props changent, un nouveau DOM virtuel est cree.
- React compare ce nouveau DOM virtuel avec la copie precedente en utilisant un
  algorithme de diffing.

2. **Detection des differences, ou diffing :**

- React identifie les parties de l'arbre qui ont change, par exemple de
  nouveaux elements, des modifications d'attributs ou des suppressions.
- Pour cela, il utilise un algorithme optimise pour les structures en arbre.

3. **Mise a jour du DOM reel :**

- React applique les changements uniquement aux parties du DOM qui doivent etre
  mises a jour, en evitant un re-rendu complet.

#### Principes fondamentaux de la reconciliation :

- **Conservation des noeuds du meme type :** si des noeuds ont le meme type,
  par exemple `<div>` reste `<div>`, React modifie seulement les attributs et
  les enfants.
- **Reutilisation des composants :** si un composant reste le meme, React
  reutilise l'instance existante.
- **Cles dans les listes :** lorsqu'une liste est rendue a partir d'un tableau,
  React utilise les cles `key` pour comparer et conserver les noeuds.

#### Exemple :

```jsx
function App({ isVisible }) {
  return isVisible ? Hello : Goodbye;
}
```

- Si `isVisible` passe de `true` a `false`, React supprimera `<h1>` et le
  remplacera par `<p>`.

#### Importance des cles `key` dans les listes :

Les cles aident React a identifier correctement les changements dans les
listes. Par exemple :

```jsx

  {items.map(item => (
    {item.text}
  ))}

```

Sans cles uniques, React ne pourra pas determiner precisement quels elements de
la liste ont change.

#### Avantages de la reconciliation :

- Reduction du nombre d'operations sur le DOM.
- Amelioration des performances des applications.
- Mise a jour fluide de l'interface utilisateur.

</details>

<details>
<summary>21. Comment mettre a jour l'etat d'un composant ?</summary>

#### React

Dans React, l'etat d'un composant est mis a jour a l'aide de la methode
`setState` dans les composants de classe ou de `useState` dans les composants
fonctionnels.

#### Composants de classe :

L'etat est mis a jour via `this.setState()`.

#### Exemple :

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

#### Composants fonctionnels :

L'etat est mis a jour via la fonction obtenue avec `useState`.

#### Exemple :

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

#### Remarques :

1. **Asynchronisme :** `setState` et `useState` fonctionnent de maniere
   asynchrone. Pour mettre a jour l'etat a partir de la valeur precedente,
   utilisez l'approche fonctionnelle :

```jsx
this.setState(prevState => ({ count: prevState.count + 1 }));
setCount(prevCount => prevCount + 1);
```

2. **Ne mettez pas l'etat a jour directement :** modifier l'etat sans utiliser
   `setState` ou `useState` ne declenche pas un nouveau rendu.

</details>

<details>
<summary>22. Que sont les expressions conditionnelles integrees ?</summary>

#### React

Les **expressions conditionnelles integrees** en JavaScript, notamment dans
React, sont des mecanismes qui permettent d'inserer des conditions directement
dans le JSX afin d'effectuer un rendu conditionnel d'elements ou de composants.
Cela rend le code plus compact et plus facile a comprendre.

#### Methodes principales :

1. **Operateur conditionnel (operateur ternaire) :** c'est l'une des methodes
   les plus courantes pour effectuer un rendu conditionnel dans JSX. Sa syntaxe
   est la suivante :

```jsx
condition ? expression_si_vrai : expression_si_faux;
```

**Exemple :**

```jsx
const isLoggedIn = true;

function App() {
  return {isLoggedIn ? Welcome, User! : Please log in};
}
```

2. **Operateur logique AND (&&) :** cette methode permet d'afficher un
   composant ou un element uniquement lorsque la condition est vraie. Si la
   condition n'est pas remplie, rien n'est rendu.

**Exemple :**

```jsx
const isUserAdmin = true;

function App() {
  return {isUserAdmin && You have admin privileges};
}
```

Dans ce cas, `<p>You have admin privileges</p>` sera affiche uniquement si
`isUserAdmin` vaut `true`.

3. **IF avant le retour du JSX :** on peut aussi utiliser les instructions `if`
   classiques avant de retourner le JSX, lorsque la condition est plus complexe
   ou lorsqu'il faut effectuer plusieurs actions conditionnelles.

**Exemple :**

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

**Avantages :**

- Les expressions conditionnelles integrees permettent d'ecrire un code plus
  propre et plus compact.

- Elles ameliorent la lisibilite et reduisent le recours a des structures
  conditionnelles supplementaires.

#### Important :

- Dans React, on ne peut pas utiliser directement les instructions `if` a
  l'interieur du JSX. En revanche, on peut les utiliser avant le retour du JSX.

</details>

<details>
<summary>23. Quelle est la difference entre la gestion des evenements en HTML et en React ?</summary>

#### React

#### Difference entre la gestion des evenements en HTML et en React :

| Critere | HTML | React |
| ------- | ---- | ----- |
| **Association de l'evenement** | Definie comme attribut : `<button onclick="handler()">`. | Utilise la notation camelCase : `<button onClick={handler}>`. |
| **Type de fonction** | Reference vers une fonction globale ou chaine de code JavaScript. | Liaison a une fonction du composant, generalement une methode ou une fonction flechee. |
| **Ajout des ecouteurs** | Les gestionnaires sont ajoutes manuellement via `addEventListener`. | React gere automatiquement la liaison via le DOM virtuel. |
| **Contexte `this`** | Le contexte doit etre defini manuellement dans les classes. | Dans les composants fonctionnels, ce probleme n'existe pas ; dans les classes, il faut encore le gerer. |
| **Comportement par defaut** | Il faut souvent utiliser explicitement `return false` pour l'empecher. | On utilise `event.preventDefault()` pour bloquer le comportement par defaut. |
| **Compatibilite** | Gere uniquement les evenements DOM natifs. | Utilise `SyntheticEvent`, une surcouche sur les evenements natifs. |
| **Compatibilite inter-navigateurs** | Les differences entre navigateurs doivent etre gerees manuellement. | React assure cette compatibilite via `SyntheticEvent`. |
| **Liaison du contexte** | Exige souvent `bind`. | Dans les composants de classe, `bind` peut etre necessaire ; dans les composants fonctionnels, non. |

#### Exemple en HTML :

```html
Click me
```

#### Exemple en React :

```jsx
function handleClick() {
  alert('Clicked!');
}

function App() {
  return Click me;
}
```

#### SyntheticEvent dans React :

React utilise une surcouche sur les evenements natifs qui normalise leur
comportement entre les differents navigateurs et ameliore la coherence.

</details>

<details>
<summary>24. Que sont les evenements synthetiques dans React ?</summary>

#### React

Les **evenements synthetiques (Synthetic Events)** dans React sont des
surcouches des evenements DOM natifs, fournissant une interface uniforme pour
leur gestion dans differents navigateurs. React cree un `SyntheticEvent` pour
chaque evenement, ce qui permet de manipuler les evenements de maniere unifiee,
avec une meilleure compatibilite inter-navigateurs et de bonnes performances.

#### Caracteristiques principales :

1. **Compatibilite inter-navigateurs :** `SyntheticEvent` abstrait les
   particularites de gestion des evenements selon les navigateurs et garantit
   un comportement uniforme.

2. **Optimisation :** `SyntheticEvent` utilisait historiquement un pool
   d'objets, ce qui reduisait le cout de creation de nouveaux objets
   evenementiels.

3. **Usage controle :** l'objet `SyntheticEvent` doit etre traite au bon
   moment. Pour des operations asynchrones, il est plus sur d'extraire les
   donnees necessaires dans une variable separee.

4. **Interface :** `SyntheticEvent` expose les memes methodes que les
   evenements natifs standards, par exemple `preventDefault()` et
   `stopPropagation()`.

#### Exemple d'utilisation :

```jsx
function handleClick(event) {
  // SyntheticEvent donne acces a la methode preventDefault()
  event.preventDefault();
  console.log('Button clicked!');
}

function App() {
  return Click me;
}
```

Dans cet exemple, `event` est un `SyntheticEvent` qui fonctionne de maniere
similaire a un evenement natif, mais avec une interface unifiee.

</details>

<details>
<summary>25. Comment gerer les evenements dans React ?</summary>

#### React

Dans React, la gestion des evenements fonctionne de maniere proche du
JavaScript standard, avec quelques differences. Les evenements y sont
synthetiques, c'est-a-dire qu'ils fournissent une abstraction par-dessus les
evenements reels du navigateur, ce qui assure une compatibilite
inter-navigateurs.

#### Principes de base de la gestion des evenements dans React :

1. **Evenements synthetiques :** tous les evenements dans React sont enveloppes
   dans un objet **SyntheticEvent**, qui constitue une implementation
   inter-navigateurs des evenements DOM standards. Cela permet de les gerer de
   la meme facon dans tous les navigateurs.

2. **Utilisation du camelCase :** dans React, les evenements s'ecrivent en
   camelCase plutot qu'en minuscules, par exemple `onClick` au lieu de
   `onclick`.

3. **Passage de fonctions comme gestionnaires :** les evenements dans React
   sont geres par des fonctions passees via les attributs des composants.

#### Exemple de gestion de l'evenement `click` :

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

#### Exemple avec un composant fonctionnel :

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

#### Particularites :

1. **Il n'est pas necessaire d'utiliser `addEventListener` :** dans React, il
   n'est pas utile d'ajouter ou de supprimer les gestionnaires manuellement.
   La bibliotheque s'en charge automatiquement.

2. **Conservation du contexte dans les composants de classe :** si les methodes
   d'un composant de classe sont utilisees comme gestionnaires, le contexte
   (`this`) doit etre lie, soit avec des fonctions flechees, soit manuellement
   dans le constructeur.

```jsx
class MyComponent extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
    // Liaison de la methode
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

3. **Passage de parametres :** si des arguments supplementaires doivent etre
   transmis au gestionnaire, on peut utiliser des fonctions flechees ou des
   fonctions parametrees.

```jsx
function MyButton({ label }) {
  const handleClick = (event, label) => {
    console.log(label);
  };

  return <button onClick={event => handleClick(event, label)}>{label};
}
```

#### Gestion des evenements dans le DOM :

Tous les evenements dans React reposent sur la delegation d'evenements : un
gestionnaire central est enregistre pour l'ensemble de l'arbre des composants,
puis les evenements sont traites via `SyntheticEvent`.

</details>

<details>
<summary>26. Que sont les evenements de pointeur (Pointer Events) ?</summary>

#### React

#### Evenements de pointeur (Pointer Events) dans React

Les **Pointer Events** sont une API qui unifie les evenements de souris,
d'ecran tactile et de stylet au sein d'un seul systeme de gestion.

#### Principaux Pointer Events

| **Evenement** | **Description** |
| ------------- | --------------- |
| **onPointerDown** | Se declenche lors d'un appui avec le doigt, la souris ou le stylet. |
| **onPointerUp** | Se declenche lors du relachement du bouton de la souris, du doigt ou du stylet. |
| **onPointerMove** | Est appele lorsque le pointeur se deplace au-dessus de l'element. |
| **onPointerEnter** | Se declenche lorsque le pointeur entre dans les limites de l'element. |
| **onPointerLeave** | Se declenche lorsque le pointeur quitte les limites de l'element. |
| **onPointerCancel** | Est appele lorsque le navigateur annule l'evenement, par exemple lors d'un changement de focus. |

#### Exemple d'utilisation dans React

```jsx
const PointerExample = () => {
  const handlePointerDown = () => console.log('Pointeur active');

  return (

      Cliquez ici

  );
};
```

Ce code affichera `"Pointeur active"` dans la console lors d'un appui avec
n'importe quel dispositif, qu'il s'agisse d'une souris, d'un ecran tactile ou
d'un stylet.

</details>

<details>
<summary>27. Quand utiliser un composant de classe au lieu d'un composant fonctionnel ?</summary>

#### React

Les composants de classe etaient utilises lorsqu'une ou plusieurs des
fonctionnalites suivantes etaient necessaires :

1. **Gestion de l'etat (`state`) :** auparavant, les composants fonctionnels ne
   prenaient pas en charge l'etat local, donc on utilisait des classes pour
   cela. Aujourd'hui, les hooks (`useState`, `useReducer`) permettent aux
   composants fonctionnels de gerer l'etat.

2. **Methodes de cycle de vie :** les classes donnaient acces a des methodes
   comme `componentDidMount`, `componentDidUpdate` et `componentWillUnmount`
   pour gerer le composant a differentes etapes de son existence. Aujourd'hui,
   cela est pris en charge par le hook `useEffect`.

3. **Gestion d'une logique complexe :** si la logique necessitait plusieurs
   methodes et un acces aux proprietes via `this`, les classes semblaient etre
   un choix naturel. L'approche moderne repose sur les hooks, qui permettent
   d'encapsuler cette logique.

#### Quand les classes ne sont plus necessaires :

Depuis React 16.8, les composants fonctionnels avec hooks ont largement remplace
le besoin des composants de classe. Dans les nouveaux projets, il vaut donc
mieux privilegier les composants fonctionnels. Les classes sont surtout
conservees pour maintenir du code ancien.

</details>

<details>
<summary>28. Que sont les composants sans etat (stateless components) ?</summary>

#### React

Les composants sans etat (`stateless components`) sont des composants qui ne
stockent ni ne gerent aucun etat interne. Ils se contentent de recevoir des
donnees via les props et de les afficher dans l'interface. En general, ce sont
des composants fonctionnels.

#### Caracteristiques :

1. **Absence d'etat :** ils n'utilisent pas `this.state` et ne modifient pas
   leur etat interne.

2. **Rendu uniquement :** ils recoivent simplement des props et les affichent
   sous forme d'elements d'interface.

3. **Simplicite et previsibilite :** ils sont plus faciles a tester et a
   maintenir, puisqu'il n'y a pas de changements d'etat a suivre.

#### Exemple :

```jsx
// Stateless component
function Greeting(props) {
  return Hello, {props.name}!;
}

// Utilisation :
;
```

#### Avantages :

- **Simplicite :** plus faciles a comprendre et a maintenir.

- **Optimisation des performances :** comme ces composants n'ont pas d'etat,
  React peut les mettre a jour plus efficacement.

#### Quand les utiliser :

- Lorsqu'un composant se contente d'afficher des donnees et n'a pas besoin de
  changer.

</details>

<details>
<summary>29. Que sont les composants avec etat (stateful components) ?</summary>

#### React

Les **composants avec etat** (`stateful components`) sont des composants qui
stockent et gerent leur etat interne. Ils utilisent le `state` pour conserver
des donnees susceptibles d'evoluer dans le temps, et ces changements influent
sur le rendu du composant.

#### Caracteristiques :

1. **Etat (`state`) :** ils utilisent `this.state` pour stocker et gerer des
   donnees susceptibles de changer.

2. **Methodes de mise a jour :** ils utilisent `this.setState()` pour mettre a
   jour l'etat.

3. **Cycle de vie :** ils ont acces aux methodes du cycle de vie du composant,
   comme `componentDidMount()`, `shouldComponentUpdate()` et
   `componentDidUpdate()`.

#### Exemple :

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

#### Avantages :

- **Composants dynamiques :** ils peuvent modifier leur contenu et leur aspect
  en fonction des changements d'etat.

- **Interactivite :** ils conviennent a la creation d'interfaces interactives,
  ou l'etat doit etre mis a jour lors des interactions de l'utilisateur.

#### Quand les utiliser :

Lorsqu'un composant doit gerer un etat interne, par exemple pour conserver des
donnees saisies dans un formulaire, un compteur, une selection, etc.

</details>

<details>
<summary>30. Que sont les composants purs (Pure Components) ?</summary>

#### React

Les **composants purs (Pure Components)** sont des composants de classe React
speciaux qui optimisent automatiquement le rendu. Ils effectuent une comparaison
superficielle des props et de l'etat afin d'eviter des mises a jour inutiles
lorsque leurs valeurs n'ont pas change.

#### Comment creer un composant pur ?

Un composant pur est cree en heritant de `React.PureComponent`.

```jsx
import React, { PureComponent } from 'react';

class MyComponent extends PureComponent {
  render() {
    return Hello, {this.props.name}!;
  }
}

// Utilisation :
;
```

#### Comment fonctionne `PureComponent` ?

- Il effectue une comparaison superficielle (`shallow comparison`) des props et
  de l'etat dans `shouldComponentUpdate`.

- Si les props et l'etat n'ont pas change, le composant n'est pas rerendu.

#### Quand utiliser `PureComponent` ?

- Lorsque les props et l'etat sont des structures simples, par exemple des
  valeurs primitives ou des objets peu imbriques.

- Pour ameliorer les performances des composants qui se mettent souvent a jour.

#### Limitations :

1. **Comparaison profonde :** `PureComponent` ne prend pas en compte les
   changements a l'interieur des objets ou tableaux imbriques. Par exemple, si
   vous mettez a jour un objet mais que sa reference reste inchangée, le
   composant ne sera pas mis a jour.

```jsx
this.setState({ data: { ...this.state.data, key: 'new value' } }); // Contournement
```

2. **Ne fonctionne pas avec les composants fonctionnels :** l'alternative
   consiste a utiliser `React.memo` pour optimiser les composants fonctionnels.

```jsx
const MyComponent = React.memo(function MyComponent(props) {
  return Hello, {props.name}!;
});
```

</details>

<details>
<summary>31. Que sont les composants d'ordre superieur (Higher-Order Components) ?</summary>

#### React

Un **composant d'ordre superieur** est une fonction qui prend un composant en
argument et retourne un nouveau composant, en etendant ses fonctionnalites.

#### Syntaxe d'un HOC :

```jsx
const EnhancedComponent = higherOrderComponent(WrappedComponent);
```

#### Caracteristiques des HOC :

1. **Il prend un composant en argument.**
2. **Il retourne un nouveau composant avec des props ou un comportement
   supplementaires.**
3. **Il permet de reutiliser la logique dans plusieurs composants.**

#### Exemple d'utilisation :

HOC ajoutant une logique d'etat a un composant :

```jsx
import React, { useState } from 'react';

// HOC : ajoute une logique d'etat
function withCounter(WrappedComponent) {
  return function EnhancedComponent(props) {
    const [count, setCount] = useState(0);

    const increment = () => setCount(count + 1);

    return ;
  };
}

// Composant qui sera etendu
function Button({ count, increment }) {
  return Clicked {count} times;
}

// Utilisation du HOC
const EnhancedButton = withCounter(Button);

export default EnhancedButton;
```

#### Cas d'utilisation concrets des HOC :

1. **Authentification :** encapsuler des composants pour verifier les droits
   d'acces.

2. **Traitement des donnees :** connexion a une API ou gestion de l'etat.

3. **Journalisation :** ajout d'un suivi des actions des composants.

#### Limitations des HOC :

- Ils peuvent creer des imbrications profondes dans l'arbre des composants si
  on en utilise trop.

- Ils peuvent rendre la lecture du code plus difficile a cause de l'empilement
  des enveloppes.

Les HOC sont un outil puissant pour reutiliser la logique, mais dans les
applications modernes ils sont souvent remplaces par les hooks React.

</details>

<details>
<summary>32. Qu'est-ce que la prop children ?</summary>

#### React

#### Qu'est-ce que la prop `children` ?

`children` est une prop speciale dans React, utilisee pour transmettre des
elements ou des composants imbriques a un composant conteneur.

#### Comment cela fonctionne-t-il ?

Lorsque vous placez du contenu entre la balise ouvrante et la balise fermante
d'un composant, ce contenu est automatiquement transmis comme valeur de
`props.children`.

#### Exemple :

- **Composant conteneur :**

```jsx
function Wrapper({ children }) {
  return { children };
}
```

- **Utilisation :**

```jsx
function App() {
  return (

      Hello, World!
      This is a paragraph inside the wrapper.

  );
}
```

- **Resultat :**

```html
Hello, World! This is a paragraph inside the wrapper.
```

#### Caracteristiques principales de `children` :

1. **Souplesse :** on peut transmettre n'importe quel type de donnees : texte,
   JSX, composants ou tableaux d'elements.

2. **Reutilisation :** un composant conteneur peut afficher dynamiquement des
   contenus differents.

3. **Structure :** cela aide a construire des composants avec une structure
   imbriquee.

#### Utilisation de `children` avec des props fonctionnelles :

Parfois, `children` est utilise comme une fonction pour transmettre des donnees
de maniere dynamique :

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

#### Resultat :

```html
Apple Banana Cherry
```

`children` est un outil puissant pour creer des composants generiques et
reutilisables dans React.

</details>

<details>
<summary>33. Qu'est-ce qu'un portail (Portal) ?</summary>

#### React

Un **portail (Portal)** dans React est un moyen de rendre des elements enfants
dans un noeud DOM situe en dehors de la hierarchie DOM du composant parent.

#### Comment cela fonctionne :

React fournit les portails via la methode `ReactDOM.createPortal`, qui prend
deux arguments :

1. **L'element React** a rendre.

2. **Le noeud DOM cible** dans lequel inserer l'element.

#### Syntaxe :

```jsx
ReactDOM.createPortal(child, container);
```

- **`child`** : l'element React a rendre.

- **`container`** : le noeud DOM dans lequel l'element sera insere.

#### Exemple d'utilisation :

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function Modal({ children }) {
  return ReactDOM.createPortal(
    {children},
    document.getElementById('modal-root') // Noeud cible
  );
}

function App() {
  return (

      Contenu principal

        Ceci est le contenu de la fenetre modale


  );
}
```

#### Ou utilise-t-on les portails :

- Fenetres modales.

- Info-bulles (tooltips).

- Menus contextuels.

#### Particularites :

1. **Hierarchie des evenements :** bien que l'element soit rendu hors de la
   hierarchie DOM, la gestion des evenements suit toujours la hierarchie des
   composants React. Par exemple, les evenements `onClick` remonteront vers les
   composants parents React.

2. **Souplesse :** les portails permettent d'inserer des elements dans des
   zones qui ne s'integrent pas a la structure DOM courante.

#### Avantages :

- Gestion simple des elements "flottants".
- Conservation du contexte React, meme en dehors de la hierarchie DOM
  principale.

</details>

<details>

<summary>34. Comment fonctionnent les portails (Portals) dans React, et quels sont leurs avantages et usages principaux en developpement UI ?</summary>

#### React

Les **portails (Portals)** dans React permettent de rendre des elements enfants
dans une autre partie du DOM, et non a l'emplacement habituel du composant.
C'est utile pour afficher des elements qui doivent se trouver hors de la
hierarchie DOM classique, par exemple des fenetres modales, des tooltips ou
des elements flottants.

#### Principaux avantages des portails :

- Ils permettent de rendre des elements a un autre endroit du DOM sans casser
  la structure des composants React.

- Ils sont utiles lorsqu'il faut afficher des elements au-dessus d'autres
  contenus, comme des modales ou des menus contextuels.

#### Comment fonctionnent les portails :

- Un portail permet d'envoyer du contenu vers n'importe quelle zone du DOM,
  meme en dehors du conteneur racine de React.

#### Exemple d'utilisation d'un portail :

```jsx
import ReactDOM from 'react-dom';

const Modal = () => {
  return ReactDOM.createPortal(
    <div className="modal">
      <h1>Ceci est une fenetre modale</h1>
    </div>,
    document.getElementById('modal-root') // Emplacement DOM de rendu du portail
  );
};

const App = () => {
  return (
    <div>
      <h1>Page principale</h1>
      <Modal />
    </div>
  );
};
```

#### Points cles :

- `ReactDOM.createPortal()` est utilise pour creer un portail. Le premier
  argument est le contenu a rendre, le second est l'element DOM dans lequel ce
  contenu est insere.

- Les portails peuvent etre utilises pour les fenetres modales, les tooltips,
  les menus flottants et d'autres elements qui doivent etre affiches en dehors
  de l'arbre principal des composants.

#### Particularites :

- Bien que les elements rendus via les portails se trouvent hors de la
  hierarchie principale des composants React, ils conservent l'acces au
  contexte, a l'etat et aux props de leurs parents.

- Les portails sont utiles lorsque des elements doivent etre places "au-dessus"
  d'un autre contenu ou a un autre niveau de la hierarchie DOM, par exemple une
  fenetre modale qui ne doit pas etre limitee par le conteneur parent.

Les portails permettent de conserver la logique et la structure du composant
sans violer les contraintes du DOM, ce qui aide a creer des composants UI
propres et pratiques.

</details>

<details>
<summary>35. Quelles sont les methodes du cycle de vie d'un composant dans React ?</summary>

#### React

Les methodes du cycle de vie d'un composant dans React servent a gerer les
differentes etapes de sa vie : creation, mise a jour et suppression.

#### Principales phases du cycle de vie :

1. **Montage (Mounting) :** lorsque le composant est ajoute au DOM.

`constructor()` : initialisation de l'etat et liaison des methodes.

`static getDerivedStateFromProps(props, state)` : mise a jour de l'etat avant
le rendu, methode rarement utilisee.

`render()` : rend le JSX dans le DOM virtuel.

`componentDidMount()` : appelee juste apres l'insertion du composant dans le
DOM. Utilisee pour les appels API ou l'initialisation de bibliotheques.

2. **Mise a jour (Updating) :** lorsque les props ou l'etat changent.

`static getDerivedStateFromProps(props, state)` : appelee avant chaque rendu.

`shouldComponentUpdate(nextProps, nextState)` : controle s'il faut rerendre le
composant. Retourne `true` par defaut.

`render()` : execute la mise a jour du DOM virtuel.

`getSnapshotBeforeUpdate(prevProps, prevState)` : capture un etat avant les
changements, par exemple la position du scroll.

`componentDidUpdate(prevProps, prevState, snapshot)` : appelee apres la mise a
jour. Utilisee pour de nouveaux appels ou pour interagir avec le DOM.

3. **Demontage (Unmounting) :** lorsque le composant est retire du DOM.

`componentWillUnmount()` : utilisee pour nettoyer les ressources, par exemple
des timers ou des abonnements.

4. **Gestion des erreurs (Error Handling) :** lorsqu'un composant provoque une
erreur.

`static getDerivedStateFromError(error)` : permet de mettre a jour l'etat apres
une erreur.

`componentDidCatch(error, info)` : journalisation des erreurs.

#### Tableau des methodes :

| Phase | Methode | Description |
| ----- | ------- | ----------- |
| **Montage** | `constructor()` | Initialise l'etat et la configuration. |
| | `getDerivedStateFromProps()` | Met a jour l'etat avant le rendu. |
| | `render()` | Rend le JSX dans le DOM virtuel. |
| | `componentDidMount()` | S'execute apres l'insertion dans le DOM. |
| **Mise a jour** | `getDerivedStateFromProps()` | Met a jour l'etat avant le rendu. |
| | `shouldComponentUpdate()` | Determine si un nouveau rendu est necessaire. |
| | `render()` | Met a jour le DOM virtuel. |
| | `getSnapshotBeforeUpdate()` | Capture un etat juste avant la mise a jour. |
| | `componentDidUpdate()` | S'execute apres la mise a jour. |
| **Demontage** | `componentWillUnmount()` | Nettoie les ressources avant la suppression. |
| **Gestion des erreurs** | `getDerivedStateFromError()` | Met a jour l'etat en cas d'erreur. |
| | `componentDidCatch()` | Journalise les erreurs. |

#### Approche moderne :

Dans les composants fonctionnels, on utilise des **hooks** a la place des
methodes de cycle de vie :

- `useEffect` remplace `componentDidMount`, `componentDidUpdate` et
  `componentWillUnmount`.

- `useState` sert a gerer l'etat.

</details>

<details>
<summary>36. Que fait la methode shouldComponentUpdate ?</summary>

#### React

- `shouldComponentUpdate` est une methode du cycle de vie des composants de
  classe, qui determine si le composant doit etre rerendu.

#### Comment cela fonctionne :

- Par defaut, elle retourne `true`, ce qui signifie qu'un rerendu a lieu a
  chaque changement de `state` ou de `props`.

- Si elle retourne `false`, React ne rerendra pas le composant, meme si les
  props ou le `state` ont change.

#### Exemple d'utilisation :

```jsx
class MyComponent extends React.Component {
  shouldComponentUpdate(nextProps, nextState) {
    return nextProps.value !== this.props.value; // Rerendu uniquement si value change
  }

  render() {
    return <div>{this.props.value}</div>;
  }
}
```

#### Alternative dans les composants fonctionnels :

- Utilisez `React.memo()` pour la memoisation.

- `useMemo()` et `useCallback()` aident a optimiser les rerendus.

</details>

<details>
<summary>37. Comment executer du code avant la suppression d'un composant de l'arbre ?</summary>

#### React

Pour executer du code avant la suppression d'un composant de l'arbre React, on
utilise les approches suivantes :

1. **Composants de classe :** `componentWillUnmount`

Dans les composants de classe, la methode du cycle de vie
`componentWillUnmount` est appelee avant la suppression du composant.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Le composant va etre supprime');
  }

  render() {
    return <div>Mon composant</div>;
  }
}
```

2. **Composants fonctionnels :** `useEffect` avec nettoyage

Dans les composants fonctionnels, le nettoyage peut etre effectue dans
`useEffect` en retournant une fonction qui sera executee avant la suppression
du composant.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Le composant va etre supprime');
    };
  }, []);

  return <div>Mon composant</div>;
}
```

3. **Traitement avant la fermeture de la page (`beforeunload`)**

Si du code doit etre execute avant la fermeture d'un onglet ou le rechargement
de la page :

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('La page se ferme');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Conclusion

- `componentWillUnmount` pour les composants de classe.

- `useEffect` avec `return` pour les composants fonctionnels.

- `beforeunload` pour les cas ou il faut reagir a la sortie de la page.

</details>

<details>
<summary>38. Pourquoi les fragments (Fragment) sont-ils preferables aux div conteneurs ?</summary>

#### React

Les fragments (`<React.Fragment>` ou `<>...</>`) sont preferables aux `<div>`
conteneurs dans React pour plusieurs raisons :

1. **Reduction du HTML inutile**

- Les fragments n'ajoutent pas d'element supplementaire dans le DOM, ce qui
  reduit le nombre de balises imbriquees et peut ameliorer les performances.

```jsx
<>
  <h1>Title</h1>
  <p>Text</p>
</>
```

- Resultat dans le DOM :

```html
<h1>Title</h1>
<p>Text</p>
```

- Contrairement a un `<div>`, qui ajouterait une imbrication supplementaire :

```html
<div>
  <h1>Title</h1>
  <p>Text</p>
</div>
```

2. **Absence d'effets de bord sur le style**

- Un `<div>` supplementaire peut affecter les styles CSS et provoquer des
  changements de mise en page indesirables. Les fragments evitent ce probleme.

3. **Meilleure compatibilite avec les tableaux**

- On ne peut pas imbriquer directement un `<div>` dans une `<table>`, mais on
  peut utiliser des fragments :

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

- Cela fonctionne correctement, alors qu'un `<div>` provoquerait une erreur.

4. **Optimisation des performances**

- Moins de noeuds inutiles dans le DOM -> rendu plus rapide et consommation
  memoire reduite.

</details>

<details>
<summary>39. Que sont les hooks dans React ?</summary>

#### React

Les **hooks React** sont des fonctions qui permettent d'utiliser l'etat et
d'autres fonctionnalites de React sans ecrire de classes.

#### Principaux types de hooks :

1. **useState** permet d'ajouter un etat aux composants fonctionnels.

```jsx
const [state, setState] = useState(initialState);
```

2. **useEffect** permet d'executer des effets de bord, par exemple des appels
   API ou des abonnements, dans les composants fonctionnels.

```jsx
useEffect(() => {
  // code de l'effet
}, [dependencies]); // dependances
```

3. **useContext** donne acces aux valeurs du contexte sans avoir besoin
   d'utiliser un composant Consumer.

```jsx
const value = useContext(MyContext);
```

4. **useRef** permet de creer des references vers des elements DOM ou de
   conserver des valeurs entre les rendus sans changer l'etat.

```jsx
const myRef = useRef(initialValue);
```

5. **useReducer** est une alternative a `useState`, pratique pour gerer des
   etats plus complexes avec des reducers, dans un style proche de Redux.

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

6. **useMemo** optimise le calcul de valeurs afin d'eviter des recomputations
   inutiles.

```jsx
const memoizedValue = useMemo(() => computeExpensiveValue(a, b), [a, b]);
```

7. **useCallback** retourne une version memoisee d'une fonction afin qu'elle ne
   soit pas recreee a chaque rendu.

```jsx
const memoizedCallback = useCallback(() => {
  // fonction;
}, [dependencies]);
```

#### Principaux avantages :

- **Composants fonctionnels :** au lieu de composants de classe, vous pouvez
  utiliser des composants fonctionnels avec des hooks.

- **Lisibilite amelioree :** la logique peut etre separee en plusieurs hooks,
  ce qui reduit la quantite de code et ameliore la modularite.

- **Reutilisation de la logique :** les hooks permettent de reutiliser la
  logique dans differents composants sans creer de hierarchies complexes.

</details>

<details>
<summary>40. Quels sont les avantages des hooks dans React ?</summary>

#### React

| **Avantage** | **Description** |
| ------------ | --------------- |
| **Moins de code** | Les hooks permettent d'eviter les classes et de reduire le volume de code. |
| **Meilleure lisibilite** | Le code avec hooks est plus facile a comprendre et a maintenir. |
| **Reutilisation de la logique** | Les custom hooks permettent de reutiliser la logique entre plusieurs composants. |
| **Gestion d'etat simplifiee** | L'utilisation de `useState` et `useReducer` rend la gestion de l'etat plus simple. |
| **Souplesse dans l'usage des effets** | `useEffect` permet de gerer les effets de bord sans recourir aux methodes de cycle de vie des classes. |
| **Migration plus facile** | Ils facilitent le passage des composants de classe aux composants fonctionnels. |

</details>

<details>
<summary>41. Quels sont les inconvenients des hooks dans React ?</summary>

#### React

| **Inconvenient** | **Description** |
| ---------------- | --------------- |
| **Nombre accru de rerendus** | Une mauvaise utilisation des hooks, surtout `useEffect`, peut provoquer des rerendus inutiles. |
| **Logique plus difficile a suivre** | La logique du composant peut etre dispersee dans plusieurs `useEffect`, ce qui complique le debogage. |
| **Absence de cycle de vie explicite** | Contrairement aux composants de classe, les hooks n'ont pas de methodes de cycle de vie clairement separees. |
| **Problemes possibles d'optimisation** | Une mauvaise utilisation de `useCallback` et `useMemo` peut conduire a un comportement inefficace. |
| **Complexite dans les grands projets** | Dans les applications de grande taille, les hooks peuvent compliquer la gestion de l'etat et des effets de bord. |

</details>

<details>
<summary>42. Quelles sont les regles et restrictions d'utilisation des hooks dans React ?</summary>

#### React

| **Regle** | **Description** |
| --------- | --------------- |
| **Utilisation uniquement dans des fonctions** | Les hooks ne peuvent etre appeles que dans des composants fonctionnels ou dans des hooks personnalises. |
| **Respect de l'ordre d'appel** | Les hooks ne doivent pas etre appeles de maniere conditionnelle (`if`, `for`, `while`), sinon l'ordre d'appel sera casse. |
| **Appel uniquement au niveau superieur** | Les hooks ne doivent pas etre appeles a l'interieur de fonctions imbriquees ou de gestionnaires d'evenements. |
| **Nommage des hooks personnalises** | Les hooks personnalises doivent commencer par `use`, par exemple `useAuth`. |
| **Respect des dependances** | Dans `useEffect`, `useMemo` et `useCallback`, les dependances (`[]`) doivent etre declarees correctement afin d'eviter un comportement inattendu. |

</details>

<details>
<summary>43. Qu'est-ce que useReducer() ?</summary>

#### React

`useReducer()` est un hook React utilise pour gerer l'etat dans les composants
fonctionnels. C'est une alternative a `useState()` adaptee aux logiques de mise
a jour plus complexes, en particulier lorsque les changements dependent de
l'etat precedent.

#### Syntaxe :

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` : fonction qui prend `state` et `action` puis retourne le nouvel
  etat.

- `initialState` : etat initial.

- `dispatch` : fonction qui declenche le reducer avec une `action` donnee.

#### Exemple :

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

#### Quand l'utiliser :

- Lorsque l'etat a une logique complexe ou plusieurs dependances.

- Lorsqu'il faut uniformiser les mises a jour de l'etat via `dispatch`.

- Pour une meilleure evolutivite, par exemple dans une gestion d'etat globale.

</details>

<details>
<summary>44. Que font les hooks useCallback(), useMemo(), useImperativeHandle() et useLayoutEffect() ?</summary>

#### React

#### `useCallback()`

Memoise une fonction afin qu'elle ne soit pas recreee a chaque rendu. C'est
utile pour transmettre des callbacks a des composants enfants.

- **Exemple :**

```jsx
import { useCallback } from 'react';

function MyComponent({ onClick }) {
  return <button onClick={onClick}>Cliquez</button>;
}

function Parent() {
  const handleClick = useCallback(() => {
    console.log('Clic');
  }, []); // La fonction est creee une seule fois

  return <MyComponent onClick={handleClick} />;
}
```

#### `useMemo()`

Memoise un calcul pour eviter de le refaire a chaque rendu lorsque les
dependances n'ont pas change.

#### Exemple :

```jsx
import { useMemo } from "react";

function ExpensiveCalculation({ num }) {
const result = useMemo(() => {
console.log("Calcul...");
return num \* 2;
}, [num]); // Execute uniquement si num change

return <div>Resultat : {result}</div>;
}
```

#### `useImperativeHandle()`

Permet de controler le comportement d'une ref dans un composant enfant.
S'utilise avec `forwardRef()`.

#### Exemple :

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
      <button onClick={() => inputRef.current.focus()}>Focus</button>
      <button onClick={() => inputRef.current.clear()}>Effacer</button>
    </div>
  );
}
```

#### `useLayoutEffect()`

Fonctionne comme `useEffect()`, mais s'execute de facon synchrone apres les
modifications du DOM. Il est utile pour mesurer ou manipuler le DOM avant que
le navigateur n'affiche la page.

- **Exemple :**

```jsx
import { useLayoutEffect, useRef } from 'react';

function LayoutEffectExample() {
  const divRef = useRef();

  useLayoutEffect(() => {
    console.log("Largeur de l'element :", divRef.current.offsetWidth);
  }, []);

  return (
    <div ref={divRef} style={{ width: '200px', height: '100px' }}>
      Element
    </div>
  );
}
```

#### Quel hook utiliser et quand ?

- `useCallback()` : pour memoriser des fonctions.

- `useMemo()` : pour memoriser des calculs.

- `useImperativeHandle()` : pour controler la ref d'un composant enfant.

- `useLayoutEffect()` : lorsqu'il faut agir avant l'affichage des changements du
  DOM, par exemple pour une mesure.

</details>

<details>
<summary>45. Comment executer une operation une seule fois lors du rendu initial ?</summary>

#### React

Pour executer une operation une seule fois lors du rendu initial dans un
composant fonctionnel, utilisez `useEffect` avec un tableau de dependances vide
(`[]`) :

#### Exemple :

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    console.log("Cela s'executera une seule fois apres le montage du composant");
  }, []);

  return <div>Composant</div>;
}
```

#### Explication :

- `useEffect(() => { /* code */ }, [])` : un tableau de dependances vide
  signifie que l'effet sera lance une seule fois apres le premier rendu, comme
  `componentDidMount` dans les composants de classe.

#### En plus, par exemple pour un abonnement/nettoyage :

```jsx
useEffect(() => {
  const interval = setInterval(() => {
    console.log("Effet lance une seule fois");
  }, 1000);

  return () => clearInterval(interval); // Nettoyage lors du demontage
}, []);
```

Cette approche est utile pour initialiser des appels API, des abonnements, des
timers, etc.

</details>

<details>
<summary>46. Qu'est-ce que le contexte (Context) ?</summary>

#### React

Le **contexte (Context)** dans React est un mecanisme qui permet de transmettre
des donnees a travers l'arbre des composants sans devoir les passer par les
props a chaque niveau.

#### Comment fonctionne le contexte :

1. **React.createContext()** sert a creer un contexte.

```jsx
const MyContext = React.createContext(defaultValue);
```

2. **Provider** est le composant qui fournit la valeur du contexte. Il entoure
   une partie de l'arbre des composants et transmet la valeur via `value`.

```jsx
<MyContext.Provider value={}>
  <YourComponent />
</MyContext.Provider>
```

3. **Consumer** est le composant qui consomme la valeur du contexte. Il utilise
   generalement une fonction enfant recevant cette valeur.

```jsx
<MyContext.Consumer>
{value => }
</MyContext.Consumer>
```

4. **useContext** est un hook qui permet d'acceder a la valeur du contexte sans
   utiliser `Consumer`.

```jsx
const value = useContext(MyContext);
```

#### Quand l'utiliser :

- Lorsqu'il faut transmettre des donnees entre des composants situes a
  differents niveaux de la hierarchie, par exemple un theme, une langue ou un
  utilisateur.

- Lorsqu'on veut eviter de faire passer des props a travers plusieurs niveaux,
  ce qui peut compliquer le code.

#### Exemple d'utilisation :

```jsx
// Creation du contexte
const ThemeContext = React.createContext('light');

// Composant qui fournit la valeur du contexte
function App() {
  return (
    <ThemeContext.Provider value="dark">
      <ThemedComponent />
    </ThemeContext.Provider>
  );
}

// Composant qui consomme la valeur du contexte
function ThemedComponent() {
  const theme = useContext(ThemeContext);
  return <div>The current theme is {theme}</div>;
}
```

#### Avantages :

- Transmission plus simple de valeurs globales.

- Ameliore l'evolutivite de l'application en reduisant le nombre de props a
  transmettre.

</details>

<details>
<summary>47. Comment fonctionne le mecanisme Context dans React pour partager des donnees entre composants ?</summary>

#### React

Le mecanisme **React Context** permet de transmettre des donnees entre
composants sans devoir les passer via les props a chaque niveau. C'est utile
pour des donnees globales comme le theme, l'authentification de l'utilisateur
ou la langue.

#### Principales etapes de travail avec le contexte :

1. **Creation du contexte :** on utilise `React.createContext()` pour creer le
   contexte. Cela retourne deux composants :

- `Provider`, le composant qui transmet la valeur du contexte.

- `Consumer`, le composant qui recoit la valeur du contexte.

```jsx
const MyContext = React.createContext();
```

2. **Fourniture du contexte :** on utilise `Provider` pour entourer les
   composants qui doivent recevoir le contexte. La valeur est passee via la
   prop `value`.

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

3. **Recuperation du contexte :** on utilise `Consumer` ou le hook
   `useContext` pour acceder a la valeur du contexte.

- **Consumer :**

```jsx
const Child = () => (
  <MyContext.Consumer>{user => <div>{user}</div>}</MyContext.Consumer>
);
```

- **Hook `useContext` (recommande dans les composants fonctionnels) :**

```jsx
const Child = () => {
  const user = useContext(MyContext);
  return <div>{user}</div>;
};
```

- **Modification du contexte :** pour modifier la valeur du contexte, on peut
  utiliser des fonctions transmises par `useState` ou d'autres methodes de
  gestion de l'etat.

```jsx
const App = () => {
  const [user, setUser] = useState('John Doe');

  return (
    <MyContext.Provider value={user}>
      <button onClick={() => setUser('Jane Doe')}>Changer l'utilisateur</button>
      <Child />
    </MyContext.Provider>
  );
};
```

#### Points cles :

- Le contexte permet d'eviter le `prop drilling`, c'est-a-dire le passage de
  props a travers de nombreux composants.

- Si la valeur du contexte change, tous les composants qui le consomment seront
  rerendus.

- **useContext** est une facon plus simple et plus moderne d'obtenir la valeur
  du contexte que `Consumer`.

Le contexte est un outil puissant, mais il vaut mieux le reserver aux donnees
globales. Pour l'etat local, un state classique reste preferable.

</details>

<details>
<summary>48. Qu'est-ce que le prop drilling et comment l'eviter ?</summary>

#### React

Le **prop drilling** consiste a faire passer des props a travers plusieurs
niveaux de composants imbriques, meme si elles ne sont necessaires qu'a un
composant plus profond dans la hierarchie. Cela complique la maintenance du
code et le rend moins lisible.

#### Exemple de prop drilling :

```jsx
const Parent = () => {
  const user = { name: 'John' };
  return <Child user={user} />;
};

const Child = ({ user }) => {
  return <GrandChild user={user} />;
};

const GrandChild = ({ user }) => {
  return <p>Nom : {user.name}</p>;
};
```

Ici, `user` est transmis via `Child`, bien que ce composant n'en ait pas
besoin : c'est exactement ce qu'on appelle le **prop drilling**.

#### Comment eviter le prop drilling ?

| **Methode** | **Description** |
| ----------- | --------------- |
| **Context API** | Permet de transmettre les donnees directement aux composants qui en ont besoin. |
| **Etats externes (Redux, Zustand, Jotai, Recoil)** | Servent a gerer un etat global sans faire passer les props manuellement. |
| **Render Props** | Permettent de transmettre des fonctions au lieu de props classiques. |
| **Custom Hooks** | Extraient la logique dans des fonctions separees pour acceder a des donnees partagees. |

#### Exemple d'utilisation de Context API a la place du prop drilling

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
  return <p>Nom : {user.name}</p>;
};
```

Ici, `user` est disponible directement dans `GrandChild`, sans transmission
inutile via `Child`.

</details>

<details>
<summary>49. Qu'est-ce que Redux ?</summary>

#### React

**Redux** est une bibliotheque de gestion d'etat pour les applications
JavaScript, particulierement populaire avec React. Elle repose sur le concept
d'un stockage global (`store`) ou tout l'etat de l'application est conserve, et
permet de le gerer au moyen de changements previsibles.

#### Principes fondamentaux de Redux :

1. **Source unique de verite** : tout l'etat est stocke dans un seul `store`
   global, ce qui facilite le suivi des modifications.
2. **L'etat est en lecture seule** : il ne peut pas etre modifie directement,
   uniquement via une `action`.
3. **Les changements passent par des fonctions pures** : l'etat est modifie a
   l'aide de reducers, qui recoivent l'etat courant et une `action`, puis
   retournent un nouvel etat.

#### Elements principaux de Redux :

- **Store** : le stockage unique de l'etat.
- **Actions** : objets qui decrivent l'intention de modifier l'etat.
- **Reducers** : fonctions pures qui definissent comment l'etat change.
- **Dispatch** : methode qui envoie une `action`.
- **Selectors** : fonctions qui recuperent les donnees necessaires depuis le
  `store`.

Redux convient bien aux grandes applications avec des flux de donnees complexes,
mais il est souvent excessif pour des projets simples.

</details>

<details>
<summary>50. Quelles autres bibliotheques de gestion d'etat en React connais-tu en dehors de Redux ?</summary>

#### React

En dehors de Redux, il existe de nombreuses bibliotheques de gestion d'etat
dans React :

1. **React Context API** est un mecanisme integre a React pour transmettre
   l'etat sans prop drilling. Il convient bien aux petites et moyennes
   applications.

2. **Zustand** est plus simple et plus leger que Redux. Il n'a pas besoin de
   reducers ni d'actions, utilise une approche imperative et fonctionne via des
   hooks.

3. **Recoil** est une bibliotheque de Facebook qui fonctionne avec des atomes
   (`atoms`) et des selecteurs (`selectors`), permettant de construire un
   systeme d'etat global souple.

4. **Jotai** ressemble a Recoil, mais en plus simple. Elle utilise aussi des
   atomes pour stocker l'etat et permet de le gerer declarativement.

5. **MobX** adopte une approche reactive de la gestion d'etat et fonctionne
   avec des observables. Il est pratique pour manipuler des objets et des
   structures complexes.

6. **Effector** est plus declaratif et souvent plus efficace que Redux. Il
   repose sur une approche reactive et facilite la gestion des flux de donnees.

7. **XState** est une bibliotheque pour travailler avec des machines d'etats
   (`state machines`), particulierement adaptee a une logique metier complexe.

Chacune a ses avantages, et le choix depend de la complexite du projet ainsi
que des exigences en matiere de performances.

</details>

<details>
<summary>51. Qu'est-ce que Redux Thunk ?</summary>

#### React

**Redux Thunk** est un middleware pour Redux qui permet d'executer des
operations asynchrones, par exemple des appels API, avant d'envoyer les
changements au `store`.

#### Comment cela fonctionne :

En temps normal, Redux permet seulement de passer des objets (`actions`) a
`dispatch`. Redux Thunk etend ce comportement en autorisant aussi des
fonctions. Cela permet :

1. D'executer des actions asynchrones avant la modification de l'etat.

2. D'acceder a `dispatch` et `getState` a l'interieur du `thunk`.

#### Exemple d'utilisation :

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

Ensuite, on appelle ce `thunk` :

```jsx
dispatch(fetchData());
```

#### Quand l'utiliser :

- Pour les appels API.
- Pour des delais ou une logique complexe avant la mise a jour du store.
- Lorsqu'il faut effectuer plusieurs `dispatch` dans le cadre d'une seule
  action.

Si l'application a une logique asynchrone complexe, il vaut mieux envisager
**Redux Saga** ou **RTK Query** comme alternatives.

</details>

<details>
<summary>52. Comment fonctionne Redux Saga ?</summary>

#### React

**Redux Saga** est un middleware pour Redux qui utilise des generateurs
(`function*`) afin de gerer les operations asynchrones dans l'application.

#### Comment cela fonctionne :

1. **Ecoute les actions** via `takeEvery` ou `takeLatest` et y reagit.

2. **Execute des effets de bord** comme des appels API, des timers, etc.

3. **Dispatche de nouvelles actions** avec `put` vers le store.

#### Exemple :

1. **Saga pour recuperer des donnees depuis l'API :**

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

2. **Ecouteur d'actions :**

```jsx
function* watchFetchData() {
  yield takeEvery('FETCH_REQUEST', fetchData);
}
```

3. **Lancement de la saga dans le `store` :**

```jsx
import createSagaMiddleware from 'redux-saga';
const sagaMiddleware = createSagaMiddleware();
const store = createStore(reducer, applyMiddleware(sagaMiddleware));
sagaMiddleware.run(watchFetchData);
```

#### Avantages de Redux Saga :

- Gere une logique asynchrone complexe.
- Integre la gestion des annulations avec `takeLatest`.
- Propose des operateurs puissants comme `call`, `put`, `select` et `delay`.

**Redux Thunk** est plus simple, mais pour des scenarios complexes **Saga** est
souvent plus adaptee.

</details>

<details>
<summary>53. Qu'est-ce que React Fiber ?</summary>

#### React

**React Fiber** est la nouvelle architecture de rendu de React, introduite a
partir de la version 16. Elle a ete concue pour ameliorer les performances,
prendre en charge le rendu asynchrone et offrir une gestion plus souple des
mises a jour de l'interface.

#### Caracteristiques principales de React Fiber :

1. **Performances ameliorees :** Fiber permet a React de conserver l'etat
   d'avancement du rendu, ce qui rend possible l'interruption puis la reprise
   du rendu si necessaire. C'est important dans les grandes applications ou les
   calculs lourds peuvent ralentir le rendu.

2. **Rendu asynchrone :** React Fiber prend en charge le rendu par morceaux,
   ce qui ameliore la reactivite de l'application, surtout dans les interfaces
   complexes, sans bloquer le thread principal.

3. **Priorite des mises a jour :** Fiber permet de donner des priorites a
   differents types de mises a jour, par exemple une priorite elevee aux
   animations et une plus basse aux changements d'etat.

4. **Decoupage du rendu en sous-taches :** dans les anciennes versions de
   React, toutes les modifications etaient traitees en une seule etape. Fiber
   decoupe le rendu en sous-taches plus petites, ce qui permet de traiter
   d'autres operations importantes, par exemple les evenements, entre deux
   etapes.

5. **Meilleure prise en charge des animations et des transitions :** grace au
   rendu asynchrone, React peut gerer plus efficacement les animations, ce qui
   rend les transitions plus fluides et plus stables.

#### Comment fonctionne React Fiber ?

Dans les anciennes versions de React, tout le processus de rendu etait
synchrone, du debut a la fin. Cela signifiait que les calculs lourds bloquaient
l'affichage de l'interface. Avec React Fiber, le rendu est divise en petites
taches qui peuvent etre executees de maniere asynchrone. Si necessaire, React
peut interrompre une tache et la reprendre plus tard sans bloquer d'autres
operations, par exemple les mises a jour de l'UI ou le traitement des
evenements.

#### Fiber permet a React de :

- Repartir le travail de rendu pour ameliorer les performances.

- Mettre en oeuvre des mises a jour asynchrones de l'interface.

- Mieux gerer les priorites et les calculs lourds, ce qui est particulierement
  important dans les interfaces et applications complexes.

#### Avantages :

- Ameliore la reactivite des applications.

- Permet de traiter des operations lourdes sans retards perceptibles pour
  l'utilisateur.

- Assure une meilleure gestion des animations et des transitions.

**React Fiber** est une evolution interne qui a change la maniere dont React
gere le rendu, en ameliorant les performances globales des applications.

</details>

<details>
<summary>54. Qu'est-ce que le Lifting State Up dans React ?</summary>

#### React

Le **Lifting State Up** est une approche dans React qui consiste a remonter
l'etat (`state`) jusqu'au plus proche ancetre commun des composants qui doivent
le partager. Cela permet d'etablir une source unique de verite pour la gestion
des donnees entre composants.

#### Idee principale :

1. **Les composants qui doivent partager des donnees ne devraient pas chacun
   avoir leur propre etat pour ces donnees.**

2. **L'etat est remonte dans un composant parent, qui transmet ensuite les
   donnees aux composants enfants via les props.**

#### Comment cela fonctionne :

1. **Le composant parent stocke l'etat.**
2. **Il transmet cet etat, ainsi que les fonctions de mise a jour, a ses
   composants enfants via les `props`.**

3. **Les composants enfants informent le parent des changements au moyen des
   fonctions transmises.**

#### Exemple :

```jsx
import React, { useState } from 'react';

function TemperatureInput({ temperature, onTemperatureChange }) {
  return (
    <fieldset>
      <legend>Entrez la temperature en Celsius :</legend>
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

#### Avantages :

1. **Garantit une source unique de verite pour l'etat.**

2. **Facilite la synchronisation des donnees entre composants.**

3. **Rend les composants plus previsibles et reutilisables.**

</details>

<details>
<summary>55. Que sont les composants controles (Controlled Components) ?</summary>

#### React

#### Composants controles (Controlled Components) dans React

Les composants controles sont des composants dans lesquels **React controle
l'etat du formulaire** via le `state`. Les valeurs des champs de formulaire,
comme `<input>`, `<textarea>` ou `<select>`, sont liees a l'etat du composant,
et les changements sont traites via des evenements.

#### Comment cela fonctionne :

1. **Le composant stocke la valeur du formulaire dans son `state`.**

2. **Les changements des champs sont geres via l'evenement `onChange`.**

3. **La valeur du formulaire est mise a jour avec `setState` ou le setter
   fourni par `useState`.**

#### Exemple :

```jsx
import React, { useState } from 'react';

function ControlledForm() {
  const [inputValue, setInputValue] = useState('');

  const handleChange = event => {
    setInputValue(event.target.value); // Mise a jour de l'etat
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
          value={inputValue} // Valeur controlee par le state
          onChange={handleChange} // Gestion des changements
        />
      </label>
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

#### Principaux avantages :

1. **Source unique de verite :** la valeur du formulaire est synchronisee avec
   l'etat du composant.

2. **Souplesse :** il est facile de valider et de modifier les donnees du
   formulaire.

3. **Transparence :** l'etat du formulaire est clair et previsible.

#### Difference avec les composants non controles :

- Dans les composants controles, la valeur du formulaire est pilotee par React
  via le `state`.

- Dans les composants non controles, la valeur est stockee dans le DOM et l'on
  y accede via une `ref`.

#### Exemple non controle pour comparaison :

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

Les composants controles offrent un meilleur controle et une meilleure
previsibilite pour le travail avec les formulaires.

</details>

<details>
<summary>56. Que sont les composants non controles (Uncontrolled Components) ?</summary>

#### React

#### Composants non controles dans React

Les composants non controles sont des composants qui stockent leur etat dans le
DOM, et non dans l'etat interne du composant React. L'acces a leurs valeurs se
fait au moyen de **refs**.

#### Caracteristiques principales :

1. **L'etat est gere par le DOM :** les valeurs des champs sont stockees et
   mises a jour directement dans le DOM.

2. **Moins d'integration avec React :** ils n'utilisent pas `useState` ni
   d'autres outils React pour stocker l'etat.

3. **Utilisation des refs :** une `ref` est utilisee pour acceder a la valeur
   des champs du formulaire.

#### Exemple de composant non controle :

```jsx
import React, { useRef } from 'react';

function UncontrolledForm() {
  const inputRef = useRef(null);

  const handleSubmit = event => {
    event.preventDefault();
    alert(`Valeur saisie : ${inputRef.current.value}`);
  };

  return (
    <form onSubmit={handleSubmit}>
      <label>
        Nom :
        <input type="text" ref={inputRef} />
      </label>
      <button type="submit">Envoyer</button>
    </form>
  );
}

export default UncontrolledForm;
```

#### Quand utiliser des composants non controles :

- Lorsqu'une integration minimale entre React et le DOM suffit.

- Lorsque les valeurs du formulaire sont traitees par des bibliotheques
  tierces.

- Lorsqu'il s'agit d'un formulaire simple sans logique complexe.

#### Avantages :

- Simplicite d'implementation pour les formulaires simples.

- Moins de code pour gerer l'etat.

#### Inconvenients :

- Moins de controle sur les valeurs.

- Validation et synchronisation des donnees plus difficiles a mettre en place.

- Approche moins orientee React.

</details>

<details>
<summary>57. Comment creer un formulaire dans React ?</summary>

#### React

#### Creation d'un formulaire dans React

Les formulaires dans React se creent a l'aide des elements `<form>` et des
champs associes comme `<input>`, `<textarea>` ou `<select>`. Leur reactivite
repose sur des composants controles ou non controles.

#### Formulaire controle (Controlled Component)

Les composants controles utilisent l'etat (`state`) pour suivre la valeur des
champs du formulaire.

#### Exemple :

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

#### Caracteristiques :

- Chaque champ est controle via le `state`.

- Les donnees du formulaire sont faciles a synchroniser et a traiter.

#### Formulaire non controle (Uncontrolled Component)

Les composants non controles utilisent une `ref` pour acceder directement aux
elements du DOM.

#### Exemple :

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

#### Caracteristiques :

- L'acces aux valeurs se fait via une `ref`.

- Convient aux formulaires simples.

#### Points essentiels :

1. **Formulaire controle :**

- Utilise le `state`.

- Convient mieux aux formulaires complexes qui demandent validation ou
  synchronisation.

2. **Formulaire non controle :**

- Utilise une `ref`.

- Approche simple sans logique complexe de gestion d'etat.

Le choix de l'approche depend de la complexite du formulaire et des besoins
d'interaction avec ses champs.

</details>

<details>
<summary>58. Comment valider les props dans React ?</summary>

#### React

Pour valider les props dans React, on utilise **PropTypes**.

1. **Installation de PropTypes, si ce n'est pas deja fait**

```sh
npm install prop-types
```

2. **Utilisation de PropTypes dans un composant fonctionnel :**

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

// Definition des PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Valeurs par defaut
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

3. **Utilisation dans un composant de classe :**

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

// Definition des PropTypes
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isAdmin: PropTypes.bool,
};

// Valeurs par defaut
UserCard.defaultProps = {
  age: 18,
  isAdmin: false,
};

export default UserCard;
```

#### Types PropTypes disponibles :

- `PropTypes.string`
- `PropTypes.number`
- `PropTypes.bool`
- `PropTypes.array`
- `PropTypes.object`
- `PropTypes.func`
- `PropTypes.node` (JSX ou texte)
- `PropTypes.element` (element React)
- `PropTypes.oneOf(['value1', 'value2'])` (liste de valeurs autorisees)
- `PropTypes.shape({ key: PropTypes.type })` (objet avec une structure definie)

#### Conclusion :

PropTypes aide a eviter des erreurs en verifiant les types des props, meme si
dans TypeScript cette verification est assuree directement par le langage.

</details>

<details>
<summary>59. En quoi React Router differe-t-il du routage classique ?</summary>

#### React

#### Difference entre React Router et le routage classique :

| Critere | React Router | Routage classique (server-side routing) |
| ------- | ------------ | ---------------------------------------- |
| **Type de routage** | Cote client (SPA) | Cote serveur (MPA) |
| **Navigation entre les pages** | Sans rechargement complet de la page, JavaScript met a jour l'URL | Rechargement complet a chaque changement de page |
| **Vitesse** | Plus rapide, car le serveur n'est pas sollicite a chaque fois | Plus lent en raison de nouvelles requetes HTTP |
| **SEO** | Moins bon sans SSR, meme si Next.js corrige souvent ce point | Meilleur, car le contenu est servi par le serveur |
| **Traitement des donnees** | Rendu dynamique de composants | Chargement de HTML cote serveur |
| **Configuration** | Necessite React Router | Utilise les capacites standard du serveur |

</details>

<details>
<summary>60. Comment transmettre des props dans React Router ?</summary>

#### React

Pour transmettre des props a des composants lors de l'utilisation de
**React Router**, il existe plusieurs approches :

1. **Utilisation du composant `Route` pour transmettre des props :** on peut
   passer des props via `Route` en utilisant `render` ou `children`.

**Exemple :**

```jsx
import { Route } from 'react-router-dom';

<Route path="/profile" render={props => <Profile {...props} user="John" />} />;
```

Ici, nous transmettons des props supplementaires au composant `Profile`.

2. **Utilisation de `useNavigate()` pour transmettre des donnees pendant la
   navigation via `state` :** lors du passage a une nouvelle page, on peut
   transmettre des donnees par `state`.

**Exemple :**

```jsx
import { useNavigate } from 'react-router-dom';

function Home() {
  const navigate = useNavigate();

  function goToProfile() {
    navigate('/profile', { state: { user: 'John' } });
  }

  return <button onClick={goToProfile}>Aller au profil</button>;
}
```

**Recuperation des props dans le composant :**

```jsx
import { useLocation } from 'react-router-dom';

function Profile() {
  const location = useLocation();
  const user = location.state?.user;

  return <div>Bienvenue, {user}</div>;
}
```

3. **Utilisation de `useParams()` pour acceder aux parametres de route :** si
   les donnees doivent etre transmises dans l'URL, on peut utiliser
   `useParams()`.

**Exemple :**

```jsx
import { useParams } from 'react-router-dom';

function Profile() {
  const { id } = useParams();

  return <div>ID utilisateur : {id}</div>;
}
```

#### Conclusion :

- `render` ou `children` conviennent pour transmettre des props directement.

- `useNavigate()` et `state` permettent de transmettre des donnees entre les
  pages.

- `useParams()` est pratique pour les parametres dynamiques dans l'URL.

</details>

<details>
<summary>61. Quelles sont les methodes de stylisation dans les composants React ?</summary>

#### React

#### Methodes de stylisation dans les composants React :

1. **Styles inline** Les styles sont passes directement sous forme d'objet via
   l'attribut `style`.

```jsx
function InlineStyle() {
  const style = {
    color: 'blue',
    fontSize: '20px',
  };

  return <h1 style={style}>Bonjour, React !</h1>;
}
```

2. **Fichiers CSS** Utilisation de fichiers CSS classiques importes dans le
   composant.

```jsx
import './styles.css';

function CSSFile() {
  return <h1 className="heading">Bonjour, React !</h1>;
}
```

```css
/* styles.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

3. **Modules CSS** Creent des styles localement isoles pour chaque composant.

```jsx
import styles from './styles.module.css';

function CSSModule() {
  return <h1 className={styles.heading}>Bonjour, React !</h1>;
}
```

```css
/* styles.module.css */
.heading {
  color: blue;
  font-size: 20px;
}
```

4. **Styled Components** Utilisation de la bibliotheque `styled-components`
   pour ecrire les styles en JavaScript.

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
  return <Heading>Bonjour, React !</Heading>;
}
```

5. **Emotion** Bibliotheque alternative de stylisation, similaire a
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
  return <h1 css={style}>Bonjour, React !</h1>;
}
```

6. **CSS-in-JS** Creation de styles dynamiques dans des fichiers JavaScript
   classiques.

```jsx
function CSSInJS({ isBlue }) {
  const style = {
    color: isBlue ? 'blue' : 'red',
    fontSize: '20px',
  };

  return <h1 style={style}>Bonjour, React !</h1>;
}
```

7. **Tailwind CSS** Framework de classes utilitaires pour styliser les
   composants.

```jsx
function TailwindExample() {
  return <h1 className="text-blue-500 text-2xl">Bonjour, React !</h1>;
}
```

**Configuration de Tailwind CSS :** ajoutez les dependances et configurez
l'outil.

8. **Sass/SCSS** CSS etendu avec prise en charge des variables, mixins et
   imbrications.

```bash
npm install sass
```

```jsx
import './styles.scss';

function SCSSExample() {
  return <h1 className="heading">Bonjour, React !</h1>;
}
```

```scss
/* styles.scss */
.heading {
  color: blue;
  font-size: 20px;
}
```

#### Le choix depend de :

- La taille du projet.

- La necessite d'isoler les styles.

- Les preferences de l'equipe.

</details>

<details>
<summary>62. Quel est l'avantage des styles modulaires (CSS Modules) ?</summary>

#### React

**Avantages des styles modulaires (CSS Modules) :**

1. **Portee locale** : les styles s'appliquent uniquement au composant et non
   globalement. Cela evite les conflits de classes et garantit qu'ils
   n'affectent pas d'autres parties de l'application.

2. **Noms de classes uniques** : CSS Modules genere automatiquement des noms de
   classes uniques, ce qui elimine le risque d'ecrasement par d'autres
   composants.

3. **Maintenance plus simple** : les problemes sont moindres lors du passage a
   l'echelle, car chaque composant possede ses propres styles, ce qui rend le
   code plus organise et plus lisible.

4. **Isolation** : chaque composant beneficie d'une isolation complete des
   styles, ce qui facilite le refactoring et les modifications sans impact sur
   d'autres composants.

5. **Integration plus simple avec JavaScript** : on peut utiliser des styles
   dynamiques en changeant les classes selon l'etat du composant.

Cela aide a garder de l'ordre dans les grandes applications et reduit le risque
d'erreurs de style.

</details>

<details>
<summary>63. Quelles approches connaissez-vous pour optimiser les performances des applications React ?</summary>

#### React

#### Approches pour optimiser les performances des applications React :

1. **Memoisation des composants :**

- Utilisez `React.memo` pour memoiser les composants fonctionnels qui ne
  dependent pas de mises a jour frequentes de props.
- Utilisez `PureComponent` pour les composants de classe.

2. **Memoisation des valeurs et des fonctions :**

- `useMemo` pour calculer des valeurs qui dependent de certaines dependances.
- `useCallback` pour memoiser des fonctions transmises a des composants
  enfants.

3. **Optimisation du rendu des listes :**

Utilisez toujours une `key` unique pour les elements de liste. Evitez les
rerendus inutiles des composants.

4. **Chargement dynamique des composants :**

- Utilisez `React.lazy` pour charger les composants a la demande.
- Combine avec `Suspense`, cela optimise le chargement de l'application.

5. **Controle des rerendus :**

- Utilisez `shouldComponentUpdate` ou `React.memo` pour reduire les rendus
  inutiles.
- Utilisez `React.Fragment` au lieu d'elements wrappers supplementaires.

6. **Decoupage du code (Code Splitting) :**

- Mettez en place `React.lazy` et les imports dynamiques pour charger le code
  des modules seulement lorsque c'est necessaire.

7. **Gestion de l'etat :**

- Evitez de stocker un etat global pour des composants qui n'en ont pas besoin.
- Deplacez les operations lourdes vers le contexte ou des bibliotheques
  specialisees comme Redux ou Zustand.

8. **Virtualisation des listes :**

- Utilisez des bibliotheques comme `react-window` ou `react-virtualized` pour
  rendre uniquement les elements visibles d'une liste.

9. **Optimisation des images :**

- Utilisez le chargement differe (`lazy loading`) pour les images.
- Compressez et optimisez les images avant de les utiliser.

10. **Reduction du nombre de composants dans le DOM :**

- Evitez l'imbrication excessive de composants.
- Supprimez les elements inutiles du DOM lors des changements de page.

11. **Mise en cache des donnees :**

- Utilisez des bibliotheques de cache comme `SWR` ou `React Query` pour gerer
  les donnees et reduire les requetes serveur.

12. **Utilisation du build de production :**

- Assurez-vous que l'application est construite en mode production avec
  `npm run build`.
- Utilisez des outils comme Webpack pour minifier et optimiser le code.

13. **Profilage de l'application :**

- Utilisez `React DevTools` pour analyser les performances.
- Identifiez les goulets d'etranglement avec l'onglet `Profiler`.

14. **Optimisation du CSS et des styles :**

- Utilisez les solutions `CSS-in-JS` comme `styled-components` uniquement
  lorsqu'elles sont necessaires.
- Compressez les styles a l'aide de `PostCSS` ou d'autres outils.

Ces approches aident a reduire les latences, a accelerer le rendu et a
ameliorer les performances globales de l'application.

</details>

<details>
<summary>64. Quelle est la difference entre memo et useMemo ?</summary>

#### React

#### Difference entre memo et useMemo

| Critere | memo | useMemo |
| ------- | ---- | ------- |
| **Qu'est-ce que c'est ?** | Fonction d'ordre superieur (HOC) | Hook |
| **But** | Evite le rerendu d'un composant si ses props n'ont pas change | Memorise le resultat d'un calcul entre les rendus |
| **Ou l'utilise-t-on ?** | Il encapsule un composant | A l'interieur d'un composant |
| **Exemple d'utilisation** | `export default memo(MyComponent);` | `const value = useMemo(() => compute(), [deps]);` |
| **Que met-il en cache ?** | Le composant entier | Le resultat d'une fonction |
| **Quand l'utiliser ?** | Si le composant est rerendu avec les memes props sans changement | Si le calcul est couteux et depend de certaines variables |

#### Quand les utiliser ?

- `memo` lorsque le composant recoit les memes props et qu'un rerendu n'est pas
  necessaire.

- `useMemo` lorsqu'il faut conserver le resultat d'un calcul pour ne pas le
  refaire a chaque rendu.

</details>

<details>
<summary>65. Pourquoi faut-il parfois passer une fonction a setState() ?</summary>

#### React

Passer une fonction a `setState()` est necessaire lorsque le nouvel etat depend
de l'etat precedent. Cela garantit une mise a jour correcte, car `setState()`
est asynchrone et peut regrouper plusieurs appels.

#### Exemple du probleme :

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

Ici, `count + 1` est calcule deux fois a partir de la meme ancienne valeur de
`count`, donc le bouton augmentera seulement de 1 au lieu de 2.

#### Bonne approche :

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

Ici, `setCount()` recoit la valeur actuelle `prevCount`, donc l'increment
fonctionne correctement et augmente la valeur de 2.

</details>

<details>
<summary>66. Comment les refs dans React sont-elles utilisees pour interagir avec les elements DOM ?</summary>

#### React

Les refs dans React servent a acceder directement a des elements du DOM ou a
des composants, en contournant le mecanisme habituel des props et de l'etat.

1. **Creation des refs :** on utilise `React.createRef()` pour creer une ref.

```jsx
const myRef = React.createRef();
```

2. **Association de la ref a un element :** la ref est passee a l'element DOM
   via l'attribut `ref`.

```jsx
<input ref={myRef} />
```

3. **Interaction avec le DOM :** la ref donne acces a l'element DOM via
   `.current`. Par exemple, pour donner le focus :

```jsx
myRef.current.focus();
```

4. **Limites :** les refs ne doivent pas servir a gerer l'etat. Elles sont
   destinees uniquement a l'interaction avec le DOM lorsque c'est necessaire,
   par exemple pour le focus, la selection de texte ou les animations.

5. **Composants fonctionnels :** depuis React 16.8, on utilise `useRef` dans
   les composants fonctionnels.

```jsx
const inputRef = useRef();
inputRef.current.focus();
```

</details>

<details>
<summary>67. Comment utiliser InnerHtml dans React ?</summary>

#### React

Dans React, pour inserer du contenu HTML dans le DOM, on utilise l'attribut
`dangerouslySetInnerHTML`. Cela permet d'inserer du HTML directement dans un
composant, mais cette approche peut etre dangereuse, d'ou le terme
"dangerously", car elle autorise l'injection de HTML brut et peut provoquer des
attaques XSS si les donnees ne sont pas nettoyees.

#### Exemple d'utilisation de `dangerouslySetInnerHTML` :

```jsx
const MyComponent = () => {
  const htmlContent = '<p>Ceci est un contenu <strong>HTML</strong>.</p>';

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
};
```

#### Explication :

- `dangerouslySetInnerHTML` prend un objet dont la cle `__html` contient une
  chaine de code HTML.

- Cela permet d'inserer du HTML dans un composant, mais ce n'est pas sur si le
  contenu provient de sources non fiables.

#### Quand l'utiliser :

- Si vous etes certain de la fiabilite et de la securite des donnees, par
  exemple lorsqu'elles viennent de vos propres serveurs.

- Lorsque vous devez inserer un contenu HTML dynamique, comme des pages ou des
  articles au format HTML.

#### Precautions :

- Securite : n'utilisez jamais `dangerouslySetInnerHTML` pour inserer des
  donnees venant d'un utilisateur ou de sources externes sans nettoyage
  prealable contre les scripts malveillants.

- Pour nettoyer le contenu, utilisez des bibliotheques comme `DOMPurify` afin
  d'eviter les attaques XSS.

**Exemple de nettoyage des donnees avant insertion :**

```jsx
import DOMPurify from 'dompurify';

const MyComponent = () => {
  const dirtyHtml = "<img src=x onerror=alert('XSS')>";
  const cleanHtml = DOMPurify.sanitize(dirtyHtml);

  return <div dangerouslySetInnerHTML={{ __html: cleanHtml }} />;
};
```

En resume, `dangerouslySetInnerHTML` doit etre utilise avec prudence et
uniquement lorsque vous etes sur de la securite du contenu.

</details>

<details>
<summary>68. Qu'est-ce que ReactDOMServer ?</summary>

#### React

**`ReactDOMServer`** est une bibliotheque incluse dans React, utilisee pour
rendre des composants React sur le serveur, c'est-a-dire pour le rendu cote
serveur (SSR). Cela permet de generer du HTML sur le serveur et de l'envoyer au
client, ce qui peut ameliorer les performances et le SEO.

#### Methodes principales :

1. **`ReactDOMServer.renderToString()` :** rend les elements React en chaine
   HTML. C'est la methode principale pour generer un HTML statique lors du
   chargement initial de la page.

```jsx
import ReactDOMServer from 'react-dom/server';
const html = ReactDOMServer.renderToString(<App />);
```

2. **`ReactDOMServer.renderToStaticMarkup()` :** rend du HTML sans attributs
   supplementaires lies a React, comme `data-reactroot`. C'est adapte a la
   creation de pages completement statiques.

```jsx
const html = ReactDOMServer.renderToStaticMarkup(<App />);
```

3. **`ReactDOM.hydrate()` :** est utilise cote client pour "hydrater" le HTML
   rendu par le serveur, c'est-a-dire pour rattacher l'interactivite React a un
   HTML deja present.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

#### Utilisation :

- **SSR (Server-Side Rendering)** : approche dans laquelle les composants React
  sont rendus sur le serveur, et non dans le navigateur, afin d'envoyer une
  page HTML deja complete au client.

- **SEO** : comme le serveur envoie directement le contenu HTML, les moteurs de
  recherche peuvent indexer les pages sans devoir executer JavaScript.

Ainsi, `ReactDOMServer` permet de creer des pages pre-rendues, ce qui ameliore
la vitesse de chargement et peut etre utile pour le SEO.

</details>

<details>
<summary>69. A quoi sert le package react-dom ?</summary>

#### React

Le package `react-dom` sert a faire interagir React avec le DOM reel dans les
applications web. Fonctions principales :

1. **`ReactDOM.render()` :** utilise pour rendre un composant dans le DOM reel.
   C'est la methode principale qui relie React aux elements HTML.

```jsx
ReactDOM.render(<App />, document.getElementById('root'));
```

2. **`ReactDOM.hydrate()` :** utilise pour hydrater du HTML rendu cote serveur,
   par exemple en SSR. Cela permet a React de prendre le controle d'un HTML
   deja present.

```jsx
ReactDOM.hydrate(<App />, document.getElementById('root'));
```

3. **`ReactDOM.createPortal()` :** permet de rendre des elements enfants a un
   autre endroit du DOM, en dehors de la hierarchie habituelle des composants.
   C'est souvent utilise pour les modales, les tooltips et les elements
   flottants.

```jsx
ReactDOM.createPortal(<Modal />, document.getElementById('modal-root'));
```

4. **`ReactDOM.unmountComponentAtNode()` :** supprime un composant React du
   DOM.

```jsx
ReactDOM.unmountComponentAtNode(document.getElementById('root'));
```

5. **`ReactDOM.findDOMNode()` :** donne acces a l'element DOM reel d'un
   composant. Cette methode est rarement utilisee, car les refs sont
   aujourd'hui privilegiees.

- Ce package est necessaire pour travailler avec le DOM reel, mais dans la
  plupart des cas, apres l'installation initiale, vous n'avez pas besoin
  d'appeler ces methodes manuellement, car elles sont souvent utilisees
  automatiquement par les outils de compilation et de rendu.

</details>

<details>
<summary>70. Comment utiliser React.lazy et React.Suspense pour charger le code de l'application ?</summary>

#### React

`React.lazy` et `React.Suspense` servent au **chargement dynamique des
composants** dans React, ce qui permet de faire du **decoupage de code** (`code
splitting`). Cela signifie que certaines parties du code ne sont chargees que
lorsqu'elles sont necessaires, ce qui ameliore les performances de
l'application.

#### Comment cela fonctionne :

1. **`React.lazy()`** permet de charger un composant de maniere differee.

2. **`React.Suspense`** sert a encapsuler une partie du code qui n'est pas
   encore chargee et permet d'afficher un contenu de secours, par exemple un
   loader, jusqu'au chargement du composant.

#### Exemple :

1. **Chargement dynamique d'un composant :** commencez par creer un composant
   qui sera charge dynamiquement.

```jsx
// Composant charge dynamiquement
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Encapsulation avec `React.Suspense` :** utilisez ensuite
   `React.Suspense` pour afficher un loader pendant le chargement du composant.

```jsx
function App() {
  return (
    <div>
      <h1>Mon application</h1>

      {/* Conteneur pour les composants charges dynamiquement */}
      <React.Suspense fallback={<div>Chargement...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Description :**

- `React.lazy()` prend une fonction qui importe dynamiquement le module.

- `React.Suspense` encapsule le composant charge via `React.lazy()` et affiche
  un contenu de secours, ici le texte "Chargement...", jusqu'a ce que le
  composant soit disponible.

#### Avantages :

- Ameliore les performances en chargeant les composants uniquement lorsque
  c'est necessaire.

- Reduit la taille du chargement initial, car des parties de l'application sont
  chargees a la demande.

Cette approche est particulierement utile dans les grandes applications, ou le
code peut etre decoupe en parties afin de reduire le temps de chargement de la
page.

</details>

<details>
<summary>71. Quelles sont les meilleures pratiques de securite dans React ?</summary>

#### React

#### Meilleures pratiques de securite dans React :

1. **Prevention du XSS (Cross-Site Scripting) :**

- Nettoyez toujours les donnees provenant de l'utilisateur avant de les
  afficher dans un composant.
- Utilisez JSX. React echappe automatiquement les entrees, mais il faut eviter
  autant que possible `dangerouslySetInnerHTML`.
- Si `dangerouslySetInnerHTML` est necessaire, assurez-vous que le contenu est
  nettoye de maniere fiable.

2. **Evitez les injections de code :**

- Ne passez jamais de donnees non verifiees a `eval()`, `setTimeout()`,
  `setInterval()` ou a d'autres fonctions qui executent du code.
- Pour les imports dynamiques, utilisez des mecanismes avec controle integre,
  par exemple `React.lazy()`.

3. **Acces securise aux API :**

- Utilisez HTTPS pour proteger les donnees transmises sur le reseau.
- Mettez en place authentification, autorisation et cookies securises
  (`HttpOnly`, `Secure`).

4. **Protection contre le CSRF (Cross-Site Request Forgery) :**

- Utilisez des jetons CSRF pour verifier toutes les requetes qui modifient des
  donnees sur le serveur.
- Utilisez l'attribut `SameSite` pour les cookies afin de limiter leur acces au
  meme domaine.

5. **Controle d'acces :**

- Verifiez que l'utilisateur a bien les droits necessaires avant d'envoyer une
  requete au serveur.
- Ne faites pas confiance aux verifications cote client. Les controles cote
  serveur doivent rester definitifs.

6. **Protection des champs de saisie :**

- Pour les formulaires et champs qui recoivent des donnees utilisateur,
  appliquez des restrictions sur les valeurs autorisees.

7. **Mise a jour des dependances :**

- Verifiez et mettez a jour regulierement les dependances pour detecter
  d'eventuelles vulnerabilites. Utilisez `npm audit` ou des outils similaires.

8. **Gestion des secrets :**

- Ne stockez pas les secrets comme les cles API ou les mots de passe dans le
  code client. Ils doivent rester cote serveur ou dans des environnements
  appropries, par exemple des variables d'environnement.

9. **Utilisation de la Content Security Policy (CSP) :**

- Utilisez une CSP pour empecher l'execution de scripts indesirables sur votre
  site.

10. **Protection contre le clickjacking :**

- Utilisez les en-tetes `X-Frame-Options` ou `Content-Security-Policy` pour
  empecher que votre site soit integre dans une balise `<iframe>` sur d'autres
  sites.

Le respect de ces pratiques aide a reduire les risques de securite dans les
applications React.

</details>

<details>
<summary>72. Comment gerer les erreurs dans React avec Error Boundary ?</summary>

#### React

Les **Error Boundaries** dans React permettent d'intercepter les erreurs dans
les composants pendant le rendu, dans les methodes du cycle de vie et dans les
constructeurs, puis de les gerer sans faire planter toute l'application.

#### Points principaux :

- Une Error Boundary est un composant qui encapsule d'autres composants et peut
  intercepter les erreurs qui surviennent dans leur code.

- Les **Error Boundaries** intercepteront uniquement les erreurs de leurs
  descendants. Elles ne capturent pas leurs propres erreurs.

#### Comment implementer une Error Boundary :

1. **Creation d'une Error Boundary :** il faut implementer deux methodes :

- `static getDerivedStateFromError(error)` met a jour l'etat lorsqu'une erreur
  survient.

- `componentDidCatch(error, info)` permet de journaliser les erreurs, par
  exemple en les envoyant au serveur.

```jsx
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }

  static getDerivedStateFromError(error) {
    // Met a jour l'etat afin d'afficher une interface de secours
    return { hasError: true, error };
  }

  componentDidCatch(error, info) {
    // Logique de journalisation des erreurs, par exemple vers un serveur
    console.error('Error caught:', error, info);
  }

  render() {
    if (this.state.hasError) {
      // Affiche une interface de secours lorsqu'une erreur survient
      return <h1>Une erreur est survenue.</h1>;
    }

    return this.props.children;
  }
}
```

2. **Utilisation de l'Error Boundary :** encapsulez dans `ErrorBoundary` les
   composants susceptibles de provoquer des erreurs.

```jsx
const App = () => {
  return (
    <ErrorBoundary>
      <MyComponent />
    </ErrorBoundary>
  );
};
```

3. **Interface de secours :** lorsqu'une erreur se produit, l'Error Boundary
   peut afficher une interface alternative, par exemple un message d'erreur, un
   bouton de nouvelle tentative ou une action de recuperation.

#### Points importants :

- Une Error Boundary n'intercepte pas les erreurs dans les gestionnaires
  d'evenements comme `onClick`, le code asynchrone, les timers ou les requetes
  reseau. Pour ces cas, utilisez `try...catch` ou d'autres mecanismes.

- Si l'erreur survient dans l'Error Boundary elle-meme, elle ne sera pas
  capturee.

Les **Error Boundaries** sont utiles pour stabiliser l'application, car elles
permettent de capter et de traiter les erreurs sans arreter l'ensemble du
systeme.

</details>

<details>
<summary>73. Qu'est-ce que l'inversion d'heritage (Inheritance Inversion) ?</summary>

#### React

L'**inversion d'heritage** est une situation dans laquelle une classe qui
devrait etre de base depend en pratique de ses descendants ou perd le controle
de la logique qui devrait rester dans la hierarchie d'heritage.

#### Problemes lies a l'inversion d'heritage

- Violation du principe de substitution de Liskov (LSP).

- Il devient difficile de modifier ou d'etendre la classe de base sans impacter
  tous ses descendants.

- La complexite augmente a cause des interdependances.

#### Exemple de mauvaise pratique

```js
class Parent {
  method() {
    throw new Error('La methode doit etre implementee dans le descendant');
  }
}

class Child extends Parent {
  method() {
    return 'Implementation dans le descendant';
  }
}
```

Ici, la classe de base n'a pas sa propre logique et oblige les descendants a
implementer le comportement, ce qui est un signe d'inversion d'heritage.

#### Alternative : la composition plutot que l'heritage

```js
class Behavior {
  method() {
    return 'Implementation sans inversion';
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

Cette approche supprime la dependance de la classe parente envers ses
descendants et rend le code plus souple.

</details>

<details>
<summary>74. Qu'est-ce que le polling et comment le mettre en oeuvre dans React ?</summary>

#### React

Le **polling** consiste a envoyer periodiquement des requetes au serveur afin
d'obtenir des donnees mises a jour. C'est utile lorsque le serveur ne prend pas
en charge les WebSockets ou les Server-Sent Events, mais que le client doit
recevoir de nouvelles informations sans recharger la page.

#### Mise en oeuvre du polling dans React

Le polling peut etre mis en oeuvre avec `setInterval`, `setTimeout` ou a l'aide
des hooks React comme `useEffect`.

1. **Utilisation de `setInterval`**

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

    fetchData(); // Executer immediatement au chargement

    const interval = setInterval(fetchData, 5000); // Polling toutes les 5 sec.

    return () => clearInterval(interval); // Nettoyage au demontage
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Chargement...'}</div>;
};
```

- `fetchData()` recupere les donnees depuis le serveur.
- `setInterval` lance un polling toutes les 5 secondes.
- `clearInterval` arrete le polling au demontage.

2. **Utilisation de `setTimeout` pour un intervalle dynamique**

Si le serveur impose des limites sur les requetes, il vaut mieux utiliser
`setTimeout` pour eviter le chevauchement des appels.

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
        console.error('Erreur de requete', error);
      } finally {
        if (isMounted) setTimeout(fetchData, 5000);
      }
    };

    fetchData();

    return () => {
      isMounted = false; // Evite de mettre a jour l'etat apres le demontage
    };
  }, []);

  return <div>{data ? JSON.stringify(data) : 'Chargement...'}</div>;
};
```

Ici, `setTimeout` n'est appele qu'une fois la requete precedente terminee, ce
qui evite le chevauchement des appels.

#### Conclusion

- `setInterval` convient a un polling constant, mais peut provoquer des appels
  qui se chevauchent.
- `setTimeout` offre plus de controle et convient mieux a un polling adaptatif.
- En cas de forte charge, il vaut mieux envisager WebSockets ou Server-Sent
  Events.

</details>

<details>
<summary>75. Comment mettre en oeuvre une liaison bidirectionnelle des donnees dans React ?</summary>

#### React

Dans React, la liaison bidirectionnelle des donnees se met en oeuvre au moyen
de **composants controles**, ou l'etat (`state`) du composant est synchronise
avec le champ de saisie (`input`).

#### Exemple d'implementation

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
      <p>Valeur saisie : {value}</p>
    </div>
  );
};

export default TwoWayBinding;
```

#### Comment cela fonctionne-t-il ?

1. **`value`** conserve l'etat actuel de la valeur saisie.

2. **`onChange`** met a jour l'etat lorsque l'`input` change.

3. **La valeur `value` mise a jour** s'affiche dans l'interface, ce qui assure
   la liaison dans les deux sens.

Cette approche permet de controler les donnees saisies, d'ajouter de la
validation et de traiter l'entree avant la mise a jour de l'etat.

</details>

<details>
<summary>76. Qu'est-ce que le flux de donnees inverse (Reverse Data Flow) dans React ?</summary>

#### React

Le flux de donnees inverse dans React designe la transmission de changements
d'etat d'un composant enfant vers un composant parent. C'est l'inverse du flux
habituel, ou le parent transmet des props a l'enfant.

#### Dans React, ce flux inverse est generalement mis en oeuvre via :

1. **Des fonctions callback :**

- Le composant enfant appelle un callback recu via les props afin d'informer le
  composant parent d'un changement ou de declencher une action.

- Par exemple, lorsqu'une valeur change dans le composant enfant, celui-ci peut
  appeler une fonction du parent qui met a jour l'etat.

2. **Exemple :**

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

- Dans cet exemple, le composant enfant transmet une valeur au parent via la
  fonction `onValueChange`, ce qui realise le flux de donnees inverse.

</details>

<details>
<summary>77. Qu'est-ce que la mutation de l'etat et comment l'eviter ?</summary>

#### React

La mutation de l'etat consiste a modifier directement un objet ou un tableau qui
represente l'etat, sans en creer de copie. Dans React, cela conduit a des
resultats imprevisibles, car React ne detecte pas toujours ce changement et ne
rerend pas le composant.

#### Pour eviter la mutation de l'etat, il faut :

1. **Creer des copies des donnees** avant de les modifier. Par exemple, pour
   les tableaux et les objets :

- Pour les tableaux : `setItems([...items, newItem])`
- Pour les objets : `setUser({ ...user, name: 'John' })`

2. **Utiliser des methodes non mutantes** comme `map()`, `filter()` ou
   `reduce()` pour les tableaux, ou `Object.assign()` pour les objets.

Cela permet a React de suivre correctement les changements et de rerendre les
composants.

 </details>

<details>
<summary>78. Qu'est-ce que le mode strict (Strict Mode) dans React et quels sont ses avantages ?</summary>

#### React

**Strict Mode** est un outil special de React qui aide a detecter les problemes
potentiels dans le code. Il n'affecte pas le comportement en production, mais
ameliore la qualite du code pendant le developpement.

Il s'active en encapsulant les composants dans `<React.StrictMode>` :

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

#### Avantages de Strict Mode

| **Fonction** | **Description** |
| ------------ | --------------- |
| **Detection des methodes de cycle de vie dangereuses** | Signale les methodes obsoletes comme `componentWillMount`, `componentWillReceiveProps` et `componentWillUpdate`. |
| **Double appel des fonctions en developpement** | Aide a reperer les effets de bord dans `useEffect` et d'autres hooks. |
| **Avertissements sur les API obsoletes** | Signale les anciens contextes comme `contextType` et les patterns dangereux. |
| **Detection des comportements imprevisibles** | Par exemple, appelle `useEffect` deux fois pour verifier que le nettoyage des effets est correct. |

#### Faut-il l'utiliser ?

Oui, si vous voulez eviter des problemes des la phase de developpement. Le
double rendu peut sembler agaçant, mais il aide a reveler des erreurs cachees.

</details>

<details>
<summary>79. Quelles sont les methodes recommandees pour verifier les types statiques ?</summary>

#### React

1. **TypeScript** : c'est l'approche la plus populaire et la plus complete pour
   la typage statique en JavaScript et React. TypeScript ajoute des types
   stricts au code et permet de verifier les types a la compilation.

2. **PropTypes** : mecanisme de validation des types de props dans les
   composants React. Il fonctionne a l'execution. Cela n'apporte pas un typage
   statique a la compilation, mais permet de verifier les props pendant
   l'execution de l'application.

```jsx
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
};
```

3. **Flow** : autre solution de typage statique pour JavaScript. Flow est moins
   populaire que TypeScript, mais il permet lui aussi d'ajouter des types et de
   les verifier a la compilation.

4. **ESLint avec des plugins de typage** : on peut utiliser ESLint avec des
   plugins comme `eslint-plugin-flowtype` ou ceux lies a TypeScript, mais cela
   n'offre pas la meme profondeur de typage que TypeScript lui-meme.

Je recommande **TypeScript**, car il s'integre bien avec React et les autres
outils, tout en fournissant un typage statique complet a la compilation.

</details>

<details>
<summary>80. Comment implementer des animations dans React ?</summary>

#### React

1. **Animations CSS** : la methode la plus simple consiste a utiliser les
   animations ou transitions CSS standards.

```jsx

<div className="my-element">Bonjour</div>

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

2. **React Transition Group** : pour des transitions plus complexes entre
   composants. Ce package permet de gerer l'animation lors de l'ajout ou de la
   suppression de composants.

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

3. **Framer Motion** : bibliotheque puissante qui permet de mettre en place des
   animations complexes dans React.

```jsx
import { motion } from 'framer-motion';

<motion.div
  animate={{ opacity: 1 }}
  initial={{ opacity: 0 }}
  transition={{ duration: 1 }}
>
  Bonjour
</motion.div>;
```

4. **React Spring** : pour des animations basees sur des modeles physiques, qui
   permettent des mouvements plus realistes.

```jsx
import { useSpring, animated } from 'react-spring';

const props = useSpring({ opacity: 1, from: { opacity: 0 } });

<animated.div style={props}>Bonjour</animated.div>;
```

5. **Styles inline et JavaScript** : on peut utiliser `setState` ou les setters
   d'etat pour modifier les styles selon l'etat du composant.

```jsx
const [opacity, setOpacity] = useState(0);

useEffect(() => {
  setOpacity(1);
}, []);

return <div style={{ opacity }}>Bonjour</div>;
```

Pour des effets d'animation plus complexes, il est recommande d'utiliser
**Framer Motion** ou **React Spring**, car ces bibliotheques offrent davantage
de possibilites et facilitent la gestion d'animations avancees.

</details>

<details>
<summary>81. Quels sont les packages d'animation les plus populaires dans React ?</summary>

#### React

#### Packages d'animation populaires dans React :

1. **Framer Motion** est l'un des packages d'animation les plus populaires dans
   React. Il est simple a utiliser, prend en charge les animations et les
   transitions, fonctionne avec le drag-and-drop et offre une API puissante
   pour creer des animations complexes.

2. **React Spring** est une bibliotheque pour creer des animations basees sur
   la physique. Elle repose sur des notions comme l'elasticite et la friction,
   et convient bien aux animations complexes et aux interactions riches.

3. **GSAP (GreenSock Animation Platform)** est une bibliotheque d'animation
   puissante qui fonctionne non seulement avec React, mais aussi avec d'autres
   frameworks. Elle est connue pour sa rapidite et sa capacite a produire des
   animations tres avancees.

4. **React Transition Group** est la bibliotheque de reference pour les
   animations de transition dans React. Elle permet de gerer les animations
   d'entree, de sortie et de changement d'etat des composants.

5. **Lottie for React** permet d'integrer facilement des animations creees dans
   After Effects au format JSON. C'est utile pour des animations complexes,
   comme des icones animees ou des elements interactifs.

</details>

<details>
<summary>82. React DevTools : comment les utiliser pour le debogage ?</summary>

#### React

1. **Installation de React DevTools**

- Si vous utilisez `Chrome` ou `Firefox`, installez simplement l'extension
  `React Developer Tools` :
- Chrome Web Store
- Firefox Add-ons

- Si vous deboguez `Electron`, `React Native` ou un autre environnement non
  standard, installez :

```sh
npm install -g react-devtools
react-devtools
```

2. **Onglets principaux et leur usage**

- ⚛ **Components** -> visualisation de l'arborescence des composants, de
  l'etat et des props.
- ⚡ **Profiler** -> analyse des performances et detection des rerendus
  inutiles.

3. **Debogage des props et de l'etat**

- Ouvrez l'onglet Components.
- Selectionnez un composant -> vous verrez ses `props`, son `state` et son
  `context`.
- Vous pouvez modifier `state` et `props` directement dans `DevTools` pour
  tester des changements de comportement.

4. **Detection des rerendus inutiles**

- Dans l'onglet Profiler, cliquez sur `Record`, effectuez l'interaction voulue,
  puis cliquez sur `Stop`.
- Verifiez le marquage en couleur :
- **Rouge** -> rendu couteux.
- **Jaune** -> cout moyen.
- **Bleu** -> rendu leger.
- Optimisez les composants avec `React.memo()`, `useMemo()` et `useCallback()`.

5. **Outils pour deboguer Context API**

- Si vous utilisez React Context, vous pouvez verifier ses valeurs dans
  DevTools.
- Selectionnez un composant qui utilise `useContext()` et consultez l'onglet
  Context.

6. **Debogage du rendu en Strict Mode**

- Si `React DevTools` montre qu'un composant est rendu deux fois, verifiez
  `StrictMode` dans `index.js` :

```jsx
<React.StrictMode>
  <App />
</React.StrictMode>
```

- Cela ne cree pas de bugs en soi, mais aide a reveler des problemes potentiels.

7. **Inspection des hooks**

- DevTools permet de voir l'etat des hooks comme `useState`, `useEffect` ou
  `useReducer`.
- Dans l'onglet Components, selectionnez un composant -> vous verrez l'etat
  de `useState`.

#### Conclusion :

**React DevTools** est un outil puissant pour deboguer l'etat, les props, les
performances et le contexte. Utilisez Profiler pour l'optimisation et
Components pour suivre les changements d'etat et de props.

</details>

<details>
<summary>83. Quels sont les linters les plus populaires pour React ?</summary>

#### React

#### Linters les plus populaires pour React :

1. **ESLint** est le linter le plus repandu pour `JavaScript`. Il prend en
   charge `React` via le plugin `eslint-plugin-react`, verifie le style du code,
   signale les erreurs et peut fonctionner avec d'autres outils comme
   `Prettier`.

2. **Prettier** est un outil de formatage automatique du code, souvent utilise
   avec `ESLint` pour garantir un style uniforme.

3. **TSLint** etait un linter pour `TypeScript` qui pouvait aussi etre utilise
   avec `React`, meme s'il est aujourd'hui largement remplace par `ESLint`,
   plus souple et mieux maintenu.

Ces outils aident a maintenir une bonne qualite de code et a prevenir les
erreurs dans les grands projets.

</details>

<details>
<summary>84. Qu'est-ce que Next.js ?</summary>

#### React

**Next.js** est un framework base sur React qui fournit des solutions pretes a
l'emploi pour le rendu cote serveur (SSR), la generation statique (SSG), les
routes API, le routage, l'optimisation des performances et le SEO.

#### Fonctionnalites principales :

- **Rendu hybride** : prise en charge du SSR, du SSG et de l'ISR.
- **Routage automatique** : les fichiers dans `pages/` deviennent
  automatiquement des routes.
- **Routes API** : creation d'endpoints serveur dans `pages/api/*`.
- **Optimisation des performances** : code splitting automatique, reduction de
  la taille du bundle.
- **Prise en charge de l'App Router** : nouvelle approche basee sur les React
  Server Components avec `app/` au lieu de `pages/`.
- **Support integre de Tailwind, TypeScript, ESLint et d'autres technologies**.

Il est utilise pour creer des applications web performantes, des blogs, des
solutions e-commerce et des interfaces complexes.

</details>

<details>
<summary>85. Quelles sont les principales differences entre Next.js et React ?</summary>

#### React

#### Principales differences entre Next.js et React :

| **Critere** | **React** | **Next.js** |
| ----------- | --------- | ----------- |
| **Type** | Bibliotheque pour construire des UI | Framework base sur React |
| **Rendu** | Principalement cote client (CSR) | Prend en charge CSR, SSR, SSG et ISR |
| **Routage** | Mis en place manuellement, souvent via React Router | Routage base sur les fichiers (`pages/` ou `app/`) |
| **SEO** | Moins bon avec un pur CSR | Bonne prise en charge du SEO grace au SSR et au SSG |
| **Routes API** | Aucune prise en charge integree | Possibilite integree de creer des endpoints API (`pages/api/`) |
| **Cache** | Pas de mecanismes integres | ISR permet de mettre a jour les pages sans regeneration complete |
| **Optimisation des performances** | Souvent via des solutions tierces | Optimisations integrees comme le code splitting et le chargement optimise des images |
| **Support des composants serveur** | Depend de la configuration | Support integre des React Server Components via `app/` |

#### Conclusion :

- **React** convient bien aux SPA rendues cote client.

- **Next.js** convient mieux aux projets optimises pour le SEO, au rendu
  hybride et aux applications web performantes.

</details>

<details>
<summary>86. A quoi sert React Helmet Async ?</summary>

#### React

**React Helmet Async** est une version optimisee de **React Helmet**, utilisee
pour mettre a jour dynamiquement le contenu de `<head>` dans les applications
React, par exemple les meta tags, les titres ou les donnees Open Graph.

#### Pourquoi en a-t-on besoin ?

1. **Optimisation SEO** : permet de modifier les titres de page, les
   meta-descriptions et les mots-cles.

2. **`<head>` dynamique** : les balises peuvent etre mises a jour pour chaque
   page sans rechargement.

3. **Prise en charge du SSR** : contrairement a React Helmet classique, cette
   version fonctionne correctement dans les applications SSR sans problemes
   d'asynchronisme.

#### Exemple d'utilisation :

```jsx
import { Helmet } from 'react-helmet-async';

function MyComponent() {
  return (
    <Helmet>
      <title>Page d'accueil</title>
      <meta name="description" content="Description de la page d'accueil" />
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

#### Pourquoi est-ce preferable a `react-helmet` ?

- Prend en charge le SSR sans erreurs liees a l'asynchronisme.
- Est plus leger et plus rapide.
- Ne cree pas de problemes avec `StrictMode`.

#### Conclusion :

Si vous avez besoin de SEO dans une application React avec SSR, il vaut mieux
utiliser `react-helmet-async`.

</details>

<details>
<summary>87. Qu'est-ce qu'un composant distribue (Distributed Component) ?</summary>

#### React

Un **composant distribue** est une conception dans laquelle un composant est
decompose en plusieurs parties independantes pouvant etre rendues ou executer
leur logique separement, tout en fonctionnant ensemble.

#### Exemples d'implementation :

1. **Code Splitting**

- Les composants ne sont charges qu'en cas de besoin, ce qui reduit la taille
  initiale du bundle.

```jsx
import { lazy, Suspense } from 'react';

const LazyComponent = lazy(() => import('./LazyComponent'));

function App() {
  return (
    <Suspense fallback={<div>Chargement...</div>}>
      <LazyComponent />
    </Suspense>
  );
}
```

2. **Composants conteneurs (Container-Presentational Pattern)**

- Separe la logique, portee par le conteneur, et l'affichage, confie au
  composant de presentation.

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
  return <div>{data ? JSON.stringify(data) : 'Chargement...'}</div>;
}

function App() {
  return (
    <DataContainer>{data => <Presentational data={data} />}</DataContainer>
  );
}
```

3. **Micro-frontends**

- Utilisation de composants autonomes separes dans differentes parties de
  l'application.
- Par exemple, differentes equipes developpent des parties d'un grand projet en
  `React`, `Vue` ou `Angular`, puis les integrent ensemble.

#### Quand l'utiliser :

- Pour optimiser les performances, notamment via le chargement paresseux.

- Pour simplifier la maintenance du code en separant la logique.

- Pour les applications evolutives, par exemple avec des micro-frontends.

</details>

<details>
<summary>88. Qu'est-ce qu'un composant de commutation (Switching Component) ?</summary>

#### React

Un **composant de commutation** dans React est un pattern ou un composant rend
dynamiquement l'un de ses composants enfants selon une condition donnee. Cela
est utile lorsqu'il faut afficher des composants differents selon l'etat, la
route ou les donnees recues.

#### Exemple 1 : commutation selon l'etat

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

- `type` determine quel composant sera affiche.

#### Exemple 2 : utilisation avec React Router

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

- Ici, `Routes` agit comme un composant de commutation qui rend le composant
  approprie selon l'URL.

#### Exemple 3 : rendu conditionnel via un objet

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

- C'est une variante plus propre, sans utiliser `switch`.

Les composants de commutation simplifient la logique et rendent le code plus
lisible lorsqu'il faut afficher conditionnellement plusieurs composants.

</details>

<details>
<summary>89. Qu'est-ce que Reselect et comment fonctionne-t-il ?</summary>

#### React

**Reselect** est une bibliotheque qui permet de creer des selecteurs efficaces
dans Redux. Elle aide a optimiser l'extraction des donnees depuis l'etat et a
eviter des rerendus inutiles de composants grace a la memoisation.

#### Comment fonctionne Reselect ?

Reselect utilise la **memoisation** pour reutiliser les resultats des calculs
si les donnees d'entree n'ont pas change.

1. **Accepte des input selectors** qui recuperent des donnees depuis l'etat.

2. **Calcule une valeur** a partir des donnees recuperees.

3. **Met le resultat en cache** afin d'eviter de refaire le calcul lorsque les
   valeurs d'entree sont identiques.

#### Exemple d'utilisation :

```jsx
import { createSelector } from 'reselect';

// Le selecteur d'entree recupere tous les utilisateurs
const selectUsers = state => state.users;

// Le selecteur d'entree recupere le filtre actif
const selectFilter = state => state.filter;

// Le selecteur memoise filtre les utilisateurs
export const selectFilteredUsers = createSelector(
  [selectUsers, selectFilter],
  (users, filter) => users.filter(user => user.role === filter)
);
```

- Sans Reselect, le composant analyserait tout le tableau `users` a chaque
  rendu.
- Avec Reselect, le selecteur ne s'execute que lorsque `users` ou `filter`
  change.

#### Avantages de Reselect :

- Reduit le nombre d'appels inutiles a `mapStateToProps`.
- Evite les rerendus inutiles des composants.
- S'integre facilement avec Redux.
- Ameliore les performances.

</details>

<details>
<summary>90. Quels types de donnees render peut-il retourner ?</summary>

#### React

La methode `render()` dans React peut retourner :

1. **Du JSX ou un element React**

```jsx
render() {
return <div>Hello, World!</div>;
}
```

2. **Un tableau d'elements**

```jsx
render() {
return [
<li key="1">Item 1</li>,
<li key="2">Item 2</li>
];
}
```

3. **Des fragments (`React.Fragment`)**

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

4. **`null` pour ne rien rendre**

```jsx
render() {
return null;
}
```

5. **Des valeurs booleennes, qui sont ignorees**

```jsx
render() {
return false; // Rien ne sera affiche
}
```

6. **Des valeurs textuelles, rendues comme du texte**

```jsx
render() {
return "Hello, World!";
}
```

7. **Des portails, pour rendre dans un element DOM hors du composant parent**

```jsx
import { createPortal } from "react-dom";

render() {
return createPortal(<div>Modal</div>, document.getElementById("modal-root"));
}
```

#### Conclusion :

Le cas principal reste le JSX ou les elements React, mais il est aussi possible
de retourner des tableaux, des fragments, `null`, du texte ou des portails.

</details>

<details>
<summary>91. Comment React gere-t-il ou limite-t-il l'utilisation de props d'un certain type ?</summary>

#### React

React limite ou verifie l'utilisation de props d'un certain type a l'aide de
`PropTypes` ou de `TypeScript`.

1. **Utilisation de PropTypes, pour une verification integree des types**

```jsx
import PropTypes from 'prop-types';

const MyComponent = ({ name, age, isActive }) => {
  return (
    <div>
      <h1>{name}</h1>
      <p>Age : {age}</p>
      <p>{isActive ? 'Actif' : 'Inactif'}</p>
    </div>
  );
};

// Definition des types de props
MyComponent.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number,
  isActive: PropTypes.bool,
};
```

- `PropTypes.string.isRequired` : `name` est une prop obligatoire.
- `PropTypes.number` : `age` doit etre un nombre.
- `PropTypes.bool` : `isActive` doit etre une valeur booleenne.

Si des types incorrects sont passes, React affichera un avertissement dans la
console, uniquement en mode developpement.

2. **Utilisation de TypeScript, pour une verification stricte a la compilation**

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
      <p>Age : {age}</p>
      <p>{isActive ? 'Actif' : 'Inactif'}</p>
    </div>
  );
};
```

- `name: string` : prop chaine obligatoire.
- `age?: number` : prop numerique facultative.
- `isActive: boolean` : prop booleenne obligatoire.

TypeScript signale une erreur avant meme l'execution si des props incorrectes
sont passees.

#### Que choisir ?

| **Methode** | **Avantages** | **Inconvenients** |
| ----------- | ------------- | ----------------- |
| **PropTypes** | Simple, fonctionne en JavaScript | Verifie seulement a l'execution, protection limitee |
| **TypeScript** | Typage strict, detecte les erreurs plus tot | Necessite une compilation, syntaxe plus complexe |

Si le projet utilise **TypeScript**, **PropTypes** est souvent inutile. Si le
projet est en **JavaScript**, **PropTypes** fournit une verification de base.

</details>

<details>
<summary>92. Quelle est la difference entre rendu et montage ?</summary>

#### React

Difference entre rendu et montage dans React

| **Processus** | **Description** |
| ------------- | --------------- |
| **Montage (Mounting)** | Le composant est cree et ajoute au DOM pour la premiere fois. Cela declenche `constructor`, `render`, `componentDidMount` dans les classes, ou `useEffect` avec un tableau vide dans les composants fonctionnels. |
| **Rendu (Rendering)** | `render()` ou le composant fonctionnel est execute pour mettre a jour le contenu. Cela se produit quand `state`, `props` ou `forceUpdate()` changent. |

#### Exemple de montage

```jsx
useEffect(() => {
  console.log('Composant monte');
}, []); // S'execute une seule fois au montage
```

#### Exemple de rendu

```jsx
const [count, setCount] = useState(0);

useEffect(() => {
  console.log('Le composant a ete rendu');
}); // S'execute a chaque rendu

return <button onClick={() => setCount(count + 1)}>+</button>;
```

Ici, le rendu se produit a chaque changement de `count`.

</details>

<details>
<summary>93. Qu'est-ce que le flux de donnees reactif dans React ?</summary>

#### React

Le **flux de donnees reactif** dans React signifie que les changements dans le
state ou les props d'un composant entrainent automatiquement une mise a jour de
l'interface, sans avoir a declencher manuellement un rerendu.

#### Principes principaux :

1. **Flux de donnees a sens unique** : React transmet les donnees du haut vers
   le bas, des composants parents vers les enfants.

2. **Declarativite** : on decrit ce qui doit etre affiche, et React se charge
   lui-meme des mises a jour.

3. **Mise a jour automatique** : si le state ou les props changent, React
   rerend uniquement les parties necessaires.

#### Exemple de mise a jour reactive :

```jsx
import { useState } from 'react';

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <div>
      <p>Compteur : {count}</p>
      <button onClick={() => setCount(count + 1)}>Incrementer</button>
    </div>
  );
}
```

#### Comment cela fonctionne-t-il ?

- `useState` cree l'etat `count`.

- Au clic, `setCount(count + 1)` met a jour l'etat.

- React rerend automatiquement le composant avec les nouvelles donnees.

#### React est-il completement reactif ?

- Non. Contrairement a des frameworks plus "reactifs" comme Svelte ou
  Solid.js, React ne met pas le DOM a jour lorsqu'une simple variable change.
  Il utilise le Virtual DOM et declenche un rerendu quand `state` ou `props`
  changent.

#### Conclusion :

- Le flux de donnees reactif dans React signifie que l'interface se met
  automatiquement a jour lorsque l'etat change, mais via le Virtual DOM et le
  batching des mises a jour pour optimiser le rendu.

</details>

<details>
<summary>94. React est-il reactif ?</summary>

#### React

React n'est pas une bibliotheque purement reactive comme Vue ou Svelte.
Cependant, il possede certaines caracteristiques qui le rapprochent des
frameworks reactifs :

1. **Mise a jour automatique de l'UI** : React met automatiquement a jour
   l'interface lorsque le state ou les props changent. Cela rappelle les
   approches reactives et passe par le rendu et la comparaison des changements.

2. **Composants fonctionnels et hooks** : l'utilisation de hooks comme
   `useState` et `useEffect` cree un effet de reactivite, ou les changements
   d'etat ou de props provoquent un nouveau rendu.

3. **Reactivite partielle** : React ne rerend que les composants dont le state
   ou les props ont change. C'est une forme de reactivite, mais contrairement a
   d'autres frameworks, React n'utilise pas des observateurs automatiques pour
   suivre les dependances.

Ainsi, React applique certains principes reactifs, mais n'est pas un framework
entierement reactif.

</details>

<details>
<summary>95. Quelles options connaissez-vous pour implementer le drag-and-drop dans React ?</summary>

#### React

Le drag-and-drop dans React peut etre implemente de plusieurs manieres :

- **Avec l'API HTML5 native** (`onDragStart`, `onDrop`)
- **Avec des bibliotheques** comme `react-dnd` ou `dnd-kit`

1. **Utilisation de l'API Drag-and-Drop native**

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

- Simple, sans bibliotheques tierces.
- Controle limite, peu adapte aux cas complexes.

2. **Utilisation de `react-dnd`, solution plus puissante**

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

- Flexible, prend en charge des cas complexes.
- Plus pratique pour travailler avec des elements imbriques.
- Ajoute une dependance supplementaire.

3. **Utilisation de `dnd-kit`, solution simple et moderne**

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

- API moderne, plus leger que `react-dnd`.
- Simple a utiliser.
- Prend en charge le tri (`sortable`).

#### Conclusion :

- Si vous avez besoin de quelque chose de simple -> **API HTML5 native.**

- Si vous avez besoin d'un controle tres souple -> **react-dnd.**

- Si vous cherchez une solution moderne et legere -> **dnd-kit.**

</details>

<details>
<summary>96. Comment rendre du code HTML dans un composant React ?</summary>

#### React

Utilisez `dangerouslySetInnerHTML`, mais avec prudence : cela peut provoquer des
attaques XSS si vous inserez des donnees non assainies.

#### Exemple :

```jsx
function MyComponent() {
  const htmlContent = "<p style='color: red;'>Ceci est du code HTML</p>";

  return <div dangerouslySetInnerHTML={{ __html: htmlContent }} />;
}
```

Si vous travaillez avec des donnees dynamiques, assainissez-les
obligatoirement avant l'insertion.

</details>

<details>
<summary>97. Comment ajouter une classe de maniere conditionnelle dans React ?</summary>

#### React

Dans React, l'ajout conditionnel de classes se fait generalement via l'attribut
`className`, en utilisant un operateur ternaire ou des fonctions pour exprimer
la condition.

#### Principales approches :

1. **Operateur ternaire**

```jsx
function MyComponent({ isActive }) {
  return (
    <div className={isActive ? 'active-class' : 'inactive-class'}>Hello</div>
  );
}
```

- Si `isActive` vaut `true`, la classe `active-class` sera appliquee.
- Sinon, `inactive-class` sera utilisee.

2. **Templates strings**

```jsx
function MyComponent({ isHighlighted }) {
  return (
    <div className={`base-class ${isHighlighted ? 'highlighted-class' : ''}`}>
      Hello
    </div>
  );
}
```

- `base-class` est toujours ajoutee.
- Si `isHighlighted` vaut `true`, `highlighted-class` est ajoutee aussi.

3. **Bibliotheque `clsx`**

- `clsx` permet de gerer les classes de facon plus elegante.

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

- `clsx` permet d'ajouter facilement plusieurs classes selon des conditions.

4. **Bibliotheque `classnames`**

- Similaire a `clsx`, mais avec davantage de possibilites.

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

5. **Extraction de la logique dans une fonction separee**

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

- La logique de determination des classes devient plus lisible et peut etre
  reutilisee.

#### Conclusion :

- Pour les cas simples, l'operateur ternaire ou les templates strings suffisent.

- Pour des conditions plus complexes, il vaut mieux utiliser `clsx` ou
  `classnames`, qui rendent le code plus lisible et pratique.

</details>

<details>
<summary>98. Comment executer du code avant la suppression d'un composant de l'arbre ?</summary>

#### React

Pour executer du code avant la suppression d'un composant de l'arbre dans
React, on utilise les approches suivantes :

1. **Composants de classe :** `componentWillUnmount`

- Pour les composants de classe, la methode de cycle de vie
  `componentWillUnmount` est appelee juste avant la suppression du composant.

```jsx
class MyComponent extends React.Component {
  componentWillUnmount() {
    console.log('Le composant va etre supprime');
  }

  render() {
    return <div>Mon composant</div>;
  }
}
```

2. **Composants fonctionnels :** `useEffect` avec nettoyage

- Dans les composants fonctionnels, on peut effectuer le nettoyage dans
  `useEffect` en retournant une fonction qui sera executee avant la suppression
  du composant.

```jsx
import { useEffect } from 'react';

function MyComponent() {
  useEffect(() => {
    return () => {
      console.log('Le composant va etre supprime');
    };
  }, []);

  return <div>Mon composant</div>;
}
```

3. **Traitement avant la fermeture de la page (`beforeunload`)**

- Si du code doit etre execute avant la fermeture de l'onglet ou le
  rechargement de la page :

```jsx
useEffect(() => {
  const handleUnload = () => {
    console.log('La page se ferme');
  };

  window.addEventListener('beforeunload', handleUnload);
  return () => window.removeEventListener('beforeunload', handleUnload);
}, []);
```

#### Conclusion

- `componentWillUnmount` pour les composants de classe.

- `useEffect` avec `return` pour les composants fonctionnels.

- `beforeunload` pour les cas ou il faut reagir a la sortie de la page.

</details>

<details>
<summary>99. Qu'est-ce que useReducer() ?</summary>

#### React

`useReducer()` est un hook React utilise pour gerer l'etat dans les composants
fonctionnels. C'est une alternative a `useState()` adaptee aux logiques de mise
a jour complexes, surtout lorsque les changements dependent de l'etat
precedent.

#### Syntaxe :

```jsx
const [state, dispatch] = useReducer(reducer, initialState);
```

- `reducer` : fonction qui recoit `state` et `action`, puis retourne le nouvel
  etat.

- `initialState` : etat initial.

- `dispatch` : fonction qui appelle le reducer avec une `action` donnee.

#### Exemple :

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

#### Quand l'utiliser :

- Lorsque l'etat a une logique ou des dependances complexes.

- Lorsqu'il faut unifier les mises a jour de l'etat via `dispatch`.

- Pour une meilleure evolutivite, par exemple dans un etat global.

</details>

<details>
<summary>100. Comment utiliser React.lazy et React.Suspense pour charger le code de l'application ?</summary>

#### React

`React.lazy` et `React.Suspense` sont utilises pour le **chargement dynamique
des composants** dans React, ce qui permet de faire du **code splitting**. Cela
signifie que certaines parties du code sont chargees uniquement quand elles
sont necessaires, ce qui ameliore les performances de l'application.

#### Comment cela fonctionne :

1. `React.lazy()` permet de charger un composant de maniere differee.

2. `React.Suspense` encapsule une partie du code qui n'est pas encore chargee
   et permet d'afficher un contenu de secours, par exemple un loader, jusqu'au
   chargement du composant.

#### Exemple :

1. **Chargement dynamique du composant :**

- Commencez par creer un composant qui sera charge dynamiquement.

```jsx
// Composant charge dynamiquement
const MyComponent = React.lazy(() => import('./MyComponent'));
```

2. **Encapsulation avec `React.Suspense` :**

- Utilisez ensuite `React.Suspense` pour afficher un loader pendant le
  chargement du composant.

```jsx
function App() {
  return (
    <div>
      <h1>Mon application</h1>

      {/* Conteneur pour les composants charges dynamiquement */}
      <React.Suspense fallback={<div>Chargement...</div>}>
        <MyComponent />
      </React.Suspense>
    </div>
  );
}
```

3. **Description :**

- `React.lazy()` prend une fonction qui importe dynamiquement le module.

- `React.Suspense` encapsule le composant charge via `React.lazy()` et affiche
  un contenu de secours, ici le texte "Chargement...", jusqu'a ce que le
  composant soit pret.

#### Avantages :

- Ameliore les performances en chargeant les composants uniquement lorsque
  c'est necessaire.

- Reduit la taille du chargement initial, car certaines parties du programme
  sont chargees a la demande.

Cette approche est particulierement utile dans les grandes applications, ou le
code peut etre decoupe en morceaux afin de reduire le temps de chargement de la
page.

</details>

<details>
<summary>101. Quelles approches sont utilisees pour effectuer des requetes HTTP dans React ?</summary>

#### React

#### Approches pour effectuer des requetes HTTP dans React

React n'a pas d'API integree pour effectuer des requetes HTTP, mais vous pouvez
utiliser des bibliotheques tierces ou les outils standards de JavaScript. Voici
les principales approches :

1. **Utilisation de Fetch API**

- Outil standard pour effectuer des requetes HTTP en JavaScript.

**Exemple :**

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

2. **Utilisation d'Axios**

- Bibliotheque pour effectuer des requetes HTTP avec une syntaxe plus simple et
  une prise en charge integree des intercepteurs.

**Exemple :**

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

- Bibliotheque pour gerer l'etat des donnees obtenues via des requetes HTTP.
  Elle prend en charge la mise en cache, les nouvelles tentatives et la mise a
  jour des donnees.

**Exemple :**

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

- Pour travailler avec une API GraphQL, on utilise souvent Apollo Client.

**Exemple :**

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

5. **Hooks personnalises**

- Vous pouvez creer vos propres hooks pour reutiliser la logique de requete.

**Exemple :**

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

#### Le choix de l'approche depend de vos besoins :

- **Fetch API** : pour des requetes simples.

- **Axios** : si vous avez besoin de plus de souplesse, par exemple avec des
  intercepteurs ou des timeouts.

- **React Query** : pour gerer la mise en cache des donnees.

- **GraphQL / Apollo Client** : si l'API repose sur GraphQL.

- **Hooks personnalises** : pour reutiliser la logique de requete.

</details>

<details>
<summary>102. Quelle est la difference entre createElement et cloneElement ?</summary>

#### React

| **Methode** | **Description** | **Usage principal** |
| ----------- | --------------- | ------------------- |
| `React.createElement` | Cree un nouvel element React. Il prend le type d'element, les props et les enfants en arguments. | Sert a creer des elements React a partir de zero, en general lors du rendu du JSX. |
| `React.cloneElement` | Clone un element React existant en permettant de modifier ses props ou ses enfants. | Sert a produire une copie modifiee d'un element React deja existant. |

#### Exemples :

`React.createElement`

```jsx
const element = React.createElement(
  'div',
  { className: 'example' },
  'Bonjour, React !'
);
```

Resultat : creation de `<div class="example">Bonjour, React !</div>`.

`React.cloneElement`

```jsx
const originalElement = <button className="primary">Cliquez</button>;

const clonedElement = React.cloneElement(originalElement, {
  className: 'secondary',
});
```

Resultat : un clone `<button class="secondary">Cliquez</button>` avec une
classe modifiee.

#### Difference :

- `createElement` cree un element entierement nouveau.

- `cloneElement` travaille a partir d'un element existant et permet d'en
  modifier les proprietes ou le contenu.

</details>

<details>
<summary>103. La fonction lazy prend-elle en charge les exports nommes ?</summary>

#### React

Non, `React.lazy` ne prend pas en charge directement les exports nommes. Elle
fonctionne uniquement avec un export par defaut. Si votre module utilise un
export nomme et que vous voulez l'utiliser avec `React.lazy`, il faut creer une
surcouche qui reexporte le composant voulu comme export par defaut.

#### Exemple de surcouche :

```jsx
// Export nomme
export const MyComponent = () => {
  return <div>Hello, World!</div>;
};

// Utilisation de React.lazy
const LazyComponent = React.lazy(() =>
  import('./MyComponent').then(module => ({ default: module.MyComponent }))
);

export default LazyComponent;
```

- Ici, on indique explicitement que `module.MyComponent` doit etre utilise comme
  export par defaut.

</details>

<details>
<summary>104. Quels sont les avantages de React ?</summary>

#### React

#### Avantages de React

1. **Performances elevees**

- L'utilisation du **Virtual DOM** minimise les mises a jour du DOM reel, ce
  qui rend le rendu plus rapide.

2. **Approche par composants**

- L'application est composee de **composants reutilisables**, ce qui simplifie
  le developpement et la maintenance.

3. **Flux de donnees a sens unique (Unidirectional Data Flow)**

- Les donnees circulent du haut vers le bas dans la hierarchie des composants,
  ce qui facilite le suivi des changements d'etat.

4. **Prise en charge des hooks**

- `useState`, `useEffect`, `useMemo` et les autres hooks permettent de gerer
  l'etat et les effets dans des composants fonctionnels, sans classes.

5. **Rendu cote serveur (SSR) et generation statique (SSG)**

- Avec Next.js, il est possible d'optimiser le SEO et d'ameliorer les
  performances.

6. **Souplesse et ecosysteme**

- React peut etre utilise avec **Redux**, **Zustand**, **MobX**,
  **React Query**, etc.

- Il prend aussi en charge **React Native** pour le developpement mobile.

7. **Capacites de debogage avancees**

- **React DevTools** permet d'inspecter en temps reel la structure des
  composants, l'etat et les props.

8. **Communaute active et soutien de Facebook**

- Grand choix de bibliotheques et de solutions pretes a l'emploi, avec une
  evolution rapide du framework.

React est un outil moderne, souple et performant pour le developpement
d'applications web.

</details>

<details>
<summary>105. Quelles sont les limites de React ?</summary>

#### React

1. **Rerendus nombreux :** si les composants sont mal optimises, cela peut
   entrainer trop de rerendus et nuire aux performances.

2. **Necessite de bien gerer l'etat :** sans bonne gestion de l'etat,
   l'application peut devenir difficile a maintenir.

3. **Flux de donnees a sens unique :** les donnees ne vont que dans un sens, ce
   qui peut compliquer leur transmission a travers plusieurs niveaux de
   composants.

4. **Modele reactif limite :** React met a jour le DOM via le Virtual DOM, mais
   cela peut etre moins efficace dans certaines applications tres grandes et
   tres dynamiques.

5. **Dependance a JavaScript :** sans JavaScript cote client, le support est
   limite.

6. **Courbe d'apprentissage :** meme si les concepts de base sont simples,
   maitriser correctement les hooks, le contexte et l'optimisation peut etre
   difficile pour les debutants.

7. **Outils tiers :** bien qu'il existe beaucoup d'outils, leur integration
   peut devenir complexe dans les grands projets.

</details>

<details>
<summary>106. A quoi servait la methode registerServiceWorker() dans React ?</summary>

#### React

`registerServiceWorker()` servait a enregistrer un Service Worker dans Create
React App, avant sa suppression de CRA a partir de la version 4.

#### Role :

- Mise en cache des ressources pour le mode hors ligne

- Acceleration du chargement de l'application

- Mise a jour des ressources en arriere-plan

#### Exemple d'utilisation, avant CRA 4 :

```javascript
import { register } from './serviceWorker';

register();
```

- Apres sa suppression de CRA, le Service Worker doit etre configure
  manuellement via `navigator.serviceWorker.register()`.

- Dans **React 19**, il n'existe aucun `registerServiceWorker()` integre, car
  cet element a ete retire bien plus tot, via Create React App 4. Si vous avez
  besoin d'un Service Worker, il faut l'enregistrer manuellement.

Conclusion : dans React 19, cette methode n'est plus d'actualite et le Service
Worker doit etre configure manuellement.

</details>

<details>
<summary>107. Que sont les evenements synthetiques (SyntheticEvent) dans React ?</summary>

#### React

Dans React, **SyntheticEvent** est une surcouche autour des evenements natifs
du navigateur, qui garantit la compatibilite entre navigateurs et harmonise le
comportement.

#### Caracteristiques de SyntheticEvent :

- Fonctionne de la meme maniere dans tous les navigateurs.

- Utilisait historiquement le pooling d'evenements, afin d'eviter de conserver
  inutilement des objets en memoire.

- Tous les evenements sont normalises et exposent les memes proprietes quel que
  soit le navigateur.

#### Exemple d'utilisation :

```jsx
function MyComponent() {
  const handleClick = event => {
    console.log(event.type); // "click"
    console.log(event.nativeEvent); // Evenement natif du navigateur
  };

  return <button onClick={handleClick}>Cliquez</button>;
}
```

#### Methodes principales :

- `event.preventDefault()` empeche le comportement par defaut.

- `event.stopPropagation()` arrete la propagation de l'evenement.

- `event.persist()` servait a desactiver le pooling afin que l'evenement ne
  soit pas recycle.

</details>

<details>
<summary>108. Quelles sont les techniques d'optimisation des performances dans React ?</summary>

#### React

#### Techniques d'optimisation des performances dans React :

1. **Memoisation des composants**

- Utilisez `React.memo()` pour eviter des rerendus inutiles.
- Utilisez `useMemo()` pour mettre en cache les calculs.
- Utilisez `useCallback()` pour garder des references de fonctions stables.

2. **Optimisation des rerendus**

- Evitez les states et props inutiles.
- Utilisez `shouldComponentUpdate` ou `React.PureComponent` dans les composants
  de classe.
- Optimisez le contexte en ne transmettant pas de valeurs inutiles.
- Utilisez des selecteurs comme avec `Reselect`, `Zustand` ou `Jotai` pour
  minimiser les mises a jour.

3. **Virtualisation des listes**

- Utilisez `react-window` ou `react-virtualized` pour n'afficher que les
  elements visibles.

4. **Mise en cache et debounce**

- `useMemo()` et `useCallback()` pour les calculs lourds.
- Debounce avec `lodash.debounce` ou throttling avec `lodash.throttle` pour les
  entrees utilisateur.

5. **Chargement paresseux (Lazy Loading)**

- `React.lazy()` et `Suspense` pour le decoupage du code.
- Imports dynamiques de modules via `import()`.

6. **Eviter les effets inutiles dans useEffect**

- Declarez correctement les dependances.
- Utilisez `useRef` pour conserver des valeurs sans provoquer de rerendu.

7. **Optimisation des images**

- Utilisez `next/image` dans Next.js.
- Optimisez les tailles et formats comme `WebP` et `AVIF`.

8. **Optimisation de React Router**

- Utilisez `React.lazy()` pour les pages.
- Evitez les rerendus inutiles en mettant a jour l'etat correctement.

9. **Separation de l'etat**

- Utilisez l'etat local lorsque l'etat global n'est pas necessaire.
- Placez les changements globaux dans `Redux`, `Zustand` ou `Recoil`.

10. **Utilisation de Web Workers**

- Pour les calculs lourds, afin de ne pas bloquer le thread principal.

</details>

<details>
<summary>109. Est-il possible d'utiliser async/await dans React ?</summary>

#### React

Oui, on peut utiliser `async/await` dans React, mais il faut tenir compte de
quelques points :

1. **Utilisation dans les composants :** `async/await` ne doit pas etre utilise
   directement dans `render()` ou comme rendu de composant, mais il peut etre
   employe dans les gestionnaires d'evenements ou dans des hooks comme
   `useEffect`.

2. **Mise en oeuvre pour les requetes asynchrones :**

- Utilisez `async/await` a l'interieur de fonctions appelees dans des hooks,
  par exemple :

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

3. **Gestion des erreurs :** n'oubliez pas d'utiliser `try/catch` pour traiter
   les erreurs lors des requetes asynchrones :

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

Ainsi, `async/await` peut et doit etre utilise pour les operations asynchrones
dans React, a condition de bien organiser son usage dans les composants.

</details>

<details>
<summary>110. Quelle est l'histoire de l'evolution de React ?</summary>

#### React

Voici un bref historique de l'evolution de React :

1. **2011**

- React est cree chez Facebook pour des besoins internes. L'ingenieur Jordan
  Walke le developpe afin de resoudre le probleme de la mise a jour efficace de
  l'interface.

2. **2013**

- Facebook publie React en open source. Au debut, la communaute reagit avec un
  certain scepticisme, notamment a cause de JSX, juge inhabituel.

3. **2015**

- Sortie de React 0.14 : React et ReactDOM sont separes, ce qui rend la
  bibliotheque plus modulaire.

- Facebook presente React Native, qui permet de creer des applications mobiles
  natives avec React.

4. **2016**

- Sortie de React 15. Les principales mises a jour concernent l'amelioration
  des performances grace a un nouveau moteur de rendu.

5. **2017**

- Sortie de React 16 avec Fiber. Cette nouvelle architecture apporte de
  meilleures performances et le support du rendu asynchrone.

- Ajout du support des portails et des **Error Boundaries**.

6. **2018**

- Facebook presente les React Hooks, qui permettent d'utiliser l'etat et les
  methodes du cycle de vie dans les composants fonctionnels. Cela change
  profondement la maniere de construire les composants.

7. **2019**

- Sortie de React 16.8 avec le support officiel des hooks.

- Amelioration experimentale du Concurrent Mode.

8. **2020**

- Sortie de React 17. L'objectif principal est de faciliter la mise a jour
  progressive de React dans les grands projets.

- Ajout du support d'outils modernes et de nouvelles possibilites autour de
  JSX.

9. **2022**

- Sortie de React 18. Les principales nouveautes incluent le Concurrent
  Rendering, ainsi que `useTransition` et `useDeferredValue`, qui ameliorent
  les performances dans les applications dynamiques.

10. **2024**

- Sortie de React 19.

- Evolution du rendu serveur avec les React Server Components.

- Prise en charge de la nouvelle fonction `use`.

- Amelioration du systeme de formulaires, de la gestion des erreurs de rendu et
  du JSX sans `import React`.

- Evolution du React Compiler pour l'optimisation automatique des performances.

#### Principales evolutions au fil du temps :

- Passage des composants de classe aux composants fonctionnels avec hooks.

- Prise en charge du rendu cote serveur (SSR).

- Introduction des mecanismes concurrents pour un rendu plus fluide.

- Integration de React avec le developpement mobile via React Native.

React reste populaire grace a ses performances, sa souplesse d'utilisation et
au soutien continu de Facebook.

</details>

<details>
<summary>111. Quelles nouveautes ont ete ajoutees dans React 19 ?</summary>

#### React

React 19 a introduit plusieurs evolutions importantes visant a ameliorer les
performances et le confort de developpement. Voici les principales nouveautes :

1. **Nouveau systeme de rendu :** le rendu asynchrone a ete renforce, ce qui
   permet a React de gerer plus efficacement les mises a jour de l'interface et
   d'ameliorer l'experience utilisateur.

2. **React Compiler :** ce nouveau compilateur optimise automatiquement les
   rerendus, reduit les mises a jour inutiles et ameliore les performances des
   applications.

3. **Actions API :** nouvelle approche pour gerer l'etat et les mutations de
   donnees cote serveur, en simplifiant les effets de bord et les requetes.

4. **Mecanique Suspense amelioree :** elle donne un controle plus fin sur le
   chargement asynchrone des donnees, la gestion de l'hydratation et les etats
   de secours.

5. **Hook `use` :** nouveau hook qui simplifie le travail avec les donnees
   asynchrones et ameliore la prise en charge des composants serveur.

6. **Prise en charge native des metatags :** `meta`, `title`, `link` et
   d'autres balises similaires peuvent desormais etre geres sans bibliotheques
   supplementaires, ce qui simplifie le SEO et la gestion des ressources.

- Ces nouveautes font de React 19 un outil plus puissant et plus confortable
  pour les developpeurs, en ameliorant a la fois les performances des
  applications et l'experience de developpement.

</details>

<details>
<summary>112. Que recommandent les developpeurs React depuis que Create React App est devenu obsolete ?</summary>

#### React

Depuis l'abandon de Create React App en fevrier 2025, il est recommande aux
developpeurs d'utiliser des frameworks modernes pour creer de nouvelles
applications React. Ces frameworks prennent en charge le rendu cote client
(CSR) et les applications monopages (SPA), qui peuvent etre deployees sur un
CDN ou des hebergements statiques sans serveur dedie.

#### Frameworks recommandes :

1. **Next.js :** propose des fonctionnalites puissantes comme le rendu cote
   serveur et la generation de sites statiques, avec de bonnes performances et
   une solide optimisation SEO.

2. **React Router :** permet de construire des SPA avec un routage dynamique et
   de gerer facilement la navigation dans l'application.

3. **Expo :** simplifie le developpement d'applications React Native en
   fournissant des outils pour creer des applications mobiles multiplateformes
   avec JavaScript et React.

</details>

<details>
<summary>113. Comment fonctionne le hook useDeferredValue dans React ?</summary>

#### React

`useDeferredValue` est un hook React apparu avec React 18 dans le cadre des
fonctionnalites concurrentes. Il permet de differer la mise a jour de certaines
valeurs, qu'il s'agisse de state ou de props, en leur donnant une priorite plus
faible afin que React traite d'abord les taches plus importantes de l'interface.

C'est tres utile lorsqu'une valeur change souvent et que chaque mise a jour de
l'interface coute cher en ressources.

##### Pourquoi utilise-t-on `useDeferredValue` ?

- Pour eviter les ralentissements dans les applications complexes, lorsque la
  reactivite de l'interface est importante.
- Pour ameliorer l'experience utilisateur, notamment lors de recherches, de
  filtres ou du rendu de grandes listes.
- Pour conserver des animations et des transitions fluides.

##### Comment cela fonctionne-t-il ?

Le hook `useDeferredValue` recoit une valeur et retourne sa version differee :

```jsx
const deferredValue = useDeferredValue(value);
```

- React met d'abord a jour les changements critiques et prioritaires.
- La valeur differee (`deferredValue`) est mise a jour de maniere asynchrone
  une fois les taches plus urgentes traitees.
- Si la valeur principale change trop vite, React peut ignorer certaines
  valeurs intermediaires pour aller directement a la plus recente.

##### Exemple d'utilisation :

Imaginons un composant avec un champ de recherche et une grande liste a filtrer
au fur et a mesure de la saisie.

###### Sans `useDeferredValue` :

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
        placeholder="Recherche..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

Cela peut provoquer des ralentissements si la liste est tres grande, car React
recalcule immediatement les resultats filtres a chaque caractere saisi.

###### Avec `useDeferredValue` :

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
        placeholder="Recherche..."
      />
      <List items={filteredItems} />
    </>
  );
}
```

Dans cette variante :

- La saisie de l'utilisateur reste immediate et fluide.
- Le filtrage de la liste est effectue de maniere asynchrone, une fois que la
  pression sur l'interface diminue.
- L'interface reste ainsi reactive.

##### Particularites de fonctionnement :

- `useDeferredValue` ne fixe pas un delai precis, contrairement au debounce.
  Il laisse React determiner automatiquement le bon moment selon la charge de
  l'interface.
- La valeur retournee par `useDeferredValue` peut etre legerement en retard par
  rapport a l'etat principal, ce qu'il faut prendre en compte dans la logique
  de l'application.

##### Avantages :

- Reduit la charge processeur pendant les interactions intenses.
- Aide a maintenir un FPS stable et une interface fluide.
- Rend l'UX plus agreable et plus previsible, surtout dans les grandes
  applications complexes.

##### Quand vaut-il mieux utiliser `useDeferredValue` ?

- Listes contenant un grand nombre d'elements.
- Formulaires avec filtrage actif et autocompletion.
- Tous les cas ou des mises a jour trop frequentes de l'interface risquent de
  degrader l'experience utilisateur.

</details>
