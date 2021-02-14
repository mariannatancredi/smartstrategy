L'applicativo è sviluppato in un unico file index.html, principakmente in html e javascript. 

I token per le API di accesso al servizio OpenWeather e Spotify sono indicate in variabili globali. Al primo lancio dell'applicativo, viene verificato il token per l'accesso ai servizi Spotify, se esso non è valorizzato, viene mostrata la pagina di autenticazione a Spotify. Una volta ottenuto il token, l'applicazione può essere utilizzata.

E' necessario insrire il CAP della località desiderata. La richiesta ad OpenWeather indicherà la situazione metereologica e suggerendo 10 canzoni da ascoltare. Le canzoni vengono selezionate da una playlist specifica, sceltra tra quelle disponibili su Spotify. 
