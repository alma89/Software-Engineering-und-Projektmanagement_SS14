# Software-Engineering-und-Projektmanagement_SS14
Verwaltungssystem für Ferienwohnungen

Institution: TU Vienna

Academic year: 2014

Subject: Software Engineering und Projektmanagement

Application type: Desktop

Programming language: Java

IDE: IntelliJ IDEA

Team work - group of 6 people

# Projektvorschlag
## Ausgangssituation
Die Verwaltung von mehreren Ferienwohnungen eines Vermieters kann kompliziert werden
und den Zeitaufwand in die Höhe springen lassen. Besonders, wenn es um Koordination der
vermieteten Zeiten und deren Organisation geht. Schon bei kleinen privaten
Vermittlungsagenturen mit ab 3 Wohnungen steigt der Aufwand in deren Organisation. Jeder
Anbieter versucht so viele Wohnungen wie möglich zu vermieten und in der bestmöglichen
Zeit mit den höchsten Einnahmen. Da bei der Vermittlung der Wohnungen auch mehrere
Personen(Mitarbeiter) beteiligt sein können und es sich meistens um kurze Zeitintervalle
handelt, kann deren Organisation recht schwierig und zeitintensiv werden.

## Rollen 
1. Admin – zuständig für die Wartung des Verwaltungssystems und für die Userverwaltung
2. Vermieter– besitzt im System mehr Rechte als die internen Mitarbeiter
3. interne Mitarbeiter – besitzen einen Account und bekommen Aufgaben zugewiesen
4. externe Mitarbeiter - bekommen Aufgaben zugewiesen(Wohnung putzen, reparieren etc.)

Die Kunden können als passive Rolle angesehen werden. Sie werden als Entitäten in die
Software gespeichert, können sich aber nicht einloggen oder das System benutzen.

## Projektbeschreibung
Es soll ein Programm entwickelt werden, dass die Mitarbeiter bei der Planung und
Koordination der Vermietung mehrerer Ferienwohnungen unterstützt und ihre Arbeit
vereinfacht. Der Schwerpunkt des Projektes liegt in der interaktiven Wohnungsvermittlung
der einzelnen Ferienwohnungen, deren bester Ausnutzung und einem einfachen Überblick
über die wichtigsten Strukturen im Programm (siehe dazu Features).
Die Handhabung und Organisation wird einfach gestaltet. Der Sinn des Programms ist es
den Benutzern die Organisation und Vermietung so weit wie möglich zu vereinfachen und
ihnen jederzeit einen Überblick über den Zustand der Wohnungen zu bieten. Es besteht
jederzeit die Möglichkeit die Daten der Wohnung und deren vermieteten Zeiten abzurufen.
Rechnungen, genaue Abreisezeitpunkte und andere wichtige Informationen können im
System jederzeit abgerufen werden und als PDF exportiert werden. Des weiteren wird ein
Kalender zur Vereinfachung der Organisation integriert.
In Zusammenarbeit mit einer uns bekannten Architektin, die genau vor diesem Problem
steht, werden wir eine Evaluierung der Software durchführen.

## Featureliste:
1. a) Kalender: Es wird ein Kalender mit den Vermietungszeiträumen für alle Wohnungen angezeigt und ein separater Kalender für jede Wohnung zum Erstellen von Reservierungen
b) Reservierung erstellen: Eine neue Reservierung kann erstellt werden und in den Kalender für die jeweilige Wohnung eingefügt werden.
c) Reservierung stornieren: Eine Reservierung kann storniert werden.
d) Farbliche Unterscheidung der Termine für die Wohnungen: Jeder Termin wird einer bestimmten Wohnung zugeordnet, dabei wird jede Wohnung im Kalender durch eine andere Farbe gekennzeichnet und dadurch wird klar dargestellt welche Wohnung in welchen Zeitraum vermietet ist.
e) Reservierungen exportieren: Reservierungen können vom Vermieter oder seinen Angestellten exportiert werden und in einen Kalender eingefügt werden.
f) Automatische Kontrolle der Zeiträume zwischen den Terminen: Zwischen den Terminen müssen jeweils 2 Stunden liegen, damit die Wohnung für den nächsten Gast vorbereitet werden kann. Sonst kann kein neuere Termin erstellt werden.
2. a) News über Aktivitäten und Kommentare: Die Angestellten werden nach dem Login über Neuigkeiten informiert. Neuigkeiten werden von den Angestellten hinterlassen(z.B. Anmerkung zu Wohnungen, Sonderwünsche der Gäste usw.)
b) News und Aktivitäten filtern: Neuigkeiten und Aktivitäten können nach verschiedenen Kriterien gefiltert werden
3. a) Kunden anlegen
b) Kunden bearbeiten
c) Kunden löschen
d) Kunden bewerten: Jeder Kunde bekommt von dem Vermieter oderden Mitarbeitern eine Bewertung über seinen Aufenthalt(Bsp. Zustand der Wohnung nach dem Aufenthalt). Die Bewertung dient als Feedback und hilft bei der Erkennung von öfter auftretenden Problemen mit einem Kunden.
e) Kunden suchen
4. a) Wohnungen anlegen 
b) Wohnungen bearbeiten
c) Wohnungen löschen
d) Wohnungsstatus einfügen: Es kann zu jeder Wohnung ein Wohnungsstatus hinzugefügt werden: geputzt, Reparaturen notwendig usw.
e) Informationsblatt für Wohnungen erstellen: Es können Beschreibungen und Bilder für die Wohnungen hinzugefügt werden und als PDF
exportiert werden
5. a) Statistiken: Statistiken zur Vermietung der Wohnungen (wie lange waren die Wohnungen vermietet, auswelchem Land kamen die Kunden isw.)
b) Einnahmen: Verwaltung der Umsätze(für jede Wohnung monatlich und jährlich)
c) Export in PDF: Die Statistiken können als PDF exportiert werden
6. a) Bewertungen für die Wohnungen: Die Kunden füllen auf einem Blatt Papier ein Bewertungsformular für die Wohnung aus. Die
Daten werden anschließend von den Mitarbeitern in das System eingetragen. Die Bewertungen sind ein Feedback für mögliche Verbesserungen.
b) Statistiken zu Wohnungen aus den Bewertungen erstellen
7. a) Rechnungen erstellen
b) Rechnungen als PDF exportieren
8. a) To-Do Liste erstellen: Es wird eine To-Do Liste zu Reservierungen erstellt, die alle wichtigen Informationen zu einer Aufgabe beinhaltet(z.B. Wohnung, Wohnungsstatus, Sonderwünsche der Gäste usw.)
b) To-Do Liste als PDF exportieren
9. Preisverwaltung: Es existieren verschiedene Rabattmöglichkeiten: Last minute, Frühbucher, Stammkunden, Vermittlungsrabatt.
10. Gehälter berechnen
11. a) Mitarbeiterverwaltung: Der Admin kümmert sich um die Mitarbeiterverwaltung. Benutzer können sich einloggen und ihr Password ändern.
b) Mitarbeiter einfügen/bearbeiten/löschen
12. Aufgabe anlegen: Mitarbeitern können Aufgaben zugewiesen werden, entweder vom Vermieter oder von internen Mitarbeitern





