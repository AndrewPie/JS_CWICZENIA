# SVG
---------------------------------------------------

## Słowo wstępu
> SVG oznacza Scalable Vector Graphics, czyli skalowalną grafikę wektorową. Język SVG jest oparty na języku XML i jest oficjalnym standardem World Wide Web Consortium. Pierwsza wersja rekomendacji, czyli SVG 1.0, ukazała się 4 września 2001 roku, natomiast SVG 1.1 Second Edition ukazało się 16 sierpnia 2011 r.
>
>Obraz w formacie SVG jest obrazem zbudowanym z poleceń zapisanych w postaci tekstu, analogicznych do języka HTML czy CSS - przeglądarka z wbudowanym interpreterem SVG (wszystkie główne przeglądarki, w tym Internet Explorer 9, wspierają SVG, natomiast Internet Explorer 8 wymaga zainstalowania bezpłatnej wtyczki Adobe SVG Viewer) czyta kod i interpretuje go, wyświetlając obraz zgodnie z oczekiwaniem autora.

z [SVG Tutorial helion]

Podstawowe tagi SVG w przykładach na podstawie http://webmaster.helion.pl/index.php/svgpodstksztalty:
- Figury:
    - Prostokąt: `<rect height="128" width="276" y="33" x="46" stroke-width="5" stroke="#000000" fill="#FF0000"/>`
    - Koło/Okrąg: `<circle r="84" cy="104" cx="108" stroke-width="5" stroke="#000000" fill="#ff7f00"/>`
    - Elipsa: `<ellipse fill="#4cff00" stroke="#007fff" stroke-width="5" cx="200" cy="70" rx="170" ry="50"/>`
    - Wielokąt: `<polygon points="50,5  100,5  125,30  125,80  100,105  50,105  25,80  25,30" style="stroke:black; fill:#cc3333; stroke-width: 5;"/>`
- Linie:
    - Odcinek: `<line y1="26" x1="39" y2="130" x2="451" stroke-width="5" stroke="#7f3f00" fill="none"/>`
    - Łamana: `<polyline points="10,40  50,30  60,50  80,120  120,140  200,100" style="fill:none;stroke:brown;stroke-width:5" />`

---------------------------------------------------
Przydatne:
- [SVG Wikipedia]
- [Inkscape]
- [SVG Tutorial w3schools]
- [SVG Tutorial helion]
- [SVG specyfikacja na W3C]
- [SVG jako wizualizacja pracy SSN]
- [Snap.svg]

---------------------------------------------------

## Zadania
### Zadanie 0.
Wykonaj fork repozytorium. Następnie sklonuj repozytorium tak, aby było możliwe przejście do niego pod adres http://wwwold.fizyka.umk.pl/~TWOJ_NUMER_INDEKSU/opss2-svg/

### Zadanie 1.
Zapoznaj się z plikiem `index.html`.

### Zadanie 2.
Dodaj losową zamianę  parametru wiatru po każdym strzale oraz tekstową informację o jego wartości.

### Zadanie 3.
Dodaj animowane przesuwające się chmury lub inne podobne obiekty graficznie reprezentujące siłę wiatru.

### Zadanie 4.
Dodaj losową zmianę położenia celu po każdym poprawnym strzale(błąd do 125px)

### Zadanie 5 - dla chętnych.
Dodaj możliwość zmiany grawitacji suwaka lub innego mechanizmu jQueryUI.

### Zadanie 6 - dla nadal nie usatysfakcjonowanych.
Dodaj możliwość regulacji siły strzału za pomocą przytrzymania klawisza spacji wraz z wizualizacją.

### Zadanie 7 - dla niestrudzonych.
Dodaj przeszkodę - ścianę.

### Zadanie 8 - dla niestrudzonych, którzy naprawdę mają nadmiar czasu i ogromne chęci.
Zmień wizualizację pocisku z `#bullet` na `#bullet-advanced` z uwzględnieniem kąta ruch pocisku. Do wyliczenia kąta możesz użyć [Math.atan2]

[SVG Wikipedia]: https://pl.wikipedia.org/wiki/Scalable_Vector_Graphics
[Inkscape]: https://inkscape.org/
[SVG Tutorial w3schools]: https://www.w3schools.com/graphics/svg_intro.asp
[SVG Tutorial helion]: http://webmaster.helion.pl/index.php/svgwstep
[SVG specyfikacja na W3C]: https://www.w3.org/TR/SVG2/
[SVG jako wizualizacja pracy SSN]: http://www.is.umk.pl/sieci-neuronowe-js-demo/
[Snap.svg]: http://snapsvg.io/
[Math.atan2]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/atan2
