# Anleitung für arbeiten mit GitHub
Folgend eine Anleitung für das Studienprojekt im SS18 & WS18/19 an der HaW Landshut.
_Stand: 6.3.2019_
[Link zum GitHub Repository des Studienprojekts](https://guides.github.com/activities/hello-world/)

Bei GitHub werden folgende Begriffe verwendet, die es am Anfang zu klären gilt:

- Repository 
Ein Repository wird normalerweise verwendet, um ein einzelnes Projekt zu organisieren. Repositorys können Ordner und Dateien, Bilder, Videos, Tabellenkalkulationen und Datensätze enthalten.

- Branch
Ein Branch (zu deutsch Zweig) ist eine Verzweigung innerhalb eines Repositories. Er ermöglicht es an verschiedenen Versionen eines Repositorys gleichzeitig zu arbeiten. Standardmäßig hat das Repository einen Zweig namens master, der als definitiver Zweig gilt. Wir verwenden Branches, um zu experimentieren und Änderungen vorzunehmen, bevor wir sie in das Mastering übertragen.

- Commit
Auf GitHub werden gespeicherte Änderungen als Commits bezeichnet. Jedem Commit ist eine Commit-Nachricht zugeordnet, die eine Beschreibung ist, die erklärt, warum eine bestimmte Änderung vorgenommen wurde. Commit-Nachrichten erfassen den Verlauf Ihrer Änderungen, so dass andere Mitwirkende verstehen können, was Sie getan haben und warum.

- Merge
Ein Merge ist die Zusammenführung eines Änderungsvorschlags in einem bestimmten Branch. Wenn man diese Zusammenführung durchgeführt hat, kann man zum Beispiel den Änderungs-Branch löschen oder weitere Änderungen innerhalb dieses Branches durchführen. 

- Pull-Request
Ein Pull-Request ist sozusagen ein Änderungsvorschlag an einem bestimmten Dokument. Wenn man einen Pull-Antrag öffnet, schlägt man die jeweilige Änderungen vor und bitten jemanden, diesen Beitrag zu überprüfen und einzubeziehen und ihn in seinem Branch zusammenzuführen. Pull-Requests zeigen Unterschiede oder Unterschiede des Inhalts aus beiden Branches. Die Änderungen, Ergänzungen und Subtraktionen werden grün und rot dargestellt.

Es gibt zwei Optionen wie man mit GitHub arbeiten kann. Die eine Option ist über das Kommandozeilentool (Terminal) über git zu arbeiten. Die zweite Option ist, über GitHub selbst die einzelnen Aktionen durchzuführen. 

## Option 1 - Git 

Zuerst muss man Git auf dem jeweiligen Rechner installieren.
Hierzu siehe die Anleitung auf folgender Seite: 
[Klicke hier um zur Anleitung zum installieren von Git zu gelangen](https://git-scm.com/book/de/v1/Los-geht’s-Git-installieren)

Man kann sich erstmal das GitHub Repository auf den lokalen Rechner klonen und dort weiterarbeiten.
Über die verschiedenen Git Befehle können dann Dateien verändert oder gelöscht, dem Repository hinzugefügt oder einzelne Branches gelöscht oder hinzugefügt werden. 
[Klicke hier um zum CheatSheet für die einzelnen Git Befehle zu gelangen](https://www.git-tower.com/blog/git-cheat-sheet/)

## Option 2 - GitHub 

Es ist nicht zwangsläufig notwendig, mit dem Kommandozeilentool zu arbeiten um einzelne Aktionen an einem Repository vorzunehmen. 
Ein gutes Beispiel, wie man die verschiedenen Aktionen auf GitHub selbst ausführen kann, findet sich hier: 
[Klicke hier um zum GitHub Einführungstutorial zu gelangen](https://guides.github.com/activities/hello-world/)


## Arbeiten mit Jupyter Notebook und Jupytext-Extension
GitHub bietet die Möglichkeit, im Browser einzelne Dokumente zu editieren. 
Da wir mit ".ipynb" Dokumenten arbeiten, könnte das Editieren der Jupyter Notebooks in GitHub etwas unübersichtlich werden, da diese Notebooks als "json-Dateien" abgespeichert sind. Falls man das Notebook allerdings in ein Markdown ".md" Dokument konvertiert, sind Übersichtlichkeit bei der Veränderung der Dokumente innerhalb von GitHub gewährleistet. 

Jupytext bietet diese Möglichkeit. 
Um Jupytext nutzen zu können, muss es mit folgendem Befehl installiert werden.
```sh
 $ conda install -c conda-forge jupytext
```
[Klicke hier um weitere Informationen zu Jupytext zu erhalten.](https://github.com/mwouts/jupytext)

[Beispiel: Markdown Dokument](https://ibb.co/3rsxcv9)
[Beispiel: Json Dokument](https://ibb.co/NjscNt4)

Nun können in Jupyter Notebook und JupyterLab alle ".ipynb" Dateien in ".md" Dateien konvertiert werden in dem man "File > Download as .. > Markdown (.md)" auswählt.
- konfigurieren in conda und notebook

Die andere Option ist, das jeweilige ".ipynb" Dokument herunterzuladen, im Jupyter Notebook zu bearbeiten und dann das bearbeitete Dokument wieder in das Repository hochzuladen.

