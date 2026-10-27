# Forschungsatlas · AG Digitale Translation

[Atlas öffnen](https://masannecklab.github.io/forschungsatlas/) · [Website der Arbeitsgruppe](https://www.digitale-translation.de/)

49 publizierte Beiträge aus Digital Health und Neurologie mit Beteiligung von Lars Masanneck, einschließlich Kooperationen und früherer Arbeiten. Die Sammlung ist kein vollständiges Verzeichnis aller Arbeiten sämtlicher AG-Mitglieder. Stand: 27. Oktober 2026.

Sechs Studien lassen sich interaktiv erkunden: Schlaganfallversorgung, Leitlinien-RAG, CIDP-Aktivität, LLM-Triage, Gehfunktion bei MS und Schlafmonitoring bei CIDP. Publizierte Werte und konstruierte Beispiele sind in jeder Ansicht getrennt gekennzeichnet. Quellen und Aussagegrenzen stehen direkt bei den Darstellungen.

## Nutzung

`index.html` enthält die vollständige öffentliche Anwendung. Sie benötigt keine Installation, externen Skripte, Schriften oder Analyse-Dienste. Publikationslinks öffnen die Originalquellen. Die Merkliste wird im Browser gespeichert; sie wird nicht an einen Server gesendet. GitHub Pages übernimmt das Hosting.

## In die AG-Website einbetten

`ionos-embed.html` enthält den Code für ein HTML-Modul in IONOS MyWebsite NOW. Auf einer Seite „Forschung erleben“ einfügen. Das Modul ist tarifabhängig; [IONOS-Anleitung](https://www.ionos.de/hilfe/websites-shops/bearbeitung-von-mywebsite-now-inhalten/verwenden-von-html-und-javascript/).

Die Einbettung passt ihre Höhe per `postMessage` an und prüft Absender-Origin und Fenster. Die Höhe ist auf einen nutzbaren Bildschirmbereich begrenzt; längere Inhalte scrollen innerhalb des Atlas. Dadurch bleiben auch Publikationsdetails in der langen Bibliografie gut erreichbar. Ohne JavaScript zur Höhenanpassung bleibt das iframe mit einer festen Ausgangshöhe scrollbar. Der Link oberhalb öffnet den Atlas separat.

`?embed=1` reduziert die doppelte Kopfzeile, die Studiennavigation bleibt erhalten. `parentOrigin` wird vom Einbettungscode aus der tatsächlichen Elternseite gesetzt. Es werden ausschließlich Höhenangaben übertragen. Bei Verwendung in einem anderen Website-Baukasten kann das gleiche HTML-Modul genutzt werden.

## Veröffentlichung und Aktualisierung

Dieses Repository enthält die geprüfte öffentliche Ausgabe. GitHub Pages veröffentlicht `main` aus dem Stammverzeichnis; `.nojekyll` deaktiviert die Jekyll-Verarbeitung. Eine neue geprüfte `index.html` ersetzt die bisherige Datei und wird über einen normalen Commit veröffentlicht. Keine Zugangsdaten oder unveröffentlichten Arbeitsunterlagen in dieses Repository aufnehmen.

[Impressum](https://www.digitale-translation.de/impressum/) · [Datenschutzerklärung](https://www.digitale-translation.de/datenschutzerklaerung/)
