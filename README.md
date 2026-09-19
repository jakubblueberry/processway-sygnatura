# ProcessWay, obrazki do podpisu mailowego

Pięć plików PNG, których używa podpis mailowy ProcessWay FinRecover Sp. z o.o.
Repozytorium jest publiczne, bo obrazki muszą być dostępne bez logowania: program pocztowy
odbiorcy pobiera je sam, w jego imieniu, bez żadnych uprawnień.

## Po co to istnieje

Gmail w przeglądarce **nie wyświetla obrazków wklejonych bezpośrednio w kod wiadomości**
(tak zwane `data:URI`). Blokuje je, bo tą drogą ukrywano złośliwe treści. Outlook na komputerze
je pokazuje i stąd brało się zgłoszenie „u jednych działa, u drugich nie".

Jedyne rozwiązanie to trzymać obrazki pod publicznym adresem i wskazywać je w podpisie.
Tym właśnie jest to repozytorium.

## Adresy

Po włączeniu GitHub Pages pliki są dostępne pod:

```
https://jakubblueberry.github.io/processway-sygnatura/sygnatura/pw-sig-logo.png
https://jakubblueberry.github.io/processway-sygnatura/sygnatura/pw-sig-telefon.png
https://jakubblueberry.github.io/processway-sygnatura/sygnatura/pw-sig-mail.png
https://jakubblueberry.github.io/processway-sygnatura/sygnatura/pw-sig-adres.png
https://jakubblueberry.github.io/processway-sygnatura/sygnatura/pw-sig-www.png
```

## Czego NIE wolno tu robić

**Nie zmieniać nazw plików ani ścieżek.** Adresy są wpisane na sztywno w podpisach, które ludzie
mają już wklejone w swoich skrzynkach. Zmiana nazwy pliku = zniknięcie logo u wszystkich naraz,
po cichu, bez żadnego komunikatu.

Jeśli obrazek wymaga poprawki, podmieniamy zawartość pliku pod tą samą nazwą.

## Stan i plan

To rozwiązanie **tymczasowe**. Repozytorium żyje na prywatnym koncie, więc docelowo pliki powinny
trafić na serwer ProcessWay (`processway.pl`), czyli pod kontrolę właściciela marki.
Przeniesienie to podmiana adresu w podpisach, nic więcej.

Do czasu przeniesienia obowiązuje zasada: **to repozytorium nie znika i nie zmienia nazwy.**

## Źródło projektu

Podpis pochodzi z pliku Figmy ProcessWay, węzeł `586:54` (543 × 423 px).
Obrazki wyeksportowano w skali 3 i skwantyzowano do 64 kolorów, żeby cały podpis zmieścił się
w limicie 102 KB, powyżej którego Gmail przycina wiadomość i ucina stopkę razem z klauzulami prawnymi.
