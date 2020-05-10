# Stundenplan
## Information:
This Repository is avalabil in english: [here](https://github.com/DieserShyguy/timetable_english)
## Beispiel:
Hier finden sie ein Beispiel: [hier](https://diesershyguy.github.io/stundenplan_deutsch)
## Anleitung:
### Schritt 0: Herunterladen
Sie können sich die Datei hier runter laden: [Downloads](https://github.com/diesershyguy/stundenplan_deutsch/releases)
### Schritt 1 Datei bearbeiten:
Öffnen ```index.html``` in einen Editor zum Beispiel den Windows Standard Editor oder Notepad++ oder sie öffnen sie in einer IDE zum Beispiel in Visual Studio Code.
### Schritt 2 Einrichtung:
Suchen sie folgende Zeilen Code die normalerweise zwischen Zeile 19 und 23 sind:
```
                    ["Montag","1","2","3","4","5","6","7"],
                    ["Dienstag","1","2","3","4","5","6","7"],
                    ["Mittwoch","1","2","3","4","5","6","7"],
                    ["Donnerstag","1","2","3","4","5","6","7"],
                    ["Freitag","1","2","3","4","5","6","7"],
```
Ersetzen sie diese mit der folgende Zeile Code:
```
                    ["<DEIN TAG>","Stunde 1"],
```
**Sein sie sicher, dass sie die IMMER Leerzeichen mit kopieren!** Ersetzen sie ```<DEIN TAG>``` mit zum Beispiel Montag. Wenn sie mehrere Stundenpläne haben, die sich zum Beispiel jede Woche abwechseln, können sie vor den Tag eine Zahl schreiben. Das kann ungefähr so aus sehen: `1 Montag`
### Schritt 3: Unterrichtstunden Hinzufügen
Setzen sie nach den Anführungsstrichen ein Komma und setzen sie weitere Anführungsstrichen. In diesen können sie ihre Fächer hineinschreiben. Es könnte so aussehen:
```
                    ["Dienstag","Physik","Mathe","Sport",]
```
### Schritt 4: Tage Hinzufügen
Um Tage hinzuzufügen, müssen sie ans Ende der Zeile gehen und `Enter`. Wenn der Text Cursor am Anfang der Zeile ist und nicht unter den eckigen Klammern, dann drücken sie 5x `Tab`. Dann fügen sie diesen Code ein.:
```
                     ["<DEIN TAG>","Stunde 1"],
```
Ersetzen sie `<YOUR DAY>` wieder mit Etwas wie Montag. Der erste Eintrag der liste ist immer der Tag. **Geben sie dort NIE den Name der ersten Stunde ein!** Weil so in der Auswahlbox die erste Stunde zur Auswahl steht und nicht der Tag. Das ist unpraktisch zum wiederfinden von den Tagen.
### Schritt 5: Datei Speichern
Klicken sie auf Datei/File und Speichern/Save oder nutzen sie einfach die Tastenkombination `Strg + S` um zu Speichern.
### Schritt 6: Datei Öffnen / Bedienung der Anwendung
Navigieren sie zum Ordner, wo sich die ``index.html`` befindet. Führen sie einen Doppel-Klick auf der ```index.html``` aus. Danach sollte sich der Standard Browser öffnen und eine Auswahlbox anzeigen. Klicken sie darauf und sie sehen alle Tage die sie Eingetragen haben. Wenn sie einen Tag anklicken, erscheint der Stundenplan des Tages auf ihrem Bildschirm. Das war's!