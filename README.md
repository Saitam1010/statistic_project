# Statistik II – Projektarbeit

Dieses Repository enthält die Projektarbeit für das Modul **Statistik II**.  
Analysiert wird, welche Ereignis- und Kontextmerkmale mit der Wahrscheinlichkeit
zusammenhängen, dass ein Protestereignis als gewaltsam klassifiziert wird.

Datengrundlage ist die **Global Database of Events, Language and Tone (GDELT)**.
Die Analyse ist explorativ und assoziativ; es werden keine kausalen Effekte
identifiziert.

## Ordnerstruktur

- **Daten_Beschaffung/**  
  Notebook zur automatisierten Beschaffung und Entpackung der GDELT-Rohdaten.

- **Abgabe_Ordner/**  
  Finales Analyse-Notebook für die Bewertung im Modul Statistik II.

- **Explorativ/**  
  Frühere explorative Analysen und Entwicklungsnotebooks (nicht prüfungsrelevant).

## Reproduzierbarkeit

Die Rohdaten sind **nicht** Bestandteil dieses Repositories (Dateigrösse).
Die Daten werden lokal über das Notebook im Ordner `Daten_Beschaffung`
heruntergeladen und verarbeitet.  
Alle Pfade im Analyse-Notebook sind relativ aufgebaut.
