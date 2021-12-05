Wstęp
------------

* [Oprogramowanie](#oprogramowanie)
* [Materiały pomocnicze](#materiały-pomocnicze)
* [Web portal](#web-portal)
* [Systemy symulacji](#systemy-symulacji)
* [Infrastruktura](#infrastruktura)

Oprogramowanie
------------

**Opis**: Na finalny produkt o nazwie oprogramowanie składają się cztery części. Są to [skrypty zadań](#skrypty-zadań), [system generowania raportów](#system-generowania-raportów)system generowania raportów, [grupowy komunikator](#grupowy-komunikator)grupowy komunikator oraz [system zbierania i analizowania danych](#system-zbierania-i-analizowania-danych)system zbierania i analizowania danych.

### Skrypty zadań

### System generowania raportów

### Grupowy komunikator

### System zbierania i analizowania danych


Materiały pomocnicze
------------

Web portal
------------

Systemy symulacji
------------

Infrastruktura
------------

**Opis**: Częściami składowymi całej infrastruktury projektu cyberpoligonu są  [serwery do wirtualizacji](#serwery-do-wirtualizacji),  [dedykowana sala wykładowa](#dedykowana-sala-wykładowa), [routery i switche](#routery-i-switche) oraz [serwery](#serwery).

### Serwery do wirtualizacji
Serwery te służą do wirtualizacji środowiska na którym odbywają się wcześniej opracowane symulacje. Na serwerach wdrożone są rozwiązania oparte o konteneryzacje na technologii Docker. 

### Dedykowana sala wykładowa
Do poprawnego działania cyberpoligonu niezbędne jest dobrze wyposażone miejsce robocze, w tym wypadku sala wykładowa. W takiej sali musi znajdować się odpowiednia ilość stanowisk do pracy, okablowanie, oraz komputery posiadające odpowiednie licencje.

### Routery i switche
Zadaniem routerów i switchów jest integracja elementów wchodzących w skład sieci cyberpoligonu. Tworzą dedykowaną sieć lokalną na której zachodzi wymiana danych ze stanowisk. Są one skonfigurowane, aby utworzyć wydzieloną sieć akademicką.

### Serwery
Serwery wchodzące w skład cyberpoligonu dzielą się na serwer HTTP oraz serwer bazodanowy(MySQL). 

Serwer HTTP obsługuje żądania protokołu komunikacyjnego. Obsługuje on stronę sieciową cyberpoligonu, na której znajdują się informacje na temat produktu, producenta, oraz niezbędne informacje do komunikacji z producentem.

Serwer bazodanowy(MySQL) wykorzystywany jest do zarządzania i równoczesnego udostępniania danych niezbędnych do prawidłowego funkcjonowania cyberpoligonu. Dzięki serwerom bazodanowym przechowywane zbiory danych są spójne a odpowiednie mechanizmy zapewniają ich bezpieczeństwo. Głównymi zbiorami danych na tym serwerze to baza danych zadań, baza danych materiałów pomocniczych, oraz baza danych wykorzystywana do monitorowania procesu symulacji.


