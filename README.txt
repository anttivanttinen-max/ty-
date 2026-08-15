VÄNÄ MotoLab – Wide Spectrum RPM & Knock Tester v2

MUUTOKSET v2
- Ohjattu RPM- ja mittauspaikan valinta isoilla painikkeilla.
- Mittauspaikan voi valita vapaasti; valmis paikka merkitään ✓.
- Jokainen mittaus tallentaa step_id:n, tavoite-RPM:n ja mittauspaikan.
- Laaja spektri 20–1000 Hz, 5 Hz välein.
- Spektrin aikakuva tallennetaan noin 200 ms välein mittauksen ajan.
- JSON sisältää jokaisesta mittauksesta bins_hz, avg_db, peak_db ja snapshots.
- Live-spektrinäyttö zoomattu 20–1000 Hz alueelle.
- FFT size 32768 paremman taajuuserottelun vuoksi.
- Oletus-RPM pisteet: idle, 2000, 3000, 4000, 5000.

KÄYTTÖ
1. Avaa index.html selaimessa.
2. Käynnistä BT/AirPod-mikrofoni.
3. Paina ALOITA TESTISARJA.
4. Valitse RPM.
5. Paina mittauspaikkaa, esim. Paisari / Pinnapultti / Tulppa / 50 cm.
6. Tarkista että ruudulla lukee oikea paikka ja RPM.
7. Paina MITTAA.
8. Tee kaikki paikat samalla RPM:llä ja siirry seuraavaan RPM-pisteeseen.
9. Lataa JSON analyysiä varten.
