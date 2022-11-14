# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.

## TODO
- Begriffe definieren und erklären (z.B. repository, branch etc.)
- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)
- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)

- Repository - Mit dem Begriff Repository wird eine zentrale Ablage für Daten, Dokumente, Programme, Metadaten und Datenmodelle bezeichnet.
  Ein Repository ist ein Verzeichnis oder Archiv, das zur Verwaltung verschiedenster 
  Daten verwendet wird und mitunter auch das Management der unterschiedlichen Dateiversionen beinhaltet.
- Branch - In Git sind Branches Bestandteil deines alltäglichen Entwicklungsprozesses.
  Git-Branches sind quasi Verweise auf einen Snapshot deiner Änderungen.
- Staging Area

## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen)
abstract-Modifizierer in einer Klassendeklaration, um anzugeben, 
dass die Klasse nur die Basisklasse für andere Klassen sein und nicht selbst instanziiert werden soll. 
Als abstrakt markierte Member müssen von Klassen, die von nicht abstrakten Klassen abgeleitet wurden, implementiert werden.
public abstract class A{}
public class B : A {}
  - abstract (Methoden)
Verwenden Sie den abstract-Modifizierer in einer Methoden- oder Eigenschaftendeklaration,
um anzugeben, dass die Methode oder Eigenschaft keine Implementierung enthalten.
public abstract void MyMethod();
  - virtual
Das Schlüsselwort virtual wird zum Ändern einer Methoden-, Eigenschaften-, Indexer- oder Ereignisdeklaration verwendet,
und lässt zu, dass sie in einer abgeleiteten Klasse außer Kraft gesetzt werden. Diese Methode kann z.B. von jeder Klasse, die sie erbt, überschrieben werden:
public virtual double Area()
{
    return x * y;
}
  - override
Das Überschreiben von Methoden ist eine Technik, mit der Sie eine Funktion aus einer anderen Klasse (der Basisklasse) innerhalb einer abgeleiteten Klasse aufrufen können. Das Erstellen einer abgeleiteten Klassenmethode mit derselben Signatur wie eine Basisklassenmethode wird als Methodenüberschreibung bezeichnet. Von einer Unterklassenmethode wird gesagt, dass sie eine Oberklassenmethode überschreibt, wenn sie denselben Namen, dieselben Parameter oder Signaturen und denselben Rückgabetyp (oder Untertyp) wie die Oberklassenmethode hat. Überschriebene Basismethoden müssen virtuell, abstrakt oder überschrieben sein.
  - Polymorphie
Allgemein kennzeichnet polymorph die Fähigkeit eines Objekts unterschiedliche Formen anzunehmen. Der Begriff Polymorph stammt aus dem Griechischen: Poly = viele, morph = Form. Für die objektorientierte Programmierung ist die Polymorphie ein mächtiges Werkzeug und zugleich ein zentrales Konzept jeder objektorientierten Programmiersprache. Während mit dem Überladen von Methoden alle Methoden den gleichen Namen aber unterschiedliche Argumente nutzen, erweitert die Polymorphie dieses Programmierkonzept. Polymorphes Überschreiben nutzt sowohl identische Methodennamen wie auch identische Argumentnamen. Somit definiert Polymorphie zwei Methoden mit identischem Rückgabetyp und identischer Argumentenliste.

- Wie überschreibt man die Methode `virtual string ToString()`?
