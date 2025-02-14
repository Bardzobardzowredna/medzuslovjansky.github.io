---
sidebar_position: 3
license: republish
author: Jan van Steenbergen
custom_edit_url: /501
origin: http://steen.free.fr/interslavic/design-criteria.html
---

# Kriterijumi dizajna

Međuslavensko je zasnovano na zajedničkom naslijeđu svih slovenskih naroda, a razlike se premošćuju izgradnjom kompromisa. Svi slovenski jezici se tretiraju jednako, iako se ne može izbjeći da je slavenski međujezik bliži „srednjim“ jezicima poput slovačkog ili rusinskog nego perifernim jezicima kao što su lužički ili makedonski. Interslavenski jezik izričito ne treba da bude „više slavenski od Slovena“ tako što ga pročišćava od stranih uticaja, iako će jezik zasnovan na zajedničkim karakteristikama slovenskih jezika ionako automatski eliminisati mnoge lokalne (neslovenske) uticaje. Međutim, nema razloga za isključivanje međunarodnog rječnika, pod uvjetom da ga mogu prepoznati svi, ili barem većina, slavenski govornici.

Primarna svrha međuslavenskog jezika, maksimalna razumljivost za sve Slovene, postiže se sistematskim davanjem najvećeg zajedničkog nazivnika slovenskih jezika, kako u pogledu gramatike, pravopisa, sintakse, tako i vokabulara. Kada se ne može naći zajedničko rješenje, pravimo kompromis. Ako je čak i kompromis nemoguć, moramo napraviti izbor ili jednostavno predložiti oba rješenja.

Sekundarna svrha je da ga mogu lako naučiti i koristiti, prvenstveno Slaveni, ali i ne-Sloveni. Očigledno je da je slovenski jezik sa gramatikom koja se sastoji od deset jednostavnih pravila nemoguć. Ipak, trudimo se da gramatika bude što jednostavnija i pravilnija, bez žrtvovanja slavenskog karaktera jezika.

Ovaj dio detaljno opisuje kako se ove dvije svrhe postižu.

## Fonologija i pisanje \{#phonology-and-writing}

Osnovni principi dizajna koji se odnose na fonologiju i pisanje su sljedeći:

- Po pravilu, i jedno i drugo treba da bude što bliže govornicima slovenskih jezika. Stoga radimo sa ograničenim brojem zvukova i izbjegavamo ugrađivanje neslavenskih elemenata.
- Svako treba da može da piše interslavenski na svojoj tastaturi, bez ikakvih posebnih gadžeta i na način da izgleda prirodno.
- Pošto se podela između latinice i ćirilice proteže sredinom slovenske teritorije, obe se tretiraju jednako.
- Nismo preskriptivisti u pogledu izgovora. Dajemo samo osnovnu naznaku, a za ostalo, svako bi trebao izgovarati međuslavenski na način koji mu je ugodan i prirodan. Nijedan izgovor nije „ispravniji“ od drugog. Isto tako, naglasak je besplatan.

U idealnom slučaju, mora biti moguće pisati interslavenski na bilo kojoj slavenskoj tastaturi. Međutim, postoji jedan problem: ove su tastature dizajnirane da odgovaraju standardnim nacionalnim pravopisima, a svaki od tih pravopisa je prilagođen potrebama određenog jezika. Otprilike polovina slovenskih jezika koristi latinično pismo, druga polovina je pisana ćirilicom, a oba pisma postoje u dvije međusobno isključive verzije: češko, slovačko, slovenačko i hrvatsko koriste latinicu sa `v`, `š`, `ž`  itd., poljsko sa @ @81 Ruski, ukrajinski, beloruski i bugarski koriste ćirilično pismo sa `й`, `ь`, `ю`,  srpskim i makedonskim sa `ј`, `љ`  i `џ`. Nije na nama da odlučujemo da li je jedan način „bolji“ ili „slavenskiji“ od drugog. Osim toga, svaki Sloven bi se trebao osjećati ugodno pisati interslavenski, pa moramo živjeti s činjenicom da se može pisati na razne načine.

Budući da su :isv[końe], :isv[koňe], :isv[konje], :isv[konie]  i _`kone`_ samo različiti, prirodni načini pisanja iste riječi, nema puno smisla raspravljati o tome koja verzija bi trebala biti „zvanična“, jer bi svaki takav izbor automatski učinio druge verzije „nezvaničnim“ “ pa stoga „pogrešno“ ili barem „nestandardno“. Stoga slijedimo potpuno drugačiji pristup: umjesto da biramo bilo kakvu službenu ortografiju, radimo s **prototipom pravopisa**. Pod pretpostavkom da se različita rješenja korištena u nacionalnim pravopisima odnose na jedan **prototip**, ovaj prototip također smatramo najboljim načinom predstavljanja međuslavenskog. Budući da imamo posla sa dva potpuno različita pisma (latinica i ćirilica), ne možemo izbjeći da za svako od njih imamo jedan prototip pravopisa.

U idealnom slučaju, oba prototipa bi trebala imati sljedeće karakteristike:

- moraju biti intuitivno razumljivi svakome ko može čitati dotično pismo
- moraju biti logični, dosljedni, nedvosmisleni i etimološki ispravni
- moraju dati pristojnu aproksimaciju ispravnog izgovora
- ako je moguće, jedan fonem (zvuk) = jedan znak
- trebali bi biti kompatibilni (jednostavna transliteracija, po mogućnosti jedna na bazi 1:1)
- ne bi trebalo da sadrže neprirodne elemente
- ne bi trebali biti ružni ili na neki drugi način uvredljivi (kao na primjer `йа` ili `łi`), ali ne bi trebali biti ograničeni na specifičnosti bilo kojeg nacionalnog jezika
- ispravno su prikazani na prosječnom kompjuterskom ekranu, stoga treba izbjegavati znakove iz neobičnih skupova znakova, kombiniranje dijakritičkih znakova i slično.

Budući da nijedan od postojećih slovenskih pravopisa ne može ispuniti sve ove zahtjeve, razlikujemo osnovnu azbuku koja se sastoji od fonema koji se mogu naći u svakom slavenskom jeziku i niza opcionih ekstenzija koje se mogu koristiti kao sredstvo za jasniji izgovor. , etimologija itd.

## Vokabular \{#vocabulary}

### Internacionalni naspram llavičkog vokabulara \{#international-versus-ѕlavic-vocabulary}

U idealnom slučaju, svaka riječ mora izgledati poznato svakom govorniku slavenskog jezika. Čak i ako se određeni oblik riječi ne pojavljuje u nečijem vlastitom jeziku, on bi barem trebao izazvati konotaciju koja mu daje nagoveštaj u pravom smjeru. Očigledno, to nije uvijek moguće, pa je stoga potrebno nekoliko mehanizama za odlučivanje o odabiru rječnika. Prvi i najvažniji korak je prikupljanje niza korijena riječi koji su prepoznatljivi za sve ili većinu Slavena. Nakon toga, ovi korijeni mogu poslužiti kao osnova za proširenje vokabulara izgradnjom složenica.

Postoje dvije vrste vokabulara koje igraju ključnu ulogu u poboljšanju međusobnog razumijevanja između dva različita jezika:

- međunarodni vokabular, riječi koje su uobičajene u mnogim, čak i nepovezanim jezicima. Većina je pozajmljena direktno ili indirektno iz latinskog i grčkog (_`filozofija`, `universitet`, `material`, `motor`_), ponekad dolazi iz drugih jezika (_`bjuro`, `fajl`, `jaguar`, `čaj`, `šokolad`_), u rijetkim slučajevima čak i iz samog slavenskog (_`vampir`, `vodka`_)
- zajednički naslijeđeni vokabular, drugim riječima, vokabular koji su oba jezika naslijedila od zajedničkog pretka, u konkretnom slučaju praslovenskog

Međunarodne riječi čine sastavni dio svakog slovenskog jezika. Njihova prednost je u tome što su u različitim jezicima praktički identični, kako oblikom tako i značenjem, te stoga predstavljaju odlično rješenje za međuslavenski, posebno za obrazovanije. U slučaju naslijeđenog rječnika situacija je nešto složenija, jer je svaki jezik prošao kroz svoj karakterističan razvoj, a kao rezultat toga, riječ u jednom jeziku možda neće odmah biti prepoznatljiva za govornike drugog, čak i ako je riječ o veoma ista reč. Uporedite na primjer poljski :isv[węgiel] i slovački :isv[uhlie] „ugalj“. Osim toga, u nekoliko slučajeva njihova su se značenja toliko udaljila jedno od drugog (npr. _`duma`_, što znači „misao“ na ruskom i „ponos“ na poljskom) da se mogu smatrati _lažnim prijateljima_, tj. riječima koje se lako mogu pogrešno shvaćen čak i u pravom kontekstu.

Opseg međunarodnog vokabulara je ograničen i neće biti od pomoći za mnoge svakodnevne koncepte. Osim toga, postoje ljudi koji jednostavno _ne vole_ da ga koriste na slavenskom. Iz tog razloga pokušavamo da ponudimo i široko razumljive slovenske alternative. Međutim, to nije uvijek moguće. Na primjer, neki slovenski narodi koriste latinske nazive mjeseci, dok drugi koriste slovenska imena. Potonji su mnogo manje ujednačeni: _listopad_ znači „studeni“ na poljskom i „listopad“ na hrvatskom (tipičan primjer lažnog prijatelja), dok samo Bjelorus može reći na koji mjesec se misli pod _`kastryčnik`_. Stoga, prema slovenskim ekvivalentima međunarodnih riječi treba postupati s oprezom.

Međunarodni vokabular se usvaja samo ako se koristi u većini slovenskih jezika. Interslavic primjenjuje određene fiksne mehanizme za njegovo posuđivanje, koji se mogu naći u [posebnom dijelu][1].

Kada je u pitanju zajednički naslijeđeni (slavenski) vokabular, trebamo učiniti tri stvari: odabrati riječi i korijen riječi, uspostaviti pravi oblik za njih i dodijeliti im osnovno značenje.

### Koje korijene koristiti? \{#which-roots-to-use}

Kada je potrebna nova riječ, počinjemo s popisom riječi koje za nju koriste različiti slovenski jezici. Ovisno o rezultatu, radimo ovo:

- Kada koren reči postoji u svim slovenskim jezicima u istom značenju, lako je: mi ga sa zahvalnošću usvajamo.
- Kada se raziđu samo jedan ili dva jezika, mi radimo isto.
- Kada se mogu razlikovati dvije ili više grupa, svaka na osnovu različitog slovenskog korijena, postupamo na sljedeći način:
  1. za svaki od tih korijena tražimo srodne u preostalim jezicima, zajedno sa njihovim značenjima,
  2. naknadno radimo isto za te korijene i značenja, stvarajući tako „semantičke porodice“,
  3. konačno, biramo one riječi koje se javljaju u svim ili većini jezika i pripisujemo im najviše „prosječnih“ značenja.
- Ako ni to ne uspije, imamo nekoliko opcija:
  1. biramo riječ koja se javlja u većini jezika
  2. analiziramo koje su riječi intuitivno razumljivije od drugih, čak i ako se koriste samo na jednom jeziku
  3. stvaramo sinonime
  4. većim i poznatijim jezicima dajemo prevlast manjim
  5. tražimo „međunarodni“ ekvivalent
  6. mi nešto „projektiramo“.

U primjeni ovog procesa sve tri potfamilije (istočna, zapadnoslavenska i južnoslovenska) tretiraju se na ravnopravnoj osnovi. Pažljivo izbjegavamo favoriziranje jednog jezika u odnosu na drugi, što nije uvijek lako, jer je jedan jezik (ruski) znatno veći od svih ostalih u smislu govornika, a nekoliko manjih jezika (poput srpskog, bosanskog i hrvatskog) je toliko slično svakom drugo da se lako mogu tretirati kao dijalekti jednog jezika. Da bismo postigli pravičan tretman jezika u vaganju njihovog unosa, koristimo sistem od šest podgrupa, a svakoj od ovih podgrupa se daje jedan „glas“:

- Ruski
- ukrajinski i beloruski
- Poljski
- češki i slovački
- slovenački i srpski/hrvatski/bosanski jezik
- bugarski i makedonski

Ako se dva jezika unutar jedne grupe ne slažu oko riječi, ½ glasa se daje jednom, a ½ glasa drugom. Ako dvije kandidatske riječi imaju isti broj glasova, odlučuje stanovništvo. Praktično, to znači da ruski uvijek pobjeđuje, što je razumno s obzirom na činjenicu da oko 70% Slovena zna taj jezik.

Iz praktičnih razloga, jezici sa manje od milion govornika, poput lužičkog, kašupskog i rusinskog, ne učestvuju u procesu glasanja. Međutim, to ne znači da se uopšte ne uzimaju u obzir.

[Mašina za glasanje][2] je alat koji primjenjuje ova pravila. Treba napomenuti da ova pravila treba da budu opšti trend; kada je drugo rešenje očigledno bolje, zdrav razum uvek treba da prevlada.

### Lažni prijatelji \{#false-friends}

Individualni razvoj slovenskih riječi u različitim jezicima, uključujući ponekad i ozbiljno odstupanje u značenju, doveo je do postojanja mnogih sličnih riječi s potpuno različitim značenjima u različitim jezicima. Ove riječi su poznate kao „lažni prijatelji“, i lijepa – iako nepotpuna – [pregled se može naći u engleskim Wikibooks][3]. Iako se ne mogu uvijek izbjeći, ovim riječima treba postupati pažljivo.

Mala razlika u značenju između jezika ne bi trebala biti problem (npr. :isv[ljubiti] znači „voleti“ na većini slovenskih jezika, ali „sviđati se“ na poljskom). I zaista velike razlike u značenju rijetko uzrokuju probleme, posebno kada pripadaju različitim kategorijama riječi (npr. _`pet` \~ `peť` \~ `peć` \~ `piec`_, noseći značenja poput „pet“, „peć“ , „opušak“ i „pjevati“). U oba slučaja šanse za nesporazum su male. Lažni prijatelji su problematični samo kada se neka riječ, uprkos ozbiljnoj razlici u značenju, još uvijek može koristiti u istom ili sličnom kontekstu i stoga je vjerovatno različito razumjeti od strane Slovena različitih nacionalnosti. Spomenuta riječ _`listopad`_, što znači „studeni“ na poljskom/češkom i „listopad“ na hrvatskom, je primjer. Očigledno, takve riječi treba izbjegavati u međuslavenskim tekstovima.

### Neologizmi \{#neologisms}

U kontekstu međuslavenskog, neologizmi su riječi koje kao takve ne postoje ni u jednom od živih slovenskih jezika. Primjeri takvih riječi su riječi portmanteau (na primjer :isv[katka] „patka“, iz ru. :isv[utka], pol. :isv[kaczka], južnoslavenski :isv[patka]), calques iz neslovenskih jezika (npr. :isv[kolokrěslo] „invalidska kolica“), kombinacije međuslavenskih korijena riječi s međuslavenskim afiksima koji u slavenskom jeziku ne postoje (na primjer _`gradnik`_ „stanovnik grada, građanin“), te riječi opisnijeg karaktera u slučajevima kada je nemoguće pronaći široko razumljivu slovensku riječ.

Mišljenja se razlikuju o stepenu u kojem su umjetno stvorene riječi prihvatljive u međuslavenskom; neki ljudi ih vole, drugi ih mrze. U rječniku nastojimo izbjegavati neologizme, osim ako nijedan od živih slovenskih jezika ne pruži riječ koja je razumljiva široj publici i koja neće biti pogrešno shvaćena od strane drugih. Primer je :isv[časina] „sat“ (staroslavenski sadrži dve reči: _`čas`_ i :isv[godina], ali prva znači „vreme“ na zapadnoslovenskom, druga znači „godina“ na južnoslovenskom, dok srpsko -Hrvatska riječ _`sat`_ je turska riječ koja drugim Slovenima uopće nije razumljiva).

### Kako uspostaviti pravu formu za root? \{#how-to-establish-the-right-form-for-a-root}

Nakon što znamo koju ćemo riječ koristiti, sljedeći korak je utvrđivanje kako bi točno trebala izgledati. Prvo i najvažnije, mora postojati unutrašnja konzistentnost: kad god se određeni korijen ili morfem pojavljuje u složenici, on bi trebao imati isti oblik, bez obzira iz kojeg jezika je ta složenica uzeta. Kako bi se spriječilo da međuslavenski postane mješavina riječi odabranih iz raznih jezika, riječi se nikada ne posuđuju direktno iz bilo kojeg slovenskog jezika.

Umjesto toga, vraćamo se hipotetičkom obliku u praslavenskom, koji se često može naći u njegovom bliskom srodniku staroslavenskom jeziku, a zatim ga podvrgavamo [modelu jednostavnog izvođenja] [4]. Ovo ne samo da garantuje koherentnost, već i poboljšava razumljivost i olakšava učenje, jer fonološki razvoj savremenih slavenskih jezika od praslovenskog ima tendenciju da bude izuzetno pravilan: kada čovek sazna kako je dati glas u njegovom jeziku predstavljen u Interslavenski – nešto što će vrlo brzo saznati čitajući nekoliko tekstova – ne samo da će moći lako prepoznati riječi, već će ih i predvidjeti bez pregledavanja rječnika.

Na primjer, zajednički slovenski nizovi `tj/dj` postaju `č/ž` u istočnoslovenskom, `c/dz` u poljskom, `c/z` u čehoslovačkom, `č/j` u slovenačkom, `ć/đ` u srpsko-hrvatskom, `ḱ/ǵ` u makedonski i `št/žd` na bugarskom. Najbolji kompromis ovdje je vjerovatno `č/dž` (npr. :isv[svěča] „svijeća“ i _`medžu`_ „između“), što ima dodatnu prednost u tome što je potonji zvučni ekvivalent prvom i na taj način stvara simetriju.

Za ilustraciju kako sve ovo funkcionira, možete vidjeti [ovdje][5] kako su lične zamjenice u međuslavenskom jeziku zasnovane na onima u prirodnim slovenskim jezicima.

## Gramatika \{#grammar}

Ono što važi za vokabular važi i za gramatiku. Gramatički elementi koji su zajednički slovenskim jezicima uvijek su polazište. Međutim, krajnji rezultat uvelike ovisi o svrsi i okolnostima za koje se Interslavic koristi. Optimiziranje razumljivosti automatski otežava govorniku ili piscu, dok pojednostavljena gramatika čini jezik manje prirodnim i stoga težim za razumijevanje. Da bismo se izborili s tim, razlikujemo dva različita gramatička nivoa. Koji je poželjniji za koju svrhu zavisi od govornika, slušaoca, medija i situacije. U idealnom slučaju, nivo 1 bi trebao biti podskup nivoa 2, tako da učenik može postepeno napredovati, a da njegovo prethodno stečeno znanje ne bude poništeno.

### Jednostavan nivo \{#simple-level}

Najjednostavniji oblik interslavenskog, `Slovianto`, nije zapravo jezik, već metod koji mogu koristiti neslavenski kao metod za učenje i/ili korištenje međuslavenskog. Sastoji se od tri različita nivoa, od kojih svaki učeniku približava „pravi“ međuslavenski.

Prvi nivo je minimalistička, primitivna gramatika, koju karakteriše odsustvo svega što nije zaista potrebno za jednostavnu komunikaciju. Gramatički rod ne igra ulogu na ovom nivou, padeži imenica su odsutni, a verbalna konjugacija ostaje ograničena na goli minimum. Malobrojni oblici koji su ostali (na primjer, množina) trebali bi biti prepoznatljivi za Slovene bez ikakvog prethodnog proučavanja, a njihovo pamćenje bi trebalo biti pitanje minuta, a ne sati. Ovaj nivo je posebno koristan za ne-Slovene koji nisu zainteresovani za učenje celog jezika, ali ipak žele da se izraze na osnovnom nivou u kontaktima sa Slovenima.

Drugi nivo uvodi gramatički rod i pruža jednostavan model za konjugaciju glagola. Treći nivo uvodi padeže imenica.

### Napredni nivo \{#advanced-level}

„Pravi“ interslavenski je prvenstveno namenjen Slovenima, ali i neslovenima koji žele da komuniciraju na ozbiljnijem nivou. Ovaj nivo se zasniva na zajedništvu slovenskih jezika. Dakle, ima gramatički rod (prisutan u svim slovenskim jezicima), sedam padeža (prisutan u svim slovenskim jezicima osim bugarskog i makedonskog), verbalni aspekt i punu konjugaciju glagola. Međutim, slavenski jezici su poznati po svojoj složenoj gramatici, a da bi se izbjegle beskonačne tabele s nominalnim i verbalnim paradigmama, još uvijek je potrebno mnogo pojednostavljenja. Da bismo pronašli dobru ravnotežu između naturalizma i jednostavnosti, pokušavamo što bliže približiti prirodno postojeće forme koristeći najlakši mogući način. Nepravilnost se izbjegava, osim ako je laka prepoznatljivost ozbiljno ugrožena. Izbjegava se i umjetnost.

Najvažnije je da je svaki gramatički završetak odmah prepoznatljiv, čak i ako oblik riječi izgleda drugačije u nečijem jeziku. Na primjer, većina slovenskih jezika može imati različite nastavke za genitiv jednine imenice muškog roda, ali postoji jedan završetak koji im je svima zajednički: `-a`, što je stoga rješenje za sve pojave ovog oblika. U slučaju glagola, brojne glagolske klase koje postoje u slovenskom jeziku svedene su na jednostavan sistem od dvije osnove, infinitivne osnove i osnove prezenta. Ovo posljednje je gotovo uvijek logičan rezultat prvog, a samo u nekoliko slučajeva ih je potrebno učiti odvojeno. Zahvaljujući ovom pristupu, postiže se mnogo pojednostavljenja bez žrtvovanja naturalističkog karaktera jezika.

Ovaj nivo je pogodan za kontakte i publikacije, ali i kao sredstvo za sticanje uvida u prirodu slavenskog.

[1]: ../vocabulary/derivation.md

[2]: http://steen.free.fr/interslavic/voting_machine.html

[3]: http://en.wikibooks.org/wiki/False_Friends_of_the_Slavist

[4]: ../vocabulary/derivation.md#proto-slavic

[5]: http://steen.free.fr/interslavic/slavic_pronouns.html

