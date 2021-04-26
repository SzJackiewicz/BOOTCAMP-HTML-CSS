![Coders-Lab-1920px-no-background](https://user-images.githubusercontent.com/30623667/104709387-2b7ac180-571f-11eb-9b94-517aa6d501c9.png)



> W katalogu z ćwiczeniem znajdziesz plik `index.html`. Otwórz go w przeglądarce WWW (wystarczy jeżeli klikniesz na niego dwa razy).  
> Otwórz też pliki przygotowane do tego zadania w wybranym przez siebie edytorze kodu (WebStorm/PyCharm/InetlliJ). 


Strona zawiera opis Pragi i galerię zdjęć. Twoim celem jest poprawienie jej wyglądu.


## Kontener z treścią

Pierwsza rzecz do poprawienia to kontener z treścią. Jest to element o klasie `.container`. 
Zastosuj dla niego stylowanie:

* szerokość: **680px**,
* maksymalna szerokość (właściwość max-width): **90%**,    
* odstęp tekstu od krawędzi kontenera: **50px**,
* kolor tła: **rgba(255, 255, 255, 0.95)**,    
* wielkość tekstu: **15px**,
* wielkość interlinii: **1.5em**,
* kolor tekstu: **rgba(0, 0, 0, 0.6)**.


## Nagłówki

Kolejnym elementem będzie wygląd nagłówków `h1, h2`.

Dodaj im stylowanie:
* kolor tekstu: **#b4411e**,
* wielkość tekstu: **32px**,
* wielkość interlinii: **1em**.


## Galeria

### Część 1

Zajmij się teraz galerią. Znajdują się w niej linki ze zdjęciami, czyli elementy `.gallery a`.

Nadaj im stylowanie:
* max-width: **50%**,
* padding: **3px**.


### Część 2

Nawet, gdy nadaliśmy linkom szerokość na 50%, zdjęcia wciąż nie mieszczą się w tych linkach. Wynika to z faktu, że grafiki `img` domyślnie wyświetlają się w swoich **oryginalnych rozmiarach** – popraw to.

Dla elementów `.gallery img` dodaj stylowanie:
* maksymalna szerokość (max-width) na **100%**
