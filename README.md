NWTK-Vagrant
============

AUTOMATISCHES VM PROVISIONING

Vagrant ist ein System, mit dem automatisch virtuelle Maschinen (für VirtualBox, VMWare, aber auch Cloud-Systeme wie AWS) erstellt und konfiguriert werden können.

Erstellen Sie eine Vagrant-Konfigurationsdatei, die ein Basis-System installiert (precise32 oder precise64). Konfigurieren Sie Vagrant so, dass auf diesem System ein Standard-Webserver mit Wordpress (d.h. apache, PHP, MySQL) betrieben wird. Dieser Webserver soll auch von ausserhalb ihres Gastsystems erreichbar sein, daher muss bei Vagrant auch eine Port-Weiterleitung konfiguriert werden.

Arbeiten Sie in 2-Personen-Teams zusammen, wobei die Provisionierung des Systems sowohl mit Chef als auch mit Puppet durchgeführt wird. Dokumentieren Sie die Übungsdurchführung.
