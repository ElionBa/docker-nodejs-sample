# Installation des Projekts

## Klonen des Repositories
#### 1. Navigieren Sie auf GitHub zur Hauptseite des Repositorys.

#### 2. Klicke oberhalb der Liste der Dateien auf  Code.


#### 3. Kopiere die URL für das Repository.

- Um ein Repository über HTTPS zu klonen, klicke unter „HTTPS“ auf .

- Wenn du das Repository mithilfe eines SSH-Schlüssels klonen möchtest, einschließlich eines Zertifikats, das von der SSH-Zertifizierungsstelle deiner Organisation ausgestellt wurde, wähle SSH und dann  aus.

- Um ein Repository über die GitHub CLI zu klonen, klicke auf GitHub CLI und dann auf.

#### 4. Öffne Git Bash.

#### 5. Ändere das aktuelle Arbeitsverzeichnis zum Speicherort, in dem Du das geklonte Verzeichnis haben willst.

#### 6. Gib git clone ein, und füge dann die zuvor kopierte URL ein.

#### 7. Drücke die EINGABETASTE, um den lokalen Klon zu erstellen.

Quelle [Github](https://docs.github.com/de/repositories/creating-and-managing-repositories/cloning-a-repository)

## Installation der Notwendigen Packete

### Scripts
- **Prettify**= Sorgt dafür das der Code einheitlich formatiert ist

- **test** = Ermöglicht es, automatisierte Tests für die Anwendung zu schreiben und auszuführen, um sicherzustellen, dass der Code korrekt funktioniert.
- **dev** = Sehr praktisch für die Entwicklung, da nodemon den Server bei Änderungen neu startet und das Debuggen erleichtert.

### dependencies
- **express** = Express ermöglicht es dir, eine Webserver-Anwendung zu erstellen, die HTTP-Anfragen (wie GET, POST) verarbeiten kann.
- **pg** = Ermöglicht die Verbindung zu einer PostgreSQL-Datenbank, um Daten zu speichern und abzurufen.
- **sqlite3** = Ermöglicht das Speichern von Daten in einer SQLite-Datenbank, die leichtgewichtig und lokal ist.
- **uuid** = Zum Erstellen von eindeutigen Bezeichnern für Datenobjekte.

- **wait-port** = Wartet darauf, dass ein bestimmter Port (auf dem ein Dienst läuft) verfügbar ist, bevor die Anwendung fortfährt.

### resolutions
- **ansi-regex** = Legt eine bestimmte Version eines Pakets fest, das möglicherweise von anderen Abhängigkeiten benötigt wird.

### prettier
- **trailingComma** = Dies erleichtert das Hinzufügen neuer Elemente und verringert das Risiko von Syntaxfehlern.
- **tabWidth** = Macht den Code besser lesbar und strukturiert, da die Einrückungen klar erkennbar sind.

- **useTabs** = Sorgt für Konsistenz in der Formatierung, da Tabs in verschiedenen Editoren unterschiedlich angezeigt werden können.

- **semi** = Verbessert die Lesbarkeit und verringert potenzielle Probleme durch fehlende Semikolons.

- **singleQuote** = Konsistente Nutzung einfacher Anführungszeichen verbessert die Lesbarkeit und verringert Inkonsistenzen.

### devDependencies
- **jest** = Ermöglicht das Schreiben und Ausführen von Tests, um sicherzustellen, dass die Anwendung wie erwartet funktioniert. Tests helfen dabei, Fehler frühzeitig zu erkennen und die Codequalität zu verbessern.

- **nodemon** = Ideal für die Entwicklung, da der Server bei jeder Änderung automatisch neu startet, was die Entwicklung effizienter macht und manuelle Neustarts überflüssig macht.
- **prettier** = Prettier sorgt dafür, dass der gesamte Code einheitlich und lesbar ist, was bei der Zusammenarbeit und Wartung des Codes hilft.

## [Docker-Konfiguration und -Installation](https://www.docker.com/products/docker-desktop/)
