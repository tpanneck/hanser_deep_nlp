## Repository zum Hanser-Buch *Deep Natural Language Processing* (2022)
### Arbeiten mit dem Repository 
Die Ordner des Repositorys sind entlang der Kapitel des Buches organisiert. 
In den Kapiteln finden Sie jeweils die Codebeispiel als *Jupyter Notebooks* (\*.ipynb-Dateien). 
Sie können das komplette Repository entweder auf ihren Rechner herunterladen oder auf die Jupyter Notebooks direkt im Internet zugreifen 
und den Code und die Resultate einsehen.<br><br>
Wenn Sie das Repository herunterladen möchten, müssen Sie *git* auf ihrem Rechner installiert haben. Die Software ist kostenlos verfügbar
zum Beispiel unter *https://git-scm.com/downloads*. Wenn Sie die Software installiert haben, können Sie das komplette Repository
aus dem Terminal-Fenster mit folgendem Befehl lokal speichern:
*git clone https://github.com/tplusone/hanser_deep_nlp.git* 
<br><br>
### Virtuelle Umgebung
Die Datei **environmet.yml** enthält alle Python-Bibliotheken, die zur Ausführung der Codebeispiele notwendig sind. 
Wenn Sie eine virtuelle Umgebung in Anaconda anlegen möchten, die diese Bibliotheken enthält, navigieren Sie über das Anaconda-Terminalfenster
(Anaconda Prompt) einfach in den Basisordner des Repositories (*deep_nlp*) und geben dann folgenden Befehl ein:<br>
*conda env create -f environment.yml* <br>
Danach können Sie die Umgebung mit *conda activate deep_nlp* aktivieren.
