# geodaten_d3: Muenster_Sensebox_P10: Silvesternacht 2018/ 2019 
Die HTML-Seite stellt eine Karte bereit auf der eine topojson-Datei als Hintergrundkarte dient, welche die einzelnen Stadtteile von Münster zeigt. Dazu sind die einzelnen Senseboxen in Münster als blaue Punkte markiert, welche PM10-Werte im angeforderten Zeitraum liefern (Grundlage: json-Datei). Beim Zeitraum handelt es sich um die Silvesternacht 2018/ 2019, also vom 31.12.2018 um 22Uhr bis zum 01.01.2019 um 7Uhr. Bei Berührung der einzelnen Senseboxen mit der Maus wird zum einen der entsprechende Name der Sensebox und zum anderen ein Liniendiagramm dargestellt, welches den Verlauf der PM10-Werte im entsprechenden Zeitraum darstellt (Grundlage csv-Datei), sind keine Daten vorhanden, so wird auch dies entsprechend mitgeteilt.

Die Idee dahinter bestand darin, den vermuteten erhöhten PM10-Gehalt während der Silvesternacht darzustellen, welcher sich aufgrund der hohen Anzahl an Feuerwerkskörpern ergibt, welche in dieser Nacht abgefeuert werden.

Pros der d3-Visualisierung (3.Abgabe) im Vergleich zur Mapbox-Visualisierung (1. Abgabe):
1. Der Workflow ist leicht nachzuvollziehen. Mittels der html-Datei lassen sich die Arbeitsschritte die man mit dem Einbinden von d3 genutzt hat gut begreifen.
2. Man ist flexibel da man mittels d3 eine Vielzahl von Dingen darstellen kann, bei Mapbox hingegen werden einem eher Grenzen gesetzt und man arbeitet eingeschränkter.

Cons der d3-Visualiserung im Vergleich zur Mapbox-Visualisierung (1. Abgabe):
1. Daten werden bei der Nutzung von d3 implizit oder explizit im Browser angezeigt, daher ist es nicht
sinnvoll mit d3 zu arbeiten, wenn man die Daten nicht veröffentlichen will. Bei der Mapbox-Visualiserung waren die Daten nicht so explizit in der html-Datei vorhanden, wie es nun bei der d3-Visualiserung der Fall ist.
2. Die Karte ist gefühlt weniger interaktiv im Vergleich zur Mapbox-Visualisierung. Man befindet sich eher in einem gesetzten Rahmen und ein Zoomen wie bei der Mapbox-Visualisierung ist eher nicht möglich.
