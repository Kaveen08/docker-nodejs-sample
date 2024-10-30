Ein Repository klonen

1.  Navigieren Sie auf GitHub zur Hauptseite des Repositorys.

2.  Klicke oberhalb der Liste der Dateien auf <> Code.

    Screenshot: Liste der Dateien auf der Startseite eines Repositorys. Die Schaltfläche „Code“ ist orange umrandet.

3.  Kopiere die URL für das Repository.

- Um ein Repository über HTTPS zu klonen, klicke unter „HTTPS“ auf (EInfügen)
- Wenn du das Repository mithilfe eines SSH-Schlüssels klonen möchtest, einschließlich eines Zertifikats, das von der SSH-Zertifizierungsstelle deiner Organisation ausgestellt wurde, wähle SSH und dann (Einfügen) aus.
- Um ein Repository über die GitHub CLI zu klonen, klicke auf GitHub CLI und dann auf

4.  Öffne Git Bash.
5.  Ändere das aktuelle Arbeitsverzeichnis zum Speicherort, in dem Du das geklonte Verzeichnis haben willst.

6.  Gib git clone ein, und füge dann die zuvor kopierte URL ein.


    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

7.  Drücke die EINGABETASTE, um den lokalen Klon zu erstellen.


    $ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
    > Cloning into `Spoon-Knife`...
    > remote: Counting objects: 10, done.
    > remote: Compressing objects: 100% (8/8), done.
    > remove: Total 10 (delta 1), reused 10 (delta 1)
    > Unpacking objects: 100% (10/10), done.

Quelle: [Github](https://docs.github.com/de/repositories/creating-and-managing-repositories/cloning-a-repository)

0
- express: Ein Framework für Node.js, das die Erstellung von Web- und API-Anwendungen vereinfacht.

- pg: Ein Client für PostgreSQL, der Verbindungen zur PostgreSQL-Datenbank herstellt und SQL-Befehle ausführt.

- sqlite3: Ein Modul, das SQLite-Datenbanken unterstützt, bei denen keine komplexe Datenbankinfrastruktur nötig ist.

- uuid: ErzeugtIdentifikatoren, nützlich, um sicherzustellen, dass jedes Objekt oder jede Sitzung eine eindeutige ID besitzt.

- wait-port: Ein Tool, das wartet, bis ein bestimmter Netzwerkport verfügbar ist, hilfreich für Anwendungen, die von anderen Diensten abhängig sind, bevor sie gestartet werden.

Auf der [Webseite von Docker](https://www.docker.com/get-started/) kann man Docker herunterladen für Windows.

