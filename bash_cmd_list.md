# System update
- sudo apt update && sudo apt upgrade
- sudo apt full-upgrade
- sudo apt dist-upgrade
- sudo apt autoremove
- sudo apt clean  
- sudo apt-get remove (Paket)
- sudo apt-get purge (Paket) Paket deinstallieren inkl.
- apt-cache search Suchbegriff

- sudo !! [more parameters]



- Archiv erstellen: tar cfv Archivname Dateiname
- ssh username:ip
- Verzeichnisgröße anzeigen: du -sh Verzeichnis
- symbol. Verknüpfung erstellen: ln -s Quelle Ziel
- Datei suchen: "find Verzeichnis -iname Name" oder "(mit Index) locate Name"
- Programm beenden: killall -s 9
- shotdown -h (Time) / reboot

Arbeitsspeicher­Ausnutzung                free -m

Prozessliste                             ps aux

Prozessorauslastung                      top

Systeminformationen                      uname -a
Eingehängte Dateisysteme                 mount -l | grep /dev/sd

Partitionen / Speicherplatz              df -h

Partitionstabelle anzeigen*              parted /dev/sda print
Informationen zur Hardware               lshw

PCI­Geräte                                lspci

… Grafikkarte                            lspci | grep VGA

… Soundkarte                             lspci | grep -i audio  und
                                         cat /proc/asound/cards

USB­Geräte                                lsusb

Netzwerk­/WLAN­Karte                       ifconfig / iwconfig
