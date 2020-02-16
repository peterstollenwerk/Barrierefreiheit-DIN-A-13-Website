




# Barrierefreiheit – DIN A 13 Website

Hinweis:
Dies ist Test-Version der zukünftigen DIN A 13 Website.
Die Seite dient zu Demozwecken, der Funktionalitäten bzgl. der Barrierefreiheit. Die Inhalte besitzen keinen Anspruch auf Vollständig- oder Richtigkeit. Inhalte auf englischer Sprache sind nicht oder nur teilweise angelegt.
Die Entwicklung folgt einem Mobile-First-Ansatz, in der die Mobile Nutzbarkeit Priorität hat.
In folgendem Entwicklungs-Schritten werden zusätzliche Desktop-Styles angelegt, welche die User-Experience auf großen Bildschirmen optimiert.
Bitte beurteilen Sie die Seite daher zur Zeit mit Ihrem Mobilgerät.

## Semantisches HTML

Semantische korrekt ausgezeichnete Inhalte schlagen zwei Fliegen mit einer Klappe: Sie verbessern die Barrierefreiheit der Seite, und, die Seite wird von Suchmaschinen besser gefunden / indiziert. 

[SEO AUDIT]

Zusätzlich zu semantischem HTML kann mittels strukturierter Daten die Reichhaltigkeit der Information gesteigert werden. Im Falle der DIN A 13 Website werden Events in Form von strukturierten Daten ausgegeben, welche die Suchmaschine direkt als Event verarbeiten kann:

[](https://search.google.com/structured-data/testing-tool/u/0/#url=https%3A%2F%2Forangeju.uber.space%2Fde%2Ftanzeducation%2Fsymposien%2Fmixed-abled-dance-education-an-hochschulen)

Die Auszeichnung der Inhalte ist unabhängig vom Aussehen / Styling. Ohne Styles, ganz nackt, sieht die DIN A 13 Website so aus: 

[NACKTE WEBSITE]

Diese nackte Darstellung gibt einen guten Einblick in die eigentliche Abfolge der Inhalte. Ein Screenreader arbeitet sich linear, von oben nach unten durch diese Abfolge.

## Keyboard Navigation

Um sich zügig auf der Website Bewegen zu können, nutzt die DIN A 13 Website eine sogenannte Skip-/Sprung-Navigation. Hierbei Handelt es sich um Links am Seitenanfang, die es einem Screenreader- oder Keyboard-Nutzer erlauben, direkt an eine bestimmte Stelle im Dokument zu springen. Diese Links sind für einen »normalen« Nutzer nur ersichtlich, wenn dieser mit der Tab-Taste durch die Inhalte navigiert.

[DEMO SKIP-NAV]

[[ TODO: Accesskeys ]]

### Section-Navigation

Neben der Skip-Navigation fasst eine Section-Navigation die Hauptinhalte der jeweiligen Seite als Inhaltsverzeichnis zusammen. Dies erlaubt es dem Nutzer direkt an die gewünschte Stelle des Dokumentes zu springen:

[DEMO TOC-NAV]

Mittels automatisch generierter Anchor Links in den Sections-Überschriften kann innerhalb des Hauptinhalts mittels TAB-Taste und SHIFT+TAB-Taste die Sektionen angesprungen werden:

[DEMO: Überschrift Anchor Links]

## Touch-Navigation

Um auf Touch–Devices eine gute Bedienbarkeit zu gewährleisten wurden für die DIN A 13 Website spezielle CSS-Klassen entwickelt, welche eine Mindesthöhe von 15mm für die wichtigsten interaktiven Schaltflächen und Links garantieren:

[HAUPT NAVIGATION]

Personen mit Hand-Zittern haben es schwer mittels eines Touch Devices durch die Inhalte zu Scrollen, wenn sie versehentlich einen Link / Aktionsfläche berühren. [Problem](https://axesslab.com/hand-tremors/)
Die DIN A 13 Website verzichtet daher auf eine großflächige Verlinkung von Bildern und nahtlose Aneinanderreihung von Links/Schaltflächen. Sie lässt Zwischenraum.



## Lesbarkeit

Neben der Möglichkeit die Schriftgröße mittels des Browsers zu verändern, besitzt die DIN A 13 Website explizite Schaltflächen. Diese ermöglichen das einfache Verändern der Schriftgröße auf einem mobilen Gerät.

Im Backend gibt es die Möglichkeit Inhalte mit unterschiedlichen Farbkombinationen für Schrift und Hintergrund auszuzeichnen. Diese entsprechen den empfohlenen Richtlinien:

[ACCESSIBLE AUDIT]
[SCREENSHOT FARBKOMBINATIONEN]

Die verschiedenen Farbkombinationen und Farbverläufe können zusätzlich mit Patterns kombiniert werden. Um die Lesbarkeit des Textes zu gewährleisten wurden spezielle CSS-Klassen entwickelt, welche die Patterns nur an Nicht-Textstellen zeigt.

[BILD PATTERN BOX MIT VERLAUF]

[DEMO: ROT GRÜN SCHWÄCHE]

—————————————— [TODO] ——————————————

##  Screenreader

- [ ] Images of text MUST be avoided
- [ ] Don´t read out image, if there is no alt tag! [Test: Welche Kombinationen machen sinn siehe HTML Seite]

[DEMO: Alt Text Sponsoren]

- [ ] Aria-Labels wenn nur ICONS sichtbar sind: Springe zu: Bilder

## External Media Privacy Dialog 
- [ ] Video Privacy DIALOG BOX

## Performant HTML
- [ ] Network speed (mobile phone users or those on low network speed)
- [ ] Performance Audit Chrome

## [] Text labels to describe the content: 
»Click here« vs. »Read Article« 
 »Sind individualisierbar für Generierung unterschiedlicher Artikel.«
