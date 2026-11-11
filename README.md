# filiere.norema.eu · filieraluiss.norema.eu

Dashboard degli Insiemi di progetti per l'Avviso Filiere Tecnologiche (PR FESR Lazio 2021-2027).

- `index.html` → **filiere.norema.eu**: Insieme "Infrastrutture produttive intelligenti" (Soggetto Cardine Tecnopolo).
- `luiss/index.html` → **filieraluiss.norema.eu**: Insieme "AgriTech & AgriFood Resilience Lazio" (Soggetto Cardine LUISS).

Ogni modifica salvata sul ramo `main` viene caricata automaticamente via FTP sui sottodomini.
I file `.htaccess` / `.htpasswd` sul server (protezione con password) non vengono toccati.

Segreti richiesti (Settings → Secrets and variables → Actions):
- `FTP_SERVER` – host FTP (es. ftp.norema.eu)
- `FTP_USERNAME` – utente FTP
- `FTP_PASSWORD` – password FTP
- `FTP_DIR` – cartella di filiere.norema.eu, con barra finale (es. `/filiere.norema.eu/public_html/` oppure `./` se l'account FTP apre già il sottodominio)
- `FTP_DIR_LUISS` – cartella di filieraluiss.norema.eu, con barra finale (es. `/filieraluiss.norema.eu/public_html/`). Deve essere diversa da `FTP_DIR`. Finché manca, la pagina LUISS non viene pubblicata.
- Facoltativi: `FTP_SERVER_LUISS`, `FTP_USERNAME_LUISS`, `FTP_PASSWORD_LUISS`, se il sottodominio LUISS ha un account FTP proprio (altrimenti si usano quelli di filiere.norema.eu).
