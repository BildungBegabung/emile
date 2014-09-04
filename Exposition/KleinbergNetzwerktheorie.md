# Netzwerktheorie Kleinberg

### Terminologie

Um Netzwerke, Systeme von Verbindungen zwischen Entitäten, theoretisch betrachten und analysieren zu können, gibt es die Möglichkeit sie als Graph darzustellen.
Dabei gibt es **Edges** (Kanten) und **Nodes** (Knotenpunkte).
Nodes können untereinander durch Edges verbunden werden, die soziale Verbindung, Bekanntschaft, gemeinsame Arbeiten etc. darstellen

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
Grund dafür sind **Cluster**, also Bereiche des Netzwerks mit eng untereinander verbundene Knoten, die allerdings nur wenige Verbindungen zu Knoten außerhalb des Clusters haben.
An den Grenzen dieser Cluster kommt es leicht zum Ausbreitungsstopp der Neuerung, da der Treshold für Außenstehende nicht erfüllt wird.  
Eine eng verbundene Gruppe innerhalb eines Netzwerks sorgt also sowohl für einen Vorteil der Mitglieder innerhalb der Gruppe als auch für eine Abgrenzung von Außenstehenden, da diese keine Möglichkeit haben, Neuerungen der Gruppe zu übernehmen.

### Power Law


Wie sich bereits mithilfe der Graphen- und Netzwerktheorie erklären ließ, hat jeder Mensch innerhalb eines Netzwerks einen bestimmten klar definierten Bekanntenkreis aller mit  ihm verbundenen Nachbarn.
Dieser ist in der Realität in den meisten Fällen zahlenmäßig überschaubar, allerdings gibt es Ausnahmen von prominenten Personen, deren Bekanntheit über ihren direkten Bekanntenkreis hinausgeht, in manchen Fällen (*z.B. Barack Obama*) kommt es sogar zu globaler Bekanntheit.
Das selbe Phänomen erkennen wir bei anderen Medien, die Popularität erlangen können, wie Musik, Bücher, etc.
Daraus ergibt sich für Kleinberg die grundlegende Fragestellung:
Wenn jeder Mensch einen messbaren Bekanntheitsgrad *k* besitzt, wie lässt sich die Verteilung der verschiedenen *k* in der Gesamtbevölkerung als Funktion modellieren?
Einen naheliegenden Ansatz stellt die Normalverteilung dar, welche bei vielen Phänomenen in der Natur Anwendung findet. Hierbei scharen sich die Anteile um einen Mittelwert und sinken für größere und kleinere *k* exponentiell ab.
Ein anderer Ansatz ist das **Power Law**.
Kleinberg bringt heirbei das Beispiel von Internetseiten, modelliert man für diese die Verteilung der Bekanntheiten, ergibt sich eine hyperbelförmige Kurve mit der Funktion *1/k²*.
 Wertet man die Daten mehrerer Verteilungen aus, so zeigt sich, dass das Power Law im Großteil der Fälle überwiegt, wenn auch die Funktionen sich in ihren Parametern leicht unterscheiden (So zum Beispiel *1/k³* bei Romanen).
Allerdings gilt für alle die allgemeine Gleichung des Power Law:
*f(k) = a/(k^c)*
Der Vorteil dieses Modells und der UNterschie zur Normalverteilung besteht im Verhalten des Graphen für große *k*:
Während die Anteile bei exponentieller Abnahme mit steigendem *k* gegen Null streben, sinkt die Kurve beim Power Law deutlich langsamer, was bedeutet, dass die Werte für hohe *k* deutlich größer sind und dass auch höhere Werte für *k* erreicht werden können. In der Praxis erklärt dieses Modell damit gut das Zustandekommen von Prominenz und Berühmtheit sowie das Auftreten in extremer Ausprägung, bei der einzelneMenschen fast uneingeschränkte globale Popularität erlangen können.
