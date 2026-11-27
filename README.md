# projekt jquery sklep z koszykiem

prosta strona sklepu komputerowego z koszykiem zakupowym wykonana w HTML, CSS i jQuery

## co robi strona
- Wyświetla 8 produktów ze zdjęciem, nazwą i ceną (dane są w atrybutach data-nazwa i data-cena)
- Pozwala dodawać produkty do koszyka i zwiększać ich ilość jeśli produkt już w nim jest
- Umożliwia zmianę ilości przyciskami plus i minus oraz usuwanie produktów, liczy wartość każdej pozycji
- Automatycznie przelicza sumę koszyka za pomocą pętli each()
- Dolicza 15zł za dostawę (darmowa od 200zł), pokazuje ile brakuje do darmowej dostawy
- Obsługuje kod rabatowy SZKOLA10 na 10% znizki oraz pokazuje błąd przy złym kodzie
- Aktualizuje licznik sztuk w nagłówku i pokazuje komunikat, gdy koszyk jest pusty
- Przycisk zamów aktywny tylko gdy w koszyku są produkty, po kliknięciu wyświetla podsumowanie i czyści koszyk

## uruchomienie
Otwórz plik index.html w przeglądarce