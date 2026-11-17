# S.peaking

Anamnesi · Valutazione funzionale · Preparazione atletica.
Barra di navigazione scura a sinistra (in basso su smartphone), area di lavoro centrale chiara, accenti gialli, stampa A4 pulita.

## Stato degli atleti
Calcolato dalla scheda più recente di ogni atleta:
- **Attivi**: scheda iniziata da meno di 42 giorni (6 settimane).
- **In scadenza**: scheda iniziata da 35 giorni o più (cambio scheda entro 7 giorni o già superato).
- **Check-in**: atleta attivo senza check-in da almeno 14 giorni. Il check-in si registra dal dettaglio atleta con «Check-in fatto oggi».

## Pubblicazione su GitHub Pages
1. Carica `index.html` nella root del repository (il file, non lo zip).
2. Settings → Pages → Deploy from a branch → main → / (root).

## Dati
- Si salvano nel browser (IndexedDB) e restano dopo la ricarica. Non si sincronizzano tra dispositivi.
- Il sito parte vuoto, senza dati di esempio.
- Dal tasto **Backup** (menu a tendina): **Esporta backup (JSON)** scarica clienti, schede e foto dei documenti. **Importa backup (JSON)** li ripristina (Unisci o Sostituisci).
- Fai un backup regolare: se cancelli i dati del browser, i dati locali vanno persi.
- Sono dati personali (anche foto di documenti): tieni conto del GDPR e proteggi i file di backup.

## Stampa
Dalla scheda di un cliente usa «Stampa», oppure «Stampa elenco» dal menu Backup. In stampa spariscono menu e pulsanti, e il tema diventa testo nero su fondo bianco, formato A4.
