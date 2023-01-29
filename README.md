# Engeto_projekt3

Elections scraper

Projekt pro Engeto Academy

Získá volební data pro vybraný kraj v Česku (2017) z "https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ". Skript extrahuje výsledky voleb z každé obce vybraného kraje do souboru csv.

Vyberte prosím kraj přes písmeno X ve sloupci „Výběr obce“ na https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ. Poté do vstupního řádku skriptu zadejte adresu URL vybraného kraje. Například pro okres Kolín zadejte tuto url: https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=2&xnumnuts=2104.

Dále budete požádáni o název souboru csv. Zadejte prosím pouze jméno bez .csv.

Výstupní soubor csv obsahuje hlavičku s kódem každé obce, názvem obce, počtem registrovaných voličů, přijatými obálkami, platnými hlasy a názvy politických stran. Čísla každé obce jsou na samostatném řádku v abecedním pořadí.

Ve stejném adresáři je i příklad výstupu csv pro okres Beroun.
