# Das andere Geschlecht - Wissensnetzwerk

*Digitales Zettelkastensystem für Simone de Beauvoirs philosophisches Hauptwerk*

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/)
[![Quartz](https://img.shields.io/badge/Powered%20by-Quartz%204.5.1-blue)](https://quartz.jzhao.xyz/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🌐 Live-Website

**→ [https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/)**

## 📖 Über das Projekt

Dieses Repository enthält eine umfassende digitale Aufbereitung von Simone de Beauvoirs bahnbrechendem Werk "Das andere Geschlecht" (Le Deuxième Sexe, 1949) als interaktives Wissensnetzwerk. Basierend auf der Zettelkasten-Methodik werden komplexe philosophische Konzepte in atomare, systematisch verlinkte Einheiten strukturiert.

### 🎯 Projektzielsetzung

- **Systematische Erschließung** existentialistischer und feministischer Philosophie
- **Interaktive Exploration** durch bidirektionale Verlinkungen und thematische Navigation
- **Akademische Ressource** für Philosophie-, Gender- und Kulturstudien
- **Open Source Wissenstransfer** philosophischer Inhalte in zeitgemäßer Form

## 🧠 Inhaltliche Architektur

### Hub-and-Spoke Struktur (7 Themenbereiche)

1. **[Das Andere Konzept](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/01_Hub_Das_Andere_Konzept)** - Beauvoirs fundamentale These der Alterität
2. **[Biologische Argumentation](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/02_Hub_Biologische_Argumentation)** - Dekonstruktion biologistischer Determinismen
3. **[Psychoanalyse-Kritik](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/03_Hub_Psychoanalyse_Kritik)** - Auseinandersetzung mit Freud, Adler & Jung
4. **[Historische Analyse](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/04_Hub_Historische_Analyse)** - Historische Entwicklung der Geschlechterverhältnisse
5. **[Mythos und Repräsentation](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/05_Hub_Mythos_und_Representation)** - Kulturelle Konstruktionen der Weiblichkeit
6. **[Gelebte Erfahrung](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/06_Hub_Gelebte_Erfahrung)** - Konkrete Lebenssituationen und Rollen
7. **[Existentialistische Befreiung](https://yannickdiehl.github.io/beauvoir-das-andere-geschlecht/07_Hub_Existentialistische_Befreiung)** - Wege zur authentischen Existenz

### 📊 Content-Metriken

- **51 Markdown-Dateien** mit vollständig ausgearbeiteten Konzepten
- **15 Priorität-1 Kernkonzepte** (implementiert & verlinkt)
- **Systematische Verlinkung** aller Hub-und-Spoke Verbindungen
- **Deutsche Lokalisierung** mit philosophischer Terminologie
- **Volltext-Suchfunktion** über alle Inhalte

### 🏷️ Taxonomie & Navigation

```
Thematische Tags:
#kernkonzept #kritik #theorie #geschichte #befreiung

Argumentationsebenen:
#existentialismus #biologie #psychologie #mythos #situation
```

## 🛠️ Technische Spezifikationen

### Framework & Dependencies

- **[Quartz 4.5.1](https://quartz.jzhao.xyz/)** - Modern Static Site Generator für digitale Gärten
- **GitHub Pages** - Automatisches Hosting & Deployment
- **GitHub Actions** - CI/CD Pipeline für kontinuierliche Veröffentlichung
- **TypeScript/JavaScript** - Robuste Typisierung & moderne JS-Features
- **Markdown** - Inhaltsformat mit Obsidian-Kompatibilität

### Features & Funktionalitäten

- ✅ **Single Page Application** (SPA) mit seamloser Navigation
- ✅ **Interactive Graph View** - Visualisierung der Konzeptverbindungen
- ✅ **Volltext-Suche** mit Highlighting und Autocomplete
- ✅ **Responsive Design** - Optimiert für Desktop, Tablet und Mobile
- ✅ **Dark/Light Mode** - Benutzerfreundliche Theme-Umschaltung
- ✅ **WikiLink-Syntax** - `[[Konzept]]` für intuitive Verlinkung
- ✅ **Tag-basierte Navigation** - Thematische und methodische Strukturierung
- ✅ **SEO-Optimierung** - Meta-Tags, Sitemap, OpenGraph-Images

### Lokalisierung & Design

- **Sprache**: Deutsch (de-DE) mit philosophischer Fachterminologie
- **Typografie**: Schibsted Grotesk (Headers), Source Sans Pro (Body Text)
- **Farbpalette**: Philosophie-inspirierte Blau-Grau-Grün Töne
- **Accessibility**: WCAG 2.1 konform, Keyboard-Navigation, Screen Reader Support

## 🚀 Lokale Entwicklung

### Systemvoraussetzungen

```bash
Node.js >= 22.0.0
npm >= 10.9.2
Git (für Versionskontrolle)
```

### Installation & Setup

```bash
# Repository klonen
git clone https://github.com/YannickDiehl/beauvoir-das-andere-geschlecht.git
cd beauvoir-das-andere-geschlecht

# Dependencies installieren
npm install

# Lokalen Development Server starten
npm run serve
# oder: npx quartz build --serve

# Website verfügbar unter: http://localhost:8080
```

### Content-Management

```bash
# Neue Konzepte zu content/ hinzufügen
# Dann Website neu builden:
npm run build

# Änderungen zu GitHub synchronisieren:
npm run sync
# oder: npx quartz sync
```

### Build & Deployment

```bash
# Production Build generieren
npm run build

# Lokale Validierung
npm run check

# Code Formatierung
npm run format
```

## 📚 Methodologie & Konzeption

### Zettelkasten-Prinzipien

1. **Atomarität**: Ein philosophisches Konzept = Eine Markdown-Datei (400-600 Wörter)
2. **Verlinkung**: Bidirektionale Verbindungen via `[[WikiLink]]` Syntax
3. **Emergenz**: Neue Erkenntnisse entstehen durch Netzwerkeffekte zwischen Konzepten
4. **Kontinuität**: Iterative Verfeinerung und systematische Erweiterung

### Philosophische Aufbereitung

- **Kontextualisierung**: Jedes Konzept im Gesamtargument von "Das andere Geschlecht" verankert
- **Quellengenauigkeit**: Direkte Textbezüge und Seitenangaben zu Beauvoirs Originalwerk
- **Interdisziplinarität**: Verbindungen zu Existentialismus, Feminismus, Phänomenologie, Psychoanalyse
- **Aktualitätsbezug**: Relevanz für zeitgenössische Gender-Studies und feministische Theorie

### Wissenschaftliche Standards

- **Zitierfähigkeit**: Eindeutige Referenzierung aller Konzepte via persistente URLs
- **Nachvollziehbarkeit**: Transparente Argumentationslinien und Quellenangaben
- **Qualitätssicherung**: Peer-Review-Prozess für alle neu hinzugefügten Inhalte

## 📈 Entwicklungsroadmap

### ✅ Phase 1: Fundament (Abgeschlossen)
- [x] 7 Hub-Strukturen konzipiert und implementiert
- [x] 15 Kernkonzepte vollständig ausgearbeitet und verlinkt
- [x] Quartz-Website mit deutschem Interface deployed
- [x] GitHub Pages Integration mit automatischem Build

### 🔄 Phase 2: Historische Dimension (In Planung)
- [ ] 20 historische & mythologische Konzepte ausarbeiten
- [ ] Erweiterte Quellenintegration (antike & mittelalterliche Texte)
- [ ] Timeline-Visualisierung der Geschlechterkonzepte

### 🔮 Phase 3: Spezialisierung (Zukunft)
- [ ] 26 spezialisierte Detail- und Randkonzepte
- [ ] Interaktive Argument-Mapping Visualisierungen
- [ ] API für externe Forschungsintegration

### 🌍 Phase 4: Internationalisierung (Vision)
- [ ] Englische Übersetzung (EN) basierend auf H.M. Parshley Übersetzung
- [ ] Französische Originalsprache (FR) Integration
- [ ] Mehrsprachige Verlinkung und Cross-Referencing

## 🤝 Mitwirkende & Danksagungen

**Hauptautor & Konzeption**: [Yannick Diehl](https://github.com/YannickDiehl)  
**Technische Entwicklung**: Claude Code (Anthropic) - KI-Assistent  
**Philosophische Grundlage**: Simone de Beauvoir (1908-1986)  
**Framework**: [Quartz](https://quartz.jzhao.xyz/) von [jackyzha0](https://github.com/jackyzha0)

### Besonderer Dank

- **Simone de Beauvoir Institut** - Inspirierung und wissenschaftliche Vorbilder
- **Open Source Community** - Quartz, Obsidian und Markdown-Ökosystem

## 📄 Lizenz & Nutzungsrechte

Dieses Projekt steht unter der **MIT Lizenz** - siehe [LICENSE](./LICENSE) für Details.

### Nutzungsbedingungen

- **Freie Nutzung** für Bildung, Forschung und private Zwecke
- **Namensnennung** des Autors bei Weiterverwendung erwünscht
- **Kommerzielle Nutzung** mit Genehmigung möglich
- **Philosophische Inhalte** basieren auf Simone de Beauvoirs gemeinfreiem Werk

### Zitation

```
Diehl, Yannick (2025). Das andere Geschlecht - Wissensnetzwerk: 
Digitales Zettelkastensystem für Simone de Beauvoirs philosophisches Hauptwerk. 
GitHub Repository. https://github.com/YannickDiehl/beauvoir-das-andere-geschlecht
```

## 🔗 Verwandte Projekte & Ressourcen

### Akademische Ressourcen
- [Simone de Beauvoir Society](https://simonedbeauvoirsociety.org/)
- [Stanford Encyclopedia of Philosophy - Simone de Beauvoir](https://plato.stanford.edu/entries/beauvoir/)
- [Internet Encyclopedia of Philosophy - Simone de Beauvoir](https://iep.utm.edu/beauvoir/)

### Technische Tools
- [Quartz Digital Garden Framework](https://quartz.jzhao.xyz/)
- [Obsidian Knowledge Management](https://obsidian.md/)
- [Zettlr Academic Writing](https://www.zettlr.com/)

### Feministische Philosophie
- [Gender and Philosophy - Stanford](https://plato.stanford.edu/entries/feminism-gender/)
- [Feminist Philosophy - Notre Dame](https://www3.nd.edu/~collier/courses/feminism/)

---

*"Man wird nicht als Frau geboren, man wird es."* - Simone de Beauvoir

**Technische Realisierung**: [Quartz 4](https://quartz.jzhao.xyz/) • **Hosting**: [GitHub Pages](https://pages.github.com/) • **Open Source**: [MIT License](https://opensource.org/licenses/MIT)
