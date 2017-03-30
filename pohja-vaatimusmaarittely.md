# Vaatimusmäärittely


## Sisällysluettelo

* [Asiakastarina]()
* [Sidosryhmät ja profiilikuvaukset]()
* [Sidosryhmäkuva]()
* [Asiakaspolku]()
* [Yleinen käyttötapaus]()
* [Yleiset toiminnalliset vaatimukset]()
* [Yleiset ei-toiminnalliset vaatimukset]()
* [Palvelu MockUp]()
* [Tärkeimmät ominaisuudet]()
* [Julkaisun suunnitelma]()
* [Palvelun/ohjelmiston arkkitehtuuri]()
* [Testaus ja laadunvarmistus]()
* [Lähteet]()

## Johdatus

Tehtävän aiheena on Jyväskylän ammattikorkeakoululle opinnäytetyön arvioimistyökalun nykyisen manuaalisen tavan tilalle. Vaatimusmäärittelyssä on tarkoituksena tuoda esiin eri sidosryhmät, käyttäjäprofiilit ja käyttötapaukset. Vaatimusmäärittelyssä tulee ilmi sovelluksen vaaditut ominaisuudet, jotka sovelluksen toimivuuden kannalta ovat välttämättömiä.


### Palvelukuvaus

Jamkista valmistuminen edellyttää opiskelijalta hyväksyttyä opinnäytetyötä. Nykyinen käytäntö opinnäytetyön hyväksymiselle on manuaalinen arviointiprosessi ja mitään valmista sovellusta tai ohjelmaa tähän työhön ei ole.

Tehtävän tavoitteena on luoda selkeä sovellus tai palvelu, jolla saataisiin tämä prosessi helpommaksi opettajille, opiskelijoille ja opinnäytetyön toimeksiantajille. Tarkoituksena olisi vähentää kirjoitustyötä ja manuaalista prosessia, jolloin saataisiin opinnäytetyön arviointi prosessia myöskin nopeutettua.

Sovelluksen tärkein ominaisuus olisi helppokäyttöisyys. Sovelluksen avulla pitäisi voida myös pitää kirjaa opinnäytetöistä, estää plaginointia, sekä auttaa opinnäytetyön tekijää seuraamaan tarkastusta ja arviointia. Sovelluksen käyttö edellyttää kirjautumista määrätyillä tunnuksilla ja eri käyttäjillä on eri oikeuksia nähdä sinne ladattuja opinnäytetöitä

### Vaatimusmäärittelytyön tilaaja

[Karo Saharinen](https://github.com/Jonssi/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/wiki/Sahka) 

### Vaatimusmäärittelyn toimittaja

Jon Sundberg, K2754

## Asiakastarina

Opiskelija on sopinut työnantajan kanssa opinnäytetyöstä. Opiskelijan ensimmäinen tehtävä on esittää opinnäytetyön aihe koulutusvastaavalle. Koulutusvastaavan hyväksyttyä aihe, hän määrää opiskelijalle kaksi ohjaajaa. Kun opiskelijan tekemä opinnäytetyö on valmis, hyväksyy toinen ohjaaja opinnäytetyön arvioitavaksi. 

Opinnäytetyö ladataa arviointisivustolle, jonka jälkeen kaikille opinnäytetyön arvioitsijoille lähetetään henkilökohtaiset tunnukset opinnäytetyön lukemista, kommentoimista ja arviointia varten. Kun kaikki sivusto on  rekisteröinyt kaikilta tunnuksilta arvioinnin, ohjelma laskee lopullisen keskiarvon ja odottaa koulutusvastaavan hyväksyntää arvioinnille. Kun arviointi on hyväksytty, opiskelija saa lopullisen arvosanan opinnäytetyötapaamisessa.
![](http://i.imgur.com/31P5lOZ.png)


## Sidosryhmät (Stakeholders) ja profiilikuvaukset (Profile descriptions)

### Arviointisovellusta käyttävät henkilöt:
* Opiskelija: [Jon Sundberg](https://github.com/Jonssi/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/wiki/Profiilikuvaus-Jon-Sundberg)
* Vertaisopiskelija: [Sbastian Laksonen](https://github.com/Jonssi/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/wiki/Profiilikuvaus-Sbastian-Laksonen)
* Ohjaava opettaja1: [Pavel Kolmimarkka](https://github.com/Jonssi/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/wiki/Profiilikuvaus-Pavel-Kolmimarkka)
* Ohjaava opettaja2: [Jarppi Viinakanjoki](https://github.com/Jonssi/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/wiki/Profiilikuvaus-Jarppi-Viinakanjoki)
* Toimeksiantaja: [Usko Suihkari](https://github.com/Jonssi/TTOS0100-Ohjelmistosuunnittelu-ja-testaus/wiki/Profiilikuvaus-Usko-Suihkari)


## Sidosryhmäkuva (Stakeholder map)

Sidosryhmäkuvan tehtävänä on graavisesti selkeyttää sidosryhmän toimivuutta ja sitä kenelle tämä annettu sovellus on suunnattu. 

![](https://i.imgur.com/J7PYw5K.png)

## Asiakaspolku (Customer Journey)



![](https://i.imgur.com/1l9s6d4.png)


## Tuotteen yleisiä vaatimuksia ja rajoituksia (General Requirements and restrictions)

Tuotteen toimivuuden kannalta on vaadittava turvallinen ja helppo käyttö. Tuotteen on oltava vakaasti toimiva ja selkeä, ettei turhaa aikaa kulu toimivuuden etsimiseen. Tuotteen ainoana mahdollisena rajoituksena on penkin ja näppäimistön välissä istuva käyttäjä.


| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| GENREQ001 | Sovellus on helppo käyttöinen | Kehitys | Koodari | 
| GENREQ002 | Kirjautuminen vaatii henkilökohtaiset tunnukset | Käyttöympäristö | Admin | 
| GENREQ003 | Arvioinnin täyttö selkeä ja helppo | Kehitys / Suunnittelu | Koodari | 
| GENREQ004 | Minimaalinen riski väärinkäytölle | Kehitys / Ylläpito | Koodari / Käyttäjä | 
| GENREQ005 | Sovelluksen oltava luotettava | Kehitys | Koodari | 



## Yleiset käyttötapaukset (General Use Cases)

# [Käyttötapaus1](https://github.com/Jonssi/TTOS0100/wiki/Usercase1)


![](http://i.imgur.com/xQjpEFp.png)


## Palveluun liittyvät toiminnalliset vaatimukset (Functional Requirements)



| Id | Vaatimuksen kuvaus |
|:-:|:-:|
| REQ001 | JAMK:n käyttäjätunnuksella haku |
| REQ002 | Kun tietoja lisätään lokiin kuittaus |
| REQ003 | Kuin tietoja muokataan lokiin kuittaus |
| REQ004 | Kirjautuminen JAMK:n tunnuksilla |
| REQ005 | Arvioinnista lähetetään kuittaus arvioijan sähköpostiin |
| REQ006 | Tietojen lisäämisen jälkeen arviointisivu luodaan |
| REQ007 | Jos väärää salasanaa syötetään useasti, lähtee ylläpidolle siitä viesti |
| REQ008 | Salasana 5 kertaa väärin, käyttäjältä vaaditaan salasanan vaihtoa |
| REQ009 | Vain annetuilla tunnuksilla kirjautuminen mahdollista |
| REQ010 | Kommenttien lisäämisestä lähetetään arvioijalle sekä opiskelijalle viesti | 


## Palveluun liittyvät ei-toiminnalliset vaatimukset (Non Functional Requirements)

| Id | Vaatimuksen kuvaus |
|:-:|:-:|
| NREQ001 | Toimii kaikilla selaimilla |
| NREQ002 | Kolme kielivaihtoehtoa: suomi, ruotsi ja englanti |
| NREQ003 | Ylläpitotyöt ei aiheuta käyttökatkoja |
| NREQ004 | Samaa työtä pystyy käsittelemään max 15henk. |
| NREQ005 | Toimivuus myös mobiililaitteilla |

### Suorituskykyvaatimukset (Performance Requirements)


| Id | Vaatimuksen kuvaus |
|:-:|:-:|
| PE001 | Haetut tiedot saatava 3sekunnin kuluessa | 
| PE002 | Sovelluksen lähettämät viestit lähtee 5min kuluessa |
| PE003 | Kirjautuminen työkaluun 5s kuluessa |
 


### Tietoturvavaatimukset (Data Security Requirements)


| Id | Vaatimuksen kuvaus |
|:-:|:-:|
| DS001 | Vain määritetyt käyttäjät pystyvät näkemään ja käsittelemään työtä |
| DS002 | Salattu yhteys |
| DS003 | Käyttäjän uloskirjaus, jos 15min ilman käyttöä |


## Palvelu MockUp-prototyyppi


MocuUP: https://ninjamock.com/s/MR89H 
[![](http://i.imgur.com/eQismdc.png)](https://ninjamock.com/s/MR89H)
[![](http://i.imgur.com/1GUHcom.png)](https://ninjamock.com/s/MR89H)

## Tärkeimmät tunnistetut ominaisuudet (Features)


| Ominaisuus | Prioriteetti |
| :-: | :-: |
| [Arviointisivusto](Ominaisuuskuvaus1) | Korkea |
| [Kielen valinta](Ominaisuuskuvaus2) | Matala |
| [Keskiarvon laskeminen](Ominaisuuskuvaus3) | Korkea |




# Palvelun/ohjelmiston arkkitehtuuri 

### Yleinen sijoittelunäkymä (Deployment diagram )

![](https://openclipart.org/image/800px/svg_to_png/17266/berteh-flow-diagram-symbols.png&disposition=attachment)


# Arkkitehtuuriin/teknologiaan liityvät vaatimukset

### Ylläpito (Maintenance)

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Vaatimus? | Yllläpito | Kuka vastaa | 
| REQ00x | Vaatimus? | Tekninen | Kuka vastaa | 
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa | 
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa | 
| REQ00x | Vaatimus? | Käytettävyys | Kuka vastaa | 

### Yleinen tietokantakuvaus (Database ER-diagram)

ER-kaavio

![](https://openclipart.org/image/800px/svg_to_png/17266/berteh-flow-diagram-symbols.png&disposition=attachment)


# Testauksen vaatimukset (Testing requirements)

### Testattavuus

| Id | Vaatimuksen kuvaus | kategoria | Vastuullinen |
|:-:|:-:|:-:|:-:|
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa | 
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa | 
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa | 
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa | 
| REQ00x | Vaatimus? | Testattavuus | Kuka vastaa | 



# Tunnistetut riskit ja testikohteet

  * Riski -> Testaustarve
  * Vaatimus -> Testaustarve



### Dokumentit, standardit ja lähteet

TÄHÄN JOTAIN SCHAIBAA!!!!

*Lähteet*

| ID | Lähde | Kuvaus | Linkki | 
|:-:|:-:|:-:|:-:| 
| Id0 | Wikipedia | Vaatimusmäärittely |   https://fi.wikipedia.org/wiki/Ohjelmiston_vaatimusm%C3%A4%C3%A4rittely
- | 
| - | -  | - | 
| - | -  | - | 
| - | -  | - | 


