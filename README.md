# SY Tiimi tekemisen laadun mittaristo – itsearviointilomake

Tämä on kevyt verkkopohjainen itsearviointilomake myyjille.

## Käyttö

- Myyjä täyttää nimen, päivämäärän ja pisteyttää 5 mittaria.
- Lomake muodostaa valmiin sähköpostipohjan.
- "Avaa sähköpostiluonnos" avaa käyttäjän oman sähköpostiohjelman.
- Lähetys tapahtuu vasta, kun myyjä itse painaa sähköpostiohjelmassa Lähetä.

## Vastaanottajan sähköpostin vaihtaminen

Avaa `index.html` ja muuta rivi:

```js
const MANAGER_EMAIL = "davis.lipskis@yrittajat.fi";
```

## Deploy Verceliin

Vie tämän kansion sisältö GitHub-repoon ja importtaa repo Verceliin.

Koska tämä on staattinen HTML-sivu, erillistä build-komentoa ei tarvita.
