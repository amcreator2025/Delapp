# Ristorante – Static Site for Vercel

Questo pacchetto contiene le pagine HTML pronte per essere pubblicate su Vercel come **sito statico**.

## Struttura
- `index.html` → reindirizza a `scelta_ordine.html`
- `scelta_ordine.html` → selezione modalità e orario
- `menu_iniziale.html` → selezione piatti (legge il menu da Supabase)
- `anagrafica_cliente_asporto.html` → dati per ritiro
- `anagrafica_cliente_consegna.html` → dati per consegna
- `conferma_ordine.html` → conferma ordine
- `vercel.json` → configurazione minima Vercel

> Nota: le credenziali **Supabase anon** inserite nei file sono OK per app pubbliche lato client. Valuta in futuro di proteggere eventuali operazioni sensibili con RLS e policy adeguate.

## Deploy rapido da CLI
1. Installa la CLI (se non già fatto):  
   `npm i -g vercel`
2. Autenticati:  
   `vercel login`
3. Nella cartella del progetto esegui:  
   `vercel --prod`

## Deploy via Dashboard Vercel
1. Comprimi o usa questa cartella così com'è (già pronta).  
2. Vai su **New Project → Import → Upload** e carica la cartella.  
3. Conferma le impostazioni (framework: *Other*, build: *Static*).  
4. Deploy → ottieni gli URL pubblici (es. `https://ristorante-static.vercel.app/`).

## URL utili (una volta online)
- `/` → reindirizza a `scelta_ordine.html`
- `/scelta_ordine.html`
- `/menu_iniziale.html`
- `/anagrafica_cliente_asporto.html`
- `/anagrafica_cliente_consegna.html`
- `/conferma_ordine.html`

Buon lavoro! 🍕
