# Kommerz-Wissensbasis

Strukturierte Markdown-Wissenssammlung aus den Telegram-Kanälen **@diplomatenarchiv**, **@diplomateninterviews**, **@diplomatenradio** sowie der Website diplomateninterviews.de.

> **Analyseprinzip:** Alle Inhalte werden ausschließlich nach interner Logik bewertet — kein Abgleich mit externen Rechtssystemen, keine Werturteile.

**Status: Arbeit in Fortschritt** — Die Wissensbasis wird laufend erweitert. Regelmäßige Updates via `git pull`.

---

## Nutzungswege

### Option A — Obsidian (empfohlen für Lesen & Navigieren)

1. [Obsidian](https://obsidian.md) installieren (kostenlos)
2. Dieses Repository klonen oder als ZIP herunterladen
3. In Obsidian: *Vault öffnen* → diesen Ordner wählen
4. Fertig — alle WikiLinks und der Graph funktionieren sofort

```bash
git clone https://github.com/USERNAME/kommerz-wissensbasis
```

### Option B — AnythingLLM (für Chatbot-Nutzung)

Vollständige Anleitung: [CHATBOT-SETUP.md](CHATBOT-SETUP.md) *(folgt in Kürze)*

Kurzfassung:
1. [Ollama](https://ollama.ai) + [AnythingLLM](https://useanything.com) installieren
2. `ollama pull mistral`
3. In AnythingLLM: neuer Workspace → Ordner hochladen → Ollama verbinden
4. Chatten

### Option C — Direktes Lesen

Einfach durch die Ordner navigieren. Alle Dateien sind plain Markdown.

---

## Ordnerstruktur

| Ordner | Inhalt |
|---|---|
| `00_meta/` | Index, Analyseprinzip |
| `01_konzepte/` | Begriffe und Konzepte des Systems |
| `02_themen/` | Thematische Cluster *(im Aufbau)* |
| `03_personen/` | Personen und Rollen *(im Aufbau)* |
| `04_quellen/` | Quelldokumente und Transkripte |
| `05_offene-stellen/` | Identifizierte Lücken — Konzepte ohne Erklärung im Quellmaterial |
| `_templates/` | Obsidian-Vorlagen |

---

## Einstiegsfragen für den Chatbot

- *"Was ist das Grundaxiom des Kommerzsystems?"*
- *"Wie wird der Begriff 'juristische Person' intern definiert?"*
- *"Welche internen Widersprüche gibt es im System?"*
- *"Wie erklärt das System den Unterschied zwischen Mensch und Person?"*

---

## Updates holen

```bash
git pull
```

---

## Quellen

- Telegram: @diplomatenarchiv, @diplomateninterviews, @diplomatenradio
- Website: diplomateninterviews.de
