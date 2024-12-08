[Co dodělat ]: #
[ ]: #
<!-- 
Pojmy:

Řízení, ovládání, regulace

Zpětná vazba

Regulátor

Soustava

Autoregulace

Spojité regulátory, nespojité, kvazispojitév
-->





# Regulace

## Cíl
-	Studenti na příkladech vysvětlí, co je to regulátor a kde se používá
-   Budou umět rozlišit mezi řízením bez zpětné vazby (ovládáním) a se zpětnou vazbou (regulací)
-   Budou umět navrhnout a realizovat dvoustavový regulátor bez hystereze i s hysterezí
-   Dále se budou orientovat v základních pojmech z oblasti řízení a regulace

## Ověření cílů

Regulace

1. Vysvětlete, co je to regulace, nakreslete regulační schéma a vysvětlete jednotlivé části
2. Na příkladu vysvětlete princip dvoustavového regulátoru s a bez hystereze
3. Na příkladu vysvětlete význam senzorů v regulátorech
4. Ve zvoleném programovacím jazyce napište hlavní část algoritmu dvoustavového regulátoru s a bez hystereze

## Úlohy

### 1. Jaký je rozdíl mezi ovládáním a regulací

1. Vyhledejte pojmy ovládání a regulace a na základě toho vyhledejte tři praktické příklady ovládání a tři praktické příklady regulace. 
2. Zkuste zjistit, zda následující příklady řízení patří do ovládání, nebo regulace:
    - Pás na pokladně v supermarketu, který se automaticky zastaví, pokud zboží přeruší optozávoru.
    - Automatická závlaha zahrady, která se standardně spouští každou noc mezi 2 a 3 hodinou ranní. A pouze v případě, že celkové množství srážek od poslední závlahy přesáhne nastavenou hodnotu, závlaha se nespustí.
    - Halový portálový jeřáb s koncovými spínači (lidově koncáky), které zajišťují, že se v daném směru pohon zastaví. Tyto spínače slouží jako elektronické dorazy.
3. Vyhledejte alespoň pět příkladů regulátorů.


### 2. Navrhněte a realizujte dvoustavový regulátor

1. Navrhněte dvoustavový regulátor teploty (termostat) bez hystereze a s hysterezí.
2. Program nejprve odzkoušejte v simulátoru. Měřenou teplotu z čidla/senzoru teploty symulujte proměnnou, kterou budete ručně měnit.
3. Vyberte vhodný senzor/čidlo teploty a zprovozněte dvoustavový regulátor v řídící jednotce.
4. Hodnoty z termostatu podle možností řídící jednotky zakomponujte do vizualizace, nebo alespoň zobrazujte na displeji.

> :key: **Termostat**
>
> Dvoustavový regulátor teploty, často s nastavitelnou hysterezí.

> :key: **Hystereze**
>
> V regulaci se s ní setkáme buď v podobě přirozené setrvačnosti soustavy, např. litinový radioátor se pomalu nahřeje a dlouho vydrží hřát i po uzavření ventilu. Nebo ji vnášíme úmyslně v podobě tzv. regulátoru s hysterezí. Je důležitá u akčních členů, kterým nesvědčí časté zapínání/vypínání, např. kvůli menší účinnosti (spalovací kotle na uhlí, dřevo, štěpku, apod.), větši poruchovosti, apod. Hysterezi do otopné soustavy můžeme také vnést např. použitím velkých akumulačních nádrží.

> :key: **Dopravní zpoždění**
>
> Doba než se projeví vliv regulátoru na soustavě.


### 3. Navrhněte a realizujte PID regulátor

1. Navrhněte PID regulátor teploty (termostat) bez hystereze a s hysterezí.
2. Program nejprve odzkoušejte v simulátoru. Měřenou teplotu z čidla/senzoru teploty symulujte proměnnou, kterou budete ručně měnit.
3. Vyberte vhodný senzor/čidlo teploty a zprovozněte dvoustavový regulátor v řídící jednotce.



