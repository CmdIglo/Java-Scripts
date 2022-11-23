In diesem Ordner sind kleine eigene Projekte zum Thema Vigenere-Verschlüsselung hinterlegt.
Der Code "Vigenere.java" ist ein Verschlüsselungs-Programm, das einen Satz und einen Schlüssel als Input nimmt.
Als Ausgabe liefert das Script den verschlüsselten Satz.

Im Ordner "Server Client App" sind drei Scripts hinterlegt, die zusammen arbeiten.
In diesem Projekt habe ich einen "Chat Raum" implementiert, der über den localhost läuft. Später sollen hier
die Nachrichten mit, je nach ausgewählter Art im GUI, entweder dem Caesar oder dem Vigenere Verfahren verschlüsselt werden.
Die Klasse "Client.java" implementiert bereits eine Methode "vigenere", die den eingegebenen Text des Users verschlüsselt.
Die Methode "caesar" muss jedoch noch implementiert werden. 
Das Projekt funktioniert so: 
Der Server, "Server.java" muss gestartet werden. Erst dann kann man einen Client öffnen, wobei es natürlich mehr Spaß macht, 
wenn man direkt zwei Clients öffnet mit "Client.java". Die Clients verbinden sich dann mit dem Server und senden als erstes, mit der 
ersten Nachricht an den Server ihren Name, den man als User im GUI unter "Settings/Username" festlegen muss. Nun kann man im Textfeld
eine Nachricht eingeben und diese dann los schicken. Da ich gerade erst mit dem Schreiben dieses Projektes angefangen habe, wird aus
irgendeinem Grund die erste Nachricht beider Clients nie zugestellt. Erst bei der zweiten Nachricht des zweiten Clients kommen die 
Nachrichten an. 
Wenn die Nachrichten jedoch erst einmal ankommen, also ab der zweiten Nachricht, bringt es Spaß ein wenig mit sich selber zu reden, oder
man startet einen Client auf zwei verschiedenen Computern und ändert auf dem PC, auf dem der Server nicht läuft, den Client-Socket
von "localhost" auf die IP-Addresse des Server-Computers im Netzwerk.
Auch diese Funktion soll im GUI Applet folgen, muss jedoch auch erst implementiert werden und das ist sehr anstrengend...

Um den Chat-Raum mit zwei verschiedenen Clients zu veranschaulichen, ist in dem Projekt "Server Client App" außerdem ein Bild von zwei
verbundenen Clients hinterlegt.