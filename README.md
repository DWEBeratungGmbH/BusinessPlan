# DWE & ARCAVIO Businessplan

Eine professionelle Website für den Businessplan von DWE & ARCAVIO - Generalübernehmung für energetische Gebäudesanierung.

## 📋 Über dieses Projekt

Dieses Repository enthält den strukturierten Businessplan der DWE & ARCAVIO, aufgebaut mit MkDocs Material Theme. Die Website bietet eine übersichtliche Darstellung unseres Geschäftsmodells, der Gesellschafterstruktur, Meilensteine und Finanzplanung.

## 🚀 Schnellstart

### Voraussetzungen
- Python 3.8+ installiert
- Git installiert

### Installation

1. **Repository klonen:**
```bash
git clone https://github.com/dwe-arcavio/businessplan.git
cd businessplan
```

2. **Python-Abhängigkeiten installieren:**
```bash
pip install -r requirements.txt
```

3. **Entwicklungsserver starten:**
```bash
mkdocs serve
```

4. **Website öffnen:** http://127.0.0.1:8000

### Website erstellen
```bash
mkdocs build
```

## 📁 Projektstruktur

```
dwe-arcavio-businessplan/
├── mkdocs.yml                    # Hauptkonfiguration
├── requirements.txt              # Python-Dependencies
├── docs/                         # Alle Markdown-Dateien
│   ├── index.md                  # Startseite
│   ├── 01-geschaeftsmodell.md    # Geschäftsmodell
│   ├── 02-gesellschafterstruktur.md
│   ├── 03-meilensteine.md
│   ├── 04-finanzplanung.md
│   └── 05-zielgruppen.md
└── docs/assets/                  # Alle externen Dateien
    ├── images/                   # Logos, Organigramm, Fotos
    ├── tables/                   # CSV-Dateien für Tabellen
    └── charts/                   # SVG/PNG Diagramme
```

## ✏️ Inhalte bearbeiten

### Markdown-Dateien bearbeiten
- Alle Businessplan-Kapitel befinden sich im `docs/` Ordner
- Jede `.md` Datei entspricht einer Website-Seite
- Markdown-Syntax für Formatierung verwenden

### Assets hinzufügen
- **Bilder:** In `docs/assets/images/` speichern
- **Tabellen:** Als CSV in `docs/assets/tables/` speichern
- **Diagramme:** Als PNG/SVG in `docs/assets/charts/` speichern

### Beispiel: Bild einbinden
```markdown
![Firmenschild](assets/images/firmenschild.jpg "DWE & ARCAVIO Firmenschild")
```

### Beispiel: Tabelle aus CSV
```markdown
| Kennzahl | 2026 | 2027 | 2028 |
|----------|------|------|------|
| Umsatz   | 150k | 300k | 500k |
```

## 🚀 Deployment

### GitHub Pages (Automatisch)
1. Code in `main` Branch pushen
2. GitHub Actions erstellt automatisch die Website
3. Website verfügbar unter: https://dwe-arcavio.github.io/businessplan

### Manuelles Deployment
```bash
mkdocs gh-deploy
```

## 🔧 Konfiguration anpassen

- **Website-Titel:** In `mkdocs.yml` unter `site_name`
- **Navigation:** In `mkdocs.yml` unter `nav`
- **Design:** Theme-Einstellungen in `mkdocs.yml`
- **Google Analytics:** Property ID in `mkdocs.yml` unter `extra.analytics`

## 📞 Kontakt

**DWE & ARCAVIO**  
Sebastian Möhrer, Geschäftsführer  
Aachen, Deutschland

---

*Erstellt mit MkDocs Material Theme | © 2025 DWE & ARCAVIO*