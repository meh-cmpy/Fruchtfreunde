# 🍹 Fruchtfreunde – fruchtfreunde.info

GitHub Pages Landing Page für das Smoothie Catering der Fruchtfreunde (Teil von BNP Eventservice).

---

## 🚀 Setup: GitHub Pages + Custom Domain

### Schritt 1 – Repository anlegen

1. Gehe zu [github.com](https://github.com) und logge dich ein
2. Klick oben rechts auf **„+"** → **„New repository"**
3. Name: `fruchtfreunde` (oder `fruchtfreunde.info`)
4. Auf **„Public"** stellen
5. Klick **„Create repository"**

---

### Schritt 2 – Datei hochladen

1. Im neuen Repo auf **„Add file"** → **„Upload files"** klicken
2. Die `index.html` aus diesem Ordner hochladen
3. Unten auf **„Commit changes"** klicken

---

### Schritt 3 – GitHub Pages aktivieren

1. Im Repo oben auf **„Settings"** klicken
2. Links im Menü: **„Pages"**
3. Unter **„Branch"**: `main` auswählen, Ordner `/root (/)` lassen
4. Klick **„Save"**
5. GitHub generiert jetzt eine URL wie: `https://deinusername.github.io/fruchtfreunde`

---

### Schritt 4 – Custom Domain `fruchtfreunde.info` verknüpfen

**Bei deinem Domain-Anbieter (z. B. IONOS, Namecheap, etc.):**

DNS-Einträge setzen:

| Typ | Name | Wert |
|-----|------|------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | deinusername.github.io |

**In GitHub Pages Settings:**

1. Unter **„Custom domain"** → `fruchtfreunde.info` eintragen
2. **„Enforce HTTPS"** aktivieren (erscheint nach ein paar Minuten)

DNS-Propagation dauert bis zu 24h – danach ist `fruchtfreunde.info` live. ✅

---

## 📁 Dateistruktur

```
fruchtfreunde/
├── index.html        ← Die komplette Website (eine Datei, alles drin)
└── README.md         ← Diese Anleitung
```

Fotos später einbinden: Bilder einfach ins Repo hochladen und in der `index.html` verlinken, z. B.:

```html
<img src="team-mike.jpg" alt="Mike" />
```

---

## ✏️ Häufige Änderungen

**Anfrage-Link anpassen** – aktuell zeigt alles auf `bnp-eventservice.de/anfrage`.  
Sobald `fruchtfreunde.info` ein eigenes Kontaktformular haben soll, einfach die `href`-Links in der `index.html` tauschen.

**Team-Fotos einbauen** – die drei Team-Cards in der `index.html` suchen (Sektion `id="team"`) und die Emoji-Avatare durch `<img>`-Tags ersetzen.

**Preise updaten** – alle Paketpreise stehen in der Sektion `id="pakete"` gebündelt.

---

## 🔗 Verbindung zu BNP Eventservice

Die Fruchtfreunde sind das Smoothie-Catering-Konzept von BNP Eventservice.  
Alle Anfragen laufen aktuell über: [bnp-eventservice.de/anfrage](https://www.bnp-eventservice.de/anfrage)

Schwester-Projekt: **Cocktailfreunde** (Cocktail Catering, ebenfalls BNP)
