# Kapitel 7 Übung in der Vorlesung ("Autos mit ```private```, ```static``` und ```final```")

> Diese Übung baut auf der Kapitel 6 Übung ("Autos, Fahrer und Wettrennen") auf! Sie sollten diese Übung daher am besten in Ihrem eigenen Fork von uebung_6 umsetzen. Notfalls können Sie auf der in diesem Repository bereitgestellten Lösung aufbauen, allerdings ist der Lerneffekt bei diesem Vorgehen geringer!

## ```private```

* Ändern Sie die Klasse ```Auto``` aus der vorangegangenen Veranstaltung derart, dass Sie alle internen Details des Autos als ```private``` deklarieren und nur noch über Hilfsmethoden verändern oder ausgeben lassen.
* Erstellen Sie wirklich nur Hilfsmethoden, wenn dies notwendig ist! Das Erstellen von Methoden „auf Verdacht“ oder „auf Vorrat“ ist schlechter Stil!

## ```final```

* Ändern Sie die Klasse ```Auto``` aus der vorangegangenen Veranstaltung derart, dass sich der Verbrauch eines Autos nach der Erzeugung eines Objektes nicht mehr verändern kann.

## ```static```

* Fügen Sie ein neues Attribut ```fahrgestellnummer``` hinzu, welche beim Erzeugen eines Autos automatisch (d.h. nicht über einen Konstruktorparameter) zugewiesen werden soll
* Es dürfen niemals zwei Autos dieselbe Fahrgestellnummer bekommen. Stellen Sie dies sicher, indem Sie sich die zuletzt vergebene Fahrgestellnummer als statisches Attribut der Klasse ```Auto``` merken.
