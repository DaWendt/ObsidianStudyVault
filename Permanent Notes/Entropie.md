tags: #CuB 

---------
Ist ein theoretisches Maß für den mittleren Informationsgehalt eines Bildes.

Die Interpretation sieht folgendermaßen aus:
- hohe Entropie: viel Zufälligkeit, hohe Unberechenbarkeit, wenig Redundanz
- niedrige Entropie: wenig Zufälligkeit, hohe Belastbarkeit, hohe Redundanz

Die Entropie H wird in Bit angegeben und wird für $N = 1$ wie folgt berechnet:

$$
- \sum_{g=0}^{|G| - 1} (p_s(g) \log_2(p_s(g)))
$$
Wenn ich eine Bildkompressionsrate ermitteln möchte, so kann ich die Entropie als Abschätzung für den extremen Fall verwenden. Allerdings nur als untere Schranke.