 04.06.2019, Montag

## **Git/GitHub & Shell Commands**

#### Git & GitHub Begriffe

Git ist ein System das entwickelt wurde um Versionen von Textdateien zu 

![GitHub explained](https://blog.red-badger.com/hubfs/Imported_Blog_Media/img-257.jpg)
*Quelle: blog.red-badger.com/2016/11/29/gitgithub-in-plain-english*


# Cheat Sheet für **Shell Befehle**

#### Wechseln zu anderen Ordnern / Inhalt anzeigen etc.:
**Befehl** | **Effekt**
------ | ------
`cd [Ordnername]` | change directory
 `..` | Weiterleitung in übergeordnete Ordner
 `z neu` = `cd ~/neuefische` | z lernt oft benutzte Ordner und bietet so Abkürzung
 `ls` | Liste aller Dateien und Unterordner eines Ordners
 `ls -la` | Liste mit Details `l` (=long; untereinander auflisten) und durch `a` (=all) werden auch versteckte Dateien angezeigt
 `tree` | Verzeichnisbaum anzeigen
 `curl` | lädt Objekt über eine URL
 `cat` | zeigt den Inhalt einer Datei

#### Neu, verschieben, kopieren, löschen, öffnen:

**Befehl** | **Effekt**
------ | ------
 `mkdir` | Ordner erstellen
 `mkdir [Ordner/Unterordner]` | Unterordner erstellen
 `mkdir -p [Ordner/Unterordner/Unterunterordner/...]` | Ordnerpfad wird erzeugt
 `touch [Dateiname]` | Datei erstellen
 `mv [alter Name] [neuer Name]` | Ordner/Datei umbenennen
 `mv [alter Pfad] [neuer Pfad]` | Ordner/Datei verschieben
 `mv [Ordner] *` | verschieben des Ordners in den aktuellen Ordner
 `cp -R [src-directory] [target-directory]` | kopiert alles aus dem Quellverzeichnis in das Zielverzeichnis
 `pbcopy` | speichert Eingabe in die Zwischenablage (Bsp.: `cat ~/.ssh/id_rsa.pub | pbcopy`)
 `rm` | remove (geht nur bei Dateien)
 `rm -rf` | Ordner löschen; `r` = rekursiv (alles in allen Unterordnern); `f` = force (nicht jede Datei einzeln bestätigen); auch *Rimraf* genannt
 `rm -rf *` | löschen aller Ordner und Dateien im aktuellen Ordner
 `code .` | aktueller Ordner wird bei VS Code aufgerufen
 `open [Datei]` | öffnet Datei mit dem Standardprogramm eines Betriebssystems
 `open .` | öffnet Ordner im Finder/Explorer







