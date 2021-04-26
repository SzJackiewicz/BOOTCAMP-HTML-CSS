![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709387-2b7ac180-571f-11eb-9b94-517aa6d501c9.png)



> W katalogu z ćwiczeniem znajdziesz plik `index.html`. Otwórz go w przeglądarce WWW (wystarczy jeżeli klikniesz na niego dwa razy).  
> Otwórz też pliki przygotowane do tego zadania w wybranym przez siebie edytorze kodu (WebStorm/PyCharm/InetlliJ). 

## Stylowanie treści

Na górze i dole strony są 2 paski, które mają ustawioną szerokość na 80%. Między nimi znajduje się element `.content`, czyli treść strony na białym tle. 
s
Ustaw temu elementowi stylowanie:
* maksymalną szerokość (max-width) na `80%`,
* wewnętrzny odstęp od krawędzi elementu `50px` z każdej strony.

Jak widzisz, po zastosowaniu powyższych właściwości nasz element jest nieco szerszy od dolnego i górnego paska. Z czego to wynika? Spróbuj to naprawić za pomocą właściwości `box-sizing`.


## Stylowanie przycisków

W treści strony znajduje się element `.btn`. 

Zastosuj dla niego stylowanie:
* odstęp wewnętrzny ustawiony na `20px 40px`,
* margines dolny `20px`.

Jak widzisz, element nie do końca dobrze się wyświetla. Dlaczego? Wynika to z faktu, że jest to ostylowany link – a linki mają domyślne wyświetlanie typu `inline`. Czym takie wyświetlanie się charakteryzuje? Zmień je na odpowiednie.


## Galeria

Na samym dole strony jest galeria o klasie `.gallery`. W jej wnętrzu znajduje się lista zdjęć o klasie `.gallery-content`, w której znajdują się ułożone poziomo zdjęcia. Niestety nie mieszczą się one w poziomie, a klient nie chce, by zajmowały więcej miejsca w pionie – więc nie mogą się zawijać.  
Za pomocą odpowiedniej właściwości spraw, by w elemencie `.gallery-content` pojawił się poziomy pasek przewijania. 
