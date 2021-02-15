L'applicativo consiglia all'utente un elenco di canzoni da ascoltare in base alla situazione metereologica della città indicata.

Per accedere al servizio è necessario essere autenticati su Spotify, dunque il primo controllo viene effettuato proprio sull'accesso eseguito.

Per ottenere l'elenco di canzoni suggerite, è necessario insrire il CAP della località desiderata. La richiesta ad OpenWeather indicherà la situazione metereologica e suggerirà 10 canzoni da ascoltare. Le canzoni vengono selezionate da una playlist specifica, sceltra tra quelle disponibili su Spotify. E' possibile cliccare su ciasun titolo per avere il link alla riproduzione.

---

L'applicativo è sviluppato in un unico file index.html, principalmente in html e javascript. La scelta di queste tecnologie è stata dettata dal ritardo della mia consegna e, dunque, dal poco tempo rimastomi disponibile allo sviluppo.
L'ideale sarebbe stato lo sviluppo della parte autenticativa in PHP con l'apertura di una sessione e la creazione di un database di città. La scelta dell'utilizzo delle API di OpenWeather con il CAP è stato dettato dall'univocità che esso offre. La soluzione più efficiente e user-friendly sarebbe stato creare una select con campo di autocompletamento, oppure, se la mole dati fosse stata troppo elevata, lavorare con più select su Nazione, Provincia e Città da popolare in maniera dinamica. Nel documento, c'è anche una sezione totalmente commentata in cui avevo ipotizzato il campo select con autocompletamento accennato in precedenza da popolare con il json delle città offerto da OpenWeather: la soluzione è stata comunque fallimentare perchè si tratta di un json troppo grande da trattare in quel modo e l'applicativo sarebbe risultato troppo lento e pesante. 
Ho cercato in ogni caso di inserire tutti i controlli del caso, sul CAP immesso e sulla gestione di errori derivanti dalle chiamate API. Nel dettaglio, ho anche lasciato in console.log() alcuni responsi.
