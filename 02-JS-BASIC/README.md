# Java Script - podstawy
---------------------------------------------------
## Słowo wstępu
### https://pl.wikipedia.org/wiki/JavaScript
> JavaScript (w skrócie JS) – skryptowy język programowania, stworzony przez firmę Netscape, najczęściej stosowany na stronach internetowych. Twórcą JavaScriptu jest Brendan Eich. Pod koniec lat 90. XX wieku organizacja ECMA wydała na podstawie JavaScriptu standard języka skryptowego o nazwie ECMAScript, aktualnie rozwijaniem tego standardu zajmuje się komisja TC39.
>
> Najczęściej spotykanym zastosowaniem języka JavaScript są strony internetowe. Skrypty te służą najczęściej do zapewnienia interakcji poprzez reagowanie na zdarzenia, walidacji danych wprowadzanych w formularzach lub tworzenia złożonych efektów wizualnych. Skrypty JavaScriptu uruchamiane przez strony internetowe mają znacznie ograniczony dostęp do komputera użytkownika. Po stronie serwera JavaScript może działać w postaci node.js lub Ringo.
>

---------------------------------------------------
### Technologie Webowe, a desktop
Interesującym dla studentów OPSS2 może być również [Electron], czyli projekt pozwalający tworzyć desktopowe aplikacje dla większości popularnych systemów operacyjnych (np. Linux, MacOS czy Windows) w technologoiach WEB'owych.

Popularnymi projektami opartymi na [Electron]ie są np.:
* [Skype]
* [WhatsApp] Dekstop
* Microsoft [Code Visual Studio]
* [Atom]

**Ze względu na powyższe możliwe jest wykonywanie projektu końcowego przy użyciu [Electron]a.**

Istnieją też inne sposoby na pisanie aplikacji dekstopowych przy pomocy html/css/js jak np. XUL czy MS HTA.

Ciekawostka [Windows95](https://github.com/felixrieseberg/windows95/releases/tag/v2.0.0) w Electronie

---------------------------------------------------
## Zadania
### Zadanie 0.
Wykonaj fork i sklonuj repozytorium, a następnie podlinkuj z niego katalog `cwiczenia` tak, aby było możliwe przeście pod adres http://wwwold.fizyka.umk.pl/~TWOJ_NUMER_INDEKSU/opss2-js-basic/
### Zadanie 1.
W pliku `calc.html` znajduje się szablon kalkulatora. Dopisz odpowiednie funkcje oraz przypnij odpowiednie zdarzenia tak, aby możliwe było wykonywanie działań.
### Zadanie 2.
Do kalkulatora z `Zadania 1` dopisz historię obliczeń - każde obliczenie powinno wyświetlić się powyżej lub poniżej formularza w pojedyńczej linii.
### Zadanie 3.
W pliku `ninja.html` znajduje się szablon gry. Dopisz odpowiednie funkcje oraz przypnij odpowiednie zdarzenia tak, aby możliwe było poruszanie postacią oraz jej ukrycie(plik ukrytej postaci znajduje się w pliku `hidden_ninja.gif`).
### Zadanie 4.
Znajdź w Internecie informacje jak przechwycić wciśnięcia klawiszy za pomocom skryptu JS. Dopisz odpowiednie fragmenty kodu, tak aby po wciśnięciu jakiegoś klawisza wykonać akcje. Dodaj w ten sposób po wciśnięciu `spacji` rzut gwiazdą ninja (można użyć znaku * jako symbolu). Gwiazda powinna się poruszać z zadaną prękością przez dwie sekundy po czym powinna zniknąć. Dopiero wtedy możliwy ma być kolejny rzut.
### Zadanie 5 - dla chętnych.
Spróbuj dodać cel do rzutów gwiazdą ninja i zliczanie punktów. Najprostszym sposobem na wykrycie kolizji jest sprawdzenie odległości między obiektami.
### Zadanie 6 - dla nadal nie usatysfakcjonowanych.
Spróbuj sprawić, aby gwiazda ninja po rzucie poruszała się parabolą lub krzywą balistyczną.
### Zadanie 7 - dla niestrudzonych.
Spróbuj sprawić, aby cel się poruszał.
### Zadanie 8 - dla niestrudzonych, którzy naprawdę mają nadmiar czasu i ogromne chęci.
Dodaj możliwość zmiany siły i kąta rzutu.

---------------------------------------------------
[Electron]: https://electronjs.org/
[Skype]: https://www.skype.com/
[WhatsApp]: https://www.whatsapp.com/
[Code Visual Studio]: https://code.visualstudio.com/
[Atom]: https://atom.io/
