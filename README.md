# Volume Smart

App Android nativa in Kotlin per programmare il volume multimediale in fasce orarie.

## Funzioni
- Fasce giornaliere con ora di inizio/fine e volume 0–100%.
- Volume configurabile fuori dalle fasce.
- Quattro sfondi colorati selezionabili.
- Allarmi esatti e ripristino della programmazione dopo il riavvio.

## Aprire il progetto
1. Installa Android Studio.
2. Estrai il progetto e apri la cartella `VolumeSmart`.
3. Attendi la sincronizzazione Gradle.
4. Collega un telefono Android con debug USB attivo oppure avvia un emulatore.
5. Premi Run.

## Permesso importante
Su Android 12 e successivi, consenti a Volume Smart di programmare allarmi esatti quando richiesto. Se non lo consenti, gli orari potrebbero non essere rispettati con precisione.

## Limiti della prima versione
- Controlla il volume multimediale, non suoneria, sveglia o notifiche.
- Lo 0% azzera il volume multimediale, ma non attiva la modalità Non disturbare.
- Gli orari sono giornalieri. Evita fasce sovrapposte: l'ultima regola che scatta determina il volume.
- Alcuni produttori Android applicano restrizioni aggressive alle app in background: potrebbe essere necessario consentire l'attività in background/avvio automatico nelle impostazioni del telefono.

## Pubblicazione su GitHub
Crea un nuovo repository GitHub, ad esempio `volume-smart`, quindi carica tutti i file e le cartelle contenuti in questo progetto (non solo il file ZIP).
