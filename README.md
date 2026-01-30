# Analiza Wypraw na Ośmiotysięczniki (1900-2020) 

Projekt Eksploracyjnej Analizy Danych (EDA) badający czynniki sukcesu i ryzyka w himalaizmie. Analiza obejmuje ponad 100 lat historii wypraw na 8 najwyższych szczytów Nepalu.

## Cel i Metodyka
Celem była weryfikacja hipotez dotyczących wpływu wieku, płci i tlenu na zdobycie szczytu.
* **Technologie:** R, R Markdown, Tidyverse (dplyr, ggplot2).
* **Statystyka:** Testy nieparametryczne (Wilcoxon), test niezależności cech (Chi-squared), testy normalności (Jarque-Bera).

## Najciekawsze Wnioski
1. **Tlen to klucz:** Wykazano silną, dodatnią zależność między użyciem tlenu a sukcesem.
2. **Szerpowie a Wspinacze:** Testy statystyczne potwierdziły, że Szerpowie są grupą istotnie młodszą od zachodnich wspinaczy.
3. **Polska vs Reszta świata:** Mimo mniejszej liczby wypraw ogółem, Polacy dominują w historii pierwszych wejść zimowych (6 z 8 badanych szczytów).

## Pliki w repozytorium
* `Analiza_Himalaizm_ADAM_ŁUKASIK.Rmd` - Główny kod projektu.
* `Analiza_Himalaizm_ADAM_ŁUKASIK.html` - Raport końcowy.
* `members.csv` - Dane (Himalayan Database).

