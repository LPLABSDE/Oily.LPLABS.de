# 🚗 Oily - Smarte Fahrzeugverwaltung

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Website](https://img.shields.io/badge/Website-online-brightgreen)](https://app.lchandi.de)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/lchandi/app.lchandi.de/graphs/commit-activity)
[![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white)](https://www.w3.org/TR/html52/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

**Moderne Website für die Oily Android App – Wartungstagebuch für Fahzeuge**

[Website besuchen](https://app.lchandi.de) • [App im Play Store](https://play.google.com/store/apps/details?id=de.lchandi.oily) • [Datenschutz](https://app.lchandi.de/datenschutz.html)

</div>

---

## ✨ Highlights

- 🎨 **Modernes Design** mit Glasmorphismus & Animationen
- 📱 **Vollständig Responsive** – Desktop, Tablet, Mobile
- 🌍 **Mehrsprachig** – Deutsch & Englisch
- ⚡ **Blitzschnell** – Statische GitHub Pages
- ♿ **Accessible** – Barrierefreie Navigation
- 🎯 **App-Integration** – Direkter Play Store Link

---

## 🚀 Features

### Website
- **Hero Section** mit ansprechender Willkommensbotschaft
- **App Gallery** mit interaktiven App-Cards
- **App Details Modal** – elegante Modals mit Animationen
- **Mehrsprachige Unterstützung** – DE/EN mit localStorage
- **Rechtliche Dokumente** – Datenschutzerklärung auf separater URL
- **Moderne UI Components** – Glass-Morphism & Gradients

### Oily App Showcase
- 📋 Wartungseinträge einfach protokollieren
- 🔔 Automatische Erinnerungen für Wartungen
- 🚗 Übersicht aller Fahrzeuge
- 📅 TÜV-Termine im Blick
- 📊 Ausführliche Wartungsstatistiken

---

## 📸 Screenshots

```
┌─────────────────────────────────────────┐
│   🏠 Home | 📱 Apps | EN | DE           │
├─────────────────────────────────────────┤
│                                         │
│     Willkommen bei LChandi             │
│                                         │
│     [Oily App Banner Bild]             │
│                                         │
│     Wir entwickeln smarte Lösungen...  │
│                                         │
│     [Unsere Apps entdecken]            │
│                                         │
├─────────────────────────────────────────┤
│   © 2026 LChandi | Datenschutz         │
└─────────────────────────────────────────┘
```

---

## 🛠️ Technologie Stack

| Bereich | Technologie |
|---------|-------------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Design** | Glasmorphismus, CSS Grid, Flexbox |
| **Hosting** | GitHub Pages |
| **Icons** | SVG, Google Fonts (Inter) |
| **Responsive** | Mobile-First Design |

---

## 📁 Projektstruktur

```
app.lchandi.de/
├── index.html              # Hauptseite (Home + Apps + Modal)
├── datenschutz.html        # Deutsche Datenschutzerklärung
├── privacy.html            # Englische Privacy Policy
├── style.css               # Globale Styles
├── CNAME                   # Custom Domain
├── Oily-APP-Banner.png     # App Banner Image
├── Oily-APP-Icon.png       # App Icon
└── README.md               # Diese Datei
```

---

## 🚀 Quick Start

### Lokal testen
```bash
# Repository klonen
git clone https://github.com/lchandi/app.lchandi.de.git
cd app.lchandi.de

# Mit Live Server starten (VS Code Extension empfohlen)
# oder einfach index.html im Browser öffnen
```

### Live auf GitHub Pages
Die Website wird automatisch deployed unter:
```
https://app.lchandi.de
```

---

## ⚙️ Konfiguration

### App-Details ändern (Modal Content)
Bearbeite in `index.html` das `appData`-Objekt:

```javascript
const appData = {
  oily: {
    de: {
      title: 'Oily',
      subtitle: 'Wartungstagebuch für Android',
      description: 'Deine Beschreibung hier...',
      features: [
        'Feature 1',
        'Feature 2',
        // ...
      ]
    }
  }
};
```

### Play Store Link aktualisieren
```html
<!-- In index.html -->
<a href="https://play.google.com/store/apps/details?id=de.lchandi.oily">
  Im Play Store herunterladen
</a>
```

### Farben & Design
Bearbeite `style.css` für Global-Styles:
```css
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --glass-bg: rgba(255, 255, 255, 0.9);
}
```

---

## 🌐 Mehrsprachigkeit

Die Website unterstützt automatisch DE/EN. Neue Sprachen hinzufügen:

```javascript
const translations = {
  de: { /* German translations */ },
  en: { /* English translations */ },
  // Neue Sprache hinzufügen:
  fr: { 
    nav_home: "Accueil",
    nav_apps: "Applications",
    // ...
  }
};
```

---

## 📱 Google Play & App Store Integration

### Play Store Privacy Policy
Google Play verlangt direkten URL-Link zur Datenschutzerklärung:
```
Trage ein: https://app.lchandi.de/datenschutz.html
```

### App Listing
- **App Icon**: `Oily-APP-Icon.png`
- **App Banner**: `Oily-APP-Banner.png`
- **Play Store URL**: https://play.google.com/store/apps/details?id=de.lchandi.oily

---

## 🎨 Design System

### Farben
- **Primär Gradient**: `#667eea → #764ba2`
- **Glas Background**: `rgba(255, 255, 255, 0.9)`
- **Text Primary**: `#1a1a1a`
- **Text Secondary**: `#666`

### Komponenten
- **Glass Cards** – mit Backdrop-Filter Blur
- **Buttons** – mit Hover & Active States
- **Modals** – mit Fade & Slide Animationen
- **Navigation** – Active-State Tracking

---

## ♿ Accessibility

- ✅ Semantisches HTML
- ✅ Alt-Text für alle Bilder
- ✅ Keyboard Navigation (ESC zum Schließen)
- ✅ Color Contrast WCAG AA
- ✅ Responsive Touch Targets

---

## 🔒 Sicherheit

- ✅ HTTPS auf app.lchandi.de (GitHub Pages)
- ✅ Keine externe APIs (nur statische Inhalte)
- ✅ Privacy-First Ansatz
- ✅ Keine Cookies ohne Zustimmung

---

## 📝 Lizenz

Dieses Projekt ist lizenziert unter der **MIT Lizenz** – siehe [LICENSE](LICENSE) Datei für Details.

```
MIT License

Copyright (c) 2026 Lovepreet Chandi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 👨‍💻 Autor

**Lovepreet Chandi**  
🔗 [Website](https://app.lchandi.de)  
📧 [E-Mail](mailto:kontakt@lchandi.de)  
📱 [GitHub](https://github.com/lchandi)

---

## 🤝 Beiträge

Bugfixes und Verbesserungen sind willkommen! 

```bash
# 1. Fork das Repo
# 2. Feature Branch erstellen
git checkout -b feature/meine-verbesserung

# 3. Changes committen
git commit -m "Add: Neue Feature XYZ"

# 4. Branch pushen
git push origin feature/meine-verbesserung

# 5. Pull Request öffnen
```

---

## 📞 Kontakt & Support

| Kanal | Link |
|-------|------|
| **Website** | https://app.lchandi.de |
| **E-Mail** | kontakt@lchandi.de |
| **GitHub Issues** | [Issues öffnen](https://github.com/lchandi/app.lchandi.de/issues) |
| **Play Store** | [Oily App](https://play.google.com/store/apps/details?id=de.lchandi.oily) |

---

## 📊 Stats

[![GitHub stars](https://img.shields.io/github/stars/lchandi/app.lchandi.de?style=social)](https://github.com/lchandi/app.lchandi.de)
[![GitHub forks](https://img.shields.io/github/forks/lchandi/app.lchandi.de?style=social)](https://github.com/lchandi/app.lchandi.de)
[![GitHub watchers](https://img.shields.io/github/watchers/lchandi/app.lchandi.de?style=social)](https://github.com/lchandi/app.lchandi.de)

---

## 📚 Weitere Ressourcen

- 🎨 [Design System Dokumentation](https://app.lchandi.de)
- 📖 [HTML5 Standard](https://www.w3.org/TR/html52/)
- 🎯 [Web Accessibility Guidelines](https://www.w3.org/WAI/)
- 🚀 [GitHub Pages Docs](https://pages.github.com/)

---

<div align="center">

**Gebaut mit ❤️ von Lovepreet Chandi**

[⬆ Nach oben](#-lchandi---smarte-fahrzeugverwaltung)

</div>
