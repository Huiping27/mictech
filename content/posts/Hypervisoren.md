+++
date = "2023-07-27"
author= "admin"
draft = false
title = 'Hypervisoren, VM Monitor'
summary = "Ein Hypervisor (auch als Virtual Machine Monitor, VMM bekannt) ist eine Art Software, Firmware oder Hardware, die es ermöglicht, virtuelle Maschinen (VMs) zu erstellen und auszuführen. Der Hypervisor erlaubt es mehreren Betriebssystemen, die Hardware-Ressourcen eines physischen Computers zu teilen, wobei jedes Betriebssystem als isolierte VM ausgeführt wird."

tags = ["Hypervisoren","Isolierung", "Linux", "Windows", "Cloudcomputing", "AWS", "Azure", "Hardware", "Isolierte Umgebung", "Backup", " CPU", "VM", "VMM"]
+++

#### Hypervisoren sind die Kerntechnologie hinter virtuellen Maschinen und ermöglichen es, mehrere Betriebssysteme auf gemeinsam genutzter Hardware auszuführen.

Ein Hypervisor (auch als Virtual Machine Monitor, VMM bekannt) ist eine Art Software, Firmware oder Hardware, die es ermöglicht, virtuelle Maschinen (VMs) zu erstellen und auszuführen. Der Hypervisor erlaubt es mehreren Betriebssystemen, die Hardware-Ressourcen eines physischen Computers zu teilen, wobei jedes Betriebssystem als isolierte VM ausgeführt wird.

##### Es gibt zwei Haupttypen von Hypervisoren:

Typ-1-Hypervisoren (Bare Metal):

Diese werden direkt auf der physischen Hardware des Hosts installiert.
Beispiele:
VMware ESXi
Microsoft Hyper-V
Xen
KVM (Kernel-based Virtual Machine)

Typ-2-Hypervisoren (Hosted):

Diese werden auf einem bereits vorhandenen Betriebssystem installiert, ähnlich wie eine Anwendung.
Das Host-Betriebssystem stellt die notwendigen Ressourcen bereit, um VMs auszuführen.
Beispiele:
VMware Workstation
Oracle VirtualBox
Parallels Desktop

##### Hauptfunktionen von Hypervisoren:

Ressourcen-Isolation: Jede VM arbeitet unabhängig mit ihrem eigenen Betriebssystem, eigenem Arbeitsspeicher, CPU und Speicherplatz, obwohl sie die gleiche physische Hardware nutzen.
Effiziente Ressourcenzuteilung: Hypervisoren verwalten die Hardware-Ressourcen effizient, sodass jede VM die benötigten Ressourcen erhält, ohne andere VMs zu beeinträchtigen.
Flexibilität: Hypervisoren bieten Flexibilität, verschiedene Betriebssysteme (Linux, Windows usw.) auf derselben physischen Hardware auszuführen. Dies ist besonders nützlich in Cloud-Umgebungen und bei der Serverkonsolidierung.

##### Häufige Anwendungsfälle:

1. Cloud-Computing: Hypervisoren sind entscheidend für Plattformen wie AWS, Azure und Google Cloud. Sie ermöglichen Multi-Tenant-Umgebungen, in denen mehrere Kunden VMs auf derselben Hardware ausführen können.
2. Entwicklung und Testen: Entwickler nutzen Hypervisoren, um isolierte Umgebungen zu schaffen, in denen sie Anwendungen auf verschiedenen Betriebssystemen testen können, ohne mehrere physische Maschinen zu benötigen.
3. Disaster Recovery: Durch die Replikation von VMs unterstützen Hypervisoren Backup- und Wiederherstellungsstrategien.






