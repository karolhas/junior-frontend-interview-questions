### 1. **Czym jest CSS i dlaczego jest używany?**

**CSS (Kaskadowe Arkusze Stylów)** służy do stylizowania i układu stron internetowych, kontrolując wygląd elementów HTML.

---

### 2. **Jakie są elementy Modelu Pudełkowego (Box Model) w CSS?**

Model Pudełkowy obejmuje treść, padding, obramowanie i margines, definiując przestrzeń zajmowaną przez element.

---

### 3. **Jaka jest różnica między klasą a ID w CSS?**

- **Klasy** (`.class`) są wielokrotnego użytku i mogą być stosowane do wielu elementów.
- **ID** (`#id`) są unikalne i przypisane do jednego elementu.

---

### 4. **Jak CSS może być zintegrowany ze stroną HTML?**

Istnieją trzy sposoby integracji CSS z HTML:

- Użycie tagów `<style>` w sekcji `<head>`
- Użycie zewnętrznego pliku `.css`
- Łączenie za pomocą `<link>` w sekcji `<head>` HTML, aby dołączyć zewnętrzny arkusz stylów

---

### 5. **Jaka jest różnica między marginesem a paddingiem?**

- **Margines**: Zewnętrzna przestrzeń poza obramowaniem elementu
- **Padding**: Wewnętrzna przestrzeń wewnątrz obramowania elementu

---

### 6. **Jak wycentrować div?**

Istnieje kilka sposobów, ale najprostszym jest użycie właściwości flexbox:

```css
div {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

---

### 7. **Czym są pseudoklasy i które z nich znasz?**

Pseudoklasa CSS to słowo kluczowe dodawane do selektora, które określa specjalny stan wybranego elementu. Na przykład, pseudoklasa `:hover` może być używana, aby stylizować przycisk, gdy wskaźnik użytkownika znajduje się nad nim. Powszechne pseudoklasy to `:hover`, `:focus`, `:visited`, `:active`, `:nth-child` i inne.

---

### 8. **Czym są pseudoelementy?**

Pseudoelement CSS to słowo kluczowe dodawane do selektora, które pozwala stylizować określoną część wybranego elementu. Najbardziej popularne pseudoelementy to `::before`, `::after` oraz `::first-letter`.

---

### 9. **Jakie są wartości właściwości display i jak działają?**

Właściwość `display` w CSS określa, jak konkretny element HTML powinien być wyświetlany.

- `display: none` - element nie jest wyświetlany
- `display: block` - elementy są ustawiane pionowo i zajmują całą dostępną szerokość
- `display: inline` - elementy są umieszczane w jednej linii; szerokość i wysokość są określone przez zawartość i nie można ich zmieniać ręcznie
- `display: inline-block` - element jest wyświetlany inline, ale jego szerokość i wysokość można zmieniać
- `display: flex` - włącza układ flexbox
- `display: grid` - włącza układ siatki (grid)

---

### 10. **Jaka jest różnica między display: none a visibility: hidden?**

- `display: none` - usuwa element z układu; przestrzeń, którą zajmował, zostaje usunięta
- `visibility: hidden` - ukrywa element, ale jego miejsce w układzie zostaje zachowane

---

### 11. **Jak działa właściwość float w CSS?**

Właściwość `float` w CSS umieszcza element po lewej lub prawej stronie jego kontenera, pozwalając tekstowi i elementom inline owijać się wokół niego. Element jest usunięty z normalnego przepływu strony, ale pozostaje częścią przepływu (w przeciwieństwie do pozycjonowania absolutnego).

---

### 12. **Czym są media queries?**

Media queries są używane, gdy różne style CSS muszą być stosowane dla różnych urządzeń w zależności od typu wyświetlacza (np. drukarka, monitor, smartfon), jak również od specyficznych cech urządzenia (np. szerokość okna przeglądarki) lub warunków zewnętrznych (np. oświetlenie otoczenia). Używa się reguły `@media`, aby zawrzeć blok właściwości CSS, jeśli określony warunek jest spełniony.

---

### 13. **Czym jest właściwość position i jakie przyjmuje wartości?**

Właściwość `position` w CSS określa, jak element jest pozycjonowany w dokumencie. Właściwości `top`, `right`, `bottom`, `left` określają ostateczne położenie pozycjonowanych elementów.

- `static`: Element jest pozycjonowany zgodnie z Normalnym Przepływem dokumentu. Wartości top, right, bottom, left oraz z-index nie mają wpływu. Jest to domyślna wartość.
- `relative`: Element jest pozycjonowany zgodnie z normalnym przepływem dokumentu, a następnie przesunięty względem samego siebie na podstawie wartości top, right, bottom, left. Przesunięcie nie wpływa na pozycję innych elementów.
- `absolute`: Element jest usunięty z normalnego przepływu dokumentu, a na stronie nie zostaje utworzona przestrzeń dla tego elementu. Element jest pozycjonowany względem najbliższego pozycjonowanego przodka (jeśli taki istnieje) lub względem początkowego kontenera.
- `fixed`: Pozycjonowanie zamraża element w miejscu, więc gdy strona jest przewijana, element pozostaje w swojej pozycji i nie przewija się razem ze stroną.
- `sticky`: Pozycjonowanie jest podobne do pozycjonowania fixed, ale element jest przyczepiony do określonego bloku, a nie do całego dokumentu.

---

### 14. **Czym jest flexbox?**

Flexbox to moduł układu, który zapewnia elastyczny sposób organizowania i wyrównywania elementów wewnątrz kontenera. Umożliwia łatwą manipulację rozmiarem, pozycją i odstępami między elementami, co czyni go idealnym do tworzenia responsywnych i dynamicznych układów. Dzięki flexboxowi można łatwo tworzyć złożone i wielokierunkowe układy bez polegania na floatach czy sztuczkach z pozycjonowaniem.

---

### 15. **Czym jest grid?**

Grid to system układu, który pozwala tworzyć złożone, oparte na siatce projekty dla stron internetowych. CSS Grid Layout dostarcza dwuwymiarową strukturę siatki, gdzie można definiować wiersze i kolumny, aby pozycjonować i wyrównywać elementy w obrębie siatki.

---

### 16. **Czym jest preprocesor CSS?**

Preprocesory CSS to języki skryptowe, które rozszerzają domyślne możliwości CSS. Umożliwiają użycie logiki w kodzie CSS, takiej jak zmienne, zagnieżdżanie, dziedziczenie, mixiny, funkcje i operacje matematyczne. Najpopularniejsze preprocesory to: **Sass, Less**.

---

### 17. **Wymień kilka frameworków CSS.**

Frameworki CSS to biblioteki, które ułatwiają stylizację stron internetowych. Niektóre z nich to: **TailwindCSS, Bootstrap, Bulma, Foundation**.

---

### 18. **Jak optymalizować CSS dla lepszej wydajności?**

- Minimalizuj i kompresuj pliki
- Zmniejsz poziom zagnieżdżania
- Unikaj używania `@import` (zamiast tego używaj `<link>` w `<head>`, np. do importowania czcionek)
- Unikaj niepotrzebnych selektorów
- Używaj efektywnych selektorów

---

### 19. **Czym jest właściwość transition?**

Właściwość transition pozwala zdefiniować stan przejściowy między dwoma stanami elementu. Różne stany mogą być definiowane za pomocą pseudoklas takich jak :hover lub :active, lub dynamicznie za pomocą JavaScriptu.

---

### 20. **Czym są keyframes?**

Keyframes są używane do definiowania konkretnych kroków animacji lub stanów w trakcie animacji. Pozwalają określić pośrednie style lub wartości właściwości, które element powinien mieć w różnych punktach czasu w trakcie animacji.

---

### 21. **Jaka jest różnica między transitions, a animations?**

- Transitions - płynnie zmieniają właściwości w czasie
- Animations - tworzą złożone sekwencje za pomocą keyframes

---

### 22. **Jak używasz dziedziczenia w CSS?**

Elementy potomne dziedziczą określone style od elementów nadrzędnych, chyba że zostaną one nadpisane.

---

### 23. **Jakie są różne sposoby określania kolorów w CSS?**

- Nazwy kolorów
- Kody HEX
- RGB/RGBA
- Wartości HSL/HSLA

---

### 24. **Jak tworzyć i używać zmiennych CSS (właściwości niestandardowych)?**

Deklaracja: `--var-name: wartość;`, użycie: `var(--var-name);`

---

### 25. **Co rozumiesz przez uniwersalny selektor?**

Uniwersalny selektor to `*`, który pasuje do dowolnego typu elementu, zamiast wybierać elementy konkretnego typu.

Przykład:

```css
* {
  color: blue;
  font-size: 10px;
}
```

---

### 26. **Czym jest box-sizing?**

Właściwość CSS `box-sizing` określa, jak obliczana jest całkowita szerokość i wysokość elementu. Gdy ustawiona jest na `border-box`, właściwości width i height obejmują zawartość, padding i obramowanie, ale nie obejmują marginesu.

---

### 27. **Zdefiniuj z-index.**

`z-index` jest używany do określenia kolejności nakładania się elementów, które zachodzą na siebie. Jego domyślna wartość to zero i może przyjmować zarówno wartości ujemne, jak i dodatnie. Wyższa wartość `z-index` jest umieszczana nad elementem o niższym indeksie. Przyjmuje następujące wartości: auto, liczba, initial i inherit.

---

### 28. **Czym są prefiksy przeglądarek i dlaczego są używane w CSS?**

Prefiksy specyficzne dla przeglądarek (np. `-webkit-`) są używane dla eksperymentalnych funkcji, które nie zostały jeszcze znormalizowane.

---

### 29. **Jaka jest różnica między jednostkami em a rem?**

- `em` jest względny w stosunku do rozmiaru czcionki elementu nadrzędnego
- `rem` jest względny w stosunku do rozmiaru czcionki w elemencie głównym (`html`)

---

### 30. **Czym jest funkcja calc() w CSS i jak jej używać?**

Funkcja `calc()` w CSS pozwala wykonywać obliczenia przy określaniu wartości właściwości CSS. Może być używana z wartościami `<length>`, `<frequency>`, `<angle>`, `<time>`, `<percentage>`, `<number>`, `<integer>` oraz `<color-function>`.

### 31. **Czym są style inline?**

Są to style zapisane bezpośrednio w HTML, które mają najwyższy priorytet (z wyjątkiem `!important`).

---

### 32. **Czym jest !important i jak się do niego odnosisz?**

Deklaracja `!important` jest używana do nadania regule stylu najwyższego priorytetu, co pozwala na nadpisanie innych reguł, które z nią kolidują. Gdy zostanie zastosowana do właściwości CSS, `!important` zapewnia, że określona wartość zostanie użyta, niezależnie od specyficzności czy kolejności innych reguł.

---

### 33. **Jaka jest różnica między border a outline?**

- `outline` nie wpływa na pozycję elementu ani jego wymiary
- `outline` nie pozwala na ustawienie obramowania tylko na jednej stronie elementu (tylko na wszystkich stronach jednocześnie)
- `outline` nie stosuje zaokrąglenia narożników ustawionego przez właściwość `border-radius`

---

### 34. **Co wiesz o responsywnym projektowaniu stron internetowych?**

Responsywne projektowanie stron internetowych pozwala na dostosowanie i reagowanie stron na różne rozmiary ekranów i urządzeń. Polega na tworzeniu elastycznych układów, korzystaniu z siatek i stosowaniu media queries, aby zapewnić optymalne wrażenia wizualne na różnych urządzeniach i rozdzielczościach.

---

### 35. **Co oznacza strumień RGB?**

RGB reprezentuje kolory w CSS. Trzy strumienie to Red (Czerwony), Green (Zielony) i Blue (Niebieski). Intensywność kolorów jest reprezentowana przez liczby od 0 do 256, co pozwala CSS na wyświetlanie szerokiego spektrum kolorów widzialnych.

---

### 36. **Czym jest BEM (Block Element Modifier)?**

BEM (Block, Element, Modifier) to podejście komponentowe do tworzenia stron internetowych. Oparte jest na zasadzie podziału interfejsu na niezależne bloki. Umożliwia szybkie i łatwe tworzenie interfejsów o dowolnej złożoności oraz ponowne wykorzystanie istniejącego kodu, unikając "kopiuj-wklej".

---

### 37. **Wyjaśnij kilka zalet CSS.**

Dzięki CSS można kontrolować różne dokumenty za pomocą jednej strony, grupować style w złożonych sytuacjach, korzystając z selektorów i metod grupowania, oraz nadawać klasy wielu elementom HTML.

---

### 38. **Jak za pomocą CSS kontrolować powtarzanie obrazów?**

Właściwość `background-repeat: none` służy do kontrolowania powtarzania obrazów.

---

### 39. **Jaki jest cel właściwości overflow i kiedy powinna być używana?**

Właściwość CSS `overflow` określa, czy zawartość elementu blokowego, która wykracza poza jego wymiary, powinna być obcinana, mieć paski przewijania, czy być wyświetlana.

---

### 40. **Jak stworzyć niestandardowy checkbox?**

Przed polem wyboru tworzy się etykietę i przypisuje ją do inputu. Następnie input jest ukrywany, a etykieta stylizowana według potrzeb.

---

### 41. **Czym są jednostki vh i vw?**

`vh` i `vw` to jednostki względne i reprezentują:

- `vh` - 1% wysokości okna przeglądarki
- `vw` - 1% szerokości okna przeglądarki

---

### 42. **Jak zmienić wygląd kursora?**

Właściwość CSS `cursor` służy do zmiany wyglądu kursora.

---

### 43. **Co decyduje o rozmiarze elementu?**

Rozmiar elementu jest określany przez szerokość i wysokość jego zawartości, paddingu, obramowania i marginesu zewnętrznego.

---

### 44. **Jak pozycjonować jeden element względem drugiego?**

Aby kontrolować pozycjonowanie elementu potomnego, ustaw właściwość `position` na `relative` i użyj `top`, `right`, `bottom`, oraz `left`, aby dostosować jego położenie.

---

### 45. **Jak usunąć punktory z listy?**

Ustaw właściwość `list-style-type: none` dla odpowiedniego elementu listy.

---

### 46. **Które style CSS są najbardziej obciążające dla przeglądarek?**

Duża liczba załadowanych czcionek, cieni, animacji oraz przezroczystości.

---

### 47. **Jak wybrać elementy z określonym atrybutem w CSS?**

Użyj selektorów atrybutów, np.:

```css
a[type="text"] {
  color: red;
}
```

---

### 48. **Czym jest właściwość aspect-ratio w CSS?**

Ustawia preferowany stosunek szerokości do wysokości dla elementu.

---

### 49. **Czy możesz wyjaśnić koncepcję hierarchii specyficzności CSS?**

Określa, które style mają zastosowanie na podstawie specyficzności selektora:

- style inline > ID > klasy > elementy.

---

### 50. **Jak stylizować pola wyboru i przyciski radiowe za pomocą CSS?**

Ukryj domyślne inputy i stylizuj niestandardowy element lub etykietę.

---

### 51. **Jaki jest cel właściwości line-height w CSS?**

Ustawia odstęp między liniami tekstu.

---

### 52. **Wyjaśnij, jakie elementy będą pasować do następujących selektorów CSS:**

- `div, p` - wybiera wszystkie elementy `<div>` oraz wszystkie elementy `<p>`.
- `div p` - wybiera wszystkie elementy `<p>`, które są wewnątrz elementu `<div>`.
- `div > p` - wybiera wszystkie elementy `<p>`, których bezpośrednim rodzicem jest element `<div>`.
- `div + p` - wybiera wszystkie elementy `<p>`, które są bezpośrednio po elemencie `<div>`.
- `div ~ p` - wybiera wszystkie elementy `<p>`, które są poprzedzone przez element `<div>`.
