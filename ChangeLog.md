# Wykaz zmian

## Wersja 2.3 - 2022-08-25

### Zmiany w pliku

Usunięto arkusz "Akronimy" \
Zmieniono formatowanie wykazu krajów \

### Zmiany w metadanych

#### *Nowe pola*

Numer Zadania - obowiązkowe \
Identyfikator Działania - obowiązkowe \

### Zmiany w makrach

#### *Makro 1*

1. Dodano opcję eksportu do CSV całego zakresu, jeśli zaznaczony jest tylko jeden wiersz - dialog TAK/NIE/Anuluj "Czy eksportować do CSV cały zakres? Odpowiedź NIE oznacza tylko bieżący wiersz."
1. Zmieniono drugi wiersz przycisku na "Drukowanie etykiet (csv)"

#### *Makro 2*

1. Do pliku eksportu kopiowany jest także arkusz metadanych w wersji czystego tekstu (bez formuł).
1. Zmieniono drugi wiersz przycisku na "Zapis dla IMBIO (xlsx)"

#### *Reguły walidacji (makra 0, 1, 2)*

##### *Metadane*

1. Pole "Identyfikator kolekcji" jest opcjonalne, a nie obowiązkowe. Walidacja kompletności sprawdza "Nazwa kolekcji", a nie "Identyfikator kolekcji"
