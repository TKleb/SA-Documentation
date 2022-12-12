Meeting Minutes 27.10

Start 15:10
Ende 16:36

**Deliverables**
Advisor:
- Hacking Lab CD Packet für IDA
- Intro 2 und 3 ins Hacking Lab

Studenten:
- PoC Server Docker mit serverseitigem builden mit Flag mit Exploit verbunden (mit Server Thematik auseinandersetzen)
    - Schwachstelle im Server
    - Binary downloadbar
    - Lokaler Exploit Netzwerkfähig machen
- Verschiedene Compiler mit public Code (pro Code eigenes Flag)

## Präsentation
    - Decisions from Sprint Meeting
    - Neues Mindmap (OK)
    - GANTT Chart: OK
    - Lab Intro 2 (Einzelschritt)
    - Lab Intro 3 (Einzelschritt)

**Rückmeldung für Labs:**
Ideal
Sollte schnell ins hacking lab

**Server Lab (S6 Overlay)**
s6 overlay: https://github.com/just-containers/s6-overlay
flag-deploy-scripts: Umgebungsvariabeln oder File (Flag verteilen)
etc/services.d/server/run wird immer ausgeführt
etc/services.d/unitd: kleiner Webserver wenn gebraucht

Github.com Hacking Lab Repo --> Neue Docker (Alpine Base)

**Windows:**
PS Files

**chocolatey / winget**
Packet Manager für Windows
Wenn nicht vorhanden dann "manuell" per ZIP hinzufügbar


** Next Steps: **
- Serverseitig Lab (siehe Deliverables)

**Decisions:**
Windows: Bootstrap script für windows (chocolatey)
Linux: Hacking lab cd packet für ida (Auftrag Ivan)
Choco / Winlab auch am Schluss definieren
Wenn Alpine dann Docker
Sonst LiveCD / Windows VM
Wenn notwendig können wir Quellcode von Beispielaufgaben anfordern / Musterlösungen
