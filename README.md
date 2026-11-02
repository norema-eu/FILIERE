# filiere.norema.eu

Pagina "Filiera Infrastrutture Intelligenti" (Avviso Filiere Tecnologiche, PR FESR Lazio 2021-2027).

Ogni modifica salvata sul ramo `main` viene caricata automaticamente via FTP sul sottodominio.
I file `.htaccess` / `.htpasswd` sul server (protezione con password) non vengono toccati.

Segreti richiesti (Settings → Secrets and variables → Actions):
- `FTP_SERVER` – host FTP (es. ftp.norema.eu)
- `FTP_USERNAME` – utente FTP
- `FTP_PASSWORD` – password FTP
- `FTP_DIR` – cartella del sottodominio, con barra finale (es. `/filiere.norema.eu/public_html/` oppure `./` se l'account FTP apre già il sottodominio)
