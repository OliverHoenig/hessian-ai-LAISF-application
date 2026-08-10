# LAISF-Bewerbung — Meettopia

Texte zum direkten Übernehmen in das Formular auf [aigude.ai/apply/laisf](https://aigude.ai/apply/laisf).  
Zeichenangaben = aktuelle Länge (Limit in Klammern). Nach dem Absenden: Bestätigungslink in der E-Mail klicken.

---

## Abschnitt 1 — Projekt & Antragsteller

### Projekttitel (200)

Meettopia – KI-gestütztes Meeting-Betriebssystem für wirksame Teammeetings

*(92 / 200)*

### Akronym (60)

Meettopia

*(9 / 60)*

### Antragsteller:in (120)

Oliver Hönig

*(12 / 120)*

### E-Mail (200)

oliver.hoenig@balanced-bytes.com

### Telefon (60)

+49 178 9088958

---

## Abschnitt 2 — Zu fördernde Person(en)

### Person 1

| Feld | Inhalt |
|---|---|
| Name | Oliver Hönig |
| Höchster akademischer Abschluss | B.Sc. Informatik (Abschlussarbeit, TU Darmstadt) |
| Adresse | *(im Formular ergänzen)* |
| E-Mail | oliver.hoenig@balanced-bytes.com |
| Telefon | +49 178 9088958 |
| Förderanteil | 50 |
| LinkedIn | *(im Formular ergänzen, falls vorhanden)* |

Solo-Founder; gewünschter Förderanteil zunächst 50 % (≤ 200 %); Vollzeit nach Abstimmung möglich.

---

## Abschnitt 3 — KI-Geschäftsidee

### Titel (80)

Meettopia: KI-Moderation, die Meetings wirksam macht

*(52 / 80)*

### Beschreibung (850)

Andere Tools organisieren Meetings; Meettopia macht Meetings endlich wieder wirksam.
Meettopia wird die Plattform für KI-gestützte Meetings und ermöglicht es Teams und Organisation, gemeinsam Geniales zu schaffen. Es wird sichergestellt, dass in jedem Meeting Ziele klar werden, Strukturen greifen und echte Fortschritte erzielt werden.
Durch KI-Moderation und KI-Avatare profitieren Teams von individuell zugeschnittenen Interventionen, schneller Problemlösung und direkten Handlungsempfehlungen. Das steigert die Wirkung jedes Meetings und macht kollektives Wissen unmittelbar nutzbar, sodass Effektivität und Innovationskraft spürbar steigen. 
Stand: MVP zur Meetingzieloptimierung und Agenda-Erstellung, Forschung zur kontextsensitiven KI-Moderation (Abschlussarbeit TU Darmstadt, Abgabe Oktober) und Netzwerk zu Facilitatoren aufgebaut.

*(841 / 850)*

### Innovationsbeschreibung (3000)

PROBLEM
In Deutschland verbringen Wissensarbeiter:innen ca. Ø5,2-12h pro Woche in Meetings. Bei Führungskräften sind 20h+ nicht selten. Studien gehen davon aus, dass 30-72% der Meetings ineffektiv sind und Meetings zu den unbeliebtesten Elementen des Arbeitsalltags zählen. Zu den gebundenen Personalkosten, kommt noch ein nicht zu unterschätzender Anteil an schwer zu quantifizierenden Faktoren, wie Zeitverlust bei Kontextwechsel und Motivationsverlust dank Meeting-Frust. Meetings sind somit ein enormer Kostenpunkt für viele Organisationen.

LÖSUNG
Gute Meetings hingegen sind kein Kostenfaktor, sondern ein Werttreiber: Sie steigern Zufriedenheit und helfen Teams innovative Lösungen zu generieren. Externe Hilfe und starre Regeln wirken oft nur punktuell, weil Teams keine Tools haben, ihre eigenen Meetings kontinuierlich selbst zu verbessern.
Meettopia unterstützt Teams von der Zieldefinition über strukturierte Agenden mit best-practice facilitation-Methoden bis zur Nachbereitung. Durch KI-gestützte Moderation und datenbasierte Insights (z. B. Redezeitanalyse, Stimmungsfeedback) werden Meetings fokussierter, kürzer und ergebnisorientierter. Individuelles datenbasiertes Feedback fördert Selbstreflexion, verbessert Kommunikationsskills und stärkt so die Meetingkultur.
Teams können eigene KI-Avatare mit Unternehmenswissen ausstatten und gezielt im Meeting einsetzen. Internes oder externes (über einen Marktplatz) Fachwissen ist so direkt verfügbar, wodurch Meetings fundierter, schneller und vielseitiger werden.

USP
Calendly, Zoom, Miro, Transkriptions-Tools und Meeting-Copilots lösen Teilprobleme (Termine, Whiteboards, Notizen). Sie adressieren Symptome, nicht aber die eigentlichen Probleme von Meetings: Struktur, Facilitation und kontinuierliche Verbesserung sind per Konstruktion der aktuellen Meeting-Tools unterrepräsentiert.

TECHNISCHE BESCHREIBUNG
Phase 1: Zieloptimierung und Agenda-Erstellung lassen sich gut mit LLM-Pipelines und RAG auf Facilitation-Best-Practices umsetzen. Die KI-Moderation braucht eine aufwendigere Reasoning-Pipeline: Während sprachbasierte KI-Systeme meist reagieren (z. B. nach Satzende), muss der Agent proaktiv in Gruppendiskussionen eingreifen können. Es ist nicht trivial diesen Zeitpunkt abzuschätzen. Das wird u. a. in meiner Abschlussarbeit (TU Darmstadt) erforscht. In Phase 1 werden überwiegend externe AI-APIs (z.B. Modelle von Mistral) genutzt.
Phase 2: Umstellung auf Open-Weight-Modelle und ggf. feinabgestimmte Modelle, um Datenhoheit zurückzugewinnen. Herausforderung: keinen Qualitätsbruch gegenüber den Cloud-APIs. Parallel soll Emotionserkennung in der Stimme als weitere Dimension hinzukommen, um kontextsensitivere Moderation und Insights zu ermöglichen.
Phase 3: Mit wachsenden Nutzerdaten können eigene Modelle für spezialisierte Teilprobleme (wie z.B. Timing zur Intervention oder Klassifikation von Meetingsituationen) trainiert werden. (bessere Qualität und Kostensenkung durch weniger Reasoning-Loops)

*(2984 / 3000)*

### Marktumfeld & Markteintritt (2200)

MARKT
Der Markt für Meeting-Optimierung ist fragmentiert. Getrieben durch Hybrid Work und den Anstieg an Meetings seit 2020 (Corona), wachsen Tools für Terminierung, Video, Whiteboards und KI-Notizen stark. Unterrepräsentiert bleiben Struktur, neutrale Moderation und datengestützte Verbesserung der Meeting-Kultur.

ZIELKUNDEN
Primär: Wissensteams, die komplex und kollaborativ arbeiten — Produkt-, Strategie-, Forschungs- und Kreativteams; besonders Agenturen, Beratung und innovativ arbeitende Mittelständler. Buyer: Teamleiter:innen, Projektmanager:innen, Scrum Master, Agile Coaches. Use Cases: Ideation/Design Thinking, Strategie-Workshops, cross-funktionales Alignment. Je größer die Organisation umso relevanter wäre eigentlich der Bedarf an Meettopia. Konzerne sind wegen langer Einkaufszyklen aber keine idealen ersten Kunden. Fokus der Validierung: agile Early Adopter mit hoher Meeting-Last und kurzem Entscheidungsweg.

UNFAIRER VORTEIL: DATENHOHEIT
Organisationen haben ein intrinsisches Interesse, Unternehmensgeheimnisse nicht weiterzugeben. In Meetings werden oft hochsensible Informationen besprochen. Meettopias unfairer Vorteil ist Datenhoheit: Standort Deutschland kommt zugute. Kein Cloud Act, wenn die Infrastruktur in Europa gehalten wird. Das schafft entscheidendes Vertrauen. Auch arbeitsrechtliche und regulatorische Anforderungen sind relevant; hier spielen die hohen Standortstandards zugunsten von Meettopia.

MARKTEINTRITT IN DREI PHASEN
Phase 1 (Pilot / LAISF): Markteintritt über persönliche Kontakte, insbesondere Facilitator:innen und bestehende Netzwerke. Ziel: mind. 1, ideal 3 Pilotkunden. Der MVP wird in realen Meetings getestet, Nutzen messbar gemacht und Feedback direkt in Produkt und Pricing eingearbeitet.

Phase 2 (SaaS): Nach validiertem Product-Solution-Fit Skalierung als SaaS für Teams. Parallel wird die Datenhoheit technisch und organisatorisch weiter ausgebaut (Open-Weight, europäische Infrastruktur).

Phase 3 (On-Demand-Hosting): Meettopia so anbieten, dass sensible Meeting-Daten die Infrastruktur des Kunden nie verlassen. Das öffnet mittel- bis langfristig regulierte und konzernnahe Segmente.

*(2152 / 2200)*

### Teamkompetenzen & LAISF-Vorhaben (2000)

TEAM
Solo-Founder: Oliver Hönig. Informatik-Studium an der TU Darmstadt; Abschlussarbeit zur kontextsensitiven, „protective“ KI-Moderation in zielorientierten Remote-Meetings — direkter Forschungsanker für Meettopia. Beruflich: ca. drei Jahre neben dem Studium in der IT-Beratung gearbeitet mit Fokus Software-Qualitätssicherung und DevOps (Konzern und Mittelstand). Das stärkt Anforderungen an Zuverlässigkeit, Testbarkeit und Integrationsqualität — zentral, wenn KI live in Meetings eingreift. Zusätzlich habe ich Connections zu Facilitator:innen aufgebaut: Zugang zu Methodenwissen, Feedback und potenziellen Pilotkanälen.

Ich bringe bereits einen abgeschlossenen Bachelor mit und beende meine aktuelle Abschlussarbeit voraussichtlich im Oktober; parallel arbeite ich in Teilzeit. Wenn möglich, starte ich LAISF daher zunächst in Teilzeit. Ich bin aber flexibel und kann mir vorstellen, ab Oktober/Dezember Vollzeit an Meettopia zu arbeiten.

Als Solo-Gründer setze ich klare Prioritäten und kann durch mein Informatikstudium fundierte technische Expertise einbringen. Zudem habe ich bereits mehrfach Projekte sowohl im Angestelltenverhältnis als auch in der Selbständigkeit eigenverantwortlich von der ersten Idee über den Vertragsabschluss bis zur erfolgreichen Umsetzung begleitet und verfüge daher über vielseitige Praxiserfahrung in verschiedenen Projektphasen.

LAISF-VORHABEN (Sep 2026 – Feb 2027)
Übergeordnetes Ziel: validierter Prototyp mit klarer Business-Perspektive und Traction durch Pilots — mindestens 1, idealerweise 3 Pilotkunden.

Zentrale Aktivitäten:
1) Bachelor-Forschung abschließen und Erkenntnisse zur kontextsensitiven KI-Moderation in Meettopia überführen.
2) MVP/Prototyp verfeinern (Zielsetzung, Agenda, erste Moderationsfähigkeiten).
3) Pilotkunden akquirieren und den Prototyp qualitätsgesichert auf den Launch mit Pilots vorbereiten.
4) Evaluierung und iterative Anpassung des Prototyps auf Basis des Feedbacks der Pilotkunden.

*(1963 / 2000)*

---

## Abschnitt 4 — Projektplan

### Gewünschtes Ziel (250)

MVP mit Ziel-/Agenda-Pipeline, Live-Transkription und erster proaktiver AI-Moderation in realen Pilots; mind. 1, ideal 3 Pilotkunden; klare Learnings und Business-Perspektive Richtung PMF.

*(188 / 250)*

### Meilenstein 1

**Fälligkeitsdatum:** 2026-10-31  
**Name (90):** BA-Transfer & Prototyp-Ausbau  
**Aktivitäten (320):** Bestehendes Konzept und Agenda-Prototyp um BA-Erkenntnisse zur proaktiven Moderation erweitern; Architektur und Tech-Stack (LLM-Pipelines, Mistral/Voxtral) darauf aufsetzen; Privacy-/BYO-Model skizzieren; Pilot-ICP und Hypothesen festlegen; Outreach starten.

*(Name 29 / 90 · Aktivitäten 258 / 320)*

### Meilenstein 2

**Fälligkeitsdatum:** 2026-12-15  
**Name (90):** MVP Prototype (Phase 1)  
**Aktivitäten (320):** Zielverfeinerung und Agenda-Erstellung produktiv nutzbar; Live-Transkription integriert; erste proaktive Moderationshinweise im Meeting; interne Tests und Facilitator-Feedback; Vorbereitung Pilot-Onboarding.

*(Name 23 / 90 · Aktivitäten 207 / 320)*

### Meilenstein 3

**Fälligkeitsdatum:** 2027-01-31  
**Name (90):** Pilot Launch & Validation  
**Aktivitäten (320):** Mindestens einen Pilotkunden onboarden; reale Meetings begleiten; Metriken und qualitative Interviews; Iteration an Interventionstiming und UX; parallel zweite/dritte Pilots akquirieren.

*(Name 25 / 90 · Aktivitäten 186 / 320)*

### Meilenstein 4

**Fälligkeitsdatum:** 2027-02-28  
**Name (90):** PMF-Signale & Roadmap Phase 2/3  
**Aktivitäten (320):** Pilot-Learnings verdichten; Pricing/ICP schärfen; Roadmap Phase 2 (Open-Weight, Datenhoheit, Stimme/Emotion) spezifizieren; Business-Perspektive und Folgefinanzierung dokumentieren; Projektdoku.

*(Name 31 / 90 · Aktivitäten 184 / 320)*

### Mittelverwendung (1200)

Die 5.000 € Materialbudget sollen gezielt für Validierung und MVP-Infrastruktur eingesetzt werden:

• ca. 1.800 € Cloud-/API (LLM-Pipelines, Live-Transkription Mistral/Voxtral) für Entwicklung + Pilots
• ca. 900 € Hosting/Infra (Staging/Prod, Logging, DSGVO-konforme Speicherung)
• ca. 1.000 € Nutzerforschung (Incentives Pilotteams, Facilitator-Workshops, Testaccounts)
• ca. 500 € Software/Tools (Prototyping, Analytics, Meeting-Integrationen)
• ca. 800 € Reise/Workshops zu Pilotterminen oder Events mit Validierungsnutzen

Bei erfolgreicher Mid-term-Präsentation und bis zu 30.000 € Zusatzförderung priorisieren wir:
• Ausbau der Pilotkapazität (weitere Teams, längere Begleitung)
• Gezielte Ansprache weiterer Pilotkunden durch teurere Akquisemaßnahmen (z.B. Messestand, Werbemittel)
• Erste Schritte Richtung Phase 2 (Open-Weight-Evaluation, Datenhoheit, ggf. Stimme/Emotion)
• Erste Experimente Richtung Interventions-Klassifikation (Datenpipeline, Evaluation)
• Stärkere Integration und Stabilität für produktiven Pilotbetrieb

*(1123 / 1200)*

---

## Abschnitt 5 — Erklärungen

Im Formular beide Checkboxen setzen:

1. **Förderfähigkeitserklärung** — Keine Kapitalgesellschaft für das Meettopia-Projekt gegründet; keine parallele öffentliche Förderung der geförderten Person im Stipendienzeitraum.
2. **Datenschutz** — [Datenschutzhinweis](https://aigude.ai/apply/laisf/datenschutz) gelesen und akzeptiert.

**Hinweis vor dem Absenden:** Bitte Eligibility kurz selbst prüfen (Balanced Bytes UG vs. Projektträger Meettopia; ggf. YBG vs. LAISF-Doppelförderung). Adresse und LinkedIn im Formular ergänzen. Absenden ist final.
