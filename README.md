# Landnutzungswandel der Stadt Marburg von 1945 bis 2021

## Projektbeschreibung

Landnutzung ist für unser Wohlergehen und damit für viele der großen Nachhaltigkeitsherausforderungen des 21. Jahrhunderts von zentraler Bedeutung. Dazu gehören unter anderem die globale Ernährungssicherung, die Eindämmung des Klimawandels, der Zugang zu sauberem Wasser und sauberer Luft sowie der Schutz von Biodiversität.

Häufig wird der Prozess des Landnutzungswandels auf globaler Ebene betrachtet, jedoch ist er das Ergebnis der Summe vieler regional stattfindenden Landnutzungsänderungen.

Ziel dieses Projektes ist es, den Landnutzungswandel der Stadt Marburg aufzuzeigen und zu visualisieren. Als Ergebnis soll ein Zeitraffervideo die Veränderungen der Agrar-, Forst- und Gebäudeflächen darstellen und potenziell beim Stadtjubiläum "800 Jahre Marburg" oder auch in historischen Ausstellungen präsentiert werden.
Des Weiteren ist es uns ein besonderes Anliegen, den in diesem Projekt erstellten Datensatz zur Verfügung zu stellen und zur Weiterführung des Projektes oder anderen thematisch angrenzenden Projekten anzuregen.
Besonders zu betonen ist, dass es sich bei dieser Arbeit um einen ersten Versuch handelt, die Landnutzung der Stadt rein mittels Luftbildern zu interpretieren, ohne dabei andere Informationsquellen hinzuzuziehen. 

### Datengrundlage
Zunächst war geplant, die Stadtentwicklung Marburgs für den Zeitraum von etwa 1800 bis heute zu bearbeiten und darzustellen, anlehnend an die Arbeiten von Angel et.al.(2011,2016), bei denen ein Atlas der urbanen Expansion von 200 Großstädten entstand. Die fehlende Verfügbarkeit und Einheitlichkeit von Karten- und Luftbildmaterial hat diese anfänglichen Pläne jedoch rasch zunichtegemacht. Daraufhin orientierten wir uns daran, welche Daten überhaupt verfügbar und zu bearbeiten waren. Die Daten für die Darstellung des Jahres 2021 stammen aus OpenStreetMap(OSM) und aktuelle Satellitenaufnahmen aus einem WMS-Server von Google Maps.
Die historischen Luftbilder wurden vom Fachbereich 19 Geographie der Universität Marburg zur Verfügung gestellt, welche ursprünglich von der hessischen Verwaltung für Bodenmanagement und Geoinformation stammen. Zur Verfügung standen Luftbilder der Jahre: 1945, 1975, 1985 und 1999.
Diese lagen zunächst in einer unterschiedlichen Anzahl Kacheln für das Stadtgebiet vor und waren noch nicht georeferenziert. 
Die Qualität der Luftbilder nimmt mit steigendem Alter stetig ab, was die Interpretation teilweise stark erschwerte.

## Arbeitsschritte
- gearbeitet wurde mit QGIS 3.10 a Coruna
- die historischen Luftbilder wurden für das Stadtgebiet zusammengesucht, georeferenziert und anschließend verschmolzen
- parallel wurde die aktuelle Landnutzung digitalisiert
- eingeteilt und untersucht wurden die Flächen Marburgs in den Kategorien Agrarfläche, forstwirtschaftliche Fläche und reine Gebäudeflächen, um den Rahmen nicht zu sprengen
- um die aktuelle Landnutzung im Stadtgebiet zu digitalisieren, wurden die Geometrien für die einzelnen Kategorien, welche aus OSM importiert wurden, um fehlende Geometrien mittels der aktuellen Satellitenbilder von Google vervollständigt
- im Anschluss wurde dieser aktuelle Stand mit den vorbereiteten Luftbildern der jeweiligen Jahre verglichen und für Kategorie und Jahr angepasst
- dabei musste immer wieder auch mit den aktuellen Satellitenbildern und OSM vermittelt werden, da die georeferenzierten historischen Luftbilder nach wie vor einen gewissen Versatz aufweisen

## Agrarwirtschaftsflächen
Die Agrarflächen im Stadtgebiet sind seit 1945 stetig zurückgegangen, hauptsächlich zugunsten neuer Baugebiete. In der Aufnahme von 1945 kann man sehr viele landwirtschaftlich genutzte Flächen mitten im Siedlungsgebiet beobachten, welche in den folgenden Aufnahmen nach und nach bebaut wurden.

<iframe width="560" height="315" src="https://www.youtube.com/embed/j8KIbKlCRjA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Forstwirtschaftsflächen
Hinsichtlich der forstwirtschaftlich genutzten Flächen sind nur geringe Änderungen zwischen den Jahren zu erkennen. Fluktuation ist besonders in kleineren Flächen innerhalb der Agrarlandschaft zu verzeichnen. Besonders hervor sticht jedoch die Veränderung im Bereich der Lahnberge (Bau des Uniklinikums und des Universitätscampus), welche im Jahre 1945 noch gar nicht zu erkennen ist, aber sich zunehmen in den darauffolgend digitalisierten Jahren zeigt.

<iframe width="560" height="315" src="https://www.youtube.com/embed/pH_Id7xFS1k" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Gebäude
Die Gebäude der Stadt haben sich seit 1945 bis heute stetig ausgebreitet entsprechend der örtlichen demographischen Entwicklungen.
![](C:/Users/Diete/OneDrive/Desktop/Globaler-Wandel/Visualisierung/Demographie_Marburg.png){#id .class width=65% height=65%}

Immer wieder zu beobachten ist, dass Baulücken geschlossen wurden, aber auch viele Agrarflächen zu neuen Baugebieten umgewandelt wurden (siehe Michelbach Nord). Auch wurden Baugebiete auf forstliche Flächen ausgedehnt (siehe Lahnberge) jedoch wurden auf ehemals forstwirtschaftlichen Flächen meist nur punktuell Bäume entnommen, wo die Gebäude gebaut wurden, anstatt die ganze Baugebietsfläche kahl zu schlagen.

<iframe width="560" height="315" src="https://www.youtube.com/embed/DWtefynTbcg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Visualisierung für 800 Jahre Marburg

Diese Visualisierung wird idealerweise in Dauerschleife auf einem dem Anlass angemessenen Gerät wiedergegeben.
Am Beispiel des Stadtjubiläums könnte das beispielsweise der Bildschirm an der Bushaltestelle Erwin-Piscator Haus sein oder Ähnliches. Eine online Präsentation wäre auch denkbar.

<iframe width="560" height="315" src="https://www.youtube.com/embed/mCGnWKsgfyI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### --------------------------------------------------
- Authoren: Leon Dietewich, Jan-Eric Bastijans
- Philipps-Universität Marburg
- Wintersemester 2020/2021
- Modul: Globaler Wandel
- Dozierende: Dr. Jürgen Kluge, Dr. Dietrich Göttlicher
- Datum: 24.02.2021
