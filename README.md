# Podravina Meteo

## Opis
Jednostavna i brza web aplikacija za prikaz vremenskih podataka, prognoze i radarskih slika, primarno fokusirana na Podravinu, ali s mogućnošću dodavanja drugih lokacija. Aplikacija koristi javno dostupne API-je za dohvat podataka u stvarnom vremenu.

## Mogućnosti
*   **Trenutno vrijeme**: Prikaz temperature, vjetra, vlage i tlaka zraka s najbliže meteorološke postaje (DHMZ).
*   **Interaktivna karta**: Prikaz meteoroloških postaja na karti s različitim slojevima (temperatura, vjetar, vlaga, tlak).
*   **Prognoza**:
    *   Kratkoročna i dugoročna prognoza (do 7 dana) koristeći MET Norway podatke.
    *   Detaljna prognoza po satima.
*   **Radar**: Animirani prikaz oborina (radar) u zadnjih sat vremena.
*   **Meteoalarm**: Prikaz aktivnih upozorenja za Zagrebačku regiju.
*   **Agro kutak**: Savjeti za poljoprivrednike.
*   **Postavke lokacije**:
    *   Automatsko lociranje (GPS).
    *   Ručno pretraživanje i dodavanje lokacija.
*   **Dizajn**: Moderno sučelje prilagođeno mobilnim uređajima i tamna tema (Dark Mode).

## Tehnologije
*   HTML5 / CSS3 / JavaScript (Vanilla)
*   [Tailwind CSS](https://tailwindcss.com/) (putem CDN-a)
*   [Leaflet.js](https://leafletjs.com/) (za karte)
*   OpenStreetMap (pločice za kartu)

## Izvori podataka
*   **DHMZ (Državni hidrometeorološki zavod)**: Trenutni podaci mjerenja i radarske slike.
*   **MET Norway**: Vremenska prognoza.
*   **Meteoalarm**: Upozorenja o opasnim vremenskim pojavama.
*   **Nominatim (OpenStreetMap)**: Pretraživanje lokacija.

## Kako pokrenuti
Jednostavno preuzmite `index.html` datoteku i otvorite je u bilo kojem modernom web pregledniku. Nije potrebna instalacija niti pokretanje servera (osim ako preglednik ne blokira CORS, u kojem slučaju koristite proxyje koji su već integrirani u kod ili lokalni server).

**Napomena**: Aplikacija koristi `corsproxy.io` za zaobilazak CORS ograničenja pri dohvatu podataka s nekih servisa.
