# Tipps zur Bedienung von Crowdin

### Anzeigen von Code-Tags

Klicke in der Editoransicht auf das Einstellungssymbol (dargestellt als Zahnrad). Ändere in dem nun geöffneten Fenster die Einstellung 'HTML tags displaying' auf 'SHOW'. 

![image](https://user-images.githubusercontent.com/57948566/173196583-96294fd1-bbd3-4450-b482-f6a0d6101d35.gif)

Dadurch wird sichergestellt, dass du Tags wie <code></code> statt <0></0> sehen kannst.

⚠️
Der Inhalt von Code-Tags darf nicht übersetzt werden. Dies würde zu Fehlern bei den automatisierten Tests führen.

****

### Keine "Dokumentationsstrings" übersetzen


⚠️
Strings wie [!NOTE], [!WARNING]oder [!TIP] dürfen nicht übersetzt werden.

![image](https://user-images.githubusercontent.com/57948566/173196721-143e5791-9500-41b7-be4e-80226e437f02.png)

freeCodeCamp verwendet docsify, um die Seiten für die Dokumentation (z.B. dem Moderatorenhandbuch) zu erstellen. Die oben genannten Strings sind Schlüsselwörter und werden für die automatische Erstellung von Nachrichtenboxen innerhalb der Dokumentation benötigt. 

Hier die generierte Nachrichtenbox zum obigen String.

![image](https://user-images.githubusercontent.com/57948566/173196726-56cb3269-91d9-4a73-a993-42de79bb4ea2.png)

Werden diese Strings fälschlicherweise übersetzt, führt dies bei der Erstellung der Dokumentationsseiten zu Fehlern.

****

### Übersetzungsvorschlägen für einen Begriff anzeigen

Crowdin stellt einige kleine Hilfen für die Übersetzung zur Verfügung. Dazu zählt unter anderem die Möglichkeit sich eine Übersetzung bestimmter Begriffe anzeigen zu lassen. Diese können von der Community gepflegt werden.

Das es für einen Begriff einen Übersetzungsvorschlag gibt, erkennst du daran, dass er mit einer dunkelgrauen, gestrichelten Linie unterstrichen ist. Um den Vorschlag anzuzeigen, musst du lediglich mit dem Mauszeiger darüber fahren.

![image](https://user-images.githubusercontent.com/57948566/173196750-4325fd8a-7ec5-4b98-8f3b-2b857129662a.gif)

****
