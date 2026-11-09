# Nachrichten v2 für die inDeal-Agenten (Stand 09.11.2026, Sie-Form)

Gebaut nach dem [Nachrichten-Baukasten 201](vorlagen/201-nachrichten-baukasten.md): **Bezug · Abnicken („…, oder?“) · Lösung + Benefit + Zahl · softer CTA (Ja/Nein)**.
Basis: N1 und N2 aus [nachrichten.md](https://github.com/michaellee80/linkedin-brand/blob/HEAD/linkedin/texte/nachrichten.md). Nach Freigabe werden die Texte dort übernommen, damit es nur eine Fassung gibt.

**Entscheidungen Michael**
- **08.11.2026:** Eine Nachricht gilt für **alle Leads eines Agenten**. Kein Beitrags- oder Anlassbezug, keine Branchen-Variable: Nichts kann falsch befüllt werden.
- **09.11.2026: Alle Leads werden gesiezt.** Begrüßung über die KI-Variable **„Begrüßung“** (Vorlage, ohne KI). Bei Anrede „Sie“ im Briefing schreibt sie automatisch „Hallo Herr/Frau Nachname“, siehe [205 KI-Variablen](vorlagen/205-ki-variablen-beispiele.md).

**Regeln:** unter 80 Wörter · Sie/Ihnen/Ihr · Zahl immer einem Fall zugeordnet · nur „Engpass-Check“ · „Deals“ nur bei Agent A (Ausnahme).

**In inDeal:** Briefing › Anrede = **Sie**, Begrüßung = **Hallo**. Im Text `{Begrüßung}` über Werkzeugleiste › KI-Variable › Vorlagen › „Begrüßung“ › Einfügen.

## Was sich gegenüber v1 ändert

| | v1 | v2 | Warum |
|---|---|---|---|
| Anrede | Du | **Sie**, Begrüßung automatisch mit Nachname | Entscheidung Michael, passt zu GFs und Vertriebsleitern im Mittelstand |
| Bezug | „Deinen Beitrag zu {Thema}“ bzw. „{Anlass}“ | „Wir sind hier schon länger vernetzt“ | Stimmt für jeden Kontakt aus Deinem Netzwerk (Liste A und B) |
| Baustein 3 B | „Ich war selbst einer: 15 direkte Reports“ | Fall Laser-Hersteller: Forecast über 80 %, Produktion plant wieder | Baukasten: über das Problem des Leads schreiben, nicht über Dich |
| CTA | „an denen wir tote Deals früh erkannt haben“ | „an denen Sie tote Deals früh erkennen“ | Nutzen für ihn, nicht Rückblick auf uns |
| Test | eine Fassung | je Agent eine Testvariante mit anderem Schmerz | Nach 50 Nachrichten wissen, welcher Schmerz zieht |

---

## AGENT A · Vertriebsleitung

### A · Standardnachricht (für alle Leads) – 71 Wörter
```text
{Begrüßung}, wir sind hier schon länger vernetzt, deshalb einfach mal direkt.

Viele Vertriebsleiter in der Industrie haben gerade eine volle Pipeline, aber Angebote, die einfach nicht entschieden werden, oder?

Bei einem Laser-Hersteller stieg die Quote von Angebot zu Auftrag in sechs Monaten von 13 % auf über 50 %. Nicht durch mehr Aktivität, sondern durch frühere Qualifizierung.

Soll ich Ihnen die 5 Warnsignale schicken, an denen Sie tote Deals früh erkennen?
```

### A-Test · Schmerz Forecast statt Pipeline – 61 Wörter
```text
{Begrüßung}, wir sind hier schon länger vernetzt, deshalb einfach mal direkt.

In vielen Industrieunternehmen fragt die Produktion jeden Monat, ob der Vertriebs-Forecast diesmal hält, oder?

Bei einem Laser-Hersteller haben wir die Pipeline von 200 auf 20 echte Verkaufschancen fokussiert. Danach lag die Forecast-Zuverlässigkeit bei über 80 %.

Soll ich Ihnen die 5 Warnsignale schicken, an denen Sie tote Deals früh erkennen?
```

---

## AGENT B · Geschäftsführung

### B · Standardnachricht (für alle Leads) – 64 Wörter
```text
{Begrüßung}, wir sind hier schon länger vernetzt, deshalb einfach mal direkt.

Viele Geschäftsführer in Produktion und Logistik merken gerade, dass der Umsatz zwar kommt, aber kaum noch planbar ist, oder?

Bei einem Laser-Hersteller lag die Forecast-Zuverlässigkeit nach sechs Monaten bei über 80 %. Die Produktion konnte wieder planen.

Soll ich Ihnen die 3 Fragen schicken, mit denen Sie Ihren Engpass in 10 Minuten eingrenzen?
```

### B-Test · Schmerz „Alles landet bei Ihnen“ – 76 Wörter
```text
{Begrüßung}, wir sind hier schon länger vernetzt, deshalb einfach mal direkt.

Viele Geschäftsführer in Produktion und Logistik merken gerade, dass immer mehr Entscheidungen wieder bei ihnen landen, oder?

Das ist selten ein Führungsproblem, meist ein Engpass in der Struktur. Bei einem Laser-Hersteller wurde aus 200 offenen Verkaufschancen in sechs Monaten eine Pipeline mit 20, auf die sich alle verlassen konnten.

Soll ich Ihnen die 3 Fragen schicken, mit denen Sie Ihren Engpass in 10 Minuten eingrenzen?
```

**Falls Agent B später neue Kontakte anschreibt:** Ersten Satz ersetzen durch „{Begrüßung}, danke für die Vernetzung.“

---

## Nach dem Ja (beide Agenten)

**1. Asset sofort schicken, ohne Pitch**

Agent A:
```text
Gern, hier sind die 5 Warnsignale: {Link 5 Warnsignale}
Gehen Sie damit einmal durch Ihre fünf größten offenen Angebote. Bei wie vielen trifft mindestens eins zu?
```

Agent B:
```text
Gern, hier sind die 3 Fragen: {Link 3 Engpass-Fragen}
Nehmen Sie sich 10 Minuten dafür. Bei welcher Frage sind Sie am längsten hängen geblieben?
```

**2. Zwei konkrete Zeiten** (nach Antwort oder einen Tag später). Zeitfenster: Di und Do, 9–12 Uhr.
```text
Wollen wir Dienstag um 10 Uhr oder Donnerstag um 9:30 Uhr 30 Minuten darüber sprechen? Dann schauen wir im Engpass-Check, wo bei Ihnen der Engpass sitzt. Das kostet Sie nichts.
```

**3. Funkstille nach 2–3 Tagen** („{Vorname}? 🙂“ passt nicht zum Sie)
```text
{Begrüßung}, kurz nachgefragt: Ist das bei Ihnen gerade ein Thema?
```

**4. Follow-up mit neuem Gedanken** (Texte in [kampagne-inDeal.md](kampagne-inDeal.md), Abschnitt „Nachfassen“). Danach Schluss.

---

## So testest Du
1. Starte Agent A mit der **Standardnachricht**.
2. Prüfe in „So liest es …“ an 3 Leads, dass `{Begrüßung}` richtig „Hallo Herr …/Frau …“ ergibt.
3. Nach **50 Nachrichten** Antwortquote notieren. Dann die nächsten 50 mit **A-Test**.
4. Gewinner ist die Fassung mit mehr **positiven Antworten**, nicht mit mehr Antworten insgesamt.
5. Gleiches Vorgehen später bei Agent B.

Benchmark aus der Kampagnen-Checkliste: Antwortquote über 20 % ist gut, über 30 % top. Etwa jede 10. Antwort ist ein klares Ja.
