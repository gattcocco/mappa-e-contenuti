# Resistenze AI

Sito statico che raccoglie e organizza materiale su:

- **Resistenze ai data center** in Italia ed Europa
- **Cause legali** sul copyright contro le aziende AI
- **Ghost workers** dell'IA e organizing dei lavoratori
- **Sindacalismo tech** contro Big Tech
- **AI literacy critica** — libri, podcast, organizzazioni

Include una **mappa interattiva** dei conflitti attivi, ospitata su uMap (OpenStreetMap).

## Come è fatto

- Una sola pagina HTML statica (`index.html`)
- CSS inline, nessuna dipendenza esterna
- Nessun JavaScript, nessun tracker, nessun cookie
- La mappa è incorporata via `iframe` da [umap.openstreetmap.fr](https://umap.openstreetmap.fr)

## Come pubblicarlo su GitHub Pages

1. Crea un repository pubblico su GitHub (es. `resistenze-ai`)
2. Carica `index.html` nella root del repo
3. Vai in **Settings → Pages**
4. Source: **Deploy from a branch** → `main` / `(root)` → Save
5. Dopo qualche minuto il sito è online su `https://<tuo-username>.github.io/resistenze-ai/`

## Come modificarlo

Modifica direttamente `index.html`. È un file lungo ma molto strutturato:
- Le sezioni sono delimitate da commenti HTML chiari (`<!-- ==================== NOME ==================== -->`)
- Lo stile è in `<style>` in alto, una sola palette di colori
- Per aggiungere un caso, copia un blocco `<div class="case">...</div>` e modificalo

## Mappa

La mappa è gestita separatamente su uMap. Per modificarla, vai sull'editor uMap usando l'account che ha creato la mappa.

URL mappa: https://umap.openstreetmap.fr/it/map/resistenze-ai-italia_1401518

## Licenza

Contenuti: [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.it)
Codice: [MIT](https://opensource.org/licenses/MIT)
