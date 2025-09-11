# Cartella `codes`

Questa cartella contiene anche file di supporto ai codici. I percorsi nei codici devono subire delle modifiche affinchè non diano errore, poichè sono pensati per una struttura diversa da quella presente in questo GitHub.

## Cartella `data`
Alcuni file originali, presenti nella cartella `data/`, erano troppo pesanti per essere caricati su GitHub.  
In particolare:
- `lichess_games_matched`
- `lichess_activity_matched`
- `lichess_users`

Questi file, originariamente in formato `.jsonl`, sono stati convertiti in `.json` mantenendo **solo la prima riga** a titolo dimostrativo.  
Lo scopo è mostrare la **struttura dei dati** senza includere l’intero dataset.

## Gestione dei limiti di Lichess
Per evitare problemi di **blocco IP** da parte di Lichess durante il download massivo dei dati:
- sono stati creati appositi **token di autenticazione**,  
- gli indirizzi IP delle richieste sono stati **ruotati tramite Decodo**, così da distribuire il carico ed evitare il rate limiting.  

## Nota d'uso
- I file qui presenti servono come esempio/struttura, **non contengono il dataset completo**.
- Per eventuali analisi è necessario ricostruire i file completi a partire dalle fonti originali.
