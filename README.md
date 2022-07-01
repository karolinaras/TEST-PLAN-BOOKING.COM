# TEST-PLAN-BOOKING.COM
Nauka pisania planu testu na przykładzie wyszukiwarki booking.com

NAME: TEST PLAN - wyszukiwarka

DESCRIPTION: 
  1.Wstęp
  Głównym celem działań testowych jestd dostarczenie interesariuszom informacji o jakości testowanego produktu.
  W przygotowanym dokumencie zostały zebrane kluczowe informacje na temat działań testowych. Zostały wyszczególnione wszystkie komponenty oprogramowania, które zostaną poddane weryfikacji, typy testów jakie zostaną przeprowadzone.
 
 2.Zakres testów
 Realizowane typy testów: 
 -testy jednostkowe
 -testy funkcjonalne
 -testy wydajnościowe
 Typy testów, które nie będą przeprowadzone:
 -testy automatyczne- ze względu na brak wystarczającego budżetu na etap związany z testowaniem oprogramowania.
 
 3.Przedmioty testów
 Komponentem poddawanym testom jest wyszukiwarka ze strony gównej booking.com z uwzględnieniem całej logiki filtrowania po odpowiednich polach.

4.Kryteria zaliczenia/niezaliczenia testów
-wykonanie zaprojektowanych przypadków testowych
-czas odpowiedzi serwera nie przekracza 700ms

5.Kryteria wejścia/wyjścia
Kryteria wejścia:
-zakończona jest faza implementacji wyszukiwarki
-działające i skonfigurowane środowisko
-dostęp do działającej i skonfigurowanej maszyny wirtualnej
Kryteria wyjścia:
-wszystkie przypadki testowe zostały zakończone pomyślnie
-komponent spełnia wszystkie ustalone założenia z załączonej dokumentacji

6.Lista wymagań funkcjonalności do przetestowania
Załącznie wsyzstkich dokumentacji, scenariuszy, user story itp.

7.Środowisko testowe
-testowy serwer(Development)
-system Windows 11 Home 64 bit
-przeglądarki biorące udział w testach: Firefox, Edge, Opera, Mozilla

8.Harmonogram testów
--przeprowadzenie testów funkcjonalnych:
-weryfikacja funkcjonalności w oparciu o user story - 3h
-wykonanie wcześniej zaprojektowanych przypadków testowych - 1h
-weryfikacja warstwy backendowej

--przeprowadzenie testów wydajnościowych:
-weryfikacja ile wynosi średni czas odpowiedzi
-weryfikacja jaka jest max ilość requestów przy jakiej wyszukiwarka działa stabilnie

9.Raport z testów
-lista zrealizowanych przypadków testowych wraz ze statusami
-pomiary z testów wydajnościowych
-inne raporty z testów

10.Lista narzędzi
-Jmeter
-Testlink
-Jira
-Browserstack

11.Zarządzanie incydentami,błędami
W procesie testowym każdy wykryty błąd powinien być odpowiednio zaroportowany do systemu Jira. Uwzględniając przy tym piorytet błędu, osobę przypisaną,komponent,którego dotyczy problem.
Zgodnie z przyjętym flow przez naszą organizację problem powinien zostać naprawiony przez dewelopera i trafić do retestów.

12.Role i odpowiedzialność
Karolina Raś - projektowanie i wykonywanie przypadków testowych


