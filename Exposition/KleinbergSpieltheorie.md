# Spieltheorie

**Spieltheorie** (siehe: Kleinberg, "Networks,Crowds and Markets", S.153-274) modelliert menschliche Interaktion in Form von Spielen, dessen *Spielausgänge* von den gewählten *Spielstrategien* abhängen und in Form einer Auszahlungsmatrix analysiert und veranschaulicht werden können.
<!-- TODO: MH hier brauchen wir auch die Annahmen der Spieltheorie: was machen/wissen Menschen? -->
<!-- TODO: MH wichtig auch verweis darauf das Spieltheorie sich mit wechselseitig abhängiger Interaktion beschäftigt; was gefangenem 1 passiert, betrifft 2 und umgekehrt. -->
<!-- TODO: MH zunächst mal überhaupt Auszahlungsmatrix erklären, was ist das? hier auch Darstellung über ein Spiel und Auszahlungsmatrix einfügen. Bedeutung der Zellen etc. klären. -->


## Die Spielstrategien

Die **streng Dominante**, die Strategie, in der der Spieler  stets nach Eigeninteresse spielt und stets die, unabhängig von den Mitspielern, beste Spielentscheidung für ihn selbst trifft. (vgl. ebd. S.164).
<!-- TODO: MH besser wäre: eine Strategie ist streng dominant, wenn ... -->
<!-- FIXME: MH das Eigeninteresse würde ich oben schon nennen, als Annahme – hier geht es jetzt nur um die  beste Auszahlung -->
Das **best response**, die Strategie, die zu der Strategie eines anderen Spielers am besten passt, d.h. die eigene Auszahlung ist am höchsten.
Hier sind mehrere beste Antworten möglich, wenn die Auszahlungen bei mehreren “Antwort-Strategien” gleich sind. (vgl. ebd. S.163)
<!-- TODO: MH würde das andersrum machen; erst best response, dann dominante Strategie. -->
<!-- FIXME: MH deutsche Begriffe nehmen: beste Antwort, nicht best response -->


## Spielausgänge

Das *Nash-Gleichgewicht* entsteht,wenn die die beiden Spieler Strategien gewählt haben, die jeweils die beste Antworten aufeinander sind.
Das *soziale Wohlfahrtsoptimum* ist die Zellenkombination mit der höchsten Summe.


Der Erfolg einer Person im Spiel liegt somit nicht nur in seinen eigenen Entscheidungen, sondern darin welche Spielentscheidungen von allen anderen getroffen werden:

>„Game theory is concerned with situations in which decision-makers interact with one another, and in which the happiness of each participant with the outcome depends not just on his or her own decisions but on the decisions made by everyone." (Kleinberg; Networks, Crowds and Markets, S.156)
<!-- TODO: MH das wäre auch ein guter einstieg, oder? -->



### Die Axiome der Spieltheorie

Nach Annahme der Axiome der "Spieltheorie" entscheidet sich der Mensch in seinem Handeln stets streng ökonomisch, das heißt, er verfolgt die Strategie mit dem größtmöglichen Gewinn (vgl. ebd. S.159).
Außerdem wird angenommen, dass jeder den "Spielplan" (vgl. ebd. S.159) kennt und somit auch alle Spielstrategien und Mitspieler.
Die letzte Annahme geht aus dem Prinzip der "Raionalität" hervor und vereint zwei Annahmen: Zum einen die des "Homo ökonomikus" und zum anderen die Annahme, dass jeder Spieler die beste "Spielstrategie" wählt (vgl. ebd., S.156).
TODO: MH anders strukturieren letzten satz. Spieltheorie/homo oek. basiert auf a) rationaler b) individueller c) Nutzenmaximierung.

Die Axiome sind vergleichbar mit folgender Annahme von Adam Smith:

>"Wer sein eigenes Interesse verfolgt, befördert das Wohl der Gesamtgesellschaft häufig wirkungsvoller, als wenn er wirklich beabsichtigt, es zu fördern. Ich habe nie erlebt, dass viel Gutes von denen erreicht wurde, die vorgaben, für das öffentliche Wohl zu handeln."
> (Adam Smith; „Wealth of Nations"(S.?))
<!-- TODO: MH super Zitat!!! -->
<!-- TODO: MH allerdings widerspricht das Zitat der Logik des Gefangenendilemmas; zwar werden gleiche Annahme nüber Menschliche Motivation getroffen, aber das Ergebnis ist radikal anders – Nash im PD führt eben nicht zum "öffentlichen Wohl." -->


### Die Spielvarianten

Zum einem kann es **Nullsummenspiele** geben.
Dabei haben alle Spielausgänge die gleiche Summenanzahl.
Zum anderen kann es **Positivsummenspiele** geben.
Ein Nichtnullsummenspiel enthällt unterschiedliche Summenanzahlen in unterschiedlichen Spielausgängen.
Da der Mensch nach Annahme der Axiome der "Spieltheorie" stets danach strebt den höchstmöglichen Gewinn zu erzielen, und eine höhere Gewinnmaximierung nur bei Nichtnullsummenspielen gegeben ist, lassen sich nur nach Positivsummenspielen Aussagen über menschliche Kooperation treffen.
Demnach geben Nullsummenspiele keine Aussage über menschliche Kooperation, da die Summenanzahl bei jedem Spielausgang gleich bleibt.

Es ergeben sich auf diese Weise zwei möglich Spielausgänge von Positivsummenspielen:
<!-- TODO: MH Würde erwägen diese Unterscheidung direkt am Anfang zu treffen, um quasi den Leser einzunorden, damit der weiss wo wir sind. Tabelle/Baumdiagramm zur Übersicht wäre auch gut. Ganz eventuell könnte das hier sogar in die Einführung.md... -->

1. Spiele **totaler Harmonie**: Summenanzahlen von Nash-Gleichgewicht und Wohlfahrtsoptimum fallen zusammen.
<!-- TODO: MH nein, *zellen* des Nash und des Wohlfahrtsoptimum fallen vor allem zusammen. Nash liegt im Wohlfahrtsoptimum -->
Beispielweise zeigt sich dieser Spielausgang im Handel oder in der Kinderaufzucht, da es auch im Interesse der Eltern ist ihre Gene fortzutragen.
<!-- TODO: MH on second thought, vielleicht lieber beim Handel nach Smith bleiben (mit o.g. Zitat), Kinderaufzucht macht nur Ärger. -->

2. Spiele mit **Kooperationsproblemen**: Summenanzahl von Wohlfahrtsoptimum und Nash Gleichgewicht unterscheiden sich.
Ein Beispiel wäre das der Nationalen Co2 Emissionen. Entscheidet sich ein Land weniger Umweltschutzmaßnahmen zu treffen so profitiert es davon nur, solange die anderen Ländern nicht die gleiche Strategie wählen.


## Das Gefangenendilemma lösen

>"Gentlemen, Adam Smith needs revision" (John Nash)

Außer durch den Einfluss eines Gewaltmonopolists oder einer Änderung der Axiome, kann das Gefangenen Dilemma nicht gelöst werden, da die Konzeption dem Menschenbild des homo ökonomicus unterliegt und davon ausgeht, dass jeder nur aus Eigeninteresse handelt und das Optimum, da die dritte Annahme (siehe oben) unzutreffend ist und ggf. nur per Zufall erreicht wird.
<!-- MH TODO: den letzten Satz verstehe ich nicht. -->
<!-- MH TODO: hier wäre vielleicht ein Hinweis auf Tilly ganz gut – die Staatsgenese löst ja schließlich sozusagen das Problem; sie stellt einen Gewaltmonpolisten bereit. -->

Adam Smith lag somit mit seiner Annahme, dass die *streng dominante* Spielstrategie stets auch am besten zum Allgemeinwohl beiträgt falsch, da man nicht grundsätzlich von Spielen *totaler Harmonie* ausgehen kann und es dementsprechend, wie aufgezeigt, auch zu Kooperationsproblemen in menschlicher Interaktion kommen kann.
<!-- MH TODO: guter Schluss! es sollte allerdings beste Antwort sein, nicht streng dominante Strategie -->
<!-- MH TODO: hier fehlt auch noch eine Überleitung zum nächsten Teil und/oder Anwendung -->
