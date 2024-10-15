Ein gerastertes [[Bild]] s kann man als eine Matrix S mit L Zeilen und R Spalten darstellen.

Jeder Eintrag hält einen N-Dimensionalen Farbwert g und lässt sich über ein Koordinatentupel referenzieren.
### Notation für einzelne Bilder

Wenn N größer als 1 ist, sollten wir in der Lage sein den richtigen Farbkanal auch über das Koordinatentupel anzusteuern.
$$
s: N^M + 1 \rightarrow N
$$

Damit lassen sich für M = 2, N Kanäle folgendermaßen ansprechen: 

$$
s(x, y, n) = g \quad g \in G
$$
### Notation für Bilder in einer Sequenz

Hier nehmen wir wie oben genannt das gleiche Tupel, fügen dem aber noch einen Part t hinzu der auch die Position in der Sequenz beschreibt.

$$
s(x, y, n, t) = g \quad g \in G
$$

#CuB 