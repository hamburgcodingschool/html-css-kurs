# HTML und CSS Kurs 2019


| Kategorie                      | Keine Kenntnisse | Grundkenntnisse | Erweiterte Kenntnisse |
| ------------------------------ | :--------------: | :-------------: | :-------------------: |
| HTML Syntax                    |                  |                 |           x           |
| HTML Grundstruktur             |                  |                 |           x           |
| HTML Elemente                  |                  |                 |           x           |
| HTML Header Informationen      |                  |        x        |                       |
| HTTP                           |                  |        x        |                       |
| CSS Naming Convention: BEM     |                  |        x        |                       |
| CSS Selektoren                 |                  |        x        |                       |
| CSS Positionierung (auch flex) |                  |                 |           x           |
| Responsive / Adaptive Design   |                  |                 |           x           |
| CSS Animationen                |        x         |                 |                       |
| Ordner-/Projektstrukturen      |        x         |                 |                       |
| Chrome DevTools                |                  |                 |           x           |
| Git                            |                  |        x        |                       |
| SCSS                           |        x         |                 |                       |
| Gulp / Grunt (Prebuilding)     |        x         |                 |                       |

## Tag 1
* Kennenlernen
* Methoden, Werte, Regeln
* Setup: git, VS Code, GitHub-Account und -Repository: *html-css-kurs*
* The twenty-eight elements used on most pages, ordered by appearance frequency https://www.advancedwebranking.com/html/
* Aufgabe: Kontaktformular

## Tag 2
* Review (ca. 30 min)
    * Was sind die 3 Hauptelemente einer jeden HTML-Struktur?
    * Welche Elemente haben keinen Content? -> input, img, meta, br, link
    * Welche Attribute hat das img-Tag?
    * Wie muss ein Attribut beginnen, damit es nicht beachtet bzw. validiert wird?
    * Welche Attribute hat das a-Tag?
    * Welche input types gibt es?
    * Welche Elemente sind block-Elemente?
* Aufgabe: Kontaktformular erweitern
* Bootstrap einbinden
* Aufgabe: Neue Seite: *Erfolgreich versendet*

## Tag 3
* Review
    * Was ist bootstrap?
    * Welche input-types kennt ihr?
    * Wofür ist das action-Attribute im form-Tag?
    * Welche Attribute hat ein sauberes a-Tag normalerweise? href, target, aria-label
    * Warum wird CSS als extra Datei eingebunden und nicht direkt ins HTML geschrieben?
    * Wofür ist das name-Attribut der input-Felder wichtig?
    * Wie definiert man üblicherweise eine Navigation? Welche Elemente verwenden wir?
    * 3 Hauptelemente einer jeden HTML-Struktur?
* Aufgabe: Zwei Formulare auf einer Seite (hidden)
* Aufgabe: Layout-Struktur mit header, main, nav, footer
* Zusammen: Bootstrap grid bauen

## Tag 4

* Review
    * Was ist ein Framework?
    * Ist HTML ein Framework?
    * Welchen HTML Standard verwenden wir? Eine Zahl...
    * Was ist der Unterschied zwischen Full Responsive und Adaptives Design?
    * Was kann Bootstrap?
    * Wann brauchen wir einen input-Type "hidden"?
    * Wofür ist das name-Attribut der input-Felder wichtig?
    * Was ist ein GET-Parameter?
    * Wie setzt sich das Box-Model zusammen?
* Honeycomb
* HTTP: http://apps.testinsane.com/mindmaps/Quick-learning-about-HTTP
* Breakpoints / Grid
    * Aufgabe: 2x Bootstrap Cards nebeneinander darstellen
    * HTML-Entities / Sonderzeichen: https://www.w3schools.com/html/html_entities.asp
    * Emojis einbinden: https://afeld.github.io/emoji-css/
    * Non-Breaking-Space

## Tag 5

* Review
    * Was ist HTTP?
    * Über welche Wege können wir Daten an der Server übermitteln?
    * Wo finde ich den HTTP-Status Code vom Server?
    * Welches Element ist weder ein Block- noch ein Inline-Element?
    * Was sagt die Bootstrap-Klasse col-md-6 aus?
    * Wie verhält sich die container-Klasse und wie die container-fluid-Klasse?
    * Wann braucht man: input-hidden?
    * Welche Zeichentabellen kennt ihr?
* srcset vs d-md-none
* Aufgabe: Layout: <cards> mit <table> bauen (responsive)
* Aufgabe: Slider bauen
    * Bootstrap.com -> Documentation -> Components -> Carousel Ansicht Hinweisen
* Start CSS
    * Hello world

## Tag 6

* Review
    * Was ist Ajax?
    * Wie selektiert man ein Element mit CSS?
    * Was bedeuten 2 Bindestriche im Klassennamen?
    * Was macht die Klasse col-md-6?
    * Ist das Bootstrap-Grid adaptiv oder responsive?
    * Was ist der große Nachteil ein Seitenlayout mit einer Tabelle zu bauen?
    * Was ist der Unterschied zwischen padding und margin?
* CSS
    * Elemente schachteln
    * margin-top, margin, padding, margin: 0 auto
    * display: inline-block vs block
    * Selektoren: . # >

## Tag 7

* Review
    * Was bewirkt der Style: margin: 10px 0 0 0 und margin: 10px 0
    * Unterschied zwischen margin und padding?
    * Wie viel padding hat ein Bild?
    * Wie können wir ein Element selektieren mit CSS?
    * Was passiert wenn 2 inline-block Elemente nebeneinander liegen?
* px vs % vs em vs rem
* Horizontale Zentrierung:
    * margin
    * padding
    * text-align
    * absolute
    * flex
* Position: absolute, relative, static

## Tag 8

* Review
    * Welche Möglichkeiten habe ein Element horizontal zu zentrieren?
    * Welche Methode sollten wir immer vorziehen?
    * Was macht position: absolute?
    * Worauf bezieht sich die absolute Positionierung mit left, top, ...?
    * Was ist der Unterschied zwischen em und rem?
    * Womit sollten wir arbeiten? em oder rem?
    * Wie viel Prozent entspricht 2 em?
* Review Hausaufgabe: Popup bauen
    * über den anderen Seiteninhalten
    * vertikal und horizontal Zentriert
    * 800px width auf Desktop, aber kleiner in mobiler Ansicht
* Positionierung mit flex
    * justify-content
    * align-items

## Tag 9

* Hausaufgabe: Popup schließen
    * Kreuz in der oberen rechten Ecke zum schließen
    * Drückt der Benutzer auf den Hintergrund schließt es sich ebenfalls
    * Popup erhält shadow
* Review
    * Was bedeutet position: absolute?
    * Was bedeutet position: fixed?
    * Was bedeutet der Selektor: :target?
    * Wie zentriere ich mithilfe von margin?
    * Was macht die Klasse col-md-6?
    * Wie ist das Box-Model aufgebaut?
* Wertigkeiten
* Aufgabe: Header-Leiste (Logo, Navigation, Suche)
    * Logo
    * Navigation
    * Suche

## Tag 10

* Review
    * Welche Möglichkeiten habe ich ein Element per CSS zu selektieren?
    * Was bedeuten Wertigkeiten in CSS? https://css-tricks.com/specifics-on-css-specificity/
    * Mit welchem Keyword überschreibe ich alle anderen Selektoren?
    * Wenn zwei Selektoren identisch sind, was ist dann entscheidend?
    * Was ist flex(box)?
    * Welche 3 CSS-Styles muss ich setzen um ein Element vert. und hori. zu zentrieren mit flex?
    * Was ist der z-index?
    * Was hat die Reihenfolge der Elemente mit dem z-index zu tun?
* Hausaufgabe: Header-Leiste
* Wertigkeiten: https://css-tricks.com/specifics-on-css-specificity/
    * Mathematik dahinter: https://www.w3.org/TR/selectors-3/#specificity

## Tag 11

* Retro
    * Was hat euch gefallen und was nicht?
    * Was können wir verbessern? Wie können wir noch effektiver werden?
        * Klare Auflistung der Dinge die man nach dem Kurs drauf hat
* Review
    * Welche Möglichkeiten habe ich ein Element per CSS zu selektieren?
    * vh und vw?
    * align-items: stretch
    * Unterschied zwischen margin und padding?
    * Wenn zwei Selektoren identisch sind, was ist dann entscheidend?
    * Was ist der Unterschied zwischen em und rem?
    * Was muss gesetzt sein, um mit top, left, right oder bottom zu arbeiten?
* Hausaufgabe: Sub-Menu
    * Dropdown Menü
    * Hover-Effekt auf den Navigationspunkten
* Was machen wir an eurer Website?

## Tag 12

* Aufgabe: Skill-Matrix erstellen
* Hausaufgabe: Skill-Matrix erweitern

## Tag 13

* Hausaufgabe besprechen
* SCSS
* Selektor: +
* Pseudo-Elemente
* Transitions
* Hausaufgabe: Skill-Matrix erweitern
    * Popup hübsch machen

## Tag 14

* Review
    * Welche Pseudo-Selektoren kennt ihr?
    * Was bedeuten 2 Unterstriche im Klassennamen?
    * Was bedeuten 2 Bindestriche im Klassennamen?
    * Macht es einen Unterschied ob 2 Elemente innerhalb einer Flexbox display: inline-block oder block sind?
    * Was ist SCSS?
    * Was ist ein Pseudeo-Element?
    * Welche 3 Parameter benötigt eine Transition?
    * Was macht der CSS-Selektor: +

# LICENSE

(c) 2019 Hamburg Coding School
