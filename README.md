# KAIVO: Specialty Coffee

## Presentazione del brand

**KAIVO** è una torrefazione artigianale: tostiamo il caffè noi, con cura, per avere un prodotto di qualità.

Sul sito puoi comprare caffè in grani, macinato o in bustine, gli accessori per prepararlo e gli abbonamenti.

Il sito è stato fatto dall'agenzia **JDYP** (Jaspreet, Daniel, Yaroslav Protocol) per le committenti Prof.ssa Villani Valentina e Anna de Vincentiis.

## Stack tecnologico

- **HTML5**: struttura delle pagine
- **CSS3**: CSS Grid per la griglia prodotti, Flexbox per header e carrello, layout responsive
- **JavaScript** (vanilla, nessun framework): catalogo dinamico, filtri e ricerca, carrello, checkout
- **localStorage**: persistenza del carrello
- **Git & GitHub**: versionamento e Pull Request

## Avviare il progetto in locale

1. Clona il repository:
   ```bash
   git clone https://github.com/glinieckidaniel/PROGETTO-KAIVO.git
   cd PROGETTO-KAIVO
   ```
2. Apri la cartella in **VS Code**, fai clic destro su `html/index.html` e scegli **Open with Live Server** (estensione Live Server).
   Il sito si apre nel browser.

## Struttura del progetto

```
PROGETTO-KAIVO/
├── html/           pagine del sito (index, catalogo, carrello, checkout, chi-siamo, contatti)
├── css/            fogli di stile
├── js/             script JavaScript
├── data/           catalogo prodotti (prodotti.json)
├── img/            immagini
├── docs/verbali/   verbali dei briefing
└── README.md
```

## Autori

| Autore | Ruolo |
|---|---|
| Jaspreet Singh | Responsabile |
| Yaroslav Bilan | Git & QA Specialist + Lead JS Developer |
| Daniel Gliniecki | CSS Designer + mediatore del gruppo |
