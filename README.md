# challenge_portfolio_Olga

# TASK 1

## Subtask 1
9/10

## Subtask 3
Cześć! Jestem Olga. Zdecydowałam się na udział w challenge portfolio aby dostać wiatru w żagle, przybliżyć się do rozpoczęcia pracy jako testerka, ugruntować swoją wiedzę z zakresu testowania manualnego oraz zdobyć nową wiedzę.

Moim celem jest stworzenie imponującego portfolio, dzięki któremu otrzymam pierwszą pracę na stanowisku testerskim.

Moje oczekiwania wobec projektu: 

-motywacja do regularnej nauki 💪, 

-wsparcie mentorów 👼,

-przełożenie teorii na praktykę 👩‍🎓 , 

-zwieńczenie 7 tygodniowego wyzwania pięknym portfolio oraz gotowością do rekrutacji i podjęcia pracy!❤ ✊

## Subtask 4
*1.Na czym polega ta aplikacja? Do czego służy?*

Jest to aplikacja dla skautów piłki nożnej, która umożliwia przeglądanie oraz dodawanie do systemu wskaźników, umiejętności i pozycji zawodników. Ma za zadanie zarabiać pieniądze poprzez zbieranie danych na temat zawodników piłki nożnej.
  

*2.Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?*

-Funkcjonalność "Logowanie do systemu", intuicyjne, nic bym nie zmieniła

-Funkcjonalność "Przypomnij hasło" w panelu logowania: służy do odzyskania hasła do logowania. Hasło przysyłane jest na email, którym user się loguje. Intuicyjne, nic bym nie zmieniła

-Funkcjonalność "Wylogowanie z systemu", intuicyjne, nic bym nie zmieniła

-Funkcjonalność "Zmiana języka podczas logowania": ta opcja daje wybór używania aplikacji w języku polskim lub angielskim i jest dostępna na stronie logowania,a także na stronie głównej po zalogowaniu się. Zmieniłabym znaki chińskie przy tej opcji np na flagę PL i GBR

-Funkcjonalność "Wyświetlanie listy graczy": lista graczy pokazuje następujące dane zawodników: imię,nazwisko, wiek, pozycja, klub, recenzja, mecze, raporty. Nie podoba mi się, że aby zobaczyć wszystkie dane muszę przewijać ekran w poziomie, zmieniłabym tą tabele aby była widoczna w całości na ekranie

-Funkcjonaloność 'Download CSV': umożliwia ściągnięcie raportu o zawodnikach w formacie CSV

-Funkcjonalność 'Print': umożliwia wydruk raportu

-Funkcjonalność 'View columns': umożliwia dostosowanie raportu do potrzeb użytkownika. Można ustawić wszystkie kolumny jako widoczne lub ukryć wybrane kolumny

-Funkcjonalność 'Filter Table': umożliwia filtrowanie danych w tabeli używając imienia, nazwiska, wieku, pozycji, nazwy klubu, recenzji

-Funkcjonalność "Możliwość dodanie nowego gracza' znajdująca się w sekcji Linki pomocnicze, umożliwia dodanie nowego zawodnika piłki nożnej do systemu


*3.Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?*

Nie podoba mi się interfejs aplikacji. Nieciekawy wizualnie, niedopracowany. Uważam, że brakuje notyfikacji typu wyskakująca chmurka, informująca do czego służy dana funkcja. 


*4.Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).*

Aplikacja nie jest intuicyjna, jest mało czytelna. Np.: sekcja 'Aktywność' budzi moje wątpliwości- czy opisuje tylko moją aktywność czy również aktywność innych użytkowników.


*5.Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. Tutaj masz na to miejsce, czas i przestrzeń! ;)*

1.Scouts Panel  opisany jako "Panel zarządzania graczami, meczami i do tworzenia raportów" nie ma linka przekierowującego do panelu,a jednynie kieruje na stronę komunikatora slack

2.Uważam, że błedem jest to, że mogę modyfikować dane zawodników w sekcji 'Gracze'. Wydaje mi się, że prawo do modyfikacji powinien mieć tylko użytkownik który dodał zawodnika lub ewentualnie jeśli ja wprowadzam zmianę to zanim ta zmiana pojawi się w systemie to dobrze aby musiała być zaakceptowana przez osobę, która stworzyła profil gracza
  
3.Podczas dodawania nowego zawodnika i edycji danych zawodnika zauważyłam błędy w niżej wymienionych polach:
   
-w polu "Telefon" można wpisać litery i znaki specjalne, nie ma ograniczenia do liczb

-w polach "Waga" i "Wzrost" dozwolone są ujemne liczby

-w polu "Data urodzenia" można wybrać datę z przyszłości

-w polu "Email" można wpisać dane bez znaku @. System nie pozwala dodać takiego nieprawidłowego adresu email ale pokazuje komunikat "Nie udało się dodać gracza" zamiast informacji "Niepoprawny email"

-wydaje mi się, że w polu "Główna pozycja" powinna być lista rozwijana z której użytkownik mógłby wybrać jedną pozycję, uniemożliwiłoby to wpisywanie abstrakcyjnych danych

-w polu "Link do YouTube" można dodać dowolny link, system nie sprawdza czy jest to link do YT czy inny

-w polu "profil facebook" system akceptuje dowolne dane np ciąg dowolnych liter "sda", czyli nie sprawdza czy użytkownik dodaje profil facebook czy inne informacje 

4.Wydaje mi się, że brakuje regulaminu, polityki prywatności

# TASK 2

## Subtask 1
[Test cases based on user stories](https://docs.google.com/spreadsheets/d/1z9CauOVjWSE9k2EN3IC2ioWue8CZauHWuFPEwzzLzi0/edit?usp=drive_link)

## Subtask 2
[Test cases based on my experience](https://docs.google.com/spreadsheets/d/1txJj5OKO9oGMF5e15Xwt6wDyI2O15vAUVYjQD3NaaLw/edit?usp=drive_link)
## Subtask 3
WHY DO WE WRITE TEST CASES?

- In order to ensure software works correctly, meet requirements and behaves as expected 

- It is helpful identifying and eliminating errors
  
- Test cases can help us increasing the product quality

- It is a knowledge database regarding an application

- Test cases gives a possibility of repeating, documented testing

- While creating test cases we can prepare test data

- Test cases gives possibility of version control (thanks to changes in test cases, we can check the history of changes within functionalities)
## Subtask 4
  [Test cases Pick Eat Up application](https://docs.google.com/spreadsheets/d/15VfjP6AsxuIDrHiARE14TpvZYTjIqo8LWIOzHe5AiLE/edit#gid=0)

# TASK 3

## Subtask 1 & 2
  [Bugs report](https://docs.google.com/spreadsheets/d/1nz_T45o7ZRS5185DuLPUhqPCMWlNNJOdEDNHgiPVzOk/edit?usp=drive_link)

## Subtast 3
  [Test report](https://docs.google.com/spreadsheets/d/1ZS7UksGLoomzaqqRipTm0naByUu-gWj6GGJffIDasi8/edit?usp=drive_link)
  
## Subtask 4
  [Test cases based on "Guidebook tour" exploratory testimg session](https://docs.google.com/spreadsheets/d/1ajBTaI03hbp6EjGXFVksARfjW24qD8FeraD_K8IACrI/edit?fbclid=IwAR1mKqOwuYSU144t5l0OrcjbFAcGcC1aGHIkLG4hpb8NIa8YQVw4GV63cm0#gid=0)

# TASK 4

## Subtask 1&2
[Bug report OLX](https://docs.google.com/spreadsheets/d/1ytfrn4Ueni4n9h-oKC76BySwvrTAUrQJYDt2WXThYJQ/edit?usp=drive_link)

During 3hours testing I have found only 2 bugs. To be more precise: one bug and one inconvenience.

On my phone: Realme GT Master Edition with Adroid 13 the OLX app works very well. 

👉I was able to easily install it and login,

👉Menu options, buttons, history, settings, links and navigation flow of the application worked perfectly fine,

👉Expected notifications were displayed within the forms,

👉No issues while rotating the phone, I was able to take and make calls as well as take the messages

## Subtask 3

*Do czego służy aplikacja OLX? Jaki jest cel tej aplikacji?*

Aplikacja służy do kupowania rzeczy, usług oraz dodawania ogłoszeń w kategoriach: Antyki i Kolekcje, Motoryzacja, Nieruchmości, Praca, Dom i Ogród, Elektronika, Moda, Rolnictwo, Zwierzęta, Dla Dzieci, Sport i Hobby, Muzyka i Edukacja, Zdrowie i Uroda, Usługi, Noclegi, Wypożyczalnia, Dla Firm, Outlet i Oddam za darmo.

Celem aplikacji jest zarabianie. OLX zarabia na ogłoszeniach w płatnych kategoriach takich jak: Nieruchomości, Motoryzacja i Praca, na opłatach serwisowych, opłatach za możliwość promowania produktu, na reklamach płatnych


*Kto ma być użytkownikiem końcowym aplikacji?*

Ludzie mieszkający w Polsce (aplikacja jest dostępna jedynie w języku polskim). OLX jest dedykowany zarówno dla indywidualnych klietnów oraz dla firm


*Czy według Ciebie aplikacja jest user friendly?*

Moim zdaniem aplikacja OLX jest przyjazna dla użytkownika:

- Łatwy i szybki proces instalacji aplikacji na telefonie oraz rejestracji/logowania, jest prosta w obsłudze;
- Efektywna = duża łatwość wykonywania zadań przez użytkownika znającego już interfejs witryny;
- Zapamiętywalna = użytkownik szybko nabywa umiejętności poruszania się po witrynie i łatwo zapamiętuje obsługę nawet po dłuższym czasie nieobecności na niej;
- przyjemna w użytkowaniu poprzez: -szybkie ładowanie strony, -intuicyjną nawigację, -architekturę informacji (logiczne i uporządkowane informacje w witrynie), -czytelną treść i jakościowy content, -przemyślany interfejs i formularze (użytkownik ma do wykonania jak najmniej zadań), -wyszukiwarka ułatwia użytkownikowi odnalezienie konkretnej informacji/rzeczy i oszczędza jego cenny czas dzięki wyświetlającym się "proponowanym wyszukiwaniom" oraz opcji filtrowania, lupka znajduje się w widocznym miejscu, na górnej belce
 

*Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność?*

Dodałabym możliwość szybkiego nawiązania kontaktu z firmą. W dobie komunikatorów i social mediów użytkownicy są przyzwyczajeni do możliwości nawiązania kontaktu 24h/dobę, dlatego rozważyłabym implementację chatu czy messengera w witrynie lub przynajmniej dobrze widocznego przycisku "Napisz do nas". W tym momencie trzeba wejść w sekcję "Konto", przewinąć stronę, a następnie kliknąć "Pomoc". Przycisk Pomoc przekierowuje do strony w której jest dużo kategorii, które trzeba przeczytać żeby wybrać dotyczącą nas. 

*Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?*


|💻Aplikacja Webowa                             | 📱  Aplikacja Mobilna                             |
|-----------------------------------------------|---------------------------------------------------|
|Przeglądarki: wygląd i funkcjonalność          |Wykonywanie i przyjmowanie połączeń i wiadomości   |
|Rozdzielczości: wygląd i funkcjonalność        |Zmiany lokalizacji                                 |
|Responsywność: wygląd i funkcjonalność         |Obracanie                                          |
|Tytuł, Favicon, social media                   |Jakość połączenia                                  |
|Odporność na brak sieci                        |Przełączanie punktów dostępowych np. z wifi na LTE |
|Wydajność                                      |Tryb oszczędzania energii                          |
|Bezpieczeństwo: SQL injection, Script Injection|Energooszczędność                                  |


  
## Subtask 4
[link to Jira](https://olgagrzywa.atlassian.net/jira/software/projects/DCP/boards/3/backlog)

# TASK 5

## Subtask 1

Operatory/zapytania SQL jakich się nauczyłam?

|OPERACJE NA TABELI:    |OPERATORY:             |FUNKCJE:              |
|-----------------------|-----------------------|----------------------|
|-select,               |-operator porównania,  |-having, group by     |
|-insert,               |-operator SQL          |-data i czas          |
|-update,               |-operatory logiczne    |-funkcje tekstowe     |
|-delete,               |-operator arytmetyczny,|-funkcje matematyczne |
|-alter,                |-sortowanie wyników                         
|-drop                  |                                            


## Subtask 3

1.Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

![image](https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/a5cd0942-7a4a-4b74-89c6-5b47d3a95ffd)



2.Wyświetl film, który powstał w 2019 roku.

<img width="486" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/ad63195f-de51-4187-a095-e5ef5b1c975a">


3.Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

<img width="467" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/0fc380b2-bd6c-4fc7-a6a5-c82275ff6009">


4.Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$

<img width="463" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/fd650c6c-0c0c-4d6d-a982-fe3c48ed4cf5">


5.Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.



6.Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny.

<img width="449" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/0d9d0038-5915-4ecf-9f0f-64e83d7c75f1">


7.Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN.

8.Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

<img width="469" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/7584b991-8e7c-403b-81f4-c9484947cabd">


9.Wyświetl dane klienta, który nie ma podanego adresu email.

<img width="457" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/e3ba4fa8-75ef-4725-89f5-5a1b2b27a8cd">


10.Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

<img width="469" alt="image" src="https://github.com/OlgaG-M/challenge_portfolio_Olga/assets/143441787/d32ed401-03ca-46e0-88d8-ead8791629d3">


