Důležité!
---------

- Nezapomeňte na titulní straně uvést své jméno a login.
- Pokud jste tak ještě neučinili, přečtěte si důkladně pokyny k projektu a soubor
  s detailní specifikací projektu!
- Pomlčky a spojovníky jsou v tomto textu reprezentovány pouze znakem -.
  Ve vysázeném dokumentu musí být správná šířka pomlček, spojovníků a mezer
  podle kontextu.
- Vzorce a některé další elementy jsou v tomto textu nahrazeny třemi tečkami.
  V projektu je vysázejte podle vzorového dokumentu.
- Odkazy na definice, rovnice, poznámky pod čarou nebo strany musí být ve
  výsledném PDF vysázeny speciálními příkazy k tomu určenými.

- Text dokumentu níže slouží pro urychlení práce (tj. hlavně ať nemusíte ručně
  přepisovat kusy textu).


Text dokumentu
--------------

Vysoké učení technické v Brně
Fakulta informačních technologií

Typografie a publikování - 2. projekt
Sazba dokumentů a matematických výrazů

2022
Jméno příjmení (xlogin)


Úvod

V této úloze si vyzkoušíme sazbu titulní strany, matematických vzorců, prostředí a dalších textových struktur obvyklých pro technicky zaměřené texty (například rovnice ... nebo Definice ... na straně ...). Pro vytvoření těchto odkazů používáme příkazy \label, \ref a \pageref.
Na titulní straně je využito sázení nadpisu podle optického středu s využitím zlatého řezu. Tento postup byl probírán na přednášce. Dále je na titulní straně použito odřádkování se zadanou relativní velikostí 0,4 em a 0,3 em.


1 Matematický text

Nejprve se podíváme na sázení matematických symbolů a výrazů v plynulém textu včetně sazby definic a vět s využitím balíku amsthm. Rovněž použijeme poznámku pod čarou s použitím příkazu \footnote. Někdy je vhodné použít konstrukci ${}$ nebo \mbox{}, která říká, že (matematický) text nemá být zalomen. 

Nedeterministický Turingův stroj (NTS) je šestice tvaru ..., kde:
... je konečná množina vnitřních (řídicích) stavů,
... je konečná množina symbolů nazývaná vstupní abeceda, ...,
... je konečná množina symbolů, ..., ..., nazývaná pásková abeceda,
..., je parciální přechodová funkce, a
... je počáteční stav a ... je koncový stav.

Symbol ... značí tzv. blank (prázdný symbol), který se vyskytuje na místech pásky, která nebyla ještě použita.
Konfigurace pásky se skládá z nekonečného řetězce, který reprezentuje obsah pásky, a pozice hlavy na tomto řetězci. Jedná se o prvek množiny ....
Konfiguraci pásky obvykle zapisujeme jako ... (podtržení značí pozici hlavy).
Konfigurace stroje je pak dána stavem řízení a konfigurací pásky. Formálně se jedná o prvek množiny ....

# poznamka pod carou: Pro libovolnou abecedu ... je ... množina všech nekonečných řetězců nad ..., tj. nekonečných posloupností symbolů ze ....


1.1 Podsekce obsahující definici a větu

Řetězec ... nad abecedou ... je přijat NTS ..., jestliže ... při aktivaci z počáteční konfigurace pásky ... a počátečního stavu ... může zastavit přechodem do koncového stavu ..., tj. ... pro nějaké ....
Množinu ... je přijat NTS ... nazýváme jazyk přijímaný NTS ....
Nyní si vyzkoušíme sazbu vět a důkazů opět s použitím balíku amsthm.

Třída jazyků, které jsou přijímány NTS, odpovídá rekurzivně vyčíslitelným jazykům.


2 Rovnice

Složitější matematické formulace sázíme mimo plynulý text. Lze umístit několik výrazů na jeden řádek, ale pak je třeba tyto vhodně oddělit, například příkazem \quad.
...
V rovnici ... jsou využity tři typy závorek s různou explicitně definovanou velikostí.
...
V této větě vidíme, jak vypadá implicitní vysázení limity ... v normálním odstavci textu. Podobně je to i s dalšími symboly jako ... či .... 
S vynucením méně úsporné sazby příkazem \limits budou vzorce vysázeny v podobě ... a .... 


3 Matice

Pro sázení matic se velmi často používá prostředí array a závorky (\left, \right). 
...
Prostředí array lze úspěšně využít i jinde.
...