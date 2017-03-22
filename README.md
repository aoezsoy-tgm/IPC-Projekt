# IPC-Projekt

Die Aufgabenstellung:

Erstelle einen Java- ODER Python-Client, der sich mit dem Server verbindet und selbstständige Entscheidungen trifft!

Grundanforderungen (50%):

    Nimm den simplen "manuellen" Client als Vorlage, um zu sehen, wie die Kommunikation mit dem Server funktioniert
    Dein Client-Programm wird über die Kommandozeile gestartet, wobei
        der Port
        die IP-Adresse des Servers
        die Zeilenanzahl des Spielfeldes (Größe)
        die Spaltenanzahl des Spielfeldes (Größe)
        als Kommandozeilenparameter übergeben wird
    Dein Client lässt den Benutzer einen Spielernamen wählen und überträgt diesen nach dem Verbindungsaufbau an den Server. Der Server bestätigt die Nachricht mit "OK"
    Der Client schickt anschließend basierend auf den Antworten des Servers selbstständig (ohne Benutzereingaben) Move-Befehle:
        "UP": Nach oben bewegen
        "RIGHT": Nach rechts bewegen
        "DOWN": Nach unten bewegen
        "LEFT": Nach links bewegen
    Der Client lässt die Spielfigur NICHT ins Wasser fallen
    Der Client bewegt sich zur Schriftrolle, wenn er sie sieht
    Der Client bewegt sich zur gegnerischen Burg, nachdem er die Schriftrolle eingesammelt hat
    Ansonsten erkundet der Client die Landschaft - auf der Suche nach Schriftrolle bzw. Burg
    Alle Verbindungen werden sauber geschlossen
    JavaDoc/DocString-Kommentare sowie Dokumentation (Sphinx/JavaDoc) sind vorhanden
    Protokoll über den implementierten Algorithmus

Erweiterungen (30%):

    Arbeite dich in den Code des Servers ein
    Erweitere den Server, sodass beliebig große Spielfelder unterstützt werden!
    Sowohl die Größe des Spielfeldes als auch die anderen Parameter (Anzahl an Waldfeldern etc.) sind über den GUI konfigurierbar
