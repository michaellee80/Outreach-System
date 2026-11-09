# KI-Variablen-Beispiele
*Lars Krüger · LinkedIn Sales System*

Wo: Reiter **Kampagne** › Schritt › **Bearbeiten** › Werkzeugleiste **KI-Variable** → Dialog **KI-Variablen** (Reiter **Vorlagen** / **Meine**, Suche „Variable suchen“, je Zeile „Öffnen“ / „Einfügen“).

## Eingebaute Vorlagen (Best Practice)
| Vorlage | Was sie liefert | Baustein |
|---|---|---|
| Begrüßung | Begrüßungswort + bereinigter Vorname (bei Sie „Hallo Herr/Frau Nachname“), ohne KI | – |
| Vorname bereinigt | Vorname ohne Titel, Emojis und Zusätze, ohne KI | – |
| Jobtitel bereinigt | Jobtitel ohne Firmenzusatz und Schlagwortketten, höchstens fünf Wörter, ohne KI | – |
| Bereich | „Ich habe gesehen, dass du im Bereich X tätig bist“ | Bezug |
| Bereich (Vernetzung) | kurzer Satz mit festem Satzanfang/-ende für die Vernetzung | Bezug |
| Berufserfahrung | „du bist ja schon seit rund X Jahren als ROLLE tätig“ | Bezug |
| Ihr verkauft X | „Ihr verkauft X, oder?“ aus der Firmenbeschreibung | Abnicken |
| Branche kurz | „in der X-Branche“ | Abnicken |
| Letzter Beitrag | Bezug auf den letzten Beitrag | Bezug |
| Türöffner-Frage | geschlossene Ja-Frage | CTA |
| Signal-Bezug | Bezug auf das Signal (Kontaktanfrage, Kommentar, Like, Profilbesuch) | Bezug |
| Persönlicher Satz | persönlicher Satz aus dem stärksten Anknüpfungspunkt | Bezug |
Die Vorlagen sind gesperrt (Schloss-Symbol). Für eigene Varianten legst du eine neue Variable an.

## Eigene Variable: „+ KI-Variable“ → „Neue KI-Variable“
| Feld | Was du einträgst |
|---|---|
| **Name** | frei, z. B. „Profil-Thema“ |
| **Prompt** | „Beschreibe, welchen Satz die KI je Lead schreiben soll. Profilfelder fügst Du per Klick ein; die Profildaten gehen getrennt als Daten an die KI.“ |
| **Feld einfügen** | Vorname, Nachname, Headline, Jobtitel, Über mich, Standort, Berufserfahrung, Firma, Firmenbeschreibung, Firmen-Website, Branche, Letzter Beitrag, Letzter Repost (Headline + Über mich sind vorausgewählt) |
| **Ausgaberegeln** | Wortgrenze (Standard 14) · Erster Buchstabe klein (folgt auf die Anrede) · Sprache folgt dem Agenten · Anrede (Du/Sie) folgt dem Agenten · Keinen Firmennamen nennen · Ausgabe ist eine Frage |
| **Ersatzwert** | „Wird genutzt, wenn das Profil zu dünn ist oder die Prüfung durchfällt. Leer = der Satz entfällt.“ |
| **Live-Vorschau** | Nächster Lead · Neu erzeugen · An 3 Leads testen |
Dann **Speichern**. Die Variable steht an der Cursorstelle im Text und liegt unter **Meine**. „Variablen-Namen zeigen“ blendet die Namen im Text ein.

## 6 Beispiele (Fokus: Profil-Themen)
**1. Profil-Thema** (Lektion 12)
- Prompt: „Schreib einen kurzen Satz, der aufgreift, worüber die Person in Headline und Über mich am meisten spricht. Nichts erfinden.“
- Felder: Headline, Über mich · Regeln: Wortgrenze 14, erster Buchstabe klein, keinen Firmennamen · Ersatzwert: leer
- Im Text: „Moin Martin, [Profil-Thema] – da sehe ich viele gerade an derselben Stelle, oder?“

**2. Security-Anlass** (Jana)
- Prompt: „Formuliere einen Halbsatz, warum IT-Sicherheit für dieses Unternehmen gerade ein Thema sein könnte (Wachstum, Umzug, neue Standorte). Nur aus den Feldern ableiten.“
- Felder: Firmenbeschreibung, Letzter Beitrag · Regeln: Wortgrenze 15, keinen Firmennamen · Ersatzwert: leer

**3. Peer-Problem**
- Prompt: „Nenne in einem Halbsatz ein typisches Problem, das Menschen in dieser Rolle und Branche gerade haben.“
- Felder: Jobtitel, Branche · Regeln: Ausgabe ist eine Frage · Ersatzwert: leer

**4. Zielkunden kurz**
- Prompt: „Wem verkauft dieses Unternehmen hauptsächlich? Antworte mit 2–4 Wörtern.“
- Felder: Firmenbeschreibung, Firmen-Website · Regeln: Wortgrenze 4, keinen Firmennamen · Ersatzwert: „euren Kunden“
- Im Text: „Ihr arbeitet vor allem mit [Zielkunden kurz], oder?“

**5. Werdegang-Brücke**
- Prompt: „Finde im Werdegang einen Wechsel oder Schwerpunkt, der zu meinem Angebot passt, und formuliere ihn als kurzen Halbsatz.“
- Felder: Berufserfahrung, Über mich · Regeln: Wortgrenze 12 · Ersatzwert: leer

**6. Repost-Gedanke**
- Prompt: „Schreib einen kurzen, ehrlichen Gedanken zum letzten Repost, wie ein Kollege, ohne Lob-Floskeln.“
- Felder: Letzter Repost · Regeln: Wortgrenze 18 · Ersatzwert: leer

## Regeln
- Erst die Vorlagen nutzen, eigene nur für Feintuning.
- Ersatzwert lieber leer lassen als etwas Allgemeines erzwingen.
- Immer „An 3 Leads testen“ und mehrmals „Nächster Lead“.
- Pro Nachricht höchstens 2 KI-Variablen, sonst klingt es zusammengesetzt.
