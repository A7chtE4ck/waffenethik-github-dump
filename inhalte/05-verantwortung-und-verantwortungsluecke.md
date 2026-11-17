# Verantwortung und Verantwortungslücke

## Moralische Verantwortung

Moralische Verantwortung bedeutet, für Handlungen, Unterlassungen oder deren vorhersehbare Folgen verantwortlich zu sein. Sie setzt normalerweise voraus, dass eine Person oder Institution über Wissen, Entscheidungsmacht und Handlungsalternativen verfügte.

Bei Waffensystemen ist Verantwortung daher mehrdimensional. Nicht nur die Person, die einen Angriff auslöst, trägt Verantwortung. Auch jene, die ein System entwickeln, finanzieren, genehmigen, verkaufen, einsetzen oder überwachen, können moralisch relevant beitragen.

## Verantwortliche Akteure

| Akteur | Art der Verantwortung | Typische Handlungsmöglichkeiten |
|---|---|---|
| Staat | Politische und rechtliche Verantwortung | Beschaffung, Einsatzregeln, Aufsicht, völkerrechtliche Bindungen |
| Militärführung | Operative und rechtliche Verantwortung | Befehle, Zielprüfung, Einsatzbegrenzung, Schulung |
| Hersteller | Produkt- und unternehmerische Verantwortung | Design, Tests, Dokumentation, Exportkontrollen |
| Entwickler:innen | Technische und berufliche Verantwortung | Sicherheitsdesign, Testabdeckung, interne Kritik, Verweigerung |
| Management | Organisatorische Verantwortung | Risikomanagement, Ressourcen, Freigabeprozesse |
| Bediener:innen | Unmittelbare Einsatzverantwortung | Zielprüfung, Eingriff, Deaktivierung, Dokumentation |
| Investor:innen | Finanzielle Mitverantwortung | Finanzierung, Anforderungen an Risikomanagement und Ethik |
| Zivilgesellschaft | Demokratische und kritische Verantwortung | Transparenz, Regulierung, unabhängige Prüfung |

## Verantwortung von Entwickler:innen

Entwickler:innen sind nicht automatisch für jeden späteren Einsatz verantwortlich. Sie tragen jedoch Verantwortung, wenn sie über spezifisches Wissen verfügen und technische Entscheidungen mittragen, die die Risiken des Einsatzes wesentlich beeinflussen.

Besonders relevant sind:

- Die Entscheidung, ob ein System vor einem Angriff eine menschliche Freigabe verlangt.
- Die Zuverlässigkeit von Zielerkennung und Klassifikation.
- Das Verhalten bei Sensorausfällen, Datenfehlern oder Manipulation.
- Die Möglichkeit, das System zu stoppen oder zu deaktivieren.
- Die Dokumentation von Tests, Grenzen und bekannten Fehlern.
- Die Kenntnis möglicher Missbrauchs- oder Exportrisiken.

Die IEEE betont, dass autonome Systeme verlässlich unter menschlicher Kontrolle bleiben müssen. Fehlende Auditierbarkeit, unklare Verantwortlichkeiten und nicht nachvollziehbare Entscheidungen sind daher keine bloßen technischen Mängel, sondern ethisch relevante Designentscheidungen. [IEEE EAD]

## Rechtliche Verantwortung

Rechtliche Verantwortung ist enger gefasst als moralische Verantwortung. Sie erfordert in der Regel eine konkrete Rechtsnorm, eine Pflichtverletzung und eine nachweisbare Verursachung.

Im Kontext autonomer Waffensysteme können mehrere rechtliche Verantwortlichkeiten entstehen:

- **Staatsverantwortlichkeit:** Ein Staat kann für Verletzungen des Völkerrechts verantwortlich sein, die durch seine Streitkräfte oder unter seiner Kontrolle erfolgen.
- **Individuelle strafrechtliche Verantwortung:** Befehlshaber, Bediener oder andere Beteiligte können für Kriegsverbrechen oder andere schwere Verstöße verantwortlich sein.
- **Unternehmensverantwortung:** Unternehmen können durch Verträge, Exportkontrollen, Haftungsregeln und Compliance-Anforderungen betroffen sein.
- **Haftung für Produktfehler:** Fehlerhafte Software, unzureichende Tests oder irreführende Dokumentation können zivilrechtliche Haftungsfragen auslösen.

Rechtliche Haftung ersetzt moralische Verantwortung jedoch nicht. Eine Person kann rechtlich nicht belangt werden, aber dennoch moralisch verantwortlich sein, etwa weil sie ein bekanntes Risiko ignoriert hat.

## Humanitäres Völkerrecht

Das humanitäre Völkerrecht verpflichtet Menschen, nicht Maschinen. Die ICRC formuliert dies ausdrücklich: Nicht das Waffensystem muss das IHL einhalten, sondern die Menschen, die es verwenden. [ICRC 2026]

Das hat zwei Konsequenzen:

1. Verantwortung darf nicht an die Technik delegiert werden.
2. Technik muss so gestaltet sein, dass Menschen ihre rechtlichen Pflichten überhaupt erfüllen können.

Ein System, das zu schnell, zu intransparent oder zu unzuverlässig entscheidet, kann die Fähigkeit von Bediener:innen untergraben, Unterscheidung, Verhältnismäßigkeit und Vorsichtsmaßnahmen zu prüfen. [ICRC 2026]

## Verantwortungslücke

Die Verantwortungslücke beschreibt die Gefahr, dass bei einem Fehlverhalten eines autonomen Systems niemand eindeutig verantwortlich gemacht werden kann.

Typische Konstellation:

- Der Entwickler wusste den konkreten Einsatz nicht.
- Der Bediener verstand die Entscheidung des Systems nicht.
- Der Befehlshaber delegierte die Entscheidung an die Technik.
- Das System selbst kann nicht moralisch verantwortlich sein.

Die Antwort darf nicht sein, Verantwortung einfach an die Maschine zu verschieben. Stattdessen muss Verantwortung durch Design, Dokumentation, Zuständigkeiten, Schulung, Aufsicht und rechtliche Regeln zuordenbar bleiben. [ICRC 2026][IEEE EAD]

## Verantwortung durch Design

Ein verantwortungsfähiges System sollte mindestens folgende Merkmale besitzen:

- Klare Zuständigkeiten vor, während und nach dem Einsatz.
- Nachvollziehbare Entscheidungswege und Audit-Trails.
- Zuverlässige Test- und Validierungsverfahren.
- Eingriffs- und Deaktivierungsmöglichkeiten.
- Begrenzte Einsatzbereiche und Zieltypen.
- Dokumentation bekannter Risiken und Fehlerfälle.
- Unabhängige ethische, rechtliche und technische Prüfung.

Diese Anforderungen folgen aus der Forderung nach sinnvoller menschlicher Kontrolle. [IEEE EAD] Sie entsprechen auch den Forderungen des ICRC nach wirksamer Aufsicht, zeitnahem Eingriff und Deaktivierung. [ICRC 2021]
