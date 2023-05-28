# Zadanie 5 - Konwersja liczb

### T1 - Poprawna konwersja

**Warunki wstępne:**

Użytkownik znajduje się na stronie konwertera i dysponuje parą poprawnie przekonwertowanych liczb (np. 255 i FF)

**Kroki:**

1. W pole “Liczba 32-bitowa” wpisz liczbę, której poprawna wartość szesnastkowa jest znana.
2. Kliknij przycisk “Konwertuj” 

**Oczekiwany rezultat:**

Poprawna konwersja liczny dzieciętnej na szesnastkową.

### T2 - Walidacja pola “Liczba 32-bitowa”

**Warunki wstępne:**

Użytkownik znajduje się na stronie konwertera.

**Kroki:**

1. W pole “Liczba 32-bitowa” wpisz liczbę spoza poprawnej klasy równoważności (zdefiniowanej jako liczby od 0 do maksimum 32-bitowego 2,147,483,647)
2. Kliknij przycisk “Konwertuj” 

**Oczekiwany rezultat:**

Zgodnie z ustaleniami liczby większe od dopuszczalnego maksimum są zamieniane na największą możliwą liczbę po czym następuje konwersja na liczbę szesnastkową.

[![HrYuhua.md.png](https://iili.io/HrYuhua.md.png)](https://freeimage.host/i/HrYuhua)
---
Test 2 ujawnia błąd. Wszystkie liczby większe niż 65535 zwracają wynik 0001.