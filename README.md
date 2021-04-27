# Engler
Nauka języka angielskiego w grach

Aplikacja webowa do nauki języka angielskiego. Za pomocą questów w grze możesz nauczyć się dużo nowych slów i nowe reguły z języka angielskiego.

Autorzy - Artsiom Kirpaniou, Daniil Kochyk

Licencja – ADWare

#### Wymagania funkcjonalne

|Identyfikator|Nazwa krótka|      Opis   | Priorytet |
|-------------|-----------|-------------|-------------|
|1.| Logowanie I rejstracja |stworzyć stronę dla rejestracji I logowania użytkowników |1|
|2.| Strona konta uzytkownika| Strona konta użytkownika z informacją o koncie I statystyką z gry| 1 |
|3.| Strona z wyborem gier |Strona na której będzie lista z grami oraz ich poziomy które może wybrać użytkownik | 1 |
|4. |Statystyka z gier | Informacja o swoich grach | 2 |
|5. |Forma kontaktowa |Strona z możliwosćią wysłania formy(wiadomości) dla wsparcia klinetów| 2|
|7. |Strona administratora| Strona na którą może wejśc tylko administrator i dodawać lub usuwać gry, quizy, zarządza kontami użytkowników| 1| 


#### Wymagania niefunkcjonalne

|Identyfikator| Nazwa krótka| Opis |Priorytet|
|--------------|------------|------------|----------|
|1.| Wielopłatformowość| Stworzenie aplikacji mobilnej| 3|
|2.| Użyteczność |Szybka nawigacja w aplikacji, interfejs łatwy do zrozumienia |1|
|3. |Bezpieczeństwo |Zgodność z wymogami bezpieczeństwa(zabiespieczenie danych użytkowników) |2|
|4.| Dostępność| Dostęp dla użytkowników do użytku w dowolnym momencie| 1|
|5.| Wydajność| Szybkość reakcji aplikacji na zapytania| 1|
|6.| Wykorzystanie pamięci operacyjnej |Minimalna zajętość w procentach pamięci RAM| 2|

                                                          
                                                          Priorytet [1-wymagana, 2 - oczekiwana, 3 - dodatkowa]


#### Architektura systemu/oprogramowania
##### Architektura rozwoju
|Lp| Nazwa produktu |Przeznaczenie w projekcie |Wersja|
|-----|-------|-------|-------|
|1.| C#| Backend| 4.0|
|2.| Angular.js| Frontend |11.0.2|
|3. |SQL server 2019| Baza danych |15.0|

##### Architektura uruchomieniowa
|Lp |Nazwa produktu| Przeznaczenie w projekcie| Wersja|
|-------|---------|---------|--------|
|1.| Visual studio code| Środowisko używane przy tworzeniu frontendu |1.55.10|
|2.| Visual studio 2019| Środowisko używane przy tworzeniu backendu |16.9.3 Community|
|3. |Windows 10 |System operacyjny używany przy tworzeniu projektu |10.0.19041.867|
|4.| Git| Systemy kontroli wersji aplikacji |2.31.1|
|5.| GitHub |Utrzymywanie projektu na serwerze, do którego mają dostęp członkowie zespołu| --|
|6. |Azure Dedicated Host| Serwer do hostowania||
