# DT 170 Lab v2

Tyylitelty staattinen DT170-laskuri GitHub Pagesiin.

## Sisältää
- Live-sliderit sylinterin korotukselle ja kanavakorkeuksille
- Pako- ja huuhteluajoitukset
- Blowdown
- Kampikulmakaavio
- Sylinterin visuaalinen porttinäkymä
- Ennen/jälkeen vertailu
- Tulostettava 1:1 porting map
- 50 x 50 mm kalibrointiruutu
- PWA/offline-välimuisti

## Päivitys GitHub Pagesiin
Korvaa repositorion `index.html`, `manifest.json` ja `sw.js` näillä tiedostoilla.
GitHub Pages julkaisee uuden version automaattisesti.

## Tulostus
Avaa Porting Map ja valitse Tulosta 1:1.
Tulostusasetuksissa käytä 100 % / Actual size.
Mittaa 50 x 50 mm kalibrointiruutu ennen porting mapin käyttämistä sylinterissä.


## v2.1 korjaus
- Korjattu sylinterin korotuksen suunta: korotus aikaistaa porttien avautumista ja kasvattaa ajoitusta.
- Päivitetty service worker -välimuistin versio.

## v2.2
- Sylinterin korotuksen laskentasuunnan korjaus.
- Positiivinen korotus kasvattaa pako- ja huuhteluajoitusta.
- Service Worker poistettu käytöstä kehityksen ajaksi.
- Sivu poistaa vanhat Service Worker -rekisteröinnit ja välimuistit automaattisesti.
