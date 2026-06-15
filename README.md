# Etyczny Kompilator AI — wersja 2.5

Autorskie narzędzie edukacyjne do projektowania, testowania i debugowania priorytetowego modelu regułowego podczas lekcji informatyki.

## Aplikacja online

https://ethicsandschool-lgtm.github.io/etyczny-kompilator-ai/

## Najważniejsze funkcje

- **S0 – stałe zabezpieczenie nr 0** (od ang. *Safeguard 0*): litera S oznacza zabezpieczenie, a cyfra 0 wskazuje, że warstwa działa przed regułami R1–R6 i nie podlega zmianie ani przesuwaniu w hierarchii;
- S0 odrzuca cechy osobowe jako kryterium wartościowania życia;
- wybór trzech spośród sześciu reguł decyzyjnych;
- hierarchia priorytetów i generowanie pseudokodu;
- cztery autorskie przypadki testowe;
- ślad decyzyjny, konflikty i chronione nierozstrzygnięcie;
- zapis V1, debugowanie i utworzenie V2;
- porównanie osobno: wyniku, reguły rozstrzygającej, konfliktów i działania S0;
- raport ucznia bez elementów nawigacyjnych i komunikatu trybu debugowania;
- pełny pseudokod V1 i V2 jest osadzany w raporcie jako stały, zawsze widoczny blok, dzięki czemu pojawia się także w pliku PDF;
- opcjonalny prompt do audytu generatywnej AI, domyślnie niedołączany do raportu.
- raport odtwarza pseudokod V1 i V2 z aktualnych definicji reguł, dzięki czemu nie zachowuje nieaktualnego opisu po aktualizacji aplikacji;
- aplikacja automatycznie odrzuca stan sesji zapisany przez starszą wersję;
- komunikat dla przypadków bez cech osobowych ma poprawne brzmienie: „W tym przypadku nie występują cechy osobowe wymagające odrzucenia.”;

## Uruchomienie lokalne

Pobierz `index.html` i otwórz go w aktualnej wersji Chrome, Edge, Firefox lub Safari. Aplikacja nie wymaga serwera, bazy danych ani logowania.

## Prywatność

Przetwarzanie odbywa się lokalnie w przeglądarce. Aplikacja nie zawiera reklam, trackerów ani zewnętrznych bibliotek i nie przesyła danych ucznia na serwer.

## Autor projektu

Autor koncepcji, specyfikacji funkcjonalnej i projektu dydaktycznego: **Łukasz Szymański**.

W technicznej implementacji wykorzystano generatywną AI jako narzędzie wspomagające przełożenie autorskiej specyfikacji na kod HTML, CSS i JavaScript. Ostateczna logika, testy, decyzje metodyczne, weryfikacja oraz publikacja projektu pozostają pod kontrolą autora.

## Prawa

Repozytorium nie jest objęte licencją open source. Wszelkie prawa zastrzeżone. Szczegóły: `PRAWA_AUTORSKIE.txt`.
