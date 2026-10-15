# Tajemnica lorda Singelworth — zeszyt olimpijski (OLiJP 2026/2027)

Samodzielna strona do pracy nad nowelą Cypriana Norwida *Tajemnica lorda Singelworth* w kontekście *Bransoletki* i *Ad leones!*: 30 scen, 5 zagadnień, 15 tez z argumentami i kontrargumentami, 25 ćwiczeń, 10 kart opracowań, słownik, edytor wypracowania, notatki, zakładki, wyszukiwarka i tryb jasny/ciemny.

Strona to **jeden plik** [`index.html`](index.html), bez frameworków, bez zewnętrznych skryptów i fontów, bez śledzenia. Działa offline: wystarczy otworzyć plik w przeglądarce.

## Jak korzystać
- **Online:** po włączeniu GitHub Pages (Settings → Pages → Source: *GitHub Actions*) strona będzie pod adresem `https://<konto>.github.io/<repozytorium>/`.
- **Offline:** pobierz `index.html` i otwórz go w przeglądarce.

## Ważne
- **Notatki, zakładki, postęp i wypracowanie są zapisywane tylko w przeglądarce** (`localStorage`). Nie ma kont ani synchronizacji. Wyczyszczenie danych przeglądarki je usuwa. W zakładce *Zeszyt* jest kopia bezpieczeństwa.
- **Przekazywanie pracy nauczycielowi:** w zakładce *Wypracowanie* uczennica pobiera plik JSON i wysyła go sama. Nauczyciel wczytuje go w osobnym panelu (`nauczyciel.html`), wystawia ocenę i odsyła plik, który uczennica wczytuje na stronie. Panel nauczyciela jest **celowo poza tym repozytorium**.
- **Podstawa tekstowa:** cytaty i lokalizacje pochodzą z wydania na Wikiźródłach (*Dzieła Cyprjana Norwida*, wyd. Pini, Warszawa 1934, s. 450–453, 465–472, 473–478). Komitet OLiJP wskazuje inne wydania (Gomulicki; Rzońca i Samsel), więc pisownia i numeracja stron mogą się różnić. Lokalizuj przez rozdział i fragment.
- **Opracowania:** przeczytano i opisano trzy artykuły (Rzepczyński 1996, Kącka 2020, Dambek-Giallelis 2017; dwa ostatnie w wersji angielskiej czasopisma). Pozostałe pozycje z listy Komitetu mają status [B] lub [N], a odwołujące się do nich tezy są hipotezami [H].
- Strona nie zawiera pełnego tekstu nowel ani cudzych skanów; cytaty są krótkie.

## Struktura
| Plik | Opis |
|---|---|
| `index.html` | cała strona (HTML + CSS + JS + treść) |
| `.github/workflows/pages.yml` | publikacja na GitHub Pages |
| `docs/TESTY.md` | wyniki kontroli technicznej |

## Licencja
Nie wybrano jeszcze licencji — **do decyzji autora/właściciela**. Bez pliku `LICENSE` obowiązują domyślnie wszelkie prawa zastrzeżone.
