# Punch-Out
---

## Útskýring

Ég mun gera emulator um Punch-Out leikinn sem var gefinn út á Nintendo NES. Punch-Out er boxing leikur þar sem þú ert að spila einn character sem heitir Little Mac 
í gegnum boxing ferilinn hans og þú munt fara í gegnum fullt af andstæðingum sumir góður, sumir slæmir. 

---

Andstæðingarnir koma í eftirfarandi röð:
 - Minor Circuit: 
    - Glass Joe
    - Von Káiser
    - Piston Honda
 - Major Circuit: 
    - Don Flamenco
    - King Hippo
    - Great Tiger
    - Bald Bull
- World Circuit: 
    - Piston Honda (again)
    - Soda Popinski
    - Bald Bull (again)
    - Don Flamenco (again)
    - Mr. Sandman
    - Super Macho Man. 
 - THE CHAMPION: 
    - Mike Tyson

![Allir andstæðingar](PO-allCharacters.webp)

---

## Controls

| Takki | Hreyfing |
| ----------- | ----------- |
| Vinstri smellur | Vinstri líkams kýling |
| Hægri smellur | Hægri líkams kýling |
| W + vinstri smellur | Jab með vinstri hönd |
| W + Hægri smellur | Jab með hægri hönd |
| A | Dodge til vinstri |
| D | Dodge til hægri |
| S | Block |
| S (x2) | Duck |
| Space | Uppercut (Notar stjörnu) |

---

### Basic Reglur

Einn slagur er gerður af 3 roundum og aðeins 2 leiðir til þess að vinna slaginn. Það er annaðhvort með KO(knockout) og andstæðingurinn stendur ekki upp eða TKO(Technical knockout) sem gerist ef sama manneskjan er KO'd 3 sinnum í sama roundi. Ef andstæðingurinn er KO'd fær hann 10 sek til þess að standa upp. Ef hann nær
því ekki þá vinnur spilarinn. 

### Spilarinn er með health bar, stamina og stjörnur. 
- Health
  - Health barinn er til þess að sjá hversu margar kýlingar í viðbót maður getur tekið áður en maður er KO'd og fer niður þegar maður verður kýldur eða blockar. 
- Stamina
  - Stamina barinn er til þess að sjá margar hreyfinar þú getur gert. Hann fer niður eftir hverja kýlingu, dodge og block. Hann minnkar sérstaklega mikið þegar maður missir kýlingu. 
- Stjörnur
  - Stjörnurnar fær maður í gegnum leikinn með því að kýla andstæðingin þegar hann á ekki von á því. Stjörnurnar lætur mann geta gert uppercut og ein stjarna hverfur þegar maður verður hittur eða blockar.

Ef spilarinn verður KO'd þá verður hann að hægri og vinstri smella eins hratt og hann getur til þess að standa aftur upp og verður það erfiðara eftir hvert skipti sem hann verður KO'd.

### Hvernig round myndi fara

Spilarinn og andstæðingurinn byrjar á því að berjast og hægt er að blocka, dodgea eða countera kýlingar þangað til annaðhvort þeirra verður KO'd eða TKO'd. Andstæðingar eru tölvur sem stundum hafa ákveðið sem þau ætla að gera eins og t.d. að kýla eða uppercut. Sumir andstæðingar hafa Special Move og nota það á ákveðnum tíma leiksins. Það er hægt að countera öll special moves en oft er tímasetningin mjög erfið.

---

[Opponent Behaviours](https://www.neoseeker.com/punch-out/faqs/2911548-mike-tysons-opponent.html)

[Visualized behaviour](https://tomorrowcorporation.com/posts/retro-game-internals-punch-out-behavior-script)

[Video Útskýring](https://www.youtube.com/watch?v=tlKW723EOMA)
