+++
date = "2024-07-21"
author= "Li"
draft = false
title = 'Server'
summary = "Ein Server ist ein Computer oder ein System, das Ressourcen, Daten, Dienste oder Programme für andere Computer, sogenannte Clients, bereitstellt."
tags = ["Server", "Web server", "HTTP Web Server", "Datenbank server", "Datei Server", " System", "Linux", "Windows", " Verwaltung eines Servers", " GUI", " Powershell", "CMD"]
+++

#### Server

Ein Server ist ein Computer oder ein System, das Ressourcen, Daten, Dienste oder Programme für andere Computer, sogenannte Clients, bereitstellt. Es gibt verschiedene Arten von Servern, wie:
Webserver (z. B. Apache, Nginx): Liefert Webseiten an Benutzer.: nginx ("engine x") is an HTTP web server, reverse proxy, content cache, load balancer, TCP/UDP proxy server, and mail proxy server.

Datenbankserver (z. B. MySQL, PostgreSQL): Verwalten und speichern Daten.

Dateiserver: Ermöglichen den Zugriff auf Dateien innerhalb eines Netzwerks.

##### Verwaltung eines Servers:

Server-Dienste starten, stoppen und neu starten:
In Linux:
bash
sudo systemctl start dienstname   # Starten
sudo systemctl stop dienstname    # Stoppen
sudo systemctl restart dienstname # Neustarten

In Windows, die Verwaltung von Serverdiensten kann ähnlich wie bei Linux über Befehle oder grafische Schnittstellen erfolgen. Statt der Linux-Kommandos wie systemctl verwendet Windows den Dienstemanager oder die PowerShell.

Über die grafische Oberfläche (GUI):
Dienste-Manager öffnen:
Drücke Windows + R, um den Dialog "Ausführen" zu öffnen.
Gib services.msc ein und drücke Enter.
In der Dienste-Ansicht siehst du eine Liste aller Dienste. Hier kannst du:
Dienste starten, stoppen oder neu starten.
Rechtsklick auf den gewünschten Dienst und wähle die entsprechende Option.

oder 
Über die PowerShell oder Eingabeaufforderung (CMD).