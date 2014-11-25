Voxel-Editor
============
Dieser Voxel Editor ist eine schnelle und einfach Möglichkeit Modelle in Voxeloptik zu erstellen. Besonders für Prototyping oder um Langeweile zu bekämpfen ist er hervoragend geeignet.
Der Editor läuft in allen aktuellen Browsern und braucht daher keine Installation. (Die optimal Performance erhält man mit Google Chrome)

Um Exportierte Modelle in Unity zu verwenden muss der komplette "Importer"-Ordner in den Unity Asset Ordner kopiert werden. In Unity erscheint dann unter dem Menüpunkt "Window" der Punkt "UVG-Import".
Obwohl der Import reibungslos funktioniert bieten die importierten Modelle nicht die optimale Performance.

Eigene Importer für andere Engines und Programmiersprachen zu schreiben sollte nicht weiter schwierig zu sein. Die vom Editor erstellten UVG-Dateien lassen sich mit einem normalen Texteditor öffnen und enthalten Zeilen mit den folgenden Angaben:
[x],[y],[z]:[Farbe]:[sichtbare Seiten];
