# Ukraine situation summary

### Zadání práce
Napište program, který stáhne a zobrazí statistiku ohledně současné situace na Ukraině. Data budou uložená ve formě JSON na stránkách https://data2.unhcr.org/en/situations/ukraine. Zobrazte data pomocí externí knihovny, která zobrazí grafy. Jeden graf by měl zobrazovat počty uprchlíku od začátku operace, další pro vybraný časový úsek. Grafy by mělo být možné po zobrazení uložit.

### Návrh řešení
1. Import dat
   * Stažení z webu, přizpůsobení dat pro program
2. Zobrazení dat o útěku
  * Zobrazení dat od počátku operace
  * Zobrazení dat ve vybraném časovém úseku 
3. Zobrazení dat o návratu
  * Zobrazení dat od počátku operace
  * Zobrazení dat ve vybraném časovém úseku
4. Zobrazení dat do kterých zemí a v jakém počtu utekli
  * Zobrazení dat od počátku operace
  * Zobrazení dat ve vybraném časovém úseku
5. Ukončení programu

### Externí knihovna Xchart
K zobrazení dat v grafu využijeme externí knhovnu Xchart, zvládne zejména tyto funkce:
* Výsečové grafy
* Sloupcové grafy
* Čárové grafy
* a další...
