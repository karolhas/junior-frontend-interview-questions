### 1. **Hoisting (Podnoszenie)**

To wbudowany mechanizm wynoszący deklarację zmiennych bez ich inicjalizowania na początek funkcji. Hoisting to proces, w którym silnik JavaScript odkłada pamięć na zmienne, funkcje i klasy, aby sprawić wrażenie, że znajdują się one na górze kodu.

---

### 2. **Scope (Zakres)**

To sekcja kodu umożliwiająca dostęp do określonych zmiennych i funkcji. Określa on widoczność zmiennych i funkcji. Zmienne i funkcje zadeklarowane w określonym zakresie nie mogą być dostępne poza tym zakresem.

---

### 3. **Różnica Między `let` i `const`**

Zarówno `let`, jak i `const` są używane do deklarowania nowej zmiennej. Główną różnicą jest to, że zmienne zadeklarowane za pomocą `const` nie mogą zostać ponownie przypisane.

---

### 4. **Różnica Między `let` i `var`**

Zarówno `let`, jak i `var` są używane do deklarowania zmiennych w JavaScript. Zmienne `var` mają zakres funkcji, podczas gdy zmienne `let` mają zakres bloku.

---

### 5. **Prymitywne Typy Danych**

Prymitywne typy danych zawierają tylko wartości jednego typu. Typy danych obejmują:

- `Number`
- `String`
- `Boolean`
- `Null`
- `Undefined`
- `Symbol`
- `BigInt`

---

### 6. **DOM (Document Object Model)**

DOM to skrót od Document Object Model. Obiekt dokumentu to reprezentacja dokumentu HTML. Można go używać do uzyskiwania dostępu i modyfikowania zawartości HTML.

---

### 7. **Domknięcie**

Domknięcie to mechanizm, który wiąże funkcję z otaczającym ją stanem. Pozwala funkcji wewnętrznej uzyskać dostęp do zasięgu funkcji zewnętrznej.

---

### 8. **Różnica Między Operatorem `==` a `===`**

Operator `==` najpierw wykonuje przekształcenia typu, a potem porównuje wartości. Operator `===` wymaga zgodności zarówno typu, jak i wartości.

---

### 9. **Dziedziczenie**

Dziedziczenie umożliwia jednemu obiektowi uzyskanie dostępu do właściwości i metod innego obiektu.

---

### 10. **Pętla Zdarzeń (Event Loop)**

Pętla zdarzeń to mechanizm, który umożliwia JavaScript obsługę wielu zdarzeń asynchronicznych, nie blokując innych zadań.

---

### 11. **IIFE (Immediately Invoked Function Expression)**

IIFE to funkcja, którą można natychmiast wywołać po jej definicji. Przykład: `(() => console.log("Hello World"))();`

---

### 12. **Callback Hell**

Callback hell to wzorzec zagnieżdżania wielu wywołań zwrotnych, co utrudnia czytanie i modyfikowanie kodu.

---

### 13. **Obietnica (Promise)**

Obietnica to obiekt reprezentujący ukończenie operacji asynchronicznej. Wynik operacji może być obsłużony przez metodę `then`.

---

### 14. **`async`/`await`**

Słowa kluczowe `async` i `await` służą do pracy z obietnicami. `async` sprawia, że funkcja zwraca obietnicę, a `await` zatrzymuje wykonanie do momentu spełnienia obietnicy.

---

### 15. **Currying**

Currying to technika rozbicia funkcji z wieloma parametrami na szereg funkcji z jednym parametrem, np. `f(a, b, c)` do `f(a)(b)(c)`.

---

### 16. **Funkcje Pierwszej Klasy**

Funkcje pierwszej klasy są traktowane jak zwykłe zmienne. Można je przypisać, przekazać jako argument, czy zwrócić z innej funkcji.

---

### 17. **Instrukcje Funkcyjne i Wyrażenia Funkcyjne**

Instrukcja funkcji to funkcja tworzona przy użyciu słowa kluczowego `function`. Wyrażenie funkcji przypisuje funkcję do zmiennej.

---

### 18. **Funkcje Pierwszego Rzędu**

Funkcje pierwszego rzędu nie przyjmują innych funkcji jako argumentów i nie zwracają funkcji.

---

### 19. **Ilość Parametrów Funkcji**

Używając właściwości `length`, można uzyskać liczbę parametrów oczekiwanych przez funkcję.

---

### 20. **Typ Zmiennej**

Aby poznać typ zmiennej, użyj operatora `typeof`.

---

### 21. **Funkcje Dostępu**

Funkcje dostępowe pozwalają pobierać lub ustawiać właściwości obiektu za pomocą `get` i `set`.

---

### 22. **Funkcje Anonimowe**

Funkcja anonimowa to funkcja bez nazwy, która może być przypisana do zmiennej lub używana jako callback.

---

### 23. **Temporalna Martwa Strefa**

Temporalna martwa strefa to obszar, w którym zmienne zadeklarowane przy użyciu `let` i `const` nie są jeszcze dostępne.

---

### 24. **Memoization (Zapamiętywanie)**

Memoization to technika buforowania wyników funkcji w celu poprawy wydajności.

---

### 25. **Różnica Między `async` i `defer`**

`async` wykonuje skrypt po pobraniu, przerywając analizowanie HTML. `defer` opóźnia wykonanie skryptu do zakończenia analizy HTML.

---

### 26. **Różnica Między Pamięcią Lokalną a Pamięcią Sesji**

Zarówno pamięć lokalna, jak i pamięć sesji przechowują dane. Pamięć lokalna zachowuje dane nawet po zamknięciu przeglądarki, natomiast pamięć sesji usuwa dane po zamknięciu karty przeglądarki.

---

### 27. **Różnica Między `slice()` a `splice()`**

Funkcja `slice()` zwraca nową tablicę zawierającą kopię oryginalnego wycinka tablicy. Funkcja `splice()` modyfikuje zawartość tablicy w miejscu i może być używana do dodawania lub usuwania elementów.

---

### 28. **Funkcje Konstruktorów (Constructor Functions)**

Funkcje konstruktorów tworzą obiekty o podobnych właściwościach i metodach.

---

### 29. **Funkcja `Promise.race()`**

Funkcja `Promise.race()` przyjmuje tablicę obietnic i zwraca wynik pierwszej obietnicy, która zostanie rozwiązana lub odrzucona.

---

### 30. **Metody `call()`, `apply()`, `bind()`**

- **`call()`**: Wywołuje funkcję z określonym kontekstem i parametrami.
- **`apply()`**: Wywołuje funkcję z określonym kontekstem i argumentami przekazanymi w postaci tablicy.
- **`bind()`**: Tworzy nową funkcję, która ma przypisany określony kontekst, ale nie wywołuje jej od razu.

---

### 31. **Dostęp do Historii Strony w JavaScript**

Obiekt `window.history` zapewnia dostęp do stosu historii przeglądarki.

---

### 32. **Sprawdzanie, Czy Obiekt Jest Zamrożony**

Użyj metody `Object.isFrozen()` aby sprawdzić, czy obiekt jest zamrożony.

---

### 33. **Obsługa Błędów w JavaScript**

Użyj bloku `try-catch` do obsługi błędów. Kod, który może rzucić błąd, umieść w bloku `try`, a obsługę błędów w `catch`.

---

### 34. **Walidacja JSON w JavaScript**

Funkcja `JSON.parse()` analizuje i waliduje ciąg JSON. Jeśli ciąg jest poprawny, zostanie zwrócony obiekt JavaScript.

---

### 35. **JavaScript Jako Język Dynamiczny**

JavaScript jest językiem dynamicznym, co oznacza, że typy zmiennych są określane podczas wykonywania.

---

### 36. **Funkcje Strzałkowe**

Funkcje strzałkowe oferują bardziej zwięzłą składnię dla deklarowania funkcji. Nie mają własnego kontekstu `this`.

---

### 37. **Klasy w JavaScript**

ES6 wprowadził klasy jako sposób na tworzenie obiektów i zarządzanie dziedziczeniem w JavaScript.

---

### 38. **Czym Są Pliki Cookie**

Pliki cookie to małe pakiety danych wysyłane przez serwer do przeglądarki i przechowywane po stronie klienta.

---

### 39. **Moduły ES**

Moduły ES, wprowadzone w ES6, to pliki JavaScript, które eksportują funkcje lub zmienne. Inne pliki mogą importować te moduły.

---

### 40. **Funkcje Generatora**

Funkcje generatora są deklarowane przy użyciu `function*`. Mogą one wstrzymywać swoje wykonanie za pomocą `yield` i wznowić je później.

---

### 41. **Generatory w JavaScript**

Generatory to funkcje, które mogą zwracać wiele wartości poprzez `yield` zamiast `return`, umożliwiając wstrzymanie i wznowienie wykonania.

---

### 42. **Funkcje Wyższego Rzędu**

Funkcje wyższego rzędu mogą przyjmować inne funkcje jako argumenty lub zwracać funkcje.

---

### 43. **Czyste Funkcje**

Czyste funkcje zawsze zwracają tę samą wartość dla tych samych argumentów i nie mają efektów ubocznych.

---

### 44. **Typy Danych w JavaScript**

W JavaScript występuje siedem prymitywnych typów danych: Number, String, Boolean, Null, Undefined, Symbol oraz typ nieprymitywny `object`.

---

### 45. **Rodzaje Błędów w JavaScript**

- **Błąd Składni (Syntax Error)**: Zła składnia programu.
- **Błąd Odniesienia (Reference Error)**: Odwołanie do zmiennej, której nie ma w pamięci.
- **Błąd Typu (Type Error)**: Przypisanie wartości niewłaściwego typu.

---

### 46. **Co Robi `delete` w JavaScript**

Operator `delete` usuwa właściwość obiektu.

---

### 47. **Browser Object Model (BOM)**

BOM pozwala na interakcję z przeglądarką za pomocą obiektu `window`, który reprezentuje okno przeglądarki.

---

### 48. **Funkcje Zwrotne (Callback Functions)**

Funkcja zwrotna to funkcja przekazywana jako argument do innej funkcji i wywoływana w odpowiednim momencie.

---

### 49. **Tryb Ścisły (Strict Mode)**

Tryb ścisły w ECMAScript 5 wprowadza bardziej rygorystyczne reguły w kodzie. Aktywowany jest przez `"use strict";`.

---

### 50. **Funkcja Jednoargumentowa**

Funkcja jednoargumentowa to funkcja przyjmująca tylko jeden parametr.

---

### 51. **Delegacja Zdarzeń (Event Delegation)**

Delegacja zdarzeń jest podejściem do efektywnego zarządzania zdarzeniami. Zamiast dodawać _event listener_ do każdego identycznego elementu, możemy dodać go do elementu nadrzędnego i użyć właściwości _event.target_ obiektu zdarzenia, aby wywołać zdarzenie na określonym celu.

---

### 52. **Debouncing**

Debouncing zapobiega ponownemu wywołaniu funkcji, dopóki nie upłynie określony czas od ostatniego wywołania. Przykładem zastosowania jest optymalizacja funkcji wyszukiwania.

---

### 53. **Obsługa Zdarzeń (Event Handling)**

Obsługa zdarzeń to proces reagowania na zdarzenia użytkownika, takie jak `click` podczas klikania na stronę internetową.

---

### 54. **Konstruktory Funkcji**

Konstruktory funkcji to normalne funkcje używane do tworzenia obiektów. `this` wskazuje na nowy, pusty obiekt, który jest zwracany z funkcji.

---

### 55. **Czym Jest JSON**

JSON to skrót od _JavaScript Object Notation_. Jest to lekki format służący do przechowywania i wymiany danych.

---

### 56. **Co to Jest NaN w JavaScript**

`NaN` oznacza "Not a Number" i reprezentuje wartość, która nie jest poprawną liczbą w JavaScript.

---

### 57. **Destrukturyzacja Obiektów**

Destrukturyzacja to technika, która pozwala na wyodrębnienie właściwości z obiektów lub elementów z tablic.

---

### 58. **Refleksja (Reflection)**

Refleksja to zdolność obiektu do przeglądania i modyfikowania swoich własnych właściwości i metod.

---

### 59. **Obiekt Argumentów**

Obiekt argumentów to tablico-podobny obiekt dostępny wewnątrz funkcji, który przechowuje przekazane argumenty.

---

### 60. **Różnica Między Obiektami Zmiennymi a Niezmiennymi**

Obiekt zmienny (mutable) to taki, którego stan można zmienić po utworzeniu. Obiekt niezmienny (immutable) nie może być zmieniony po utworzeniu.

---

### 61. **Różnica Między `window` a `document`**

- **`window`**: Obiekt `window` jest najwyższym poziomem w hierarchii DOM i reprezentuje okno przeglądarki.
- **`document`**: Obiekt `document` reprezentuje załadowaną stronę internetową i pozwala na manipulację jej zawartością.

---

### 62. **Różnica Między `fetch()` a `XMLHttpRequest()`**

`fetch()` to nowoczesne API oparte na obietnicach, które upraszcza obsługę asynchronicznych żądań HTTP, podczas gdy `XMLHttpRequest()` jest starszym API, które nie korzysta z obietnic.

---

### 63. **Różnica Między Funkcjami a Metodami**

Funkcje to niezależne bloki kodu, podczas gdy metody to funkcje przypisane jako właściwości obiektu.

---

### 64. **Różnica Między Dziedziczeniem Prototypowym a Klasycznym**

Dziedziczenie prototypowe opiera się na tworzeniu nowych obiektów z istniejących, podczas gdy dziedziczenie klasyczne wykorzystuje klasy do dziedziczenia właściwości i metod.

---

### 65. **Różnica Między `null` a `undefined`**

`null` oznacza brak wartości, natomiast `undefined` oznacza, że zmienna została zadeklarowana, ale nie zainicjowana.

---

### 66. **Metoda `unshift()`**

`unshift()` dodaje nowy element na początku tablicy i zwraca nową długość tablicy.

---

### 67. **Zastosowanie `this` w JavaScript**

`this` odnosi się do obiektu, w którym dana funkcja została wywołana. W konstruktorach, `this` jest używane do przypisywania wartości do atrybutów obiektu.

---

### 68. **Throttling**

Throttling ogranicza liczbę wywołań funkcji w określonym przedziale czasowym.

---

### 69. **Dlaczego Potrzebujemy Modułów**

Moduły pozwalają podzielić kod na mniejsze, bardziej zorganizowane części, ułatwiając współpracę i konserwację dużych aplikacji.
