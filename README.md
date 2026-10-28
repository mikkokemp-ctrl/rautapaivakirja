# Rautapäiväkirja

Staattinen painonnoston treenilaskuri, päiväkirja ja ennätyslista. Käyttää vain selaimen paikallista `localStorage`-tallennusta.

## Julkaisu GitHub Pagesissa

1. Luo GitHubiin uusi repository, esimerkiksi `rautapaivakirja`.
2. Lataa tämän kansion tiedostot repositoryn juureen: `index.html`, `manifest.webmanifest`, `sw.js` ja `icon.svg`.
3. Avaa repositoryn **Settings → Pages**.
4. Valitse **Deploy from a branch**, branch `main` ja folder `/(root)`, ja tallenna.
5. Kun julkaisu on valmis, avaa GitHub Pagesin antama HTTPS-osoite puhelimella tai tietokoneella.
6. Lisää aloitusnäyttöön selaimen valikosta. iPhonessa Safari → Jaa → Lisää Koti-valikkoon. Androidissa Chrome → valikko → Lisää aloitusnäyttöön / Asenna sovellus.

## Tärkeää

- Tiedot tallentuvat kyseisen selaimen paikalliseen muistiin. Ne eivät synkronoidu laitteiden välillä.
- Vie varmuuskopio säännöllisesti **Varmuuskopio**-välilehdeltä.
- Treenin laskennan jälkeen tarkista kaikki painot ennen päiväkirjaan tallentamista.
- Nykyinen parseri tunnistaa tavallisia prosenttimerkintöjä kuten `75%x4`, `75% x 4` ja `80%×3`; poikkeavat muodot tai epäselvät liikkeet voivat vaatia tarkistusta.
- Maksimipohjat ovat muokattavissa **Ennätykset**-välilehdellä. Alustavat pohjat ovat käyttäjän vahvistamat: tempaus 90 kg, työntö 123 kg, pukkitempaus 83 kg, raakarive 115 kg, takakyykky 165 kg, maastaveto 190 kg, penkkipunnerrus 107,5 kg ja pystypunnerrus 70 kg.
- Työntö veto ja työntö irrotus käyttävät alustavasti työntö-pohjaa 123 kg.
