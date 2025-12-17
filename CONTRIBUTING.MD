# Współpraca – CONTRIBUTING.md

Dziękujemy za zainteresowanie współpracą przy projekcie o stolicach świata. Celem jest stworzenie rzetelnego, uporządkowanego źródła informacji o stolicach różnych państw.

## Zasady ogólne

- Sprawdź otwarte issue i PR, aby uniknąć duplikacji.
- Większe zmiany najpierw zaproponuj w issue.
- Zachowaj spójny styl kodu i struktury plików/danych.

## Nazewnictwo branchy

- Funkcjonalności: `feature/nazwa-funkcjonalnosci` (np. `feature/dodanie-strony-warszawa`)
- Poprawki błędów: `fix/opis-bledu`
- Dokumentacja/dane: `docs/opis-zmiany`

## Konwencja commitów

Format: `<typ>: krótki opis zmiany`  
Typy: `feat` (funkcjonalności), `fix` (bugi), `docs` (treści), `refactor` (zmiany kodu bez zmiany logiki), `chore` (konfiguracja, narzędzia).  
Przykład: `feat: dodanie strony o stolicy Hiszpanii`

## Komunikacja

- Błędy i propozycje funkcji zgłaszaj w **Issues**.
- Zmiany wprowadzaj przez **Pull Requests** z opisem zmian i sposobu testowania.
- Styl: rzeczowo, z szacunkiem, bez ad personam.

## Proces pracy

1. Fork repozytorium.
2. Sklonuj forka i przejdź do katalogu: `git clone https://github.com/twoj-login/nazwa-repo.git` oraz `cd nazwa-repo`.
3. Utwórz branch: `git switch -c feature/dodanie-strony-warszawa`.
4. Wprowadź zmiany, zrób commity zgodne z konwencją, zaktualizuj branch względem `main` (rebase/merge).
5. Wypchnij branch: `git push -u origin feature/dodanie-strony-warszawa`.
6. Utwórz pull request do `main`.
- Dodawaj tylko zweryfikowane informacje (nazwa stolicy, kraj, podstawowe dane).
- Zachowuj spójny format danych z resztą repozytorium.
- Ciekawostki i informacje historyczne zapisuj neutralnie i faktograficznie.
