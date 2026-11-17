# Speaking

Sito per la gestione di una palestra: clienti, schede di allenamento, backup dei dati.
Tema scuro ad alto contrasto (nero, giallo, bianco) e stampa A4 pulita.

## Pubblicazione su GitHub Pages
1. Carica `index.html` nella root del repository (il file, non lo zip).
2. Settings → Pages → Deploy from a branch → main → / (root).

## Dati
- Si salvano nel browser (IndexedDB) e restano dopo la ricarica. Non si sincronizzano tra dispositivi.
- Il sito parte vuoto, senza dati di esempio.
- **Esporta backup (JSON)** scarica clienti, schede e foto dei documenti. **Importa backup (JSON)** li ripristina (Unisci o Sostituisci).
- Fai un backup regolare: se cancelli i dati del browser, i dati locali vanno persi.
- Sono dati personali (anche foto di documenti): tieni conto del GDPR e proteggi i file di backup.

## Stampa
Dalla scheda di un cliente usa «Stampa», oppure «Stampa elenco» dalla Home. In stampa spariscono menu e pulsanti, e il tema diventa testo nero su fondo bianco, formato A4.
