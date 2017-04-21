Opis innowacji aplikacje.gov.pl - EZD
=====================================

Uwaga: Przed niektórymi nazwami znajduje się numer. Prośba o jego
pozostawienie - ułatwia śledzenie zmian w stosunku do innych
analizowanych systemów.

Aplikacje.gov.pl - Twoje nowe miejsce pracy

**#innowacja Rozwiązanie dostępne na urządzeniach mobilnych**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**#innowacja Rozwiązanie dostępne w chmurze**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**#innowacja Dzięki jasnemu wydzieleniu EZD dajemy więcej przestrzeni na rozwój nowych, wyspecjalizowanych aplikacji dla urzędników**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**#innowacja Niezaprzeczalność danych w systemie**

**1. Korespondencja przychodząca**
==================================

Ta część systemu służy przyjęciu, zarejestrowaniu, opisaniu i
rozdzieleniu korespondencji przychodzącej do urzędów. Korespondencja po
wpływie przechodzi przez kluczowy dla działania systemu etap -
**rejestrację oraz nadanie metadanych**. Od tego momentu wpływ
funkcjonuje w systemie, można go wyszukać, przekazywać oraz prowadzić na
nim działania merytoryczne.

**Miejsce rejestracji korespondencji przychodzącej**

+---------------------------------------+------------------------+-------------+
| Rodzaj korespondencji przychodzącej   | Kancelaria lub         | Konto       |
|                                       | sekretariat urzędu     | użytkownika |
+=======================================+========================+=============+
| przesyłka złożona osobiście           | X                      |             |
+---------------------------------------+------------------------+-------------+
| list zwykły                           | X                      |             |
+---------------------------------------+------------------------+-------------+
| list polecony                         | X                      |             |
+---------------------------------------+------------------------+-------------+
| paczka pocztowa                       | X                      |             |
+---------------------------------------+------------------------+-------------+
| przesyłka kurierska                   | X                      |             |
+---------------------------------------+------------------------+-------------+
| plik xml z systemu ePUAP (portal do   | X                      | X           |
| kontaktów z urzędami)                 |                        |             |
+---------------------------------------+------------------------+-------------+
| wiadomość poczty elektronicznej       | X                      | X           |
+---------------------------------------+------------------------+-------------+
| wiadomość poczty elektronicznej z     | X                      | X           |
| załącznikiem                          |                        |             |
+---------------------------------------+------------------------+-------------+
| fax                                   | X                      |             |
+---------------------------------------+------------------------+-------------+

`**#innowacja** <https://laboratoriumee.hackpad.com/ep/search/?q=%23innowacja&via=MLQHmZI3w8y>`__ **Metadane w systemie pobierane są w sposób automatyczny**
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Metadane w systemie pobierane są w sposób automatyczny z systemów i baz
zewnętrznych:

-  envelo
-  REGON
-  fax
-  e-mail

`**#innowacja** <https://laboratoriumee.hackpad.com/ep/search/?q=%23innowacja&via=MLQHmZI3w8y>`__
**Integracja z elektronicznym klientem faxu** Rocznie w MC
rejestrowanych jest 12 000 faxów, które skanuje się do systemu. W ramach
systemu powinien funkcjonować elektroniczny klient faxu, ktory pozwoli
na pobieranie faxów do systemu.

`**#innowacja** <https://laboratoriumee.hackpad.com/ep/search/?q=%23innowacja&via=MLQHmZI3w8y>`__
**Integracja z usługami firm obsługujących przesyłki** Możliwość
głębokiej integracji w zakresie przekazywania danych o przesyłkach -
odbiór i wysyłka.

**2. Skład chronologiczny**
===========================

Skład chronologiczny to miejsce gdzie trafiają zeskanowane przesyłki
przychodzące w formie fizycznej do urzędu. Po wykonaniu skanu,
wpływ/przesyłka przychodząca otrzymuje dwa numery - rejestru przesyłek
przychodzących (najczęściej skrót RPW) oraz numer w składzie
chronologicznym. Następnie umieszczana jest razem z inną korespondencją
w odpowiednim pomieszczeniu zwanym Składem Chronologicznym. Dla
odróżnienia od systemu tradycyjnego, przesyłki w SC są przechowywane w
kolejności wpływu, a nie ze względu na powiązania tematyczne/sprawy.

**Korespondencja wychodząca**
=============================

Obsługa analogicznie do korespondencji przychodzącej. Korespondencja
wychodząca może być inicjowana przez wszystkich pracowników. Fizyczna
wysyłka realizowana przez Kancelarię. Również wszyscy pracownicy
inicjujący korespondencję wychodzącą powinni mieć możliwość wydrukowania
niezbędnych etykiet lub nadruku kopert.

**4. Wprowadzenie struktury organizacyjnej instytucji, 5. Nadawanie ról i uprawnień użytkowników, 8. Konto instytucji**
=======================================================================================================================

Ta część systemu jest jedną z tych, w których zajdzie największa zmiana.
Obecnie konfiguracja odbywa się per konkretny instalowany system. Oprócz
Active Directory będącego zbiorem informacji o użytkownikach wszystkie
pozostałe ustawienia są wprowadzane za każdym razem osobno, a zmiana w
jednej aplikacji nie powoduje zmian w innych.

W aplikacje.gov.pl zmieniamy filozofię konfiguracji oprogramowania dla
administracji. Jedno konto instytucji ma być miejscem z którego
zarządzamy danymi organizacji, listą pracowników, strukturą
organizacyjną, rolami i uprawnieniami zarówno do konkretnych aplikacji
jak i w ich ramach.

Te elementy będą początkiem user journey dla każdej instytucji
dołączającej do aplikacje.gov.pl

-  Rejestracja konta instytucji i osoby inicjującej proces (nie mamy de
   facto konta instytucji tylko konta osób uprawnionych do
   reprezentacji.
-  Pobranie danych na podstawie numeru REGON
-  Założenie konta
-  Podgląd aplikacji na platformie
-  Uzupełnienie listy pracowników
-  Uzupełnienie struktury organizacyjnej
-  Uzupełnienie ról i uprawnień
-  Rozpoczęcie pracy z aplikacjami
-  Dodatkowo aplikacja EZD wymagać będzie wgrania JRWA - Jednolitego
   Rzeczowego Wykazu Akt

`**#** <https://laboratoriumee.hackpad.com/ep/search/?q=%23Innowacja&via=MLQHmZI3w8y>`__\ **innowacja
Jedno konto instytucji na platformie dla wielu aplikacji (w tym EZD)**
**#innowacja Na podstawie listy pracowników generowana jest struktura
organizacyjna** **#innowacja Możliwość zarządzania rolami i
uprawnieniami globalnie dla wszystkich używanych aplikacji (w tym EZD)**

**Zastępstwa, nieobecności, delegowanie zadań**
===============================================

Ten moduł służy do czasowej (krótko i długoterminowej) zmiany ról i
uprawnień dla poszczególnych użytkowników. Istotne jest uwzględnie dwoch
trybów - zaplanowanego i nagłego. Moduł powinien umożliwiać szybką
reakcję w wyniku otrzymania informacji o nagłej nieobecności.

**7. Logowanie użytkownika**
============================

Ten moduł ma służyć weryfikacji tożsamości użytkowników. Powinien być
zintegrowany z przyjętymi w organizacjami metodami logowania - np. z
wykorzystaniem karty z chipem, tokenów, metod biometrycznych

\*\*\*\* **#innowacja Ekran i metody logowania są takie same dla
wszystkich aplikacji (w tym EZD), a przełączanie między nimi na
platformie aplikacje.gov.pl nie wymaga od użytkowników dodatkowych
akcji**

**10. Dekretacja**
==================

Dekretacja to czynność dodania do obiektu (np. wpływu korespondencji
przychodzącej) informacji na temat osoby wyznaczonej do zajęcia się nim,
najczęściej z informacją na temat dodatkowych zadań w formie instrukcji,
np. “Proszę o załatwienie”. Istotne jest to, że dekretacja przebiega w
hierarchii co do zasady z góry na dół, a instrukcje mają najczęściej
formę kilku wymiennych schematów. Z perspektywy użytkowników moduł
dekretacji powinien pozwalać ustalać własne szablony/schematy
dekretacji. Należy rozważyć wyświetlanie podpowiedzi na podstawie
wcześniejszych działań użytkowników w zakresie dekretacji. W module
powinno znajdować się podsumowanie wszystkich dokonanych dekretacji,
natomiast w podglądzie bieżącym powinna być możliwość wybrania
dekretacji dzisiaj/w ostatnim tygodniu/ w ostatnim miesiącu. Powinny być
również możliwe widoki w podziale na pracowników, na których
zadekretowaliśmy. Dekretacja musi być dobrze rozwiązana w wersji
mobilnej - brak możliwości jej wykonywania blokuje często prace.

**#innowacja Udostępniamy moduł do szybkiej dekretacji, który pozwala
rozdzielać dokumentację, wraz z dekretacją, pomiędzy podległych
pracowników gdziekolwiek jesteś**

możliwość ustalenia szablonów dekretacji podgląd dokumentów benchmark
mechanizmu - Tinder

**9. Obsługa spraw**
====================

**#innowacja Dostarczamy wewnętrzny edytor tekstu, który pozwala
współpracować nad projektami pism. Edycja tekstu, komentarze, wkłady -
wszystko w jednym miejscu**

Benchmark - Paper, Hackpad, Google Docs

**#innowacja Dzięki wymaganiu dokładniejszego określenia relacji
pomiędzy dokumentami aplikacje.gov.pl - EZD pozwala zorientować się w
zależnościach pomiędzy obiektami w sprawie**

Np. obecnie w EZD PUW wiemy, że obiekty mają jakiś rodzaj relacji, ale
system nie odnotowuje dokładniejszych informacji.

**Perspektywa osoby prowadzącej sprawę**

Moduł powinien umożliwiać:

-  podgląd obecnie prowadzonych spraw, terminów ich załatwienia, spraw z
   przekroczonymi terminami
-  przyjęcie do realizacji zadekretowanej korespondencji
-  utworzenie nowej sprawy na podstawie obiektu w postaci korespondencji
-  utworzenie nowej sprawy bez obiektu w postaci korespondencji
-  obowiązkowo wybranie kategorii JRWA - jednolitego rzeczowego wykazu
   akt oraz kategorii archiwalnej
-  prowadzenie sprawy - tworzenie pism (m.in. na podstawie wzorów),
   dołączanie załączników
-  przekazanie innym osobom prośby o wkład do tworzonego pisma (podobnie
   do trybu sugerowania w edycji dokumentów Google) - realizowane w
   ramach wbudowanego edytora tekstu
-  możliwość przekazania gotowego pisma do akceptacji elektronicznej
   i/lub podpisu - wybór ścieżki z listy procesów, jej modyfikacja lub
   stworzenie własnej od nowa (miniproces wyklikiwany tak samo jak
   procesy w instytucji)
-  podgląd czy pismo jest akceptowane/podpisywane na kolejnych etapach
   procesu,
-  otrzymywanie uwag do zmian w piśmie od osób z dalszego etapu ścieżki
-  otrzymywanie powiadomień o ewentualnych zmianach ścieżki dokonanych
   na wyższym poziomie hierarchii
-  otrzymywanie powiadomień o gotowości pisma do wysyłki (jeżeli nie
   jest to ścieżka elektroniczna)
-  możliwość tworzenia notatek wewnętrznych
-  możliwość tworzenia notatek widocznych tylko i wyłącznie dla autora
-  możliwość podglądu spraw prowadzonych i/lub załatwionych w
   przeszłości

**Perspektywa osoby nieprowadzącej sprawy**

-  możliwość otrzymywania i odpowiadania na prośby o wkład do pisma
-  możliwość dodawania uwag do pisma
-  możliwość zmiany ścieżki akceptacji następującej po mojej
   akceptacji/podpisie (z dopisaniem komentarza uzasadniającego zmianę)
-  możliwość podglądu wkładów do pism wykonanych w przeszłości

**Perspektywa podglądu pojedynczej sprawy**

-  podgląd najważniejszych informacji o sprawie, tj. nazwa sprawy, numer
   sprawy, osoba prowadząca sprawę, obiekty w sprawie, strony w sprawie,
   powiązania pomiędzy obiektami (wynikanie - obecnie w systemie EZD PUW
   tego brakuje), wszystkie daty w sprawie (założenia, załatwienia,
   terminy wynikające z przepisów)
-  możliwość wejścia w szczegóły każdego obiektu w sprawie oraz
   obejrzenia jego elektronicznego obrazu
-  możliwość szybkiego przełączania pomiędzy różnymi widokami obiektów w
   sprawie - chronologiczny, typy obiektów, osoby tworzące obiekty,

**11. Pulpit użytkownika (lista widoków może ulec zmianie)**
============================================================

\*\*\*\*W tym miejscu użytkownicy będą widzieli najważniejsze informacje
w zależności od zajmowanego przez siebie w hierarchii miejsca

Kierownictwo instytucji - podsumowanie stanu instytucji, sprawy do
podpisu, śledzenie wybranych spraw (np. ze względu na ważność),
monitoring terminowości załatwiania spraw, statystyki dla instytucji

Kadra zarządzająca - podsumowanie najważniejszych informacji o
instytucji, śledzenie wybranych spraw w ramach zarządzanej komórki
organizacyjnej (np. ze względu na ważność), monitoring terminowości
załatwiania spraw w ramach zarządzanej komórki organizacyjnej,
statystyki dla zarządzaniej komórki organizacyjnej.

Osoby prowadzące sprawy - podsumowanie najważniejszych informacji o
komórce organizaycjnej, której są częścią, śledzenie prowadzonych przez
siebie spraw (np. ze względu na ważnośc), monitroing terminowości
prowadzonych przez siebie spraw, statystyki indywidualne

Osoby pracujące w kancelarii/punktach kancelaryjnych/sekretariatach -
podgląd i obsługa korespondencji przychodzącej, możliwość podglądu
wpływów zarejestrowanych w przeszłości, możliwość podglądu wpływów z
uwzględnieniem podziału na źródła wpływu, dzień/godzinę wpływu

Osoby pracujące w Archiwum Zakładowym - zgodnie z opisem modułu

**12. Pulpit instytucji**
=========================

Zbiorowy widok stanu instytucji - wyciąg ogólny ze statystyk dotyczących
liczby załatwianych spraw, terminowości instytucji, liczby prowadzonych
spraw per komórka organizacyjna (ranking)

**14. Statystyki**
==================

Moduł zbierający statystyki z systemu w sposób automatyczny. Zarządzanie
w ramach modułu powinno dawać możliwość edycji źródeł informacji do
zestawień statytstycznych. Oprócz tego modul statystyk powinien dawać
możliwość generowania dowolnych zestawień/raportów oraz ich
eksportowania. Uprawnienia do podglądu statystyk powinny być określane w
module ról i uprawnień.

**15. Rejestry podstawowe (skonfigurowane), 16. Rejestry - generowanie**
========================================================================

W tym miejscu systemu powinniśmy mieć możliwość zarządzania prowadzonymi
w instytucji rejestrami. Rejestry powinny dzielić się na dynamiczne i
statyczne. Tak jak w przypadku statytystyk, uprawnienia do podglądu i
zmiany rejestrów powinny być określane w module ról i uprawnień.

W przypadku rejestrów dynamicznych, czyli samogenerujących się na
podstawie danych systemowych, powinniśmy mieć możliwość określenia zasad
kiedy i jakie dane zyskują formę wpisu do rejestru.

W przypadku rejestrów statycznych, czyli powstających w wyniku dokonania
wpisu przez uprawnioną osobę, powinniśmy mieć możliwość określenia pól
wchodzących w skład wpisu rejestrowego.

**17. Obsługa skarg i wniosków**
================================

Obsługa skarg i wniosków to szczególna odmiana procesu prowadzonego w
ramach obsługi spraw. Jako osobny moduł powinna wyświetlać się jedynie
osobom zaangażowanym w jego obsłużenie. Zasadnicze różnice to:

-  wskazanie osób w instytucji wyznaczonych do załatwianie skarg i
   wniosków - to do nich będzie wpływać korespondencja i to tylko one
   powinny mieć do niej dostęp + osoba kierującą instytucją
-  skarga i wniosek będą osobnym typem procesu uruchamianego w systemie,
   którego zasady można określać w module 24. Procesowość.

**18. Archiwum Zakładowe**
==========================

\*\*\*\*\*\*#innowacja Możliwość przekazania wielu spisów
zdawczo-odbiorczych w ramach jednego wniosku do Archiwum Państwowego\ **
**\ #innowacja Walidator spisu zdawczo-odbiorczego jest fragmentem
back-endu EZD bez potrzeby przeprowadzania walidacji samodzielnie z
wykorzystaniem zewnętrznych narzędzi\ ** **\ #innowacja Komunikacja z
systemem Archiwum Dokumentów Elektronicznych prowadzona jest w ramach
systemu\ ** Przesłanie wniosku, śledzenie jego statusu, informacja o
poprawkach do przesłanych spisów zdawczo-odbiorczych są realizowane w
systemie EZD **\ #innowacja Po zatwierdzeniu spisu zdawczo-odbiorczego
powiązana z nim paczka archiwalna przekazywana jest automatycznie\*\*

Archiwum Zakładowe to moduł pozwalający na zarządzanie dokumentacją,
która została przekazana do AZ. Decyzja o tym jaką kategorię ma sprawa i
w jaki sposób będzie archiwizowana podejmuje osoba prowadząca sprawę. W
tym module spotykają się następujące procesy:

-  Po upływie określonego czasu (najczęściej 3 lata) osoba prowadząca
   sprawę musi dostać powiadomienie, że część jej spraw należy przekazać
   do Archiwum Zakładowego - pytanie czy to moduł Archiwum Zakładowe
   powinien przypominać o tej akcji do podjęcia na podstawie kategorii
   JRWA
-  Następnie wybrane sprawy przekazywane są do Archiwum Zakładowego. Dla
   osoby prowadzącej sprawę staną się one zamknięte do edycji. Od tego
   momentu edycji mogą dokonywać jedynie osoby wyznaczone do zajmowania
   się Archiwum Zakładowym.
-  Moduł powinien umożliwiać obróbkę i uzupełnianie metadanych w
   przekazanych sprawach
-  Po upływie 10 lat od przekazania do Archiwum Zakładowego, na
   podstawie kategorii archiwalnej, część spraw zostaje przekazana do
   Archiwum Państwowego. Moduł AZ powinien pozwolić na obsługę tego
   procesu, na który składają się:
-  stworzenie spisu zdawczo-odbiorczego,
-  stworzenie wniosku o przekazanie X spisów zdawczo-odbiorczych,
-  przesłanie wniosku do właściwego Archiwum Państwowego (podpowiedź na
   podstawie lokalizacji instytucji lub jej specjalnego charakteru - np.
   instytucja centralna),
-  obsłużenie ewentualnych uwag do spisów zdawczo-odbiorczych,
-  poinformowanie o zaakceptowaniu spisu zdawczo-odbiorczego
-  W przypadku dokumentacji papierowej moduł powinien obsługiwać
   wypożyczenia fizycznych kopii dokumentów zarówno po stronie
   pracowników instytucji, jak i pracowników Archiwum Zakładowego

**19. Paczka migracyjna**
=========================

Paczka migracyjna jest częścią systemu, która wpływa na projektowanie
jedynie (i aż) w zakresie zbieranych w systemie metadanych. W związku z
tym wykaz metadanych/pól będzie zawsze powiązany z aktualnym stanem
wiedzy na temat paczki migracyjnej.

**24. Procesowość**
===================

Ten moduł pozwala (uwzględniając aktualną strukturę organizacyjną)
ustawiać procesy w instytucji. Procesy powinny być możliwe do podglądu w
BPMN. Jednak sam interfejs tworzenia procesów należy dostosować do
oczekiwań użytkowników administracji publicznej. Być może forma pytań o
relacje będzie lepszym rozwiązaniem na etapie konfiguracji.

**#innowacja Generator procesów wyłapuje potencjalne pętle w procesach
już na etapie ich wprowadzania**

**26. Baza adresatów**
======================

Baza adresatów to część systemu, która jest wspólna na pewno dla
wszystkich użytkowników w ramach jednej instytucji-instancji. System
powinien wymuszać korzystanie w pierwszej kolejności z danych w bazie
adresatów. W przypadku braku poprawności zachęcać do ich aktualizacji
(umożliwiając zamieszczenie wewnętrznego komentarza na temat dokonanej
zmiany). Własne bazy adresatów instytucji powinny być ograniczone do
minimum, korzystając maksymalnie z ogólnodostępnych baz takich jak np.
REGON.

**#innowacja System stosuje hierarchię źródeł danych adresowych co ma
prowadzić do pozyskiwania najaktualniejszych danych, które nie dublują
istniejących baz**

**27. Metadane, słowniki, wzory**
=================================

**#innowacja Geotagowanie spraw i obiektów**

Geotagowanie będziem możliwe w miejscu

::

    InnyTemat ::= inne klucz Klucz klucz wartosc WartośćKlucza wartosc inne 

Długość i szerokość geograficzna to będą 2 pola *InnyTemat*

--------------

Zestaw i formaty podstawowych metadanych w systemie będzie określany z
góry wymogami paczki migracyjnej. Jednak musimy założyć sytuację, gdy
instytucje będą chciały dodawać dodatkowe metadane. W tym module musi
być miejsce na określenie ich listy, jakich obiektów w systemie dotyczą,
jaki mają format.

Kolejny temat to słowniki w ramach instytucji (np. teleadresowy, kodow
pocztowych). Minimum jest funkcjonowanie wspólnego słownika w ramach
jednej instytucji. Powinniśmy założyć również możliwość skorzystania ze
słownika współdzielonego przez inne instytucje lub będącego
słownikiem/bazą centralną (np. REGON).

Wzory dokumentów to kolejny ważny element zapewnienia spójności w ramach
urzędu, ale także oszczędzenia pracownikom i pracowniczkom sprawdzania
za każdym razem jaki jest aktualnie obowiązujący format wysyłanych pism.
Z drugiej strony mamy Centralne Repozytorium Wzorów, w ramach którego
umieszczane są wzory pism przez różne instytucje. Jako system EZD
powinniśmy zarówno dać możliwość stworzenia dowolnego wzoru jak i jego
zaimportowania (np. z CRW). Podgląd i wykorzystanie wzorów dokumentów
powinny być możliwe z poziomu modułu 11. Pulpit użytkownika

**28. Integracje**
==================

**#innowacje Zarządzanie wszystkimi integracjami instancji w ramach
platformy**

Ten moduł powinien pozwolić nam na podgląd wszystkich obecnych
integracji naszej instancji oraz ich status. Coś na kształt podglądu
stanu chmury AWS
(`https://status.aws.amazon.com <https://status.aws.amazon.com/>`__)
