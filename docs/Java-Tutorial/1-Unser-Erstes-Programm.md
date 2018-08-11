# 1. Unser erstes Programm

---

Damit Ihr hier alles versteht, würde ich euch die Einführung in Eclipse ans Herz legen, diese findet Ihr [hier](../Editor-und-IDE/Eclipse.md).

Hier werden wir nun unser erstes Java Programm schreiben.

Öffnet dazu das Programm Eclipse und erstellt ein neues Projekt. Nennt es wie Ihr wollt.
Danach wird eine Klasse und die ***Main Method*** hinzugefügt. Nenn die Klasse am besten **HelloWorld**.

Danach seht Ihr folgendes im Editor:
```java
public class HelloWorld {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
	}
}
```
Das ist erstmal sehr überfordernt am Anfang. Doch was bedeuted das alles ?

Gehen wir den Code einmal durch.

In der ersten Zeile steht **`public class HelloWorld`**, dies bedeute das wir dort eine Öffentliche Klasse Namens *HelloWorld* erstellen, zu Klassen kommen wir später noch. Ihr braucht es noch nicht zu verstehen, mir ist die Strukturierung wichtig damit Ihr wisst wie man dies zu lesen hat. 

Danach folgt eine `{`, diese Geschweifteklammer sagt aus, dass es sich hier um ein Block von Code handelt. 

In der Klammer sehen wir dann **`public static void main(String[] args)`**. Dabei handelt es sich um eine Methode die Öffentlich ist und diese von überall im Programmcode aufgerufen werden kann. Dazu sagt das keyword `static` aus das diese Methode statisch ist, dazu auch später mehr. Als letztes sehen wir `void main`. Ihr seht außerdem eine **`()`**, da stehen sogenante Parameter drin, eine erklärung folg später Jede Methode oder Funktion benötigt einen Rückgabewert, in diesem Fall ist es `void` also nichts. 

Das keyword `main` muss in jedem Programm vorhanden sein. Es ist der Startpunkt jedes Programmes. Ohne eine Main Methode kann ein Programm nicht gestartet werden ! Es folgt wieder eine `{` und dann stehen so komische `//` Zeichen, das sind sogenante Kommentare. Es gehört zum guten Ton, Programme ausführlich zu kommentieren. Java ignoriert Kommentare, sie werden also nicht mit in die Laufzeit eigebunden. Am Ende wird die zweite `}` geschlossen. Als allerleztes wird die erste `}` geschlossen. Alle Klammern müssen geschlossen werden, sonst kommt es zu Fehler !

Wenn Ihr nun versucht das Programm auszuführen, wird euch aufallen, dass hier gar nichts passiert. Das liegt daran, weil das Programm nichts weiter macht als zu starten. Es liegt ja auch keine Anweisung in der `Main` Methode vor. 

Irgendwie langweilig oder ?

Damit das Programm irgendwas macht, schreiben wir mal etwas hinzu. 
Fügt folgendes der **Main Methode** hinzu. 

```java

System.out.println("Hello World);
```

In Eurer Datei steht jetzt folgendes:

```java
public class HelloWorld {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Hello World");
	}
}
```

Aber was genau haben wir da jetzt gemacht ?

Wir rufen die Methode `println` von dem Objeckt `out` auf. Dieses Objekt gehört zur Klasse `System`.

Die Begriffe Objekte, Klassen und Methoden werden später noch erklärt. Es reicht erstmal das Ihr wisst, dass es diese Begriffe existieren.

Klickt jetzt oben auf den Ausführen Button. Wenn nun unten `Hello World` als als Ausgabe erscheint, habt Ihr erfolgreich euer erstes Programm geschrieben.


Im nächsten Kapitel werden wir uns mit Datentypen und Variablen beschäftigen. Klickt dazu [hier](2-Datentypen-und-Variablen.md).

Und keine Sorge wenn Ihr das Beispiel oben noch nicht verstanden habt, im folgenden Kapitel wird alles erklärt.

