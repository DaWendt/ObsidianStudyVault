Beschreibt den Status eines Containers, also sowas wie eine Blaupause welche die Bestandteile des Containers beschreibt.

Sie werden schichtweise aufeinander gestapelt, mit einem base image als Fundament. Images können aus niederen Schichten Files 
- erben 
- hinzufügen
- ersetzen 
- löschen

### Bestandteile

Directory Tree: Beinhaltet all jene Software welche für die Laufzeit essentiell ist.

Manifest list: Ein JSON-File dass mehrere Images verlinkt um verschiedene Architekturen zu unterstützen.

Ein weiteres JSON File (config) was rootfs, env variables, runtime user etc. definiert.

