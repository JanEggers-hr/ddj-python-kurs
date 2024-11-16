# Installation, Schritt für Schritt

...was wir im Seminar getan haben: 

## Miniconda installieren

Eine Python-Umgebung mit allem Drum und Dran für Windows, Mac (neuere: M1, älter als 2020: Intel) und Linux-Rechner. 

- Auf die Seite https://docs.anaconda.com/free/miniconda/ gehen
- Das passende Programmpaket anklicken und installieren
- Die **Kommandozeile** ausführen: 
    - Auf Mac: Das Programm "terminal" suchen und starten
    - Auf Windows: Startfläche links unten anklicken, "CMD" anklicken (bzw.: nach dem Installieren von Miniconda das "Anaconda Prompt")
    - Auf Linux: Hey, wer Linux hat, kann das auch selbst.
  - Ein wenig zwischen den Ordnern herumnavigieren, mit diesen Befehlen: 
    - ```mkdir name``` legt im augenblicklichen Ordner einen Unterordner ```name``` an
    - ```cd name``` wechselt in den Unterordner
    - ```cd ..``` wechselt zurück in den übergeordneten. 
    - Inhalt des augenblicklichen Ordners anzeigen lassen: ```dir``` (Windows) bzw. ```ls -l``` (Mac und Linux)
  - Auf der Kommandozeile eingeben: ```python``` - wir kriegen ```>>>``` als Eingabeaufforderung
  - In Python rechnen: z.B. ```15 * 5```

## VSC installieren

Den Editor für Programmierer installieren: VSC, Visual Studio Code

[code.visualstudio.com](https://code.visualstudio.com/)

In VSC auf der linken Seite auf die "Erweiterungen" (das Symbol mit den drei kleinen Quadraten und dem vierten, das eingepuzzlet wird), und suchen und installieren: 

- Deutsch
- Python
- Python Debugger
- juPyter
- Continue

## Unser erstes Python-Programm 

- In VSC eine neue Datei öffnen - VSC fragt, was für eine; wir so: Python

```
print("Hello World!")
i = 1234 * 5
print(i)
```

Neues Programm, zum Debuggen: 

```
j = input(„Zahl eingeben“
print (5 * j)
```
Wieso funktioniert das nicht wie erwartet? Der Debugger verrät es uns - die Möglichkeit, ein Programm Schritt für Schritt auszuführen. 

Öffne den Debugger - das Play-Symbol mit dem kleinen Käfer. Klicke neben die zweite Zeile (die mit dem Print-Befehl), sodass ein roter Punkt erscheint. Führe das Programm im Debugger aus - es stoppt in der Print-Zeile; links zeigt es uns an, dass j keine Zahl enthält, sondern eine Zeichenkette mit einer Zahl, und das ist für den Computer etwas anderes. Also:
```
j_text = input(“Zahl eingeben”)
j = int(j_text)
print(5 * j)
# (Verstehen: Text ist keine Zahl!)
```

## Git und Github
Jupyter extension	https://github.com/JanEggers-hr/ddj-python-kurs herunterladen und entpacken
14:30	Ipynb Hello World	Notebook-Zellen ausführen
 	Ipynb Übung 01	 
 	Continue installieren	https://www.janeggers.tech/eeblog/2024/quickie-so-schreibt-die-ki-deinen-programmcode-mit/
VSC-Extension "Continue" installieren; API-Token einklinken
 	Platform.openai.com für API-Key	OpenAI-API-Key generieren (für Abrechnung: Kreditkartendaten) 
- Übrigens noch ein Stückchen besser beim Programmieren: Claude 3.5 Sonnet von Anthropic
 	Ollama	z.B. deepseek-coder:6.7b - das läuft auch in einem 16GB-Computer ganz ordentlich
15:00	DONE	 
