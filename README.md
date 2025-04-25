# Vizualizace překryvů voličů mezi kandidujícími (SKAS PrF MU 2025, Mgr)

Tento projekt obsahuje interaktivní vizualizaci, která znázorňuje, jak se překrývalo voličstvo jednotlivých kandidujících ve volbách do Studentské komory Akademického senátu Právnické fakulty Masarykovy univerzity (volební obvod studentů magisterského studia) v roce 2025.

Vizualizaci si můžete prohlédnout zde:  
👉 **[https://otflorian.github.io/muni-law-as-2025-mgr/](https://otflorian.github.io/muni-law-as-2025-mgr/)**

## Co vizualizace ukazuje

- **Uzel = kandidující osoba**
- **Spojnice mezi dvěma uzly = překryv voličů** (vypočtený pomocí *Jaccardova indexu*)
- **Síla propojení = podíl společných voličů vůči všem, kdo volili alespoň jednoho z dvojice**
- **Barva uzlu = komunita kandidátů**, kteří mají podobný voličský základ (podle detekce komunit)

Uživatel může:
- pohybovat s uzly (drag & drop)
- měnit prahovou hodnotu Jaccardova indexu pomocí posuvníku
- zobrazit si tabulku se seznamem propojení nad daným prahem
- obnovit stránku pro změnu výchozího rozmístění uzlů

## Použité technologie

- [Python](https://www.python.org/) (pandas, networkx, pyvis)
- [vis.js / vis-network](https://visjs.github.io/vis-network/) pro interaktivní graf
- HTML + JavaScript

## Autor

Vizualizaci vytvořil [Oldřich Tristan Florian](https://otflorian.com)

## Licence

Licencováno pod **[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**
