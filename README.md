1. Stwórz nowy projekt. Wykonaj w nim następujące polecenia:
* Napisz w nim pustą klasę `Pojazd` oraz dwie dziedziczące po niej klasy `Samochod` i `Rower`.
* Teraz utwórz interfejs `Jazda`, zawierający deklarację metody `Jedz()` typu `void`.
* Podepnij interfejs do klas `Samochod` i `Rower` i zaimplementuj metodę `Jedz()` w sposób niejawny wyświetlając w konsoli komunikat `"Jadę samochodem"` lub `"Jadę rowerem"`.
* Stwórz po jednym obiekcie typu `Samochod` i `Rower`. Dla nowo utworzonych obiektów wywołaj metodę `Jedz()` i zobacz co wyświetli się na ekranie.
* Stwórz nowy interfejs `Muzyka` z metodą `Klakson()` typu `void` i podepnij go do klasy `Rower`. Następnie dodaj implementację, by ta metoda wyświetla łańcuch `"dryń"`. Wywołaj metodę na obiekcie typu `Rower`. Czy wielodziedziczenie interfejsów w Java jest możliwe?
* Narysuj diagram UML projektu.
* Skorzystaj z rzutowania w górę i stwórz obiekt `Rower` zrzutowany na typ `Pojazd` (`Pojazd rower2 = new Rower();`). Wywołaj na tym obiekcie metodę `Klakson()`. Czy to jest możliwe?
