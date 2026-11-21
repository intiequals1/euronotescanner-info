# EuroNoteScanner – Übersicht

Stand: 21.11.2026

EuroNoteScanner war eine Webanwendung, mit der ich für mich selbst herausfinden wollte, wie man Bargeld mit Technologie auf Richtigkeit überprüfen kann: Foto eines Euro-Scheins hochladen, Seriennummer per Texterkennung (OCR) auslesen, Ziffern- und Quersumme berechnen, Ländercode bestimmen. Soweit mir zu dem Zeitpunkt bekannt war, haftet man selbst, wenn man auch unwissentlich mit Falschgeld etwas kaufen möchte.

Das Repository mit dem Quellcode ist seit 21.11.2026 privat. Diese Seite fasst zusammen, warum, und was an diesem Tag geschehen ist.

## Anlass

Die Anwendung hatte eine Speicherfunktion, die analysierte Scheine samt Foto in das öffentliche Repository schrieb.

Gespeichert waren zwei Einträge vom 31.05.2025 mit Seriennummer, Prüfsummen, Ländercode und demselben Foto eines Euro-Scheins. Frühere Fassungen der Datei vom 30.05.2025 enthielten Einträge ohne Foto. Es gibt keinen Hinweis darauf, dass Dritte die Speicherfunktion genutzt haben: Alle Einträge stammen aus Mai 2025, der letzte Commit vor dem 21.11.2026 war mein eigener vom 29.03.2026.

## Bedenken

### Datenschutzrechtlich

- Die Seite versprach, Einträge „verschlüsselt in einem privaten GitHub-Repository“ zu speichern. Tatsächlich lagen sie unverschlüsselt in einem öffentlichen Repository.
- Hochgeladene Fotos wurden vollständig gespeichert und waren für alle abrufbar, auch über die Website.
- Jeder Eintrag verband eine bestimmte Banknote – Seriennummer und Foto – mit meinem GitHub-Konto und einem genauen Zeitpunkt.
- Fotos können mehr zeigen als den Schein, etwa Hände oder die Umgebung der Aufnahme.
- Was in einem öffentlichen Repository liegt, bleibt in der Git-Historie und in Kopien erhalten, auch wenn die Datei später gelöscht wird.

### Abbildung von Euro-Banknoten

Für Abbildungen von Euro-Banknoten gelten die [Reproduktionsvorschriften der Europäischen Zentralbank](https://www.ecb.europa.eu/euro/html/reproduction.de.html) (Beschluss EZB/2013/10). Nach den Erläuterungen der EZB müssen digitale Abbildungen den Schriftzug „SPECIMEN“ tragen; in Originalgröße ist die Auflösung auf 72 dpi begrenzt. Verantwortlich ist, wer die Abbildung herstellt. Die gespeicherten Fotos trugen keinen solchen Schriftzug.

### Sicherheit

Die Speicherfunktion war ohne Anmeldung erreichbar. Jeder hätte damit Inhalte in mein öffentliches Repository schreiben können.

### Moralisch

Der fotografierte Schein ist nicht mehr in meinem Besitz.

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

Fotografiert habe ich ausschließlich einen Schein aus meinem eigenen Besitz. Zum Zeitpunkt der Aufnahme durfte ich rechtmäßig über ihn verfügen. Banknoten anderer Personen habe ich nicht fotografiert.

Zweck der Verwendung der bisherigen Daten war ausschließlich, die Technologie zu überprüfen, mich über rechtliche und ethische Themen zu informieren, bei rechtlichen Informationen auf dem aktuellen Stand zu bleiben und mich moralisch zu bilden. Für andere Zwecke habe ich sie nicht verwendet, und ich hatte und habe nicht die Absicht dazu.

### In einfachen Worten

- Der Geldschein auf dem Foto war mein eigenes Geld. Ich durfte ihn fotografieren und ausgeben.
- Geld von anderen Menschen habe ich nicht fotografiert.
- Ich habe die Daten nur für einen Zweck benutzt: um die Technik auszuprobieren und um zu lernen, was Gesetze erlauben und was richtig und fair ist. Für etwas anderes habe ich sie nicht benutzt, und ich werde es auch nicht tun.

## Weitere Recherchen und Fragen

Wer sich für das Thema interessiert – die Echtheitsprüfung von Bargeld mit Technologie –, weitere Recherchen anstellen möchte oder Fragen zu diesem Vorgang hat, kann sich gerne an mich wenden: [dangulea.at](https://www.dangulea.at/)

Claudiu Dangulea, Wien
