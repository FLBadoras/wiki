# Contributing

Mitwirken an diesem Wiki ist erwünscht und gern gesehen! Dieses Wiki ist für
unsere Spielerschaft gedacht, und darf entsprechend hier mitentwickelt werden.

Im Folgenden sind ein paar Informationen dazu zu finden, was man dabei sinnvoll
beachten kann.

## Allgemeines

### Einbringen von Improvements

Ihr könnt auf [Github](https://github.com/FLBadoras/wiki) einfach Dateien
abändern. Dabei müsst ihr wahrscheinlich "das Repository forken" und
anschließend "eine Pull Request öffnen". Keine Panik, da passiert nichts
schlimmes.

Falls das zu kompliziert ist, könnt ihr einfach eine [Issue
erstellen](https://github.com/FLBadoras/wiki/issues/new) und euren Vorschlag
beschreiben.

### Lokal testen

Um Änderungen lokal zu testen, kann man sich an dem folgenden
[Github-Guide](https://docs.github.com/de/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll?platform=linux)
orientieren.

Lokales Testen ist sehr gerne gesehen, aber kein zwingendes Muss.

## Spezielle Anforderungen

### Einträge zu Commands

Möchte man einen Command im Wiki auflisten, so ist dies unter `_commands`
möglich. Dort erstellt man eine Markdown-Datei, die wie der Command heißt, z.B.
`willkommen.md`. Dabei ist `.md` die Dateiendung für Markdown-Dateien.

Die Datei sollte wie folgt aufgebaut sein:

```md
---
command: #Required, name of the command
description: #Required, description of the command
aliases: #Optional, list of aliases for that command
system: #Optional, names the associated system
layout: default
---
Beschreibung des Commands
```

Commits sollten mit dem Schlüsselwort `[CMD]` beginnen. Hier ein paar Beispiele:

- `[CMD] Added /willkommen`: Dieser Commit fügt dem Wiki den Command
  `/willkommen` hinzu. Die Datei heißt vermutlich willkommen.md
- `[CMD] Updated /willkommen`: Der Eintrag `willkommen.md` wurde aktualisiert.

### Einträge zu Teammitgliedern

Einträge zu Teammitgliedern können unter `_team_members` erstellt werden. Eine
Datei sollte dabei wie folgt aufgebaut sein:

```md
---
name: #Required, name of the team member.
section: #Required, must be one of the following: misc, admin, team, support
position: #Required, concrete position of the team member, e.g. "Architekt"
responsibilities: #Optional, a list of direct responsibilities of that person
contributions: #Optional, a list of projects that person contributes to
---
Eigener Text des Teammitglieds. Hier kann Markdown in jeglicher Hinsicht mit
Ausnahme von Überschriften verwendet werden.
```

Die Datei sollte nach folgendem Schema benannt werden:

1. Zunächst eine Ziffer im Sinne des `section`-Eintrages:
| `section` | Ziffer |
| ---- | ---- |
| admin | `1` |
| team | `2` |
| support | `3` |
| help | `4` |
2. Der Ziffer folgt ein Bindestrich...
3. ... sowie der Name des Teammitglieds.
4. Anschließend muss man noch die Dateiendung `.md` ergänzen.

Hier ein beispielhaftes Team mit den zugehörigen Dateinamen:
| Name | `section` | Dateiname |
| ---- | --------- | --------- |
| hubsi_hd | `misc` | `0-hubsi_hd.md` |
| habicht_XD | `admin` | `1-habicht.md` |
| xXmarcelXx_YT_HD | `admin` | `1-xXmarcelXx_YT_HD.md` |
| caaaarl | `team` | `2-caaaarl.md` |
| carsten | `team` | `2-carsten.md` |
| gustav | `support` | `3-gustav.md` |
