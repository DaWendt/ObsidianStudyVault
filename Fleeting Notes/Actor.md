tags: #Ver-Sys 

--- 
Eine Gruppe an Actors sind Einheiten die sich keinen Speicher teilen, nebenläufige Einheiten sind und **ausschließlich** über Nachrichten kommunizieren.

Die Kommunikation nennt sich [[Message-Passing]].

Die Daten werden sequenziell abgearbeitet und ein Actor bearbeitet nur eine Nachricht auf einmal. Der Rest landet in einem Queue-System.

Passenderweise gibt es eine Option mit unterschiedlichen Sprachen ein Actor-System zu bauen: [[Proto.Actor]]


##### Bestandteile

- Mailbox
- Verhalten
- Nachrichten
- Ausführungsumgebung
- Adresse

##### Fehlersituationen

Bei Abstürzen oder Fehlern gibt es den Supervisor, welcher reagieren kann.