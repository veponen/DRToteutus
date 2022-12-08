# Työn jakaminen 
Työn voi jakaa erillisiin osiin manuaali-triggerin avulla tai microsoft list kohdalta. 
Testataan käytännössä. Jaetaan vertaisarviointi Use Case pienempiin palasiin. Suunnitellaan paloissa testattava toteutus. 
**Rajapinnat:** jos käytetään manuaali-triggerillä eroteltuja paloja, rajapintamuuttujat pitää nimetä sovitusti selkeästi:RAJ_<muuttuja>. Ja niiden arvot pitää heti sijoittaa oikeassa tilanteessa käytettäviin muuttujiin. Ensimmäinen kokeilu: vertaispalautelomakkeen korvaaminen? 
VAKysyVertaisarviointi

## yleinen flown rakenne
Meidän UC:n yleisestä rakenteesta: 
yleensä useita ihmisiä jotka antavat jonkinlaisia vastauksia ja niitä sitten käsitellään jotenkin, joten voidaan hahmottaa eräänlainen "malliratkaisu" jota voi sovittaa tilanteen mukaan. 
Vaihe 1: käyttäjiltä kerätään tietoja listaan
Vaihe 2: kun tietoja on kerätty tarpeeksi tai jonkinlainen aikaraja tulee vastaan tietoja käsitellään jotenkin. 
Vaihe 3a: käyttäjiltä kerätään lisää tietoja aiemmin annettuihin tietoihin perustuen 
    * Tämä vaihe ei onnistu jos ei käytetä jaettua exeliä johon listan tiedot jalostetaan tai powerAppsia
Vaihe 3b: Tiedot jalostetaan jotenkin raportiksi ja sitä hyödynnetään toiminnassa, ryhmiin jaossa tai tehtävien jaossa tai roolien jaossa tms. 

Suunnitellaan tomintamalli ja ohjevideot aiheeseen. 

### Demotapaus
Yksinkertainen testitapaus? tulevissa jaksoissa 1. tehtävä.
kysytään/tallennetaan ryhmä, nimi, numero1, numero2
Kolmen tallennuksen jälkeen kirjoitetaan raporttirivi raporttikantaan


### Flown mallipalaset joita voi hyödyntää
Triggerinä form
Triggerinä listamuutos
Silvastin löytämä ohje listan sisällön syöttämisestä flowhun. 

## 1. palanen
Talleta vertais-arvio-laatikkoon saakkaa. 



# Havaittuja lisätarpeita
TODO: Kaikkeen "speksaustyöhön" pitäisi saada palautekanava. Jos tulee jotain mieleen jälkikäteen: lisäyksiä tai muutoksia, pitäisi olla helppo nopea tapa kirjata sellainen ylös käsiteltäväksi myöhemmin. Pitäisi pystyä helposti liittämään muutos aiheeseen. Esim. katselmointikommentti suoraan vaikkapa aktiviteettikaavion johonkin elementtiin tai useampaan elemenettiin. 
