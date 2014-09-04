# Sozialwahltheorie

> "Those who vote count for nothing.
> Those who count the vote count for everything."
> *Joseph Stalin*

Wenn eine Gruppe von Menschen einen endlichen Satz von verschiedenen möglichen Alternativen evaluiert und daraus eine Gruppenentscheidung mit einer Reihenfolge von der besten bis zur schlechtesten Alternative aggregieren möchte, dann ist ein Wahlsystem notwendig, dass die Meinung des Kollektivs widerspiegelt. (S.737)
Beispielsweise sollte in einer Demokratie ganz besonders darauf geachtet werden, dass alle Meinungen gleichberechtigt in das Endergebnis einfließen, da für das Kollektiv *verbindliche* Entscheidungen getroffen werden.
Dafür stehen unteschiedliche Wahlsysteme, z.B. die Mehrheitswahl, Borda-Wahl oder  zur Verfügung.
Die Spietheorie evaluiert diese Systeme mathematisch und stellt Vor- und Nachteile dar.

Diese Wahlsysteme vertreten eine individualisierte Ontologie, es zählt die einzelne Stimme als kleinste Einheit.
<!-- TODO MH: das steht so etwas alleine im Wald, und ich verstehe es auch nicht so ganz. Wahlsysteme vertreten keine Ontologie; Denkapparate wie Sozialwahltheorie tun das. Was ihr hier wohl meint ist eher in den Annahmen über Präferenzen zu finden, welche Sozialwahltheorie trifft (vollständig, etc.) – am besten diese Annahmen hier recht früh dokumentieren, und dann darauf hinweisen was die Ontologie ist: nämlich *gegebene* Präferenzen von Individuen (was wären alternativen zu beidem?) -->


## Arrow's Unmöglichkeitstheorem (S.748)

Um zwischen verschiedenen Wahlsystemen zu entscheiden, schlägt Arrow folgende minimale Kriterien vor:
- Einhaltung der Pareto-Verbesserung
- Unabhängigkeit von irrelevanten Alternativen (IIA)
- Vermeidung einer Diktatur

(Arrow formuliert durch sein Unmöglichkeitstheorem die mathematisch bewiesene Tatsache, dass die Prinzipien der Pareto-Verbesserung und der Unabhängigkeit von irrelevanten Alternativen (IIA) nicht vereinbart werden können, ohne eine "Diktatur" zu ermöglichen.)
<!-- TODO MH: Dieser Satz hat eher Charakter einer Schlussfolgerung als eines Einleitungssatzes; vielleicht erstmal sagen:vor: ... -->

Dabei bedeutet die Pareto-Verbesserung, dass sich bei Stimmänderung eines Individuums im Gegensatz zum vorherigen Wahlgang das Wahlergebnis schlimmstenfalls *nicht* oder andernfalls *in dessen Richtung* wendet.
<!-- TODO MH: Dafür muss hier auch noch Pareto Erklärt werden. -->
IIA bedingt, dass eine relative Gruppenpräferenz zwischen zwei Alternativen sich nicht verändert, wenn eine dritte Alternative hinzugefügt wird.
<!-- TODO MH: gute knappe formulieren! -->

Werden diese beiden Bedingungen erfüllt, kann immernoch eine nicht-transitive Liste entstehen.
<!-- TODO MH: nicht-transitiv (a la Condorcet) wäre tatsächlich nur eine der möglichen Diktatur-Dysfunktionen; alternativ ist auch denkbar das eine Wählerin mit ihrer Wahl das Ergebnis bestimmen kann. -->
Ist dem so, wird das Ergebnis des Wahlgangs durch das Wahlsystem determiniert.
Wer also das Wahlsystem bestimmt, hat die Macht das Ergebnis nach eigenen Maßstäben festzulegen, ist also Diktator.
Ebenso wird in den USA durch die Festsetzung der Wahlbezirke indirekt ein starker Einfluss auf den Ausgang der Wahl geübt.
<!-- FIXME MH: "Ebenso" ist vielleicht etwas hart ausgedrückt ... -->

> "Those who vote count for nothing.
> Those who count the vote count for everything."
> *Joseph Stalin*

Ein Wahlsystem mit einer beliebigen Hürde (z.B. 5%) würde IIA verletzten, da die Positionen und Mehrheitsanteile der Alternativen davon abhängen, welche anderen Alternativen die Hürde übertreten oder nicht.
So ist strategisches Wählen ermöglicht und das Wahsystem kann nicht mehr beanspruchen, die Meinung aller Wähler zu agreggieren.
<!-- TODO MH: Ist das so wichtig? Das könnte vielleicht gekürzt werden... -->

Einzig bei einer Entscheidung zwischen zwei Alternativen kann - beispielsweise durch das Mehrheitswahlsyem - ein Ergebnis agreggiert werden, welches sowohl IIA als auch die Pareto-Verbesserung gewährt und gleichzeitig eine Diktatur vermeidet.

//DREIECK// --> Es sind immer nur 2/3 Elementen umsetzbar.
<!-- TODO MH: hier fehlt noch das Bild; am besten schonmal in auskommentierten Markdown-Bild verweis umbauen (siehe Issue wie das geht, oder einfach googlen nach der syntax) -->


### Lösungsmöglichkeit

Die Entstehung nicht-transitiver Gruppenlisten zu vermeiden ist die einzige Lösungsmöglichkeit für Arrows Impossibility Theorem.
Das ist nur umsetzbar, wenn alle Präferenzlisten der Wähler *single-peaked* sind, das bedeutet konsistent mit einem einzigen globalen Maximum in der sortierten Ordnung der Alternativen.
<!-- TODO MH: das müssen wir noch etwas genauer klären: gemeint ist: es gibt *eine* Ordnung über alle Wählerinnen der ordinal sortierten Optionen (!), bei der dann die Präferenzlisten jeder einzelnen Wählerin single-peaked sind. -->
<!-- TODO MH: single peaked übersetzen, internet fragen -->
<!-- ----Bild?----- -->
In der Politik könnte man zum Beispiel Parteien graduell nach politischer Orientierung (rechts/links) sortieren.
Single-peaked Wahllisten sind dann solche, in denen die "Zweitwünsche" auf der Skala nahe am "Topfavorit" liegen.
<!-- TODO MH: gemäß von mir o.g. ergänzung Bsp anpassen -->

Widersprüchliche Wahlen, wie die rechteste Partei als Erstwahl und die linkeste Partei als Zweitwahl, sind nicht single-peaked und tragen dazu bei, dass evtl nicht-transitive Gruppenergebnisse entstehen.
<!-- TODO MH: genau, absolut, gutes Beispiel. Im Sinne der o.g. Ergänzung liegt das problem hier darin, das eben *keine* eine Präferenzordnung findbar ist, die für alle Wähler single-peaked preferences hervor ruft. Man könnte bsp. als dimension populistisch/nicht-populistisch verwenden, dann wäre vielleicht für diese Extremwähler ihre ordnung single-peaked, aber für viele andere (eher an rechts-links orientierte Wähler) wäre sie es möglicherweise nicht. DAS ist das problem. -->

Um solches Wahlverhalten zu vermeiden, muss
- eine Übereinstimmung aller Teilnehmer über die Verteilung der Alternativen bestehen.
- alle Teilnehmer über diese Verteilung aufgeklärt sein.

Fraglich ist, wie dieses Ziel zu erreichen ist.

Ist es überhaupt aus demokratischer Sicht vertretbar, eine allgemein gültige Ordung der Alternativen festzulegen?
Laut XY ist "nobody (is) obviously more qualified than anypne else", folglich kann auch niemand allein befähigt sein Meinungen zu ordnen.
Außerdem müssen alle bürger gut über die Wahlmöglichkeiten informiert sein, um single-peakedness zu erreichen.
Dahl drückt sich als sehr liberaler Demokrat allerdings sehr wage aus und sieht das "enlightend understanding" nicht als bedingungslose Grundlage einer Demokratie, da
Autonomie dadurch eingeschränkt würde.
Denn gerade dieses Prinzip vielfältiger Meinungen (inklusive der "fehlinformierten") hat XY dazu bewegt, ein auf Wahlen beruhendes demokratisches System als bestes Staatssystem einzuführen.
Kann eine Demokratie mit Wahlen dann überhaupt praktisch umgesetzt werden?
Oder ist vielmehr Dewey im Recht, wenn er die Demokratie im Kontext ihrer Zeit sieht und behauptet, sie sei niemals vollendet? (---ZITAT!!!)

Eine andere Möglichkeit wäre, Erziehung besser zu gestalten und den Bürgern wie Heini zu helfen eine gefestigtere Meinung zu entwickeln und "verwirrte Entscheidungen zu vermeiden. -> Benner
<!-- FIXME: MH In den oberen Absätzen sind noch Fragmente, unübersetztes etc. drin. -->
<!-- TODO: MH außerdem sollten die oberen Paragrafen mit den Lösungen der single-peakedness Probleme deutlich knapper ausfallen; das war ja eher so eine Randbemerkung. Für uns ist es Interessant hier auf die Notwendigkeit von Bildung sowie den Widerspruch zu liberalen Verschreibungen hinzuweisen. -->
