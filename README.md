# KAIVO: Specialty Coffee Roasters

E-commerce di nicchia per una torrefazione artigianale, sviluppato dall'agenzia **JDYP** (Jaspreet Daniel Yaroslav Protocol) per le committenti Prof.ssa Villani Valentina e Anna de Vincentiis.

## Il brand

**KAIVO** è una torrefazione artigianale di specialty coffee. Il sito vende miscele in grani e macinato, accessori per l'estrazione e abbonamenti.

*(Da completare: storia del brand, palette colori, tono di voce.)*

## Stack tecnologico

- **HTML5**: struttura delle pagine
- **CSS3**: CSS Grid per la griglia prodotti, Flexbox per header e carrello, layout responsive
- **JavaScript** (vanilla, nessun framework): catalogo dinamico, filtri e ricerca, carrello, checkout
- **localStorage**: persistenza del carrello
- **Git & GitHub**: GitHub Flow, Pull Request con code review

## Funzionalità previste

- Catalogo dinamico (8-12 prodotti) caricato da una struttura dati JS o da un file `.json`
- Filtri per categoria, ordinamento per prezzo, ricerca in tempo reale
- Dettaglio prodotto in modale con scelta della macinatura
- Carrello con badge, quantità modificabili, subtotale, spedizione gratuita sopra i 50 €, totale
- Carrello persistente con localStorage
- Checkout simulato con validazione del form e conferma ordine
- Design responsive per smartphone, tablet e desktop

## Avviare il progetto in locale

1. Clona il repository:
   ```bash
   git clone <URL-del-repository>
   cd <nome-cartella>
   ```
2. Se i prodotti sono in un file `.json`, serve un piccolo server locale (aprire `index.html` con un doppio clic non basta). Due opzioni:
   - con l'estensione **Live Server** di VS Code, tasto destro su `index.html` e "Open with Live Server"
   - oppure da terminale:
     ```bash
     python3 -m http.server 8000
     ```
     poi apri `http://localhost:8000` nel browser.

## Flusso di lavoro Git

Usiamo **GitHub Flow**:

- `main` è stabile e protetto: niente push diretti.
- Ogni lavoro nasce da un ramo corto: `feat/…`, `fix/…`, `style/…`, `docs/…`.
- Ogni Pull Request richiede almeno **1 approvazione** di un altro componente prima del merge.
- Commit atomici con prefissi standard: `feat:`, `fix:`, `style:`, `docs:`, `refactor:`.

I verbali delle riunioni sono in [`docs/verbali/`](docs/verbali/).

## Autori e ruoli

| Autore | Ruolo |
|---|---|
| Jaspreet Singh | Responsabile |
| Yaroslav Bilan | Git & QA Specialist + Lead JS Developer |
| Daniel Gliniecki | CSS Designer + mediatore del gruppo |

Tutti i componenti contribuiscono allo sviluppo del codice.

## Committenti

Prof.ssa Villani Valentina e Anna de Vincentiis. Progetto di 3 settimane, Classe 5ª Informatica.
