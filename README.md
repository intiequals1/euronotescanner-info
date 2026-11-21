# EuroNoteScanner – Übersicht

Stand: 21.11.2026

EuroNoteScanner war eine Webanwendung, mit der ich für mich selbst herausfinden wollte, wie man Bargeld mit Technologie auf Richtigkeit überprüfen kann: Foto eines Euro-Scheins hochladen, Seriennummer per Texterkennung (OCR) auslesen, Ziffern- und Quersumme berechnen, Ländercode bestimmen. Soweit mir zu dem Zeitpunkt bekannt war, haftet man selbst, wenn man auch unwissentlich mit Falschgeld etwas kaufen möchte.

Das Repository mit dem Quellcode ist seit 21.11.2026 privat. Diese Seite fasst zusammen, warum, und was an diesem Tag geschehen ist.

## Anlass

Die Anwendung hatte eine Speicherfunktion. Sie nahm Einträge ohne Anmeldung und ohne Prüfung an und schrieb sie in das öffentliche Repository – einschließlich des hochgeladenen Fotos. Foto und Seriennummer waren damit für alle abrufbar, auch über die Website.

Gespeichert waren zwei Einträge vom 31.05.2025 mit Seriennummer, Prüfsummen, Ländercode und demselben Foto eines Euro-Scheins. Frühere Fassungen der Datei vom 30.05.2025 enthielten Einträge ohne Foto. Es gibt keinen Hinweis darauf, dass Dritte die Speicherfunktion genutzt haben: Alle Einträge stammen aus Mai 2025, der letzte Commit vor dem 21.11.2026 war mein eigener vom 29.03.2026.

## Bedenken

- **Datenschutzrechtlich:** Hochgeladene Fotos wurden vollständig und öffentlich gespeichert.
- **Moralisch:** Der fotografierte Schein ist nicht mehr in meinem Besitz.

## Arbeitsverlauf am 21.11.2026

| Zeit (MEZ) | Schritt |
|---|---|
| ab 08:30 | Prüfung meiner Softwareprojekte nach dem EU Cyber Resilience Act (CRA). EuroNoteScanner ist danach kein CRA-Produkt (Browser-Anwendung, keine Einnahmen). Dabei fiel die ungeschützte Speicherfunktion auf. |
| 12:33 | Einträge und Quellstand privat archiviert. |
| 12:34 | Einträge aus dem aktuellen Stand gelöscht, Löschung im README dokumentiert. |
| 12:38 | Speicherfunktion abgeschaltet: Speichern und Laden entfernt, die Website speichert keine Analysen mehr. |
| 12:40 | Vollständige Historie privat gesichert, danach die Einträge aus der gesamten Git-Historie aller Branches entfernt. |
| 12:46 | Repository auf privat gestellt. |

## Erklärung

Die bisherigen Daten wurden von mir nicht für meinen Zweck verwendet. Ich hatte und habe nicht die Absicht dazu.

## Weitere Recherchen und Fragen

Wer sich für das Thema interessiert – die Echtheitsprüfung von Bargeld mit Technologie –, weitere Recherchen anstellen möchte oder Fragen zu diesem Vorgang hat, kann sich gerne an mich wenden: [dangulea.at](https://www.dangulea.at/)

Claudiu Dangulea, Wien
