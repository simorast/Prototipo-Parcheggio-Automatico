Prototipo di Sistema di Parcheggio Automatico

Un prototipo fisico e funzionante per un sistema di gestione accessi automatizzato, rilevante per la logistica e l'automazione di processo.

Demo del Progetto

[Guarda il video del prototipo in funzione] (https://www.linkedin.com/posts/simone-rastelli-25b406288_volevo-condividere-il-mio-ultimo-progetto-activity-7097490868437200896-OG5F?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD4n4noBukvyhqbUdpJa2GcWz6Des7ZLqPg)

Obiettivo del Progetto

L'obiettivo era simulare un sistema di parcheggio intelligente capace di: Contare i posti liberi e mostrare lo stato ("FULL" o posti disponibili) su un display LCD. Gestire automaticamente una sbarra di accesso tramite uno step motor. Rilevare l'ingresso e l'uscita dei veicoli tramite sensori a infrarossi.

Componenti Utilizzati

Microcontrollore: MSP430FR6989 (il "cervello" del sistema). Sensori: Sensori IR (Infrarossi) per rilevare la presenza dei veicoli. Attuatori: Step Motor e Driver dedicato per controllare la sbarra di accesso. Display: Schermo LCD integrato per comunicare lo stato del parcheggio all'utente.

Logica di Funzionamento

Il sistema opera su una logica di processo sequenziale:

Ingresso Auto: Un'auto viene rilevata dal sensore di ingresso (S5). Il sistema controlla se ci sono posti liberi. Se SÌ: Lo step motor alza la sbarra. L'auto passa, viene rilevata dal sensore interno (S6) e la sbarra si abbassa. I posti liberi vengono aggiornati sull'LCD. Se NO (FULL): L'accesso non è consentito e l'LCD mostra "FULL".

Uscita Auto: Un'auto viene rilevata dal sensore interno (S6). Lo step motor alza la sbarra. L'auto passa, viene rilevata dal sensore di uscita (S5) e la sbarra si abbassa. I posti liberi vengono aggiornati.

Documentazione Tecnica
(Nota: Questo progetto è stato sviluppato come prototipo fisico. La logica è stata implementata in C per CCS, ma il codice sorgente non è più disponibile. La documentazione e il video demo illustrano l'intero funzionamento del sistema.)

Per tutti i dettagli sui componenti, gli schemi e la logica, è disponibile la documentazione completa del progetto.

Consulta la tesina completa (PDF)

(Nota: Questo progetto è stato sviluppato come prototipo fisico. La logica è stata implementata in C per CCS, ma il codice sorgente non è più disponibile. La documentazione e il video demo illustrano l'intero funzionamento del sistema.)
