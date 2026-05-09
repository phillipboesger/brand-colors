# Bösger Digital – Brand Colors

Eine interaktive Brand-Identity-Seite für **Bösger Digital**, erreichbar unter [colors.boesger.com](https://colors.boesger.com).

## Inhalt

Die Seite dokumentiert die visuelle Identität von Bösger Digital und enthält:

- **Farbpalette** – Alle Brand-Farben mit HEX-Werten, klickbar zum Kopieren in die Zwischenablage
- **Hintergründe** – Abgestufte Hintergrundfarben von Deep bis Elevated
- **Akzentfarben** – Primäre Cyan-Akzente und deren Varianten
- **Typografie** – Schriftfamilien und -größen
- **Assets** – Logos und weitere Markenmaterialien zum Download

## Farbpalette

| Token | HEX | Verwendung |
|---|---|---|
| `--bg-deep` | `#000D1C` | Tiefstes Hintergrundlevel |
| `--bg-base` | `#001222` | Basishintergrund |
| `--bg-surface` | `#062237` | Kartenoberflächen |
| `--bg-elevated` | `#124061` | Erhöhte Elemente |
| `--accent` | `#01BFFB` | Primärfarbe / CTA |
| `--accent-light` | `#6BDFF1` | Heller Akzent |
| `--accent-deep` | `#058FC1` | Dunklerer Akzent |
| `--accent-muted` | `#336D91` | Gedämpfter Akzent / Labels |
| `--text-primary` | `#FFFFFF` | Primärer Text |
| `--text-body` | `#C0F6FC` | Fließtext |
| `--text-muted` | `#336D91` | Sekundärer Text |

## Nutzung

Die gesamte Seite besteht aus einer einzigen `index.html`-Datei – kein Build-Prozess, keine Abhängigkeiten.

```bash
# Lokal öffnen
open index.html

# Oder mit einem einfachen HTTP-Server
npx serve .
```

## Deployment

Die Seite wird über **GitHub Pages** bereitgestellt. Der CNAME `colors.boesger.com` ist in der Datei `CNAME` konfiguriert.

Änderungen am `main`-Branch werden automatisch veröffentlicht.

## Lizenz

© Bösger Digital. Alle Rechte vorbehalten.
