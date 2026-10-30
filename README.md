# Diario — task e impegni

Il diario di Simone Maria Gervasoni, in una forma che non dipende da nessun servizio:
una pagina HTML autonoma e un file di dati in formato aperto, ospitati in questo repository GitHub.

## Come si usa

- **Dal repository**: scarica o clona il repository e apri `index.html` nel browser. Funziona offline, senza account e senza server: i dati sono incorporati nella pagina e in `data.json`.
- **Online (opzionale)**: se attivi GitHub Pages (Settings → Pages → branch `main`, cartella `/`), la pagina è raggiungibile a un indirizzo web tuo e legge `data.json` direttamente dal repository.

## I dati

- `data.json` è la fonte canonica: task, routine e registro, in JSON leggibile e modificabile a mano.
- Nella pagina puoi spuntare i task, aggiungerne di nuovi e importare/esportare `data.json`.
  Le modifiche fatte nel browser restano nel browser (localStorage); per renderle definitive,
  usa **Esporta** e sostituisci `data.json` nel repository con il file scaricato.
- Struttura di `data.json`: `tasks` (id, title, date, time, detail, category, kind, done, done_at),
  `routines` (title, cadence, detail), `log` (date, text).

## Storia

Creato il 30 ottobre 2026 esportando il diario tenuto fino a quel giorno dentro Muse,
su richiesta di Simone: il diario doveva essere una cosa vera, sua, che resta anche
cambiando strumenti. Questa copia è indipendente: Muse non serve per leggerla o usarla.
