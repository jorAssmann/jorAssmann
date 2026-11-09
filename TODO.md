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
- [x] Commit-Adresse im Konto prüfen
- [x] Erster Commit, Repo `jorAssmann/jorAssmann` öffentlich anlegen (docs/ANLEITUNG.md)
- [x] KOI_TOKEN anlegen (nur Metadata: Read) und als Secret hinterlegen, ggf. Freigabe Org-Admin
- [x] Workflow „Koi“ manuell starten, Log prüfen: keine Warnung, Sprachen erscheinen
- [x] Workflow „Prüfen“ grün
- [ ] Nach einigen Tagen: Größe und Trend plausibel?

## Etappe 2a: Feinschliff ✔
- [x] Becken im Breitformat 840 × 270, füllt die README-Breite
- [x] Beschriftung: Contributions der letzten 30 Tage statt des Jahres
- [x] Profiltext oberhalb des Koi: „Das ist mein Contribution-Koi“
- [x] Schwimmroute statt fester Runde: umherziehen, ausruhen, am Rand verharren und wenden
      (übernommen aus dem privaten Repo)

## Entscheidungen
- **Keine Sprachfarben aus Firmen-Repos** (9. 11. 2026): Mit „Private contributions“ zählen
  die Org-Commits für die Größe, die API liefert sie aber nur als anonyme Summe ohne Repo,
  auch mit vollen Rechten. Farben bräuchten eigenen Abfragecode und einen Org-Token mit
  Lesezugriff auf Firmencode als Secret im öffentlichen Repo. Nutzen (Farbflecken) zu klein
  für Aufwand und Risiko.

## Später
- [ ] Private Kopie: frisch ohne Historie nach `~/Projekte/privat/github-koi`, Repo `<privater-name>/<privater-name>`
      (vorher: Okay der Führungskraft, ggf. MIT-Lizenz im Firmen-Repo; privaten Benutzernamen erfragen)
- [ ] `vergabeRadar`: Commits laufen über das private Konto `reischassmann-boop` und zählen
      nicht für `jorAssmann`; Identität im Firmenordner umstellen (Skill `git-workflow`)
- [ ] Ähnliche Sprachfarben (Python/TypeScript sind beide blau) unterscheidbarer machen
