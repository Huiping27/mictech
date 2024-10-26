+++
date = "2024-09-28"
author= "Li"
draft = false
title = 'Access Control Lists ACLs'
summary = " Access Control Lists (ACLs) sind Datenstrukturen, die festlegen, welche Benutzer oder Systeme Zugriff auf bestimmte Ressourcen haben und welche Arten von Zugriff ihnen gestattet sind. Sie ermöglichen eine detaillierte Kontrolle über den Zugriff und die Berechtigungen in einem IT-System."
tags = ["ACL", "Ressource", "Berechtigung", "Zugriffs-AcL", "Filter-AcL", "Sicherheit", "Flexiblität", "Komplexität", "Fein granulare Kontrolle","Performance"]
+++

#### Aufbau einer ACL

##### Was sind Access Control Lists (ACLs)?
Access Control Lists (ACLs) sind Datenstrukturen, die festlegen, welche Benutzer oder Systeme Zugriff auf bestimmte Ressourcen haben und welche Arten von Zugriff ihnen gestattet sind. Sie ermöglichen eine detaillierte Kontrolle über den Zugriff und die Berechtigungen in einem IT-System.

##### Aufbau einer ACL

Eine ACL besteht typischerweise aus einer Liste von Einträgen, die aus folgenden Bestandteilen bestehen:

Subjekt: Dies kann ein Benutzer, eine Gruppe von Benutzern oder ein System sein, das auf die Ressource zugreifen möchte.
Ressource: Das Ziel, auf das zugegriffen werden soll (z. B. eine Datei, ein Ordner oder ein Netzwerkdienst).
Berechtigung: Die Art des Zugriffs, der gewährt oder verweigert wird (z. B. Lesen, Schreiben, Ausführen oder Löschen).

##### Typen von ACLs
Zugriffs-Acl (Access Control List): Legt fest, welche Benutzer oder Gruppen Zugriff auf eine Ressource haben und welche Berechtigungen ihnen zugewiesen sind.

Filter-Acl (Filter Access Control List): Wird häufig in Netzwerken verwendet, um den Datenverkehr zu steuern, indem sie festlegt, welche Pakete durch ein Netzwerkgerät (z. B. einen Router) weitergeleitet oder blockiert werden.

##### Funktionsweise
Wenn ein Benutzer versucht, auf eine Ressource zuzugreifen, überprüft das System die zugehörige ACL.
Anhand der Einträge in der ACL wird entschieden, ob der Zugriff gewährt oder verweigert wird.
ACLs können auf verschiedene Ebenen implementiert werden, z. B. auf Dateisystemebene, Netzwerkebene oder in Anwendungen.
