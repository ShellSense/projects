---
title: "Server_Terminal_FullSetup"
author: "ShellSense"
date: "26.08.2023"
theme:
  codeBlock:
    background: "brightBlack"
    foreground: "yellow"
  emph:
    foreground: "blue"
  strong:
    foreground: "red"
  title:
    foreground: "green"
wrap: true
incrementalLists: true
transitions: true
---

# **Terminal Workflow**: 
## Vollausgestattetes Arbeitsumfeld auf dem Ubuntu Server 20.04 LTS

---
# Inhaltsverzeichnis

## 1.0 Vorbereitung
  * 1.1 Einleitung
  * 1.2 Voraussetzungen
  * 1.3 Installation
## 2.0 Durchführung
  * 2.1 Konfiguration
  * 2.2 Anwendung
### 3.0 Optimierung (Teaser)
  * 3.1 Hardening
  * 3.2 Fehlerbehebungen
  * 3.3 Automatisierung
### 4.0 Zwischenstand
  * 4.1 Weiterführende Ressourcen
  * 4.2 Fazit/Zusammenfassung
## 5.0 Optimierung (Vertiefung)
  * 5.1 Hardening
  * 5.2 Fehlerbehebungen
  * 5.3 Automatisierung
## 6.0 Abschluss
  * 6.1 Weiterführende Ressourcen
  * 6.2 Fazit/Zusammenfassung
  * 
---

# 1.0 Vorbereitung

---

# 1.1 | Vorbereitung | Einleitung

- *Was ist die Shell?*
- *Grundlegende Befehle und ihre Anwendung*


> "In der Einfachheit liegt die wahre Komplexität."
> - Albert Einstein


---

# 1.2 | Vorbereitung | Voraussetzungen


* Auswahl des richtigen Systems: **Ubuntu Server 20.04 LTS**
  
* Erste Schritte nach der Installation

---

# 1.3 | Vorbereitung | Installation

Live-Demo einiger Basisbefehle und -funktionen.

Folge ShellSense auf:
- [](https://www.twitch.tv/ShellSense)
- [](https://www.youtube.com/@ShellSense)
- [](https://odysee.com/@ShellSense)
- [](https://github.com/ShellSense)

---

# 2.0 Durchführung

---

# 2.1 | Durchführung | Konfiguration

Einblick in einen typischen Workflow eines Terminal-Nutzers.

- Morgenroutine: E-Mails, Kalender, Aufgaben
- Arbeit: Scripting, Datenmanagement, Kommunikation
- Abendroutine: Updates, Backups, Abschlussarbeiten

---

# 2.2 | Durchführung | Anwendung

## Morgen: Der produktive Start des Tages

- **E-Mails abrufen**: Verwendung von Mutt oder einer anderen Terminal-E-Mail-Anwendung
- **Kalenderüberprüfung**: Terminal-basierte Kalender-Apps wie `calcurse`
- **To-Do-Liste**: `taskwarrior` für die Tagesplanung

---

# Praxis

Live-Demo der Arbeit mit den Terminal-Tools.

Folge ShellSense auf:
- [Twitch](https://www.twitch.tv/ShellSense)
- [YouTube](https://www.youtube.com/@ShellSense)
- [Odysee](https://odysee.com/@ShellSense)
- [GitHub](https://github.com/ShellSense)


---

# 3.0 Optimierung (Teaser: Backup)


## 3.1 | Optimierung | Hardening
## 3.2 | Optimierung | Fehlerbehebungen
## 3.3 | Optimierung | Automatisierung
---

# 4.0 Zwischenstand

---

# 4.1 Zwischenstand | Fazit

Was haben wir heute gelernt?
- Wie komme ich zu diesen Informationen?
  * apropos `stichwort`
  * Online-Suche
  * Tutorials
- Wie lerne ich Befehlen / Tools kennen?
  * manpages
  * Projekte

---

4.2 Zwischenstand | weiterführende Ressourcen

- **Allgemeine Ressourcen und Tutorials**
  - [DigitalOcean's Community Tutorials](https://www.digitalocean.com/community/tutorials)
  - [Linuxize Tutorials](https://linuxize.com/)
  - [Ubuntu Server Guide](https://ubuntu.com/server/docs)

- **Community-Unterstützung und Foren**
  - [Stack Overflow](https://stackoverflow.com/)
  - [Ubuntu Forums](https://ubuntuforums.org/)
  
- **Online-Kurse und Bildungsplattformen**
  - [Linux Academy](https://linuxacademy.com/)
  - [Udemy Linux Kurse](https://www.udemy.com/courses/search/?q=linux)
  
- **Bücher und Literatur**
  - [Linux Command Line and Shell Scripting Bible](https://www.amazon.com/Linux-Command-Shell-Scripting-Bible/dp/111898384X)
  - [How Linux Works](https://www.amazon.com/How-Linux-Works-2nd-Superuser/dp/1593275676)

- **Werkzeuge und Dokumentation**
  - [Manpages Ubuntu](https://manpages.ubuntu.com/)

---

# **Bascis: Fragen & Antworten**

Jetzt ist die Zeit für Fragen aus dem Chat!

Folge ShellSense auf:
- [Twitch](https://www.twitch.tv/ShellSense)
- [YouTube](https://www.youtube.com/@ShellSense)
- [Odysee](https://odysee.com/@ShellSense)
- [GitHub](https://github.com/ShellSense)

---

# 5.0 | Optimierung

---

# 5.0 | Optimierung | Hardening

### **Benutzersicherheit**
- Erstellung und Verwaltung von Benutzerkonten.
- Sicherstellen, dass der Root-Zugang minimiert und `sudo` verwendet wird.

### **Firewall-Management mit `ufw`**
- Aktivieren und Konfigurieren der Firewall.
- Einstellen von Zugriffsregeln, z.B. für SSH.

### **Systemüberwachung**
- Einsatz von `auditd` zur Protokollierung von Systemaktivitäten.
- Anzeigen und Filtern von Systemlogs mit `journalctl`.
- Überwachung spezifischer Dienste und Ereignisse.

---

# 5.0 | Optimierung | Fehlerbehebung

### **Backup und Systemwiederherstellung**
- Erstellen eines Skripts zur Sicherung wichtiger Dateien mit `rsync`.
- Verwendung von Snapshots zur Datenwiederherstellung.

### **Log-Dateien**
- Verständnis und Überwachung von Systemlogs.
- Analyse kritischer Ereignisse und Vorfälle.

### **Prozessmanagement**
- Troubleshooting mit Tools wie `ps`, `top`, `kill` etc.
- Überwachung und Steuerung aktiver Systemprozesse.

---

# 5.0 | Optimierung | Automatisierung

### **Cron Jobs und Shell-Skripte**
- Planung regelmäßiger Aufgaben mit `cron`.
- Erstellung von Skripten zur Automatisierung komplexer Workflows.

### **Infrastructure as Code mit `Ansible`**
- Einrichten eines Ansible-Playbooks.
- Automatisches Verteilen und Ausführen von Skripten und Befehlen auf Remote-Servern.

---

# Praxis

Live-Demo von Optimierungstechniken und -Tools.

Folge ShellSense auf:
- [Twitch](https://www.twitch.tv/ShellSense)
- [YouTube](https://www.youtube.com/@ShellSense)
- [Odysee](https://odysee.com/@ShellSense)
- [GitHub](https://github.com/ShellSense)

---

# **Bascis: Fragen & Antworten**

Jetzt ist die Zeit für Fragen aus dem Chat!


# Danke für's Zuschauen!

Folge ShellSense auf:
- [Twitch](https://www.twitch.tv/ShellSense)
- [YouTube](https://www.youtube.com/@ShellSense)
- [Odysee](https://odysee.com/@ShellSense)
- [GitHub](https://github.com/ShellSense)

