---
sidebar_position: 3
license: republish
author: Jan van Steenbergen
custom_edit_url: /501
origin: http://steen.free.fr/interslavic/design-criteria.html
---

# Konštrukčné kritériá

Interslovančina vychádza zo spoločného dedičstva všetkých slovanských národov a rozdiely sa premosťujú budovaním kompromisov. So všetkými slovanskými jazykmi sa zaobchádza rovnako, hoci sa nedá vyhnúť tomu, že slovanský medzijazyk má bližšie k „stredným“ jazykom, ako je slovenčina alebo rusínčina, než k periférnym jazykom, ako je srbčina alebo macedónčina. Interslovančina vyslovene nemá byť „slovanskejšou ako Slovania“ očistením od cudzích vplyvov, aj keď jazyk založený na spoločných znakoch slovanských jazykov aj tak automaticky odstráni mnohé miestne (neslanské) vplyvy. Nie je však dôvod vylučovať medzinárodnú slovnú zásobu za predpokladu, že ju poznajú všetci alebo aspoň väčšina slovansky hovoriacich.

Primárny účel interslovančiny, maximálna zrozumiteľnosť pre všetkých Slovanov, sa dosahuje systematickým poskytovaním najväčšieho spoločného menovateľa slovanských jazykov, a to z hľadiska gramatiky, pravopisu, syntaxe a slovnej zásoby. Keď nie je možné nájsť spoločné riešenie, vytvoríme kompromis. Ak ani kompromis nie je možný, musíme si vybrať alebo jednoducho navrhnúť obe riešenia.

Sekundárnym účelom je, že sa to dá ľahko naučiť a používať predovšetkým Slovanmi, ale aj Neslovanmi. Je zrejmé, že slovanský jazyk s gramatikou, ktorá pozostáva z desiatich jednoduchých pravidiel, je nemožný. Napriek tomu sa snažíme udržiavať gramatiku čo najjednoduchšiu a najpravidelnejšiu bez toho, aby sme obetovali slovanský charakter jazyka.

Táto časť podrobne popisuje, ako sa tieto dva účely dosahujú.

## Fonológia a písanie \{#phonology-and-writing}

Základné princípy dizajnu týkajúce sa fonológie a písania sú nasledovné:

- Spravidla by mali byť obe známe pre ľudí, ktorí hovoria slovanskými jazykmi. Preto pracujeme s obmedzeným počtom zvukov a vyhýbame sa zakomponovaniu neslovanských prvkov.
- Každý by mal vedieť písať medzislovančinu na vlastnej klávesnici, bez špeciálnych pomôcok a tak, aby to bolo prirodzené.
- Keďže rozdelenie na latinku a cyriliku prebieha stredom slovanského územia, s oboma sa zaobchádza rovnako.
- Nie sme preskriptivisti, pokiaľ ide o výslovnosť. Uvádzame len základné informácie a zvyšok by mal každý vyslovovať medzislovanský jazyk tak, aby mu to bolo príjemné a prirodzené. Žiadna výslovnosť nie je „správnejšia“ ako iná. Rovnako aj slovný stres je zadarmo.

V ideálnom prípade musí byť možné písať medzislovanským jazykom na akejkoľvek slovanskej klávesnici. Je tu však jeden problém: tieto klávesnice boli navrhnuté tak, aby zodpovedali štandardným národným pravopisom a každý z týchto pravopisov bol prispôsobený potrebám konkrétneho jazyka. Asi polovica slovanských jazykov používa latinku, druhá polovica je písaná v cyrilike a obe abecedy existujú v dvoch vzájomne sa vylučujúcich verziách: čeština, slovenčina, slovinčina a chorvátčina používajú latinku s `v`, `š`, `ž`  atď., poľština s @ @81 Ruština, ukrajinčina, bieloruština a bulharčina používajú cyriliku s `й`, `ь`, `ю`,  srbčina a macedónčina s `ј`, `љ`  a `џ`. Nie je na nás, aby sme sa rozhodli, že jedna cesta je „lepšia“ alebo „slovanskejšia“ ako tá druhá. Okrem toho, každý Slovan by sa mal cítiť pohodlne pri písaní medzislovančiny, takže musíme žiť s tým, že sa to dá písať rôznymi spôsobmi.

Keďže :isv[końe], :isv[koňe], :isv[konje], :isv[konie]  a _`kone`_ sú len rozdielne, prirodzene sa vyskytujúce spôsoby písania toho istého slova, nemá zmysel diskutovať o tom, ktorá verzia by mala byť „oficiálna“, pretože každá takáto voľba by automaticky urobila iné verzie „neoficiálnymi“. “ a teda „nesprávne“ alebo aspoň „neštandardné“. Preto sa riadime úplne iným prístupom: namiesto výberu akéhokoľvek oficiálneho pravopisu pracujeme s **prototypovým pravopisom**. Za predpokladu, že rôzne riešenia používané v národných pravopisoch sa všetky vzťahujú na jeden **prototyp**, považujeme tento prototyp aj za najlepší spôsob reprezentácie interslovančiny. Keďže máme do činenia s dvoma úplne odlišnými abecedami (latinkou a azbukou), nemôžeme sa vyhnúť tomu, aby sme mali jeden prototyp pravopisu pre každú z nich.

V ideálnom prípade by oba prototypy mali mať nasledujúce vlastnosti:

- musia byť intuitívne zrozumiteľné každému, kto vie čítať danú abecedu
- musia byť logické, konzistentné, jednoznačné a etymologicky správne
- musia dať slušnú aproximáciu správnej výslovnosti
- ak je to možné, jedna fonéma (hláska) = jeden znak
- mali by byť kompatibilné (jednoduchý prepis, najlepšie jeden v pomere 1:1)
- nemali by obsahovať neprirodzené prvky
- nemali by byť škaredé alebo inak urážlivé (ako napríklad `йа` alebo `łi`), ale nemali by byť obmedzené na špecifiká žiadneho národného jazyka
- na priemernej obrazovke počítača sa zobrazujú správne, preto sa treba vyhýbať znakom z neobvyklých znakových sád, kombinovaniu diakritiky a podobne.

Pretože žiadny z existujúcich slovanských pravopisov nemôže spĺňať všetky tieto požiadavky, rozlišujeme medzi základnou abecedou pozostávajúcou z foném, ktoré možno nájsť v každom slovanskom jazyku, a množstvom voliteľných rozšírení, ktoré možno použiť ako prostriedok na ujasnenie si výslovnosti. etymológia atď.

## Slovná zásoba \{#vocabulary}

### Medzinárodná verzus lavická slovná zásoba \{#international-versus-ѕlavic-vocabulary}

V ideálnom prípade musí byť každému hovorcovi slovanského jazyka povedomé každé slovo. Aj keď sa konkrétna forma slova nevyskytuje v cudzom jazyku, mala by aspoň evokovať konotáciu, ktorá mu naznačí správny smer. Je zrejmé, že to nie je vždy možné, a preto je potrebných niekoľko mechanizmov na rozhodnutie o výbere slovnej zásoby. Prvým a najdôležitejším krokom je zhromaždenie súboru koreňov slov, ktoré sú rozpoznateľné pre všetkých alebo väčšinu Slovanov. Potom môžu tieto korene slúžiť ako základ pre rozširovanie slovnej zásoby vytváraním zlúčenín.

Existujú dva typy slovnej zásoby, ktoré zohrávajú kľúčovú úlohu pri zlepšovaní vzájomného porozumenia medzi dvoma rôznymi jazykmi:

- medzinárodná slovná zásoba, slová, ktoré sú bežné v mnohých, aj nepríbuzných jazykoch. Väčšina z nich bola prevzatá priamo alebo nepriamo z latinčiny a gréčtiny (_`filozofija`, `universitet`, `material`, `motor`_), niekedy pochádza z iných jazykov (_`bjuro`, `fajl`, `jaguar`, `čaj`, `šokolad`_), v zriedkavých prípadoch dokonca zo samotnej slovanskej (_`vampir`, `vodka`_)
- spoločná zdedená slovná zásoba, inými slovami slovná zásoba, ktorú oba jazyky zdedili od spoločného predka, v tomto konkrétnom prípade praslovančiny

Medzinárodné slová sú neoddeliteľnou súčasťou každého slovanského jazyka. Ich výhodou je, že v rôznych jazykoch bývajú prakticky totožné, a to formou aj významom, a preto poskytujú vynikajúce riešenie pre medzislovančinu, najmä pre vzdelanejších. V prípade zdedenej slovnej zásoby je situácia o niečo zložitejšia, pretože každý jazyk prešiel vlastným charakteristickým vývojom a v dôsledku toho nemusí byť slovo v jednom jazyku okamžite rozpoznateľné pre tých, ktorí hovoria iným jazykom, aj keď ide o veľmi rovnaké slovo. Porovnajte napríklad poľské :isv[węgiel] a slovenské :isv[uhlie] „uhlie“. Okrem toho sa ich význam v niekoľkých prípadoch tak vzdialil od seba (napr. _`duma`_, čo znamená „myšlienka“ v ruštine a „hrdosť“ v poľštine), že ich možno považovať za _falošných priateľov_, t. j. slová, ktoré môžu byť ľahko nepochopené aj v správnom kontexte.

Rozsah medzinárodnej slovnej zásoby je obmedzený a pre mnohé každodenné pojmy nepomôže. Okrem toho sú ľudia, ktorí to jednoducho _neradi_ používajú v slovanskom jazyku. Z tohto dôvodu sa snažíme poskytnúť aj všeobecne zrozumiteľné slovanské alternatívy. To však nie je vždy možné. Napríklad niektoré slovanské národy používajú latinské názvy mesiacov, iné zasa slovanské. Tie sú oveľa menej jednotné: _listopad_ znamená v poľštine „november“ a v chorvátčine „október“ (typický príklad falošného priateľa), zatiaľ čo iba Bielorus vie povedať, ktorý mesiac znamená _`kastryčnik`_. Preto so slovanskými ekvivalentmi medzinárodných slov treba zaobchádzať opatrne.

Medzinárodná slovná zásoba sa preberá iba vtedy, ak sa používa vo väčšine slovanských jazykov. Interslovanská používa určité pevné mechanizmy na jej požičiavanie, ktoré možno nájsť v [špeciálnej sekcii][1].

Pokiaľ ide o bežnú zdedenú (slovanskú) slovnú zásobu, musíme urobiť tri veci: vybrať slová a korene slov, stanoviť pre ne správnu formu a priradiť im základný význam.

### Ktoré korene použiť? \{#which-roots-to-use}

Keď je potrebné nové slovo, začneme s inventarizáciou slov, ktoré na to používajú rôzne slovanské jazyky. V závislosti od výsledku robíme toto:

- Keď nejaký koreň slova existuje vo všetkých slovanských jazykoch v rovnakom význame, je to jednoduché: vďačne si ho osvojujeme.
- Keď sa rozchádza len jeden alebo dva jazyky, robíme to isté.
- Keď sa dajú rozlíšiť dve alebo viac skupín, každá na základe iného slovanského koreňa, postupujeme takto:
  1. pre každý z týchto koreňov hľadáme príbuzné jazyky v zostávajúcich jazykoch spolu s ich významom,
  2. následne robíme to isté pre tieto korene a významy, čím vytvárame „sémantické rodiny“,
  3. nakoniec vyberieme tie slová, ktoré sa vyskytujú vo všetkých alebo vo väčšine jazykov, a priradíme im tie „priemerné“ významy.
- Ak ani to nefunguje, máme niekoľko možností:
  1. vyberieme slovo, ktoré sa vyskytuje vo väčšine jazykov
  2. analyzujeme, ktoré slová sú intuitívne zrozumiteľnejšie ako iné, aj keď sa používajú iba v jednom jazyku
  3. vytvárame synonymá
  4. väčším a známejším jazykom dávame prevahu nad menšími
  5. hľadáme „medzinárodný“ ekvivalent
  6. niečo „nastrojíme“.

Pri uplatňovaní tohto procesu sa so všetkými tromi podrodinami (východná, západná a juhoslovanská) zaobchádza rovnako. Dôsledne sa vyhýbame uprednostňovaniu jedného jazyka pred druhým, čo nie je vždy jednoduché, pretože jeden jazyk (ruština) je oveľa väčší ako všetky ostatné, pokiaľ ide o osoby, ktorými hovoria, a niekoľko menších jazykov (ako srbčina, bosniančina a chorvátčina) je si navzájom veľmi podobné. iné, že by sa mohli ľahko považovať za dialekty jedného jazyka. Aby sme dosiahli spravodlivé zaobchádzanie s jazykmi pri zvažovaní ich vstupov, používame systém šiestich podskupín a každá z týchto podskupín má jeden „hlas“:

- ruský
- ukrajinský a bieloruský
- poľský
- český a slovenský
- slovinčina a srbčina/chorvátčina/bosniančina
- bulharčina a macedónčina

Ak sa dva jazyky v rámci jednej skupiny nezhodnú na jednom slove, ½ hlasu dostane jeden a ½ hlasu druhý. Ak majú dve kandidátske slová rovnaký počet hlasov, rozhoduje obyvateľstvo. Prakticky to znamená, že ruština vždy vyhrá, čo je rozumné vzhľadom na skutočnosť, že asi 70 % Slovanov tento jazyk ovláda.

Z praktických dôvodov sa na hlasovaní nezúčastňujú jazyky, ktoré hovoria menej ako miliónom ľudí, ako napríklad lužická srbčina, kašubčina a rusínčina. To však neznamená, že sa vôbec neberú do úvahy.

[hlasovacie zariadenie][2] je nástroj, ktorý tieto pravidlá uplatňuje. Treba poznamenať, že tieto pravidlá sú myslené ako všeobecný trend; keď je iné riešenie zjavne lepšie, vždy by mal zvíťaziť zdravý rozum.

### Falošní priatelia \{#false-friends}

Individuálny vývoj slovanských slov v rôznych jazykoch, vrátane niekedy vážneho posunu významu, viedol k existencii mnohých podobne vyzerajúcich slov s úplne odlišným významom v rôznych jazykoch. Tieto slová sú známe ako „falošní priatelia“ a pekný – aj keď neúplný – [prehľad nájdete v anglických Wikibooks][3]. Hoci sa im nemožno vždy vyhnúť, s týmito slovami by sa malo zaobchádzať opatrne.

Malý rozdiel vo význame medzi jazykmi by nemal byť nevyhnutne problémom (napr. :isv[ljubiti] znamená „milovať“ vo väčšine slovanských jazykov, ale „milovať“ v poľštine). Naozaj veľké rozdiely vo význame len zriedka spôsobujú problémy, najmä ak patria do rôznych kategórií slov (napr. _`pet` \~ `peť` \~ `peć` \~ `piec`_, nesúce významy ako „päť“, „rúra“ , „ohorok cigarety“ a „spievať“). V oboch prípadoch je pravdepodobnosť nedorozumení malá. Falošní priatelia sú problematickí iba vtedy, keď sa slovo, napriek veľkému rozdielu vo význame, môže stále používať v rovnakom alebo podobnom kontexte, a preto ho Slovania rôznych národností môžu chápať odlišne. Príkladom je už spomínané slovo _`listopad`_, ktoré v poľštine/češtine znamená „november“ a v chorvátčine „október“. Je zrejmé, že takýmto slovám by sa malo v interslovanských textoch vyhnúť.

### Neologizmy \{#neologisms}

V kontexte interslovančiny sú neologizmy slová, ktoré ako také neexistujú v žiadnom zo živých slovanských jazykov. Príkladom takýchto slov sú slová portmanteau (napríklad :isv[katka] „kačica“, z Ru. :isv[utka], poľ. :isv[kaczka], južnoslovanské :isv[patka]), kalky z neslovanských jazykov (napríklad :isv[kolokrěslo] „vozičkár“), kombinácie medzislovanských slovných koreňov s medzislovanskými príponami, ktoré sa v slovanskom jazyku nevyskytujú (napríklad _`gradnik`_ „mešťan, občan“), a slová s popisnejším charakterom v prípadoch, keď nie je možné nájsť široko zrozumiteľné slovanské slovo.

Názory sa rôznia na mieru, do akej sú umelo vytvorené slová prijateľné v interslovančine; niektorí ľudia ich milujú, iní ich nenávidia. V slovníku sa neologizmom vyhýbame, pokiaľ žiadny zo živých slovanských jazykov neposkytuje slovo, ktoré je zrozumiteľné pre širšie publikum a ostatní ho nepochopia. Príkladom je :isv[časina] „hodina“ (stará cirkevná slovančina obsahuje dve slová: _`čas`_ a :isv[godina], ale prvé znamená v západoslovančine „čas“, druhé znamená v južnoslovančine „rok“, zatiaľ čo srbčina -Chorvátske slovo _`sat`_ je turecké slovo, ktoré nie je iným Slovanom vôbec zrozumiteľné).

### Ako vytvoriť správnu formu pre koreň? \{#how-to-establish-the-right-form-for-a-root}

Keď už vieme, ktoré slovo použijeme, ďalším krokom je stanovenie toho, ako by malo presne vyzerať. V prvom rade musí existovať vnútorná konzistencia: vždy, keď sa v zlúčenine vyskytne určitý koreň alebo morféma, mala by mať rovnakú formu, bez ohľadu na to, z akého konkrétneho jazyka je táto zlúčenina prevzatá. Aby sa medzislovančina nestala zmesou slov vybraných z rôznych jazykov, slová sa nikdy nepožičiavajú priamo zo žiadneho slovanského jazyka.

Namiesto toho sa vrátime k hypotetickej forme v praslovančine, ktorú často môžeme nájsť v jej blízkej príbuznej staroslovienčine, a následne ju podrobíme [modelu pre jednoduché odvodenie][4]. To nielenže zaručuje súdržnosť, ale tiež zlepšuje zrozumiteľnosť a uľahčuje učenie, pretože fonologický vývoj moderných slovanských jazykov z praslovančiny má tendenciu byť mimoriadne pravidelný: keď človek vie, ako je daný zvuk v jeho vlastnom jazyku reprezentovaný v Medzislovančina – čo veľmi rýchlo zistí prečítaním niekoľkých textov – dokáže slová nielen ľahko rozpoznať, ale aj predvídať bez toho, aby musel kontrolovať slovník.

Napríklad bežné slovanské sekvencie `tj/dj` sa stávajú `č/ž` vo východoslovančine, `c/dz` v poľštine, `c/z` v česko-slovenskom jazyku, `č/j` v slovinčine, `ć/đ` v srbochorvátčine, `ḱ/ǵ` v macedónsky a `št/žd` v bulharčine. Najlepším kompromisom je tu pravdepodobne `č/dž` (napr. :isv[svěča] „sviečka“ a _`medžu`_ „medzi“), čo má ďalšiu výhodu v tom, že to druhé je zneným ekvivalentom prvého, a teda vytvára symetriu.

Pre ilustráciu toho, ako to všetko funguje, si môžete pozrieť [tu][5], ako osobné zámená v interslovančine vychádzajú z tých v prirodzených slovanských jazykoch.

## Gramatika \{#grammar}

Čo platí pre slovnú zásobu, platí aj pre gramatiku. Východiskom sú vždy gramatické prvky, ktoré majú slovanské jazyky spoločné. Konečný výsledok však do veľkej miery závisí od účelu a okolností, na ktoré sa Interslovan používa. Optimalizácia zrozumiteľnosti automaticky sťažuje rečníkovi alebo pisateľovi, zatiaľ čo vďaka zjednodušenej gramatike je jazyk menej prirodzený, a preto je ťažšie porozumieť. Aby sme sa s tým vyrovnali, rozlišujeme dve rôzne gramatické úrovne. Ktorý z nich je na aký účel výhodnejší, závisí od hovoriaceho, poslucháča, média a situácie. V ideálnom prípade by úroveň 1 mala byť podmnožinou úrovne 2, aby sa učiaci sa mohol postupne posunúť vpred bez toho, aby jeho predtým získané vedomosti boli znehodnotené.

### Jednoduchá úroveň \{#simple-level}

Najjednoduchšia forma interslovančiny, `Slovianto`, nie je v skutočnosti jazykom, ale skôr metódou, ktorú môžu používať Neslovania ako metódu učenia a/alebo používania interslovančiny. Pozostáva z troch rôznych úrovní, z ktorých každá približuje učiaceho sa „skutočnej“ medzislovančine.

Prvá úroveň je minimalistická, primitívna gramatika, ktorá sa vyznačuje absenciou všetkého, čo nie je skutočne potrebné pre jednoduchú komunikáciu. Gramatický rod na tejto úrovni nehrá rolu, chýbajú pády podstatných mien a slovesná konjugácia zostáva obmedzená na nevyhnutné minimum. Tých pár tvarov, ktoré zostali (napríklad množné číslo), by malo byť pre Slovanov rozoznateľných bez akéhokoľvek predchádzajúceho štúdia a ich zapamätanie by malo byť skôr otázkou minút ako hodín. Táto úroveň je užitočná najmä pre Neslovanov, ktorí nemajú záujem naučiť sa celý jazyk, no napriek tomu chcú mať možnosť vyjadrovať sa na základnej úrovni v kontaktoch so Slovanmi.

Druhá úroveň predstavuje gramatický rod a poskytuje jednoduchý model na spojovanie slovies. Tretia úroveň zavádza pády podstatných mien.

### Pokročilá úroveň \{#advanced-level}

„Skutočná“ medzislovančina je primárne určená pre Slovanov, ale aj Neslovanov, ktorí chcú komunikovať na serióznejšej úrovni. Táto úroveň je založená na spoločných znakoch slovanských jazykov. Má teda gramatický rod (prítomný vo všetkých slovanských jazykoch), sedem pádov (prítomný vo všetkých slovanských jazykoch okrem bulharčiny a macedónčiny), verbálny aspekt a plnú konjugáciu slovies. Slovanské jazyky sú však povestné svojou zložitou gramatikou a aby sme sa vyhli nekonečným tabuľkám s nominálnymi a verbálnymi paradigmami, stále je potrebné veľké zjednodušenie. Aby sme našli správnu rovnováhu medzi naturalizmom a jednoduchosťou, snažíme sa čo najpresnejšie priblížiť prirodzene existujúcim formám použitím čo najjednoduchších prostriedkov. Nepravidelnosti sa zabráni, pokiaľ nie je vážne ohrozená ľahká rozpoznateľnosť. Vyhýba sa aj umelosti.

Najdôležitejšie je, že každá gramatická koncovka je okamžite rozpoznateľná, aj keď skloňovaná forma slova vyzerá v cudzom jazyku inak. Napríklad väčšina slovanských jazykov môže mať rôzne koncovky pre genitív jednotného čísla podstatného mena mužského rodu, ale jednu koncovku majú všetky spoločnú: `-a`, ktorá je teda riešením pre všetky výskyty tejto formy. V prípade slovies sa početné slovesné triedy, ktoré existujú v slovanskom jazyku, zredukovali na jednoduchý systém dvoch kmeňov, infinitívneho kmeňa a kmeňa prítomného času. To druhé je takmer vždy logickým výsledkom prvého a len v niekoľkých prípadoch sa musia učiť samostatne. Vďaka tomuto prístupu sa dosiahne veľa zjednodušení bez obetovania naturalistického charakteru jazyka.

Táto úroveň je vhodná na kontakty a publikácie, ale aj ako prostriedok na nahliadnutie do podstaty slovančiny.

[1]: ../vocabulary/derivation.md

[2]: http://steen.free.fr/interslavic/voting_machine.html

[3]: http://en.wikibooks.org/wiki/False_Friends_of_the_Slavist

[4]: ../vocabulary/derivation.md#proto-slavic

[5]: http://steen.free.fr/interslavic/slavic_pronouns.html

