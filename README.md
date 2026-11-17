# S.peaking

Anamnesi · Valutazione funzionale · Preparazione atletica.
Barra di navigazione scura a sinistra (in basso su smartphone), area di lavoro centrale chiara, accenti gialli, stampa A4 pulita.

## Nuovo cliente: anamnesi
«+ Nuovo Cliente» apre la pagina «Anamnesi, obiettivi e stile di vita»: dati anagrafici e misure (età, sesso, peso, altezza, livello, circonferenze, certificato medico, con BMI e rapporti vita/fianchi e vita/altezza calcolati), PAR-Q a 7 domande, stato di salute, obiettivi a scelta multipla, gara o sport obiettivo, sport extra settimanali con stima del carico, gruppi muscolari prioritari e preferenza di split (la decisione finale spetta al Personal Trainer). Dal dettaglio atleta il pulsante «Anamnesi» riapre il modulo per modificarlo.

## Test funzionali
Dal dettaglio atleta («Test funzionali») o dai passi in alto (1. Anamnesi · 2. Test · 3. Scheda). Ogni test ha la guida espandibile «cos'è, a cosa serve, come eseguirlo».
- Controllo motorio e postura: Overhead Squat Assessment, Single Leg Squat (dx/sx).
- Mobilità e flessibilità: ASLR, Shoulder Mobility, Test di Thomas (dx/sx), Sit-and-Reach.
- Core e resistenza: Plank, Push-up, Pull-up / Body Row.
- Forza: 1RM diretto o stimato (Epley e Brzycki) su più esercizi.
- Cardio: Rockport (usa peso, età e sesso dell'anamnesi), Ruffier-Dickson, Cooper.
I risultati sono salvati nel cliente e finiscono nel backup.

## Generatore di schede
Pagina intera con: logica di lavoro e riquadro **Date chiave** (inizio, settimana di scarico proposta nella 4ª settimana, cambio scheda proposto dopo 6 settimane, tutto modificabile); **warm-up** e **cool-down** generati in automatico dai muscoli allenati e modificabili; tabella esercizi con muscolo, serie, ripetizioni, kg, recupero e **note esecutive e tecniche** (compilate in automatico per gli esercizi della libreria); **volume settimanale per muscolo** con confronto MEV/MRV (valori indicativi). Le stesse sezioni compaiono nella scheda visualizzata, stampata e scaricata.

## Stato degli atleti
Calcolato dalla scheda più recente di ogni atleta (data di cambio scheda, o 6 settimane dall'inizio se manca):
- **Attivi**: cambio scheda non ancora raggiunto.
- **In scadenza**: cambio scheda entro 7 giorni o già superato.
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
