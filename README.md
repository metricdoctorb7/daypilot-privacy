# DAYPILOT — Informativa privacy per GitHub Pages

Questa cartella contiene la pagina HTML della privacy policy di DAYPILOT e le istruzioni per pubblicarla gratuitamente con GitHub Pages.

## Prima di pubblicare (importante)

1. Apri `index.html` e cerca:
   `[STEFANO MANTICA / Proprietario e Sviluppatore dell'app DAYPILOT]`
2. Sostituisci il testo con il tuo nome e cognome reale oppure con la denominazione legale del titolare.
3. Rileggi tutta l'informativa e verifica che corrisponda alla versione effettiva di DAYPILOT, incluse eventuali librerie o servizi aggiunti in futuro.
4. Salva il file.

Non pubblicare la pagina con il segnaposto ancora presente. Questo documento è una bozza informativa basata sull'ispezione del progetto fornito, non una consulenza legale né una garanzia di conformità a Google Play o al GDPR.

## Pubblicazione con GitHub Pages

1. Accedi a https://github.com con l'account `metricdoctorb7`.
2. Premi `+` in alto a destra e scegli `New repository`.
3. Nome repository: `daypilot-privacy`.
4. Imposta il repository su `Public` e crealo. Non è necessario caricare l'intero progetto Android.
5. Nella pagina del repository scegli `Add file` → `Upload files`.
6. Carica `index.html` e `.nojekyll` (puoi caricare anche questo README, se vuoi).
7. Premi `Commit changes`.
8. Apri `Settings` → `Pages`.
9. In `Build and deployment`, seleziona `Deploy from a branch`.
10. Seleziona branch `main` e cartella `/(root)`, quindi salva.
11. Attendi la pubblicazione e apri l'indirizzo mostrato nella sezione Pages. Di norma sarà:
    `https://metricdoctorb7.github.io/daypilot-privacy/`
12. Apri il link in una finestra anonima per verificare che sia accessibile senza login.

La pubblicazione può richiedere alcuni minuti. Non considerare il sito pubblicato finché GitHub Pages non mostra il link e la pagina non si apre pubblicamente.

## Note

- Il repository deve essere pubblico con il piano GitHub Free per usare Pages.
- Non inserire password, token, chiavi private, file APK o dati personali degli utenti nel repository.
- In seguito, Google Play richiede anche di inserire il link della privacy policy in Play Console e, per app che trattano dati sensibili come la posizione, di rendere la policy accessibile dall'app stessa. Verifica i requisiti correnti prima della pubblicazione.
