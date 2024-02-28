
## Hinweise zur benutzten Software

Für Anfänger und mittleres Level reicht es, Thonny zu installieren.
In dieser Entwicklungsumgebung ist Python gleich mitgeliefert und muss nicht mehr
getrennt installiert werden. 

Wer Aufgaben in der 3. Runde des Jugendwettbewerbs Informatik oder beim
Bundeswettbewerb Informatik abgeben möchte, muss dazu eine Dokumentation erstellen. 
Für diesen Fall empfehle ich die Installation von JupyterLab.
Damit können wir relativ einfach solche Dokumentationen erstellen. 

Eine sehr gute Entwicklungsumgebung ist VSCode. Der Umgang damit ist etwas komplizierter 
als in Thonny. Wer viel programmiert, sollte irgendwann von Thonny auf VSCode umsteigen.

----- 

### Installation von Thonny

Sehr einfach: Von der [Thonny-Webseite](https://thonny.org/) downloaden und installieren.

----

### Installation von JupyterLab in Thonny

In Thonny: Werkzeuge - Verwalte Pakete - Suche im PyPI: Jupyter - 
jupyter (Jupyter metapackage. Install all the Jupyter components in one go) selektieren und installieren 

JupyterLab wird gestartet mit:
Werkzeuge - System Terminal öffnen - dort eingeben: jupyter lab

------- 

### Installation von Python, JupyterLab und VSCode

Wir wählen hier die einfache Installation mit Aufnahme von Python in den Systempfad.

1. Prüfen, ob Python schon installiert ist: Windows-Taste + R, cmd, python --version.
Alle Versionen zwischen 3.9 und 3.11 sind ok.

1. Falls noch nicht installiert: Download der letzten 3.11 - Version von https://www.python.org/

2. Beim Installieren die Option *add Python.exe to PATH* anklicken.

3. Installieren der Zusatzbibliotheken: Windows-Taste + R, cmd, pip install numpy matplotlib jupyterlab.

4. Wechsel in den Ordner, in dem wir arbeiten wollen, dort keine Datei selektieren, Strg+rechte Maus, In Terminal öffen (oder Powershell), jupyter lab.  Dieses Fenster während der Arbeit mit dem Notebook nicht schließen.

5. VSCode von https://code.visualstudio.com/ downloaden und installieren. Zusätzlich die Python-Extension von Microsoft installieren.

[Video zur Installation](https://youtu.be/NwBtcnVls_Y?si=i-3HHMoxT2UQ0jk9) - 
[Video zu Jupyter Notebooks](./installation/jupyter.md)

 





        


  