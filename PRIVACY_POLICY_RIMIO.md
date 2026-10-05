# Privacy Policy di RIMIO

**Ultimo aggiornamento: 5 ottobre 2026**

La presente informativa descrive come RIMIO tratta dati e permessi nell'ambito delle funzionalità disponibili nell'app iOS. RIMIO è progettata secondo un approccio **local-first**: i documenti e la maggior parte dei dati inseriti dall'utente restano sul dispositivo e non vengono trasmessi automaticamente allo sviluppatore.

## 1. Titolare e contatti

RIMIO è fornita da:

**Claudio Frontini**  
Contatto privacy: **frontiniclaudio@gmail.com**  
Privacy Policy: **https://claudiofrontini.github.io/rimio-privacy/**

Non è stato nominato un Responsabile della Protezione dei Dati (DPO), salvo che ciò diventi necessario in base alla normativa applicabile o all'evoluzione del servizio.

## 2. Principi generali

RIMIO è progettata per aiutare l'utente a organizzare documenti, scadenze, promemoria, appuntamenti, ricette, liste, tessere, informazioni relative a veicoli e altre attività della vita quotidiana.

Nella versione descritta da questa informativa:

- non è richiesto un account RIMIO;
- non sono presenti SDK pubblicitari o di profilazione;
- non sono utilizzati tracker pubblicitari;
- non sono utilizzati SDK analytics di terze parti per analizzare il comportamento dell'utente;
- i documenti personali non vengono caricati automaticamente su server dello sviluppatore;
- la persistenza principale dell'Archivio è locale e non utilizza CloudKit.

RIMIO applica criteri di minimizzazione dei dati e prova a non conservare campi personali non necessari alla funzione richiesta.

## 3. Dati trattati nell'app

A seconda delle funzioni utilizzate, RIMIO può elaborare sul dispositivo informazioni contenute in:

- bollette e documenti relativi a utenze;
- contratti e abbonamenti;
- documenti assicurativi e relativi a veicoli;
- avvisi di pagamento, rate e altri documenti finanziari;
- documenti sanitari, referti e risultati di laboratorio;
- documenti personali o amministrativi;
- fatture, ricevute, garanzie e documenti relativi ad acquisti;
- ricette, liste della spesa, promemoria e appuntamenti;
- tessere fedeltà e relativi codici;
- fotografie, PDF, testo riconosciuto tramite OCR e campi strutturati estratti dal documento.

Questi contenuti sono utilizzati per fornire la funzione scelta dall'utente, ad esempio classificazione, archiviazione, ricerca, confronto, scadenze, promemoria o spiegazioni in linguaggio semplice.

Lo sviluppatore **non riceve automaticamente** i contenuti archiviati nell'app.

La ricerca globale viene costruita localmente e non indicizza il testo OCR completo né gli identificativi sensibili esclusi dalle policy dell'app. Per le Tessere fedeltà, numero socio e valore barcode restano nel dettaglio locale ma non vengono usati come chiavi della ricerca globale; per i Contatti la ricerca globale usa nome e categoria ma non telefono, email, indirizzo o note.

## 4. Basi giuridiche

Per i trattamenti che, in base alle circostanze, sono soggetti al Regolamento (UE) 2016/679 e riconducibili al titolare, le basi giuridiche possono comprendere:

- l'esecuzione delle funzionalità richieste dall'utente o di misure adottate su richiesta dell'utente, ai sensi dell'art. 6, par. 1, lett. b) GDPR;
- il consenso, ai sensi dell'art. 6, par. 1, lett. a) GDPR, quando una specifica funzione facoltativa richiede tale base giuridica;
- l'adempimento di eventuali obblighi di legge, ai sensi dell'art. 6, par. 1, lett. c) GDPR, ove applicabile.

Le autorizzazioni di iOS a Fotocamera, Foto, Microfono, Riconoscimento vocale, Posizione, Calendario e Notifiche sono **permessi tecnici del sistema operativo** e non coincidono automaticamente con il consenso ai sensi del GDPR.

## 5. Dati sanitari

Referti, risultati di laboratorio e altri documenti sanitari possono contenere categorie particolari di dati personali ai sensi dell'art. 9 GDPR.

RIMIO li elabora localmente soltanto quando l'utente sceglie di acquisire, importare o utilizzare tali documenti. Il contenuto sanitario non viene trasmesso automaticamente allo sviluppatore.

Le funzioni di spiegazione, glossario e lettura descrittiva hanno finalità esclusivamente informative ed educative. La lettura descrittiva organizza valori, unità, flag e intervalli già presenti nel referto e non formula diagnosi, possibili cause, prognosi, prescrizioni, indicazioni terapeutiche o suggerimenti di ulteriori esami. Le spiegazioni generate vengono ulteriormente minimizzate per evitare di replicare nomi di professionisti, recapiti, codici fiscali o altri dati amministrativi non necessari. Non deve essere utilizzata per prendere decisioni cliniche senza un professionista sanitario.

Qualora in futuro venissero introdotti trattamenti remoti di dati sanitari o altre funzionalità che richiedano una specifica condizione ai sensi dell'art. 9 GDPR, la presente informativa verrà aggiornata prima dell'attivazione di tali trattamenti e verrà acquisita l'eventuale manifestazione esplicita richiesta dalla normativa.

## 6. Fotocamera e libreria Foto

Con autorizzazione dell'utente, RIMIO può usare Fotocamera e libreria Foto per acquisire o importare documenti, ricette, tessere e altri contenuti previsti dalle funzioni dell'app.

L'accesso viene richiesto per la funzione selezionata dall'utente. Le immagini importate vengono trattate localmente e conservate secondo le preferenze di conservazione scelte nell'app. Per ridurre i picchi di memoria, le immagini selezionate dalla libreria Foto vengono acquisite tramite rappresentazione file quando disponibile, sottoposte a limiti di dimensione e risoluzione e ridimensionate localmente prima dell'uso nelle funzioni dell'app. Anche le immagini scelte dall'app File vengono validate per dimensione e risoluzione e downsamplate con ImageIO prima della decodifica completa. Le copie temporanee create per l'importazione vengono rimosse al termine dell'operazione o in caso di annullamento. Se l'app viene terminata prima del cleanup, al successivo avvio RIMIO elimina le sole copie temporanee riconoscibili come proprie (`rimio-photo-*`), senza ispezionare timestamp del filesystem e senza toccare altri file temporanei.

## 7. Microfono e riconoscimento vocale

Quando l'utente avvia una funzione vocale, RIMIO può richiedere accesso al Microfono e al Riconoscimento vocale.

RIMIO utilizza le tecnologie Speech di Apple e richiede il riconoscimento sul dispositivo quando supportato. Se il riconoscimento on-device non è disponibile, l'audio può essere elaborato tramite i servizi Apple secondo le condizioni e le informative applicabili di Apple.

L'ascolto viene avviato dall'utente. RIMIO non utilizza il microfono per ascolto pubblicitario o profilazione. La trascrizione vocale viene mantenuta temporaneamente in memoria per mostrare il feedback e completare la finalizzazione di Speech; uscendo dalla funzione viene rimossa. Il testo viene conservato nei dati locali dell'app soltanto quando l'utente lo applica a un campo o quando un comando esplicito salva il relativo contenuto.

## 8. Calendario

Se l'utente sceglie di sincronizzare un appuntamento, RIMIO può richiedere accesso al Calendario Apple per creare, ritrovare, aggiornare o eliminare gli eventi associati agli appuntamenti gestiti dall'app.

RIMIO non utilizza il contenuto del calendario per pubblicità o profilazione.

Quando l'utente elimina dati o appuntamenti collegati, l'app prova a rimuovere anche gli eventi di Calendario creati e associati da RIMIO, ove tecnicamente possibile.

## 9. Posizione

RIMIO può utilizzare la posizione per funzioni avviate dall'utente, ad esempio:

- salvataggio della posizione di parcheggio;
- ricerca di negozi o luoghi pertinenti nelle vicinanze;
- promemoria di prossimità collegati alla lista della spesa.

Il salvataggio del parcheggio non richiede un tracciamento continuo.

Se l'utente associa una foto al parcheggio, RIMIO la ridimensiona e comprime localmente prima della persistenza per ridurre lo spazio occupato e la quantità di immagine conservata.

Quando l'utente attiva volontariamente un promemoria di prossimità per un negozio, RIMIO registra un trigger geografico locale gestito da iOS. Per questa funzione è sufficiente l'autorizzazione alla posizione **Mentre usi l’app**; dopo la registrazione del trigger, il sistema operativo può consegnare l'avviso quando il dispositivo entra nella zona anche se RIMIO non è aperta. RIMIO non avvia un tracciamento GPS continuo in background per questa funzione.

La posizione non viene utilizzata da RIMIO per pubblicità o profilazione.

## 10. Notifiche

Se l'utente abilita promemoria, appuntamenti, rate o scadenze, RIMIO può programmare notifiche locali sul dispositivo.

Per impostazione predefinita, RIMIO utilizza contenuti generici nelle notifiche per ridurre l'esposizione di titoli, note, importi o altre informazioni personali sulla schermata di blocco. L'utente può scegliere volontariamente di mostrare contenuti più dettagliati dalla sezione **Privacy e sicurezza**.

Il metadata persistente delle notifiche RIMIO conserva soltanto il tipo della notifica e un identificativo tecnico. Quando l'utente apre una notifica, gli eventuali dettagli vengono ricostruiti dal database locale soltanto dopo che l'app è attiva e, se abilitato, dopo lo sblocco tramite il sistema di protezione dell'app. Le versioni precedenti che potevano contenere dettagli duplicati nel payload vengono sanificate all'apertura dell'app.

Le notifiche possono essere disattivate dalle impostazioni dell'app o dalle Impostazioni di iPhone.

## 11. Autenticazione biometrica e codice dispositivo

L'utente può attivare la protezione dell'accesso a RIMIO tramite il sistema di autenticazione del dispositivo.

Face ID, Touch ID e il codice di sblocco sono gestiti da iOS. RIMIO riceve soltanto l'esito dell'autenticazione e **non riceve né conserva i dati biometrici o il codice del dispositivo**.

## 12. Accesso a Internet e servizi esterni

Alcune funzioni avviate dall'utente richiedono una connessione Internet. In particolare, RIMIO può:

- scaricare il catalogo pubblico Open Data del Portale Offerte ARERA / Acquirente Unico per il confronto luce e gas;
- aprire il comparatore ufficiale AGCOM per offerte Internet e telefonia;
- aprire Preventivass IVASS per il confronto RC Auto;
- aprire siti ufficiali di operatori di telepedaggio, streaming o altri servizi confrontabili;
- usare i servizi Apple per ricerche di luoghi e mappe;
- importare una ricetta o un manuale da un URL scelto dall'utente;
- aprire pagine web o ricerche avviate dall'utente.

Per le ricette importate dal web, RIMIO usa la pagina indicata per estrarre localmente gli elementi utili della ricetta. Nell'Archivio vengono conservati il contenuto strutturato necessario alla funzione (ad esempio titolo, ingredienti, preparazione e fonte) e non l'intero testo della pagina web. Quando una fonte URL viene salvata per ricette o procedure da manuale, RIMIO rimuove credenziali, parametri di query e fragment non necessari, così eventuali token o parametri temporanei non vengono mantenuti nel dato locale.

Quando l'utente sceglie di cercare un manuale tramite Google, RIMIO mostra prima la query esatta che verrà inviata e richiede una conferma esplicita. Alla ricerca non vengono allegati automaticamente documenti, testo OCR o altri record dell'Archivio.

Nel confronto luce e gas, RIMIO scarica il **catalogo pubblico** delle offerte. Le bollette, i consumi, i costi e il profilo ricavati dall'Archivio restano sul dispositivo e non vengono caricati automaticamente sul Portale Offerte o inviati ai fornitori.

Per AGCOM, Preventivass e gli altri siti esterni RIMIO non trasferisce automaticamente i dati personali estratti dai documenti. Se l'utente decide di inserire informazioni direttamente su un sito esterno, tali dati vengono trattati dal relativo servizio secondo le proprie condizioni e informative privacy.

L'accesso a un sito esterno comporta normalmente la trasmissione di dati tecnici di connessione, come l'indirizzo IP, al gestore di quel sito. RIMIO non controlla i trattamenti effettuati autonomamente da tali soggetti.

I dati economici provenienti da cataloghi o siti esterni possono cambiare nel tempo. RIMIO li utilizza a fini informativi e di confronto e invita l'utente a verificare le condizioni aggiornate presso la fonte ufficiale prima di assumere decisioni contrattuali.

## 13. Nota sui confronti economici

Le stime mostrate da RIMIO non rappresentano necessariamente il prezzo finale che verrà applicato dal fornitore.

Per luce e gas i valori utilizzati nel confronto derivano dai dati base o confrontabili disponibili nel catalogo pubblico. Possono non riflettere integralmente l'eventuale spread, l'indice di mercato aggiornato, sconti, bonus, promozioni, imposte, costi di rete o altre condizioni specifiche del singolo fornitore. Nelle offerte indicizzate RIMIO può mostrare la componente o lo spread quando disponibile nel tracciato, ma la stima può restare parziale.

Prima di aderire a un'offerta, l'utente deve verificare prezzo finale, condizioni economiche, durata, vincoli, costi accessori e documentazione contrattuale sul sito o nei documenti ufficiali del fornitore.

Questa sezione ha finalità informativa sul funzionamento del comparatore e non modifica le regole sul trattamento dei dati personali descritte nella presente Privacy Policy.

## 14. Apple Intelligence e modelli locali

Alcune funzioni possono utilizzare framework Apple e modelli disponibili sul dispositivo, inclusi i Foundation Models quando supportati.

RIMIO non invia automaticamente il contenuto dei documenti personali a servizi di intelligenza artificiale di terze parti. Quando una funzione genera o riscrive contenuti con Foundation Models, RIMIO indica nel risultato che si tratta di un'elaborazione AI locale con modello Apple sul dispositivo. Quando il modello Apple non è disponibile, RIMIO utilizza, ove previsto, logiche locali alternative e le identifica come elaborazioni basate su regole, oppure la funzione non viene eseguita.

## 15. Protezione e conservazione locale

Il database principale dell'Archivio viene conservato nell'area Application Support dell'app, è configurato senza CloudKit, utilizza le protezioni di Data Protection disponibili su iOS ed è escluso dal backup secondo la configurazione dell'app.

RIMIO applica inoltre misure di protezione dell'interfaccia quando l'app passa in background, per ridurre la visualizzazione di contenuti personali nello snapshot dell'app switcher.

L'utente può scegliere se conservare le immagini originali dei **nuovi** documenti importati. Se l'opzione di conservazione delle immagini originali viene disattivata, RIMIO mantiene i dati strutturati e il testo OCR necessari a ricerca, confronto e ri-analisi, ma non conserva le relative immagini o pagine originali dei nuovi import secondo la funzione disponibile nell'app.

## 16. Conservazione e cancellazione

I dati locali restano disponibili fino a quando l'utente li elimina, utilizza la funzione di cancellazione complessiva dell'app o rimuove l'app dal dispositivo, salvo eventuali elementi gestiti da servizi di sistema o servizi esterni.

L'utente può:

- modificare o eliminare singoli elementi;
- disattivare promemoria e notifiche;
- rimuovere promemoria di prossimità;
- cancellare i dati locali gestiti da RIMIO tramite la sezione **Privacy e sicurezza**;
- scegliere, per i nuovi documenti, di non conservare le immagini originali.

La cancellazione complessiva dei dati locali RIMIO non dipende dall'autorizzazione al Calendario. L'app prova inoltre a rimuovere gli eventi di Calendario associati; se il permesso è stato revocato o EventKit non consente la rimozione, i dati locali vengono comunque eliminati e RIMIO segnala che eventuali eventi Apple Calendar possono richiedere una cancellazione manuale.

La cancellazione complessiva rimuove anche eventuali archivi locali legacy (`default.store` e relativi file di supporto) rimasti da versioni precedenti o da un upgrade interrotto, lo stato tecnico per-ID, le notifiche gestite da RIMIO e l'eventuale marker locale protetto creato per completare un ripristino interrotto. Eventuali dati di import/anteprima ancora presenti soltanto in memoria vengono scartati. Le preferenze dell'utente relative a protezione dell'app, protezione durante la cattura schermo, visibilità dei dettagli nelle notifiche e conservazione delle immagini originali restano invece invariate e possono essere modificate separatamente nella sezione **Privacy e sicurezza**.

## 16-bis. Messaggi preparati e condivisione volontaria

RIMIO può preparare testi che l'utente può modificare, copiare o condividere. La generazione usa dati strutturati già minimizzati e non inserisce automaticamente il testo OCR completo del documento. Identificativi e recapiti sensibili vengono mascherati secondo le regole di privacy dell'app.

RIMIO non invia automaticamente questi messaggi: copia e condivisione avvengono soltanto dopo un'azione esplicita dell'utente. Per i riepiloghi dei Dossier viene mostrata un'anteprima modificabile prima di aprire la share sheet di iOS.

La copia negli appunti è limitata al dispositivo e configurata con scadenza temporale. Quando RIMIO perde il primo piano, la durata residua del contenuto copiato dall'app viene ridotta; RIMIO interviene solo se la clipboard contiene ancora il valore copiato dall'app e non cancella un contenuto che l'utente o un'altra app abbia sostituito successivamente.


## 16-ter. Protezione schermo, clipboard e diagnostica

Quando RIMIO passa in stato inattivo o in background, l’interfaccia viene coperta da uno **privacy shield** per ridurre l’esposizione dei contenuti nell’app switcher. Per impostazione predefinita RIMIO oscura inoltre l’intera interfaccia quando iOS segnala che la scena è oggetto di **registrazione schermo, mirroring, screen sharing o remote control**. Questa protezione può essere disattivata volontariamente da **Privacy e sicurezza** e resta una preferenza locale del dispositivo corrente.

RIMIO non può impedire preventivamente un singolo screenshot: iOS comunica all’app l’avvenuta acquisizione solo dopo che lo screenshot è stato creato. Una copia salvata dall’utente nell’app Foto o condivisa tramite funzioni di sistema è quindi esterna all’archivio protetto di RIMIO e segue le impostazioni e le informative dei servizi scelti dall’utente.

La baseline di release non scrive nei log applicativi contenuti OCR, campi dei documenti, nomi, recapiti, indirizzi, importi, dati sanitari, coordinate o altri dati dell’archivio. Eventuali strumenti diagnostici della build Debug operano sui dati locali e non vengono inclusi nella build Release come schermate operative.

## 17. Dati inviati volontariamente allo sviluppatore

Se l'utente contatta lo sviluppatore tramite email, possono essere trattati l'indirizzo email, il contenuto del messaggio e gli eventuali allegati inviati volontariamente.

Tali dati vengono utilizzati per rispondere alla richiesta, gestire assistenza o richieste privacy e, ove necessario, adempiere a obblighi legali o tutelare diritti. L'utente è invitato a non inviare documenti sanitari, bancari o altri contenuti sensibili se non strettamente necessario.

## 18. Permessi di sistema e revoca

Fotocamera, Foto, Microfono, Riconoscimento vocale, Notifiche, Calendario e Posizione vengono utilizzati soltanto nelle funzioni che ne hanno bisogno e secondo le autorizzazioni concesse dall'utente. RIMIO non richiede questi permessi in blocco all'avvio: la richiesta avviene quando l'utente attiva volontariamente la relativa funzione.

In particolare, l'accesso completo al Calendario viene utilizzato per creare, ritrovare, aggiornare ed eliminare gli appuntamenti RIMIO sincronizzati; la Posizione mentre usi l'app viene utilizzata per parcheggio, ricerca di luoghi/negozi e attivazione dei promemoria di prossimità scelti dall'utente. Fotocamera e Foto vengono utilizzate soltanto per i contenuti che l'utente decide di acquisire o selezionare.

I permessi possono essere modificati o revocati dalle Impostazioni di iPhone. Dopo la revoca, alcune funzioni potrebbero non essere disponibili.

La sezione **Privacy e sicurezza** di RIMIO mostra lo stato dei principali permessi e consente di raggiungere le Impostazioni di sistema quando necessario.

## 19. Destinatari e trasferimenti

RIMIO non condivide automaticamente con terze parti i documenti archiviati, i dati OCR o i campi strutturati dell'utente.

I servizi Apple e i siti esterni aperti dall'utente trattano autonomamente eventuali dati tecnici o informazioni che l'utente decide di fornire loro, secondo le rispettive informative.

RIMIO non effettua autonomamente trasferimenti del contenuto dell'Archivio verso Paesi terzi. Eventuali trasferimenti effettuati dai fornitori esterni utilizzati o visitati dall'utente sono disciplinati dalle condizioni e dalle misure adottate da tali fornitori.

## 20. Minori

RIMIO **non è destinata a persone di età inferiore a 18 anni**.

Le funzionalità dell'app possono riguardare documenti personali, dati sanitari, contratti, pagamenti, assicurazioni e altre informazioni pensate per la gestione della vita quotidiana di un utente adulto.

Lo sviluppatore non raccoglie intenzionalmente tramite propri server dati personali di minori nell'ambito delle funzionalità descritte dalla presente informativa.

## 21. Diritti dell'interessato

Nei casi in cui il Regolamento (UE) 2016/679 sia applicabile, l'interessato può esercitare i diritti previsti dalla normativa, inclusi, ove applicabili:

- accesso ai dati personali;
- rettifica;
- cancellazione;
- limitazione del trattamento;
- opposizione;
- portabilità dei dati;
- revoca di un eventuale consenso, senza pregiudicare la liceità del trattamento effettuato prima della revoca.

Poiché i contenuti archiviati da RIMIO sono principalmente conservati sul dispositivo e non sono accessibili automaticamente allo sviluppatore, molte operazioni di consultazione, modifica e cancellazione possono essere effettuate direttamente nell'app.

Da **Privacy e sicurezza → Esporta i miei dati** l'utente può inoltre generare volontariamente una copia strutturata in formato JSON dei dati locali gestiti da RIMIO. L'esportazione viene preparata sul dispositivo e non viene caricata automaticamente su server RIMIO. Può includere dati personali, sanitari, finanziari, contatti, posizione e le immagini che l'utente ha scelto di conservare. Gli identificativi tecnici legati a notifiche e Calendario e lo stato locale delle preferenze di sicurezza/privacy (App Lock, dettaglio notifiche e conservazione immagini) non vengono inclusi come dati portabili; il campo legacy richiesto dagli schemi precedenti viene esportato con valori neutralizzati. RIMIO non applica una cifratura propria al file esportato: la protezione della copia dopo il salvataggio dipende quindi dalla destinazione scelta dall'utente. Prima della codifica completa RIMIO applica inoltre un preflight locale al contenuto binario (immagini/allegati) e può rifiutare un archivio eccezionalmente grande se non può essere preparato con un margine di memoria e spazio considerato sicuro; il rifiuto non modifica i dati già salvati. Dopo la codifica, il passaggio al selettore File utilizza una copia temporanea `rimio-export-*` protetta con Data Protection completa ed esclusa dai backup; RIMIO la elimina al termine del selettore e, se il processo viene interrotto prima del cleanup, al successivo cold start. Il cleanup riconosce esclusivamente i file temporanei export creati da RIMIO.

Da **Privacy e sicurezza → Ripristina da file RIMIO** l'utente può selezionare una precedente esportazione RIMIO. Prima di qualsiasi modifica locale l'app verifica formato, versione dello schema, struttura, identificativi, dimensione del file e limiti di sicurezza del contenuto e mostra un'anteprima. Il file selezionato viene prima copiato in uno snapshot temporaneo locale `rimio-import-*`, protetto con Data Protection completa ed escluso dai backup. La lettura è limitata e usa una mappatura del file durante preview e restore, così l'intero JSON non resta conservato nello stato dell'interfaccia mentre l'utente decide come procedere. Lo snapshot viene eliminato dopo successo, annullamento o errore e, se il processo viene interrotto prima del cleanup, al successivo cold start; il cleanup riconosce esclusivamente i file temporanei restore creati da RIMIO. L'utente può scegliere di **Unire** i record, lasciando invariati quelli che hanno già lo stesso identificativo locale, oppure di **Sostituire** i dati RIMIO presenti sul dispositivo. I riferimenti interni tra documenti e dossier vengono verificati rispetto alla modalità scelta: in Unisci possono puntare anche a elementi già esistenti sul dispositivo; in Sostituisci devono puntare a elementi inclusi nel file. I riferimenti che non hanno una destinazione valida vengono rimossi in modo controllato e l'utente viene informato, evitando UUID orfani nello store ripristinato. Il salvataggio SwiftData viene eseguito come operazione controllata e, se il commit non riesce, le modifiche della transazione vengono annullate e il rollback viene verificato sugli identificativi locali. Dopo un commit riuscito RIMIO usa un marker temporaneo locale, protetto con Data Protection completa ed escluso dai backup, per poter completare in modo idempotente la ricostruzione di promemoria e altri effetti locali se l'app viene interrotta in quel momento. In modalità Sostituisci il marker distingue la pulizia locale già completata dall'eventuale rimozione di vecchi eventi Apple Calendar ancora pendente: se l'accesso Calendar non è temporaneamente disponibile, il marker viene conservato e la sola operazione esterna residua può essere ritentata senza ripetere gli effetti locali già conclusi. Il marker viene eliminato soltanto quando non restano operazioni recuperabili pendenti. Le preferenze di protezione e privacy del dispositivo corrente, incluse App Lock, dettaglio delle notifiche e conservazione delle immagini, non vengono sovrascritte dal file importato. Gli appuntamenti vengono ripristinati nell'app ma non vengono ricreati automaticamente nel Calendario Apple, per evitare duplicazioni di eventi esterni. In caso di sostituzione, RIMIO tenta inoltre di rimuovere gli eventi Calendario precedentemente collegati, se dispone dell'autorizzazione necessaria.

Per le operazioni che scrivono nuovi dati sul dispositivo, RIMIO verifica inoltre di poter mantenere un margine locale di sicurezza. Se lo spazio è insufficiente, l'app può rimuovere esclusivamente cache ricreabili proprie e, se ciò non basta, interrompe il nuovo salvataggio prima del commit oppure gestisce l'errore di sistema con rollback. Questa gestione non comporta la cancellazione automatica di documenti, immagini o altri dati personali già archiviati. Export, restore e download temporanei possono essere rifiutati finché l'utente non libera spazio sufficiente.

Per richieste ulteriori è possibile utilizzare il contatto privacy indicato nella presente informativa.

Resta fermo il diritto di proporre reclamo al **Garante per la protezione dei dati personali** o all'autorità di controllo competente.

## 22. Hosting della presente informativa

Questa Privacy Policy è pubblicata tramite GitHub Pages. La visita alla pagina può comportare il trattamento da parte di GitHub di dati tecnici di connessione secondo le proprie condizioni e informative privacy.

L'hosting della Privacy Policy è distinto dal funzionamento locale dell'Archivio RIMIO e non comporta l'invio a GitHub dei documenti conservati nell'app.

## 23. Modifiche alla Privacy Policy

La presente informativa può essere aggiornata quando cambiano le funzionalità dell'app, i servizi utilizzati, la struttura tecnica o gli obblighi applicabili.

La versione pubblicata indica la data dell'ultimo aggiornamento. In caso di modifiche sostanziali che richiedano una nuova informazione o una nuova scelta dell'utente, RIMIO adotterà le misure appropriate prima di applicare il nuovo trattamento.

## 24. Contatti

Per richieste relative alla privacy, al trattamento dei dati o all'esercizio dei diritti applicabili:

**Claudio Frontini**  
**frontiniclaudio@gmail.com**


### Affidabilità del ripristino dei promemoria di prossimità
Durante un ripristino, gli eventuali promemoria locali basati sulla posizione vengono riconciliati sul dispositivo prima che il recovery sia considerato completato. La procedura non invia dati di posizione a server RIMIO e mantiene il comportamento locale già previsto dall’app.
