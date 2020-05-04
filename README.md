# M300-Services
 ## Modul 300 - Plattform übergreifende Dienste

## Einführung
In diesem Modul haben wir gelernt, wie man automatisiert virtuelle Maschinen aufsetzt und diese verwaltet. Ausserdem haben wir alle unsere Dateien/Erkenntnisse auf GitHub hochgeladen. Hier haben wir mit GitBash, Vagrant und Visual Studio gearbeitet.

## Installationen
Als erstes habe ich einen GitHub Account erstellt und mir das Repository von der Lehrperson angesehen (wo auch übrigens alle Anleitungen sind).
Das Repository vom Modul habe ich lokal auf meinem Laptop heruntergeladen.
Ich habe folgende Programme installiert: GitBash, Vagrant und Visual Studio Code
Ausserdem habe ich noch ein Ubuntu Image heruntergeladen um dieses in der virtuellen Umgebung einzusetzen.


## GitBash
GitBash benutzen wir, um auf dem eigenen GitHub Verzeichnis Änderungen vorzunehmen. Hierbei habe ich der Anleitung gefolgt, welche uns von der Lehrperson gegeben wurde.
Mit GitBash haben wir auch die Vagrant Files erstellt und laufen gelassen.

## Visual Studio Code
Mit diesem Programm habe ich mein Vagrant File entsprechend konfiguriert, sodass automatisch Apache2 installiert wird.
Auch die Firewall & Proxy Regeln/Konfigurationen wurden hier automatisiert. 
Die einzelnen Commands für die Automatisierung wurden im Verlauf der Arbeiten hinzugefügt.

## Vagrant File
Das Vagrant File ist der Hauptkern der Automatisierung von Virtuellen Maschinen.
Hier wird alles definiert, was beim aufstarten (vagrant up) installiert und eingestellt wird.

Am besten ist es, wenn man sich Schritt für Schritt durcharbeitet und die einzelnen Konfigurationen testet.

WICHTIG: Ein Backup vom Vagrant File machen, weil bei Änderungen Fehler vorkommen können.

 # Docker
 
 ## Vorwissen
 Docker ist eine Containervirtualisierungssoftware welche erlaubt Boxen zu erstellen um OS getrennt voneinander laufen zu lassen.
 
 ## Erlerntes Wissen
 
  Die Docker-Technologie verwendet den Linux Kernel und seine Funktionen wie Cgroups und namespaces, um Prozesse zu isolieren, dadurch     ebendiese abgesondert voneinander ausgeführt werden können. Diese Unabhängigkeit ist der Vorsatz der Container – die Fähigkeit, eine     Anzahl von Prozesse und Applikationen alleinig voneinander betreiben zu können. So wird Ihre Infrastruktur besser genutzt und           zeitgleich die Gewissheit bewahrt, die sich aus der Arbeit mit einzelnen Systemen ergibt.

  Containertools, inbegriffen Docker, wirken mit einem Image-basierten Bereitstellungsmodell. Das macht es bequemer, eine Anwendung oder   ein Paket von Services mit all deren Abhängigkeiten in vielerlei Umgebungen zusammen zu nutzen. Docker von selbst weiterhin die         Anlieferung der Application (oder Kombinationen von Prozessen, die eine Applikation darstellen) im Zuge jener Container-Umgebung.

  Diese Tools errichten auf Linux-Containern auf – was Docker benutzerfreundlich und einzigartig macht – und geben den Benutzern auf       diese Weise zu keinem Zeitpunkt dagewesenen Zugriff auf Applikationen. Sie realisieren eine klar schnellere Anlieferung und             Überprüfung von Varianten ebenso deren Verbreitung.
