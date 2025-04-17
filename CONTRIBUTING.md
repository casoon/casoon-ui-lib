# Beitragen zur CASOON UI Library

Vielen Dank für dein Interesse, zur CASOON UI Library beizutragen! Diese Anleitung hilft dir, unseren Entwicklungsprozess kennenzulernen und zu verstehen, wie du effektiv mitwirken kannst.

## Entwicklungsphilosophie

Die CASOON UI Library verfolgt diese Grundprinzipien:

- **Modularität**: Komponenten sollten unabhängig und wiederverwendbar sein
- **Effizienz**: Optimierung für Performance und LightningCSS
- **Zugänglichkeit**: Alle Komponenten müssen zugänglich und barrierefrei sein
- **Konsistenz**: Einheitliches Design und einheitliche API für alle Komponenten

## Styleguide

### CSS-Konventionen

1. **Verwende logische Eigenschaften**, wenn möglich:
   - `inline-size` statt `width`
   - `block-size` statt `height` 
   - `inline-start` statt `left`/`right` (je nach Sprachrichtung)

2. **CSS-Werte in Kleinbuchstaben**:
   - `optimizespeed` statt `optimizeSpeed`
   - `auto` statt `Auto`

3. **Verwende CSS-Layers korrekt**:
   - `@layer core { ... }` für Kern-Funktionalität
   - Module sollten `.module.css` Dateierweiterung verwenden

4. **CSS-Variablen**:
   - Folge der bestehenden Benennungskonvention (z.B. `--color-primary-500`)
   - Definiere neue Variablen in `layers/tokens.css`
   - Verwende bestehende Variablen, statt neue zu erstellen

### Neue Komponenten

1. **Studiere bestehende Komponenten** vor dem Erstellen neuer
2. **Erstelle ein Modul** in `modules/` mit der Erweiterung `.module.css`
3. **Dokumentiere** mit Kommentaren die Nutzung der Komponente
4. **Füge Varianten** für verschiedene Anwendungsfälle hinzu
5. **Teste** die Komponente in verschiedenen Browsern

## Beitragsprozess

1. **Forke** das Repository
2. **Erstelle einen Feature-Branch**: `git checkout -b feature/neue-komponente`
3. **Entwickle** deine Änderungen
4. **Führe Linting durch**: `npm run lint`
5. **Pushe**: `git push origin feature/neue-komponente`
6. **Erstelle einen Pull Request** mit einer klaren Beschreibung

## Code-Qualität

- **Linting**: `npm run lint` muss ohne Fehler durchlaufen
- **Keine direkten Commits** auf den `main`-Branch
- **Selbstprüfung**: Überprüfe deine Änderungen auf mögliche Fehler vor dem Einreichen

## Pull Requests

Dein Pull Request sollte Folgendes enthalten:

- **Beschreibung** der Änderungen
- **Kontext** warum die Änderungen notwendig sind
- **Screenshots**, wenn visuelle Änderungen vorgenommen wurden
- **Testanweisungen**, wie die Änderungen zu testen sind

## Kontakt

Bei Fragen oder Unklarheiten wende dich bitte an das CASOON-Entwicklungsteam.

## 🚀 Erste Schritte

1. Forken Sie das Repository
2. Klonen Sie Ihren Fork: `git clone https://github.com/ihr-username/casoon-ui-lib.git`
3. Erstellen Sie einen neuen Branch: `git checkout -b feature/ihr-feature-name`

## 📝 Pull Requests

1. Stellen Sie sicher, dass Ihr Code den Styleguide entspricht
2. Fügen Sie Tests für neue Funktionen hinzu
3. Aktualisieren Sie die Dokumentation
4. Beschreiben Sie Ihre Änderungen im Pull Request

## 🎨 Styleguide

### CSS
- Verwenden Sie OpenProps für CSS-Variablen
- Folgen Sie der BEM-Namenskonvention
- Fügen Sie Kommentare für komplexe CSS-Regeln hinzu
- Halten Sie die CSS-Dateien modular und organisiert

### JavaScript/TypeScript
- Verwenden Sie TypeScript für neue Komponenten
- Folgen Sie den ESLint-Regeln
- Fügen Sie JSDoc-Kommentare hinzu
- Halten Sie die Funktionen klein und fokussiert

### Dokumentation
- Aktualisieren Sie die README.md bei relevanten Änderungen
- Fügen Sie Beispiele für neue Funktionen hinzu
- Dokumentieren Sie Breaking Changes

## 🧪 Tests

- Fügen Sie Unit-Tests für neue Funktionen hinzu
- Stellen Sie sicher, dass alle Tests bestanden werden
- Testen Sie in verschiedenen Browsern

## 📚 Dokumentation

- Aktualisieren Sie die Dokumentation bei Änderungen
- Fügen Sie Beispiele hinzu
- Dokumentieren Sie Breaking Changes

## 🐛 Bug Reports

1. Überprüfen Sie, ob der Bug bereits gemeldet wurde
2. Erstellen Sie ein neues Issue
3. Beschreiben Sie den Bug detailliert
4. Fügen Sie Schritte zur Reproduktion hinzu
5. Geben Sie die erwarteten und tatsächlichen Ergebnisse an

## 💡 Feature Requests

1. Überprüfen Sie, ob das Feature bereits vorgeschlagen wurde
2. Erstellen Sie ein neues Issue
3. Beschreiben Sie das Feature detailliert
4. Erklären Sie den Nutzen des Features

## 📝 Commit Messages

- Verwenden Sie aussagekräftige Commit Messages
- Folgen Sie der Konvention: `type(scope): description`
- Beispiele:
  - `feat(animations): add fade-in effect`
  - `fix(grid): correct responsive breakpoints`
  - `docs(readme): update installation instructions`

## 🔄 Workflow

1. Aktualisieren Sie Ihren Fork mit dem Hauptrepository
2. Erstellen Sie einen Feature-Branch
3. Entwickeln Sie Ihre Änderungen
4. Führen Sie Tests durch
5. Erstellen Sie einen Pull Request

## 📞 Support

Bei Fragen oder Problemen:
- Öffnen Sie ein Issue
- Besuchen Sie die [Homepage](https://www.casoon.de)
- Kontaktieren Sie uns über GitHub

## 📝 Lizenz

Mit Ihrem Beitrag stimmen Sie zu, dass Ihre Änderungen unter der MIT-Lizenz veröffentlicht werden.

Vielen Dank für Ihren Beitrag zur Casoon UI Library! 🎉 
