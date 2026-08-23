# Miniprojekti: 1-vuotistarkastuksen ennakkoselvitys 2026

## Tavoite

Valmistella Kultarinnantie 20 A:n riippumaton ennakkotarkastus ennen rakennuttajan varsinaista 1-vuotistarkastusta.

Tavoitteena ei ole tehdä yleistä vanhan talon kuntotarkastusta, vaan tunnistaa noin vuoden ikäisessä uudiskohteessa uskottavat toteutus-, käyttöönotto- ja dokumentointipuutteet silloin, kun ne ovat vielä selkeästi rakennuttajan vastuu-/takuukeskustelun piirissä.

## Periaate

Jokaisessa teknisessä kokonaisuudessa pyritään muodostamaan ketju:

> **suunnitelma → käyttöönotto-/mittaustulos → nykyinen pistokoe → johtopäätös**

Johtopäätös kirjataan muodossa:

- OK / vastaa dokumentoitua tavoitetta
- poikkeama
- ei todennettavissa käytettävissä olevalla aineistolla

Pelkkä visuaalinen “näyttää hyvältä” ei ole riittävä silloin, kun lähtöarvo tai käyttöönottotulos on olemassa.

## Nykytila 2026-08-23

Puhelimelta löytynyt `Kultsi`-aineistopaketti tuotiin Google Driveen ja järjestettiin Kultarinnantie 20 -pääkansion alle nimellä `Technical Documentation`.

Aineisto muutti aiempaa tilannekuvaa olennaisesti. Nyt löytyvät mm.:

- pääpiirustukset A/B/C ja asemapiirros
- ilmanvaihtosuunnitelmat A/B/C, molemmat kerrokset
- alkuperäiset ilmamäärämittaukset A/B/C
- vesi- ja viemärisuunnitelmat A/B/C sekä asemakuva/kaivokuvat
- lämpöjohtosuunnitelmat A/B/C
- lattialämmityssuunnitelmat ja laskelma
- painekoepöytäkirjat
- tiiveysmittausraportit A/B/C
- sähkön teho- ja valaistussuunnitelmat A/B/C sekä asemakuva
- sähkön käyttöönottotarkastuspöytäkirjat A/B/C
- rakennustapaselostus
- kodin käyttö- ja huolto-ohje
- loppukatselmuspöytäkirjan kopio
- hallinnanjako- ja kiinteistöasiakirjoja

## Tällä hetkellä tärkeimmät avoimet kysymykset

### P0 — loppukatselmuspöytäkirjan täydellisyys

Driveen löytynyt loppukatselmuspöytäkirja sisältää sähköisen allekirjoituksen kansilehden ja varsinaisen Espoon rakennusvalvonnan pöytäkirjan sivun `1 (2)`. Varsinaista sivua `2 (2)` ei ole vielä löytynyt.

**Exit:** täydellinen loppukatselmuspöytäkirja on saatu ja mahdolliset ehdot/huomiot on huomioitu tarkastusbriefissä.

### P0 — Rakmentor-tarkastuksen todentava toteutus

Rakmentorilta on pyydetty rakennus-, LVI- ja sähköasiantuntijan yhteistä tarkastusta. Tarkastuksen pitää hyödyntää nyt löytyneitä lähtödokumentteja eikä jäädä pelkäksi visuaaliseksi kierrokseksi.

**Exit:** sovittu kirjallisesti, mitkä vertailut ja pistomittaukset tehdään sekä mitä tuloksia raporttiin kirjataan.

### P1 — ilmanvaihto / NIBE S735 + SAM

Aiemmin on esiintynyt toistuvaa matalataajuista vihellys-/ulvontaääntä. Huoltokäynnin jälkeen oire poistui, mutta juurisyy tai tehdyt asetusten muutokset eivät ole dokumentoituna.

Tarkastuksessa:

- verrataan pistemittauksia alkuperäisiin ilmamäärämittauksiin ja IV-suunnitelmiin
- mitataan rakennuksen paine-ero ulkoilmaan
- tarkastetaan näkyvät kanavat, venttiilit, kondenssivedet, eristykset ja liitokset
- tarkastetaan relevantit NIBE/SAM-asetukset ja puhallintilat
- kirjataan aiempi äänihavainto historiatietona, ei oletettuna nykyvikana

### P1 — märkätilat

Tarkastetaan ainakin:

- käytännön vesikoe ja lattiakaadot
- kaivot ja näkyvät liittymät
- läpiviennit, kynnykset sekä seinä-lattialiittymät
- pintakosteuskartoitus indikatiivisena mittauksena
- laatat, saumat, silikonit, halkeamat ja mahdolliset kopolaatat
- poistoilmavirta ja siirtoilman toiminta

Lisäksi selvitetään, löytyvätkö vedeneristyksen toteutus-/laadunvarmistuskuvat tai tarkastusasiakirjat.

### P1 — sähkö ja sähköauton latausvalmius

Rakennustapaselostuksessa luvataan, että sähkökaapelointi mahdollistaa nopean sähköauton latauspisteen asentamisen.

Nyt käyttöönottotarkastuspöytäkirja ja sähköpiirustukset löytyvät. Tarkastuksessa varmistetaan lisäksi käytännössä:

- syöttö pysäköintipaikalle
- vaiheistus ja johdinpoikkipinta
- sulake-/suojalaitevaraus
- keskuksen kapasiteetti
- realistinen latausteho
- tarvitaanko vielä uutta kaapelointia tai kaivamista
- kuormanhallinnan tarve
- mitä fyysisesti puuttuu ennen latauslaitteen asennusta

### P2 — rakentamisen laadunvarmistusdokumentit

Selvitettävä vielä ainakin:

- märkätilojen vedeneristyksen QA / valokuvat / tarkastusmerkinnät
- rakentamisen aikaiset kosteus- ja kuivumismittaukset, jos sellaisia on tehty
- rakennusluvan edellyttämien vesi-, ilmanvaihto- ja lämmityslaitteiden katselmusten/tarkastusten merkinnät, jos ne eivät sisälly muuhun loppudokumentaatioon
- NIBE/SAM-käyttöönotto- ja huoltodokumentit sekä mahdollinen kirjaus aiemmasta äänihäiriöstä

## Rajaus

Tämä branch on työtila yhdelle rajatulle miniprojektille. Varsinaisia talon PDF:iä ei kopioida GitHubiin. Google Drive on alkuperäisaineiston säilytyspaikka; GitHub toimii tilannekuvana, päätöslokina ja tehtävien kontrollipintana.
