# Mirror https://sejm.gov.pl

## Opis
To repozytorium zawiera dane mirrorowane z oficjalnego API Sejmu Rzeczypospolitej Polskiej (dostępnego pod adresem [api.sejm.gov.pl](https://api.sejm.gov.pl)). Celem projektu jest zapewnienie transparentnego dostępu do informacji publicznych, wraz z możliwością przejrzystego śledzenia dokonywanych aktualizacji.

## Zastrzeżenie prawne (Disclaimer)

### 1. Informacja publiczna
Dane przechowywane w tym repozytorium pochodzą z oficjalnego API Sejmu RP i są uznawane za **informację publiczną** zgodnie z Ustawą z dnia 6 września 2001 r. o dostępie do informacji publicznej (Dz.U. 2001 nr 112 poz. 1198 z późn. zm.). Zgodnie z art. 61 Konstytucji RP, każdy ma prawo do uzyskiwania informacji o działalności organów władzy publicznej, w tym do pobierania i rozpowszechniania takich danych.

### 2. Zgodność z prawem
- **Prawa autorskie**: Dokumenty urzędowe publikowane przez Sejm RP, takie jak projekty ustaw czy stenogramy, nie podlegają ochronie prawa autorskiego na podstawie art. 4 Ustawy z dnia 4 lutego 1994 r. o prawie autorskim i prawach pokrewnych (Dz.U. 1994 nr 24 poz. 83 z późn. zm.). Jednakże niektóre materiały, takie jak zdjęcia czy grafiki, mogą być objęte prawami autorskimi osób trzecich. Użytkownicy repozytorium są odpowiedzialni za weryfikację statusu prawnego takich materiałów przed ich dalszym wykorzystaniem.
- **Dane osobowe**: Część danych (np. informacje o posłach) może zawierać dane osobowe w rozumieniu Rozporządzenia Parlamentu Europejskiego i Rady (UE) 2016/679 (RODO). Dane te są przetwarzane w interesie publicznym (art. 6 ust. 1 lit. e RODO) w celu zapewnienia transparentności działań Sejmu RP. Użytkownicy repozytorium są zobowiązani do przestrzegania przepisów RODO przy dalszym przetwarzaniu tych danych.
- **Warunki korzystania z API**: Mirrorowanie danych odbywa się zgodnie z zasadami użytkowania API Sejmu RP. W przypadku jakichkolwiek zmian w regulaminie API lub żądań Kancelarii Sejmu dotyczących usunięcia określonych danych, mechanizm mirrorowania będzie aktualizoway do maks. 30 dni w celu zapewnienia zgodności.

### 3. Aktualizacja danych
Repozytorium jest automatycznie aktualizowane **co 30 minut**, aby odzwierciedlać najnowsze dane dostępne w API Sejmu RP. Proces aktualizacji obejmuje zarówno dodawanie nowych dokumentów, jak i usuwanie materiałów, które zostały wycofane z API na wniosek Kancelarii Sejmu lub innych uprawnionych podmiotów (np. w przypadku próśb o usunięcie danych zgodnie z prawem). Dzięki temu repozytorium pozostaje zgodne z zamysłem Kancelarii Sejmu dotyczącym publicznego udostępniania danych.

### 4. Odpowiedzialność
- Dane w repozytorium są dostarczane "tak jak są" (as-is), bez żadnych gwarancji co do ich kompletności, dokładności czy aktualności.
- Właściciel repozytorium nie ponosi odpowiedzialności za jakiekolwiek szkody wynikające z wykorzystania danych, w tym za naruszenia praw osób trzecich.
- Użytkownicy repozytorium są odpowiedzialni za przestrzeganie obowiązujących przepisów prawa podczas korzystania z danych, w tym przepisów dotyczących ochrony danych osobowych i praw autorskich.

### 5. Kontakt
W przypadku pytań dotyczących repozytorium lub danych w nim zawartych, prosimy o kontakt z administratorem repozytorium przez e-mail dzikstarbiznes@gmail.com. W sprawach związanych z oryginalnymi danymi prosimy kontaktować się z Biurem Komunikacji Społecznej Kancelarii Sejmu RP ([kontakt@sejm.gov.pl](mailto:kontakt@sejm.gov.pl)).

### 6. Licencja
Dane mirrorowane w tym repozytorium, jako informacje publiczne, mogą być swobodnie wykorzystywane, o ile nie narusza to przepisów prawa. W przypadku materiałów objętych prawami autorskimi osób trzecich, użytkownicy są zobowiązani do uzyskania odpowiednich zgód przed ich użyciem.

## Jak korzystać
- Dane są dostępne w formacie JSON w folderach odpowiadających kategoriom (np. `ustawy`, `posłowie`, `stenogramy`) oraz w formach publikacyjncych (np. `.pdf`/`.docs` dla mirrorowanych ustaw).
- Metadane każdego pliku zawierają informacje o źródle i dacie pobrania.
- Zachęcamy do zapoznania się z dokumentacją API Sejmu ([api.sejm.gov.pl](https://api.sejm.gov.pl)) w celu uzyskania szczegółowych informacji o strukturze danych.

## Uwagi
Projekt ma na celu wspieranie transparentności i dostępu do informacji publicznych. Jeśli masz sugestie dotyczące ulepszenia repozytorium, zapraszamy do zgłaszania ich przez system Issues na GitHubie.
