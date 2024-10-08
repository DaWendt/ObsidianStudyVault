## Konventionen

- für gewöhnlich nimmt man pro definierter Funktion ein File
## Organisationsstruktur

- das package system wird immer am Anfang des Files definiert
	```
	<file main>
	package main 

	func main(){
	}
	```
	- die main Funktion ==muss== im package main sein!
- generell deklariert das package den Ort im Go-Code
## Neat Stuff

- das [[package-fmt]] gibt uns Printoptionen
- go doc etwas gibt die Dokumentation

## Datenstrukturen
### [[Slices]]:
Eine repräsentative Sicht auf Arrays.

## Syntax
- im Allgemeinen deklariert man zuerst den Namen, dann den Typ. Dies gilt auch für [[Methoden-in-go]].
## Testen
[[Testen-in-go]] ist relativ leicht und wird mit dem Befehl go test <Verzeichnis> realisiert.