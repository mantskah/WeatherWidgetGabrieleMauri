# WeatherWidgetGabrieleMauri
### Non avendo implementato lo swipe come da telefono, per scorrere le pagine del widget è necessario clickare con il mouse a destra o a sinistra sul widget stesso.

## Introduzione:
Per svolgere l’esercitazione fornita ho utilizzato un file HTML e uno CSS.
Per l’API ho utilizzato la versione gratuita di OpenWeather.
A causa della versione gratuita di open weather non mi è stato possible reperire i dati ora per ora e giorno per giorno.
Per ovviare a tale problema ho agito così:

**Prima pagina:** Meteo corrente.

**Seconda Pagina:** Meteo ogni 3 ore a partire dal momento attuale.

**Terza Pagina:** Meteo alle ore 12 per i 5 giorni successivi.

## Struttura:
Basandomi sulle immagini fornite, ho fatto una draft su codeframe, di come le 3 “pagine” mostrate dal widget sarebbero state rappresentate.

La prima pagina ha 2 colonne, quella di sinistra mostra temperatura attuale e nome della città, in questo caso Fabbriche di Vergemoli, Lucca. A destra, un icona mostra la condizione meterologica. Il gradiente cambia colore in Giallo, se soleggiato, Grigio se coperto e blu se piove.

La seconda pagina, ho usato una griglia e diviso in piccoli “div” ognuno con temperatura, icona e ora. L’icona si aggiorna in base al Meteo.

La terza pagina, simile alla seconda, usa una griglia dove vengono mostrati i dati recuperati per i giorni a vernire.


