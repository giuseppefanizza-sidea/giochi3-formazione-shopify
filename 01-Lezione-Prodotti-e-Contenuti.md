# 📖 Lezione 1 — Prodotti, Collezioni e Contenuti Editoriali

**Corso:** Formazione Shopify Giochi3  
**Destinatari:** Team Marketing, Category Manager  
**Durata:** ~90 minuti (+ 15 min Q&A)  
**Data:** ___________  
**Formatore:** ___________

---

## Obiettivi della lezione

Al termine della lezione i partecipanti saranno in grado di:

1. Comprendere come funziona il catalogo prodotti e il ruolo del middleware
2. Sapere cosa possono (e non possono) modificare sulla scheda prodotto
3. Creare e gestire collezioni manuali e automatiche
4. Scrivere contenuti editoriali efficaci per le pagine collezione
5. Creare e ottimizzare Pages (pagine statiche) in Shopify
6. Gestire la homepage tramite il tema (sezioni e blocchi)
7. Pubblicare articoli blog per SEO e traffico organico

---

## Scaletta

| Blocco | Durata | Contenuto |
|--------|--------|-----------|
| **Intro** | 5 min | Obiettivi, agenda, regole del gioco |
| **Parte 1** — Overview Prodotti e Collezioni | 30 min | Come funziona il catalogo, cosa può fare il team, collezioni automatiche vs manuali |
| **Pausa** | 5 min | — |
| **Parte 2** — Contenuti Editoriali | 50 min | Pagine collezione, Pages, Homepage, Blog |
| **Q&A e Recap** | 15 min | Domande, checklist operativa, prossimi passi |

---

## Materiali di supporto

- Slide di presentazione: `LEZIONI/slides/lezione-01-slides.html`
- Documenti di riferimento:
  - `01-Gestione-Prodotti/01-prodotti-e-varianti.md`
  - `01-Gestione-Prodotti/02-collezioni-manuali-automatiche.md`
  - `01-Gestione-Prodotti/04-gestione-immagini-media.md`
  - `05-Contenuti-e-Pagine/01-pagine-e-blog.md`
  - `05-Contenuti-e-Pagine/03-seo-base-shopify.md`

---

## Prerequisiti per i partecipanti

- Accesso all'admin Shopify (ruolo Staff o superiore)
- Laptop con browser aggiornato
- Familiarità base con l'interfaccia Shopify (login, navigazione sidebar)

---

---

# PARTE 1 — Overview Prodotti e Collezioni

*Durata: 30 minuti*

---

## 1.1 Come funziona il catalogo Giochi3

### Il flusso dei dati

```
Gestionale/ERP  →  Middleware  →  Shopify
                      ↓
           Prodotti creati e aggiornati
           automaticamente nel catalogo
```

Il catalogo è alimentato **automaticamente** dal middleware. I prodotti **non si creano a mano** (unica eccezione: bundle promozionali).

### Cosa sincronizza il middleware

| Dato | Gestito da middleware | Modificabile dal team |
|------|:--------------------:|:--------------------:|
| Titolo e descrizione | ✅ | ⚠️ (può essere sovrascritta) |
| Prezzi (vendita, confronto, costo) | ✅ | ❌ |
| SKU e EAN | ✅ | ❌ |
| Inventario / quantità | ✅ | ❌ |
| Varianti | ✅ | ❌ |
| Immagine principale | ✅ | ⚠️ (potrebbe essere sovrascritta) |
| Immagini aggiuntive | ❌ | ✅ |
| Tag | Parziale | ✅ (si sommano) |
| Metafield custom | ❌ | ✅ |
| SEO (meta title, description, URL) | ❌ | ✅ |
| Stato (Attivo/Bozza) | ❌ | ✅ |

### Regola d'oro

> 🎯 **Il team arricchisce, non sostituisce.** Il vostro lavoro è aggiungere valore editoriale a un catalogo che arriva già strutturato: immagini lifestyle, tag strategici, metafield, contenuti SEO.

---

## 1.2 La scheda prodotto — cosa potete fare

### Azioni consentite

1. **Aggiungere immagini** — foto ambientate, dettagli confezione, video
2. **Compilare l'alt text** — fondamentale per SEO e accessibilità
3. **Aggiungere tag** — per collezioni, filtri, promozioni
4. **Compilare metafield** — età consigliata, numero giocatori, video YouTube
5. **Ottimizzare la SEO** — meta title, meta description, URL handle
6. **Cambiare stato** — Attivo/Bozza per nascondere/mostrare un prodotto

### Azioni vietate

- ❌ Creare prodotti manualmente (tranne bundle)
- ❌ Modificare prezzi
- ❌ Modificare inventario/quantità
- ❌ Rinominare varianti

### Demo live: scheda prodotto

📋 **Esercizio guidato:**
1. Aprire un prodotto dal catalogo
2. Aggiungere un'immagine secondaria
3. Compilare l'alt text
4. Aggiungere un tag (es. `novita-2026`)
5. Verificare la sezione SEO

---

## 1.3 Collezioni — organizzare il catalogo

### Due tipi di collezione

| Tipo | Come funziona | Quando usarla |
|------|---------------|---------------|
| **Automatica** | I prodotti entrano/escono da soli in base a regole (tag, tipo, prezzo…) | Categorie merceologiche, marche, fasce età |
| **Manuale** | Aggiungi/rimuovi prodotti uno a uno | Selezioni editoriali, bundle curati, promo stagionali |

### Collezione automatica — esempio pratico

**"Giochi da Tavolo"**
- Condizione: Tag del prodotto → è uguale a → `gioco-tavolo`
- Risultato: ogni prodotto con quel tag appare automaticamente

**"Novità Giugno 2026"**
- Condizione: Tag del prodotto → contiene → `novita-2026`
- Risultato: si popola man mano che il middleware sincronizza nuovi arrivi

### Collezione manuale — quando usarla

- "I nostri preferiti" — selezione curata dal team
- "Bundle Natale" — pacchetti promozionali specifici
- "Offerte della settimana" — rotazione manuale

### La pagina della collezione

Ogni collezione ha una **pagina pubblica** con:
- Titolo
- Descrizione (contenuto editoriale — fondamentale per SEO!)
- Immagine di copertina
- Griglia prodotti
- SEO (meta title, meta description, URL)

> ⚠️ **La descrizione della collezione è un contenuto editoriale a tutti gli effetti.** Non lasciarla vuota — è la vostra opportunità per posizionarvi su Google e guidare il cliente.

### Best practice per Giochi3

- Collezioni automatiche per: categorie, marche, fasce d'età, bundle
- Collezioni manuali per: promo stagionali, selezioni editoriali
- Ogni prodotto può stare in più collezioni contemporaneamente
- Le collezioni alimentano il **menu di navigazione**
- Compilare SEMPRE descrizione + SEO della collezione

### Demo live: creare una collezione

📋 **Esercizio guidato:**
1. Creare una collezione automatica "Giochi 3-5 anni"
2. Condizione: Tag → contiene → `eta-3-5`
3. Scrivere una descrizione editoriale (almeno 100 parole)
4. Aggiungere un'immagine di copertina
5. Compilare la sezione SEO

---

---

# PARTE 2 — Contenuti Editoriali

*Durata: 50 minuti*

---

## 2.1 Mappa dei contenuti in Shopify

Shopify offre **4 tipi di contenuti editoriali** su cui il team lavora direttamente:

```
Contenuti Editoriali Shopify
│
├── 📂 Pagine Collezione     → Descrizioni delle categorie prodotto
│                               (visibili sotto il titolo della collezione)
│
├── 📄 Pages (Pagine)        → Contenuti statici (Chi siamo, FAQ, Guide...)
│                               (raggiungibili via menu o link diretto)
│
├── 🏠 Homepage              → La vetrina principale del sito
│                               (gestita tramite il Theme Editor)
│
└── 📝 Blog                  → Articoli editoriali per SEO e engagement
                                (guide, consigli, novità, eventi)
```

### Perché i contenuti editoriali contano

| Obiettivo | Come i contenuti aiutano |
|-----------|--------------------------|
| **SEO / Traffico organico** | Testi unici e ricchi di keyword posizionano il sito su Google |
| **Conversione** | Descrizioni convincenti guidano all'acquisto |
| **Fiducia** | Pagine istituzionali (Chi siamo, Policy) rassicurano il cliente |
| **Engagement** | Il blog porta traffico informazionale e costruisce autorità |
| **Brand** | Il tono di voce e i contenuti definiscono l'identità Giochi3 |

---

## 2.2 Pagine Collezione — il contenuto più sottovalutato

### Dove si trova

La descrizione della collezione appare sulla pagina `/collections/nome-collezione`, tipicamente:
- **Sopra** la griglia prodotti (introduzione)
- Oppure **sotto** la griglia (approfondimento SEO)
- Dipende dal tema — nel caso Giochi3, verificare con il tecnico

### Come si modifica

1. **Prodotti → Collezioni** → seleziona la collezione
2. Campo **Descrizione** — editor rich text (grassetto, heading, elenchi, immagini)
3. Sezione **SEO** in basso — meta title, meta description, URL

### Struttura consigliata per la descrizione

```
[H2] Titolo editoriale accattivante con keyword
[Paragrafo] 2-3 frasi che introducono la categoria e parlano al target
[H3] Per chi sono questi prodotti
[Paragrafo] Target (età, occasione), benefici
[H3] Come scegliere
[Paragrafo] Criteri di scelta (età, tipo di gioco, marca)
[CTA] Frase che invita a esplorare o filtrare
```

### Esempio: Collezione "Giochi da Tavolo"

> **I migliori giochi da tavolo per tutta la famiglia**
>
> Cerchi un gioco da tavolo per le serate in famiglia o un regalo originale? Nella nostra selezione trovi giochi di strategia, cooperativi, party game e classici intramontabili, tutti scelti per qualità e divertimento garantito.
>
> **Per chi sono**
> Dai 3 anni in su, con giochi graduati per età e complessità. Trovi giochi per 2 giocatori fino a grandi gruppi da 8+.
>
> **Come scegliere**
> Filtra per età consigliata, numero di giocatori o durata della partita. I nostri preferiti hanno il badge ⭐ nella scheda prodotto.

### Checklist SEO per pagine collezione

- [ ] Meta title con keyword primaria (es. "Giochi da Tavolo per Bambini e Famiglie | Giochi3")
- [ ] Meta description con CTA (es. "Scopri oltre 200 giochi da tavolo...")
- [ ] URL pulito (`/collections/giochi-da-tavolo`)
- [ ] Descrizione di almeno 150-300 parole
- [ ] Heading (H2, H3) strutturati
- [ ] Keyword naturali nel testo (no keyword stuffing)

### Priorità per Giochi3

Compilare PRIMA le collezioni ad alto traffico potenziale:
1. Categorie principali (Costruzioni, Action Figures, Giochi da Tavolo, Peluche)
2. Marche top (YES TOYS, Hasbro, Mattel)
3. Fasce d'età (0-2, 3-5, 6-8, 9+)
4. Collezioni promozionali (Novità, Offerte, Bundle)

---

## 2.3 Pages — le pagine statiche

### Cosa sono

Le Pages sono contenuti statici accessibili da un URL fisso. Non cambiano nel tempo (o raramente). Servono per informazioni istituzionali, di servizio, e guide.

### Come si creano

**Percorso:** Negozio online → Pagine → Aggiungi pagina

| Campo | Cosa compilare |
|-------|---------------|
| **Titolo** | Nome della pagina (diventa anche H1) |
| **Contenuto** | Editor rich text: testo, immagini, video, tabelle, link |
| **Template** | Scegli layout (default o custom se disponibili) |
| **Visibilità** | Pubblicata / Nascosta (con data programmata) |
| **SEO** | Meta title + Meta description + URL handle |

### Pages essenziali per Giochi3

| Pagina | URL | Contenuto | Priorità |
|--------|-----|-----------|----------|
| Chi siamo | `/pages/chi-siamo` | Storia Giochi3, mission, valori, foto negozi | Alta |
| Contatti | `/pages/contatti` | Form, telefono, email, mappa store, orari | Alta |
| FAQ | `/pages/domande-frequenti` | Domande frequenti (spedizioni, resi, pagamenti) | Alta |
| Spedizioni | `/pages/spedizioni` | Tempi, costi, corrieri, soglia free shipping | Alta |
| Resi e Rimborsi | `/pages/resi` | Policy reso, procedura, tempistiche | Alta |
| Lista Nascita | `/pages/lista-nascita` | Come funziona il servizio, vantaggi, CTA registrazione | Media |
| Punti Vendita | `/pages/store-locator` | Mappa, indirizzi, orari dei negozi fisici | Media |
| Programma Fidelity | `/pages/fidelity` | Come funziona la card, punti, vantaggi | Media |
| Lavora con noi | `/pages/lavora-con-noi` | Posizioni aperte, cultura aziendale | Bassa |

### Best practice per le Pages

- **Struttura il testo** con heading (H2, H3), elenchi puntati, tabelle — evita muri di testo
- **Usa immagini** per spezzare il contenuto (foto negozi, icone, infografiche)
- **Mobile first** — il 70%+ dei visitatori naviga da mobile, testi brevi e leggibili
- **CTA chiara** — ogni pagina dovrebbe avere un'azione successiva (link a collezione, contatto, registrazione)
- **Aggiorna periodicamente** — orari, policy, FAQ cambiano nel tempo

### ⚠️ Attenzione: URL e redirect

- L'URL di una pagina si imposta alla creazione e **non va cambiato** dopo la pubblicazione
- Se devi cambiarlo: crea prima un **redirect** da vecchio a nuovo URL
- Percorso: Negozio online → Navigazione → Redirect URL

### Demo live: creare una pagina

📋 **Esercizio guidato:**
1. Creare la pagina "Spedizioni"
2. Strutturare il contenuto con H2, elenchi, tabella costi
3. Aggiungere un'immagine o icona
4. Compilare la SEO
5. Pubblicare e verificare il risultato frontend

---

## 2.4 Homepage — la vetrina digitale

### Come funziona

La homepage NON si gestisce come una Page. Si modifica dal **Theme Editor** (personalizzatore del tema):

**Percorso:** Negozio online → Personalizza → seleziona "Home page" nel menu a tendina in alto

### Struttura a sezioni e blocchi

Il tema Shopify organizza la homepage in **sezioni** impilate verticalmente. Ogni sezione contiene **blocchi** configurabili.

```
┌─────────────────────────────────────────┐
│  [SEZIONE] Slideshow / Hero Banner       │  ← Immagine grande + testo + CTA
├─────────────────────────────────────────┤
│  [SEZIONE] Collezioni in evidenza        │  ← 3-4 collezioni con immagine
├─────────────────────────────────────────┤
│  [SEZIONE] Prodotti in evidenza          │  ← Griglia prodotti scelti
├─────────────────────────────────────────┤
│  [SEZIONE] Banner promozionale           │  ← Immagine + testo promo
├─────────────────────────────────────────┤
│  [SEZIONE] Testo con immagine            │  ← USP (spedizione gratuita, resi...)
├─────────────────────────────────────────┤
│  [SEZIONE] Blog / Novità                 │  ← Ultimi 3 articoli del blog
├─────────────────────────────────────────┤
│  [SEZIONE] Newsletter                    │  ← Form iscrizione email
└─────────────────────────────────────────┘
```

### Cosa può fare il team sulla homepage

| Azione | Come |
|--------|------|
| Cambiare immagine del banner/slideshow | Theme Editor → sezione Slideshow → carica nuova immagine |
| Modificare testo e CTA del banner | Theme Editor → sezione Slideshow → campi testo/link |
| Cambiare le collezioni in evidenza | Theme Editor → sezione "Collezioni" → seleziona collezioni diverse |
| Aggiornare i prodotti in evidenza | Theme Editor → sezione "Prodotti" → scegli prodotti/collezione |
| Aggiungere/rimuovere una sezione | Theme Editor → "+ Aggiungi sezione" o icona cestino |
| Riordinare le sezioni | Theme Editor → trascina le sezioni nella sidebar |

### Calendario aggiornamento homepage

| Frequenza | Cosa aggiornare |
|-----------|-----------------|
| Settimanale | Banner hero (promo in corso, novità) |
| Bi-settimanale | Prodotti in evidenza (rotazione) |
| Mensile | Collezioni in evidenza (stagionalità) |
| Stagionale | Layout completo (Natale, Estate, Back to School) |

### Best practice

- **Banner hero:** immagine di alta qualità (1920×800 px min), testo breve (max 8 parole), CTA chiara ("Scopri la collezione", "Acquista ora")
- **Non sovraccaricare:** max 6-8 sezioni in homepage. Meglio poche e curate che tante e confuse
- **Above the fold:** le prime 2 sezioni sono le più importanti — è ciò che il cliente vede senza scrollare
- **Mobile:** verificare SEMPRE l'aspetto mobile (icona telefono nel Theme Editor)

### ⚠️ Attenzione

- Le modifiche nel Theme Editor sono **live** se lavori sul tema pubblicato — usa "Duplica tema" per testare prima
- Le immagini dei banner devono essere ottimizzate (compresse) per non rallentare il caricamento
- Non rimuovere sezioni strutturali senza coordinarsi col team tecnico

### Demo live: modificare la homepage

📋 **Esercizio guidato:**
1. Aprire il Theme Editor sulla homepage
2. Modificare il testo dello slideshow/hero
3. Cambiare una collezione in evidenza
4. Verificare il risultato su mobile
5. Salvare (su tema duplicato per sicurezza)

---

## 2.5 Blog — contenuti per SEO e engagement

### A cosa serve il blog per Giochi3

| Obiettivo | Esempio contenuto |
|-----------|-------------------|
| **Traffico organico (SEO)** | "Migliori giochi per bambini 5 anni: guida 2026" |
| **Supporto alle vendite** | "Come scegliere il primo gioco da tavolo" |
| **Stagionalità** | "Idee regalo Natale per bambini: la guida completa" |
| **Brand awareness** | "Giochi3 apre il 6° punto vendita a Ragusa" |
| **Supporto campagne** | Landing informativa per Google Ads / Social |

### Come si crea un articolo

**Percorso:** Negozio online → Articoli del blog → Aggiungi articolo

| Campo | Cosa compilare |
|-------|---------------|
| **Titolo** | H1 ottimizzato per SEO e click (es. "10 Giochi da Tavolo per Famiglie: la Guida 2026") |
| **Contenuto** | Corpo dell'articolo con H2, H3, immagini, link a prodotti |
| **Immagine in evidenza** | Immagine cover per anteprima (1200×628 px per social sharing) |
| **Autore** | Chi ha scritto l'articolo |
| **Tag articolo** | Per categorizzare (guida, novità, evento, stagionale) |
| **SEO** | Meta title, meta description, URL handle |
| **Pubblicazione** | Data e ora (immediata o programmata) |

### Struttura articolo tipo

```
[H1] Titolo con keyword — generato dal campo Titolo
[Intro] 2-3 frasi che catturano l'attenzione + anticipano il contenuto
[H2] Prima sezione
[Paragrafo + immagine]
[H2] Seconda sezione
[Paragrafo + elenco prodotti consigliati con link]
[H2] Terza sezione
[Paragrafo + tabella comparativa]
[H2] Conclusione / Riepilogo
[CTA] "Scopri tutta la collezione Giochi da Tavolo →" (link a collezione)
```

### Calendario editoriale consigliato

| Frequenza | Tipo | Esempio |
|-----------|------|---------|
| 1/settimana | Guida prodotto | "I migliori giochi da tavolo per famiglie" |
| 2/mese | Lista consigliata | "Top 10 regali Natale bambina 6-8 anni" |
| Mensile | News/evento | "Nuovo punto vendita a Ragusa!" |
| Stagionale | Guida tematica | "Lista nascita completa: cosa non può mancare" |

### SEO per gli articoli blog

- **Keyword research:** prima di scrivere, identifica la keyword target
  - Tool gratuiti: Google Trends, Google Suggest (autocomplete), Answer The Public
- **Titolo:** keyword primaria all'inizio + hook emotivo
  - Es. "Giochi per Bambini 3 Anni: 15 Idee che Adorerà"
- **URL:** breve, con keyword, senza date
  - ✅ `/blogs/guida/giochi-bambini-3-anni`
  - ❌ `/blogs/guida/articolo-giugno-2026-giochi`
- **Meta description:** 155 caratteri con keyword + CTA
- **Immagini:** alt text descrittivo, compresse, nomi file ottimizzati
- **Link interni:** collegare ai prodotti e alle collezioni citate
- **Lunghezza:** minimo 800 parole per articoli SEO, 300+ per news

### Collegare blog e vendite

Il blog non è fine a sé stesso — deve portare verso i prodotti:

1. **Link a prodotti** nel corpo del testo ("Scopri la [Pista Avventura YES TOYS](/products/yes-toys-pista-avventura)")
2. **Link a collezioni** come CTA finale ("Vedi tutti i [Giochi da Tavolo →](/collections/giochi-da-tavolo)")
3. **Sezione "Prodotti correlati"** — se il tema lo supporta, automatizza il cross-selling

### ⚠️ Errori da evitare

- Articoli troppo corti (<300 parole) — non si posizionano
- Nessun link interno ai prodotti — occasione persa di conversione
- Immagine in evidenza mancante — brutta anteprima sui social
- URL cambiati dopo la pubblicazione — link rotti e penalizzazione SEO
- Contenuto duplicato da altre fonti — penalizzazione Google

### Demo live: creare un articolo blog

📋 **Esercizio guidato:**
1. Creare l'articolo "I 5 migliori giochi per bambini 3-5 anni"
2. Strutturare con H2 e almeno un'immagine
3. Inserire 2-3 link a prodotti del catalogo
4. Compilare la SEO completa
5. Programmare la pubblicazione per il giorno successivo

---

---

# RECAP E CHECKLIST OPERATIVA

---

## Cosa avete imparato oggi

✅ Il catalogo arriva dal middleware — voi arricchite, non sostituite  
✅ Le collezioni organizzano il catalogo — automatiche per categorie, manuali per editoriale  
✅ Le pagine collezione hanno bisogno di descrizioni SEO ricche  
✅ Le Pages servono per contenuti istituzionali e di servizio  
✅ La homepage si gestisce dal Theme Editor (sezioni e blocchi)  
✅ Il blog genera traffico organico e supporta le vendite  

---

## Checklist post-lezione — azioni immediate

| # | Azione | Chi | Entro quando |
|---|--------|-----|-------------|
| 1 | Compilare descrizione delle 5 collezioni principali | Category Manager + Marketing | 1 settimana |
| 2 | Creare/aggiornare le Pages essenziali (FAQ, Spedizioni, Resi) | Marketing | 1 settimana |
| 3 | Aggiornare la homepage con banner e collezioni attuali | Marketing | 3 giorni |
| 4 | Pubblicare il primo articolo blog | Marketing | 2 settimane |
| 5 | Verificare alt text sulle immagini dei top 20 prodotti | Category Manager | 2 settimane |

---

## Prossima lezione

**Lezione 2:** Marketing e Promozioni — Codici sconto, sconti automatici, Shopify Email, Automazioni Flow

---

*Documento generato per la Formazione Shopify Giochi3 — Luglio 2026*
