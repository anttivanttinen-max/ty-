VÄNÄ MotoLab Contact RPM + Knock Sweep v6

V6 KAMERA:
- automaattinen LCD-näytön haku koko kamerakuvasta
- lukitus ja näytön seuranta puhelimen liikkuessa
- automaattinen uudelleenhaku, jos seuranta katoaa
- varamenetelmä: napauta LCD:tä kerran tai rajaa vasen ylä + oikea ala
- segmentit tunnistetaan pinta-alasta, ei yksittäisistä pikseleistä
- adaptiivinen Otsu-kynnys LCD:n valaistuksen mukaan
- temporalinen virhesuodatus: yksittäiset väärät numerot hylätään
- SEARCHING / LOCKED / CAM RPM / confidence näkyvät reaaliajassa
- sweep vapautuu vasta kun kamera on lukossa ja mikrofoni toimii
- JSONiin tallentuu hyväksytty RPM, raaka RPM, numerot, confidence, lock-tila ja seurattu LCD-laatikko

AUDIO:
- RPM-spektri 20–1000 Hz / 5 Hz
- knock 1–15 kHz
- WAV-raakaääni
- kameramittarin viivearvio audion suhteen

TESTI:
1. Kiinnitä kuuloke pinnapultin jatkomutteriin alumiinishimmillä.
2. Käynnistä mikrofoni.
3. Käynnistä kamera ja näytä digitaalinen RPM-mittari kameralle.
4. Odota LOCKED. CAM RPM:n pitää vastata mittarin näyttöä.
5. Jos SEARCHING jatkuu, paina HAE NÄYTTÖ tai NAPAUTA NÄYTTÖÄ ja napauta LCD:tä kerran.
6. Aloita sweep ja kaasuttele rauhallisesti ylös/alas.
7. Lopeta ja vie JSON + WAV.
