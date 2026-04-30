# Connessioni

## Stato
Documento in definizione.

Questo file raccoglie le possibili connessioni da usare nel progetto BuyerWise Lab.

Per scelta operativa iniziale, questo file puo contenere credenziali in chiaro.

Nota: se la cartella viene condivisa, caricata online, inviata via email o compressa in un archivio, verranno condivise anche username, password, token e API key presenti qui.

## Campi credenziali standard
Ogni connessione deve usare questi campi quando applicabili:

```text
URL login:
URL documentazione:
Username:
Email:
Password:
API key:
Secret key:
Token:
Account creato: no
Iscrizione fatta: no
Test accesso fatto: no
Stato:
Note:
```

## Stati possibili

| Stato | Significato |
|---|---|
| Da verificare | Servizio da studiare |
| Da creare | Account o accesso da creare |
| In attesa credenziali | Account esistente, manca configurazione locale |
| Attiva | Connessione pronta all'uso |
| Scartata | Servizio non adatto |

## Servizi di informazione e trend

### Google Trends
- Categoria: motore di ricerca / trend
- Uso previsto: capire crescita di interesse per argomenti e parole chiave
- Area: globale e paesi specifici
- Periodi: fino a 5 anni con API ufficiale alpha, da verificare con accesso reale
- API key richiesta: si per API ufficiale alpha, accesso da richiedere
- URL documentazione: https://developers.google.com/search/apis/trends
- Google Cloud Project Number: 31418153155
- Google Cloud Project ID: buyerwise-lab
- Username:
- Email:
- Password:
- API key:
- Account creato: si
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: in preparazione
- Note: fonte importante per Fase 1. Project ID identificato: buyerwise-lab. Il numero 31418153155 e il Project Number.

### Google Search / SERP
- Categoria: motore di ricerca
- Uso previsto: analizzare risultati, ricerche correlate e interesse commerciale
- Area: globale e paesi specifici
- API key richiesta: probabilmente tramite servizio terzo
- URL documentazione:
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: utile per capire intenti di ricerca e concorrenza.

### SerpApi Google Trends
- Categoria: API trend / SERP
- Uso previsto: automatizzare Google Trends, Google Search e altre ricerche
- Area: globale e paesi specifici
- API key richiesta: si
- URL documentazione: https://serpapi.com/google-trends-api
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: candidato pratico per Fase 1.

### DataForSEO Trends
- Categoria: API trend / SEO
- Uso previsto: analisi trend per parole chiave, aree e periodi
- Area: globale e paesi specifici
- API key richiesta: si
- URL documentazione: https://docs.dataforseo.com/v3/dataforseo_trends-overview/
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: candidato pratico per Fase 1 automatizzata.

### Google News
- Categoria: notizie
- Uso previsto: intercettare temi in crescita legati alle notizie
- Area: globale e paesi specifici
- API key richiesta: da verificare
- URL documentazione:
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: utile ma da filtrare per rischio e monetizzazione.

### YouTube
- Categoria: video / ricerca contenuti
- Uso previsto: verificare interesse video, visualizzazioni, argomenti emergenti
- Area: globale e paesi specifici
- API key richiesta: si, tramite Google Cloud / YouTube Data API
- URL documentazione: https://developers.google.com/youtube/v3
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: importante per valutare se un argomento puo funzionare come video.

### TikTok Creative Center
- Categoria: social / trend
- Uso previsto: individuare hashtag, contenuti e interessi emergenti
- Area: globale e paesi specifici, se disponibile
- API key richiesta: da verificare
- URL documentazione: https://ads.tiktok.com/business/creativecenter/
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: utile soprattutto per contenuti brevi.

### Pinterest Trends
- Categoria: social / trend visuale
- Uso previsto: moda, casa, beauty, lifestyle, design, ricette
- Area: da verificare
- API key richiesta: da verificare
- URL documentazione: https://help.pinterest.com/en/business/article/pinterest-trends
- Username:
- Email:
- Password:
- API key:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: utile per categorie visuali.

## Marketplace

### Amazon
- Categoria: marketplace
- Uso previsto: prodotti acquistabili, disponibilita, dati prodotto, affiliazione
- Area: Italia e altri marketplace nazionali
- API key richiesta: da verificare
- URL documentazione:
- Username:
- Email:
- Password:
- API key:
- Secret key:
- Tracking ID:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: piu utile nelle fasi prodotto che nella Fase 1 generale.

### eBay
- Categoria: marketplace
- Uso previsto: prodotti, vendite, disponibilita, affiliazione
- Area: Italia e altri paesi
- API key richiesta: da verificare
- URL documentazione: https://developer.ebay.com/api-docs/buy/browse/static/overview.html
- Username:
- Email:
- Password:
- API key:
- Secret key:
- Token:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: da valutare per trend commerciali e prodotti usati/nuovi.

### AliExpress
- Categoria: marketplace
- Uso previsto: prodotti economici, trend internazionali, affiliazione
- Area: globale
- API key richiesta: da verificare
- URL documentazione:
- Username:
- Email:
- Password:
- API key:
- Secret key:
- Token:
- Account creato: no
- Iscrizione fatta: no
- Test accesso fatto: no
- Stato: da verificare
- Note: utile per prodotti economici e trend emergenti.

### Comparaprezzi italiani
- Categoria: comparatori / marketplace
- Uso previsto: prezzi, disponibilita, prodotti popolari
- Area: Italia
- API key richiesta: da verificare
- Stato: da verificare
- Note: da identificare i servizi piu adatti.

## Community e discussioni

### Reddit
- Categoria: community
- Uso previsto: discussioni, problemi reali, trend informali
- Area: globale, community specifiche per paese o lingua
- API key richiesta: da verificare
- Stato: da verificare
- Note: utile per capire cosa interessa davvero agli utenti.

### Forum verticali
- Categoria: community
- Uso previsto: segnali tecnici e discussioni di nicchia
- Area: da verificare per categoria
- API key richiesta: no o da verificare
- Stato: da verificare
- Note: i forum cambiano in base alla categoria.

### Quora
- Categoria: domande e risposte
- Uso previsto: domande frequenti e interessi degli utenti
- Area: globale
- API key richiesta: da verificare
- Stato: da verificare
- Note: da valutare accessibilita e qualita dati.

## Programmi di affiliazione

### Amazon Programma Affiliazione
- Categoria: affiliazione
- Uso previsto: monetizzazione prodotti tramite link affiliati
- Area: Italia e altri marketplace nazionali
- Account richiesto: si
- API key richiesta: da verificare
- Stato: da verificare
- Note: da verificare requisiti, regole immagini, prezzi e disclosure.

### eBay Partner Network
- Categoria: affiliazione
- Uso previsto: monetizzazione prodotti e offerte
- Area: da verificare
- Account richiesto: si
- API key richiesta: da verificare
- Stato: da verificare
- Note: da valutare per categorie prodotto.

### Network di affiliazione
- Categoria: affiliazione
- Uso previsto: trovare programmi per categorie non coperte da Amazon
- Esempi da verificare: Awin, TradeDoubler, CJ Affiliate, Daisycon
- Account richiesto: si
- API key richiesta: da verificare
- Stato: da verificare
- Note: utile per categorie come viaggi, software, finanza, casa, servizi.

## Note operative
Questo file dovra essere aggiornato ogni volta che una connessione viene verificata, attivata, scartata o sostituita.

Ogni servizio dovra avere, quando possibile:
- fonte ufficiale
- tipo di dati disponibili
- limiti di utilizzo
- costi
- requisiti tecnici
- requisiti legali o commerciali
- utilita per Fase 1
- utilita per fasi successive
