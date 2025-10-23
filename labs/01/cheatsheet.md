### DIS08 Datenmodellierung  
16.10.2025  

#### **Basic Formatting**

* Headings:  
 Es gibt sechs verschiedene Überschrift Größen. (1 die größte, 6 die kleinste). Für Überschrift 1 setzen Sie ein # und ein Leerzeichen vor Ihren Text. Für Überschrift 2 setzen Sie zwei # vor Ihren Text. Für Überschrift 3, drei # und so weiter. (Überschrift 1 und 6 werden selten verwendet.)  
* line breaks: 
 Setzen Sie zwei Leerzeichen an das Ende der Zeile um einen Zeilenumbruch zu kreieren. 
* Italic:
 Setzen Sie folgendes Zeichen zu Beginn und an das Ende Ihres Textes: _  
_Italic_
* Bold:
 Setzen Sie folgendes Zeichen zu Beginn und an das Ende Ihres Textes: **
* Strikethrough:
 Setzen Sie zwei "~" zu begin und an das Ende Ihres Textes.
 ~~Text~~
* Inline Code:
 Setzen Sie einen Backtick zu Beginn und an das Ende Ihres Codes. Bei ganzen Codeblöcken, setzten sie drei davon "```".
 `www.google.com`


#### **Listen:**

* Unordered list
 Setzten Sie ein "*" und ein Leerzeichen vor jede Zeile der Liste. Dieses ändert sich zu einem typischen Listen Punkt.
* Geordnete Liste
 Für eine geordnete Liste mit Zahlen schreiben Sie diese auch genau so in Markdown. Wichtig zu beachten ist das Leerzeichen hnter der Zahl mit dem Punkt.
* Nested lists
 Unterlisten in Listen rückt man mit einem weiteren Leerzeichen ein. Eine weitere Liste in der Unterliste dann mit zwei Leerzeichen.

#### **Links & Images**  
Es gibt zwei verschiedene Link Arten in Markdown.

* Inline link
 Um einen Inline Link zu erstellen, fügt man den Link in folgende Klammern: []. Den Linktext fügt man in folgende Klammern: ().
Bsp.: [Search for it.](www.google.com)
* Reference-style link
 Für einen reference link setzt man oben im code den Namen für den Link in [] Klammern. Unten am Ende des Codes definiert man daraufhin die Namen zu den Links.  
   * Bsp.: Do you want to [see something fun][a fun place]?  
 [a fun place]: www.zombo.com
* Images
  *Inline image links: Setzen Sie zu Beginn ein "!". Darauf folgen "[]" Klammern, in denen der Text zum Bild steht. Zum Schluss folgen die "()" Klammern, in denen der Link zum Bild vorhanden ist.  
  *Reference image links: Setzen Sie zu Beginn ein "!". Daraufhin den Text zum Bild in "[]". Nun folgt der tag zum Bild, ebenfalls in "[]". Dieser wird zum Schluss definiert. 
     *Bsp.: 
    ![Black cat] [Black]
    [Black]: link zum Bild

#### **Code & Technical Content**
* Inline Code:
 Setzen Sie einen Backtick zu Beginn und an das Ende Ihres codes.
 `www.google.com`
* Fenced code blocks:
 Bei ganzen Codeblöcken, setzten sie drei Backticks "```" zu Beginn und an das Ende Ihres Codeblocks.
 Bsp:  
 ```
 Text
 Text
 ```

#### **Quotes & Notes**

* Blockquotes
 Um einen zitierten Text hervorzuheben müssen Sie zu Beginn ein ">" setzten.  
 Bei mehreren Paragraphen müssen Sie auch in die leeren Zeilen ein ">" setzen.

#### **Tables**
* Basic tables
  Mit senkrechten Strichen "|" und Bindestrichen `-` werden Spalten und Überschriften getrennt.
  Bsp.:
  | Name | Alter |
  |------|-------|
  | Lea  | 21    |
  | Tom  | 25    |
* Alignment
  Sie können den Text in Spalten links, zentriert oder rechts ausrichten, indem Sie Doppelpunkte (:) in der Trennzeile nutzen.
  Die Bindestriche - zeigen die Spalte an, die Doppelpunkte bestimmen die Ausrichtung:  
  Bsp.:
  | Links | Zentriert | Rechts |
  |:------|:----------:|-------:|
  |A      |B           |C       |
* Complex tables
  Für komplexe Tabellen nutzt man HTML-Syntax direkt im Markdown
  Bsp.:
  <table>
  <tr><th colspan="2">Überschrift</th></tr>
  <tr><td>A</td><td>B</td></tr>
  </table>
   
#### **Task Lists**
* Checkboxes
  Mit '- [ ]' (leer) und `- [x]` (abgehakt) lassen sich To-do-Listen erstellen.


Dividers & Layout

    Horizontal rules
    Line breaks

Online and collaborative editors

    Markdown-based editors

Platform/Tool Specific: GitHub

    Task lists
    Mentioning users (@username)
    Automatic linking of issues/PRs
    Emoji shortcodes




