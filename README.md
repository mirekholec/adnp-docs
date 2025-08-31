# ADNP DOCS

Tento repositář obsahuje články a aktuality webové stránky [adnpasociace.cz](https://adnpasociace.cz)

## Struktura aktuality

Aktualita je vždy jen jeden odstavec - krátké sdělení bez uvádění zdrojů. 



## Struktura článku

- úvodní popis
- hlavní text - zpravidla 3 odstavce
- závěr



### Zdroje

Nově se zdroje zapisují přímo do textu jako poznámka pod čarou. Místo čísla poznámky se uvádí URL (typicky DOI). Během generování se automaticky zdroje očíslují dle pořadí v textu a na konci článku se vygeneruje seznam použitých zdrojů.

## YAML vlastnosti v MD souborech

Následující tabulka obsahuje všechny YAML vlastnosti používané v hlavičkách MD souborů:

| Název vlastnosti | Povinnost | Vysvětlení |
|------------------|-----------|------------|
| title | Povinná | Název článku nebo aktuality |
| author | Povinná | Autor článku (jméno a příjmení) |
| date | Povinná | Datum publikace ve formátu YYYY-MM-DD |
| category | Povinná | Kategorie obsahu ("clanek" nebo "aktualita") |
| css | Povinná | CSS styl pro zobrazení (prázdný řetězec "" nebo "extra") |
| description | Povinná | Krátký popis obsahu článku nebo aktuality |
| update | Nepovinná | Datum aktualizace článku ve formátu YYYY-MM-DD |
| doi | Nepovinná | DOI odkaz na publikovaný článek |
| preview | Nepovinná | Příznak pro náhled článku (boolean) |
| reviewer | Nepovinná | Jméno recenzenta článku |
| img | Nepovinná | URL obrázku pro náhled článku |