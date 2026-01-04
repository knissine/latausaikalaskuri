# Latausaikalaskuri
PWA (Progressive Web Application) muotoon tehty HTML/JavaScript-sivu sähköauton latausajan ja latausajankohdan määrittämiseksi.
Käyttäjä voi siis selaimella muodostaa pikakuvakkeen puhelimen näytölle ja saada puhelinsovellusmaisen käyttökokemuksen.

Sovelluksessa voi pitää yllä pörssisähkön marginaalia, siirtohintaa yö- ja päiväsähkölle (hammasratas näytön oikeassa yläkulmassa) ja listaa autoista (päänäytöllä).
Tiedot tallennetaan selaimen localStorage:en.

Sähkön hinta haetaan osoitteesta: https://api.spot-hinta.fi/TodayAndDayForward

Tällä hetkellä valitaan yksi yhtenäinen latausjakso.
"Latausikkuna":n avulla voidaan rajata minä aikana latauksen tulisi tapahtua.

Ei huomioida ulkoilman lämpötilan vaikutusta latausnopeuteen eikä muitakaan "latauskäyriä".

Huomautus: Projektin historia on kirjoitettu uudelleen 4.1.2026 kehittäjätietojen päivittämiseksi. Jos olet kloonannut projektin ennen tätä ajankohtaa, tee uusi kloonaus: git clone [url].
