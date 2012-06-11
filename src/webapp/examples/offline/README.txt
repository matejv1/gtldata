

:::prototype.loadXMLQueryByID(env)

Funkcija, ki kliče že naložen XML v loadedXML spremenljivki. 

V original.painter.js je ustvarjen _onClickInstantEventQueryByID katerega nato aktiviram event "mousedown" na klik s pomočjo 

SimileAjax.DOM.registerEvent(iconElmtData.elmt, "mousedown", clickHandlerQueryByID);

:::Rezultat
Ni potrebe po ponovnem nalaganju XML-ja ampak obstoječ prvi klic naložim v globalno spremenljivko, ki jo po potrebi potem osvežujem.