# TALIA – WordPress-Plugins

Quellcode der eigenen WordPress-Plugins für [talia-solutions.de](https://talia-solutions.de).

## Struktur

```
plugins/
  talia-prozess/     Prozess-Plugin
  <konsole>/         Konsole
  <kundenportal>/    Kundenportal
```

Jeder Ordner unter `plugins/` entspricht einem Ordner in `wp-content/plugins/` auf dem Server.

## Regeln

- Keine Zugangsdaten, `wp-config.php` oder Datenbank-Dumps committen.
- FTP/SFTP-Zugangsdaten für das Deployment liegen ausschließlich als GitHub-Secrets vor.
