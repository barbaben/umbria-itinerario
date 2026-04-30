# Mappa itinerario Umbria - GitHub Pages

Questa cartella è pronta per essere pubblicata su **GitHub Pages**.

## Contenuto
- `index.html` → pagina principale della mappa interattiva

## Pubblicazione rapida

### Metodo 1: repository dedicato
1. Crea un nuovo repository su GitHub, ad esempio `umbria-itinerario`.
2. Carica il file `index.html` nella root del repository.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, scegli:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Salva e attendi la pubblicazione.
6. Il sito sarà disponibile su un URL del tipo:
   `https://TUO-USERNAME.github.io/umbria-itinerario/`

### Metodo 2: sito utente/organizzazione
Se vuoi pubblicarlo come sito principale GitHub Pages:
1. Crea un repository chiamato `TUO-USERNAME.github.io`
2. Carica `index.html` nella root
3. GitHub Pages lo pubblicherà all'indirizzo:
   `https://TUO-USERNAME.github.io/`

## Come incorporarlo in Notion
1. Dopo la pubblicazione, copia l'URL pubblico della pagina.
2. In Notion digita `/embed`.
3. Incolla il link GitHub Pages.
4. Ridimensiona il blocco per vedere meglio la mappa.

## Nota tecnica
La pagina usa librerie caricate da CDN pubblici:
- Leaflet per la mappa
- OpenStreetMap per le tile
- Fontshare per i font

Quindi non richiede build, framework o dipendenze locali.
