# 50 AI Asset Pipelines für Google Ads (Make.com Blueprints)

> **Automatisierte Creative-Expansion, 25 Copywriting-Hook-Frameworks & Conversion-Wert-Maximierung für Google Ads (Performance Max & Responsive Suchanzeigen)**

Dieses Repository enthält **50 produktionsbereite Make.com (Integromat) Blueprints**, die speziell entwickelt wurden, um KI-gestützte Anzeigenalternativen für Google Ads zu generieren, zu validieren und über die Google Ads API hochzuladen.

---

## Zweck & Funktionsweise

### 1. Algorithmisches Lernen & Futter für den Algorithmus
Google Ads Smart Bidding (tCPA / tROAS) und Performance Max (PMax) Algorithmen benötigen kontinuierlich frische, qualitativ hochwertige Creative-Assets. Durch das Bereitstellen diverser Text- und Asset-Varianten erhält der Algorithmus die nötigen Datenpunkte, um neue Nutzersegmente und Auktionen effizient zu erschließen.

### 2. Ad Spend Shift & CPL-Senkung
Das Hauptziel der Pipelines ist es, **neue Anzeigen-Ansprachen mit günstigeren Lead-Kosten (CPL)** zu identifizieren. Sobald das System feststellt, welche Ansprachen (Hooks) überragende Conversions liefern, kann das Werbebudget gezielt auf diese Top-Performer umgeschichtet werden.

### 3. Kontinuierliche monatliche Routine
Die Pipelines sind für eine **monatliche Test- und Skalierungsroutine** konzipiert:
1. **Analysieren:** Performance der bestehenden Assets auslesen.
2. **Generieren:** 50 neue AI-Anzeigenalternativen (25x RSA, 25x PMax) auf Basis spezifischer Psychology- & Copywriting-Hooks erstellen.
3. **Review & Governance:** Automatische Qualitäts- und Richtlinienprüfung durch einen Review-Agenten.
4. **Upload & Testing:** Upload über die Google Ads API für die automatisierte A/B-Auswertung im Zeitverlauf.

---

## End-to-End Datenfluss

```
[Aktive Kampagne / RSAs / Asset-Gruppen] 
                   │
                   ▼
       [Landing Page Grounding & Final URL]
                   │
                   ▼
  [AI Copywriting Engine (25 Hook Frameworks)]
    ├── 25 Blueprint Pipelines für Responsive Suchanzeigen (RSA)
    └── 25 Blueprint Pipelines für Performance Max (PMax)
                   │
                   ▼
 [Quality & Compliance Review Agent (Char Limits & Policy Clean)]
                   │
                   ▼
   [Google Ads API Upload (Mutations Payload)]
```

---

## Die 25 Copywriting Hook-Frameworks

Die 50 Pipelines teilen sich auf in **25 RSA-Pipelines** und **25 PMax-Pipelines**, basierend auf erprobten Werbepsychologie-Hooks:

| # | Hook Framework | Psychologischer Fokus & Ansprache |
|---|---|---|
| 01 | **Autoritäts-Hook** | Etabliert Expertenstatus, Zertifizierungen & Branchenführung |
| 02 | **Beweis-Hook** | Zahlen, Daten, Fakten & harte Kennzahlen zur Untermauerung |
| 03 | **Demonstrations-Hook** | Zeigt den konkreten Funktions- und Arbeitsablauf des Produkts |
| 04 | **Dringlichkeits-Hook** | Erzeugt FOMO, zeitliche Begrenzung & Handlungsdruck |
| 05 | **Einzigartigkeits-Hook** | Hebt das USV & Alleinstellungsmerkmal klar hervor |
| 06 | **Fehler-Hook** | Warnt vor häufigen, teuren Fehlern der Zielgruppe |
| 07 | **Geheimnis-Hook** | Weckt Neugier durch unkonventionelle Insider-Tipps |
| 08 | **Identitäts-Hook** | Spricht die Selbstwahrnehmung & Zielgruppen-Rolle direkt an |
| 09 | **Insider-Hook** | Vermittelt exklusives Fachwissen hinter den Kulissen |
| 10 | **Kontrarian-Hook** | Hinterfragt gängige Branchen-Mythen & Glaubenssätze |
| 11 | **Mechanismus-Hook** | Erklärt das spezifische "Wie" & die Funktionsweise des Erfolgs |
| 12 | **Mythen-Hook** | Räumt mit weit verbreiteten Irrtümern der Branche auf |
| 13 | **Neugier-Hook** | Stellt offene Fragen & erzeugt einen Information Gap |
| 14 | **Problem-Hook** | Fokussiert das zentrale Problem der Zielgruppe präzise |
| 15 | **Schmerz-Hook** | Adressiert emotionale & finanzielle Schmerzpunkte direkt |
| 16 | **Social-Proof-Hook** | Nutzt Kundenbewertungen, Testimonials & Kundenzahlen |
| 17 | **Spezifitäts-Hook** | Arbeitet mit extrem präzisen Angaben, Fristen & Details |
| 18 | **Status-Hook** | Zielt auf Aufstieg, Ansehen & Prestigegewinn ab |
| 19 | **Story-Hook** | Verpackt das Angebot in eine greifbare Vorher-Nachher-Story |
| 20 | **Vergleichs-Hook** | Stellt Alt vs. Neu bzw. Herkömmlich vs. Lösung gegenüber |
| 21 | **Vorteils-Hook** | Stellt die direkten Transformationen & Benefits in den Vordergrund |
| 22 | **Warnungs-Hook** | Macht auf versteckte Risiken & Stolpersteine aufmerksam |
| 23 | **Wunsch-Traum-Hook** | Visualisiert das ideale Endergebnis & das Traum-Szenario |
| 24 | **Zugehörigkeits-Hook** | Stellt die Gemeinschaft & den Beitritt zu einer Elite-Gruppe dar |
| 25 | **Überraschungs-Hook** | Verblüfft mit unerwarteten Fakten & Wendungen |

---

## Repository-Struktur

```
50-ai-asset-pipelines-google-ads/
├── README.md
├── LICENSE
└── blueprints/
    ├── rsa/    (25 Make.com Blueprint JSONs für Responsive Suchanzeigen)
    └── pmax/   (25 Make.com Blueprint JSONs für Performance Max Asset-Gruppen)
```

---

## Setup & Import-Anleitung (Make.com)

1. **Blueprint herunterladen:** Navigiere im Repository in den Ordner `blueprints/rsa/` oder `blueprints/pmax/` und wähle den gewünschten Hook aus.
2. **Neues Szenario in Make.com erstellen:**
   - Logge dich bei [Make.com](https://www.make.com) ein.
   - Erstelle ein neues Szenario.
   - Klicke unten auf die drei Punkte (`...`) -> **Import Blueprint**.
   - Wähle die entsprechende `.blueprint.json`-Datei aus.
3. **Verbindungen konfigurieren (Connections):**
   - **Google Ads Connection:** OAuth2-Verbindung mit der Google Ads API herstellen.
   - **AI Connection (Gemini / OpenAI):** API-Key für das LLM hinterlegen.
   - **Custom Webhooks / HTTP:** Landing-Page Scraper URLs anpassen.
4. **Variablen & IDs anpassen:**
   - `Customer ID` (Google Ads Kundennummer ohne Bindestriche).
   - `Campaign ID` & `Ad Group ID`.
5. **Szenario aktivieren & Schedule festlegen:** Auf monatliche Ausführung stellen.

---

## Review & Quality Governance Agent

Jede Pipeline enthält ein automatisches **Review-Agenten-Modul**:
- **Zeichenlängen-Garantie:** 
  - RSA Headlines ≤ 30 Zeichen | Descriptions ≤ 90 Zeichen
  - PMax Headlines ≤ 30 Zeichen | Long Headlines ≤ 90 Zeichen | Descriptions ≤ 90 Zeichen
- **Compliance Sanitization:** Automatische Bereinigung aggressiver oder verbotener Werbebegriffe gemäß Google Ads Richtlinien.

---

## Lizenz & Credits

Erstellt von [Slava Wagner](https://github.com/SlavaWagner).  
Inspiriert von der [ai-ads-pipeline](https://github.com/SlavaWagner/ai-ads-pipeline).  

Dieses Projekt ist unter der MIT-Lizenz lizenziert – siehe die [LICENSE](LICENSE) Datei für Details.

Erstellt mit Hilfe von Antigravity CLI
