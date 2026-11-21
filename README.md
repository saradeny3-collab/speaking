# S.peaking

Anamnesi · Valutazione funzionale · Preparazione atletica.
Barra di navigazione scura a sinistra (in basso su smartphone), area di lavoro centrale chiara, colore principale **viola #4B0082** con testo bianco, stampa A4 pulita.

## Nuovo cliente: anamnesi
«+ Nuovo Cliente» apre la pagina «Anamnesi, obiettivi e stile di vita»: dati anagrafici e misure (età, sesso, peso, altezza, livello, circonferenze, certificato medico con data di scadenza, con BMI e rapporti vita/fianchi e vita/altezza calcolati), PAR-Q a 7 domande, stato di salute con **infortuni e traumi** (zona, lato, stato, «fermo fino al»), obiettivi a scelta multipla, gara o sport obiettivo, sport extra settimanali con stima del carico, gruppi muscolari prioritari e preferenza di split (la decisione finale spetta al Personal Trainer). Dal dettaglio atleta il pulsante «Anamnesi» riapre il modulo per modificarlo.

## Infortuni e traumi
Nell’anamnesi, «+ Aggiungi infortunio o trauma»: zona (cervicale, spalla, gomito, polso/mano, lombare, anca/inguine, ginocchio, caviglia/piede), lato, stato e **«Fermo fino al»** (tasto 📅 calendario, oppure +1/+2/+4/+6 settimane da oggi): la data la chiedi al cliente.
- **Acuto** e **In recupero**: la zona resta ferma. Tutti gli esercizi che la caricano sono esclusi e non entrano nella scheda, compresi rinforzo e mobilità della zona; il cliente allena il resto del corpo.
- **Pregresso**: tutti ammessi; quelli ad alto carico sono segnalati «cautela». Solo qui vengono favoriti rinforzo e mobilità della zona (es. lombare → dead bug, bird dog, hip thrust; spalla → face pull, elevazioni prone).
- **Scadenza**: la data «fermo fino al» è la scadenza per cambiare la scheda. Il generatore propone il cambio scheda in quella data (se arriva prima delle 6 settimane); l’editor la segnala con «Usa come cambio scheda»; l’atleta passa «In scadenza» 10 giorni prima e, a data superata, compare «Verifica infortunio». Gli esercizi restano esclusi finché non cambi lo stato in «Pregresso».
- **Blocco**: un esercizio escluso scritto a mano compare con l’etichetta rossa «escluso per infortunio»; al salvataggio la scheda non si salva finché non lo togli («Togli e salva»). In libreria il pulsante diventa «Escluso».
Le regole valgono per selezione automatica, libreria, blocchi, proposte del prossimo esercizio, «Varia», riscaldamento ed editor. Per i clienti già salvati, gli infortuni scritti nelle note vengono riconosciuti e proposti alla prossima apertura dell’anamnesi.

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
- **Ogni esercizio è una scheda** che si legge per intero, senza scorrere in orizzontale: nome e tendina, serie, ripetizioni, RPE, recupero; carico target, pattern, muscolo; note esecutive a tutta larghezza; tasti ✦ ⇄ × sempre visibili.
- **Riscaldamento e defaticamento**: elenco di esercizi della libreria (massimo 10 minuti ciascuno) con dosaggio e minuti modificabili, tendina «Varia», «+ Aggiungi esercizio», «Libreria esercizi» e totale dei minuti (avviso oltre i 10).

- **Selezione automatica**: incrocia obiettivi multipli, sport o gara, gruppi prioritari, livello, PAR-Q, carico degli sport extra e test funzionali. Ai principianti propone di preferenza macchine e multiarticolari semplici (linee guida del manuale CSEN).
- **Prescrizione**: serie, ripetizioni, **RPE**, **carico target (%1RM / RIR)** con i kg (≈) calcolati dal 1RM stimato quando c'è, recupero.
- **Tabella per seduta**: esercizio, pattern, muscolo, serie, ripetizioni, RPE, carico target, recupero, note esecutive (postura e respirazione). Niente colonna Kg: i kg, se calcolati, sono nel carico target.

## Editor modulare interattivo (nuovo)
Voce **Editor schede** nel menu, oppure «Modifica nell'editor» da una scheda salvata, o «Editor scheda» dal dettaglio atleta.
- In alto gli **atleti come pulsanti**: un clic per passare da uno all'altro (se ci sono modifiche non salvate chiede conferma). Con più di 6 atleti compare la ricerca.
- Menu **Scheda** per scegliere quale scheda dell'atleta aprire; «+ Scheda vuota» o «⚡ Generatore».
- **Sedute come schede** (Seduta 1 · Upper A, Seduta 2 · Lower A…), più «+ Seduta», «Duplica seduta», «Elimina seduta».
- Esercizi a schede leggibili per intero (come nel generatore), con la tendina **«⇅ Varia esercizio»**.
- **Riscaldamento e defaticamento** come elenco di esercizi (massimo 10 minuti), con «Scrivi in automatico».
- **Celle modificabili** direttamente: esercizio, serie, reps, RPE, recupero, carico target, note, pattern, muscolo. Scrivendo un esercizio della libreria, le altre celle si compilano da sole.
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

## Dispense di preparazione specifica: Hyrox e judo agonistico (nuovo)
Voce **Dispense** nel menu: le due dispense consultabili (modello prestativo, 4 fasi del macrociclo, mesociclo, microciclo tipo, stazioni o qualità specifiche, sedute tipo) e l’elenco dei loro esercizi in libreria con la guida completa.
- **Anamnesi**: se il campo «Gare, competizioni o sport» contiene «Hyrox» o «judo», il generatore usa il programma della dispensa. Il nuovo campo **«Data della gara obiettivo»** serve a calcolare la fase.
- **Generatore**: lo split proposto è **«Hyrox (dispensa)»** o **«Judo agonistico (dispensa)»**, con il menu **«Fase della preparazione»**. La fase si calcola dalle settimane che mancano alla gara e si può cambiare a mano:
  - Hyrox: Base (oltre 16 settimane), Build (9–16), Specific (3–8), Taper (ultime 2);
  - judo: Preparazione generale (oltre 16), Conversione (9–16), Specificità (4–8), Taper (ultime 3).
- **Sedute della dispensa** con i dosaggi di ogni fase:
  - Hyrox: forza gambe + stazioni, forza parte alta + catena posteriore, compromised running; con 4–6 sedute si aggiungono ripetute di corsa, corsa lunga in zona 2 e riposo attivo;
  - judo: forza massima e core, ipertrofia funzionale e presa, prevenzione e mobilità, potenza esplosiva e presa, circuito specifico, HIIT e aerobico in zona 2.
- **Profilo dell’atleta**: livello, PAR-Q, test e infortuni restano validi. Un esercizio non adatto viene sostituito con un’alternativa del profilo, e la logica di lavoro elenca le sostituzioni.
- **Date chiave**:
  - Hyrox: mesociclo 3+1 (cambio scheda dopo 4 settimane, scarico nella 4ª);
  - entrambi: cambio scheda anticipato all’inizio della fase successiva;
  - in Taper: niente scarico e cambio scheda alla data della gara.
- **Editor**, «+ Aggiungi blocco»: Compromised running (Hyrox), Stazioni Hyrox (burpee + wall ball), Blocco presa (judo), HIIT judo 15/15 e 30/15.
- Glossario con i termini delle dispense (compromised running, Roxzone, zona 2, VT2, EMOM, unbroken, tapering, RFD, kumi-kata, kuzushi, uchi-komi, randori, ukemi, golden score).
- I dosaggi che la dispensa non indica sono segnati «dosaggio indicativo» e vanno validati dal Personal Trainer.

## Judo: stagione agonistica e programma di 12 settimane (nuovo)
Dalla dispensa «Proposta di workout per il judo agonistico» (due scansioni, 30 pagine). La preparazione del judo è coperta su tre orizzonti:
- **Lungo periodo (stagione):** off-season (8–12 settimane), pre-season (6–8), in-season (16–24) e transizione (2–4), oltre al macrociclo di 24 settimane della prima dispensa.
- **Medio periodo (12 settimane verso la gara):** 20 sessioni in 6 blocchi da 2 settimane:
  1. Costruzione della base (sessioni 1–3);
  2. Sviluppo della potenza (4–6);
  3. Resistenza e tecnica (7–9);
  4. Picco di performance (10–12);
  5. Preparazione alla gara (13–18);
  6. Fase di picco (19–20).
- **Breve periodo:** «Mantenimento tra le gare» per le gare minori e «Transizione · recupero attivo» dopo la gara. La dispensa descrive questi due periodi senza sedute dettagliate, quindi le sedute sono costruite da me e segnate «dosaggio indicativo».

Nel generatore, con «judo» nel campo gara dell’anamnesi:
- **Programma proposto:** se la gara è entro 12 settimane (o passata da meno di 4) viene proposto per primo lo split **«Judo: 12 settimane verso la gara»**; altrimenti il macrociclo di 24 settimane. Entrambi restano nel menu.
- **Blocco:** si calcola dalla data della gara, con cambio scheda alla fine del blocco e nella fase di picco alla gara.
- **Sedute:** ogni seduta unisce palestra e tatami (uchi-komi, nage-komi, ne-waza, randori) con i dosaggi della dispensa: % 1RM con i kg dal massimale, % del peso corporeo e recuperi.

Altre novità:
- **Libreria:** 22 esercizi nuovi (randori, uchi-komi, nage-komi, ne-waza, sprint, corsa continua e a intervalli, circuiti pesi e cardio, battle rope, agilità, salti, power push-up, power clean, strappo, slancio…). Le indicazioni «Dalla dispensa Judo 12 settimane» sono anche sugli esercizi già presenti.
- **Pagina Dispense:** terza scheda «Judo 12 settimane».
- **Editor:** nuovo blocco «Lavoro sul tatami (judo)».
- **Glossario:** periodi della stagione, shiai, tori/uke, ne-waza/katame-waza, tokui-waza.

## Yanagi Academy: allenamenti di gruppo e squadra (judo)
Voce **Yanagi Academy** nel menu. «+ Nuovo gruppo o squadra» apre le impostazioni:
- **Gruppo**: nome, categoria o fascia d’età (Bambini, Ragazzi/Esordienti, Cadetti, Junior, Senior, Master, Amatori, misto), inizio e fine facoltativa del programma.
- **Giorni e orari**: spunta i giorni della settimana, con l’ora di inizio e la durata (da 1 a 3 ore).
- **Obiettivo gara agonistica**: nome, data, livello e luogo. La fase si calcola dalla data: oltre 16 settimane *preparazione generale*, 9–16 *conversione*, 4–8 *specificità*, ultime 3 *taper*, poi 3 settimane di *transizione*. Ogni 4ª settimana è di scarico (non nel taper). La fase si può anche scegliere a mano; senza gara il gruppo resta in preparazione generale.
- **Atleti**: quelli in archivio (spunta) e altri nomi scritti a mano.

**Calendario e sedute**: riepilogo, calendario del mese con le sedute colorate per fase (ora, focus, scarico, ✓ svolta, ✕ annullata, 🏆 gara) e l’elenco delle prossime sedute. Il calendario arriva alla data di fine, oppure a 3 settimane dopo la gara, oppure a 12 settimane dall’inizio.

**Struttura di ogni seduta**, proposta in automatico da fase, focus del giorno e durata:
1. Riscaldamento (saluto, corsa con andature o giochi, mobilità, ukemi);
2. Preparazione atletica (a corpo libero e piccoli attrezzi, diversa per fase);
3. Tecnica ed esercizi specifici (tecnica del giorno, kumi-kata, uchi-komi, nage-komi o ne-waza, situazioni di gara);
4. Randori (numero di round calcolato dai minuti; in specificità round da 4 min con golden score);
5. Defaticamento (stretching, respirazione, saluto).

Il focus ruota tra i giorni: **A** forza e tachi-waza, **B** rapidità, potenza e ne-waza, **C** resistenza specifica e randori (**M** seduta completa con un solo allenamento a settimana). Per Bambini e Ragazzi: giochi, percorsi e randori di studio.

Nella seduta si cambiano minuti, esercizi (con l’elenco della libreria), dosaggi e note; si segna lo stato (programmata, svolta, annullata), i presenti e le note. «Salva seduta» vale solo per quella data; «Ripristina proposta automatica» torna alla proposta. Ci sono anche «Stampa / PDF», «Condividi con il gruppo» (testo per WhatsApp o altre app) e la guida «Come si esegue» per gli esercizi della libreria.

**Esportazione**: «Stampa calendario / PDF» (A4 orizzontale) ed «Esporta Excel (.xlsx)», con il foglio «Calendario» (una riga per seduta, con le cinque parti) e il foglio «Gruppo» (dati e atleti).

I gruppi sono salvati nel cloud (`users/<UID>/gruppi`), sul dispositivo e nel backup JSON. Contenuti, dosaggi e minuti proposti sono indicativi e vanno adattati dal tecnico.

## Libreria esercizi
238 esercizi. Ai 191 di base se ne aggiungono 47 dalle dispense (22 del programma judo di 12 settimane, elencati sopra) e 25 dalle prime due:
- **Hyrox**: SkiErg, vogatore, sled pull alla fune, sled drag, burpee broad jump, affondi con sandbag, rematore Pendlay, corsa a ritmo gara, ripetute a soglia, corsa lunga in zona 2;
- **judo**: gi pull-up, trazioni con asciugamano o fune, pinch grip, kumi-kata isometrico, landmine rotational press, squat jump con elastico, jump squat zavorrato, power clean da sospensione, Turkish get-up, Zercher carry, isometrie del collo, Y-T-W-L, uchi-komi con elastico, complex con bilanciere, air bike 30/15.

Nuovo tipo **Condizionamento** (ergometri, corsa, circuiti a tempo): non conta nel volume per muscolo. Nuovo filtro **Sport** (Hyrox · Judo). Legenda e libreria mostrano le indicazioni «Dalla dispensa…».

I 191 di base comprendono gli esercizi originali, il **repertorio del corso Personal Trainer CSEN** e 28 esercizi di **riscaldamento e defaticamento** (cardio leggero, mobilità, attivazione, allungamento, foam rolling) (petto, dorso, spalle, braccia, cosce, glutei, polpacci, addome). Organizzati per **pattern di movimento** (Push, Pull, Squat, Hinge, Carry, Isopush, Mobilità), con barra di ricerca e **filtri rapidi** per pattern, **tipo** (Base multiarticolare, Complementare di isolamento, Esplosivo, Core, Trasporto, Condizionamento, Mobilità, Riscaldamento) e **attrezzatura** (bilanciere, manubri, macchine, cavi, corpo libero, piccoli attrezzi). Avvisi «sconsigliato dai test», «sconsigliato dal PAR-Q», «livello superiore».

## Legenda e glossario
La legenda mostra solo i **nomi degli esercizi come pulsanti**: un clic apre la tendina con la spiegazione completa («Apri tutte» per aprirle insieme; in stampa e PDF escono tutte aperte). Per ogni esercizio: tipo e attrezzatura, scopo funzionale, muscoli target primari e secondari, postura e assetto iniziale, fase eccentrica e concentrica, respirazione, sicurezza. In fondo alla scheda c'è il pulsante **📖 Glossario dei termini tecnici** (1RM, RIR, RPE, superserie, MEV/MRV, deload, Valsalva, DOMS…): resta chiuso e si apre solo con un clic. In stampa e PDF esce solo se l'hai aperto.

## Esportazione della scheda
Dalla scheda salvata o dall'editor:
- **Stampa / Esporta PDF**: apre la stampa del browser; scegli «Salva come PDF» per un documento A4 senza menu, con legenda (e glossario, se aperto) su due colonne. Non escono sedute a settimana, split e logica di lavoro.
- **Esporta Excel (.xlsx)**: foglio «Scheda» con intestazione atleta (atleta, obiettivi, gara, date; senza livello, nome scheda, sedute a settimana e logica di lavoro) e colonne Seduta, Esercizio, Pattern, Muscolo, Serie, Ripetizioni, RPE, Carico target, Recupero, Note, più «Sett. 1…N» (scarico segnato) per annotare i carichi settimana per settimana; fogli «Legenda esercizi» e «Glossario».
- **CSV** (separatore «;» per Excel in italiano) e **Scarica HTML**.
- **📲 Condividi con l’atleta**: link alla versione interattiva per smartphone (vedi sotto).

## Condivisione con l’atleta (link per smartphone)
Dalla scheda salvata (o dall’anteprima dell’editor) il pulsante **📲 Condividi con l’atleta** crea un link alla versione interattiva della scheda:
- **WhatsApp** (apre direttamente la chat dell’atleta, se il telefono è nell’anamnesi), **Telegram**, **Altre app…** (menu di condivisione del telefono), **Copia link**, **Anteprima**.
- L’atleta apre il link in Safari o Chrome, senza installare nulla: sedute a schede, settimana corrente (con la settimana di scarico segnalata), riscaldamento e defaticamento, per ogni esercizio serie, ripetizioni, RPE, carico target, recupero e note, e la tendina «Come si esegue».
- Per ogni serie segna **kg** e **ripetizioni** e tocca **✓**: parte il **timer di recupero** (vibrazione e suono alla fine, +15 s, Stop; in superserie parte dopo l’ultimo esercizio). I dati restano sul suo telefono, settimana per settimana.
- **Invia i risultati al PT** manda il riepilogo della seduta (es. «Panca piana: 60 kg × 8, 60 kg × 7») su WhatsApp, Telegram o un’altra app.
- Il link contiene solo la scheda: niente anamnesi, PAR-Q, infortuni, test o logica di lavoro. La scheda sta dopo il «#» dell’indirizzo, quindi non arriva a GitHub né ad altri server; chi ha il link però può leggerla, quindi va mandato solo all’atleta.
- Il link è una **fotografia** della scheda: se la modifichi, manda un link nuovo. In futuro, con Firebase, potrà diventare un link sempre aggiornato.
- Prima dell’invio la finestra controlla che il sito pubblicato sia aggiornato. Se all’atleta compare «link tagliato», rimandalo con «Copia link» incollato nella chat.
- Se apri l’app dal file sul computer e non dal sito, la prima volta ti chiede l’indirizzo del sito pubblicato (es. `https://tuonome.github.io/speaking/`).

## Elenco atleti (PDF, Excel, CSV)
In home il pulsante **Elenco atleti ▾** esporta tutti gli atleti in ordine di cognome, con la data di aggiornamento:
- **Stampa / Esporta PDF**: anteprima a schermo, poi «Stampa / Salva PDF» → «Salva come PDF». Foglio A4 orizzontale con cognome, nome, codice fiscale, data di nascita, età, telefono, email, città, certificato medico (con scadenza) e stato.
- **Esporta Excel (.xlsx)** e **CSV**: in più sesso, livello, obiettivi, gara o sport, data gara, numero e scadenza del documento.
I dati vengono dall’anamnesi («Contatti e dati personali»): i campi vuoti escono vuoti. È un file con dati personali: conservalo e invialo con cura.

## Stato degli atleti
Calcolato dalla scheda più recente di ogni atleta (data di cambio scheda, o 6 settimane dall'inizio se manca):
- **Attivi**: cambio scheda non ancora raggiunto.
- **In scadenza**: cambio scheda, fine dello stop medico per infortunio o scadenza del certificato medico entro **10 giorni** o già superati. In home il riquadro «⚠ Scadenze entro 10 giorni» le elenca dalla più vicina (un clic sul nome apre l’atleta); ogni atleta ha l’etichetta precisa («Scheda tra 9 gg», «Stop infortunio tra 5 gg», «Certificato scaduto»…) e il dettaglio atleta mostra tutte le date.
- **Verifica infortunio**: la data «fermo fino al» è passata.
- **Check-in**: atleta attivo senza check-in da almeno 14 giorni.

## Pubblicazione su GitHub Pages
1. Carica `index.html` nella root del repository (il file, non lo zip).
2. Settings → Pages → Deploy from a branch → main → / (root).

## Accesso e cloud (Firebase)
- All’apertura il sito chiede **email e password** (l’utente creato in Firebase → Authentication). «Password dimenticata?» manda un’email per sceglierne una nuova.
- Clienti, anamnesi, test e schede sono salvati su **Firestore** (progetto `speaking-bb3af`, percorso `users/<tuo UID>/utenti`, `users/<tuo UID>/schede` e `users/<tuo UID>/gruppi`): entrando con la stessa email da PC e telefono vedi gli stessi dati. Tornando sull’app dopo almeno un minuto, gli elenchi si aggiornano con le modifiche fatte altrove.
- Resta una copia sul dispositivo (IndexedDB) per aprire l’app anche senza rete. Le modifiche fatte offline partono da sole quando torna la connessione; lo stato è nel menu **Backup** («Dati sincronizzati», «modifiche in attesa»).
- **Primo accesso su un dispositivo che ha già dei clienti**: compare il riquadro «… non sono ancora nel cloud» con **Carica nel cloud** (si fa una volta sola). Si può fare anche da Backup → «Carica nel cloud i dati di questo dispositivo». I clienti già presenti nel cloud non vengono sovrascritti.
- **Backup solo per il PT**: il menu Backup (e «Importa backup») compare solo dopo l’accesso con la tua email. L’atleta, con il link della scheda, non vede né menu né Backup. Se il cloud non è raggiungibile, «Continua con i dati salvati su questo dispositivo» compare solo su un dispositivo in cui hai già fatto l’accesso (o con il file aperto dal computer); su un telefono qualsiasi l’app resta chiusa.
- **Esci** (menu Backup): «Esci» tiene la copia sul dispositivo; «Esci e cancella da questo dispositivo» è per un computer o telefono non tuo.
- Se Firebase non è raggiungibile (niente internet, oppure sito aperto dal file sul computer) puoi continuare con i dati salvati sul dispositivo: le modifiche vengono inviate al cloud al prossimo accesso.
- Le **foto dei documenti** restano solo sul dispositivo in cui le hai caricate.
- Il link per l’atleta (`#s=…`) non chiede l’accesso e non legge il cloud.
- Regole di Firestore da tenere pubblicate:
```
rules_version = '2';
service cloud.firestore {
  match /databases/{database}/documents {
    match /users/{uid}/{document=**} {
      allow read, write: if request.auth != null && request.auth.uid == uid;
    }
  }
}
```
- Domini autorizzati (Authentication → Settings): `saradeny3-collab.github.io`.

## Dati
- **Backup → Esporta backup (JSON)** e **Importa backup (JSON)** (Unisci o Sostituisci) restano come copia di sicurezza; con l’accesso fatto, un backup importato va anche nel cloud.
- Piano gratuito Firebase (Spark): 1 GiB di dati, 20.000 scritture e 50.000 letture al giorno, più che sufficienti per un Personal Trainer.
- Il sito parte vuoto, senza dati di esempio.
- Sono dati personali e sanitari: tieni conto del GDPR, usa una password robusta e proteggi i file di backup.
