---
sidebar_position: 3
license: republish
author: Jan van Steenbergen
custom_edit_url: /501
origin: http://steen.free.fr/interslavic/design-criteria.html
---

# Kriterij dizajna

Međuslavenski se temelji na zajedničkom naslijeđu svih slavenskih naroda, a razlike se premošćuju građenjem kompromisa. Svi se slavenski jezici tretiraju jednako, iako se ne može izbjeći da je slavenski međujezik bliži jezicima „srednje razine“ poput slovačkog ili rusinskog nego perifernim jezicima poput lužičkosrpskog ili makedonskog. Međuslavenski jezik izričito nije zamišljen kao „slavenskiji od Slavena“ pročišćavanjem od stranih utjecaja, iako će jezik koji se temelji na sličnostima slavenskih jezika ionako automatski eliminirati mnoge lokalne (neslavenske) utjecaje. Nema, međutim, razloga za isključivanje internacionalnog rječnika, pod uvjetom da ga mogu prepoznati svi, ili barem većina, slavenskih govornika.

Primarna svrha međuslavenskog jezika, maksimalna razumljivost za sve Slavene, postiže se sustavnim pružanjem najvećeg zajedničkog nazivnika slavenskih jezika, kako u smislu gramatike, pravopisa, sintakse, tako i vokabulara. Kada se ne može pronaći zajedničko rješenje, gradimo kompromis. Ako je čak i kompromis nemoguć, moramo se odlučiti ili jednostavno predložiti oba rješenja.

Sekundarna namjena je da ga se može lako naučiti i koristiti prvenstveno Slavenima, ali i neslavenima. Očito je nemoguć slavenski jezik s gramatikom koja se sastoji od deset jednostavnih pravila. Ipak, nastojimo zadržati gramatiku što je moguće jednostavnijom i pravilnom, bez žrtvovanja slavenskog karaktera jezika.

Ovaj odjeljak detaljno opisuje kako se postižu ove dvije svrhe.

## Fonologija i pisanje \{#phonology-and-writing}

Osnovna načela dizajna u vezi s fonologijom i pisanjem su sljedeća:

- Govornicima slavenskih jezika u pravilu bi oba trebala biti što poznatija. Stoga radimo s ograničenim brojem zvukova i izbjegavamo uključivanje neslavenskih elemenata.
- Svatko bi trebao moći pisati međuslavenski na svojoj tipkovnici, bez ikakvih posebnih naprava i tako da se osjeća prirodno.
- Budući da podjela između latinice i ćirilice prolazi sredinom slavenskog teritorija, oba se tretiraju ravnopravno.
- Nismo preskriptivisti što se tiče izgovora. Dajemo samo osnovnu naznaku, a za ostalo svatko bi trebao izgovarati međuslavenski na način koji mu je udoban i prirodan. Nijedan izgovor nije „ispravniji“ od drugog. Isto tako, naglasak riječi je besplatan.

U idealnom slučaju, mora biti moguće pisati međuslavenski na bilo kojoj slavenskoj tipkovnici. Međutim, postoji jedan problem: ove su tipkovnice dizajnirane da odgovaraju standardnim nacionalnim pravopisima, a svaki od tih pravopisa prilagođen je potrebama određenog jezika. Otprilike polovica slavenskih jezika koristi latinicu, druga polovica je napisana ćirilicom, a oba alfabeta postoje u dvije međusobno isključive verzije: češki, slovački, slovenski i hrvatski koriste latinicu s `v`, `š`, `ž`  itd., poljski s @ @81 Ruski, ukrajinski, bjeloruski i bugarski koriste ćirilicu s `й`, `ь`, `ю`,  srpskim i makedonskim s `ј`, `љ`  i `џ`. Nije na nama da odlučimo je li jedan način „bolji“ ili „slavenskiji“ od drugog. Osim toga, svaki bi se Slaven trebao osjećati ugodno pišući međuslavenski, pa moramo živjeti s činjenicom da se on može pisati na razne načine.

Budući da su :isv[końe], :isv[koňe], :isv[konje], :isv[konie]  i _`kone`_ samo različiti, prirodni načini pisanja iste riječi, nema puno smisla raspravljati o tome koja bi verzija trebala biti "službena", jer bi svaki takav izbor automatski učinio druge verzije "neslužbenima" “ pa samim time i „pogrešno“ ili barem „nestandardno“. Stoga slijedimo potpuno drugačiji pristup: umjesto odabira bilo koje vrste službenog pravopisa, radimo s **prototipom pravopisa**. Pod pretpostavkom da se sva različita rješenja koja se koriste u nacionalnim pravopisima odnose na jedan **prototip**, smatramo da je i ovaj prototip najbolji način predstavljanja međuslavenskog. Budući da se radi o dva potpuno različita pisma (latinici i ćirilici), ne možemo izbjeći postojanje jednog prototipa pravopisa za svako od njih.

U idealnom slučaju, oba prototipa bi trebala imati sljedeće karakteristike:

- moraju biti intuitivno razumljivi svakome tko zna čitati dotičnu abecedu
- moraju biti logični, dosljedni, nedvosmisleni i etimološki ispravni
- moraju dati pristojnu aproksimaciju pravog izgovora
- ako je moguće, jedan fonem (glas) = jedan znak
- trebaju biti kompatibilni (jednostavna transliteracija, po mogućnosti jedna na bazi 1:1)
- ne smiju sadržavati neprirodne elemente
- ne smiju biti ružni ili na bilo koji drugi način uvredljivi (kao na primjer `йа` ili `łi`), ali ne smiju biti ograničeni na specifičnosti bilo kojeg nacionalnog jezika
- ispravno se prikazuju na prosječnom zaslonu računala, stoga treba izbjegavati znakove iz neobičnih skupova znakova, kombiniranje dijakritika i slično.

Budući da niti jedan od postojećih slavenskih pravopisa ne može ispuniti sve ove zahtjeve, razlikujemo osnovnu abecedu koja se sastoji od fonema koji se mogu naći u svakom slavenskom jeziku i niza izbornih proširenja koja se mogu koristiti kao sredstvo za jasniji izgovor , etimologija itd.

## Rječnik \{#vocabulary}

### Internacionalni naspram Ẑlavskog vokabulara \{#international-versus-ѕlavic-vocabulary}

U idealnom slučaju, svaka riječ mora izgledati poznata svakom govorniku slavenskog jezika. Čak i ako se određeni oblik riječi ne pojavljuje u nečijem vlastitom jeziku, trebao bi barem izazvati konotaciju koja im daje nagovještaj u pravom smjeru. Očito, to nije uvijek moguće, pa je stoga potrebno nekoliko mehanizama za odlučivanje o odabiru vokabulara. Prvi i najvažniji korak je prikupljanje niza korijena riječi koji su prepoznatljivi svim ili većini Slavena. Poslije ti korijeni mogu poslužiti kao osnova za proširivanje rječnika građenjem složenica.

Postoje dvije vrste vokabulara koje igraju ključnu ulogu u poboljšanju međusobnog razumijevanja između dva različita jezika:

- međunarodni vokabular, riječi koje su uobičajene u mnogim, čak i nesrodnim jezicima. Većina je posuđena izravno ili neizravno iz latinskog i grčkog (_`filozofija`, `universitet`, `material`, `motor`_), ponekad dolazi iz drugih jezika (_`bjuro`, `fajl`, `jaguar`, `čaj`, `šokolad`_), u rijetkim slučajevima čak i iz samog slavenskog (_`vampir`, `vodka`_)
- zajednički naslijeđeni vokabular, drugim riječima, rječnik koji su oba jezika naslijedila od zajedničkog pretka, u ovom konkretnom slučaju praslavenskog

Internacionalne riječi sastavni su dio svakog slavenskog jezika. Njihova je prednost u tome što su u različitim jezicima praktički identični, kako oblikom tako i značenjem, pa su stoga izvrsno rješenje za međuslavenski, osobito za obrazovanije. U slučaju naslijeđenog vokabulara situacija je nešto složenija, jer je svaki jezik prošao kroz svoj karakterističan razvoj, pa kao rezultat toga, riječ u jednom jeziku možda neće odmah biti prepoznatljiva govornicima drugog, čak i ako se radi o vrlo ista riječ. Usporedite primjerice poljski :isv[węgiel] i slovački :isv[uhlie] „ugljen“. Osim toga, u nekoliko slučajeva njihova su se značenja toliko udaljila jedno od drugog (npr. _`duma`_, što znači "misao" na ruskom i "ponos" na poljskom) da se mogu smatrati _lažnim prijateljima_, tj. riječima koje se lako mogu pogrešno shvaćen čak iu pravom kontekstu.

Opseg međunarodnog vokabulara je ograničen i neće biti od pomoći za mnoge svakodnevne pojmove. Osim toga, postoje ljudi koji jednostavno _ne vole_ koristiti ga u slavenskom. Iz tog razloga nastojimo ponuditi i široko razumljive slavenske alternative. To ipak nije uvijek moguće. Na primjer, neki slavenski narodi koriste latinske nazive mjeseci, dok drugi koriste slavenske nazive. Potonji su mnogo manje jednoobrazni: _listopad_ znači „studeni“ na poljskom, a „listopad“ na hrvatskom (tipičan primjer lažnog prijatelja), dok samo Bjelorus zna na koji se mjesec misli pod _`kastryčnik`_. Stoga sa slavenskim ekvivalentima internacionalnih riječi treba postupati s oprezom.

Međunarodni vokabular usvaja se samo ako se koristi u većini slavenskih jezika. Međuslavenski jezik primjenjuje određene ustaljene mehanizme za njegovo posuđivanje, koji se mogu pronaći u [posebnom odjeljku][1].

Kad je riječ o zajedničkom naslijeđenom (slavenskom) vokabularu, trebamo učiniti tri stvari: odabrati riječi i korijene riječi, utvrditi im pravi oblik i dodijeliti im osnovno značenje.

### Koje korijene koristiti? \{#which-roots-to-use}

Kada je potrebna nova riječ, počinjemo s popisom riječi koje za nju koriste različiti slavenski jezici. Ovisno o rezultatu, radimo sljedeće:

- Kad korijen riječi postoji u svim slavenskim jezicima u istom značenju, lako je: sa zahvalnošću ga usvajamo.
- Kad se samo jedan ili dva jezika raziđu, mi činimo isto.
- Kada se mogu razlikovati dvije ili više skupina, svaka na temelju različitog slavenskog korijena, postupamo na sljedeći način:
  1. za svaki od tih korijena tražimo srodne riječi u preostalim jezicima, zajedno s njihovim značenjima,
  2. naknadno, činimo isto za te korijene i značenja, stvarajući tako „semantičke obitelji“,
  3. konačno, odabiremo one riječi koje se pojavljuju u svim ili većini jezika i pripisujemo im najprosječnija značenja.
- Ako ni to ne uspije, imamo nekoliko opcija:
  1. biramo riječ koja se pojavljuje u većini jezika
  2. analiziramo koje su riječi intuitivno razumljivije od drugih, čak i ako se koriste samo u jednom jeziku
  3. stvaramo sinonime
  4. većim i poznatijim jezicima dajemo prednost nad manjim
  5. tražimo „međunarodni“ ekvivalent
  6. nešto „projektiramo“.

U primjeni ovog procesa sve tri potporodice (istočna, zapadna i južnoslavenska) tretiraju se na ravnopravnoj osnovi. Pažljivo izbjegavamo favorizirati jedan jezik u odnosu na drugi, što nije uvijek lako, jer je jedan jezik (ruski) uvelike veći od svih ostalih u smislu govornika, a nekoliko manjih jezika (poput srpskog, bosanskog i hrvatskog) tako je međusobno slično drugo da bi se lako mogli tretirati kao dijalekti jednog jezika. Kako bismo postigli pravičan tretman jezika u vaganju njihovog unosa, koristimo sustav od šest podskupina, a svakoj od tih podskupina daje se jedan „glas“:

- ruski
- ukrajinski i bjeloruski
- poljski
- češki i slovački
- slovenski i srpski/hrvatski/bosanski
- bugarski i makedonski

Ako se dva jezika unutar jedne skupine ne slažu oko riječi, ½ glasa daje se jednom, a ½ glasa drugom. Ako dvije riječi kandidata imaju isti broj glasova, odlučuje stanovništvo. To praktično znači da ruski uvijek pobjeđuje, što je i logično s obzirom na to da oko 70% Slavena zna taj jezik.

Iz praktičnih razloga, jezici s manje od milijun govornika, poput lužičkosrpskog, kašupskog i rusinskog, ne sudjeluju u procesu glasovanja. No to ne znači da se uopće ne uzimaju u obzir.

[Stroj za glasanje][2] je alat koji primjenjuje ova pravila. Treba napomenuti da su ova pravila namijenjena kao opći trend; kad je drugo rješenje očito bolje, uvijek treba prevladati zdrav razum.

### Lažni prijatelji \{#false-friends}

Individualni razvoj slavenskih riječi u raznim jezicima, uključujući ponekad i ozbiljne promjene u značenju, doveo je do postojanja mnogih riječi sličnog izgleda s potpuno različitim značenjima u različitim jezicima. Ove su riječi poznate kao „lažni prijatelji“, i lijep – iako nepotpun – [pregled se može naći u engleskim Wikiknjigama][3]. Iako se ne mogu uvijek izbjeći, s ovim riječima treba pažljivo postupati.

Mala razlika u značenju među jezicima ne bi trebala nužno predstavljati problem (npr. :isv[ljubiti] znači "voljeti" u većini slavenskih jezika, ali "voljeti" u poljskom). Stvarno velike razlike u značenju također rijetko uzrokuju probleme, posebno kada pripadaju različitim kategorijama riječi (npr. _`pet` \~ `peť` \~ `peć` \~ `piec`_, noseći značenja poput „pet“, „pećnica“ , „opušak“ i „pjevati“). U oba slučaja šanse za nesporazume su male. Lažni prijatelji su problematični samo kada se riječ, usprkos ozbiljnoj razlici u značenju, još uvijek može koristiti u istom ili sličnom kontekstu i stoga je vjerojatno da će je Slaveni različitih nacionalnosti različito razumjeti. Primjer je spomenuta riječ _`listopad`_, koja na poljskom/češkom znači „studeni“, a na hrvatskom „listopad“. Očito je da takve riječi treba izbjegavati u međuslavenskim tekstovima.

### Neologizmi \{#neologisms}

U međuslavenskom kontekstu neologizmi su riječi koje kao takve ne postoje ni u jednom od živih slavenskih jezika. Primjeri takvih riječi su portmanto riječi (na primjer :isv[katka] „patka“, iz ru. :isv[utka], polj. :isv[kaczka], južnoslavenski :isv[patka]), kalkovi iz neslavenskih jezika (na primjer :isv[kolokrěslo] „invalidska kolica“), kombinacije međuslavenskih korijena riječi s međuslavenskim afiksima koji ne postoje u slavenskom jeziku (na primjer _`gradnik`_ „stanovnik grada, građanin“), te riječi s više opisnog karaktera u slučajevima kada je nemoguće naći široko razumljivu slavensku riječ.

Mišljenja su različita o stupnju u kojemu su umjetno stvorene riječi prihvatljive u međuslavenskom; neki ih ljudi vole, drugi ih mrze. U rječniku nastojimo izbjegavati neologizme, osim ako nijedan od živih slavenskih jezika ne nudi riječ koja je razumljiva široj publici i koju drugi neće krivo razumjeti. Primjer je :isv[časina] „sat“ (starocrkvenoslavenski nudi dvije riječi: _`čas`_ i :isv[godina], ali prva znači „vrijeme“ na zapadnoslavenskom, potonja znači „godina“ na južnoslavenskom, dok srb. -Hrvatska riječ _`sat`_ je turska riječ koja ostalim Slavenima uopće nije razumljiva).

### Kako uspostaviti pravi oblik za korijen? \{#how-to-establish-the-right-form-for-a-root}

Nakon što znamo koju ćemo riječ koristiti, sljedeći korak je utvrđivanje kako bi ona točno trebala izgledati. Prvo i najvažnije, mora postojati unutarnja dosljednost: kad god se određeni korijen ili morfem pojavi u složenici, trebao bi imati isti oblik, bez obzira iz kojeg jezika je ta složenica preuzeta. Da se spriječi da međuslavenski jezik postane mješavina riječi odabranih iz raznih jezika, riječi se nikada ne posuđuju izravno iz bilo kojeg slavenskog jezika.

Umjesto toga, vraćamo se na hipotetski oblik u praslavenskom, koji se često može naći u njegovom bliskom srodnom starocrkvenoslavenskom, i naknadno ga podvrgavamo [modelu za jednostavno izvođenje][4]. Ovo ne samo da jamči koherentnost, već također poboljšava razumljivost i olakšava učenje, jer fonološki razvoj suvremenih slavenskih jezika od praslavenskog ima tendenciju da bude izuzetno pravilan: kada osoba zna kako je određeni glas u njegovom jeziku predstavljen u Interslavic – što će vrlo brzo saznati čitanjem nekoliko tekstova – moći će ne samo lako prepoznati riječi, nego ih i predvidjeti bez provjere rječnika.

Na primjer, zajedničkoslavenski nizovi `tj/dj` postaju `č/ž` na istočnoslavenskom, `c/dz` na poljskom, `c/z` na češko-slovačkom, `č/j` na slovenskom, `ć/đ` na srpskohrvatskom, `ḱ/ǵ` na makedonski i `št/žd` na bugarski. Najbolji kompromis ovdje je vjerojatno `č/dž` (npr. :isv[svěča] „svijeća“ i _`medžu`_ „između“), koji ima dodatnu prednost što je potonji zvučni ekvivalent prvome i tako stvara simetriju.

Za ilustraciju kako sve ovo funkcionira, možete vidjeti [ovdje][5] kako se osobne zamjenice u međuslavenskom jeziku temelje na onima u prirodnim slavenskim jezicima.

## Gramatika \{#grammar}

Ono što vrijedi za vokabular vrijedi i za gramatiku. Uvijek se polazi od gramatičkih elemenata koji su zajednički slavenskim jezicima. Međutim, krajnji rezultat uvelike ovisi o svrsi i okolnostima za koje se Interslavic koristi. Optimiziranje razumljivosti automatski otežava govorniku ili piscu, dok pojednostavljenija gramatika čini jezik manje prirodnim i stoga težim za razumijevanje. Kako bismo se nosili s tim, razlikujemo dvije različite gramatičke razine. Koji je poželjniji za koju svrhu ovisi o govorniku, slušatelju, mediju i situaciji. U idealnom slučaju, razina 1 trebala bi biti podskup razine 2, tako da učenik može postupno napredovati bez da se njegovo prethodno stečeno znanje poništi.

### Jednostavna razina \{#simple-level}

Najjednostavniji oblik međuslavenskog jezika, `Slovianto`, zapravo nije jezik, već prije metoda koju neslaveni mogu koristiti kao metodu za učenje i/ili korištenje međuslavenskog jezika. Sastoji se od tri različite razine, od kojih svaka približava učenika „pravom“ međuslavenskom.

Prva razina je minimalistička, primitivna gramatika koju karakterizira odsutnost svega što zapravo nije potrebno za jednostavnu komunikaciju. Gramatički rod ne igra ulogu na ovoj razini, padeži imenica su odsutni, a verbalna konjugacija ostaje ograničena na minimum. Ono malo preostalih oblika (na primjer, množina) trebalo bi biti prepoznatljivo za Slavene bez prethodnog proučavanja, a njihovo pamćenje trebalo bi biti pitanje minuta, a ne sati. Ova razina je posebno korisna za neslavene koji nisu zainteresirani za učenje cijelog jezika, ali ipak žele biti u mogućnosti da se izraze na osnovnoj razini u kontaktu sa Slavenima.

Druga razina uvodi gramatički rod i daje jednostavan model za konjugiranje glagola. Treća razina uvodi padeže imenica.

### Napredna razina \{#advanced-level}

„Pravi“ međuslavenski prvenstveno je namijenjen Slavenima, ali i neslavenima koji žele imati mogućnost komuniciranja na ozbiljnijoj razini. Ova se razina temelji na sličnostima slavenskih jezika. Dakle, ima gramatički rod (prisutan u svim slavenskim jezicima), sedam padeža (prisutan u svim slavenskim jezicima osim bugarskog i makedonskog), verbalni aspekt i punu konjugaciju glagola. Međutim, slavenski jezici poznati su po svojim složenim gramatikama, a kako bi se izbjegle beskonačne tablice s nominalnim i verbalnim paradigmama, još uvijek je potrebno mnogo pojednostavljenja. Kako bismo pronašli dobru ravnotežu između naturalizma i jednostavnosti, nastojimo što je moguće bliže približiti prirodno postojeće forme koristeći najlakša moguća sredstva. Nepravilnosti se izbjegavaju, osim ako laka prepoznatljivost nije ozbiljno ugrožena. Izbjegnuta je i umjetnost.

Najvažnije je da je svaki gramatički završetak odmah prepoznatljiv, čak i ako nagnuti oblik riječi izgleda drugačije na nečijem vlastitom jeziku. Na primjer, većina slavenskih jezika može imati različite nastavke za genitiv jednine imenice muškog roda, ali postoji jedan zajednički završetak: `-a`, koji je stoga rješenje za sve pojave ovog oblika. U slučaju glagola, brojni glagolski razredi koji postoje u slavenskom jeziku svedeni su na jednostavan sustav od dvije osnove, infinitivne osnove i osnove sadašnjeg vremena. Potonji je gotovo uvijek logičan rezultat prvog, a samo u nekoliko slučajeva moraju se učiti zasebno. Zahvaljujući ovom pristupu, postiže se puno pojednostavljenja bez žrtvovanja naturalističkog karaktera jezika.

Ova je razina prikladna za kontakte i publikacije, ali i kao sredstvo za stjecanje uvida u prirodu slavenskog jezika.

[1]: ../vocabulary/derivation.md

[2]: http://steen.free.fr/interslavic/voting_machine.html

[3]: http://en.wikibooks.org/wiki/False_Friends_of_the_Slavist

[4]: ../vocabulary/derivation.md#proto-slavic

[5]: http://steen.free.fr/interslavic/slavic_pronouns.html

