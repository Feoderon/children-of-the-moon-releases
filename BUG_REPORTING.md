# Fehler melden / Report a bug

Dieses Repository verteilt **nur fertige Windows-Spielversionen** von Children of the Moon. Der Godot-Quellcode liegt in einem separaten privaten Repository.

## Für Tester und Brüder

**[🐛 Neuen Bug melden](https://github.com/Feoderon/children-of-the-moon-releases/issues/new?template=bug_report.yml)**

1. Spielversion aus dem Launcher eintragen (z. B. `test-0.11.88`).
2. **Host / Client / beide** angeben.
3. Beschreiben, was passiert, was passieren sollte und wie man den Fehler reproduzieren kann.
4. Optional einen Screenshot, eine Fehlermeldung oder ein Log anhängen.
5. Vorher unter **[offenen Bugs](https://github.com/Feoderon/children-of-the-moon-releases/issues?q=is%3Aissue+is%3Aopen)** prüfen, ob der Fehler schon gemeldet wurde. Bei gleichem Fehler lieber dort kommentieren.

**Datenschutz:** Diese Issues sind öffentlich. Bitte keine Radmin-IP-Adressen, Zugangsdaten, privaten Chatprotokolle, Tokens oder persönlichen Informationen posten.

## Ablauf der Fehlerbehebung

`Gemeldet → geprüft/reproduziert → Fix-Branch im privaten Code-Repo → automatisierte Tests → Experimental-Release → gemeinsam nachtesten → Issue schließen`.

- Dringende Blocker kommen zuerst; reine Grafikfehler später.
- Wenn ein Bug mehrfach auftritt, die Zusatzbeobachtungen im vorhandenen Issue ergänzen.
- Jede Behebung bekommt nach Möglichkeit einen Regressionstest, damit derselbe Fehler bei späteren Updates nicht wiederkommt.
- GitHub Issues sind die zentrale Liste; ein Assistent kann sie bei einer gemeinsamen Entwicklungssitzung lesen, kommentieren und mit Fix-PRs verknüpfen. Eine automatische Überwachung oder selbstständige Bearbeitung ohne gestartete Sitzung ist dadurch **nicht** eingerichtet.
- **Stable** bleibt unverändert, bis ein getesteter Build ausdrücklich freigegeben wird.
