# Fase 1 - Radar Trend di Mercato

## Stato
Procedura in definizione.

Questo file descrive la prima macrofase del progetto BuyerWise Lab. La procedura verra aggiornata man mano che vengono verificate le fonti, le connessioni disponibili e il formato migliore degli output.

## Obiettivo
Individuare gli argomenti, le categorie e i temi con maggiore crescita di interesse in una o piu aree geografiche e in un periodo scelto dall'utente.

La Fase 1 non sceglie ancora il prodotto finale da recensire. Serve a capire dove si sta muovendo l'attenzione delle persone e quali argomenti meritano una successiva analisi di mercato.

## Analisi previste

### Analisi A - Scenario ampio
L'Analisi A viene usata per osservare un'area ampia.

Esempi di area:
- Mondo
- Europa
- America
- Cina
- altra area scelta dall'utente

Parametri scelti dall'utente:
- area geografica
- periodo di analisi, espresso in giorni
- numero di risultati richiesti

Scopo:
- capire i grandi movimenti dell'area scelta
- individuare temi globali o macrotrend
- tradurre e presentare i risultati in italiano

### Analisi B - Scenario operativo
L'Analisi B viene usata per osservare un'area piu specifica e monetizzabile.

Esempi di area:
- Italia
- Francia
- Spagna
- Germania
- Europa
- altra area scelta dall'utente

Parametri scelti dall'utente:
- area geografica
- periodo di analisi, espresso in giorni
- numero di risultati richiesti

Scopo:
- trovare opportunita realmente sfruttabili
- individuare categorie o argomenti adatti a contenuti video
- valutare monetizzazione, affiliazione e rischio

## Esempio di richiesta

```text
Esegui Fase 1.

Analisi A:
- area: Mondo
- periodo: 90 giorni
- risultati: 10

Analisi B:
- area: Italia
- periodo: 30 giorni
- risultati: 20
```

## Fonti e connessioni
Le fonti da usare non vengono definite direttamente in questo file.

Le connessioni, i servizi candidati, le API e gli eventuali requisiti di accesso sono descritti nel file:

```text
macrofasi/connessioni.md
```

Questo file della Fase 1 deve leggere quel documento per sapere quali emittenti di traffico sono disponibili, quali sono da verificare e quali richiedono iscrizione o chiavi API.

## Tabella emittenti Fase 1

Questa tabella indica quali fonti possono essere usate per il Radar Trend di Mercato e se sono gia operative.

| Fonte | Tipo | Accesso | Iscrizione | Fatto | Utile Fase 1 | Note |
|---|---|---|---|---|---|---|
| Google Trends | trend ricerca | sito / API alpha | API su richiesta | no | altissima | fonte principale per crescita interesse |
| SerpApi Google Trends | API trend | API key | si | no | altissima | alternativa pratica per automatizzare Google Trends |
| DataForSEO Trends | API trend | API key | si | no | altissima | utile per automazione e dati per area/periodo |
| YouTube Data API | video/search | API key Google | si | no | alta | utile per capire se il tema funziona in video |
| TikTok Creative Center | social trend | web | da verificare | no | alta | utile per trend brevi e virali |
| Pinterest Trends | trend visuali | account business | si | no | media/alta | utile per casa, moda, beauty, ricette |
| Google News | news | web / API terze | dipende | no | media | utile ma molti temi hanno rischio alto o bassa monetizzazione |
| Amazon | marketplace | account / API | si | no | media | piu utile nelle fasi prodotto |
| Amazon Product Advertising API | prodotti / affiliazione | API key | si | no | media in Fase 1, alta dopo | richiede Programma Affiliazione Amazon |
| eBay Browse API | marketplace | API | si | no | media | prodotti disponibili e prezzi |
| eBay Marketplace Insights | vendite storiche | API limitata | si + approvazione | no | alta se ottenibile | vendite fino a 90 giorni, accesso ristretto |
| eBay Partner Network | affiliazione | account | si | no | bassa in Fase 1, alta dopo | programma affiliato eBay |
| AliExpress Portals | marketplace / affiliazione | API / account | si | no | media | utile per prodotti economici e globali |
| Reddit | community | API / web | si per API | no | media | segnali reali, discussioni, problemi utenti |
| Quora | domande | web | da verificare | no | bassa/media | utile per capire domande frequenti |
| Forum verticali | community | web | dipende | no | media | cambiano per categoria |
| Comparaprezzi italiani | prezzi / prodotti | web / API se esiste | dipende | no | media | utile soprattutto dopo la scelta categoria |
| Awin | affiliazione | account | si | no | bassa in Fase 1, alta dopo | network affiliati |
| TradeDoubler | affiliazione | account | si | no | bassa in Fase 1, alta dopo | network affiliati |
| CJ Affiliate | affiliazione | account | si | no | bassa in Fase 1, alta dopo | network affiliati |
| Daisycon | affiliazione | account | si | no | bassa in Fase 1, alta dopo | network affiliati |

## Emittente di traffico
Nel progetto, una "emittente di traffico" e un servizio, sito, piattaforma o fonte dati che permette di capire cosa le persone stanno cercando, guardando, comprando, discutendo o seguendo in un determinato periodo.

Esempi:
- motori di ricerca
- piattaforme video
- social network
- marketplace
- comparatori prezzi
- siti di notizie
- community
- forum
- strumenti di trend analysis

## Output richiesto
La Fase 1 deve produrre una tabella unica con numerazione progressiva.

La numerazione non deve ripartire da 1 per ogni analisi.

Esempio:
- Analisi A: risultati 1-10
- Analisi B: risultati 11-30

## Campi della tabella

| Campo | Descrizione |
|---|---|
| N | Numero progressivo unico |
| Analisi | A oppure B |
| Area | Area geografica analizzata |
| Giorni | Periodo analizzato espresso in giorni |
| Argomento | Tema, categoria o trend individuato |
| Descrizione | Breve spiegazione del trend |
| Crescita | Valutazione della crescita dell'interesse |
| Monetizzazione | Potenziale di guadagno tramite contenuti, pubblicita o altre forme |
| Affiliazione | Possibilita di usare link affiliati o programmi partner |
| Rischio | Rischio editoriale, legale, reputazionale o commerciale |
| Finestra 80% traffico | Periodo in cui si concentra circa l'80% dell'interesse rilevato |
| Decisione | Approfondire, monitorare o scartare |

## Finestra 80% traffico
La "Finestra 80% traffico" serve a capire se un argomento e caldo adesso oppure se il suo picco e gia passato.

Esempi:
- ultimi 14 giorni
- ultimi 60 giorni
- da 300 a 200 giorni fa
- distribuito su tutto il periodo
- picco iniziale, ora in calo

Questa informazione e importante per evitare di investire tempo su argomenti che hanno avuto traffico nel periodo scelto, ma che non sono piu in crescita nel momento attuale.

## Argomenti sensibili
Gli argomenti sensibili non devono essere eliminati automaticamente, ma devono essere evidenziati con rischio alto o medio.

Esempi:
- guerre
- terremoti
- morti
- tragedie
- cronaca nera
- politica estrema
- salute delicata
- finanza speculativa
- disastri naturali

Questi argomenti possono avere molto traffico, ma spesso sono poco monetizzabili, rischiosi o non adatti a contenuti promozionali.

## Formati output futuri
Da definire piu avanti.

Possibili formati:
- Markdown
- HTML leggibile da telefono
- CSV
- Excel

Per ora il formato definitivo non e ancora deciso.

## Chiusura della Fase 1
La Fase 1 termina quando l'utente sceglie uno o piu numeri dalla tabella da portare alla fase successiva.

Esempio:

```text
Approfondisci il numero 12.
```

Il numero scelto diventera input della fase successiva.
