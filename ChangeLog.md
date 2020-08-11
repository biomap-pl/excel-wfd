# Wykaz zmian

## Wersja 2.2 - 2022-08-07

### Zmiany w arkuszu 

#### *Zmiany nazw pól*

OrigTaxonName -> VerbatimTaxonName\
OrigLabelText -> VerbatimSourceText\
OrigLocality -> VerbatimLocalityText\
OrigLocalityLanguage -> VerbatimLocalityLanguage\
AssociatedSpeciesRecordCode -> AssociatedSpeciesRecordID\
DateText -> VerbatimDateText

#### *Nowe pole*

VerbatimSourceTextScheme\

### Zmiany w makrach

#### *Makro 0*

Walidacja danych prawidłowych zwraca komunikat "Dane są poprawne!".

#### *Makro 2*

Nazwa pliku eksportu wg schematu *imbio-wfd-[nr partnera z zerem wiodącymi]-[prefiks]-[data]-[godzina]*.

#### *Makro 3*

Korekta liczby zer wiodących w BarcodeID (łącznie 6 miejsc).

#### *Reguły walidacji (makra 0, 1, 2)*

1. Dodane sprawdzanie pól *Contributor* i *RecordBasis*. 

2. Puste komórki w sprawdzanych kolumnach zmieniają wypełnienie na kolor żółty. 

3. Metadane - sprawdzenie kompletności zwraca wykaz pustych pól, które należy wypełnić.
