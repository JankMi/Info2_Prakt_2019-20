# Informatik 2 - Praktikum
## Ablauf
Wie aus dem Informatik 1 Praktikum bekannt:
Aufgaben aus dem Pool von Prof. Herold werden bearbeitet und im Praktikum abgenommen.

Die Vorgaben aus dem Informatik 1 Praktikum, wie:    
- die Überprüfung der Eingaben,
- Formatierung  
  
sind weiterhin gültig. 

Abgenommene Aufgaben werden auf dem Testatbogen abgezeichnet.  
**Sie sind für Ihren Testatbogen verantwortlich**


## Neuerungen zum WS 2019/20
### Speichern von Daten
Das Home-Laufwerk wird nicht mehr gesichert - nach dem Abmelden sind diese Daten weg! 
Verwenden Sie das Netzlaufwerk "Home".

### Nur Linux
Auf den Labor-PCs wird nurnoch Linux bereitgestellt.  
Die installierten C-"Entwicklungsumgebungen" sind:
- Visual Studio Code
- Geany
- emacs
- CodeBlocks
- Qt-Creator
  
Alle unter Anwendungen->Entwicklung zufinden.

#### Grundlegende Terminal-Befehle
- ls - list, zeigt die Dateien im aktuellen Ordner
- cd {Ziel} - change directory, wechselt in den Ziel-Ordner
  - ..   = übergeordneter Ordner
  -  .  = aktueller Ordner
  - ~ =  Home-Ordner
- mkdir {Name} - make directory, legt ein Verzeichnis an
- man {Befehl} - Hilfe Seite zum Befehl (ggf. auch {Befehl} --help)
- gcc - C-Compiler

### Visual Studio Code
Haben Sie in den Ziel ordner navigiert, können Sie mit "code ." den Ordner als Workspace öffnen.
![VSCodeScreenShot](/pics/VSCodeExample.png)

### Make-System
``` Makefile
CC= gcc
CFLAGS= -Wall

helloworld:
	$(CC) example.c $(CFLAGS) -o makeExample
	
# wird zu: gcc example.c -Wall -o makeExample
```
![VSCodeScreenShot](/pics/VSCode_makefileExample.png)

Mehr zum Thema http://www.cs.colby.edu/maxwell/courses/tutorials/maketutor/
