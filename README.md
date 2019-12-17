# Checkpoint Viikko 1, JavaScript

Kloonaa tämä repositorio omalle koneellesi ja toimi alla olevien ohjeiden mukaisesti.

## Taso 1
Toteuta tämän projektin HTML sivu siten, että se tulostaa tähdillä toteutettuja kolmioita. Kolmioiden määrä ja koko tulee käyttäjältä. Käyttäjä antaa sivulla olevaan input-kenttään merkkijonon, jossa on numeroita väliviivalla erotettuina. Tulosta sitten niin monta kolmiota kuin numeroita on, ja kunkin kolmion koko määräytyy numeron perusteella. 

Esimerkiksi syötteestä `3-2-6` tulisi seuraava tulostus:

```
*
**
***
*
**
*
**
***
****
*****
******
```

Vaatimuksia:
* Koodin tulee toimia riippumatta syötteen lukujen suuruudesta.
* Jos käyttäjä antaa uudet luvut, niin aiempi tulostus poistuu
* Käyttäjä voi antaa 1-<em>N</em> kolmiota piirrettäväksi, eli koodin on toimittava myös silloin kun halutaan tulostaa enemmän tai vähemmän kuin kolme kolmiota
* Tulostuksessa jokainen tähtirivi on oman &lt;p&gt;-elementin sisällä

Palautus: paketoi HTML-tiedosto zipiksi, ja palauta se Canvaksessa

## Taso 2
Tee tämä vain jos  taso 1 tuntuu helpolta, tai olet jo tehnyt sen onnistuneesti.

Tässä tehtävässä tulostetaan myös kolmioita käyttäjän syötteen perusteella, mutta kolmiot voivat olla ylös tai alas osoittavia. Tämä kerrotaan antamalla A- tai V-kirjain ennen lukua. Kirjain+luku -yhdistelmät erotetaan tässäkin väliviivalla, esimerkiksi A2-A5-V3-A2

* A: kolmion kärki osoittaa ylös, eli muistuttaa hieman A-kirjainta
* V: kolmion kärki osoittaa alas, eli muistuttaa hieman V-kirjainta

Esimerkki tulostuksesta syötteellä `A3-A2-V4`:
```
*
**
***
*
**
****
***
**
*
```

Palautus: Pull request omasta repositoriosta, Canvaksessa tekstinä: <b>Oma Nimi: github-tunnus</b>
