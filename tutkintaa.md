# yleistä selvittelytyötä
Ongelma: voiko MSForms lomakkeita generoida listasta-?
Ei voi: https://techcommunity.microsoft.com/t5/microsoft-forms/can-i-pre-populate-a-microsoft-form-choice-area-with-sharepoint/m-p/2076531

Ilmeisesti on pakko tehdä microsoft apps aplikaatio. 

Microsoft Listaan automaattisesti kasvava ID-kenttä
https://techcommunity.microsoft.com/t5/sharepoint/auto-increment-number-field-in-a-sharepoint-list/m-p/1141477


# Toimintaohjeita ratkaisun kehitykseen
Kun käytetään MS power - perhettä low code kehityksessä kannttaa lähteä liikkeelle Siitä mitä tietoa tarvitaan.

* Katsokaa käyttötapauskaaviotanne ja listatkaa tiedot joita tarvitsette. Ja vain tiedot joita tarvitaan.
* Miettikää käyttötapauskaavioon liittyvät käsitteet, Tehkää niistä listaa. 
* Käyttäkää käsitteitä otsikointa ja listatkaa tiedot/tietoalkiot noiden otsikoiden alle. 
* Jos tieto/tietoalkio liittyy useampaan useampaan käsitteeseen, listatkaa se kaikkien käsitteiden alle
* Tehkää jokaisesta käsitteestä microsoft list -lista, listan nimeksi käsite, sarakkeiksi tiedot/tietoalkiot.

# Esimerkki: 
tiimin tehtävälista- käyttötapauskaavio
![](./UCKaaviot/groupFeedback.png)
Ryhmien muodostus on monimutkainen operaatio joka jakautuu mahdollisesti useampiin mahdollisiin skenaarioihin, joissa on vaihtelevia tietotarpeita, joten liian haastava tähän. 

## **Kysy vertaispalaute**
Opettajan laittaa vertaispalaute-kyselyn auki. Kaikilta ryhmäläisiltä kysytään. Lopuksi tehdään raportti ryhmästä. 
Alla Aktiviteettikaavio käyttötapauksesta "kysy vertaispalaute" (nimen pitäisi ehkä olla "anna vertaispalaute"). 

**Yleistä:** Käyttötapauksen, ja siten tämän aktiviteettikaavionkin käynnistää jokin tapahtuma, "triggeri". "triggeri" tässä on: 'ryhmän jäsen antaa vertaispalautteen'. Vertaa edellämainittua käyttötapauksen "triggeri" käsitettä power automateen, mikä se voisi olla siellä??? Mikä se voisi olla tässä use-casessa käytännössä?

![](./ucActivityVertais.png)

## **Kysy vertaispalaute** käyttötapauksen tietovarastot
Opettajan antaa opiskelijoille ryhmätyön vertaispalautelomakkeen kurssin päätteeksi. 
Ryhmän jäsenelle näytetään lomake jossa kysytään aktiivisuus/kontribuutio-arvio kaikista ryhmän jäsenistä asteikolla 1-5, 5 hyvin aktiivinen 1 ei ollenkaan aktiivinen. Myös itsestä pitää antaa "oma-arvio". 
Lisäksi vapaamuotoinen arvio-teksti toiminnasta

* Käsitteet alustavasti: (suluissa perässä oikea nimi personal lists-osiossa)
* Opiskelijoiden ryhmät: nämä ovat lähtötietona (VAGroupMembers)
    * opiskelija (otsikko/Title)
    * ryhmä
* VertaisArviot: Ryhmäläisten antamat (VAPeerReviews)
    * Opiskelija (otsikko/Title)
    * Arvioitava opiskelija
    * Ryhmä
    * Arvio
    * Arvioteksti
* ArvioRaportti: vertaisarvioista jalostettu kun kaikki on annettu (VAReviewReport)
    * Opiskelija (otsikko/Title)
    * Ryhmä
    * laskettu arvio-koonti
    * yhdistetty arvioteksti




