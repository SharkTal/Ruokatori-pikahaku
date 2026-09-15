# Huomasin työpaikalla toistuvan ongelman — ja ratkaisin sen koodilla

---

Työskentelen Prisman ruokatorilla. Jokainen kiireinen lounasaika paljastaa saman asian: tuotekoodien etsiminen hidastaa kaikkea.

Asiakas ostaa lämpimän aterian. Työntekijän täytyy löytää 5-numeroinen tuotekoodi, syöttää se vaakaan ja tulostaa hintalappu. Koodi pitäisi etsiä hyllyjen reunoilla olevista vanhoista, epäselvistä paperilapuista. Uudet työntekijät eivät muista koodeja ulkoa. Jonot kasvavat.

Tämä toistuu joka päivä. Se ei ole ihmisen ongelma — se on järjestelmäongelma.

---

## Mitä tein?

Rakensin kevyen verkkosovelluksen, joka toimii suoraan puhelimen selaimessa. Ei asennusta, ei salasanoja, ei yrityksen verkkoon liittymistä.

1. Avaa linkun puhelimella
2. Kirjoita tuotteen nimi
3. Näe tuotekoodi heti
4. Syötä vaa'alle

**Koko toimitus vie 3 sekuntia. Aiemmin se vei 30–60 sekuntia.**

Hallintatilalla esihenkilöt voivat päivittää tuotteet, kun valikoima muuttuu. Tiedot voi viedä JSON-tiedostona ja jakaa tiimille — kaikki päivittää omat puhelimensa yhdellä klikkauksella.

---

## Mitä opin?

**Yksinkertaisuus on ominaisuus.** Yksi HTML-tiedosto, joka toimii kaikissa puhelimissa, riittää. Ei frameworkkeja, ei riippuvuuksia.

**Paras koodi ratkaisee todellisen ongelman.** Ei tarvitse olla monimutkainen — sen pitää toimia.

**Aloite ratkaisee.** Kukaan ei pyytänyt minua rakentamaan tätä. Huomasin ongelman ja tein jotain.

---

## Seuraava askel

Tämä on prototyyppi. Se todistaa konseptin. Seuraava luonnollinen kehitysaskel on lisätä pieni tietokantataustakehityksen, jotta synkronointi tapahtuisi automaattisesti ilman manuaalista tiedostojen jakamista.

---

🔧 **Teknologia:** HTML, CSS, JavaScript, LocalStorage  
📂 **Avoin lähdekoodi:** https://github.com/SharkTal/Ruokatori-pikahaku  
🌐 **Live-demo:** https://sharktal.github.io/Ruokatori-pikahaku/

---

*Jos sinulla on työpaikalla samanlainen toistuva ongelma, joka vaatii ratkaisun — otan mielelläni yhteyttä.*

#OmaAloite #RatkaisuKeskeinen #Ohjelmistokehitys #Tuottavuus #JavaScript #WebSovellus #Innovaatio
