# Google-Cloud-Platform
## Compute Engine
Compute Engine è un servizio di calcolo su cloud offerto da Google Cloud Platform (GCP). Consente di creare e gestire macchine virtuali (VM) in un ambiente altamente scalabile e affidabile. 

Con Compute Engine, puoi creare istanze di VM con una configurazione personalizzata, inclusa la scelta del sistema operativo, la quantità di memoria, il numero di CPU e la capacità di archiviazione. Puoi anche selezionare la posizione geografica delle tue istanze VM per ottimizzare le prestazioni o rispettare i requisiti di conformità.

Compute Engine offre una vasta gamma di opzioni di prezzi e piani tariffari flessibili, consentendo di scegliere tra istanze a pagamento in base al tempo di utilizzo (on-demand) o riservate, che offrono sconti significativi per impegni a lungo termine. Puoi scalare facilmente le tue istanze VM verso l'alto o verso il basso in base alle tue esigenze di carico di lavoro, consentendo di adattare le risorse computazionali al traffico e alle richieste dell'applicazione.

Inoltre, Compute Engine supporta la gestione di istanze VM in cluster o gruppi di istanze per migliorare la resilienza e l'affidabilità del tuo sistema. Puoi anche integrare Compute Engine con altri servizi di Google Cloud, come lo storage di dati persistente, il bilanciamento del carico e le reti virtuali, per creare soluzioni complesse e distribuite.

Compute Engine di GCP fornisce un ambiente flessibile e scalabile per eseguire le tue applicazioni e i tuoi carichi di lavoro in cloud, offrendo una vasta gamma di opzioni di configurazione e prezzi.

### Prezzi Compute Engine
I prezzi delle macchine virtuali (VM) in Google Cloud Platform (GCP) possono variare in base alla regione selezionata. Diverse regioni possono avere prezzi leggermente diversi per le stesse specifiche di VM a causa di fattori come la disponibilità delle risorse e i costi operativi regionali. Di seguito sono riportati alcuni esempi di prezzi delle VM in diverse regioni di GCP.

Nota: I seguenti prezzi sono solo indicativi e possono essere soggetti a modifiche. È sempre consigliabile verificare i prezzi aggiornati sulla pagina ufficiale di Google Cloud Platform o contattare direttamente il supporto di Google Cloud per ottenere informazioni precise sui prezzi.

1. Regione: us-central1 (Iowa, Stati Uniti)
   - VM di tipo n1-standard-1 (1 CPU, 3,75 GB di memoria): circa $0,0475 all'ora.
   - VM di tipo n1-standard-4 (4 CPU, 15 GB di memoria): circa $0,19 all'ora.

2. Regione: europe-west1 (Belgio)
   - VM di tipo n1-standard-1 (1 CPU, 3,75 GB di memoria): circa €0,0375 all'ora.
   - VM di tipo n1-standard-4 (4 CPU, 15 GB di memoria): circa €0,15 all'ora.

3. Regione: asia-southeast1 (Singapore)
   - VM di tipo n1-standard-1 (1 CPU, 3,75 GB di memoria): circa $0,054 all'ora.
   - VM di tipo n1-standard-4 (4 CPU, 15 GB di memoria): circa $0,216 all'ora.

Per ottenere i prezzi aggiornati e dettagliati delle VM in base alla regione specifica e alle specifiche desiderate, ti consiglio di consultare il sito ufficiale di Google Cloud Platform o utilizzare il calcolatore dei prezzi fornito da Google Cloud.

### Scontistiche di prezzi
Google Cloud Platform (GCP) offre diverse modalità scontistiche per le macchine virtuali (VM) al fine di fornire prezzi più convenienti per gli utenti che necessitano di risorse computazionali a lungo termine o che desiderano impegnarsi con un utilizzo prevedibile. Di seguito sono elencate le principali modalità scontistiche disponibili in GCP per le VM:

1. Prezzi on-demand: Questa è la modalità di prezzo di base per le VM in GCP. In questa modalità, paghi il prezzo standard per l'utilizzo delle VM in base al tempo effettivo di utilizzo. Non è richiesto alcun impegno a lungo termine o contratto.

2. Sconti per l'utilizzo continuativo (Committed Use Discounts - CUD): Questa modalità offre uno sconto significativo per gli utenti che si impegnano a utilizzare le VM per un periodo prolungato, generalmente da uno a tre anni. L'utente seleziona un impegno di utilizzo (in termini di vCPU e memoria) per il periodo scelto e paga un prezzo scontato in anticipo. Questo prezzo è inferiore rispetto al prezzo on-demand.

3. Sconti per l'utilizzo sostenuto (Sustained Use Discounts - SUD): Questa modalità offre sconti automatici in base all'utilizzo a lungo termine delle VM. Se utilizzi una VM per una percentuale significativa del mese, riceverai uno sconto graduale automatico sulla tariffa oraria per quella VM. Ad esempio, se utilizzi una VM per il 50% del mese, riceverai uno sconto del 10% sulla tariffa oraria per quella VM.

4. Sconti per istanze preemptible: Le istanze preemptible sono VM a basso costo che possono essere interrotte in qualsiasi momento da Google con un preavviso breve (generalmente entro 24 ore). Queste VM sono adatte per i carichi di lavoro non critici e temporanei. Le istanze preemptible offrono prezzi notevolmente scontati rispetto alle istanze on-demand standard, ma non sono garantite per l'uso continuativo.

È importante notare che le modalità scontistiche possono variare a seconda del tipo di VM, della regione e delle opzioni di configurazione selezionate. Inoltre, le modalità di sconto possono essere combinate per ottenere ulteriori vantaggi. Si consiglia di consultare la documentazione ufficiale di Google Cloud o contattare il supporto di Google Cloud per ottenere informazioni dettagliate sulle modalità scontistiche attuali e le relative condizioni.

## Cloud Run
Cloud Run è un servizio serverless di Google Cloud Platform (GCP) che consente di eseguire facilmente container stateless in un ambiente completamente gestito. Cloud Run consente di eseguire le tue applicazioni in modo scalabile senza preoccuparti della gestione dell'infrastruttura sottostante.

Con Cloud Run, puoi confezionare le tue applicazioni in container Docker, includendo tutte le dipendenze necessarie, e distribuirle su Cloud Run. Quando ricevi una richiesta, Cloud Run istanzia automaticamente un container per gestire quella richiesta in modo isolato. Se non ci sono richieste in arrivo, i container vengono scalati automaticamente a zero, risparmiando risorse e denaro.

Le principali caratteristiche di Cloud Run includono:

1. Serverless: Cloud Run gestisce automaticamente il provisioning delle risorse, il bilanciamento del carico e l'allocazione dei container, consentendoti di concentrarti sullo sviluppo dell'applicazione senza preoccuparti dell'infrastruttura.

2. Scalabilità automatica: Cloud Run scala automaticamente i container in base al volume delle richieste in arrivo. I container vengono avviati e arrestati dinamicamente in base alla necessità, garantendo che le tue applicazioni siano sempre disponibili e che tu paghi solo per l'utilizzo effettivo.

3. Piattaforma agnostica: Puoi eseguire container Docker su Cloud Run, il che ti consente di utilizzare qualsiasi linguaggio di programmazione o stack tecnologico che preferisci. Cloud Run supporta sia le immagini di container completamente gestite che le immagini di container che eseguono su un ambiente Kubernetes.

4. Connessione a eventi e servizi GCP: Cloud Run può essere facilmente integrato con altri servizi di Google Cloud Platform come Pub/Sub, Cloud Storage, BigQuery e molti altri. Puoi creare pipeline di elaborazione degli eventi o interagire con servizi GCP in modo semplice e scalabile.

5. Fatturazione precisa: Con Cloud Run, paghi solo per il tempo di esecuzione effettivo dei tuoi container e le risorse utilizzate. Non ci sono costi fissi o minimi, il che rende Cloud Run una soluzione economica per applicazioni con carichi di lavoro variabili.

Cloud Run di Google Cloud Platform è un servizio serverless che consente di eseguire facilmente container Docker in modo scalabile e senza preoccuparti dell'infrastruttura sottostante. È un'opzione conveniente per le applicazioni che richiedono flessibilità, scalabilità e un ambiente gestito.

### Cloud Run (job)
Cloud Run for Anthos, che consente di eseguire applicazioni containerizzate su Kubernetes come lavoro (job). Cloud Run for Anthos estende le funzionalità di Cloud Run in modo che le applicazioni possano essere eseguite su un ambiente Kubernetes, consentendo di gestire sia servizi continui che lavori ad hoc.

I lavori (jobs) sono tipicamente processi che vengono eseguiti solo una volta o in modo periodico, senza la necessità di scalare in risposta alle richieste in arrivo. Questi lavori possono essere pianificati o avviati manualmente per eseguire operazioni specifiche, come l'elaborazione di batch, l'importazione/esportazione di dati, la generazione di report, ecc. Cloud Run for Anthos offre la flessibilità di eseguire tali lavori su Kubernetes e sfrutta le funzionalità di scalabilità e gestione fornite da Kubernetes.

Cloud Run è principalmente un servizio per eseguire applicazioni come servizi continui in modo scalabile e serverless. Tuttavia, esiste anche una variante chiamata Cloud Run for Anthos che consente di eseguire applicazioni su Kubernetes come lavori (jobs) per esigenze specifiche.

## Google Kubernetes Engine
Google Kubernetes Engine (GKE) è un servizio di Google Cloud Platform (GCP) che consente di gestire e orchestrare i container su Kubernetes. Kubernetes è un sistema open-source per l'automazione della distribuzione, della scalabilità e della gestione delle applicazioni containerizzate.

Con GKE, puoi creare e gestire facilmente cluster di Kubernetes altamente disponibili ed efficienti senza dover preoccuparti dell'installazione, della configurazione e della manutenzione dell'infrastruttura sottostante. GKE si occupa dell'implementazione dei nodi del cluster, del bilanciamento del carico, del monitoraggio, dell'autoscaling e di altre funzionalità chiave di Kubernetes.

Le caratteristiche principali di Google Kubernetes Engine includono:

1. Scalabilità: GKE consente di scalare facilmente il tuo cluster di Kubernetes in base alle esigenze del tuo carico di lavoro. Puoi aumentare o ridurre il numero di nodi del cluster per soddisfare la domanda dei tuoi container.

2. Affidabilità: GKE garantisce l'alta disponibilità delle tue applicazioni containerizzate. I nodi del cluster sono distribuiti su più zone di disponibilità per garantire la ridondanza e la tolleranza ai guasti.

3. Gestione semplificata: GKE semplifica la gestione del tuo cluster di Kubernetes fornendo un'interfaccia intuitiva e strumenti di automazione. Puoi utilizzare la console di GCP, l'interfaccia della riga di comando (CLI) o le API per gestire il tuo cluster.

4. Integrazione con strumenti GCP: GKE si integra con altri servizi di Google Cloud Platform, come il bilanciamento del carico, il monitoraggio, il registro dei contenitori e lo storage persistente, per fornire una soluzione completa per le tue applicazioni containerizzate.

5. Sicurezza: GKE implementa funzionalità di sicurezza avanzate per proteggere le tue applicazioni containerizzate. Offre isolamento del livello di rete, autenticazione e autorizzazione basate su IAM di GCP e supporto per la crittografia dei dati in transito e a riposo.

GKE offre un'infrastruttura scalabile, affidabile e gestita per eseguire le tue applicazioni containerizzate su Kubernetes. È particolarmente indicato per carichi di lavoro che richiedono una gestione avanzata dei container, il bilanciamento del carico, la scalabilità orizzontale e altre funzionalità offerte da Kubernetes.

## Cloud Function
Google Cloud Functions è un servizio di elaborazione serverless offerto da Google Cloud Platform (GCP). Consente di scrivere e distribuire facilmente piccole porzioni di codice (funzioni) che vengono eseguite in risposta a eventi specifici senza dover preoccuparsi dell'infrastruttura sottostante.

Le funzioni di Cloud Functions sono scritte generalmente in JavaScript (Node.js), ma sono supportati anche altri linguaggi come Python, Go, Java e .NET. Ogni funzione è un'unità di codice indipendente che viene attivata da un evento specifico, come un caricamento di file su Cloud Storage, un messaggio inviato a una coda Pub/Sub o una richiesta HTTP.

Le caratteristiche principali di Google Cloud Functions includono:

1. Serverless: Cloud Functions gestisce automaticamente il provisioning delle risorse e l'esecuzione delle funzioni in base all'evento scatenante. Non è necessario preoccuparsi dell'infrastruttura sottostante o della gestione dei server.

2. Scalabilità automatica: Le funzioni di Cloud Functions vengono scalate in modo automatico e dinamico in risposta al volume degli eventi in arrivo. Le funzioni possono essere eseguite in parallelo per gestire il carico in modo efficace.

3. Event-driven: Le funzioni vengono attivate da eventi specifici, che possono provenire da una varietà di servizi di GCP come Cloud Storage, Pub/Sub, Firestore, Firestore in tempo reale, Cloud Scheduler, HTTP e molti altri. Quando si verifica un evento, la funzione associata viene eseguita.

4. Paga solo per l'utilizzo: Con Cloud Functions, paghi solo per il tempo di esecuzione effettivo delle tue funzioni e per le risorse utilizzate durante l'esecuzione. Non ci sono costi fissi o minimi, il che lo rende un'opzione economica per carichi di lavoro con picchi di traffico.

5. Integrazione con l'ecosistema GCP: Cloud Functions si integra facilmente con altri servizi di Google Cloud Platform. Puoi utilizzare funzioni di Cloud Functions per estendere e automatizzare le funzionalità di altri servizi, creare pipeline di dati, implementare logica di business personalizzata e molto altro.

Le funzioni di Cloud Functions sono progettate per scenari in cui è necessario eseguire piccoli pezzi di codice in risposta a eventi specifici senza la necessità di gestire l'infrastruttura sottostante. È particolarmente utile per l'elaborazione di eventi, l'automazione di compiti, l'integrazione di servizi e la creazione di microservizi.

## GCP SQL
Google Cloud SQL è un servizio di database relazionale completamente gestito offerto da Google Cloud Platform (GCP). Consente di creare, gestire e scalare facilmente database relazionali basati su MySQL, PostgreSQL e SQL Server nel cloud.

Le caratteristiche principali di Google Cloud SQL includono:

1. Gestione completamente gestita: Cloud SQL si occupa della gestione dell'infrastruttura sottostante, inclusa l'installazione, la configurazione, il backup, il ripristino e la manutenzione del database. Ciò consente di concentrarsi sullo sviluppo delle applicazioni senza dover preoccuparsi dell'amministrazione del database.

2. Scalabilità: Cloud SQL consente di scalare verticalmente (aumentando le risorse di calcolo e memoria) o orizzontalmente (aggiungendo istanze del database) in modo da adattarsi alle esigenze del tuo carico di lavoro.

3. Affidabilità e disponibilità elevata: Cloud SQL replica automaticamente i dati in più zone di disponibilità per garantire la ridondanza e la tolleranza ai guasti. In caso di guasti hardware o di zona, Cloud SQL commuta automaticamente su una replica per mantenere i database in esecuzione senza interruzioni.

4. Sicurezza avanzata: Cloud SQL implementa misure di sicurezza avanzate per proteggere i dati dei tuoi database, tra cui crittografia dei dati in transito e a riposo, controlli di accesso basati su IAM di GCP e firewall di rete per controllare l'accesso al database.

5. Integrazione con l'ecosistema GCP: Cloud SQL si integra facilmente con altri servizi di Google Cloud Platform, come Compute Engine, Kubernetes Engine, App Engine e BigQuery. Puoi utilizzare Cloud SQL come backend per le tue applicazioni cloud native.

6. Supporto per MySQL, PostgreSQL e SQL Server: Cloud SQL supporta i principali motori di database relazionali, tra cui MySQL, PostgreSQL e SQL Server. Ciò consente di migrare facilmente i tuoi database esistenti su Cloud SQL o creare nuovi database utilizzando uno dei motori supportati.

Cloud SQL semplifica la gestione dei database relazionali, offrendo una soluzione completamente gestita che riduce il carico operativo e consente di concentrarsi sullo sviluppo delle applicazioni. È adatto per una vasta gamma di casi d'uso, tra cui applicazioni web, applicazioni aziendali, sviluppo e test, e molto altro ancora.

## Dataflow
