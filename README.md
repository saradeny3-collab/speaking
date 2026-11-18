# S.peaking

Anamnesi · Valutazione funzionale · Preparazione atletica.
Barra di navigazione scura a sinistra (in basso su smartphone), area di lavoro centrale chiara, colore principale **viola #4B0082** con testo bianco, stampa A4 pulita.

## Nuovo cliente: anamnesi
«+ Nuovo Cliente» apre la pagina «Anamnesi, obiettivi e stile di vita»: dati anagrafici e misure (età, sesso, peso, altezza, livello, circonferenze, certificato medico, con BMI e rapporti vita/fianchi e vita/altezza calcolati), PAR-Q a 7 domande, stato di salute con **infortuni e traumi** (zona, lato, stato), obiettivi a scelta multipla, gara o sport obiettivo, sport extra settimanali con stima del carico, gruppi muscolari prioritari e preferenza di split (la decisione finale spetta al Personal Trainer). Dal dettaglio atleta il pulsante «Anamnesi» riapre il modulo per modificarlo.

## Infortuni e traumi
Nell’anamnesi, «+ Aggiungi infortunio o trauma»: zona (cervicale, spalla, gomito, polso/mano, lombare, anca/inguine, ginocchio, caviglia/piede), lato e stato.
- **Acuto**: sono esclusi tutti gli esercizi che caricano la zona.
- **In recupero**: sono esclusi quelli ad alto carico; gli altri compaiono con l’etichetta «cautela».
- **Pregresso**: tutti ammessi; quelli ad alto carico sono segnalati «cautela».
Vengono favoriti esercizi di rinforzo e alternative sicure (es. lombare → dead bug, bird dog, hip thrust; spalla → face pull, elevazioni prone) e, se non è acuto, la mobilità della zona. La regola applicata compare sotto l’elenco, nella logica di lavoro e nel riepilogo del generatore. Valgono per selezione automatica, libreria, blocchi, proposte del prossimo esercizio ed editor (etichetta rossa «da evitare» o arancione «cautela» sotto il nome). Per i clienti già salvati, gli infortuni scritti nelle note vengono riconosciuti e proposti alla prossima apertura dell’anamnesi.

## Test funzionali
Dal dettaglio atleta («Test funzionali») o dai passi in alto (1. Anamnesi · 2. Test · 3. Scheda). Ogni test ha la guida espandibile «cos'è, a cosa serve, come eseguirlo».
- Controllo motorio e postura: Overhead Squat Assessment, Single Leg Squat (dx/sx).
- Mobilità e flessibilità: ASLR, Shoulder Mobility, Test di Thomas (dx/sx), Sit-and-Reach.
- Core e resistenza: Plank, Push-up, Pull-up / Body Row.
- Forza: 1RM diretto o stimato (Epley e Brzycki) su più esercizi.
- Cardio: Rockport (usa peso, età e sesso dell'anamnesi), Ruffier-Dickson, Cooper.
I risultati sono salvati nel cliente e finiscono nel backup.

## Generatore di schede
Pagina intera, in ordine: impostazione (nome, **sedute a settimana**, **split**), pulsante **⚡ Genera proposta automatica**, **Logica di lavoro**, riquadro **Tempistiche di programmazione** (inizio, scarico nella 4ª settimana, cambio scheda dopo 6 settimane, tutto modificabile), warm-up, **sedute**, cool-down, volume settimanale, **legenda**.

- **Split**: Full Body, Upper/Lower, Push/Pull/Legs, **Push/Pull** (gambe incluse: spinta + quadricipiti / tirata + femorali), **Push/Pull solo parte alta**, **Upper/Lower + Full Body**, **Arnold split** (petto e dorso · spalle e braccia · gambe), Monofrequenza e **Personalizzato**: scegli il tipo di ogni seduta (Full Body, Upper, Lower, Push, Pull, Legs, Push + gambe, Pull + gambe, Petto e dorso, Spalle e braccia, Petto e tricipiti, Dorso e bicipiti, Spalle e core, Braccia, Glutei e femorali).
- **Tendina «⇅ Varia esercizio»** sotto ogni esercizio: da 5 a 8 alternative della libreria compatibili con livello, PAR-Q, test e infortuni (prima «stesso movimento», poi «stesso muscolo o pattern»), più «Altro dalla libreria…». Serie, ripetizioni, RPE e recupero restano se il tipo di esercizio è lo stesso.
- **Ogni esercizio è una scheda** che si legge per intero, senza scorrere in orizzontale: nome e tendina, serie, ripetizioni, RPE, kg, recupero; carico target, pattern, muscolo; note esecutive a tutta larghezza; tasti ✦ ⇄ × sempre visibili.
- **Riscaldamento e defaticamento**: elenco di esercizi della libreria (massimo 10 minuti ciascuno) con dosaggio e minuti modificabili, tendina «Varia», «+ Aggiungi esercizio», «Libreria esercizi» e totale dei minuti (avviso oltre i 10).

- **Selezione automatica**: incrocia obiettivi multipli, sport o gara, gruppi prioritari, livello, PAR-Q, carico degli sport extra e test funzionali. Ai principianti propone di preferenza macchine e multiarticolari semplici (linee guida del manuale CSEN).
- **Prescrizione**: serie, ripetizioni, **RPE**, **carico target (%1RM / RIR)**, kg calcolati dal 1RM stimato quando c'è, recupero.
- **Tabella per seduta**: esercizio, pattern, muscolo, serie, ripetizioni, RPE, carico target, kg, recupero, note esecutive (postura e respirazione). Scorre in orizzontale su schermi piccoli.

## Editor modulare interattivo (nuovo)
Voce **Editor schede** nel menu, oppure «Modifica nell'editor» da una scheda salvata, o «Editor scheda» dal dettaglio atleta.
- In alto gli **atleti come pulsanti**: un clic per passare da uno all'altro (se ci sono modifiche non salvate chiede conferma). Con più di 6 atleti compare la ricerca.
- Menu **Scheda** per scegliere quale scheda dell'atleta aprire; «+ Scheda vuota» o «⚡ Generatore».
- **Sedute come schede** (Seduta 1 · Upper A, Seduta 2 · Lower A…), più «+ Seduta», «Duplica seduta», «Elimina seduta».
- Esercizi a schede leggibili per intero (come nel generatore), con la tendina **«⇅ Varia esercizio»**.
- **Riscaldamento e defaticamento** come elenco di esercizi (massimo 10 minuti), con «Scrivi in automatico».
- **Celle modificabili** direttamente: esercizio, serie, reps, RPE, recupero, kg, carico target, note, pattern, muscolo. Scrivendo un esercizio della libreria, le altre celle si compilano da sole.
- Righe: ↑ ↓ per riordinare, ⇄ per sostituire dalla libreria, × per togliere, SS per la superserie con la riga sopra.
- **+ Aggiungi esercizio**, **Libreria esercizi** e **+ Aggiungi blocco**: superserie (spinta + tirata, gambe, braccia), triserie/circuito, blocco esplosivo, core, finisher con trasporto, mobilità, blocco vuoto, oppure una **seduta completa** (Full Body, Upper, Lower, Push, Pull, Legs, Petto e tricipiti…). Gli esercizi sono scelti dal profilo dell'atleta.
- **Salva scheda** aggiorna la scheda esistente; **Salva come nuova** ne crea una copia. «Anteprima · Stampa · Excel» esporta anche le modifiche non ancora salvate.

## Proposte del prossimo esercizio
Nell’editor e nel generatore, quando inserisci un esercizio (scritto, dalla libreria o da una proposta), sotto la riga compaiono 5 proposte:
1. **Antagonista**, già impostato in superserie (puoi togliere la spunta);
2. **Stesso muscolo**, di solito un complementare dopo un multiarticolare;
3. **Pattern complementare**, la variante che manca nella seduta (es. dopo la panca: spinta verticale o tirata);
4. **Core e stabilità**, scelto in base al pattern;
5. **Funzionale / correttivo**: mobilità dai test, rinforzo per l’infortunio, esercizio specifico dello sport, trasporto.
Ogni campo è modificabile (con l’elenco della libreria) e «⇄ Altra» propone un’alternativa della stessa tipologia. «+ Aggiungi» lo inserisce subito dopo e propone il successivo. Il tasto ✦ su una riga apre le proposte per quell’esercizio; la spunta «Proponi a ogni esercizio» le attiva o disattiva in automatico.

## Libreria esercizi
191 esercizi: quelli già presenti, il **repertorio del corso Personal Trainer CSEN** e 28 esercizi di **riscaldamento e defaticamento** (cardio leggero, mobilità, attivazione, allungamento, foam rolling) (petto, dorso, spalle, braccia, cosce, glutei, polpacci, addome). Organizzati per **pattern di movimento** (Push, Pull, Squat, Hinge, Carry, Isopush, Mobilità), con barra di ricerca e **filtri rapidi** per pattern, **tipo** (Base multiarticolare, Complementare di isolamento, Esplosivo, Core, Mobilità, Riscaldamento) e **attrezzatura** (bilanciere, manubri, macchine, cavi, corpo libero, piccoli attrezzi). Avvisi «sconsigliato dai test», «sconsigliato dal PAR-Q», «livello superiore».

## Legenda e glossario
La legenda mostra solo i **nomi degli esercizi come pulsanti**: un clic apre la tendina con la spiegazione completa («Apri tutte» per aprirle insieme; in stampa e PDF escono tutte aperte). Per ogni esercizio: tipo e attrezzatura, scopo funzionale, muscoli target primari e secondari, postura e assetto iniziale, fase eccentrica e concentrica, respirazione, sicurezza. In fondo alla scheda c'è il **glossario dei termini tecnici** (1RM, RIR, RPE, superserie, MEV/MRV, deload, Valsalva, DOMS…).

## Esportazione della scheda
Dalla scheda salvata o dall'editor:
- **Stampa / Esporta PDF**: apre la stampa del browser; scegli «Salva come PDF» per un documento A4 senza menu, con legenda e glossario su due colonne.
- **Esporta Excel (.xlsx)**: foglio «Scheda» con intestazione atleta e colonne Seduta, Esercizio, Pattern, Muscolo, Serie, Ripetizioni, RPE, Carico target, Kg, Recupero, Note, più «Sett. 1…N» (scarico segnato) per annotare i carichi settimana per settimana; fogli «Legenda esercizi» e «Glossario».
- **CSV** (separatore «;» per Excel in italiano) e **Scarica HTML**.

## Stato degli atleti
Calcolato dalla scheda più recente di ogni atleta (data di cambio scheda, o 6 settimane dall'inizio se manca):
- **Attivi**: cambio scheda non ancora raggiunto.
- **In scadenza**: cambio scheda entro 7 giorni o già superato.
- **Check-in**: atleta attivo senza check-in da almeno 14 giorni.

## Pubblicazione su GitHub Pages
1. Carica `index.html` nella root del repository (il file, non lo zip).
2. Settings → Pages → Deploy from a branch → main → / (root).

## Dati
- Si salvano nel browser (IndexedDB) e restano dopo la ricarica. Non si sincronizzano tra dispositivi.
- Il sito parte vuoto, senza dati di esempio.
- Dal tasto **Backup**: **Esporta backup (JSON)** e **Importa backup (JSON)** (Unisci o Sostituisci).
- Fai un backup regolare: se cancelli i dati del browser, i dati locali vanno persi.
- Sono dati personali e sanitari: tieni conto del GDPR e proteggi i file di backup.
