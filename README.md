# Recupero dati da API – JavaScript + Bootstrap

[![GitHub repo](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/tuo-username/tuo-repo)

Questo progetto dimostra come recuperare dati da un’API esterna utilizzando `fetch()` in JavaScript e visualizzarli dinamicamente in pagina con l’aiuto di Bootstrap.

L’interfaccia presenta un pulsante che, una volta cliccato, attiva uno spinner di caricamento e svuota il contenitore dei dati per evitare sovrapposizioni. Il programma effettua una richiesta HTTP verso l’endpoint `https://jsonplaceholder.typicode.com/posts`, che restituisce una lista di post in formato JSON.

Una volta ricevuti i dati, lo spinner viene nascosto e vengono selezionati i primi dieci post. Per ciascun post, il programma crea una card Bootstrap contenente il titolo e il corpo del messaggio. Le card vengono distribuite in una griglia responsive grazie alle classi di layout di Bootstrap.

Questo esercizio è utile per comprendere il funzionamento delle chiamate asincrone con `fetch()`, la gestione del DOM con `createElement()` e l’integrazione con framework CSS come Bootstrap per una presentazione visiva efficace.
