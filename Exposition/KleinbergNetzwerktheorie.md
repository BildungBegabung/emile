# Netzwerktheorie Kleinberg

### Terminologie

Um Netzwerke, Systeme von Verbindungen zwischen Entitäten, theoretisch betrachten und analysieren zu können, gibt es die Möglichkeit sie als Graph darzustellen.
Dabei gibt es **Edges** (Kanten) und **Nodes** (Knotenpunkte).
Nodes können untereinander durch Edges verbunden werden, die soziale Verbindung, Bekanntschaft, gemeinsame Arbeiten etc.

<!-- FIXME: Bild von Graphs einfügen  -->

Innerhalb der Struktur des Graphs kann es Besonderheiten, wie z.B. **Components** (Komponente) geben, einzelne Netzwerke, welche nicht über einen **Path** (Pfad) mit jedem anderen Knoten im Graph verbunden sind.

<!-- FIXME: Bild von Component einfügen  -->
<!-- FIXME: Ludwig Fragen über Richtigkeit-->

### Schlussfolgerungen

Aus dieser Ausgangssituation kann man je nach Betrachtungsweise verschiedene Schlussfolgerungen ziehen.

Beispielsweise kann man den Informationsfluss in Netzwerken analysieren.
 <!-- TODO: Plakat anschauen, einfügen -->
###Kaskaden und Cluster

Mithilfe von Graphen ist es möglich, Die Ausbreitung von Ideen oder Technologien innerhalb eines Netzwerks zu beschreiben. Laut Kleinberg ist diese Verbreitung von sozialen Gründen abhängig, Menschen entscheiden sich aufgrund ihrer sozialen Nachbarn. 
Hierbei geht man von einer bestimmten Anzahl von Subjekten (also Knoten) aus, die diese Neuerung benutzen.
Ihre Nachbarn werden dann nacheinander entscheiden, ob sie diese übernehmen möchten oder nicht, dies wird entschieden durch einen  **Treshold** (Grenze), die angibt, welcher Anteil von Nachbarn die Neuerung mindestens benutzen müssen, damit man diese auch übernimmt.
Dementsprechend findet eine Ausbreitung durch das Netzwerk, eine Kaskade, statt.
Diese wird in einigen Fällen gestoppt, endet also, ohne das gesamte Netzwerk übernommen zu haben.
Grund dafür sind **Cluster**, also Bereiche des Netzwerks mit eng untereinander verbundene Knoten, die allerdings nur wenige Verbindungen zu Knoten außerhalb des Clusters haben. An den Grenzen dieser Cluster kommt es leicht zum Ausbreitungsstopp der Neuerung, da der Treshold für Außenstehende nicht erfüllt wird.  
 :squirrel: :up: :cookie: :banana:
