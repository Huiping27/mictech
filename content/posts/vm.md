+++
date = "2023-09-20"
author= "Li"
draft = false
title = 'VM'
summary = "VM steht für Virtual Machine (virtuelle Maschine). Eine virtuelle Maschine ist ein Software-Emulator, der die Funktionalität eines physischen Computers nachbildet."
tags = ["Isolation", "Cloud Computing", "Isolierung", "physischen Harware", "virtuell", "Flexibilität", "Hypervisor", "virtual box", "VMware","Hyper-V","VM"]
+++

Mithilfe von Virtualisierungstechnologien ermöglicht es eine VM, mehrere Betriebssysteme oder Anwendungen unabhängig auf derselben physischen Hardware auszuführen. Die VM funktioniert wie ein eigenständiger Computer mit CPU, Speicher, Festplatte und Netzwerkverbindungen, allerdings alles virtuell.

#### Hauptmerkmale einer VM

1. Isolation: Jede VM ist von anderen VMs und dem Host-System isoliert. 

2. Ressourcenteilung: Die physische Hardware (CPU, Speicher, Netzwerk) kann von mehreren VMs gleichzeitig genutzt werden, was zu einer effizienteren Ressourcenausnutzung führt.

3. Flexibilität und Skalierbarkeit: VMs können einfach erstellt, gelöscht oder kopiert werden. 

4. Hypervisor: Die Software, die VMs verwaltet und ihre Ausführung steuert, wird als Hypervisor bezeichnet. Es gibt zwei Arten:

Type-1-Hypervisor (Bare Metal): Läuft direkt auf der Hardware, ohne ein darunterliegendes Betriebssystem (z. B. VMware ESXi, Microsoft Hyper-V).
Type-2-Hypervisor (Hosted): Läuft auf einem Host-Betriebssystem und stellt dort VMs bereit (z. B. VirtualBox, VMware Workstation).
