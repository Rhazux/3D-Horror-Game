# Ideový plán hry

[Zpět na hlavní stránku projektu](../README.md)

## Formální název projektu

**Explore Abandoned Hospital**

## Marketingový úvodník

Nemocnice je už dávno zavřená. Přesto se z jejího opuštěného oddělení ozývá zvonek pro přivolání sestry. Vstoupíš dovnitř, abys zjistil, odkud zvuk přichází. Dveře se za tebou zavřou a jejich ovládání přestane reagovat.

S baterkou v ruce prozkoumej prázdné místnosti, najdi potřebné předměty a obnov napájení dveří. Pozorně sleduj své okolí. Ze sousedního pokoje se ozývají kroky a některé věci při návratu nejsou tam, kde původně byly.

Najdi cestu ven z oddělení, které možná není tak opuštěné, jak se zdá.

## Popis hry

### Základní myšlenka

Chci vytvořit krátkou 3D hororovou hru z pohledu první osoby pro jednoho hráče. Hra bude zaměřená na průzkum prostředí, hledání předmětů a budování napětí.

Hráč se ocitne uvnitř opuštěné nemocnice. Kvůli nefunkčnímu elektrickému pohonu vstupních dveří bude muset obnovit jejich napájení, aby se dostal ven.

Předpokládaná délka prvního hraní bude přibližně 5–10 minut.

### Prostředí a velikost mapy

Mapa bude obsahovat maximálně čtyři malé propojené prostory. Recepce a vstupní chodba budou tvořit jeden společný prostor.

| Prostor | Vybavení a účel |
| --- | --- |
| Recepce se vstupní částí | Pult, židle a vstupní dveře. Zde hráč začne a na konci odejde. |
| Pokoj pacientů | Postele, noční stolek a osobní věci. Hráč zde najde klíč od sesterny. |
| Sesterna | Stůl, skříňky a rozvodná skříň. Zde hráč obnoví napájení. |
| Vyšetřovna | Vyšetřovací lehátko a staré vybavení. Hráč zde najde náhradní pojistku. |

Z recepce povedou dveře do pokoje pacientů a sesterny. Ze sesterny bude přístupná vyšetřovna. Celá hra se bude odehrávat uvnitř této části budovy.

### Pohyb a ovládání

Hráč bude ovládat postavu z pohledu první osoby. Pomocí klávesnice se bude pohybovat po místnostech a myší se rozhlížet.

Stěny, dveře a větší vybavení budou mít kolize, aby jimi postava nemohla procházet.

| Klávesa nebo zařízení | Akce |
| --- | --- |
| W, A, S, D | Pohyb |
| Myš | Rozhlížení |
| E | Interakce s předměty, dveřmi a zařízeními |
| F | Zapnutí a vypnutí baterky |
| Esc | Pozastavení hry a otevření nabídky |

### Herní možnosti

- **Průzkum prostředí:** Hráč bude procházet místnosti a hledat předměty potřebné k pokračování.
- **Baterka:** Od začátku bude mít baterku, kterou půjde zapínat a vypínat. Pro krátký průchod bude mít neomezenou kapacitu.
- **Interakce:** Při zamíření na použitelný předmět se zobrazí krátká výzva. Hráč bude moci otevírat dveře, sbírat předměty, číst poznámky a používat zařízení.
- **Předměty:** Klíč a pojistka se po sebrání automaticky uloží a na správném místě použijí.
- **Úkoly:** Aktuální cíl se zobrazí stručným textem. Cedulky a poznámka v sesterně pomohou s orientací.
- **Hororové události:** Vybrané akce spustí zvuk, změnu osvětlení nebo přesunutí předmětu mimo hráčův výhled.
- **Opakované hraní:** Po dokončení půjde hru spustit znovu nebo ukončit.

### Cíl hráče a průběh hry

Hlavním cílem bude obnovit napájení vstupních dveří a opustit nemocniční oddělení.

1. Hráč začne v recepci a zjistí, že vstupní dveře nereagují.
2. V pokoji pacientů najde klíč od sesterny.
3. Odemkne sesternu a zjistí, že v rozvodné skříni chybí pojistka.
4. Podle krátké poznámky vyhledá náhradní pojistku ve vyšetřovně.
5. Vrátí se do sesterny, vloží pojistku a obnoví napájení.
6. Projde zpět do recepce, otevře vstupní dveře a dokončí hru.

Průchod doplním několika hororovými událostmi. Po sebrání klíče se například ozvou kroky ze sousední místnosti. Při návratu do recepce bude jedna židle stát na jiném místě.

Každá událost se během jednoho hraní spustí pouze jednou. Průchod východovými dveřmi zobrazí závěrečnou obrazovku.

## Popis audiovizuálu

### Vizuální stránka

Prostředí vytvořím ve 3D. V Blenderu připravím modely místností, dveří, postelí, stolů, skříněk a dalších předmětů.

Nemocnice bude působit zanedbaně a dlouho neudržovaně. Použiju zašlé stěny, oprýskanou barvu, špinavou podlahu, rezavé vybavení a rozházené věci.

Barevnost bude tvořit hlavně šedá, vybledlá zelená a studené modré odstíny. Jednotlivé místnosti budou mít rozpoznatelné vybavení, aby se v nich hráč dokázal orientovat.

Před obnovením napájení bude hlavním světlem baterka, doplněná slabým světlem z oken. Po opravě se rozsvítí část stropních světel a jedno může krátce zablikat.

Rozhraní bude obsahovat malý zaměřovací bod, výzvy k interakci, aktuální úkol a informace o sebraných předmětech.

### Zvuková stránka

Použiju zvuky kroků, vrzání dveří, kapající vody, kovových ran a větru za okny. Zvuky rozmístím do prostoru tak, aby hráč vnímal směr, odkud přicházejí.

Výrazným motivem bude nemocniční zvonek s vlastním bateriovým napájením. Ze sousedních místností se budou ozývat zvuky, i když v nich hráč nikoho neuvidí.

Napětí podpoří jemný hluboký zvuk v pozadí a krátké výraznější efekty během vybraných událostí. Celkovou hlasitost půjde upravit v nabídce.

## Chystané použité technologie

| Technologie | Plánované využití |
| --- | --- |
| Godot | Sestavení mapy, osvětlení, zvuky, kolize, rozhraní a propojení celé hry |
| GDScript | Pohyb hráče, interakce, postup úkolů a spouštění událostí |
| Blender | Tvorba modelů prostředí, nábytku a předmětů |
| Git a GitHub | Ukládání verzí projektu a organizace souborů |
| Markdown | Zápis dokumentace |

Hru plánuji připravit pro Windows.

Nejprve vytvořím jednoduchý prototyp a zprovozním celý průchod od začátku po konec. Potom doplním podrobnější modely, textury, osvětlení a zvuky.

## Dvě hypotézy

Po vydání první hratelné verze nechám hru vyzkoušet deset lidí, kteří ji ještě nehráli. Všichni budou hrát stejnou verzi samostatně, se zapnutým zvukem a bez předchozího vysvětlení řešení.

### Hypotéza 1 – hororová atmosféra

**Předpokládám, že alespoň 7 z 10 hráčů ohodnotí napětí při hraní známkou 4 nebo 5 na pětibodové škále.**

Po hraní položím každému otázku: „Jak silné napětí jsi při hraní cítil?“

Hodnocení bude od 1 – žádné napětí do 5 – velmi silné napětí.

Hypotézu v tomto testu potvrdím, pokud alespoň sedm hráčů vybere hodnotu 4 nebo 5. Při nižším počtu ji vyvrátím.

### Hypotéza 2 – srozumitelnost postupu

**Předpokládám, že alespoň 8 z 10 hráčů dokončí hru při prvním hraní do 10 minut bez pomoci jiné osoby.**

Čas budu měřit od získání ovládání postavy po zobrazení závěrečné obrazovky. Zaznamenám čas, dokončení hry a případnou pomoc jiné osoby. Nápovědy přímo ve hře budou povolené.

Hypotézu v tomto testu potvrdím, pokud podmínku splní alespoň osm hráčů. Při nižším počtu ji vyvrátím.
