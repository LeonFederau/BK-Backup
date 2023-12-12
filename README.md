Projektidee
===========
Lehrer haben alle Schülerdaten zentral auf einem USB-Datenträger.
Der jeweilige Datenträger ist Bitlocker-verschlüsselt und wird fertig
vorbereitet von der Schulleitung zur Verfügung gestellt.

Das Backup des Datenträgers soll automatisiert erfolgen (ohne User-Eingriff).
Die Sicherung der Daten soll im pädagogischen Netz im persönlichen Bereich 
des Benutzers abgelegt werden.
Der Datenträger soll automatisch beim Einstecken erkannt werden und
entscheiden, ob gesichert werden muss. Falls gesichert werden muss, soll diese
automatisch durchgeführt werden (täglich).
Falls die Sicherung der Daten unterbrochen wird, soll beim nächsten
Einstecken diese fortgesetzt werden.

Bei Verlust eines Datenträgers kann eine Wiederherstellung der Daten auf einen
neuen Datenträger erfolgen.

Die gesicherten Daten sollen versioniert werden, so dass die Rekonstruktion
der Daten von einem beliebigen Zeitpunkt aus der Vergangenheit erfolgen kann.

Idee:	Reverse Incremental Backup<br>
Option	Rekonstruieren von Einzeldateien / Verzeichnissen

Rahmenbedingungen
================= 
- Sicherung des Speichermediums 
- Schutz vor unerlaubtem Zugriff 
- Barrierefreiheit
- Berechtigung
- Betriebssystem
- Speicherplatz
- Ein persönliches Laufwerk im Netz (U:\)
