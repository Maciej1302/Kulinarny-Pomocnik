# Kulinarny-Pomocnik
Kulinarny pomocnik to aplikacja mobilna napisana przy pomocy języka Python oraz frameworka do aplikacji mobilnych Kivy, która dobiera przepisy kuchenne na podstawie podanych przez użytkownika składników. Motywacją aplikacji jest codzienny problem „co mogę dziś zjeść” z którym boryka się spora część społeczeństwa – na pewno każdy choć raz nie miał pomysłu na przysłowiowy obiad mimo to, że miał mnóstwo różnych produktów. Kulinarny pomocnik rozwiązuje ten problem – dobiera odpowiednie przepisy na podstawie podanych składników i wybranej kaloryczności posiłku. 

Funkcjonalność: 
Podstawową funkcjonalnością aplikacji (dostępną w zakładce dla gości) jest generacja przepisów kuchennych w zależności od podanych produktów i zadanej kaloryczności  - jest to sztandarowa funkcjonalność programu. Oprócz wyżej wspomnianej podstawowej funkcjonalności użytkownik aplikacji może zarejestrować się w aplikacji podając imię, nazwisko, maila, hasło i datę urodzenia. W czasie rejestracji walidacji podlegają podane dane, walidacja imienia – czy nie zawiera liter i zaczyna się dużą literą, nazwiska – tak samo jak imienia, maila – standardowa walidacja e-mail, hasła – min. 8 znaków w tym min. 1 duża litera, min. 1 mała litera, min. 1 liczba, min. 1 znak specjalny, walidacja daty urodzenia – data musi być podana w standardzie ISO 8601 (YYYY-MM-DD) po udanej rejestracji użytkownik posiada konto w aplikacji. Posiadacz konta poza podstawową funkcjonalnością zyskuje dostęp do wielu dodatkowych funkcji, między innymi możliwość zapisywania ulubionych przepisów i wybranych przepisów. Zalogowany użytkownik ma możliwość zmiany danych podanych przy rejestracji, uzyskuje dostęp do swoich ulubionych przepisów oraz do analizy w której skład wchodzą histogramy z najczęściej wybieranymi przepisami, najczęściej stosowanymi składnikami, wykresy zjedzonych kalorii w danych dniach/miesiącach, dostępna jest również analiza finansowa, która przybliża użytkownikowi kwoty wydane na jedzenie w poszczególnych dniach/miesiącach/latach. Oprócz wyżej wspomnianych funkcjonalności w skład dodatkowych funkcji, które użytkownik uzyskuje po rejestracji aplikacja oferuje również możliwość znajdywania i dodawania znajomych – po dodaniu znajomego możliwy jest wgląd w ulubione przepisy znajomego (o ile dany znajomy wyraził zgodę na udostępnienie swoich przepisów – użytkownik może zmieniać to w swoich ustawieniach prywatności), kolejną funkcjonalnością dostępną z poziomu zalogowanego użytkownika jest możliwość zmiany języka, Dark Mode, sekcja HELP, ocenienie aplikacji czy polecenie aplikacji znajomym (za polecanie aplikacji przewidziany jest benefit w postaci braku reklam) jak i również sekcja „About App” gdzie użytkownik może dowiedzieć się o aktualnej wersji aplikacji czy planowanych aktualizacjach. Warto dodać, że przy każdym logowaniu użytkownika do aplikacji generowany jest unikalny token sesji użytkownika, przez który w łatwy sposób może on uzyskać pomoc w zakładnie „HELP”. Oprócz panelu użytkowników i gości dostępny jest panel dla administratorów, którzy mogą zarządzać kontami użytkowników (KRUD). Aplikacja będzie miała również napisane testy unittest.

Kulinarny pomocnik jest aplikacją przeznaczoną na IOS oraz Android. Aplikacja jest w ciągle rozbudowywana i aktualizowana, planowany termin ukończenia aplikacji wraz z jej wszystkimi funkcjonalnościami to koniec lutego 2024r. 
