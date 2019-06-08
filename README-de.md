Example 0.8.2
=============
Beispielerweiterung für Entwickler.

Sprache: [English](README.md), Deutsch

**TODO:** *Verwende diese Erweiterung zum Erstellen einer neuen Funktion. Sie enthält die Dateien `example.php` mit Beispiel-Code, `extension.ini` für Metadaten sowie `README.md` als Dokumentationsvorlage. Beginne die Dokumentation mit dem Namen deiner Erweiterung, gefolgt von einer einzeiligen Beschreibung. In den unteren Sektionen ist Platz für weiteren Text. Falls möglich, füge ein Bildschirmfoto hinzu. Im Sinne einer internationalen Gemeinschaft sollten Optionen, Argumente sowie der Name deiner Erweiterung auf Englisch verfasst werden.*

<p align="center"><img src="example-screenshot.png?raw=true" alt="Screenshot"></p>

## So wird diese Erweiterung installiert

1. [Datenstrom Yellow herunterladen und installieren](https://github.com/datenstrom/yellow/).
2. [Erweiterung herunterladen](https://github.com/schulle4u/yellow-extension-example/archive/master.zip). Falls du Safari verwendest, klicke die Datei mit rechts an und wähle 'Datei speichern unter'.
3. Kopiere `master.zip` in dein `system/extensions`-Verzeichnis.

Zum Deinstallieren lösche einfach die [Erweiterungsdateien](extension.ini).

**TODO:** *Ändere den zweiten Link, sodass er auf dein eigenes Repository verweist.*

## So wird etwas gemacht

Erstelle einen `[example]`-Shortcut. 

Die folgenden Argumente sind verfügbar, mit Ausnahme des ersten Arguments sind alle Angaben optional:

`Something` = Beispielargument, wird in dieser Erweiterung nicht verwendet    
`Style` = Beispiel-Stil, wird in dieser Erweiterung nicht verwendet

**TODO:** *Ändere die Überschrift entsprechend deiner Erweiterung. Beschreibe, was ein Benutzer damit tun kann. Meistens genügt hierfür eine einzige Sektion, lediglich bei Umfangreichen Erweiterungen empfiehlt sich die Aufteilung in mehrere Sektionen. Erwähne auch die von dir verwendeten Drittanbieter-Dienste und Bibliotheken.*

## Einstellungen

Die folgenden Einstellungen können in der Datei `system/settings/system.ini` vorgenommen werden:

`ExampleSomething` = Beispieleinstellung, wird in dieser Erweiterung nicht verwendet  
`ExampleStyle` = Beispiel-Stil, wird in dieser Erweiterung nicht verwendet  

**TODO:** *Zeige, wie sich deine Erweiterung konfigurieren lässt. Beschreibe alle Einstellungen und Dateien, in denen der Benutzer Anpassungen vornehmen kann.*

## Beispiele

Einbettung eines Beispieltextes:

    [example]
    [example abc]
    [example abc 123]

**TODO:** *Zeige, wie man deine Erweiterung verwenden kann. Notiere einige fertige Beispiele zum Kopieren und Einfügen.*

## Entwickler

Beispielname.

**TODO:** *Gib deinen Namen an. Wann immer möglich, erwähne auch andere Entwickler, wenn du Code von ihnen nutzt. Teste danach alles im [Entwickler-Kit](https://github.com/datenstrom/yellow-developers).*