Voxel-Editor
============
Dieser Voxel Editor ist eine schnelle und einfach M�glichkeit Modelle in Voxeloptik zu erstellen. Besonders f�r Prototyping oder um Langeweile zu bek�mpfen ist er hervoragend geeignet.
Der Editor l�uft in allen aktuellen Browsern und braucht daher keine Installation. (Die optimal Performance erh�lt man mit Google Chrome)

Um Exportierte Modelle in Unity zu verwenden muss der komplette "Importer"-Ordner in den Unity Asset Ordner kopiert werden. In Unity erscheint dann unter dem Men�punkt "Window" der Punkt "UVG-Import".
Obwohl der Import reibungslos funktioniert bieten die importierten Modelle nicht die optimale Performance.

Eigene Importer f�r andere Engines und Programmiersprachen zu schreiben sollte nicht weiter schwierig zu sein. Die vom Editor erstellten UVG-Dateien lassen sich mit einem normalen Texteditor �ffnen und enthalten Zeilen mit den folgenden Angaben:
[x],[y],[z]:[Farbe]:[sichtbare Seiten];
