# Reaktionen in inDeal – Agent A und B (Entwurf 08.11.2026)

Grundlage: [Reaktionen-Spickzettel](vorlagen/reaktionen-spickzettel.md) (Lars Krüger). Eintragen im Reiter **Antworten**. Gespeichert wird automatisch.
Regeln und Einwände: [zielgruppe-indeal.md](zielgruppe-indeal.md), Teil B. Texte: [nachrichten-agenten-v2.md](nachrichten-agenten-v2.md).

**Feld „Aktion des Agenten“: höchstens 60 Zeichen.** Alle Aktionen unten sind darauf gekürzt.

---

## 1. Ton und Grenzen (gilt für alle Reaktionen)
- **Anrede:** wie der Lead schreibt. Siezt er, dann Sie. Duzt er oder ist unklar, dann Du.
- **Keine Preise nennen**
- **Gespräch beenden nach 2 Einwänden**
- Das kostenlose Gespräch heißt immer **„Engpass-Check“**. Nie „Erstgespräch“, „Beratung“, „Wachstumsanalyse“.
- Höchstens 3 Sätze, eine Frage pro Nachricht

## 2. Termine (Antworten › Termine › Bearbeiten)
- [ ] **Feste Zeitfenster:** Dienstag 09:00–12:00 und Donnerstag 09:00–12:00
- [ ] **Buchungslink:** https://calendly.com/leeperformance/engpass-check-kostenlos (für Agent B später die eigene Calendly-Kopie)
- [ ] **Dauer:** 30 Minuten

## 3. Teilbares Ergebnis (Kampagne › Zahnrad › Briefing)
| Agent | Teilbares Ergebnis |
|---|---|
| A | https://drive.google.com/file/d/1NG8aztAZrFVolBqsHvlIPXyI4XVvcf1A/view (5 Warnsignale) |
| B | https://drive.google.com/file/d/1zzQFJi0vE-MprVeZoB7gG9uk3mxZW4z-/view (3 Engpass-Fragen) |

---

## 4. Die 5 Standard-Reaktionen (Kachel anklicken › Bearbeiten)

### Positiv
| Feld | Eintrag |
|---|---|
| Beispielantwort | „Ja, gern, schick mal rüber.“ |
| Aktion des Agenten | `Teilbares Ergebnis + 2 Termine Di/Do. Max. 3 Sätze` |
| Zielstatus | Gespräch läuft |
| Vorlage (optional) | siehe unten |

Vorlage Agent A:
```text
Gern, hier sind die 5 Warnsignale: {Teilbares Ergebnis}
Geh damit einmal durch Eure fünf größten offenen Angebote. Wenn Du magst, schauen wir danach 30 Minuten im kostenlosen Engpass-Check drauf: {Termin 1} oder {Termin 2}?
```
Vorlage Agent B:
```text
Gern, hier sind die 3 Fragen: {Teilbares Ergebnis}
Nimm Dir 10 Minuten dafür. Wenn Du magst, schauen wir danach 30 Minuten im kostenlosen Engpass-Check drauf: {Termin 1} oder {Termin 2}?
```
*Die Platzhalter in geschweiften Klammern ersetzt inDeal. Wie sie dort genau heißen, siehst Du im Editor über „Variablen-Namen zeigen“. Lieber leer lassen als falsch benennen: Dann schreibt der Agent den Entwurf selbst nach der Aktion.*

### Frage
| Feld | Eintrag |
|---|---|
| Beispielantwort | „Was genau machst Du denn?“ / „Worum geht es?“ |
| Aktion des Agenten | `Kurz antworten aus FAQ, dann Engpass-Check anbieten` |
| Zielstatus | Gespräch läuft |
| Vorlage | leer (Agent nutzt FAQ aus Teil B) |

### Einwand
| Feld | Eintrag |
|---|---|
| Beispielantwort | „Haben schon einen Berater.“ / „Wir sind gut aufgestellt.“ |
| Aktion des Agenten | `Erst nachfragen, nicht pitchen. Nach 2 Einwänden Ende` |
| Zielstatus | Gespräch läuft |
| Vorlage | leer (Agent nutzt die Einwandtabelle aus Teil B) |

### Später
| Feld | Eintrag |
|---|---|
| Beispielantwort | „Gerade schlecht, melde Dich in drei Monaten.“ |
| Aktion des Agenten | `Bedanken, Teilbares Ergebnis anbieten, kein Druck` |
| Zielstatus | Später kontaktieren (Wiedervorlage in 3 Monaten) |
| Vorlage | „Alles klar, danke für die ehrliche Antwort. Soll ich Dir bis dahin die {5 Warnsignale / 3 Fragen} schicken? Dann hast Du sie, wenn das Thema hochkommt.“ |

### Absage
| Feld | Eintrag |
|---|---|
| Beispielantwort | „Kein Interesse.“ / „Aktuell nicht mein Thema.“ |
| Aktion des Agenten | `Freundlich bedanken, keine Rückfrage, Gespräch beenden` |
| Zielstatus | Kein Interesse |
| Vorlage | „Danke Dir für die klare Antwort, {Vorname}. Alles Gute weiterhin!“ |

*Bewusst ohne Rückfrage: Wer klar absagt, soll nicht noch eine Frage bekommen. Das schützt Deinen Ruf in Deinem eigenen Netzwerk.*

---

## 5. Eigene Reaktionen (+ Reaktion)

### Bitte um Unterlagen
| Feld | Eintrag |
|---|---|
| Woran erkennt der Agent sie? | Der Lead fragt nach Infos, Unterlagen, Folien oder einer Website. |
| Beispielantwort | „Schick mir gerne mal Infos.“ |
| Aktion des Agenten | `Teilbares Ergebnis schicken, eine Rückfrage dazu stellen` |
| Zielstatus | Gespräch läuft |

### Eigenes Projekt oder eigene Lösung *(Fall Hofmann)*
| Feld | Eintrag |
|---|---|
| Woran erkennt der Agent sie? | Der Lead erzählt, dass er das Thema gerade selbst angeht oder ein eigenes Tool baut. |
| Beispielantwort | „Ich baue dafür gerade selbst eine Lösung mit KI.“ |
| Aktion des Agenten | `Interesse zeigen, nicht konkurrieren, nach Engpass fragen` |
| Zielstatus | Gespräch läuft |
| Vorlage | „Spannend! Meine Erfahrung: Das Tracking ist selten das Problem, eher die Frage, was überhaupt in die Pipeline gehört. Wo hakt es bei Euch heute am meisten: Erfassung, Qualifizierung oder Nachverfolgung?“ |

### Weiterleitung an Kollegen
| Feld | Eintrag |
|---|---|
| Woran erkennt der Agent sie? | Der Lead sagt, er ist nicht zuständig, und nennt jemand anderen. |
| Beispielantwort | „Da ist eher unser Vertriebsleiter der Richtige.“ |
| Aktion des Agenten | `Danken, um Namen oder kurze Vorstellung bitten` |
| Zielstatus | Gespräch läuft |

### Kennt Michael persönlich *(bestehende Kontakte!)*
| Feld | Eintrag |
|---|---|
| Woran erkennt der Agent sie? | Der Lead bezieht sich auf eine gemeinsame Vergangenheit, ein Projekt oder ein Treffen. |
| Beispielantwort | „Hallo Michael, lange nicht gehört! Wie geht's Dir?“ |
| Aktion des Agenten | `Nicht automatisch antworten, an Michael übergeben` |
| Zielstatus | Manuell bearbeiten |

*Wichtig gerade bei Liste A und B: Viele kennen Dich. Antwortet der Agent auf „Wie geht's Dir?“ mit einem Terminvorschlag, ist die Beziehung beschädigt. Diese Antworten schreibst Du selbst.*

---

## 6. Testgespräch, bevor es live geht (Antworten › Testgespräch)

| Test | Als Lead schreiben | Erwartung |
|---|---|---|
| Positiv | „Ja, gern.“ | Link zum teilbaren Ergebnis + zwei konkrete Termine Di/Do + Buchungslink |
| Frage | „Was machst Du genau?“ | Kurze Antwort, kein Vortrag, Engpass-Check angeboten |
| Einwand | „Haben schon einen Berater.“ | Rückfrage, kein Pitch |
| Preis | „Was kostet das?“ | **Kein Preis**, Verweis auf kostenlosen Engpass-Check |
| Später | „Melde Dich im Frühjahr.“ | Bedanken, Asset anbieten, kein Druck |
| Absage | „Kein Interesse.“ | Ein Satz Dank, Ende |
| Persönlich | „Hey Michael, wie geht's?“ | Keine automatische Antwort, Übergabe an Dich |
| Sie | „Guten Tag Herr Lee, gern.“ | Antwort in Sie-Form |

**„Antworten senden“: Mit Freigabe** (mindestens die ersten 2 Wochen). Im Ernstfall prüfst Du jeden Entwurf und klickst **Freigeben**.
