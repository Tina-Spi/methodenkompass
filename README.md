# ⬡ MethodenKompass

**KI-gestützte Unterrichtsplanung für Lehrpersonen** – findet passende Methoden für jede Phase Ihrer Unterrichtseinheit.

---

## 🚀 Deployment auf GitHub Pages (Schritt für Schritt)

### Schritt 1 – GitHub-Repository erstellen

1. Gehen Sie auf [github.com](https://github.com) und melden Sie sich an (oder registrieren Sie sich kostenlos)
2. Klicken Sie oben rechts auf das **+** → **New repository**
3. Geben Sie als Repository-Name ein: `methodenkompass`
4. Wählen Sie **Public** (erforderlich für den kostenlosen GitHub Pages-Plan)
5. Klicken Sie auf **Create repository**

---

### Schritt 2 – Datei hochladen

1. Im neu erstellten Repository klicken Sie auf **Add file** → **Upload files**
2. Ziehen Sie die Datei `index.html` in das Upload-Fenster
3. Klicken Sie unten auf **Commit changes**

---

### Schritt 3 – GitHub Pages aktivieren

1. Im Repository klicken Sie oben auf **Settings**
2. Im linken Menü unter **Code and automation** → **Pages**
3. Unter **Source** wählen Sie:
   - Branch: `main`
   - Ordner: `/ (root)`
4. Klicken Sie auf **Save**

---

### Schritt 4 – Ihre App aufrufen

Nach ca. 1–2 Minuten ist Ihre App erreichbar unter:

```
https://IHR-BENUTZERNAME.github.io/methodenkompass/
```

*(Ersetzen Sie `IHR-BENUTZERNAME` durch Ihren GitHub-Benutzernamen)*

GitHub zeigt Ihnen die URL auch direkt auf der Pages-Einstellungsseite an (grüner Banner).

---

## 🔑 API-Key einrichten

1. Öffnen Sie die App im Browser
2. Beim ersten Start öffnet sich automatisch das **API-Key-Fenster**
3. Holen Sie sich Ihren Anthropic API-Key unter:
   👉 [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
4. Fügen Sie den Key ein (beginnt mit `sk-ant-...`) und klicken Sie **Speichern**

> **Sicherheit:** Der API-Key wird ausschließlich in Ihrem Browser (`localStorage`) gespeichert und **nie** an Dritte übertragen. Jede Person, die die App nutzt, muss ihren eigenen Key eingeben.

---

## 💶 Kosten

| Nutzung | Kosten (ca.) |
|---------|-------------|
| 1 Unterrichtsplanung | ~ 0,2–0,5 Cent |
| 100 Planungen/Monat | ~ 20–50 Cent |

Anthropic bietet bei der Registrierung ein **kostenloses Startguthaben** an.

---

## 🛠️ Funktionen

- **3 didaktische Phasenvorlagen**: 4-Phasen-Modell, Einstieg–Kern–Schluss, 5E-Modell
- **Frei konfigurierbare Phasen**: Namen, Dauer und Beschreibung anpassbar
- **KI-Methodenempfehlungen** für jede Phase: je 2–3 Methoden mit Begründung, Ablauf, Materialien, Zeitaufwand und Differenzierungsvarianten
- **Sozialform-Präferenzen** beeinflussen die Empfehlungen
- **Export** der Planung als `.txt`-Datei

---

## 📁 Dateistruktur

```
methodenkompass/
└── index.html   ← Die gesamte App (HTML + CSS + JS in einer Datei)
```

---

## 🔧 Lokale Nutzung (ohne GitHub)

Für die lokale Nutzung benötigen Sie einen kleinen Webserver (wegen CORS-Einschränkungen im Browser):

```bash
# Im Ordner mit der index.html:
python -m http.server 8080

# Dann im Browser aufrufen:
http://localhost:8080
```

---

## 📄 Lizenz

MIT – frei verwendbar und anpassbar für schulische und private Zwecke.
