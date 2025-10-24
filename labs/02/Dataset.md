### Dataset

#### 1. [Mein Dataset](https://offenedaten-koeln.de/dataset/freiwillige-feuerwehr-koeln-personalzahlen-2023)


#### 2.  
* Title & Source (where you found it)
Titel: Freiwillige_FW_Einheiten_2023  
Source: [Offene Daten Köln](https://offenedaten-koeln.de/dataset/freiwillige-feuerwehr-koeln-personalzahlen-2023) 
* File Format
 CSV-Datei
* Size (rows, columns, or file size)
 rows: 28  
 colums: 3  
 file size: 812 Bytes
* Basic statistics (e.g., ranges, averages, min/max for numeric columns)

Gesamtanzahl der Einheiten der Freiwillige Feuerwehr Koeln 2023: 27

Durchschnittliche Werte

|aktive Mitglieder  |davon Frauen  |
|:-----------------:|:------------:|
|35,89              |3,67          |

|         |Einheit  |Anzahl aktiver Mitglieder |
|:-------:|:-------:|:------------------------:|
|max. Anzahl|Umweltschutzdienst|74  |
|min.Anzahl|Loeschgruppe Libur|18|
* Geographic or temporal coverage (e.g., “Covers traffic data in New York, 2015–2023”)
 Die Daten zeigen die Personalzahlen der Freiwillige Feuerwehr in Köln, im Jahr 2023.
* License (Is it open? What are the conditions for reuse?)
 Datenlizenz Deutschland – Zero – Version 2.0  
Jede Nutzung ist ohne Einschränkungen oder Bedingungen zulässig.


#### 3.  
Mögliches passendes Dataset: Einwohneranzahl pro Stadtteil in Köln, 2023.

* How the two datasets could be linked or compared
   * Man kann die Anzahl der Aktiven Mitglieder der FF. und die Einwohneranzahl des jeweiligen Stadtteils in Verbindung bringen.
   * Wie korreliert die Einwohnerzahl eines Stadtteils mit der Größe der freiwilligen Feuerwehr dort?
   * Welche Löschgruppen haben relativ zur Einwohnerzahl viele Mitglieder?
   * Wie variiert der Frauenanteil in der Feuerwehr im Verhältnis zum Anteil Frauen in der Bevölkerung des Gebietes?
* What kinds of research questions could be answered by combining them
   * Gibt es Stadtteile mit hoher Einwohnerzahl aber relativ wenigen freiwilligen Feuerwehrmitgliedern?
   * Wie groß ist der Anteil von Frauen bei der freiwilligen Feuerwehr pro Gebiet, und wie steht dieser im Verhältnis zum Frauenanteil in der Gesamtbevölkerung des Gebiets?
* What kinds of next steps would be necessary to merge the datasets?
   1. Einwohnerdaten importieren
   2. Gemeinsame Schlüsselelemente finden
   3. Zusammen führen 
   4. Berechnungen durchführen
   5. Analysieren & Visualisierung
   6. Interpretation

#### 4.  
FAIR principles (Findable, Accessible, Interoperable, Reusable)

* Findable: Is the dataset easy to locate with sufficient metadata?
 Ja. Auf der Seite: Offene Daten Köln, ist er sehr einfach auffindbar.  
 Auch wenn man folgendes bei Google eingibt werden die Daten sofort angezeigt. (Personalzahlen der Freiwillige Feuerwehr in Köln, im Jahr 2023)
* Accessible: Can anyone download it without barriers?
 Ja. Die Daten sind für alle frei zugänglich.
* Interoperable: Is it provided in a machine-readable, standard format?
 Ja. Teilweise bis vollständig interoperabel, weil:
   * Maschinenlesbares Format: CSV-Datei (Comma Separated Values).  
     (CSV ist ein offener, standardisierter, maschinenlesbarer Formattyp, der problemlos in Tools wie Excel, R, Python, Power BI etc. importiert werden kann.)
   * Klare Struktur:  
     Eine Kopfzeile (Einheit, aktive Mitglieder, davon Frauen) ist vorhanden.  
     Jede Zeile steht für einen Datensatz (eine Löschgruppe).

     Das erfüllt typische Anforderungen an tabellarische Open-Data-Formate.
   * Kein proprietäres Format:
     Es ist nicht an spezielle Software gebunden (z. B. kein .xlsx- oder .sav-Format).
* Reusable: Is the license clear, and is the documentation sufficient for reuse?
 Ja. Da es sich um folgende Lizenz handelt: Datenlizenz Deutschland – Zero – Version 2.0  
 Jede Nutzung ist ohne Einschränkungen oder Bedingungen zulässig.
