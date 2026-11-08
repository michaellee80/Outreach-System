# Nachrichten v2 für die inDeal-Agenten (Entwurf 08.11.2026)

Gebaut nach dem Nachrichten-Baukasten (Lars Krüger): **Bezug · Abnicken („…, oder?“) · Lösung + Benefit + Zahl · softer CTA (Ja/Nein)**.
Basis: N1 und N2 aus [nachrichten.md](https://github.com/michaellee80/linkedin-brand/blob/HEAD/linkedin/texte/nachrichten.md). Nach Freigabe werden die Texte dort übernommen, damit es nur eine Fassung gibt.

**Variablen** (inDeal, Werkzeugleiste im Nachrichten-Editor): `{Vorname}`, `{Firma}`, `{Branche kurz}`, `{Letzter Beitrag}`, `{Signal-Bezug}`.
**Regeln:** unter 80 Wörter · Du groß · Zahl immer einem Fall zugeordnet · nur „Engpass-Check“ · „Deals“ nur bei Agent A (Ausnahme).

## Was sich gegenüber v1 ändert

| | v1 | v2 | Warum |
|---|---|---|---|
| Bezug A | „Deinen Beitrag zu {Thema}“ | Zwei Fassungen: mit Beitrag **und** ohne Beitrag (bestehende Kontakte posten oft nicht) | Kein erfundener Bezug |
| Abnicken | „in der Industrie“ | `{Branche kurz}` | Sofort-Erkennung: „Das bin ich.“ |
| Baustein 3 B | „Ich war selbst einer: 15 direkte Reports“ (über Dich) | Fall Laser-Hersteller: Forecast über 80 %, Produktion plant wieder | Baukasten: über das Problem des Leads schreiben, nicht über Dich |
| CTA | „an denen wir tote Deals früh erkannt haben“ | „an denen Du tote Deals früh erkennst“ | Nutzen für ihn, nicht Rückblick auf uns |
| Test | eine Fassung | je Agent eine Testvariante mit anderem Schmerz | Nach 50 Nachrichten wissen, welcher Schmerz zieht |

---

## AGENT A · Vertriebsleitung (bestehende Kontakte)

### A1 · mit Beitrag (wenn `{Letzter Beitrag}` gefüllt ist) – 70 Wörter
```text
Hallo {Vorname}, ich hatte Deinen Beitrag zu {Letzter Beitrag} gesehen.

Viele Vertriebsleiter in {Branche kurz} haben gerade eine volle Pipeline, aber Angebote, die einfach nicht entschieden werden, oder?

Bei einem Laser-Hersteller stieg die Quote von Angebot zu Auftrag in sechs Monaten von 13 % auf über 50 %. Nicht durch mehr Aktivität, sondern durch frühere Qualifizierung.

Soll ich Dir die 5 Warnsignale schicken, an denen Du tote Deals früh erkennst?
```

### A2 · ohne Beitrag (Ersatz, bestehender Kontakt) – 74 Wörter
```text
Hallo {Vorname}, wir sind schon länger vernetzt, und Du verantwortest bei {Firma} den Vertrieb.

Viele Vertriebsleiter in {Branche kurz} haben gerade eine volle Pipeline, aber Angebote, die einfach nicht entschieden werden, oder?

Bei einem Laser-Hersteller stieg die Quote von Angebot zu Auftrag in sechs Monaten von 13 % auf über 50 %. Nicht durch mehr Aktivität, sondern durch frühere Qualifizierung.

Soll ich Dir die 5 Warnsignale schicken, an denen Du tote Deals früh erkennst?
```

### A-Test · Schmerz Forecast statt Pipeline – 67 Wörter
```text
Hallo {Vorname}, wir sind schon länger vernetzt, und Du verantwortest bei {Firma} den Vertrieb.

In vielen Firmen in {Branche kurz} fragt die Produktion jeden Monat, ob der Vertriebs-Forecast diesmal hält, oder?

Bei einem Laser-Hersteller haben wir die Pipeline von 200 auf 20 echte Verkaufschancen fokussiert. Danach lag die Forecast-Zuverlässigkeit bei über 80 %.

Soll ich Dir die 5 Warnsignale schicken, an denen Du tote Deals früh erkennst?
```

---

## AGENT B · Geschäftsführung

### B1 · mit Anlass (wenn `{Signal-Bezug}` gefüllt ist) – 62 Wörter
```text
Hallo {Vorname}, ich habe gesehen, dass {Signal-Bezug}.

Viele Geschäftsführer in {Branche kurz} merken in so einer Phase, dass der Umsatz zwar kommt, aber kaum noch planbar ist, oder?

Bei einem Laser-Hersteller lag die Forecast-Zuverlässigkeit nach sechs Monaten bei über 80 %. Die Produktion konnte wieder planen.

Soll ich Dir die 3 Fragen schicken, mit denen Du Deinen Engpass in 10 Minuten eingrenzt?
```

### B2 · ohne Anlass (Ersatz) – 63 Wörter
```text
Hallo {Vorname}, ich habe mir {Firma} angesehen und bin hängen geblieben.

Viele Geschäftsführer in {Branche kurz} merken gerade, dass der Umsatz zwar kommt, aber kaum noch planbar ist, oder?

Bei einem Laser-Hersteller lag die Forecast-Zuverlässigkeit nach sechs Monaten bei über 80 %. Die Produktion konnte wieder planen.

Soll ich Dir die 3 Fragen schicken, mit denen Du Deinen Engpass in 10 Minuten eingrenzt?
```

### B-Test · Schmerz „Alles landet bei Dir“ – 74 Wörter
```text
Hallo {Vorname}, ich habe gesehen, dass {Signal-Bezug}.

Viele Geschäftsführer in {Branche kurz} merken in so einer Phase, dass immer mehr Entscheidungen wieder bei ihnen landen, oder?

Das ist selten ein Führungsproblem, meist ein Engpass in der Struktur. Bei einem Laser-Hersteller wurde aus 200 offenen Verkaufschancen in sechs Monaten eine Pipeline mit 20, auf die sich alle verlassen konnten.

Soll ich Dir die 3 Fragen schicken, mit denen Du Deinen Engpass in 10 Minuten eingrenzt?
```

---

## Nach dem Ja (beide Agenten)

**1. Asset sofort schicken, ohne Pitch**

Agent A:
```text
Gern, hier sind die 5 Warnsignale: {Link 5 Warnsignale}
Geh damit einmal durch Eure fünf größten offenen Angebote. Bei wie vielen trifft mindestens eins zu?
```

Agent B:
```text
Gern, hier sind die 3 Fragen: {Link 3 Engpass-Fragen}
Nimm Dir 10 Minuten, ehrlich beantwortet. Bei welcher bist Du am längsten hängen geblieben?
```

**2. Zwei konkrete Zeiten** (nach Antwort oder einen Tag später). Zeitfenster: Di und Do, 9–12 Uhr.
```text
Magst Du Dienstag um 10 Uhr oder Donnerstag um 9:30 Uhr 30 Minuten drüber sprechen? Dann schauen wir im Engpass-Check, wo bei Euch der Engpass sitzt. Kostet Dich nichts.
```

**3. Funkstille nach 2–3 Tagen**
```text
{Vorname}? 🙂
```

**4. Follow-up mit neuem Gedanken** (Texte in [kampagne-inDeal.md](kampagne-inDeal.md), Abschnitt „Nachfassen“). Danach Schluss.

---

## So testest Du
1. Starte Agent A mit **A1/A2** (inDeal nimmt A1, wenn ein Beitrag gefunden wird, sonst A2).
2. Nach **50 Nachrichten** Antwortquote notieren. Dann die nächsten 50 mit **A-Test**.
3. Gewinner ist die Fassung mit mehr **positiven Antworten**, nicht mit mehr Antworten insgesamt.
4. Gleiches Vorgehen später bei Agent B.

Benchmark aus der Kampagnen-Checkliste: Antwortquote über 20 % ist gut, über 30 % top. Etwa jede 10. Antwort ist ein klares Ja.
