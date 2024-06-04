# ZADANIE 
## Všeobecné pokyny

- Vytvorte **novy repoziár** pre toto zadanie
- Pre každú úlohu vytvorte **samostatný php súbor** identifikovaný názvom úlohy (názov uvediem)
- **Importujte** si databázu northwind.sql **(POZOR NOVA VERZIA DATABAZY, ABY FUNGOVALI AJ OSTATNE POZIADAVKY!!!)**
- Pre komunikaciu s databázov **vytvorte používateľa** s názvom: "userdb" a heslom: "databaza", budeme mať všetci jednotné
- **súbor** na komunikáciu s databázou **pomenujte connect.php** a vo všetkých ostatných php súboroch budete tento súbor volať **pomocou** volania: 
```php
require_once "connect.php";
```

## Úloha 01 
Vytvorte vo vašom repozitáre súbor  uloha01.php
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 01"** a pod ním výpíšte z databázy všetky stĺpce z tabuliek Zákazníci, Objednávky a Dodávatelia
-  v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 02"** a pod ním výpíšte z databázy všetkých zákazníkov v abecednom poradí, podľa krajiny a názvu
-  v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 03"** a pod ním výpíšte z databázy všetky objednávky podľa dátumu
-  v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 04"** a pod ním výpíšte z databázy počet všetkých objednávok uskutočnených v roku 1997
-  v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 05"** a pod ním výpíšte z databázy mená všetkých kontaktných osôb, kde je osoba manažérom, v abecednom poradí
-  v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 06"** a pod ním výpíšte z databázy Získajte všetky objednávky zadané 19. mája 1997  

## Úloha 02 
Vytvorte vo vašom repozitáre súbor  uloha02.php

 - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 01"** a pod ním vytvorte prehľad pre všetky objednávky z roku 1996 a ich zákazníkov (152 riadkov)
 - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 02"** a pod ním vytvorte  prehľad, ktorý zobrazuje počet zamestnancov a zákazníkov z každého mesta, ktoré má zamestnancov (5 riadkov)
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 03"** a pod ním vytvorte  prehľad, ktorý zobrazuje počet zamestnancov a zákazníkov z každého mesta, ktoré má zákazníkov (69 riadkov)
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 04"** a pod ním vytvorte  prehľad, ktorý zobrazuje počet zamestnancov a zákazníkov z každého mesta (riadky)
 - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 05"** a pod ním vytvorte  zostavu, ktorá zobrazuje ID objednávok a súvisiace mená zamestnancov pre objednávky, ktoré boli odoslané po požadovanom dátume (37 riadkov)
 - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 06"** a pod ním vytvorte  zostavu, ktorá zobrazuje celkové množstvo objednaných produktov (z tabuľky Order_Details). Zobrazovať záznamy len pre produkty, ktorých objednané množstvo je menšie ako 200 ( riadkov)
 - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 07"** a pod ním vytvorte  zostavu, ktorá zobrazuje celkový počet objednávok podľa zákazníka od 31. decembra 1996. Prehľad by mal vrátiť iba riadky, pre ktoré je celkový počet objednávok väčší ako 15 (5 riadkov)
 
  ## Úloha 03
  Vytvorte vo vašom repozitáre súbor  uloha03.php 
  - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 01"** a pod ním vypíšte: Aké boli naše celkové príjmy v roku 1997 (Výsledok musí byť 617 085,27)
  - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 02"** a pod ním vypíšte:  Aká je celková suma, ktorú nám doteraz každý zákazník zaplatil (Tip: QUICK-Stop nám zaplatil 110 277,32)
  - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 03"** a pod ním vypíšte:  10 najpredávanejších produktov (Tip: Najpredávanejší produkt je „Côte de Blaye“)
  - v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 04"** a pod ním vytvorte zobrazenie s celkovými výnosmi na zákazníka
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 05"** a pod ním vypíšte: Ktorí zákazníci zo Spojeného kráľovstva nám zaplatili viac ako 1 000 dolárov (6 riadkov)
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 06"** a pod ním vypíšte: Koľko zaplatil každý zákazník spolu a koľko v roku 1997. Chceme jednu sadu výsledkov s nasledujúcimi stĺpcami:  CustomerID,  Meno spoločnosti,  Krajina
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 07"** a pod ním vypíšte:Celkový počet zákazníkov zo všetkých objednávok
- v súbore vyrobte nadpis prvej kategórie **h1 s názvom "požiadavka 08"** a pod ním vypíšte:Celkový počet zákazníkov z 1997 objednávok Môžete to vyskúšať pomocou pohľadov, poddotazov alebo dočasných tabuliek. Skúste použiť zobrazenie [Súčet objednávok], ktoré už v databáze existuje. (91 riadkov, zákazník "Centro comercial Moctezuma" má celkové príjmy 100,80 a nulové (0) príjmy v roku 1997)
 
 <!---
 ## Úloha 03
Vytvorte vo vašom repozitáre súbor  uloha03.php Pri tejto úlohe nahrajte do repozitára aj export vašej verzie databázy pod názvom "northwind-03.sql"

 - Vložte sa do tabuľky Zamestnanci a zahrňte nasledujúce polia: Priezvisko, Meno, Titul, Zdvorilostný titul, Dátum narodenia, Dátum prenájmu, Mesto, Región, PSČ, Krajina, Domovský telefón, Hlásenia Komu
-  Vložiť objednávku pre seba do tabuľky Objednávky Zahrňte nasledujúce polia: CustomerID, EmployeeID, OrderDate, RequiredDate
-  Vložte podrobnosti objednávky do tabuľky Order_Details Zahrňte nasledujúce polia: OrderID, ProductID, UnitPrice, Quantity, Discount


 Aktualizujte svoj telefón (z predchádzajúceho záznamu v tabuľke Zamestnanci) (1 riadok)
 Dvojnásobné množstvo záznamu podrobností objednávky, ktoré ste vložili predtým (1 riadok)
 Zopakujte predchádzajúcu aktualizáciu, ale tentoraz aktualizujte všetky objednávky, ktoré sú s vami spojené (1 riadok)


 Vymažte záznamy, ktoré ste predtým vložili. Neodstraňujte žiadne ďalšie záznamy!
 
 --->
