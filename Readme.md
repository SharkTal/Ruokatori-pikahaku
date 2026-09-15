# Tuotekoodien pikahaku (Kassan ja keittiön apuri)

> **⚠️ Tärkeä huomautus (Vastuuvapauslauseke):** 
> Tämä on epävirallinen työkalu. Se ei ole sidoksissa Prisman virallisiin järjestelmiin. 
> (Tämä työkalu on tehty oma-aloitteisesti työnteon helpottamiseksi, ei osana yrityksen virallisia järjestelmiä.)

🔗 **Live-demo:** <https://sharktal.github.io/Ruokatori-pikahaku/>  
📂 **Lähdekoodi:** <https://github.com/SharkTal/Ruokatori-pikahaku>

---

## 📌 Miksi tämä työkalu tehtiin? (Ongelma, johon törmäämme päivittäin)

Kuvittele tilanne: On kiireinen lounasaika. Asiakas ostaa lämpimän aterian. Työntekijän täytyy löytää kyseisen tuotteen **5-numeroinen tuotekoodi**, syöttää se vaakaan, tulostaa hintalappu ja liimata se pakkaukseen.

**Mitä ongelmia tässä oli aiemmin?**
*   Hyllyjen reunoilla on paljon vanhoja, epäselviä paperilappuja, joista oikean koodin löytäminen on hidasta ja virhealtista.
*   Uusien työntekijöiden on vaikea muistaa ulkoa kymmeniä eri koodeja.
*   Koodin etsiminen aiheuttaa asiakkaille turhaa jonottamista.

## 💡 Ratkaisu: Tuotekoodien pikahaku

Tämä on kevyt verkkosivu, joka toimii suoraan puhelimen selaimessa. **Sitä ei tarvitse asentaa erikseen, eikä se vaadi salasanoja tai liittymistä yrityksen verkkoon.**

Työntekijä avaa vain linkin puhelimellaan:
1. Kirjoittaa tuotteen nimen (esim. "Kana" tai "Lohi").
2. Näkee heti oikean tuotekoodin isolla fontilla.
3. Syöttää koodin manuaalisesti vaa'alle.

**Näin säästämme aikaa ja vähennämme virheitä.**

## 🛠️ Miten työntekijät käyttävät sitä?

**Peruskäyttö (Kaikille työntekijöille):**
1. Avaa linkki puhelimellasi.
2. Kirjoita hakukenttään tuotteen nimi tai koodi.
3. Näet heti oikean tuotekoodin isolla fontilla.
4. Napauta korttia → koodi näytetään suurella kokona vaa'alle syöttämistä varten.

**Vinkki:** Lisää sivu puhelimesi aloitusnäytölle (Lisää kotinäytölle), niin se toimii kuin mikä tahansa sovellus!

## ⚙️ Miten tuotteita päivitetään? (Esimiehille ja vastuuhenkilöille)

Tuotevalikoima muuttuu neljännesvuosittain. Tätä varten työkaluun on sisäänrakennettu helppo **Hallintatila (Admin)**.

**Näin päivität tuotteet (esim. kerran kvartaalissa):**
1. Avaa sivu ja paina oikean yläkulman nappia **"🔧 Hallintaan (Admin)"**. (Salasana: `admin`).
2. **Lisää uusi tuote:** Kirjoita nimi ja koodi, paina "Lisää tuote".
3. **Poista vanha tuote:** Etsi listalta ja paina "Poista".
4. **Tallenna ja poistu:** Kun olet valmis, paina vihreää **"✅ Tallenna ja sulje"** -nappia.

**❗ Tärkein vaihe: Tietojen jakaminen muille!**
Koska tämä työkalu toimii itsenäisesti puhelimissa (ilman yrityksen palvelinta), sinun täytyy jakaa päivitetyt tiedot muille työntekijöille.
*   Hallintatilassa paina **"📥 Lataa varmuuskopio (JSON)"**. Laite tallentaa tiedoston puhelimeesi.
*   Lähetä tämä tiedosto esimerkiksi työporukan WhatsApp-ryhmään tai sähköpostilla.
*   Muut työntekijät avaavat oman sivunsa, menevät Hallintatilaan ja painavat **"📤 Palauta varmuuskopiosta"** ja valitsevat lähettämäsi tiedoston. Kaikki tiedot päivittyvät heti!

## 🔧 Teknologia

*   **Etupää:** HTML, CSS, JavaScript (ei riippuvuuksia, ei frameworkkeja)
*   **Tietojen tallennus:** LocalStorage (toimii offline-tilassa)
*   **Tietojen jakaminen:** JSON-vienti ja -tuonti
*   **Isäntä:** GitHub Pages
*   **Yhteensopivuus:** Toimii kaikissa moderneissa älypuhelimissa

## 🔮 Tulevaisuuden visio (Kehitysehdotus)

Tämä työkalu on tällä hetkellä **prototyyppi (kokeiluversio)**. Se on tehty osoittamaan, että pienellä vaivalla voidaan ratkaista arjen ongelmia.

Jos tämä osoittautuu hyödylliseksi, tätä ideaa voidaan kehittää eteenpäin yrityksen virallisilla resursseilla:
*   **Automaattinen synkronointi:** Tiedot päivittyisivät kaikille työntekijöille reaaliajassa ilman manuaalista tiedostojen lähettämistä. Tämä vaatisi pienen tietokantataustan, jolloin kaikki muutokset näkyisivät automaattisesti kaikilla laitteilla.

---
*Kehitetty oma-aloitteisesti työnteon sujuvoittamiseksi. (因工作流程优化需求而自主开发。)*
