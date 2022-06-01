

# Pisno - pričakovano

---

<!-- ## Prva pola programiranje
## Druga pola širše znanje RAČ/RSO
## Sistemi
## Omrežja
## Informatika
## Baze, načrtovanje baz
## Informacijski sistemi (IS)
## Objektni pristop -->

---

# Izpitne vsebine

---
---
---

# **Algoritmi in programski jeziki**
## Opredeli pojem algoritma
* Načrt/Navodilo za izvedbo zaporedja operacij nad podatki, da se doseže želeni rezultat.

## Obvezne lastnosti algoritma
* Popolnost - vse akcije morajo biti natančno definirane
* Nedvoumnost - obstaja le en način interpretacije ukazov
* Determinizem - mora dosečti želeni rezultat
* Končnost - mora se zaključiti

## Načini zapisa algoritma
* Diagram poteka
* Tabela
* Psevdokoda

## Pojem in funckija programskega jezika
* Programski jezik - storju berljiv umetni jezik, ki programerju omogoča pisanje programov, ki izvajajo razna opravila

## Razvrsti vrste programskih jezikov po namenu in uporabi
* Skriptni?
* Tolmačeni?
* Prevajani?

## Razlika med strukturiranim in objektnim programiranjem
* Objektno programiranje - program sestavljajo objekti
* Strukturirano programiranje - program sestavljajo moduli in metode

## Razlika med prevajanjem in tolmačenjem
* Prevajanje - compile - celoten program se pretvori v strojno kodo in izvede
* Tolmačenje/Interpretacija - interpret - program izvede vsako linijo sproti

## Delovanje osnovnih gradnikov postpokovnih prog. jezikov (zaporedje, vejitev, iteracija...)
* TODO <!-- TODO -->

## Sledi izvajanju algoritma za dani primer - VAJA

## Izdelaj algoritem za dani primer - VAJA

---
---
---

# **Programiranje**
## Razlikuj pojme izvorna koda, izvršljiva koda, podatkovni tip

* Izvorna koda - človeško berljiva koda napisana v višjem programskem jeziku
* Izvršljiva koda - rezultat prevajanja izvorne kode v format, ki ga lahko uporablja CPE
* Podatkovni tip - klasifikacija, ki določa kakšne vrednosti lahko sprejema spremenljivka

## Opredeli spremneljivka, konstanta, podatkovni tip

* Spremenljivka - vrednost, ki se lahko spreminja glede na potrebe programa
* Konstanta - spremenljivka, ki ima konstantno vrednost - po dodelitvi se vrednost ne da več spremeniti
* Podatkovni tip - klasifikacija, ki določa kakšne vrednosti lahko sprejema spremenljivka - boolean, int, String, float...

## Operatorji in njihova prioriteta
![operatorji_aritm](/attach/operatorji_aritm.png)
![operatorji_dodelitveni](/attach/operatorji_dodelitveni.png)
![operatorji_primerjalni](/attach/operatorji_primerjalni.png)
![operatorji_logicni](/attach/operatorji_logicni.png)

## Uporaba osnovnih in sestavljenih tipov podatkov
* TODO <!-- TODO -->

## Uporabi pogojne stavke
* if... else if... else, while stavki

## Izvedba iteracije z zankami
* for loop ```for(int i= 0; i<x; i++)```

## Sledi izvajanju programa za dani primer - VAJA

## Definicija razreda
* Načrt za ustvarjanje objektov
![java_class](/attach/java_class.png)

## Vloga in način izvajanja konstruktorja
* Konstruktor - posebna metoda, ki se uporablja za inicializacijo objektov
* Pokliče se kadar se ustvari objekt nekega razreda
* Atributam objekta dodeli začetne vrednosti
![java_constructor](/attach/java_constructor.png)

## Deklaracija in uporaba objektov
![deklaracija_objekta](/attach/deklaracija_objekta.png)

## Uporaba metod za delo z objekti razredov Math, String, StringBuffer, Integer, Double, Float, Long, Short, Byte, Random
* _import java.util.Random_
<!-- TODO dopolni math random in ostale metode-->

## Uporabi enkapsulacijo, dedovanje in polimorfizem
* Enkapsulacija poskrbi, da so občutljivi podatki skriti pred uporabniki
* Značilne metode *get* pa *set* za atribute tipa *private*
![java_enkapsulacija](/attach/java_enkapsulacija.png)

+ Dedovanje je koncept, ki omogoči, da razred deduje metode in atribute drugega razreda
+ S tem se prihrani na podvojevanju kode
+ Subclass (otrok/child) - razred, ki podeduje atribute in metode od starša
+ Superclass (starš/parent) - razred, od katerega se podedujejo atributi in metode
![java_dedovanje](/attach/java_dedovanje.png)

- Polimorfizem omogoča izvajanje istega dejanja na različne načine
- Primer, superclass *Žival* ima metodo *glas()*, vsi subclassi imajo tudi metodo *glas()*, a vsaka žival ma unikatno vrednost - unikaten glas
![java_polimorfizem](/attach/java_polimorfizem.png)

* __Dedovanje in Polimorfizem oba uporabljata ključno besedo <u>*extends*</u>__

## Zapiši programsko kodo za prestrezanje in obravnavo izjem
```java
try{ Integer.parseInt(cifra) }
catch{ System.out.println("Spremenljivka cifra vsebuje nedovoljene znake ali je prazna.")}
```
## Zapiši program za dani primer - VAJA
---
---
---

# **Zgradba in delovanje računalnika**
## Gradniki računalniškega sistema

* TODO <!-- TODO -->

## Opiši in razloži naloge, zgradbo in tehnične lastnosti osnovnih enot računalniškega sistema; CPE (ALE, registri, vodila, krmilna enota), pomnilnik, V/I enote

<!-- Vaje : http://egradivo.ecnm.si/KIT/centralno_procesna_enota.html -->

* **CPE** - osrednji del rač., ki obdeluje/procesira podatke in nadzoruje ter upravlja ostale enote
* **Aritmetično-Logična Enot** - ALE - izvršuje operacije nad podatki, ki jih zahtevajo ukazi
* **Registri** - pomnilniške celice, ki začasno hranijo podatke in njihove naslove - najhitrejši pomnilnik, omogoča hitro izvajanje operacij v CPE
* **Vodila** - linija, ki tvori povezavo med dvema ali več deli računalnika
* **Krmilna enota** - **najpomembnejši del CPE** - skrbi za **pretok podatkov po vodilih** in **krmili izvajanje ukazov**
* **Pomnilnik** - spomin računalnika - hrani vse ukaze in podatke vnešene preko V/I enot
* **V/I enote** - vhodno informacijo pretvorijo v računalniku-razumljivo obliko, izhodne pa v človeku-razumljivo obliko

## Razlogi za uporabo več različnih pomnilnikov (pomnilniška hiearhija), opis le teh, loči med ROM in PROM
* Uporaba pomnilnika glede na namen - razmerje med ceno in hitrostjo
* Višja cena pomeni manjši razpoložljivi prostor

![pomn_hiearhija](/attach/pomn_hiearhija.png)

+ ROM - Read Only Memory - vrednosti v pomnilniki se zapišejo in se ne dajo več spremeniti
+ PROM - Programmable Read Only Memory - vrednosti se dajo spremeniti
## Načini in značilnosti priključitve V/I naprav

* TODO <!-- TODO -->

---
---
---

# ****Številski sistemi****
## Naštej in razloži, čemu se v računalništvu uporabljajo različni številski sestavi - opiši jih
* Desetiški - sestav za prikaz cifer na človeku-prijazen način
* Binarni - oblika zapisa električnih signalov v mikrokrmilnikih in CPE
* Osmiški - krajši način zapisovanja binarnih števil - 0 do 7
* Šestnajstiški - še krajši način zapisovanja binarnih števil - uporablja za naslavljanje - 0 do F

## Pretvarjaj med sestavi
* Binary > Base10 - $2^x$
* Binary > Base 8 - Osmiški sestav za cifro uporabi 3 bite
* Binary > Base 16 - Šestnajstiški sestav za cifro uporabi 4 bite
* Base 8 > Base 16 - V dvojiškega pa potem v base 16

## Računske operacije s sestavi, prečna in vzdolžna pariteta, kontrolna vsota

* TODO <!-- TODO -->

---
---
---

# **Ukazi**
## Razloži pojme operacija, operand, naslov in način naslavljanja
* TODO <!-- TODO -->

## Opiši zgradbo ukaza
* TODO <!-- TODO -->

## Naštej in opiši tipe operandov - celo nepredznačeno in predznačeno število (signed unsigned integer), število v pomični vejici, bajt - znak, četverko in bit
* TODO <!-- TODO -->

## Loči fizične, logične in navidezne naslove
* TODO <!-- TODO -->

## Naštej osnovne operacije - aritmetične, logčine, primerjalne, vhodne/izhodne in operacije za delo s pomnilnikom
* TODO <!-- TODO -->
---
---
---

# **Poznavanje slojev v arhitekturi računalnika**
## Naštej sloje - (digitalna tehnika, mikroprograma, strojni ukazi, zbirnika, operacijskega sistema, višjih programskih jezikov in sloj aplikativne programske opreme)
* TODO <!-- TODO -->

## Opiši vse sloje in razloži njihovo vlogo
* TODO <!-- TODO -->

## Opiši in razloži razliko med tolmačenjem (interpretiranjem) in prevajanjem
* Prevajanje - compile - celoten program se pretvori v strojno kodo in izvede
* Tolmačenje/Interpretacija - interpret - program izvede vsako linijo sproti

## Vrste programske opreme in opredeli naloge
* TODO <!-- TODO -->

## Naštej vrste najbolj razširjene programske opreme, opredeli funkcijo in ovrednoti uporabo
* TODO <!-- TODO -->

---
---
---

# **Računalniško omrežje**
## Razloži pomen povezave računalnikov v računalniško omrežje
* Računalniki se povezujejo v omrežje z namenom deljenja in izmenjavo virov

## Opiši in obrazloži načine organiziranja rač. omrežij (omrežje enakopravnih, odnos strežnik-odjemalec)
* Strežnik gosti podatke, do katerih odjemalci lahko dostopajo

## Omrežja glede na geografski obseg - LAN, WLAN, MAN, WAN
* LAN - lokalno žično omrežje
* WLAN - lokalno brezžično omrežje
* MAN - območje mesta
* WAN - prostrano omrežje - Internet

## Opiši pojma standard in protokol
* Protokol - nabor pravil za interakcijo med dvema ali večimi strankami
* Standard - smernice za potek interakcije, izdelavo produkta, itd..

## Naštej in opiši sloje modela ISO/OSI
* A P S T O P F
![isoosi](/attach/isoosi.png)

+ Aplikacijski - vmesnik med uporabinkom in omrežjem - SMTP, POP za epošto, HTTP
+ Predstavitveni - uskladitev načinov predstavitve podatkov - kompresija, šifriranje - SSL, TLS
+ Sejni - vzpovstavitev, vzdrževanje in prekinitev seje med končnimi napravami
+ Transportni - zagotovitev povezave med končnimi napravami - fragmentacija in defragmentacija, error correction - TCP in UDP
+ Omrežni - pravilno potovanje paketkov po omrežju - IPv4, IPv6
+ Povezovalni - omrežna topologija, kontrola pretoka, določanje enote sporočil - Ethernet, FDDI, ARP
+ Fizični - določa fizične lastnosti, zapis podatkov za prenos po fizičnem mediju - RJ45, Optika, Coax

## Pomen protokolov posameznega sloja ISO/OSI, funkcije posameznega sloja

+ Aplikacijski -  SMTP, POP za epošto, HTTP
+ Predstavitveni - SSL, TLS
+ Sejni -
+ Transportni - TCP in UDP
+ Omrežni - IPv4, IPv6, ICMP, IGMP
+ Povezovalni - Ethernet, FDDI, ARP
+ Fizični - RJ45, Optika, Coax

## Opiši model TCP/IP
* Standardiziran protokoln sklad - komunikacija v heterogenem okolju
* Sporočila se razdelijo na paketke (TCP) in pošlejo po Internetu ali omrežju (IP)
* TODO <!-- TODO -->

---

# **Model TCP/IP - plast omrežnega vmesnika**
## Opiši prenosne medije - coax kabel, sukana parica, optični kabel, brezžični medij
* Coaxialni kabel - prevodna sredica obdana s izolantom in opletom - poceni in upogljiv a počasen - danes večinoma zastarel
* Sukana parica - prepletene žice, 4 pari za ethernet standard - danes prevladuje - sukanje prepreči motnje/presluh
* Optični kabel - standard za daljše razdalje - uporaba svetlobe za pošiljanje podatkov
* Brezžični medij  - primer je WiFi standard za WLAN omrežja - 2.4GHz in 5GHz signali za sporazumevanje

## Značilnosti, prednosti/slabosti topologij - vodilo, zvezda, obroč, zvezda-obroč, drevo
* Vodilo:
* + Enostavna postavitev, ekonomična poraba kabla in enostavna razširitev
* - Počasen prenos pri velikem prometu, ena prekinitev uniči omrežje, težko odkrivanje napak

+ Zvezda:
+ + Enostavno priključevanje postaj, centraliziran nadzor, izpad elementa ne vpliva na omrežje
+ - Izpad zvezdišča poruši celotno omrežje, potrebno je več kabla

* Obroč: (MAU)
* + Enakovreden dostop za vse postaje, zanesljiv prenos podatkov, ni dodatne obremenitve pri novih članih
* - Izpad enega elementa poruši celotno omrežje, težko odkrivanje napak, za razširitev potrebno prekiniti promet

- Fizična zvezda logični obroč:
- + Enakovreden dostop uporabnikov in zanesljivost ter redundanca zvezdišča
- - Izpad zvezdišča poruši celotno omrežje

## Naštej in opiši pristopne metode - CSMA, CSMA/CD, Token Ring, FDDI, ATM
* CSMA - Carrier Sense Multiple Access - preverjanje zasedenosti omrežnega medija preden se pošlje promet
* CSMA/CD - Collision detection - CSMA + preverjanje trkov, ob trku se počaka nekaj trenutkov preden se znova poizkusi pošiljanje
* Token Ring - žeton daje imetniku privilegij pošiljanja prometa - v enem trenutku pošilja samo en član omrežja (imetnik žetona) - fizična zvezda logični obroč - MAU
* FDDI - hitro optično omrežje topologije obroč - povezovanje mest - hrbtenica hitrih omrežij - dvojni obroč za redundanco
* ATM - podatki so razdeljeni v pakete fiksne velikosti (celice) in poslane preko virtualnih povezav

## Pomen fizičnega naslova omrežne kartice
* Fizični naslov omrežne kartice je MAC naslov, je unikatni identifikator za prepoznavanje naprave v lokalnem omrežju

## Opiši naprave za povezovanje v krajevna omrežja - stikalo, usmerjevalnik
* Usmerjevalnik - privzeti prehod za lokalno omrežje - usmerja paketke med lokalnim in prostranim omrežjem - deluje na tretjem nivoju
* Stikalo - obravnava paketke v lokalnem omrežju - deluje na drugem nivoju

---

# **Model TCP/IP - omrežna plast**
## Opis razredov naslovov IP in ustrezne maske
* TODO <!-- TODO -->

## Razlika med zasebnim in javnim IP naslovom
* Zasebni IP naslov je naslov, ki se uporablja znotraj lokalnega omrežja in ni dostopen izven lokalnega omrežja
* Javni IP naslov je unikaten naslov usmerjevalnika na Internetu - vsak zasebni naslov v danem omrežju komunicira na Internetu s javnim naslovom prehoda

## Razdelitev omrežja na podomrežja
* TODO <!-- TODO -->

## Razloži in opiši - Unicast, Multicast in Broadcast
* Unicast - komunikacija ena na ena
* Multicast - komunikacija ena postaja z večimi napravami določene skupine
* Broadcast - komunikacija ena postaja z vsemi napravami

## Opiši naloge usmerjevalnika
* Povezuje omrežja in dovoljuje določen promet
* Omogoča komunikacijo med različnimi arhitekturami in okolji
* Izvaja NAT pretvorbe

## Opiši privzeti prehod (gateway)
* Naprava, katera omogoča povezovanje z različnimi omrežji
* Privzeta naprava, ki prejema in posreduje promet namenjen izven lokalnega omrežja
* TODO <!-- TODO -->

## Navedi funkcije DHCP
* DHCP dodeljuje IP naslov, omrežno masko in privzeti prehod vsem napravam v lokalnem omrežju

---

# **Model TCP/IP - Transportna plast**
## Razlika med protokoloma TCP in UDP
* TCP - povezavni protokol -zagotavlja zanesljiv prenos - potrjevanje prejema in kontrola pretoka
* UDP - nepovezavni protokol -ne zagotavlja zanesljivega prenosa v zameno za hitrejši prenos - slepo pošiljanje brez potrjevanja prejema

# **Model TCP/IP - Aplikacijska plast**
## Obrazloži delovanje storitev aplikacijske plasti - prenos datotek, svetovni splet, elektronska pošta - opiši protokole, ki omogočajo te storitve
* Prenos datotek - FTP porta 20(prenos) in 21(nadzor) -
* Svetovni splet - HTTP port 80 -
* Elektronska pošta -  POP(dostava do uporabnika) in IMAP(dostava med strežniki) -

---
---
---

# **Funkcije operacijskega sistema** <!-- NOTE | Večuporabniški, večopravilni... -->
## Naštej vrste operacijskih sistemov in jih opiši
* Enopravilni in enouporabniški OS: en uporabnik, ki obenem lahko izvaja samo en program preden lahko gre na naslednjega - slaba izkoriščenost sistemskih virov
* Večopravilni OS: možnost paralelnega izvajanja programov - vsak program ima dodeljen čas na CPE
* Večuporabniški OS: potreba po preverjanju uporabnikov, vodenje evidence, poverilnice, zaščita podatkov
* Porazdeljeni OS: sistemski viri in moč so porazdeljeni preko mreže čez več računalnikov
* Mrežni OS: računalnik ima svoje vire, lahko pa jih da v skupno rabo preko omrežja
* Realnočasovni: takojšen odziv in pravočasna izvedba opravil

## Naštej in opiši naloge operacijskega sistema in naloge njegovih gradnikov
* Dodeljevanje sistemskih virov procesom, časovno razporejanje opravil, reševanje konfliktnih situacij,
* Optimizacija in nadzor uporabe virov, vmesnik med uporabnikom in strojno opremo

![kernel_diagram](/attach/kernel_diagram.png)

* Vmesnik -
* Lupina - del programske opreme, ki uporabniku zagotavlja vmesnik - dostop do jedra
* Jedro - izvaja sistemska opravila in skrbi za normalno delovanje operacijskega sistema
* Gonilniki - del programske opreme, ki omogoča komunikacijo med programsko in strojno opremo
* Strojna oprema - fizična oprema - CPE, pomnilnik, ... - nekaj si zbluzi

## Razloži vzroke za prekinitve, vrste prekinitev in potek prekinitve
* ?? Vzrok: potrebna je izvedba prekinitve za delovanje V/I naprav??

+ Vrste:
+ Strojne - fizični električni signal, ki spremeni delovanje CPE
+ Programske - strojni ukazi, ki preusmerijo tok dogajanja CPE

- Potek:
![potek_prekinitve](/attach/potek_prekinitve.png)


## Razloži delovanje V/I podsistema in datotečnega podsistema
* TODO <!-- TODO -->

## Opiši razlike med procesi, posli in opravili
* Proces - program, ki se izvaja v pomnilniku -
* Opravilo (task) - gradniki posla - enota izvedbe
* Posel (job) - enota dela -

## Opiši zgradbo imenikov in datotek ter zaščito le-te
* TODO <!-- TODO -->

## Uporabi ukaze OS - upravljaj prostor na disku, spreminjanje pravic za datoteke, upravljanje uporabnikov in skupin

* chmod ogw - owner group world - dodeljevanje pravic
![chmod](/attach/chmod.png)

* mkdir, touch, rm - ustvari mapo/imenik, ustvari datoteko, izbriši datoteko
---
---
---

# **Podatkovna baza in sistemi za njeno upravljanje**
## Prednosti in slabosti podatkovnih baz (PB)
* Prednosti:
* Nadzorovana redundanca podatkov
* Skupna raba podatkov
* Preprečevanje nepooblaščenega dostopa do podatkov

- Slabosti:
- Cena programske opreme za upravljanje PB
- Potreben čas za učenje in privajanje na sistem
- Odvisnost od proizvajalca/dobavitelja SUPB

## Razloži arhitekturo ANSI/SPARC PB
* Tri-nivojska zasnova: Zunanji > Konceptualni > Fizični

+ Vsi uporabniki uporabljajo iste podatke
+ Uporabnik nima dostopa do fizičnih podatkov
+ Sprememba strukture ne vpliva na uporabniške poglede
+ Fizične spremembe nimajo vpliva na interno shemo
+ Administrator lahko spremeni konceptualno strukturo brez vpliva na uporabnika

![ansisparc](/attach/ansisparc.png)

- Zunanji nivo predstavlja različne poglede (sheme) uporabnikov na PB
- Konceptualni nivo vsebuje celovito informacijo o vsebini in strukturi PB
- Notranji nivo opisuje kako so podatki shranjeni v PB

## Naštej vrste uporabnikov PB, opiši delo in naloge administratorja PB
* Naivni uporabnik - slepo uporablja uporabniške aplikacije
* Superuser - zna izvajati poizvedbe
* Programer - piše aplikacije za uporabnike
* Administrator - ureja strukturo PB in je zadolžen za arhiviranje in varnostne kopije

## Opredeli vlogo in funkcije SUPB
* Ustvarjanje in spreminjanje PB
* Manipulacija podatkov
* Izvajanje transakcij
* Zaščita podatkov
* Zagotavljanje integritete podatkov

## Navedi osnovne možnosti za shranjevanje PB in organizacijo podatkov v datotekah
* Fizične in logične datoteke?
* TODO <!-- TODO -->

---
---
---

# **Načrtovanje PB**
## Opiši potek razvoja PB
![razvojpb](/attach/razvojpb.png)

## Navedi gradnike konceptualnega modela in elemente logičnega modela
* TODO <!-- TODO -->

## Izdelaj konceptualni model za dani primer - VAJA

## Pretvori konceptualni model v logičnega - VAJA

---
---
---

# **Implementacija PB**
## Stavki za ustvarjanje, spreminjanje, brisanje gradnikov PB
![dml](/attach/dml.png)

## Stavki za ustvarjanje in brisanje PB
![ddl](/attach/ddl.png)

## Preizkusi delovanje integritetnih omejitev - VAJA

## Dokumentiraj strukturo PB - VAJA

## Predstavi načrt PB ter vrednoti in zagovarjaj izbrano rešitev - VAJA

---
---
---

# **Stavki SQL pri delu s podatki v PB**
## Zapiši stavek za filtrirano in popolno branje iz ene ali več tabel
* TODO <!-- TODO -->

## Uporabi vgrajene funkcije za izvedbo operacij nad podatki in združi zapise
* TODO <!-- TODO -->

## Zapiši stavek, ki vrne razliko, unijo ali presek dveh tabel
* Razlika - NOT X AND Y
* Unija - WHERE X AND Y
* Presek - WHERE X AND Y

## Dodaj nov zapis v tabelo in prepiši podatke med tabelami
* TODO <!-- TODO -->

## Stavek za posodabljanje podatkov v tabeli
![update](/attach/update.png)

## Stavek za brisanje zapisov tabele
![delete](/attach/delete.png)

## Na podlagi danih povezav oceni posledice brisanja/posodabljanja vrednosti - VAJA  

---
---
---

# **Informacija in sistemi**
## Opredeli osnovne pojme; podatek, informacija, znanje
* Podatek - dejstva, predstavljena z vrednostmi, ki imajo pomen v določenem kontekstu
* Informacija - pomen, ki ga človek pripiše podatkom ali novo spoznanje, ki ga človek doda svojemu poznavanju sveta
* Znanje - celota podatkov, ki si jih kdo vtisne v zavest z učenjem

## Razloži vlogo informacijskih sistemov (IS) v organizaciji
* Cilj IS je posredovati pravo informacijo na pravo mesto ob pravem času z minimalnimi stroški.
* Glavna naloga IS je oskrbovanje uporabnikov z informacijami o preteklem in trenutnem delovanju ter predvidenem obnašanju organizacije ter njenega okolja.

## Naštej osnovne dejavnosti in gradnike IS
* Zajemanje podatkov - sprememba podatkov v obliko primerno za strojno obdelavo
* Obdelava podatkov - analiza in organizacija podatkov - sortiranje, združevanje, preverjanje pravilnosit
* Oblikovanje informacij - oblikovanje informacij za človeški pregled
* Shranjevanje podatkov - shranjevanje za poznejšo uporabo  
* Prenos podatkov -
* Nadzor - usmerjanje aktivnosti z namenom da uporabnik dobi točno tisto kaj rabi

![komponente_is](/attach/komponente_is.png)

## Naštej in opiši značilnosti različnih vrst IS
* Transakcijski - podpora poslovanju organizacije
* Upravljalski - zagotavlja informacije potrebne za upravljanje organizacije
* Odločitveni - odvisen od transakcijskega in upravljalskega IS - pomoč pri sprejemanju odločitev v organizaciji
* Direktorski - spremljanje rezultatov organizacije in urejanje splošnih pogojev poslovanja

---
---
---

# **Razvoj informacijskih sistemov (IS)**
## Naštej probleme in njihove vzroke pri uporabi IS
* WHAT DO YOU MEAN

## Zapiši in opiši faze življenskega cikla IS
![cikelIs](/attach/cikelIs.png)

## Naštej pristope k razvoju IS
![pristopIs](/attach/pristopIs.png)

## Opiši funkcije orodja CASE pri razvoju in vzdrževanju IS
![funkcijeCase](/attach/funkcijeCase.png)

* Prednosti/Slabosti CASE
![proconCase](/attach/proconCase.png)
---
---
---

# **Objekto usmerjena sistemska analiza in načrtovanje z UML**
## Naštej značilnosti objektno usmerjenega pristopa - (class, object, method, message, polymorphism, inheritance, encapsulation)
* Razred - družina objektov s podobno strukturo
* Objekt - primerek razreda, ki ima identiteto, strukturo in obnašanje
* Metoda - ?
* Sporočilo - mehanizem, kjer pošiljatelj zahteva izvedbo operacije pri prejemniku
* Polimorfizem - objekti isto obnašanje izvedejo na različne načine
* Dedovanje - specifični objekti podedujejo lastnosti splošnih objektov
* Enkapsulacija - združitev pomembnih lastnostih na enem mestu

## Naštej osnovne skupine diagramov UML;
## Strukturne (razredni diagram, diagram objektov)
![diagram_razredni](/attach/diagram_razredni.png)

## Obnašanj (diagram aktivnosti, diagram primerov-uporabe (use-case), zaporedja, stanja)
![diagram_usecase](/attach/diagram_usecase.png)

## Navedi simbole in njihov pomen;
* mama ti stric

## - osnovni gradniki primerov uporabe: akter, primer uporabe, meja sistema, povezava, relacija, vključevanje (include), razširitev (extend), generalizacija
![povezave_usecase](/attach/povezave_usecase.png)

## - razredni diagrami: razred, atribut, opracija, povezava, števnost
![diagram_razredni2](/attach/diagram_razredni2.png)

## Naštej in upoštevaj korake pri izdelavi diagramov primerov uporabe - VAJE

## Za dani primer nariši use-case diagram - VAJE

## Za dani primer nariši razredni diagram - VAJE
