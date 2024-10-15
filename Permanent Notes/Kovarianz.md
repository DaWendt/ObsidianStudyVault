tags: #CuB 

----
Allgemein gesagt beschreibt die Kovarianz $v$ das Maß für linearen Zusammenhang zweier Variablen. In unserem Fall sprechen wir hier von den Farbkanälen $i$ und $j$.

$$
v_{i,j}=\frac{1}{L*R}\sum_{x=0}^{L-1}\sum_{y=0}^{R-1}(s(x, y, i) - m_{S,i})(s(x, y, j)-m_{S,j})
$$
Erinnerung: $m_{s,i}$ beschreibt den [[Mittelwert]].

Die Interpretation sieht dabei folgendermaßen aus:
- $v_{i,j}>0$ : Beide Variablen bewegen sich in die selbe Richtung
- $v_{i,j}<0$ : Beide Variablen bewegen sich entgegengesetzt
- $v_{i,j}\approx 0$ : Kein linearer Zusammenhang zwischen Variablen

Um alle Kanalkombinationen sowie deren Kovarianzen festzuhalten erschafft man eine Kovarianzmatrix.

