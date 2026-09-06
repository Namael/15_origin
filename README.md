# Patnáctka náš domov — čistý redesign stávajícího webu

Redesign webu **15nasdomov.cz** beze změny obsahu.

Veškerý text je převzatý z původního webu doslova. Nic není domyšlené,
přeformulované ani zkrácené. Změnil se pouze vzhled, struktura stránek
a technické provedení.

> Existuje i druhá varianta v repozitáři **Namael/15**, kde jsou texty
> přepsané a doplněné. Tenhle repozitář je ta konzervativní cesta.

## Jak to spustit

Otevřít `index.html` v prohlížeči. Žádný build, žádné závislosti.

Pro veřejný náhled: **Settings → Pages → Deploy from branch → main / root**.

## Stránky

Struktura kopíruje navigaci původního webu.

| Odkaz | Stránka | Zdroj |
|---|---|---|
| `#/` | Domů | `/` |
| `#/novinky` | Novinky | `/blog` |
| `#/kandidati` | Naši kandidáti | `/nas-tym` |
| `#/program` | Náš program | `/volebni-program` + 10 podstránek |
| `#/ke-stazeni` | Ke stažení | `/ke-stazeni` |
| `#/kalendar` | Kalendář | `/kalendar` |
| `#/archiv` | Články z archivu | `/novinky` |
| `#/studie` | Koncepční studie koalice | `/koncepcni-studie-koalice` |
| `#/radnice` | Radnice pro občany | `/kopie-4-roky-na-radnici` |

## Hustota, ne rozvláčnost

Web je stavěný tak, aby se muselo co nejméně rolovat.

První obrazovka nese všechno podstatné najednou: titulek, odstavec
„KDO JSME?" jako shrnutí, číslo transparentního účtu, oba QR kódy pro dar,
termín voleb, banner a rozcestník na čtyři hlavní stránky. Nic z toho není
schované pod záhybem.

Zbylé čtyři otázky z původní titulky jsou vedle sebe ve čtyřech sloupcích,
ne pod sebou.

Program byl na starém webu rozdělený na deset samostatných stránek. Tady je
na jedné. Kapitoly jsou sbalené, takže celý program je vidět jako seznam
deseti řádků a rozbalíte si jen to, co vás zajímá. Úvodní text je vysázený
do dvou sloupců. Všech 129 programových bodů je zachováno.

Archiv obsahuje všech 213 článků z let 2018 až 2020 jako hustý dvousloupcový
seznam s filtrem podle roku. Perex se rozbalí po kliknutí na titulek.

## Vizuální směr

Dvě tiskové barvy na bílém papíře, podle bannerů uskupení.

| | |
|---|---|
| Červená | `#E8224B` |
| Červená pro malý text | `#C2143A` |
| Modrá | `#2D4370` |
| Podklad | `#FFFFFF` |

Titulky **Archivo**, texty **Source Serif 4**. Ostré hrany, silné dělicí linky,
žádné stíny ani zaoblené karty. Plně responzivní.

## Fotografie

Vše ve složce `assets/` pochází z vašich materiálů. Titulní banner je dodaný
soubor `banner.avif`, zbytek je stažený ze stávajícího webu. QR kódy pro dar
200 a 500 Kč jsou původní, míří na transparentní účet `2900937009/2010`.

Pořadí portrétů 1 až 16 odpovídá pořadí na stávajícím webu. **Projděte si ho**,
přiřazení tváře ke jménu je citlivá věc.

## Poznámky k textu

Do textů jsem nezasahoval s jedinou výjimkou a jednou opravou technického rázu.

- **`MAJETEK A BYTOVÁ POLITIKA`.** Přehled programu na starém webu uvádí
  „MAJTEK", samotná podstránka sekce uvádí správně „MAJETEK". Použil jsem
  variantu z podstránky. Řekněte, jestli chcete zachovat i překlep.
- **Mezery před interpunkcí.** Při čtení starého webu vznikaly artefakty typu
  `k volbám ,` tam, kde byl v textu odkaz. Ty jsem mechanicky opravil.
  Slova ani jejich pořadí se nikde nezměnily.

Ostatní odchylky od spisovné češtiny jsou ponechané tak, jak jsou na webu dnes,
včetně `PeadDr.`, `devítipodklažák` a `s velkým náskokem vyhrál volby`.

## Co ještě vyřešit před spuštěním

- soubory PDF pod tlačítky ke stažení, prezentace ke koncepčním studiím
- napojení newsletteru a redakčního systému pro novinky
- odkazy na jednotlivé články archivu, teď je to seznam bez detailu
- autorská práva a popisky k fotografiím, včetně souhlasu vyfotografovaných osob
- cookies a zásady zpracování osobních údajů
- povinné údaje o zadavateli a zpracovateli volební kampaně
