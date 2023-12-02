# Node-red sovellus

Sovellus mittaa melu- ja äänitasoja ja tallentaa ne tietokantaan. Mittaukset ovat nähtävissä dashboardissa. 

Tarkempi kuvaus sovelluksesta löytyy [Youtube videolta](https://youtu.be/VSl5tDobns8)

## Yleiskuva

Sovellus toimii Raspeberry Pi 4:llä, jossa asennettu Dockeriin MySQL-tietokanta.

![Yleiskuva](yleiskuva.png)

## Dashboard 

Tietokantaan tallenetut tiedot sekä ajantasaiset tiedot näkyvät dashboardissa

![Dashboard](node-red dashboard.JPG)

## Node-red flow

![Node-red flow](flowimage.png)

[Node-red flow](flow.json)

### Mittaaminen

![Mittaaminen](mittaus.png)

### Raja-arvon asettaminen, taulukointi ja pylväsdiagrammi

![Raja-arvon asettaminen](rajaarvo.png)

### Viimeisten 30 päivän arvojen taulukointi

![30 viimeistä päivää](tietokanta30pv.png)

### Sähköpostin lähetys

![Sähköpostin lähetys](email.png)

### Tietokannasta poistaminen

![Tietonnasta poistaminen](tietokantapoisto.png)