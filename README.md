Documentazione progetto PHP 

Backend:

Deve ricevere dati da un server
Questi dati devono influenzare una dashboard
Ricompensa gli utenti con punti che si possono spendere su premi, ad esempio un biglietto al cinema

GitHub:
Link: https://github.com/dliuzzi/raccoltaDifferenziata
Descrivere progetto nel file Readme sul gruppo Git


Documentazione:
Tracciare la raccolta dei rifiuti
Tracciare i premi ecologici
Descrivere cosa permette di fare il modulo
Sistema utenti

front-end
1.creazione di una pagina login
2.creazione su una pagina “about us”

1. Definire lo scopo del modulo
- Descrivete cosa permette di fare il modulo.
- Indicate chi lo utilizza (utente registrato, amministratore, ecc.).
- Spiegate l’obiettivo ambientale e funzionale (es. tracciamento, premialità, statistiche).
2. Progettare la struttura dei dati
- Elencate le entità coinvolte (es. Raccolta, TipoRifiuto, Utente).
- Indicate i campi principali per ciascuna entità.
- Specificate le relazioni Eloquent tra le entità (es. User hasMany Raccolte).
3. Definire i flussi utente
- Descrivete passo passo come l’utente interagisce con il modulo.
- Indicate le schermate previste (form, tabella, conferma, riepilogo).
- Usate uno schema a blocchi o un diagramma se possibile.
4. Documentare la progettazione
- Create un file o documento con
   • Descrizione del modulo
   • Entità e relazioni
   • Flussi utente

Gestione ruoli:
-Servizi:
Ritiro rifiuti su commissione
Pulizie occasionali di spiagge
Gestione della raccolta rifiuti a premi (Ogni 10 bottiglie 1 euro di buono)
Monitoraggio delle statistiche della raccolta rifiuti


1. Descrizione dello scopo del modulo
Il progetto è articolato in tre componenti principali, ciascuna delle quali contribuisce alla realizzazione di una piattaforma web interattiva:

Sito Web (Front-End): composto da tre pagine principali — una Home con dashboard, una pagina di Login e una sezione “About Us”.

Back-End: infrastruttura logica responsabile della gestione dell'autenticazione degli utenti e della connessione al database.

Database: archivio centralizzato che contiene le informazioni relative agli utenti (cittadini) e ai servizi offerti dalle aziende di smaltimento.




L’obiettivo complessivo del progetto è lo sviluppo di un sito web che consenta all’utente/cittadino di effettuare il login e accedere, attraverso la dashboard della homepage, a una panoramica dettagliata dei punti ottenuti per la raccolta differenziata svolta. Tali punti, generati e aggiornati dinamicamente tramite il database, potranno essere utilizzati per riscattare premi e bonus di vario tipo, contribuendo così a incentivare comportamenti virtuosi in ambito ambientale.
