# TODO

## Etappe 1: Koi verfeinert und geprüft ✔
- [x] Wachstum aus regelmäßiger Aktivität (365 Tage, Halbwertszeit 30 Tage), schrumpft in Pausen
- [x] Farben aus den Commits der letzten 90 Tage, gewichtet nach Sprachanteil
- [x] Lebensphase und Trend in der Beschriftung
- [x] KOI_TOKEN für private Repos, Rückfall auf GITHUB_TOKEN bei Ablauf
- [x] Projekt nach Hausstandard: uv, ruff, pyright strict, pytest, CI
- [x] Sichttest aller Lebensphasen, Echtlauf gegen die API
- [x] Review: Stichtag = gestern, Teilfehler der API, Wiederholung bei Netzabbruch, Farbprüfung
- [x] Neuer Look: Schwimmwelle, Koi-Silhouette, Schuppen, Schleierschwanz, Seerose mit Blüte
- [x] Review des Zeichencodes: glatte Bahn, Safari-sicherer Zuschnitt, gestuftes Wachstum, Tests

## Etappe 2: Online bringen
- [ ] Commit-Adresse im Konto prüfen
- [ ] Erster Commit, Repo `jorAssmann/jorAssmann` öffentlich anlegen (docs/ANLEITUNG.md)
- [ ] KOI_TOKEN anlegen (nur Metadata: Read) und als Secret hinterlegen, ggf. Freigabe Org-Admin
- [ ] Workflow „Koi“ manuell starten, Log prüfen: keine Warnung, Sprachen erscheinen
- [ ] Workflow „Prüfen“ grün
- [ ] Nach einigen Tagen: Größe und Trend plausibel?

## Später
- [ ] Private Kopie: frisch ohne Historie nach `~/Projekte/privat/github-koi`, Repo `<privater-name>/<privater-name>`
      (vorher: Okay der Führungskraft, ggf. MIT-Lizenz im Firmen-Repo; privaten Benutzernamen erfragen)
- [ ] Ähnliche Sprachfarben (Python/TypeScript sind beide blau) unterscheidbarer machen
- [ ] Profiltext oberhalb des Koi in README.md ausformulieren
