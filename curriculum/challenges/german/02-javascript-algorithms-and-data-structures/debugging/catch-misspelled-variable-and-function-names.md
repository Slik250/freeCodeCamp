---
id: 587d7b84367417b2b2512b35
title: Falsch geschriebene Variablen- und Funktionsnamen abfangen
challengeType: 1
forumTopicId: 301186
dashedName: catch-misspelled-variable-and-function-names
---

# --description--

Die Methoden `console.log()` und `typeof` sind die beiden wichtigsten Methoden, um Zwischenwerte und Typen von Programmausgaben zu überprüfen. Jetzt ist es an der Zeit, sich mit den häufigsten Formen von Bugs zu beschäftigen. Ein Problem auf der Ebene der Syntax, mit dem schnelle Tipper mitfühlen können, ist der einfache Rechtschreibfehler.

Transposed, missing, or miscapitalized characters in a variable or function name will have the browser looking for an object that doesn't exist - and complain in the form of a reference error. Bei JavaScript-Variablen- und Funktionsnamen wird zwischen Groß- und Kleinschreibung unterschieden.

# --instructions--

Korrigiere die beiden Rechtschreibfehler im Code, damit die Berechnung des `netWorkingCapital` funktioniert.

# --hints--

Überprüfe die Schreibweise der beiden Variablen, die in der Berechnung des NetWorkingCapitals verwendet werden. Die Konsolenausgabe sollte Folgendes anzeigen: " Net working capital is: 2".

```js
assert(netWorkingCapital === 2);
```

Es sollten keine falsch geschriebenen Variablen im Code vorkommen.

```js
assert(!__helpers.removeJSComments(code).match(/recievables/g));
```

Die Variable `receivables` sollte im Code richtig deklariert und verwendet werden.

```js
assert(__helpers.removeJSComments(code).match(/receivables/g).length == 2);
```

Es sollten keine falsch geschriebenen Variablen im Code vorkommen.

```js
assert(!__helpers.removeJSComments(code).match(/payable;/g));
```

Die Variable `payables` sollte im Code richtig deklariert und verwendet werden.

```js
assert(__helpers.removeJSComments(code).match(/payables/g).length == 2);
```

# --seed--

## --seed-contents--

```js
let receivables = 10;
let payables = 8;
let netWorkingCapital = recievables - payable;
console.log(`Net working capital is: ${netWorkingCapital}`);
```

# --solutions--

```js
let receivables = 10;
let payables = 8;
let netWorkingCapital = receivables - payables;
console.log(`Net working capital is: ${netWorkingCapital}`);
```
