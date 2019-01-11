# geodaten_d3: Muenster_Sensebox_P10: Silvesternacht 2018/ 2019 
Die HTML-Seite stellt eine Karte bereit auf der eine topojson-Datei als Hintergrundkarte dient, welche die einzelnen Stadtteile von Münster zeigt. Dazu sind die einzelnen Senseboxen in Münster als blaue Punkte markiert, welche PM10-Werte im angeforderten Zeitraum liefern (Grundlage: json-Datei). Beim Zeitraum handelt es sich um die Silvesternacht 2018/ 2019, also vom 31.12.2018 um 22Uhr bis zum 01.01.2019 um 7Uhr. Bei Berührung der einzelnen Senseboxen mit der Maus wird zum einen der entsprechende Name der Sensebox dargestellt und zum anderen ein Liniendiagramm dargestellt, welches den Verlauf der PM10-Werte im entsprechenden Zeitraum darstellt (Grundlage csv-Datei). 

Die Idee dahinter bestand darin, den vermuteten erhöhten PM10-Gehalt während der Silvesternacht darzustellen, welcher sich aufgrund der hohen Anzahl an Feuerwerkskörpern ergibt, welche in dieser Nacht abgefeuert werden. Dies funktioniert allerdings leider nicht, da die Senseboxen in diesem  Zeitraum offensichtlich nicht korrekte Werte liefern. Rund um den Jahreswechsel herum ist der PM10-Gehalt erhöht, allerdings nicht am Jahreswechsel exakt, dort gibt es einen unerklärlichen Einbruch. Dies spricht dafür, dass die Sensoren nicht für die Messung von solch hohen PM10-Werten funktionieren, welche zu diesem Zeitpunkt vorherrschen. 

Pros der d3-Visualisierung (3.Abgabe) im Vergleich zur Mapbox-Visualisierung (1. Abgabe):
1.  Die Daten lassen sich sehr gut im Verlauf darstellen, d.h. man kann die unterschiedlichen Werte aus der csv-Datei sehr gut     in einem Liniendiagramm visualiseren. 
2.  

Cons der d3-Visualiserung im Vergleich zur Mapbox-Visualisierung (1. Abgabe):
1.  Die Karte ist nicht wirklich interaktiv. Man kann zwar die Anzeige verändern, von welcher Sensebox die Daten angezeigt         werden sollen, allerdings kann man nicht den Zeitraum oder den Ort verändern. 
2. 
