# scal-SKU
## Opis

Aplikacja do szybkiego scalania SKU oddzielonych enterami w polu tekstowym. Użytkownik może wybrać separator (|, & lub +) i skopiować wynik do schowka. Duplikaty SKU są automatycznie wykrywane i usuwane, a użytkownik otrzymuje informację o ich liczbie.

## Do czego można to wykorzystać?
Pracując w Excelu, często operuję na plikach zawierających numery SKU, kody EAN, stany magazynowe i inne dane produktów. Wielokrotnie potrzebuję szybko sprawdzić, czym są te produkty, na jakich marketplace'ach są dostępne oraz zobaczyć ich miniaturki. Standardowo wymagałoby to ręcznego wpisywania każdego SKU w wyszukiwarkę BaseLinkera. Warto wiedzieć, że **w systemie BaseLinker można wyszukać wiele produktów jednocześnie, scalając ich numery SKU znakiem '|'**. Dzięki tej aplikacji mogę skopiować całą kolumnę SKU z Excela, wkleić ją do aplikacji, która automatycznie scali numery tym właśnie znakiem, i jednym kliknięciem wyszukać je w BaseLinkerze. To proste rozwiązanie znacząco przyspiesza pracę i analizę produktów.

## Funkcjonalności

- **Wklejanie SKU** – użytkownik wkleja listę SKU oddzielonych enterami.
- **Wybór separatora** – możliwość scalania SKU za pomocą `|`, `&` lub `+`.
- **Usuwanie duplikatów** – automatyczne usuwanie powtarzających się SKU.
- **Informacja o duplikatach** – liczba znalezionych duplikatów i ich lista.
- **Kopiowanie wyniku** – przycisk do szybkiego kopiowania scalonego SKU.
- **Powiadomienie o kopiowaniu** – komunikat o sukcesie z liczbą skopiowanych SKU.

## Jak używać?

1. Wklej SKU w pole tekstowe.
2. Wybierz separator za pomocą przycisków.
3. Otrzymasz scaloną listę SKU bez duplikatów.
4. Kliknij „Copy”, aby skopiować wynik.

## Technologie

- HTML
- CSS
- JavaScript

## Przykłady użycia

**Wejście:**

```
ABC123
XYZ456
ABC123
LMN789
```

**Wynik (separator **`|`**):**

```
ABC123|XYZ456|LMN789
```

**Powiadomienie:**

```
Znaleziono 1 duplikat: ABC123 (usunięto)
Skopiowano! (3)
```

