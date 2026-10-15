# Kontrola techniczna (15.10.2026)

Środowisko: Chromium w aplikacji desktopowej, serwer HTTP na localhost; widok desktopowy i 375×812 px.

## Potwierdzone
- Składnia JS poprawna (`node --check`); brak błędów w konsoli po załadowaniu.
- Brak zasobów zewnętrznych poza trzema odnośnikami „Otwórz źródło” (otwierane w nowej karcie); brak `fetch`/XHR/analityki; brak zduplikowanych `id`.
- 30 scen (14 + 8 + 8), 5 zagadnień, 15 tez, 10 kart opracowań, 25 ćwiczeń; dziewięć widoków się przełącza.
- Filtry Atlasu działają (utwór, zagadnienie, stan): „Ad leones!” = 8 scen, P4 = 8 scen, „Przeczytane” = 1 po zaznaczeniu.
- Notatka, zaznaczenie „przeczytana”, zakładka, treść wypracowania, motyw i ostatni widok przetrwały przeładowanie strony (`localStorage`).
- Głęboki odnośnik `#ST13` po przeładowaniu otwiera Atlas i rozwija kartę.
- Wyszukiwanie („papier” → 8 wyników) przenosi do właściwej karty.
- Oznaczenie „gotowa do oceny” zapisuje wersję pierwotną; wczytanie pliku z oceną (symulowane) wyświetla status, uzasadnienie i porównanie wersji.
- Brak poziomego przewijania w żadnym z dziewięciu widoków na 375 px.

## Niesprawdzone
- Faktyczne pobranie plików (prace, kopia bezpieczeństwa, ocena) i ich wczytanie z dysku; testowano tylko dane w pamięci przeglądarki.
- Test fizycznego zamknięcia i ponownego otwarcia przeglądarki na docelowym komputerze uczennicy (test przeładowania strony jest tylko jego namiastką).
- Wygląd trybu jasnego i druk na fizycznej drukarce; czytnik ekranu.
- Publiczny URL (wymaga włączenia GitHub Pages po wypchnięciu repozytorium).

## Kontrola treści (rygor źródłowy)
- Wszystkie 30 cytatów scen sprawdzono automatycznie jako dosłowne fragmenty tekstu pobranego z Wikiźródeł (wyd. Pini 1934). Cytaty w polach „Za”, „Przeciw” i w streszczeniach scen nie były sprawdzane maszynowo.
- Streszczenia tez Rzepczyńskiego, Kąckiej i Dambek-Giallelis oparte na pełnych tekstach artykułów (Kącka i Dambek-Giallelis w wersji angielskiej). Strony polskich wersji nie były sprawdzane.
- Adamiec, Dąbrowicz: tylko relacje z drugiej ręki (oznaczone [B]); Bachtin, Skalińska, Maciejewski, Łapiński, Łubieński, Rzepczyński 1996 (książka): brak lektury ([N]).
- „Bransoletka”: w czytanym tekście nie ma nazwy miasta ani kraju; zapisane jako pytanie otwarte.
- Interpretacje scen i tez oznaczone [I]/[H] są propozycjami do obrony, nie ustaleniami.

## Do decyzji właściciela
- Licencja treści.
- Czy repozytorium ma być publiczne: strona zawiera interpretacje i ćwiczenia, a nie zawiera danych uczennicy (brak imion; podpis wypracowania jest polem opcjonalnym, zapisywanym lokalnie).
- Wydanie podstawowe: Wikiźródła (Pini 1934) czy wydania wskazane przez Komitet.
