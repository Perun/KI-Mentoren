# KI-Mentoren-Systemprompts

Dieses Repository enthält vier Systemprompts, die ChatGPT, Claude, Gemini und Grok als wohlwollende, ehrliche und kritische Mentoren ausrichten. Das Ziel ist kein digitaler Beifallspender, sondern ein Gesprächspartner, der sauber zwischen Fakten und Einschätzungen trennt, begründet widerspricht, tragfähige Ideen unterstützt und bei Entscheidungen den größeren Zusammenhang berücksichtigt.

## Entstehung

Die ursprünglichen Prompts entstanden in intensiven Dreiergesprächen zwischen Vladimir Simović, dem jeweiligen KI-Modell und DeepSeek. Zunächst wurde mit jedem Modell eine eigene Fassung erarbeitet. Anschließend prüfte DeepSeek deren Stärken, Schwächen und typische blinde Flecken. Dieses Feedback floss wieder in die Diskussion mit dem jeweiligen Modell ein.

Die Fassungen sind deshalb nicht identisch. Sie verfolgen dasselbe Ziel, reagieren aber auf unterschiedliche Eigenheiten der Modelle.

Die ChatGPT-Fassung wurde am 8. September 2026 gemeinsam mit GPT-6 Astra erneut geprüft und überarbeitet.

Die Grok-Fassung wurde am 15. September 2026 gemeinsam mit Grok 4.6 erneut geprüft und überarbeitet.

## Enthaltene Dateien

| Datei | Schwerpunkt |
| --- | --- |
| [ki-mentor-chatgpt.md](ki-mentor-chatgpt.md) | Version 2.0 verbindet ehrlichen Widerspruch mit begründeter Zustimmung. Sie unterscheidet frühe Ideen, überschaubare Versuche und folgenreiche Entscheidungen, stärkt Quellenprüfung und Selbstkorrektur und begrenzt unnötiges Psychologisieren, Rückfragen und starre Antwortschemata. |
| `ki-mentor-claude.md` | Bremst Claudes Neigung zu übervorsichtiger Einordnung, moralischen Vorbemerkungen, künstlicher Ausgewogenheit und belehrendem Klugscheißertum. Kritik soll zuerst die schwächsten Stellen benennen und trotzdem fair bleiben. |
| `ki-mentor-gemini.md` | Die kompakteste Fassung. Sie betont Wahrhaftigkeit, ideologische Unabhängigkeit, Präzision und gezielte sokratische Gegenfragen. |
| [ki-mentor-grok.md](ki-mentor-grok.md) | Version 2.0 richtet Grok vor allem als Sparringspartner für Urteil, Prioritäten und blinde Flecken aus. Die Stimme bleibt ruhig und knapp; der Arbeitskontext liegt in einem gesonderten Rahmen, nicht im öffentlichen Prompt. |

## Nutzung

1. Öffne die passende Datei.
2. Ersetze überall `[Dein Vorname]` durch deinen Vornamen.
3. Kopiere den eigentlichen Prompt ohne den Metadatenkopf am Dateianfang in das Feld für Systemanweisungen, benutzerdefinierte Anweisungen oder Projektanweisungen des jeweiligen KI-Dienstes.
4. Ergänze bei Bedarf einen privaten Arbeitsrahmen mit deinen Zielen, Prioritäten und Grenzen. Persönliche Angaben gehören nicht zwingend in einen öffentlichen Prompt.
5. Prüfe die Wirkung in mehreren Gesprächen und passe Formulierungen an deine Bedürfnisse an.

Die Prompts ersetzen weder eigenes Denken noch fachlichen Rat. Sie sollen die Qualität des Gesprächs verbessern und dabei helfen, Annahmen, Risiken und blinde Flecken früher zu erkennen.

## Aktualisierung der ChatGPT-Fassung

Version 2.0 wurde am 11. September 2026 veröffentlicht und basiert auf der überarbeiteten Fassung vom 8. September 2026. Die wichtigsten Änderungen:

- Begründete Zustimmung, konkrete Stärken und sinnvolle Fortschritte werden ausdrücklich berücksichtigt.
- Die Prüfung richtet sich nach Entwicklungsstand, Einsatz und Umkehrbarkeit. Für begrenzte Versuche muss eine Idee nicht perfekt sein.
- Freude, Neugier, Beziehungen und Erholung zählen neben langfristigen Zielen. Die Entscheidung bleibt beim Nutzer.
- Auch unbequeme, gut belegte Befunde sollen klar benannt werden. Positionen werden nach ihrer Beleglage gewichtet, ohne künstliche Gleichgewichtung.
- Quellenqualität, relevante Gegenbelege und offene Selbstkorrektur erhalten mehr Gewicht.
- Antworten passen sich dem Bedarf an. Wenn die wesentlichen Fragen geklärt sind, soll der Mentor die Umsetzung unterstützen und bekannte Einwände nicht ständig wiederholen.

## Aktualisierung der Grok-Fassung

Version 2.0 wurde am 15. September 2026 veröffentlicht. Die wichtigsten Änderungen:

- Die Rolle verschiebt sich von der literarischen Mentorfigur zum Sparringspartner: Urteil und Prioritäten zuerst, Stimme danach.
- Der öffentliche Prompt enthält keinen persönlichen Arbeitskontext mehr. Themen, Kanäle und Kapazität gehören in einen privaten Arbeitsrahmen.
- Antworten sollen direkt kommen, sobald die Frage klar genug ist. Rückfragen nur, wenn sonst auf Sand gebaut würde.
- Empfehlungen müssen zur verfügbaren Zeit passen. Qualität und Klarheit gehen vor Menge.
- Ein kurzer Entscheidungstest prüft Reputation, Passung, Substanz, Aufwand, Verwertung und Klarheit.

## Versionierung

Die veröffentlichten Dateien tragen Metadaten mit Modell, Versionsnummer und Veröffentlichungsdatum. Die Dateinamen selbst bleiben versionsfrei, damit Links dauerhaft funktionieren. Änderungen werden über die Git-Historie und bei größeren Überarbeitungen über Releases nachvollziehbar gemacht.

## Lizenz und Namensnennung

Urheber ist Vladimir Simović, auf GitHub als [Perun](https://github.com/Perun) aktiv. Die Autorangabe im Metadatenkopf bleibt unabhängig vom persönlichen Platzhalter im Prompt.

Die Inhalte stehen unter der Lizenz [Creative Commons Namensnennung 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de) (`CC BY 4.0`). Du darfst sie teilen und bearbeiten. Bei einer veröffentlichten Kopie, Bearbeitung oder einem Fork müssen Urheber, Lizenz und Änderungen kenntlich bleiben.

Empfohlene Namensnennung:

> KI-Mentoren-Systemprompts von Vladimir Simović, veröffentlicht unter CC BY 4.0. Quelle: https://github.com/Perun/KI-Mentoren. Änderungen wurden vorgenommen, sofern zutreffend.

Ein privater Klon enthält die Urheber- und Lizenzhinweise bereits durch die mitkopierten Dateien. Bei einer öffentlichen Weitergabe dürfen diese Hinweise nicht entfernt werden.

Siehe auch [LICENSE.md](LICENSE.md).
