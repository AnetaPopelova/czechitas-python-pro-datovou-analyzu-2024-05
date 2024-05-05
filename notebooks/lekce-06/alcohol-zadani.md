
# Vliv alkoholu na výkonnost studentů

## Cíl analýzy
Zjistit, jak konzumace alkoholu ovlivňuje akademické výsledky studentů. 

Cílem je analyzovat, zda existuje souvislost mezi množstvím konzumovaného alkoholu, četností sociálních aktivit a výkonem ve škole.


### Krok 1: Načtení a příprava dat

- Načtěte data,
- přejmenujte sloupce pro lepší manipulaci,
- zkontrolujte typy dat,
- zjistěte počet 
  - záznamů v každém sloupci,
  - chybějících hodnot v každém sloupci,
  - počet unikátních hodnot v každém sloupci a 
- upravte datový typ sloupce `Timetamp` na `datetime` - časové pásmo zanedbejte (může se hodit parametr `format`).

### Krok 2: Explorativní analýza dat (EDA)
- Proveďte základní statistický popis dat, 
- pro sloupce `["Sex", "Accommodation", "Monthly_Allowance"]` vypiš unikátní hodnoty a jejich počet
- vizualizujte distribuci klíčových proměnných:
  - histogram a boxpot pro Yearly GPA (identifikujte extrémní hodnoty)
  - sloupcovy graf pro počet žen vs mužů v datasetu a
- formulujte 3 vlastní hypotézy, které lze na datech ověřit.

### Krok 3: Čištění dat
- Odstraňte všechny záznamy, kde chybí informace o měsíčním kapesném,
- textové hodnoty ve sloupci měsíční kapesné nahraďte celým číslem (středová hodnota) a
- odstraňte všechny záznamy studentů `Postgraduate` studia.

### Krok 4: Vizualizace výsledků
- Vytvořte vizualizace souvisejících s vašimi hypotézami.
- Pokud potřebujete provést dodatečné čistění nebo tranformaci dat, učiňte tak.

### Krok 5: Závěr a doporučení
- Sumarizujte zjištěné výsledky, diskutujte o jejich významu a uveďte možná doporučení pro zainteresované strany, jako jsou univerzitní poradci a studenti.
