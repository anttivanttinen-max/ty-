VÄNÄ MotoLab – Solo RPM & Knock Tester v1

Tarkoitus
---------
Yksin käytettävä ohjattu testiohjelma AirPod/BT-mikrofonin RPM- ja
korkeataajuisen värähtelysignaalin vertailuun.

Testin logiikka
---------------
Jokainen kierrosalue tehdään näin:

1. Kalibrointi pakoputken loppupäässä / stingerin alussa.
2. Samalla RPM-alueella käydään kaikki muut mittauspaikat läpi.
3. Seuraava RPM-alue alkaa uudella kalibroinnilla pakoputkessa.
4. Paikkoja voi ohittaa.
5. Jokainen mittaus tallentuu erikseen.
6. Tuloksia voidaan tarkastella myöhemmin sekä RPM-alueittain että paikoittain.

Oletuspisteet:
- tyhjäkäynti
- 3000 rpm
- 5000 rpm
- 7000 rpm
- 9000 rpm

Oletuspaikat:
- vapaa mikrofoni 0,5 m pakoputkesta
- vapaa mikrofoni 0,5 m moottorista
- mikrofoni suoraan pinnapulttiin
- pinnapultti + lyhyt jäykkä letku
- tulpan metalliosa
- oma paikka

Solo-käyttö
-----------
- isot painikkeet
- siirtymäajan laskuri
- ääniohjaus selaimen speech synthesis -toiminnolla
- värinäpalautetta tuetuilla puhelimilla
- automaattinen eteneminen
- testin voi keskeyttää ja jatkaa selaimen localStoragesta
- puuttuvan adapterin testi voidaan ohittaa

Data
----
JSON sisältää myös mittausten yksittäiset näytteet:
- aikaleima
- arvioitu RPM
- RPM confidence
- mic dB
- HF / knock score
- havaittu fundamental
- H1–H6 spektritieto

CSV sisältää testien yhteenvetorivit.

HUOM
----
HF / Knock -arvo on tässä kokeellinen korkeataajuisen värähtelyn mittari.
Sitä ei pidä käyttää yksin moottorin suojaukseen tai varmana nakutustunnistuksena.

iPhone/Safari
-------------
Avaa sivu HTTPS-osoitteesta, jos mikrofonilupa ei toimi paikallisesta tiedostosta.
Safari/BT voi myös päättää itse käytettävän Bluetooth-mikrofonin reitityksestä.
