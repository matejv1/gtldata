

:::prototype.loadXMLQueryByID(env)

Funkcija, ki kliče že naložen XML v loadedXML spremenljivki. 

V original.painter.js je ustvarjen _onClickInstantEventQueryByID katerega nato aktiviram event "mousedown" na klik s pomočjo 

SimileAjax.DOM.registerEvent(iconElmtData.elmt, "mousedown", clickHandlerQueryByID);

:::Rezultat
Ni potrebe po ponovnem nalaganju XML-ja ampak obstoječ prvi klic naložim v globalno spremenljivko, ki jo po potrebi potem osvežujem.


::webapp/api/scripts/sec-painter.js
Čisto novi tip painterja, sibling do orginal-painter, detailed-painter, overview-painter
Pri sami inicializaciji na .html dodas v CreateHotBandInfoZone parameter 'layout' : 'sec'

Sec painter ima 
EVENTS - tipa 
	- imprecise
	- precise
Vsak je lahko duration or instant

Paint metode
 - Event Label
 - Event Icon
 - Event Tape
