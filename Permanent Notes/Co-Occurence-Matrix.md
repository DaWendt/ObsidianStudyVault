tags: #CuB 

------
Eine solche Matrix braucht 2 Dinge:
- Ein Bild zur Analyse
- Eine Relation (z.B.: rechter Nachbarpixel r)

Die Größe der Matrix $W$ ist in diesem Fall Quadratisch und entspricht der $|G|$. Die Indexe von $G$ bestimmen die Position in der Matrix.

Beispiel:

Wie oft kommt die Wertkombination $g_1 \space r \space g_2$ vor?
Position der Antwort: $(g_1/g_2)$

Die Matrix hat ein paar interessante Interpretierungsmöglichkeiten.
Auf der Hauptdiagonalen sind logischerweise alle Kombinationen vertreten wo $g_1=g_2$ ist. 
--> Dies sagt aus wie groß der homogene Bildbereich dieses Farbwerts ist!
