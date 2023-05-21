# Státnicové otázky MPC-IBE

Nejnovější export je dostupný [zde](https://github.com/VUT-FEKT-IBE/MPC-IBE-SZZ/releases/latest).

## Základy informační bezpečnosti

Vybírají se právě čtyři předměty.

*Vybírají se maximálně čtyři předměty:*

- [MPC-PDA](#MPC-PDA) Pokročilé datové struktury a algoritmy
- [MPC-CT3](#MPC-CT3) Bezpečnost ICT3
- [MPC-KRY](#MPC-KRY) Kryptografie
- [MPC-ODP](#MPC-ODP) Odpovědnost v právu ICT

*Vybírá se maximálně jeden předmět:*

- [MPC-MOS](#MPC-MOS) Moderní síťové technologie
- [MPC-PKT](#MPC-PKT) Pokročilé komunikační techniky

## Vybrané partie informační bezpečnosti

Vybírají se právě dva předměty.

*Vybírají se maximálně dva predměty:*

- [MPA-KPM](#MPA-KPM) Mobile Network Communication Systems
- [MPC-UIN](#MPC-UIN) Umělá inteligence
- [MPC-PLD](#MPC-PLD) Programovatelné logické obvody
- [MPC-CSI](#MPC-CSI) Číslicové signály a systémy
- [MPC-SSY](#MPC-SSY) Bezdrátové senzorové sítě
- [MPC-PZO](#MPC-PZO) Pokročilé techniky zpracování obrazu
- [MPC-SKS](#MPC-SKS) Služby komunikačních systémů
- [MPC-NAV](#MPC-NAV) Počítače a jejich periferie
- [MPC-VDP](#MPC-VDP) Vyšší techniky datových přenosů
- [MPC-MPG](#MPC-MPG) Moderní počítačová grafika
- [MPC-OSE](#MPC-OSE) Optical Networks
- [MPA-MOK](#MPA-MOK) Modern Cryptography

## Seznam předmětů a jejich otázek

### MPC-KRY

- [x] Formální definice kryptografického systému, symetrické a asymetrické šifry. Výpočetně těžké matematické problémy pro asymetrické šifry.
- [x] Služby bezpečnosti zajišťované kryptografickými prostředky, kryptografické mechanismy, které tyto služby zajišťují.
- [x] Kryptograficky bezpečné generátory náhodných čísel – požadavky, hodnocení bezpečnosti, příklady realizace.
- [x] Hašovací funkce, formální definice, požadované vlastnosti, hodnocení bezpečnosti, příklady algoritmů a použití.
- [ ] Kryptografie nad eliptickými křivkami, principy, důvody použití, příklady algoritmů.
- [ ] Digitální podpis, principy, standardy, metody pro distribuci veřejných klíčů (PKI).
- [x] Kvantová distribuce klíčů, důvody použití, příklady protokolů.
- [x] Postkvantová kryptografie – důvody použití, jaké těžké matematické problémy se zde využívají (kryptosystém McEliece, kryptosystém založený na mřížkách). Jednorázový podpis pomocí hašovacích funkcí (Lamport).
- [x] V souvislosti s nařízením eIDAS vysvětlete pojmy - elektronický podpis, zaručený elektronický podpis a kvalifikovaný elektronický podpis. elektronická pečeť, elektronické časové razítko.
- [x] Autentizační protokoly, principy, použití, hodnocení jejich bezpečnosti (BAN logika).

### MPC-PKT

- [x] TCP/IP: Vazba mezi RM ISO/OSI a TCP/IP. Filozofie vzájemného propojování sítí. Souběh aplikací a zapouzdřování přenášených dat.
- [x] Úloha IPv4 (Internet Protocol verze 4) vrstvy. IPv4 adresy. IPv4 datagram. IP tunelování. Protokol ICMPv4 (Internet Control Message Protocol verze 4).
- [x] Protokoly transportní vrstvy a jejich srovnání: UDP (User Datagram Protocol), Protokol TCP (Transmission Control Protocol), SCTP (Stream Control Transmission Protocol), protokol QUIC.
- [x] Jmenný systém DNS (Domain Name System): důvody existence, popis fungování protokolu, úloha resolveru, kořenové servery DNS, DNSsec. Protokoly MDNS (Multicast DNS) a LLMNR (Link-Local Multicast Name Resolution).
- [x] Princip protokolů zálohování výchozí brány. Protokoly HSRP (Hot Standby Router Protocol) a VRRP (Virtual Router Redundancy Protocol).
- [x] Multicastový přenos dat, adresování, protokoly, směrování multicastu.
- [x] IPv6 (Internet Protocol verze 6): vlastnosti protokolu a důvody existence, přechodové mechanizmy, datagram a systém rozšiřujících záhlaví, adresace.
- [x] IPv6 (Internet Protocol verze 6): funkce ICMPv6 protokolu, popis automatické konfigurace v IPv6 síti, fungování multicastu v IPv6.
- [x] Autonomní systémy. Protokoly IGP (Interior Gateway Protocol) a EGP (Exterior Gateway Protocol). Základní charakteristika protokolu BGP (Border Gateway Protocol). Multihoming, peering a tranzit.
- [x] Teorie konečných automatů a její použití v oblasti komunikačních protokolů, způsoby grafické reprezentace.

### MPC-CT3

- [x] Bezpečnost na vrstvě L1 (bezpečnostní opatření, klíčování, dohled nad sítí) a bezpečnost na vrstvě L2 (bezpečnostní opatření, příklady útoků, MACsec).
- [x] Bezpečnost na vrstvě L3 (bezpečnostní opatření, příklady útoků, IPsec, bezpečnost IPv6).
- [x] Bezpečnost TCP (útoky, protiopatření), protokol TLS - Transport Layer Security (princip, součásti, příklady útoků).
- [x] Bezpečnost UDP (útoky, protiopatření, zabezpečení nad protokolem UDP), bezpečnost DNS, protokol DNSSEC.
- [ ] Zabezpečení v sítích typu Low-Power Wide Area Network (kryptografické ochrany, problémy a omezení), zabezpečení v mobilních sítích 2G - 5G (základní principy bezpečnosti pro 2G, 3G a 4G), bezpečnost a slabiny optických sítí.
- [x] Ochrana soukromí v ICT (pojmy, typy anonymizace), kryptografické metody zajištující ochranu soukromí, síťové metody poskytující ochranu soukromí a anonymizační nástroje a systémy.
- [ ] Forenzní analýza (hlavní cíle, základní principy, vysvětlete časové značky a časovou osu událostí).
- [x] Analýza škodlivého kódu (základní dělení analýz, cíle a metody statické a dynamické analýzy).
- [ ] Penetrační testování (rozdíly v penetračním testování realizovaným metodou Ad-hoc a pomocí metodologie, hlavní cíle ASVS metodologie, bezpečnostní úrovně) a testování bezpečnosti webové aplikace (zranitelnost Path traversal).
- [ ] Standardy v kyberbezpečnosti (ISO, PCI DSS, FIPS, známé organizace), certifikace a hodnocení kyberbezpečnosti (Common Criteria, OWASP).

### MPC-PDA

- [ ] Hierarchie výpočetní složitosti. P, P-úplné, NP, NP-úplné, PSPACE, EXP-SPACE, HP těžké, rozhodnutelné, nerozhodnutelné. Definice problému s batohem. Definice problému k-řezu. Definice problému obchodu.
- [ ] Optimalizace: Genetické programování, inicializace, křížení, mutace. Optimalizace rojem částic. Optimalizace mravenčí kolonií.
- [x] Grafy – incidenční matice, matice sousedností. Handshaking lemma. Silně propojené komponenty grafu. Silně propojené komponenty – Kosarajův algoritmus, Tarjanův algoritmus.
- [ ] Detekce cyklů v grafu. Eulerova cesta grafem, Hamiltonovská cesta grafem. Floyd-Warhsallův algoritmus. Algoritmus rozpoznání bipartitiního grafu.
- [ ] Párování grafu, problém maximální shody – definice, Maďarský algoritmus. Problém časové tabule. Algoritmus barvení grafu. Isomorfismus grafu – Ullmanův algoritmus.
- [ ] Definice toku sítí. Problém maximálního toku / minimálního řezu. Ford Fulkersonův algoritmus.
- [ ] Univerzální aproximační teorém. Neuron, Maticová verze dopředné neuronové sítě. Rychlost učení. Dávky a minidávky a efekt na učení se. Vrstva zahazování.
- [ ] Definice konvoluční neuronové vrstvy. Metody regularizace. Přenesené učení a známé předučené sítě.
- [ ] Lineární a polynomiální regrese. Logistická regrese. Optimalizace s pomocí gradientního sestupu.
- [x] Rekurentní neuronové sítě. Popis LSTM vrstvy. Segmentace – U sítě.
- [x] Zpětnovazební učení, Q-učení. Průzkum vs. využití. SARSA.
- [ ] Metody náhodného průchodu, metoda Node2Vec. Členění druhů umělé inteligence. Pojmy: kombinatorická generalizace, relační induktivní zaměření.

### MPC-ODP

- [x] Režim omezení odpovědnosti poskytovatelů služeb informační společnosti typu mere conduit, caching a hosting
- [x] Aktivní povinnosti poskytovatelů služeb informační společnosti (monitoring, filtrování)
- [x] Pojem osobního údaje, titul ke zpracování osobních údajů, zvláštní kategorie osobních údajů
- [ ] Právní postavení správce a zpracovatele osobních údajů
- [ ] Práva subjektů osobních údajů
- [x] Povinné subjekty dle zákona o kybernetické bezpečnosti
- [x] Bezpečnostní opatření, varování, reaktivní opatření a ochranná opatření dle zákona o kybernetické bezpečnosti
- [x] Procesní nástroje pro zajištování elektronických důkazů
- [x] Typy a znaky skutkových podstat počítačových trestných činů
- [x] Subjektivní a objektivní odpovědnost

### MPC-CSI

- [ ] Popis diskrétních signálů. Vyjádření binárních čísel. Energetické a výkonové signály. Periodické signály. Základní 1D a 2D signály. Spektrum DFŘ a DFT. Algoritmus FFT. Transformace Z (1D a 2D). Zpětná transformace Z, reziduová věta.
- [ ] Vnější a stavový popis 1D a 2D diskrétních systémů. BIBO stabilita a kauzalita. LTI 1D diskrétní systém. Grafy signálových toků- Masonovo pravidlo. Celková, vynucená a přirozená odezva. Systémy typu IIR a FIR. Metoda odstranění přesahu a metoda přičtení přesahu. LSI 2D diskrétní systém a jeho vlastnosti. Spojování 1D a 2D systémů z dílčích sekcí.
- [ ] Maticový zápis, 1. kanonická a 2. kanonická struktura. Kontrola kauzality diskrétního systému a její algoritmizace. Autonomní diskrétní systém a generace harmonického signálu. Postup návrhu číslicových filtrů.
- [ ] Systém s minimální fází, fázovací článek, inverzní systém. Určení signálu z reálné části spektra. Vzorkování pásmově omezených signálů. Reálný signál, analytický signál a komplexní obálka. Hilbertova transformace pro spojité a diskrétní signály. Kvadraturní modulátor a demodulátor.
- [ ] Goertzelův algoritmus. Rozkladová a rekonstrukční banka číslicových filtrů, výpočet spektra diskrétního signálu pomocí rovnoměrné DFT banky. Polyfázová reprezentace signálů. Subpásmové kódování. QMF číslicové filtry. Perfektní rekonstrukce. Transmultiplexery
- [ ] Gaborova transformace a krátkodobá Fourierova transformace. Empirická modální dekompozice. Wavelety a jejich tvorba. Spojitá a diskrétní waveletová transformace. Waveletová transformace s diskrétním časem. Souvislost waveletové transformace s bankami číslicových filtrů. Dvourozměrná vlnková transformace.
- [ ] Popisná statistika, statistický model. Empirický a teoretický model rozdělení. Zákon velkých čísel, centrální limitní věty. Náhodný výběr, statistiky, testování statistických hypotéz. Chyba prvního a druhého druhu. Parametrické a neparametrické testy, testy dobré shody. P-P plot, Q-Q plot. Základní míry statistické vazby.
- [ ] Přímá a zpětná lineární předpověď. Výpočet lineárních predikčních koeficientů. Křížové struktury typu AR a ARMA a jejich využití. Volba řádu modelu. Použití lineární predikčníní analýzy pro kompresi řečového signálu.
- [ ] Definice výkonové spektrální hustoty a její vlastnosti. Bílý šum. Působení lineárního systému na náhodný proces. Neparametrické a parametrické metody.
- [ ] Zobecněný princip superpozice. Komplexní a reálné kepstrum. Rozbalení fáze. Homomorfní filtrace, definice a její použití. Aproximace exponenciální funkce pomocí řetězových zlomků.

### MPC-MPG

- [ ] Světlo, barva. Barevné modely a prostory (RGB, CMY, CMYK, HLS, YCBCR, Lab, stupně šedi). Gama korekce.
- [ ] Obraz jako dvojrozměrný signál. Vzorkování spojitého obrazu, kvantování. Aliasing, moiré. Vektorová vs. bitmapová grafika - výhody, nevýhody. Transformace obrazu (DFT, DCT, DWT).
- [ ] Základní zobrazovací režimy, struktura systému s grafickým adaptérem, paměť snímku, bitové roviny.
- [ ] Základy vektorové grafiky. Matematický popis 2D křivek. Typy navázání dvou křivek. Princip a postup rasterizace základních prvků – přímka, kružnice, elipsa.
- [ ] Pláty a Bézierovy kubiky v 3D, řídicí body. Typy navazování plátů. Algoritmus de Casteljau pro jejich polygonizaci, subdivision.
- [ ] Homogenní souřadnice a jejich použití při geometrických transformacích (posun, rotace, změna měřítka a podobně). Promítání rovnoběžné a středové, pohledový objem.
- [ ] Texturování, mapování 2D textur na 3D objekt, interpolace textur, komprese textur. Bitmapové a procedurální textury.
- [ ] Formáty vyjádření čísel, pevná a pohyblivá řádová čárka, aritmetika procesoru.
- [ ] Třídění paralelních systémů. Proudové zpracování instrukcí, cache, technologie SIMD.
- [ ] Architektury moderních grafických procesorů (GPU). Řetězec zpracování grafických dat. GPU jako paralelní systém. Jazyk CUDA.

### MPC-NAV

- [ ] Počítač, mikroprocesor, princip funkce, architektury počítačů, CISC, RISC, úzké profily.
- [ ] Mikroprocesory 8086, 80286, chráněný režim, adresace v chráněném režimu.
- [ ] Mikroprocesor 80386, stránkování, deskriptor, adresace se stránkováním.
- [ ] Vyrovnávací paměť, 80486, zavedení násobných jednotek, Pentium, jednotka MMX.
- [ ] Superskalární architektura mikroprocesoru, mikroprocesory Pentium Pro, Pentium II, SSE, PIII.
- [ ] Architektura Netburst, Pentium IV, multiprocessing a jeho implementace u PIV, GPR registry x86-64.
- [ ] Architektura mikroprocesorů AMD64, APU a jeho implementace, mikroarchitektura Core a Core iX, jednotka AVX.
- [ ] Operační paměť, parametry, typy operačních pamětí, synchronní paměti DRAM (DDR, DDR2, DDR3, DDR4), parametry a vlastnosti, paměťové moduly.
- [ ] Sběrnice, parametry, typy, hierarchie, interní sběrnice PC, sběrnice PCI, port AGP, sběrnice PCI-Express, sběrnice HyperTransport, QPI.
- [ ] Čipová sada, parametry a vlastnosti, typy, hierarchie, vývoj čipových sad.

### MPC-OSE

- [ ] Přenosové vlastnosti optických vláken, vlákna mnohovidová a jednovidová, polymerová optická vlákna (POF).
- [ ] Výroba optických vláken, druhy vláken a kabelů (standardy UIT – T, G xxx), spojování optických vláken a kabelů, optické konektory.
- [ ] Zdroje a detektory záření - jejich charakteristiky.
- [ ] Teoretické problémy přenosu optickou sítí - vlnová optika a geometrická optika. Nelineární vlivy u optických vláken.
- [ ] Vlnové délky a pásma využívaná pro přenos, útlum a disperze vláken, disperze chromatická - CD a polarizační – PMD, doporučení UIT. Metody potlačování dispersních vlivů.
- [ ] Optické opakovače a zesilovače.
- [ ] Optické přístupové sítě - FTTx, optické transportní sítě, globální sítě. Výhledy sítí FTTH.
- [ ] Optické linkové zakončení, optické linkové kódy, dosah optického spoje. Optoelektronické linkové trakty. Příklady sítí různých provozovatelů.
- [ ] Multiplexování u optických přenosů - WDM, DWDM, CWDM.
- [ ] Transmisní a reflektometrická (OTDR) metoda měření optických vláken. Metody měření CD a PMD. Dohled (monitoring) optických telekomunikačních sítí.

### MPC-PLD

- [ ] Struktura obvodů FPGA, porovnání s ASIC, realizace logických funkcí strukturou v FPGA (LUT). Princip implementace designu do FPGA (syntéza, mapování, PAR).
- [ ] Kombinační a sekvenční obvody, synchronní a asynchronní systémy: principy, vlastnosti. Klopné obvody: staticky/dynamicky řízené, synchronní/asynchronní nulování/nastavení.
- [ ] Časové parametry digitálních obvodů, nastavení omezujících podmínek (constraints), statická časová analýza, metody optimalizace časových parametrů (pipelining, register retiming, register replication). Hodinové domény.
- [ ] Vlastnosti LUT a její alternativní využití v FPGA, blokové paměti, bloky pro syntézu kmitočtu a zpracování hodinových signálů, struktura I/O buňky, I/O standardy.
- [ ] Realizace synchronních čítačů v obvodech PLD: binární, Grayův, LFSR - výhody, nevýhody, popis pomocí jazyka HDL.
- [ ] Stavové automaty: typ Moore a Mealy - blokové schéma, typy výstupů, stavové diagramy, ekvivalentní stavy, kódování stavů v obvodech PLD a FPGA, nepracovní (nevyužité) stavy a jejich ošetření.
- [ ] Ověření funkce navržené konstrukce, simulace, verifikace, testbench.
- [ ] Jazyk VHDL: behaviorální a strukturální styl popisu, souběžné a sekvenční příkazy, proměnné, signály, porty, process, slohy.
- [ ] Rychlá sériová komunikace a bloky pro její podporu v FPGA, multigigabitové transceivery, návrh plošných spojů, napájení obvodů FPGA. Technologie FPGA (FLASH, SRAM, Antifuse) – vlastnosti.
- [ ] Číslicové zpracování signálů v FPGA, bloky pro podporu DSP operací, binární reprezentace čísel. Procesory v FPGA, vestavěné (embedded) systémy, systém na čipu (SoC).

### MPC-PZO

- [ ] Základní vlastnosti rastrového obrazu, okolí pixelu, vzdálenost pixelů. Jasové transformace: základní typy, gama korekce. Histogram, ekvalizace histogramu: odvození pro spojitou funkci, přechod k diskrétním hodnotám, souvislost distribuční funkce s ekvalizační procedurou.
- [ ] Geometrické transformace obrazu: euklidovské, afinní, projektivní, transformační rovnice, význam jednotlivých prvků transformační matice. Interpolační techniky: nejbližší soused, bilineární.
- [ ] DFT, filtrace obrazu: základní transformační rovnice pro DFT, vlastnosti spektra, SS složka, maximální obrazová frekvence, postup při filtraci, základní typy filtrů, konvoluční teorém.
- [ ] Detekce hran, objektů v obraze: vyhlazovací prostorové filtry, metody výpočtu první a druhé derivace obrazové funkce, princip zostření obrazu pomocí Laplaciánu, jednorozměrná hrana a její derivace.
- [ ] Základy segmentace: Cannyho hranový detektor, přehled a popis prahovacích metod. Metoda detekce objektů dle Violy-Jonese: definice Haarových příznaků, trénování, řazení do kaskády.
- [ ] Biometrická obrazová identifikace: přehled metod a jejich základní vlastnosti, třídy otisků prstu, markanty, rozpoznání tváří metodou PCA, vysvětlení principu vlastních vektorů.
- [ ] Model kamery: popis přímky a bodu v projektivní rovině, paralelní promítání, perspektivní promítání, intrinsické parametry, extrinsické parametry, scéna se dvěma pohledy (disparita), princip kalibrace. Homografie: tři základní typy, důkaz existence matice H pro zobrazení roviny snímané perspektivní kamerou, skládání panoramatického pohledu: válcové, kulové souřadnice, detektory významných bodů.
- [ ] Epipolární geometrie: kamerová báze, epipól, epipolární rovina, epipolární svazek, epipolární přímky, geometrická podstata, základní rovnice mapování bod->přímka, rektifikace stereo páru do jednoduché geometrie. Extrakce prostorové informace: jednoduchá stereo geometrie, disparitní mapa, disparitní prostor, korespondenční problém, základní princip dynamického programování.
- [ ] Optický tok: aperturový problém, charakteristika metod dle Horna-Schuncka, dle Lucase-Kanadeho, pojem časoprostorová krychle, algoritmus SimpleFlow, algoritmus dle Farnebäcka.

### MPC-SSY

- [ ] Základní architektura AVR mikroprocesorů, dostupné periférie, práce s registry.
- [ ] Pamětní prostor mikroprocesoru AVR - FLASH paměť, SRAM paměť, EEPROM paměť.
- [ ] Sériový přenos dat. Sběrnice USART, SPI, I2C.
- [ ] Čítače/časovače, režimy funkce, princip, využití.
- [ ] Rozdělení senzorů, senzory neelektrických veličin, principy. A/D převod, parametry převodníků, chyby A/D převodu.
- [ ] Princip šíření rádiového signálu prostředím, využívané antény a jejich vlastnosti.
- [ ] Standard IEEE 802.15.4 a jeho rozdělení. Fyzická vrstva dle IEEE 802.15.4. Detekce energie na kanále, parametr RSSI, parametr LQI, formát rámce na fyzické vrstvě IEEE 802.15.4
- [ ] Definice linkové vrstvy dle IEEE 802.15.4, formát rámce, struktura super-rámce, typy zařízení, mezirámcové intervaly, synchronizovaná a nesynchronizované metoda CSMA/CA.
- [ ] Protokol ZigBee, definice síťové vrstvy, formát NWK rámce, směrování v mesh síti pomocí AODV, směrování ve stromové struktuře. Směrovací tabulky – dočasná a trvalá, tabulka sousedů, Aplikační vrstva.
- [ ] Protokoly Bluetooth a Bluetooth Low Energy, LORA, SigFox. MQTT protokol pro Internet věcí.
- [ ] Protokoly pro průmyslové aplikace, lokalizace bezdrátových uzlů, energetická spotřeba při přenosu dat.

### MPC-SKS

- [x] Služby komunikačních systémů – obecný rozbor, signalizační systém SS7, Telecommunication Management Network - TMN, telekomunikační služby z pohledu ekonomiky.
- [x] Integrované služby digitální sítě – ISDN, základní a primární přístup, referenční model účastnické přípojky ISDN, strukturu rámce na rozhraní S a U, napájení terminálů.
- [x] Asynchronní přepravní způsob – ATM, buňka ATM, synchronizace, virtuální cesta a virtuální kanál, třídy služeb, ATM vrstvový model, síťové prvky ATM.
- [x] Digitální účastnická přípojka xDSL, HDSL, ADSL, spojení, referenční model, modulace, rušivé vlivy, přeslechy.
- [x] IPv6, návaznost na IPv4, kvalita služeb QoS, referenční model OSI versus síťová architektura TCP/IP.
- [x] Pasivní optické sítě (topologie sítě a způsob komunikace sestupný/vzestupný směr).
- [x] Vývoj pasivních optických sítí a jejich rozdíly z pohledu fyzické a přenosové vrstvy.
- [x] Aktivační proces koncové jednotky v síti GPON.
- [x] Využití celočíselného programování v současných sítích, síť jako graf, rozdělení zátěže z pohledu ceny přenosu.
- [x] IP přenos sítí wavelength division multiplexing (WDM), CWDM, DWDM, TDM versus WDM, problematika přiřazování vlnových délek (RWA).

### MPC-UIN

- [ ] Umělá inteligence (UI) - definice, základy UI, historie UI, oblasti aplikací UI.
- [ ] Perceptron - charakteristika, neuron, topologie, algoritmus učení, vybavování, Minského kritika perceptronu.
- [ ] Umělé neuronové sítě - základní terminologie a rozdělení UNN: neuron, topologie, učení, vybavování
- [ ] Vícevrstvá neuronová síť - charakteristika, neuron, topologie, algoritmus učení "error back propagation", vybavování.
- [ ] Hopfieldova síť - charakteristika, neuron, topologie, algoritmus učení, vybavování.
- [ ] Kohonenova samoorganizační mapa - charakteristika, topologie, neuron, algoritmus učení, vybavování.
- [ ] RCE síť - charakteristika, neuron, topologie, algoritmus učení, vybavování.
- [ ] Expertní systémy (ES) - historie znalostních systémů, definice, typy ES, pravidlový ES, tvorba BZ, konzultace, přínosy ES.
- [ ] Inteligentní robot - inteligentní systém, generace robotů, inteligentní (kognitivní) robot, blokové schéma inteligentního robota.

### MPC-VDP

- [ ] Komunikační řetězec, vrstvový model datového přenosu, základní operace při zpracování signálu u digitálního komunikačního systému. Úrovně signálu a vztažné hodnoty, absolutní a relativní úroveň, útlum, zisk, odstup signálu od šumu, výkonová spektrální hustota, přenosová kapacita kanálu.
- [ ] Princip zvyšování odolnosti přenášené zprávy proti chybám, informační poměr kódu, Hammingova vzdálenost, podmínky možnosti detekce a korekce chyb.
- [ ] Vlastnosti ovlivňující návrh protichybového kódového systému. ARQ systémy.
- [ ] Rozdělení protichybových kódů. Schéma realizace procesu kódování blokových kódů a stromových kódů. RM kódy, jejich základní parametry. Obecné blokové schéma kodéru turbokódu, význam jeho částí, dekódování turbokódů. Přehled možností používaných pro zabezpečení proti dlouhým shlukům chyb.
- [ ] Kryptografické metody zabezpečení datových přenosů, architektura bezpečnosti, služby bezpečnosti, mechanizmy bezpečnosti.
- [ ] Metalická vedení, náhradní schéma homogenního vedení, primární parametry, sekundární parametry jednotky a vzájemné vztahy. Konstrukce symetrických kabelových vedení používaných v přístupové síti, DM a x čtyřky. Modely elektrických parametrů kabelových vedení určené pro simulaci DSL.
- [ ] DSL systémy, vlastnosti, referenční konfigurace, typické uspořádání přípojky, možnosti využití. Základní charakteristiky jednotlivých systémů ADSL, VDSL, vlastnosti, použití.
- [ ] Vliv rušení na provoz xDSL, kategorizace, dosažitelná přenosová rychlost, model přeslechů (NEXT, FEXT), princip výpočtu přeslechů. Spektrální vlastnosti DSL přenosových systémů, správa spektra, cíle, metody.
- [ ] PLC systémy - praktické využití v energetice - limity technologie, datové objemy, rušení a opakovače. Chytré elektroměry - DLMS protokol a OBIS objekty.
- [ ] IoT technologie - LoRa, SigFox, NB-IoT.

### MPA-KPM

- [ ] Legacy cellular systems 0G, 1G, 2G: Network architecture, medium access control, packet switching, and circuit switching techniques. Multiple access (FDMA, TDMA, CDMA).
- [ ] 3G cellular systems: Network architecture, handover types, modulation schemes (CDMA, WCDMA), radio interface channel architecture.
- [ ] 4G cellular systems: Modulation schemes for LTE (OFDM, OFDMA, SC-FDMA), error-control methods (ARQ/HARQ).
- [ ] 4G cellular systems: IP-based architecture (E-UTRAN, EPS vs. EPC), LTE radio resource grid (frame structure, slot structure). Utilization of the frequency spectrum, physical layer (physical channels, transport channels).
- [ ] 4G cellular systems: Key blocks within the communication infrastructure (RAN, EPC), EPS communication levels with UE (AS, NAS).
- [ ] 4G cellular systems: EPS bearers, protocol architecture (control plane, user plane X2 interface), EPC tracking area update procedure.
- [ ] 4G cellular systems: EPS protocol architecture (Control Plane, User Plane), S1 interface, S5/S8 interface, X2 interface,
- [ ] 4G cellular systems: RRC states (RRC Idle, RRC Connected), EPS Connection Management (ECM Idle, ECM Connected), EPS mobility management (EMM Registered, EMM Deregistered), EPS Radio Resource Management (RRM).
- [ ] 4G cellular system: VoLTE (architecture, principles), CSFB, SVLTE, VoWiFi, Quality of Service (QoS) mechanisms in LTE (QCI), EPS security (key hierarchy and their relations).
- [ ] Next-generation heterogeneous systems: Different types of use cases: eMBB (enhanced Mobile Broadband), URLLC (Ultra Reliable Low Latency Communications), mMTC (massive Machine Type Communications). Utilization of the frequency spectrum (sub-6GHz, millimeter wave).

### MPC-MOS

- [ ] Základní vlastnosti a komponenty modelu systému front. Kendallova klasifikace. Charakterizace systémů M/M/1 a M/M/1/0
- [ ] Chování ideální a reální sítě a její reakce na rostoucí zatížení.
- [ ] Algoritmy ochrany proti zahlcení sítě: zpětný tlak (backpressure), tlumící paket (choke packet), implicitní a explicitní signalizace zahlcení.
- [ ] Metody řízení toku dat na úrovni linkové vrstvy, normovaná propustnost jednotlivých mechanismů.
- [ ] Transportní protokol TCP: mechanizmus alokace kreditů, vliv velikosti okna na výkonnost protokolu TCP. Implementační detaily protokolu TCP: možnosti opakovaného vysílání, způsoby odesílání, doručení a převzetí TCP segmentů.
- [ ] Samočasovací chování protokolu TCP. Mechanismy pro nastavení doby odezvy (RTT) a technika pomalého startu.
- [ ] Mechanismy správy plovoucího okna: dynamické nastavení velikosti okna v případě zahlcení, rychlý opakovaný přenos, rychlé zotavení
- [ ] Mechanismy ochrany proti zahlcení: Random Early Detection (RED) a Weighted Random Early Detection (WRED), Explicit Congestion Notification (ECN)
- [ ] Zajišťování kvality služeb v datových sítích, dohled nad síťovým provozem, klasifikace paketů, řízené odesílání paketů
- [ ] Zajištění kvality služeb v bezdrátových sítích řady 802.11: základní metody řízení přístupu k médiu a jejich rozšíření podle standardu 802.11e - Rozšířený distribuovaný přístup ke kanálu (EDCA), Přístup ke kanálu řízený pomocí HCF (HCCA)

### MPC-MOK

- [x] Lattice: lattice definition, base of a lattice, CVP problem, SVP problem, Hadamard ratio, Babai algorithm, GGH public key cryptosystem.
- [x] LWE and RLWE: LWE problem, RLWE problem, Regev one-bit cryptosystem.
- [x] Lattice-based protocols: Module-LWE problem, LWR problem, NTT, KYBER scheme, SABER scheme.
- [x] Homomorphic Encryption (HE): homomorphism, HE definition, kind of HE (partially, somewhat, fully), Bootstrapping, Paillier Cryptosystem
- [x] Secret Sharing: Threshold Secret Sharing, Shamir Secret Sharing, unique polynomial theorem, Interpolation problem.
- [x] Secure Multi-Party Computation (SMPC): SMPC definition, SMPC security requirement and adversarial behavior, e-voting, oblivious transfer
- [ ] Blockchain and Smart Contracts: blockchain architecture, transactions and blocks, mining, forks, consensus, smart contracts, 51 % attack on blockchain.
- [ ] Cryptocurrencies: cryptocurrency (definition, requirements), Ecash, Bitcoin, CryptoNote, proof of work in Bitcoin, Bitcoin address and wallet, Bitcoin’s transaction flow, double spending problem.
- [x] Data privacy 1: statistical disclosure control methods, disclosure risk, information loss, microdata, privacy categories (identifiers, quasi-identifiers, sensitive data), non-perturbative methods (sampling, global recording, suppression)
- [x] Data privacy 2: syntethic data, perturbative masking (noise addition, microaggregation, rank swapping), k-anonymity, record linkage
