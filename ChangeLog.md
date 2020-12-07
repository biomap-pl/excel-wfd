# Wykaz zmian

## Wersja 2.5 - 2020-12-07

### Zmiany w danych

#### Nowe pola
ObservedAboundance

#### Zmieniony nagłówek
AssociatedSpeciesRecordID --> AssociatedSpeciesBarcodeID

### Zmiany w makrach

#### *Makro 0*
Walidacja rozszerzona o sprawdzanie, czy w wierszu z nagłówkami znajdują się wymagane kolumny (pobierane z arkusza "schemat danych - opis pól").

#### *Makro 1*
Usunięcie usterek zw. z użyciem cudzysłowu i korekta wydajności eksportu.

#### *Makro 5*
Korekty:
1. Import metadanych,
1. Drobne zmiany dotyczące wyglądu formularza i jego kontroli,
1. Po zakończeniu pracy makra jest ustawiana domyślna szerokość dla wszyskich kolumn,
1. Poprawiono bugi.


<!-- ======================================= -->
## Wersja 2.4 - 2020-10-19

### Zmiany w schemacie danych

#### Nowe pola
Aspect, Slope

#### Zmiany w przyciskach aktywujących makra
1. Zmieniono kolorystykę
1. Zmieniono tekst na przyciskach

### Zmiany w metadanych
Skorygowano metadane i formatowanie warunkowe.

### Zmiany w makrach

#### *Makro 0*
Złączono komunikaty o błędach w jeden komunikat zbiorczy.

#### *Makro 1*
1. Złączono komunikaty o błędach w jeden komunikat zbiorczy
1. Zmieniono treść komunikatu "Drukowanie etykiet x:y" na "Eksport wierszy od x do y"

#### *Makro 2*
1. Złączono komunikaty o błędach w jeden komunikat zbiorczy

#### *Makro 3*
1. Zmieniono nagłówek formularza z "Podaj zakres" na "Podaj zakres wartości końcówki kodu"

#### *Makro 5* (nowe)
Makro importuje dane z arkusza *dane* z wybranych przez użytkownika plików *.xlsx* i *.xlsm* 

<!-- ======================================= -->
## Wersja 2.3 - 2020-08-25

### Zmiany w pliku

Usunięto arkusz "Akronimy".\
Zmieniono formatowanie wykazu krajów.

### Zmiany w metadanych

#### *Nowe pola*

Numer Zadania - obowiązkowe.\
Identyfikator Działania - obowiązkowe.

### Zmiany w makrach

#### *Makro 1*

1. Dodano opcję eksportu do CSV całego zakresu, jeśli zaznaczony jest tylko jeden wiersz - dialog TAK/NIE/Anuluj "Czy eksportować do CSV cały zakres? Odpowiedź NIE oznacza tylko bieżący wiersz."
1. Zmieniono drugi wiersz przycisku na "Drukowanie etykiet (csv)"

#### *Makro 2*

1. Do pliku eksportu kopiowany jest także arkusz metadanych w wersji czystego tekstu (bez formuł)
1. Zmieniono drugi wiersz przycisku na "Zapis dla IMBIO (xlsx)"

#### *Reguły walidacji (makra 0, 1, 2)*

##### *Metadane*

1. Pole "Identyfikator kolekcji" jest opcjonalne, a nie obowiązkowe. Walidacja kompletności sprawdza "Nazwa kolekcji", a nie "Identyfikator kolekcji"