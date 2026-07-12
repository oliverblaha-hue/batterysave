# batterysave

`batterysave` je malá macOS aplikace do horní lišty, která hlídá baterii a upozorní tě při dosažení nastaveného procenta.

## Funkce

- běží jen v horní liště
- průběžně kontroluje stav baterie
- při vybíjení ukazuje odhad času do vybití
- když macOS neposkytne odhad času, ukáže procenta baterie
- při nabíjení nebo napájení ze zdroje ukazuje jen `-`
- pošle oznámení jen ve chvíli, kdy baterie přesně dosáhne nastavené hodnoty
- nastavení hranice přímo z menu v horní liště
- výběr jazyka aplikace: English / Čeština
- automatické spuštění po přihlášení
- podpora Apple Silicon i Intel Maců

## Instalace

1. Otevři `batterysave-installer.dmg`.
2. Spusť `install-batterysave.command`.
3. Vyber jazyk aplikace.
4. Nastav procento baterie pro upozornění.
5. Pokud se macOS zeptá, povol oznámení.

## Použití

Po instalaci se `batterysave` zobrazí v horní liště.

V horní liště ukazuje:

- čas do vybití, například `2h 15m`
- procenta baterie, pokud macOS neposkytne odhad času
- `-`, pokud se Mac nabíjí nebo je připojený ke zdroji

Kliknutím na položku v horní liště můžeš:

- změnit procento pro upozornění
- zapnout nebo vypnout upozornění jen při vybíjení
- změnit jazyk aplikace
- ukončit aplikaci

## Oznámení

Oznámení přijde jen ve chvíli, kdy baterie při vybíjení přesně dosáhne nastavené hodnoty.

Příklad:

```text
Stav baterie klesl na 25 %.
