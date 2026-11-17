# Speaking

Gestionale per palestra: utenti (con lettura del documento d'identità), schede di allenamento e andamento dei carichi.
Sito statico: HTML, CSS e JavaScript, senza build e senza server.

## Struttura

```
index.html
css/style.css
js/app.js
README.md
```

## Pubblicare su GitHub Pages

1. Crea un repository su GitHub e carica questi file mantenendo le cartelle.
2. *Settings → Pages → Deploy from a branch*, branch `main`, cartella `/ (root)`.
3. Dopo circa un minuto il sito è su `https://TUO-UTENTE.github.io/NOME-REPO/`.

## Dove vengono salvati i dati

Utenti, schede e foto dei documenti sono salvati **solo nel browser del dispositivo** (IndexedDB), non nel repository e non su un server.
Quindi:
- ogni dispositivo/browser ha il proprio archivio, non sincronizzato;
- cancellare i dati del sito dal browser elimina anche gli utenti;
- per usarlo da più dispositivi o con più operatori serve un backend (es. Supabase o Firebase).

## Impostazioni in `js/app.js`

- `LOGIN_ATTIVO`: mostra la schermata di login. È solo un segnaposto grafico e **non protegge nulla**: su un sito pubblico chiunque può aprirlo.
- `CARICA_DATI_DEMO`: con `true` precarica utenti e schede di esempio al primo avvio.

## Lettura del documento

La lettura automatica usa Tesseract.js, caricato da jsDelivr alla prima lettura (serve internet) e poi eseguita nel browser: le immagini non vengono inviate a nessun server.
Per usarlo offline, copia i file di Tesseract in `vendor/tesseract/` (`tesseract.min.js`, `worker.min.js`, il core e `lang/ita.traineddata`, `lang/eng.traineddata`).

## Privacy

I dati dei clienti e le immagini dei documenti sono dati personali (GDPR): usa il sito solo su dispositivi protetti e informa gli iscritti sul trattamento.
