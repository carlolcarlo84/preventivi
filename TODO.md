# TODO - CM IBRIC Preventivi

## Analisi progetto

PWA per creare e gestire preventivi per lavori di muratura e pitturazione.

**Struttura attuale:**
- `index.html` (1850 righe) — HTML + CSS + JS tutto in un file
- `manifest.json` — configurazione PWA
- `sw.js` — service worker per offline
- `icon.svg` — icona app
- `TODO.md` — questo file

**Funzionalità esistenti:**
- Dashboard con statistiche (totali, bozze, inviati, importo)
- CRUD completo preventivi (crea, modifica, elimina, duplica)
- Editor con 3 sezioni: Lavori, Manodopera, Materiali
- Calcolo automatico totale
- Stampa / PDF (tramite finestra di stampa browser)
- Condivisione WhatsApp (testo + file HTML)
- Backup e ripristino (JSON)
- Impostazioni azienda
- Installazione PWA (offline)
- Promemoria backup ogni 7 giorni
- Ricerca e filtro per stato

## Task

### Alta priorità
- [ ] Inizializzare Git e collegare auto-deploy su Vercel (GitHub → Vercel)
- [x] Sync cloud con Firebase Firestore (dati condivisi tra dispositivi)
- [ ] Separare HTML/CSS/JS in file distinti
- [ ] Aggiungere gestione IVA (scorporo, importo ivato/non ivato)
- [ ] Rivedere la numerazione preventivi (formato personalizzabile)

### Media priorità
- [ ] Aggiungere sconto percentuale o fisso sul totale
- [ ] Template di preventivi predefiniti
- [ ] Migliorare la validazione input (campi obbligatori, formati)
- [ ] Aggiungere colonna "categoria" ai lavori
- [ ] Ordinamento colonne nella dashboard
- [ ] Anteprima prima della stampa

### Bassa priorità
- [ ] Esportazione PDF nativa con libreria js (jsPDF o similar)
- [ ] Tema scuro
- [ ] statistiche grafiche (chart)
- [ ] Inviare preventivo via email direttamente
- [ ] Test funzionali
- [ ] i18n / multilingua
