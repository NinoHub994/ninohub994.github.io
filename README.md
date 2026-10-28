# Sito personale di Antonino Pirri

Sito statico pubblicato con GitHub Pages. Non richiede build o dipendenze:
la pagina iniziale è `index.html` e la policy privacy è `privacy.html`.

## Pubblicazione su GitHub Pages

Il workflow in `.github/workflows/pages.yml` pubblica automaticamente il
contenuto della repository quando viene aggiornato il branch `main`.

1. Crea una repository GitHub e pubblica il branch `main`.
2. Nelle impostazioni della repository, apri **Pages** e seleziona
   **GitHub Actions** come sorgente di pubblicazione.
3. Al termine del workflow, GitHub mostrerà l'indirizzo del sito nella
   sezione **Pages**.

Per un sito personale all'indirizzo `https://<utente>.github.io/`, la
repository deve chiamarsi `<utente>.github.io`. Per un sito di progetto,
l'indirizzo predefinito è `https://<utente>.github.io/<repository>/`.
