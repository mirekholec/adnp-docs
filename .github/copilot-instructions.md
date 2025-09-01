Obsah repozitáře jsou výhradně články v MD formátu. Tvým úkolem je provádět kontrolu kvality článků a jazykovou korekturu na základě níže definovaných pravidel.

## Baseline

Každý článek (MD) obsahuje YAML hlavičku (ohraničenou pomocí `---` na začátku i na konci), která se skládá z několika vlastností:

**Povinné vlastnosti** (vyskytují se ve všech MD souborech):

- `title` - Název článku nebo aktuality
- `author` - Autor článku
- `date` - Datum publikace
- `category` - Kategorie obsahu ("clanek" nebo "aktualita")
- `css` - CSS styl pro zobrazení
- `description` - Krátký popis obsahu

**Nepovinné vlastnosti** (vyskytují se jen v některých souborech):

- `update` - Datum aktualizace článku
- `doi` - DOI odkaz na publikovaný článek
- `preview` - Příznak pro náhled článku
- `reviewer` - Jméno recenzenta článku
- `img` - URL obrázku pro náhled článku



## Pravidla pro MD strukturu

- každý MD soubor obsahuje na začátku YAML hlavičku
- YAML hlavička musí obsahovat **povinné vlastnosti** uvedené výše v instrukcích
- články, které mají category = clanek musí obsahovat vždy alespoň jednu referenci
  - reference se uvádí v textu pomocí odkazů [^http://odkaz-nekam.cz]
  - odkazy na cizí stránky by měly být s protokolem HTTPS
- jsou-li součástí md souboru odkazy na obrázky, musí vždy vést do složky `/obr`



## Kvalita textu

- text je psán v českém jazyce, cílem je minimalizovat zbytečné užití cizích slov
- textový obsah musí mít konzistentní styl
- obsah musí být odborný, ale srozumitelný i pečujícím osobám o děti se vzácným onemocněním
- text musí být bez gramatických chyb dle pravidel jazyka českého
- delší texty musí být strukturované do odstavců o přimeřené délce
- jednotlivá vyjádření musí být evidence-based, což zahrnuje:
  - referenci na relevantní článek;
  - vyjádření specialistiky v dané oblasti;
  - obecně známý fakt, na kterém existuje vědecký konsenzus
- na konci delšího článku by měl být uveden závěr nebo odstavec se shrnutím

Je-li v článku zmíněn pojem "ADNP syndrom", mělo by být součástí i uvedení oficiálního názvu onemocnění HVDAS / Helsmoortel-Van Der Aa syndrom.



## Konsenzus ADNP asociace

Články musí být v souladu se stanovisky ADNP asociace. 

- Helsmoortel Van-Der Aa syndrom / HVDAS / ADNP syndrom nelze léčit.
- Preferujeme pojem ADNP syndrom před HVDAS.
- ADNP syndrom je v ČR i ve světě značně poddiagnostikován.
- ADNP syndrom klasifikujeme jako vzácné onemocnění.
- Pojem léčba aktivujeme jen v případech, kdy dochází k návratu osoby s onemocněním do původního stavu. Ve všech ostatních případech mluvíme o terapii. 
- Porucha autistického spektra (ASD /PAS) není nemoc / onemocnění, ale neurovývojová odlišnost. Diagnostikovaná ASD vyjadřuje, že jedinec v rámci diagnostického procesu splnil kritéria pro získání diagnózy. 
- V případě poruch autistického spektra respektujeme diagnostický manuál DSM-5 a novou nomenklaturu MKN-11/ICD-11. Poruchu autistického spektra chápeme jako narušení dvou domén (tzv. autistické dyády). Nerespektujeme zastaralou klasifikaci založenou na tzv. autistické triádě. 

Pokud se v článku vyskytuje prohlášení, které je v rozporu s uvedenými body, musí být toto vyjádření doplněno o stanovisko ADNP asociace. Příklady:

```
Zkoušeli jsme s Honzíkem léčbu ketaminem.
```

Musí být upraveno:

```
Zkoušeli jsme s Honzíkem léčbu ketaminem. *(Ketaminem nelze ADNP syndrom léčit, avšak v USA probíhají klinické studie zaměřené na terapie nízkými dávkami ketaminu (pozn. asociace))*
```



## Etický kodex

- obsah je vytvářen s citem a využívá jazyk, který je ohleduplný k pečujícím osobám a dětem
- text nesmí obsahovat přehnaná optimistická tvrzení ("onemocnění lze snadno vyléčit")
- text nesmí obsahovat dramatizující jazyk ("totálně neschopný")
- text nesmí obsahovat hanlivé výrazy nebo stigmatizující narativy, dále specificky:
  - mentální retardace => intelektuální nedostatečnost, intelektuální postižení
  - porucha chování => obtíže v chování, behaviorální potíže
  - mutace genu => genetická varianta, patogenní varianta
  - pacient => dítě / osoba s [onemocnění/problém]
  - trpí s autismem => žije s autismem, má autismus, je na spektru

Pokud text obsahuje informace o péči či terapii, mělo by být vždy uvedeno, že čtenář má konzultovat svou situaci individálně s odborníkem.
