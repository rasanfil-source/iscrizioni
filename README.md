# Iscrizioni Cammino 2026 🥾

[English version here](README_EN.md)

---

## Descrizione
Questo progetto è un sistema di gestione delle iscrizioni per il "Cammino 2026", organizzato dalla Parrocchia S. Eugenio. L'applicazione permette di gestire i partecipanti, calcolare i saldi (inclusi transfer e opzioni aggiuntive come assicurazione o colazione) e inviare riepiloghi automatici tramite email.

### Caratteristiche principali
- 🔍 **Ricerca Partecipanti**: Lookup rapido per cognome o nome e cognome.
- 💰 **Gestione Saldi**: Calcolo automatico dei costi basato sulle opzioni selezionate (transfer Roma-Fiumicino, Porto-Tui, ecc.).
- 📧 **Invio Email**: Generazione e invio di email professionali con il riepilogo del saldo e le istruzioni per il pagamento (IBAN).
- 📋 **Verifica Dati**: Controllo automatico dei dati mancanti (documenti, taglie magliette, ecc.) integrato con un foglio di adempimenti pre-partenza.
- ⚡ **Performance**: Utilizzo di meccanismi di caching per velocizzare le operazioni di lettura dai fogli Google.

### Nota sull'implementazione
> [!IMPORTANT]
> Il **codice principale** dell'applicazione (Interfaccia Utente e logica frontend) risiede nei file con estensione **`.htm`** / **`.html`** (o file `.txt` contenenti codice HTML). La logica di backend è gestita tramite Google Apps Script.

---

## Stack Tecnologico
- **Backend**: Google Apps Script (JavaScript)
- **Frontend**: HTML5, CSS3 (Vanilla), JavaScript
- **Database**: Google Sheets
- **Notifiche**: Gmail API
