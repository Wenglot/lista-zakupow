Lista Zakupów
Prosta aplikacja webowa do zarządzania listą zakupów, stworzona w HTML, CSS i JavaScript. Umożliwia dodawanie, usuwanie i oznaczanie produktów jako kupione, z zapisywaniem danych w localStorage.
Funkcjonalności

Dodawanie produktów do listy z podstawową walidacją (nie można dodać pustego pola).
Usuwanie produktów za pomocą przycisku „Usuń”.
Oznaczanie produktów jako kupione za pomocą checkboxa (przekreślenie tekstu).
Trwałość danych dzięki localStorage – lista pozostaje po odświeżeniu strony.

Technologie

HTML: Struktura strony i formularz dodawania produktów.
CSS: Stylizacja z użyciem Flexbox, responsywny design.
JavaScript: Logika aplikacji, manipulacja DOM, obsługa localStorage.

Jak uruchomić?

Sklonuj repozytorium:git clone https://github.com/wenglot/lista-zakupow.git


Otwórz plik index.html w przeglądarce (np. Chrome, Firefox).
Wpisz nazwę produktu w polu tekstowym, kliknij „Dodaj”, oznacz jako kupione lub usuń.


Dodanie responsywności dla urządzeń mobilnych.
Możliwość edycji istniejących produktów.
Filtrowanie listy (np. tylko kupione/niekupione produkty).
Poprawa semantyki HTML (np. <button> zamiast <a> dla „Usuń”).

Autor

Imię: [Bartłomiej Gawlas]
GitHub: [Wenglot]
Kontakt: [bartek.gawlas@onet.pl]

Nauka
Projekt powstał w ramach nauki programowania webowego:

Tworzenia dynamicznych elementów w DOM za pomocą document.createElement.
Obsługi zdarzeń (addEventListener) i manipulacji stylami w JavaScript.
Używania localStorage do zapisywania danych po stronie klienta.
Podstawowej stylizacji z Flexbox w CSS.
