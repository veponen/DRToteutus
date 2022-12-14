# Persoonallisuuden käsittelyn käyttötapaus
1. Käyttäjä antaa testitulokset, neljä merkkiä
2. lue 1. ja 2. merkki MBTI merkkijonon keskeltä
3. Lue tallennetulta MBTI-listalta toisen vuorossa oleva MBTI tulos
4. Vertaile annetun ja listalta luetun BMTI tulosta
5. Tallenna henkilöiden yhteensopivuus-tulos yhteensopivuus-listalle.
6. jos annetutMBTIt listalla on vielä rivejä, siirrytään askeleeseen 3.





# vaihtoehto-skenaariot
1. askeleessa havaitaan että vanhat tulokset on olemassa TÄMÄ SKENAARIO PITÄÄ POISTAA. 
1. a tarkastetaan onko annettu MBTI sama kuin aemmin
1. a.a jos on, lopetetaan ohjelmia
1. a.b. Poistetaan vanhat yhteensopivuustiedot
1. a.c. lähetetään viesti muutoksesta ylläpitäjälle ongelmanselvittelyä varten.
Palataan pääskenaarion askeleeseen 2 ja jatketaan suoritusta.

1. askeleessa havaitaan että annettu tyhjä MBTU
1b. palataan pääskenaarion loppuun suorittamatta lauseita

# Tarvittavat tietolistat
Yhteen listaan lisätään lomakkeelta tulevat tiedot. Muutoksia voi tulla.     
Yhteen listaan lisätään henkilön yhteensopivuustiedot.    ( ota selvää voiko listojen välille tehdä relaation)

# Mahdolliset taulut
* Personallisuustesti : Otsikko, email, MBTI, MBTI_middle, GPAHighSchool, GPAVocational, GPAVocInstName, 
* MBTIList: GivenName, SurName, eMail, MBTI, GPA, GPA2
* SuggestedPairs: Compatibility, studentEmail, PAirEmail, StudentMBTI
* MBTItesti: Otsikko, mbti, 
* TE_lista: pelkkä testi. 
* Pairs: Otsikko, Compatibility, studsEmail2, studEmail
