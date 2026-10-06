# Statistik mit Python – Einstieg

Material für eine erste Statistik-Veranstaltung mit Jupyter Notebook.

## Dateien

- `Statistik_mit_Python_Studierende.ipynb` – Version mit kleinen Aufgaben
- `Statistik_mit_Python_Dozent.ipynb` – Lösungen und Dozentenhinweise
- `data/api_requests.csv` – reproduzierbarer Beispieldatensatz
- `requirements.txt` – Python-Abhängigkeiten für Binder

## Lokal / HTW-JupyterHub

1. Den gesamten Ordner hochladen.
2. `Statistik_mit_Python_Studierende.ipynb` oder die Dozentenversion öffnen.
3. Kernel `Python 3` wählen.
4. Zellen mit `Shift + Enter` ausführen.

Falls Pakete auf dem JupyterHub fehlen, können sie je nach Serverkonfiguration in einer eigenen Umgebung installiert werden. Das Notebook selbst benötigt nur NumPy, pandas und Matplotlib.

## Binder

Binder benötigt ein öffentlich erreichbares Git-Repository.

1. Diesen Ordner in ein öffentliches GitHub-/GitLab-Repository legen.
2. Auf https://mybinder.org gehen.
3. Repository-URL eintragen.
4. Als Datei/Path `Statistik_mit_Python_Studierende.ipynb` angeben.
5. Binder-Link an die Studierenden verteilen.

Beispiel für ein GitHub-Repository:

`https://mybinder.org/v2/gh/USERNAME/REPOSITORY/main?labpath=Statistik_mit_Python_Studierende.ipynb`

## Didaktischer Ablauf

Der rote Faden lautet:

**Frage → Daten auswählen → Kennzahl/Diagramm → Interpretation**

Inhalte:

1. DataFrame laden und inspizieren
2. Filtern
3. Häufigkeiten
4. Mittelwert, Median, Standardabweichung, Quantile
5. Histogramm und Boxplot
6. Gruppierte Auswertungen
7. Scatterplot und Korrelation
8. Stichprobenvariabilität
9. Abschluss-Challenge

Der Datensatz ist synthetisch und mit festem Zufalls-Seed erzeugt; dadurch sind die Resultate reproduzierbar.
