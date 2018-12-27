# Hálózati operációs rendszerek gyakorlat tantárgy	

            13.3.2. Linux kiszolgáló telepítése és üzemeltetése	 	96 óra/96 óra
1. A szerver hardver konfigurálása
1. A futási szintek beállítása, alapértelmezett futási szint beállítása, váltás a futási szintek között
1. A rendszer leállítása, újraindítása parancssorból
1. A lemezek partícionálása (a fájlrendszer és a swap terület elválasztása)
1. A boot manager telepítése és beállítása
1. Megosztott könyvtárak telepítése
1. Különböző csomagkezelők használata, a függőségek kezelése
1. Programok telepítése forrásból
1. A parancssor és héj használata (shell parancsok, a shell környezet konfigurálása, egyszerű szkriptek írása)
1. Parancssori szűrők használata, szöveges fájlok kezelése
1. Fájlok és könyvtárak kezelése (másolás, áthelyezés, törlés, helyettesítő karakterek, fájltulajdonságok lekérdezése, módosítása)
1. Folyamatok kezelése (előtérben, háttérben futtatás, folyamatok monitorozása, jel küldése folyamatnak)
1. Folyamatok futási prioritásának módosítása
1. Szövegfeldolgozás reguláris kifejezések segítségével
1. Egyszerű szövegszerkesztési lépések (pl. vi editor alapszolgáltatásai)
1. Fájlrendszer monitorozása, egyszerű hibák elhárítása
1. Fájlhozzáférések és lemezkvóták kezelése
1. Hardlink és szimbolikus link létrehozása, törlése
1. X Window konfigurálása, képernyőkezelők használata (pl. XDM, GDM, KDM)
1. Időzített rendszerfelügyeleti beállítások (cron)
1. Nyomtatási sor kezelése, általános nyomtatási hibaelhárítás
1. Hálózati címek beállítása, hálózati alapszolgáltatások használata (ftp, telnet, ssh, ping, dig, traceroute, tracepath)
1. Címfordítással kapcsolatos beállítások
1. Hálózati hibaelhárítás
1. Névfeloldás működése, beállításai (/etc/hosts, /etc/resolv.conf, /etc/nsswitch.conf, DNS)
1. Kétkulcsos titkosítása használata a biztonságos adattovábbításban (OpenSSH, GnuPG, X11 tunnels)
1. Forgalomirányítási beállítások
1. A rendszer biztonsági mentése, részleges és teljes mentés készítése, és rendszer visszaállítása ezekből
1. Apache webszerver telepítése, konfigurálása
1. Adatbázis kiszolgáló telepítése és üzemeltetése
1. Tűzfal és proxy szolgáltatások beállítása (iptables, squid, ACL, kliensazonosítás)
1. Levelezési szolgáltatások alapbeállításai (SMTP protokoll, postfix, sendmail, exim)

            13.3.3. Különböző hálózati operációs rendszerek integrációja
32 óra/32 óra
1. A különböző operációs rendszereket futtató gépek multiboot rendszerének beállítása
1. Samba szolgáltatás beállítása Linux szerveren Windows kliensek kiszolgálására
1. LDAP szolgáltatás beállítása Linuxon az Active Directory használatához
1. Exchange szerver elérése Linuxon futtatott POP3, IMAP kliensek segítségével

#### FELADATOK
1. Meghatározza a hálózati kiszolgáló funkciójának és várható terhelésének megfelelő hardvert 

1. Redundanciát és magas rendelkezésre állást biztosító tároló rendszert telepít és konfigurál

1. Kiválasztja a működési körülményeknek legmegfelelőbb hálózati operációs rendszer változatot, illetve disztribúciót

1. Kiválasztja a működési körülményeknek legmegfelelőbb hálózati operációs rendszer telepítési módot, partícionálja a merevlemezt, kiválasztja és létrehozza a fájlrendszert, feltelepíti a hálózati operációs rendszert

1. Beszerzi a szükséges eszközmeghajtó programokat és feltelepíti a rendszerbe

1. Telepíti az operációs rendszer biztonsági frissítéseit, kernelt konfigurál és fordít

1. Feltelepíti és beállítja a boot manager-t, testre szabja az indítási folyamatot, beállítja a rendszer futási szintjét és megfelelő módon leállítja, illetve újraindítja a kiszolgálót

1. Rendszerösszetevők és alkalmazások telepítéséhez csomagkezelő rendszert használ

1. Gondoskodik a különböző szerepkörök, tulajdonságok és szolgáltatások telepítéséről, kezeléséről, beállítja a szolgáltatások indításának módját

1. Hálózati címtárszolgáltatást telepít, konfigurál és üzemeltet; felhasználókat és csoportokat hoz létre, jelszókezelést végez

1. Hálózati csoportházirendet tervez meg és alkalmaz

1. Hálózati fájl- és nyomtató szolgáltatást telepít és konfigurál, beálltja a megosztásokat

1. Lemezkvótát állít be a felhasználók számára, beállítja a fájlrendszer jogosultsági és tulajdonosi rendszerét

1. Testre szabja és használja a shell környezetet, egyszerűbb feladatok megoldására scripteket készít

1. Ütemezett feladatkezelést végez

1. Dinamikus IP-címkiosztást biztosító hálózati szolgáltatást telepít

1. Hálózati operációs rendszeren működő dinamikus forgalomirányítási protokollt telepít és konfigurál

1. Beállítja a szoftveres tűzfalat és az egyéb fejlett biztonsági funkciókat

1. DNS kiszolgálót telepít és konfigurál

1. Web kiszolgálói feladatokat biztosító hálózati szolgáltatást telepít és konfigurál, virtuális web kiszolgálót és virtuális könyvtárat hoz létre 

1. FTP szervert telepít, konfigurál, virtuális FTP szervert, virtuális könyvtárat létrehoz

1. E-mail kiszolgálót telepít és konfigurál

1. Adatbázis kiszolgálót telepít és konfigurál

1. Biztonságos távoli elérést biztosító szolgáltatást telepít és konfigurál

1. Hálózati hozzáférés-védelmet telepít és állít be

1. Hálózati mentési és visszaállítási feladatot tervez meg és hajt végre

1. Monitorozza és felügyeli a hálózati operációs rendszer és az ügyfelek működését, naplózási beállításokat végez, naplófájlokat elemez

1. Virtualizációs környezetet telepít, virtuális munkaállomásokat és kiszolgálókat telepít

1. Felügyeli, monitorozza és optimalizálja a virtuális munkakörnyezetben üzemelő számítógépek működését

1. Egymással együttműködő és egymást kiegészítő funkciójú szabadforrású és üzleti szerver operációs rendszert egyaránt tartalmazó rendszert tervez, konfigurál és üzemeltet

1. Betartja a munka-, baleset-, tűz- és környezetvédelmi, valamint a távközlési szakmára vonatkozó előírásokat

#### SZAKMAI ISMERETEK
1. Hálózati operációsrendszerek telepítési módjai

1. Tároló-rendszerek típusai működési elvük

1. Hálózati címzés és címkiosztás (IPv4 és IPv6 címzés)

1. Szoftveres tűzfal és egyéb biztonsági beállítások

1. DNS és WINS alapok

1. Távoli elérést biztosító technológiák

1. Nyomtató kiszolgálás

1. Fájl kiszolgálás

1. Web- és FTP kiszolgálás

1. E-mail kiszolgálás

1. Adatbázis kiszolgálás

1. Hálózat felügyelet és a hibaelhárítás

1. Virtualizált környezet és hálózat, illetve virtuális gépek telepítése és beállítása

1. Munka-, baleset-, tűz- és környezetvédelmi előírások

#### SZAKMAI KÉSZSÉGEK
1. Bináris számrendszer használata 

1. IP-címzés 

1. Angol nyelvű, olvasott szakmai szöveg megértése és felhasználása

#### SZEMÉLYES KOMPETENCIÁK
1. Precizitás 

1. Megbízhatóság 

1. Önállóság 

1. Döntésképesség 

#### TÁRSAS KOMPETENCIÁK
1. Együttműködés 

1. Kezdeményezőkészség 

1. Prezentációs készség 

#### MÓDSZER KOMPETENCIÁK
1. Logikus gondolkodás 

1. Hibakeresés (diagnosztizálás) 

1. Problémamegoldás, hibaelhárítás 


