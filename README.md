# Bresser_4CAST-for-VIS2

![status](https://img.shields.io/badge/status-alpha-orange)
![version](https://img.shields.io/badge/version-0.1-orange)
![license](https://img.shields.io/badge/license-Public%20Domain-lightgrey)
![GitHub all releases](https://img.shields.io/github/downloads/quinti123/Bresser_4CAST-for-VIS2/total)

![Station](Bresser_readme1.png)

Dieses VIS2 view für iobroker simuliert eine Bresser 4Cast MD Wetterstation (Art.Nr. 7003800).
Sie blendet Daten aus dem iobroker über eine Grafikdatei der Wetterstation Bresser_4CAST ein.
Die Daten werden aus dem Objekttree des Projektes WLAN Wetterstation übernommen.

Benötigt werden folgende Adapter:
  - Vis2 (sollte aber auch noch mit Vis1 funktionieren)
  - materialdesign Widgets
  - timeandweather Widgets
  
  ### Filter objects
The adapter updates as much information from your UniFi controller as possible, but offers the possibility to limit the updated information.

It is possible to disable the update of selected information or filter specific objects of that information.

| Information | Objects filterable by                   |
|-------------|-----------------------------------------|
| Clients     | Name, Hostname, IP address, MAC address |
| Devices     | Name, IP address, MAC address           |
| WiFis       | Name                                    |
| Networks    | Name                                    |
| Health      | Subsystem                               |
  
  
