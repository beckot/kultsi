# SIDE QUEST — toimittajien due diligence ennen lukitusta

Tilanne: 2026-09-05

## Mission

Varmista ennen 1-vuotistarkastuksen toimittajan lopullista lukitusta, ettei nykyisen value-suosituksen taustalla ole sellaista toimija-, referenssi-, talous-, koordinointi- tai matkakuluriskiä, joka muuttaisi päätöksen.

Tämä on rajattu side quest. Se ei avaa kilpailutusta uudelleen eikä muuta teknistä tarkastusbriefiä.

Nykyinen pääsuositus ennen tätä tarkistusta on:

**Suomen Talokatsastus + Caire Oy + SähköTTV**

Rakmentor on tekninen fallback. Tayka on aktiivinen challenger vain, jos heidän sähköpakettinsa valmistuu ennen päätöstä.

## Miksi side quest avattiin

Kotitalouden päätössanity-check nosti viisi ennen varausta tarkistettavaa asiaa:

1. liittyykö Talokatsastukseen, Caireen tai SähköTTV:hen olennaisia toimittajariskejä
2. ovatko referenssit, pätevyydet ja relevantti kokemus riittävän vahvoja juuri tähän toimeksiantoon
3. näkyykö yritysten taloudellisessa tilanteessa jatkuvuus- tai toimitusriskiä
4. onko kolmen toimijan kokonaisuus aidosti modulaarinen: voiko tarvittaessa käyttää vain 1/3 tai 2/3 osuudesta ilman että muu kokonaisuus hajoaa tai hinnoittelu muuttuu olennaisesti
5. mitkä Talokatsastuksen ja SähköTTV:n todelliset matkakulut ovat ja kuinka paljon ne kaventavat eroa Rakmentoriin

## Evidence rules

- Käytä ensisijaisesti yritysten omia sivuja, YTJ-/rekisteritietoa, julkisia taloustietoja ja riippumattomia arvostelu-/referenssilähteitä.
- Erota vahvistettu tieto, heikko signaali ja puuttuva tieto.
- Älä pidä korkeaa tähtiarviota yksin riittävänä näyttönä.
- Älä johda taloudellista vakautta liikevaihdosta yksin; katso vähintään toiminnan jatkuvuutta, maksuhäiriö-/verovelka-/konkurssi- tai muun olennaisen riskin signaaleja siltä osin kuin julkisesti saatavissa.
- Älä kopioi yksityisiä sähköposteja tai yksityisiä Drive-linkkejä public repoon.
- Matkakulut arvioidaan todellisen laskutusmallin ja lähtöpaikan perusteella, ei arvauksena.

## SQ-01 — toimijariskit

Arvioi erikseen:

### Suomen Talokatsastus Oy

- oikeushenkilö ja toiminnan jatkuvuus
- vastuullinen tarkastaja / tekijä
- onko palvelumalli riippuvainen yhdestä henkilöstä
- reklamaatio-/vastuu- tai muu julkinen riskisignaali, jos sellainen löytyy
- vastuuvakuutuksen tai muun ammatillisen vastuun signaali, jos julkisesti saatavilla tai tarjouksessa vahvistettavissa

### Caire Oy

- onko IV-mittaus ja -säätö aidosti ydinosaamista
- kuka tekee mittauksen
- käytettävä mittauskalusto / raportointikäytäntö siltä osin kuin vahvistettavissa
- toiminnan jatkuvuus ja toimitusriski

### SähköTTV

- onko sähköasennus/-mittaus aidosti ydinosaamista
- kuka tekee tarkastuksen ja millä pätevyydellä
- pystyykö toimija tekemään juuri sovitut käyttöönottotesteri-/keskus-/EV-valmiusmittaukset
- toiminnan jatkuvuus ja toimitusriski

**Exit:** kustakin toimijasta on `GREEN / AMBER / RED`-arvio ja lyhyt perustelu.

## SQ-02 — referenssit ja pätevyydet

Varmista ainakin:

- Matteus Knuutin koulutus ja AKK/FISE-status
- Talokatsastuksen referenssisignaali nimenomaan tarkastuksista / uudiskohteista / takuuvaiheen havainnoista, jos löydettävissä
- Cairen näyttö IV-mittaus- ja säätötöistä
- SähköTTV:n näyttö mittaus-/sähköasennustöistä ja tarkastuksen tekijän pätevyys
- riippumattomien asiakasarvioiden määrä ja laatu, painottaen sisältöä eikä tähtikeskiarvoa

Tärkein kysymys:

> Onko näyttö riittävä siihen, että näiden kolmen yrityksen tuottamaa raporttia uskaltaa käyttää rakennuttajan vuositarkastuksessa teknisenä tausta-aineistona?

**Exit:** referenssi-/pätevyysriski on luokiteltu ja mahdolliset ennen varausta tarvittavat vahvistukset on nimetty.

## SQ-03 — taloudellinen tilanne

Tarkista kustakin yrityksestä siltä osin kuin julkisesti saatavissa:

- yritys aktiivinen ja rekisterissä
- viimeisin saatavilla oleva liikevaihto / tulos / henkilöstö tai muu mittakaavasignaali
- mahdollinen verovelka-, maksuhäiriö-, saneeraus-, konkurssi- tai muu jatkuvuusriski
- onko yritys niin uusi/pieni, että yhden avainhenkilön riski on olennainen

Tavoite ei ole tehdä luottoluokitusta vaan vastata:

> Onko realistinen riski, että toimija ei pysty toimittamaan sovittua työtä tai raporttia lähiviikkoina?

**Exit:** `no material concern / concern / unknown` kustakin toimijasta.

## SQ-04 — kolmen toimijan modulaarisuus

Selvitä, voiko kokonaisuuden osat tilata ja toteuttaa itsenäisesti:

1. Talokatsastus / rakennustekniikka
2. Caire / IV-mittaukset
3. SähköTTV / sähkömittaukset

Varmista:

- tekevätkö Caire ja SähköTTV toimeksiannon vaikka jokin muu osa ei toteudu
- säilyykö heidän ilmoitettu hintansa silloin
- kuka koordinoi ajanvarauksen
- tulevatko raportit erikseen vai yhdistettynä
- voiko kaksi kolmesta toteuttaa ensin ja kolmas myöhemmin ilman evidenssiketjun heikkenemistä
- kenen vastuulla on havaintojen kokoaminen yhdeksi rakennuttajalle käyttökelpoiseksi paketiksi

Tämä tulkitsee sanity-checkin `1/3–2/3`-kysymyksen käytännöllisesti: **onko paketti aidosti jaettavissa ilman lock-inia tai olennaista lisäkustannusta.**

**Exit:** modulaarisuus on `YES / PARTIAL / NO` ja vaikutus päätökseen on kirjattu.

## SQ-05 — matkakulut

Nykyiset tiedot:

- Talokatsastus: 900 € + matkakulut, aiemmin ilmoitettu 1,35 €/km
- Caire: noin 200 €, matkakulut sisältyvät
- SähköTTV: 204 € + matkakulut
- Rakmentor: 2 259 € baseline

Selvitä ennen päätöstä:

- Talokatsastuksen laskutettava lähtöpaikka / kilometrimäärä / mahdollinen minimiveloitus
- SähköTTV:n laskutettava lähtöpaikka / kilometrikorvaus / mahdollinen matka-aikaveloitus
- lasketaanko kilometrit yhteen suuntaan vai meno-paluu
- onko pysäköinti tai muu matkalisä erikseen
- realistinen `low / expected / high` koko matkakuluille

Laske sen jälkeen:

`Talokatsastus-kokonaisuus = 1 304 € + kaikki todelliset matkakulut`

ja

`hintaetu Rakmentoriin = 2 259 € - Talokatsastus-kokonaisuus`

Päätöstä ei pidä perustaa 955 € säästöön ennen kuin matkakulut ovat mukana.

**Exit:** matkakulujen odotusarvo ja konservatiivinen yläraja on tiedossa.

## Decision rule

Kun SQ-01...SQ-05 on tehty:

### GREEN

Valitse Talokatsastus + Caire + SähköTTV, jos:

- ei olennaista toimija- tai talousriskiä
- referenssit/pätevyydet riittävät
- kolmen toimijan koordinointi on käytännössä hallittavissa
- matkakulujen jälkeen säästö Rakmentoriin on edelleen merkittävä suhteessa coverage-eroon

### AMBER

Tee yksi rajattu lisävahvistus ennen varausta, jos:

- tekijän nimi/pätevyys puuttuu
- modulaarisuus tai raporttien yhdistäminen on epäselvä
- matkakulut ovat avoimet mutta eivät todennäköisesti muuta päätöstä

### RED

Palaa Rakmentoriin tai vertaile Taykan valmistunut kokonaisuus, jos:

- joku kriittinen mittausosuus ei ole luotettavasti toimitettavissa
- yrityksen jatkuvuus/toimituskykyyn liittyy konkreettinen riski
- hajautettu malli ei tuota yhtenäistä käyttökelpoista evidenssiä
- todelliset matkakulut ja lisäkoordinointi syövät olennaisesti hintaedun

## Side quest completion

Side quest suljetaan vasta, kun nämä viisi vastausta voidaan tiivistää yhdelle päätösriville:

> `riskit | referenssit | talous | modulaarisuus | all-in-hinta → suositus`

Pääpolun toimittajalukitus on siihen asti **BLOCKED BY SIDE QUEST**, ei HITL-päätös.