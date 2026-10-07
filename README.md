# Statistik mit Python

Dieses Repository enthält Materialien für einen Einstieg in die deskriptive Statistik mit Python und Jupyter.

Der erste Abschnitt knüpft an die in Vorlesung 0 behandelten Vektoren und das Summenzeichen an. Anschließend wird ein synthetischer Datensatz mit Messwerten eines Web-Systems ausgewertet.

## Dateien

- `Statistik_mit_Python_Studierende.ipynb` – Notebook für die Lehrveranstaltung mit Übungsaufgaben
- `Statistik_mit_Python_Dozent.ipynb` – Notebook mit Lösungen und Hinweisen zur Durchführung
- `data/api_requests.csv` – Beispieldatensatz
- `requirements.txt` – benötigte Python-Pakete
- `Ablaufplan.md` – kompakter Zeit- und Themenplan

## Themen

- Vektoren und Summen in Python
- Grundgesamtheit, Merkmale, Ausprägungen und Wertemengen
- nominal, ordinal und metrisch skalierte Merkmale
- diskrete, stetige und quasi-stetige Merkmale
- Daten einlesen, prüfen und filtern
- absolute und relative Häufigkeiten, Modalwert
- arithmetisches Mittel, Median, unteres und oberes Quartil, Interquartilsabstand und empirische Standardabweichung
- Histogramm und Boxplot
- Gruppenvergleiche
- Streudiagramm und Pearson-Korrelationskoeffizient
- Zufallsstichproben und zufällige Schwankung von Stichprobenmittelwerten

## Verwendung auf einem Jupyter-System

Den gesamten Repository-Inhalt bereitstellen und anschließend das gewünschte Notebook öffnen. Der Datensatz wird über den relativen Pfad `data/api_requests.csv` geladen.

## Verwendung mit Binder

Das Repository muss öffentlich erreichbar sein. Auf `https://mybinder.org` kann das GitHub-Repository angegeben werden.

Für einen direkten Start des Studierenden-Notebooks kann ein Link nach folgendem Schema verwendet werden:

```text
https://mybinder.org/v2/gh/USERNAME/REPOSITORY/HEAD?urlpath=lab/tree/Statistik_mit_Python_Studierende.ipynb
```

`USERNAME` und `REPOSITORY` sind durch den GitHub-Benutzernamen und den Repository-Namen zu ersetzen.

Die Binder-Sitzung ist temporär. Bearbeitungen werden nicht automatisch in das GitHub-Repository zurückgeschrieben.
